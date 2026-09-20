# firelite-cli

Command-line manager for the [FireLite](https://github.com/rizaptk/firelite)
embedded document engine: document CRUD, queries, indexes, watch streams,
and LAN/cloud sync management.

## Compatibility

| firelite-cli | firelite core |
|---|---|
| 0.2.1 | `cloud_sync` branch (pre-crates.io) |

## Build

```sh
cargo build --release
```

The `firelite` dependency tracks the core `cloud_sync` branch until the
first crates.io release, then pins to `version = "0.8"`.
