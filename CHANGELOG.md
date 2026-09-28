# Changelog — `toxi-graphql`

Per-crate history extracted from the monolith changelog
([meshackbahati/toxi](https://github.com/meshackbahati/toxi/blob/main/CHANGELOG.md)),
which remains the full documentation hub.

## 3.1.5

- **toxi-graphql** (`3.1.1`): query execution runs in `spawn_blocking`
  instead of on the async worker, so CPU-bound Juniper execution no longer
  stalls unrelated connections.
