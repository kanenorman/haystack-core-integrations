# Changelog

## [integrations/astra-v2.1.0] - 2025-06-27

### 🐛 Bug Fixes

- Astra - fix types + add py.typed (#2011)

### 🧹 Chores

- Align core-integrations Hatch scripts (#1898)
- Fix linting for ruff 0.12.0 (#1969)
- Remove black (#1985)


## [integrations/astra-v2.0.1] - 2025-04-03


### ⚙️ CI

- Review testing workflows (#1541)

### 🌀 Miscellaneous

- Fix: astra-haystack remove init files to make them namespace packages (#1595)

## [integrations/astra-v2.0.0] - 2025-03-11

### 🧹 Chores

- Use Haystack logging across integrations (#1484)
- Astra - pin `haystack-ai>=2.11.0` and remove dataframe checks (#1492)


## [integrations/astra-v1.0.0] - 2025-02-17

### 🧹 Chores

- Inherit from `FilterDocumentsTestWithDataframe` in Document Stores (#1290)
- [**breaking**] Astra - remove dataframe support (#1376)

## [integrations/astra-v0.1.2] - 2024-11-25


## [integrations/astra-v0.9.4] - 2024-11-25

### 🌀 Miscellaneous

- Fix: Astra - fix embedding retrieval top-k limit (#1210)

## [integrations/astra-v0.10.0] - 2024-10-22

### 🚀 Features

- Update astradb integration for latest client library (#1145)

### ⚙️ CI

- Adopt uv as installer (#1142)

### 🧹 Chores

- Update ruff linting scripts and settings (#1105)

### 🌀 Miscellaneous

- Fix: #1047 Remove count_documents from delete_documents (#1049)

## [integrations/astra-v0.9.3] - 2024-09-12

### 🐛 Bug Fixes

- Astra DB, improved warnings and guidance about indexing-related mismatches (#932)
- AstraDocumentStore filter by id (#1053)

### 🧪 Testing

- Do not retry tests in `hatch run test` command (#954)


## [integrations/astra-v0.9.2] - 2024-07-22

### 🌀 Miscellaneous

- Normalize logical filter conditions (#874)

## [integrations/astra-v0.9.1] - 2024-07-15

### 🚀 Features

- Defer the database connection to when it's needed (#769)
- Add filter_policy to astra integration (#827)

### 🐛 Bug Fixes

- Fix astra nightly
- Fix typing checks
- `Astra` - Fallback to default filter policy when deserializing retrievers without the init parameter (#896)

### ⚙️ CI

- Retry tests to reduce flakyness (#836)

### 🌀 Miscellaneous

- Ci: install `pytest-rerunfailures` where needed; add retry config to `test-cov` script (#845)
- Fix: Incorrect astra not equal operator (#868)
- Chore: Minor retriever pydoc fix (#884)

## [integrations/astra-v0.7.0] - 2024-05-15

### 🐛 Bug Fixes

- Make unit tests pass (#720)

### 🌀 Miscellaneous

- Chore: change the pydoc renderer class (#718)
- [Astra DB] Explicit projection when reading from Astra DB (#733)

## [integrations/astra-v0.6.0] - 2024-04-24

### 🐛 Bug Fixes

- Pass namespace in the docstore init (#683)

### 🌀 Miscellaneous

- Chore: add license classifiers (#680)
- Bug fix for document_store.py (#618)

## [integrations/astra-v0.5.1] - 2024-04-09

### 🐛 Bug Fixes

- Fix `haystack-ai` pins (#649)

### 🌀 Miscellaneous

- Remove references to Python 3.7 (#601)
- Make Document Stores initially skip `SparseEmbedding` (#606)

## [integrations/astra-v0.5.0] - 2024-03-18

### 📚 Documentation

- Review `integrations.astra` (#498)
- Small consistency improvements (#536)
- Disable-class-def (#556)

### 🌀 Miscellaneous

- Fix example code for Astra DB pipeline (#481)
- Make tests show coverage (#566)
- Astra DB: Add integration usage tracking (#568)

## [integrations/astra-v0.4.2] - 2024-02-21

### 🌀 Miscellaneous

- Proper name for the sort param (#454)

## [integrations/astra-v0.4.1] - 2024-02-20

### 🐛 Bug Fixes

- Fix order of API docs (#447)
- Astra: fix integration tests (#450)

## [integrations/astra-v0.4.0] - 2024-02-20

### 📚 Documentation

- Update category slug (#442)

### 🌀 Miscellaneous

- Update the Astra DB Integration to fit latest conventions (#428)

## [integrations/astra-v0.3.0] - 2024-02-15

### 🌀 Miscellaneous

- Model_name_or_path > model (#418)
- [Astra] Change authentication parameters (#423)

## [integrations/astra-v0.2.0] - 2024-02-13

### 🌀 Miscellaneous

- [**breaking**] Change import paths (#277)
- Generate api docs (#327)
- Astra: rename retriever (#399)

## [integrations/astra-v0.1.1] - 2024-01-18

### 🌀 Miscellaneous

- Update the import paths for beta5 (#235)

## [integrations/astra-v0.1.0] - 2024-01-11

### 🌀 Miscellaneous

- Adding AstraDB as a DocumentStore (#144)

<!-- generated by git-cliff -->
