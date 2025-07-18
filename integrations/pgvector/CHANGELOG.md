# Changelog

## [integrations/pgvector-v5.2.0] - 2025-06-26

Note: Version 5.2.0 was released by mistake.
It is functionally identical to version 3.4.1 and does not introduce any new features or changes.

### 🧹 Chores

- Remove black (#1985)


## [integrations/pgvector-v3.4.1] - 2025-06-20

### 🐛 Bug Fixes

- Pgvector - do not pass null `meta` to `Document.from_dict` (#1980)


## [integrations/pgvector-v3.4.0] - 2025-06-10

### 🐛 Bug Fixes

- Fix pgvector types + add py.typed (#1914)

### 🧹 Chores

- Align core-integrations Hatch scripts (#1898)
- Update md files for new hatch scripts (#1911)


## [integrations/pgvector-v3.3.1] - 2025-05-28

### 🌀 Miscellaneous

- Add pins for Pgvector (#1849)

## [integrations/pgvector-v3.3.0] - 2025-05-06

### 🚀 Features

- Pgvector - make error messages more informative (#1684)


## [integrations/pgvector-v3.2.0] - 2025-04-11

### 🚀 Features

- Add halfvec support for storing high-dimensional embeddings in half-precision (#1607)


## [integrations/pgvector-v3.1.0] - 2025-03-20

### 🚀 Features

- Pgvector - async support (+ refactoring) (#1547)


### ⚙️ CI

- Review testing workflows (#1541)

## [integrations/pgvector-v3.0.1] - 2025-03-12


### 🌀 Miscellaneous

- Fix: pgvector - improve `_create_table_if_not_exists` to be used without admin rights (#1490)

## [integrations/pgvector-v3.0.0] - 2025-03-11


### 🧹 Chores

- Remove Python 3.8 support (#1421)
- Use Haystack logging across integrations (#1484)
- Pgvector - pin haystack and remove dataframe checks (#1518)

## [integrations/pgvector-v2.0.0] - 2025-02-13

### 🧹 Chores

- Pgvector - remove support for dataframe (#1370)


## [integrations/pgvector-v1.3.0] - 2025-02-03

### 🚀 Features

- Pgvector - add like and not like filters (#1341)

### 🧹 Chores

- Inherit from `FilterDocumentsTestWithDataframe` in Document Stores (#1290)


## [integrations/pgvector-v1.2.1] - 2025-01-10

### 🐛 Bug Fixes

- PgvectorDocumentStore - use appropriate schema name if dropping index (#1277)


## [integrations/pgvector-v1.2.0] - 2024-11-22

### 🚀 Features

- Add `create_extension` parameter to control vector extension creation (#1213)


## [integrations/pgvector-v1.1.0] - 2024-11-21

### 🚀 Features

- Add filter_policy to pgvector integration (#820)
- Add schema support to pgvector document store. (#1095)
- Pgvector - recreate the connection if it is no longer valid (#1202)

### 🐛 Bug Fixes

- `PgVector` - Fallback to default filter policy when deserializing retrievers without the init parameter (#900)

### 📚 Documentation

- Explain different connection string formats in the docstring (#1132)

### 🧪 Testing

- Do not retry tests in `hatch run test` command (#954)

### ⚙️ CI

- Retry tests to reduce flakyness (#836)
- Adopt uv as installer (#1142)

### 🧹 Chores

- Update ruff invocation to include check parameter (#853)
- PgVector - remove legacy filter support (#1068)
- Update changelog after removing legacy filters (#1083)
- Update ruff linting scripts and settings (#1105)

### 🌀 Miscellaneous

- Ci: install `pytest-rerunfailures` where needed; add retry config to `test-cov` script (#845)
- Chore: Minor retriever pydoc fix (#884)
- Chore: Update pgvector test for the new `apply_filter_policy` usage (#970)
- Chore: pgvector ruff update, don't ruff tests (#984)

## [integrations/pgvector-v0.4.0] - 2024-06-20

### 🚀 Features

- Defer the database connection to when it's needed (#773)
- Add customizable index names for pgvector (#818)

### 🌀 Miscellaneous

- Docs: add missing api references (#728)
- [deepset-ai/haystack-core-integrations#727] (#738)

## [integrations/pgvector-v0.2.0] - 2024-05-08

### 🚀 Features

- `MongoDBAtlasEmbeddingRetriever` (#427)
- Implement keyword retrieval for pgvector integration (#644)

### 🐛 Bug Fixes

- Fix order of API docs (#447)

### 📚 Documentation

- Update category slug (#442)
- Disable-class-def (#556)

### 🌀 Miscellaneous

- Pgvector - review docstrings and API reference (#502)
- Refactor tests (#574)
- Remove references to Python 3.7 (#601)
- Make Document Stores initially skip `SparseEmbedding` (#606)
- Chore: add license classifiers (#680)
- Type hints in pgvector document store updated for 3.8 compability (#704)
- Chore: change the pydoc renderer class (#718)

## [integrations/pgvector-v0.1.0] - 2024-02-14

### 🐛 Bug Fixes

- Pgvector: fix linting (#328)

### 🌀 Miscellaneous

- Pgvector Document Store - minimal implementation (#239)
- Pgvector - filters (#257)
- Pgvector - embedding retrieval (#298)
- Pgvector - Embedding Retriever (#320)
- Pgvector: generate API docs (#325)
- Pgvector: add an example (#334)
- Adopt `Secret` to pgvector (#402)

<!-- generated by git-cliff -->
