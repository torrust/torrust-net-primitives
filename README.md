# Torrust Net Primitives

[![Testing](https://github.com/torrust/torrust-net-primitives/actions/workflows/testing.yaml/badge.svg)](https://github.com/torrust/torrust-net-primitives/actions/workflows/testing.yaml)

Generic networking primitive types for [Torrust](https://torrust.com/) projects.

This crate provides low-level networking types that are reusable across Torrust projects
without pulling in tracker-specific dependencies.

## Types

- `service_binding::ServiceBinding` — represents a network address binding (protocol + socket address).
- `service_binding::Protocol` — supported network protocols (`UDP`, `HTTP`, `HTTPS`).

## Quick Start

Add this to your `Cargo.toml`:

```toml
[dependencies]
torrust-net-primitives = "0.1.0"
```

## Documentation

[Crate documentation](https://docs.rs/torrust-net-primitives).

## License

The project is licensed under the terms of the [GNU AFFERO GENERAL PUBLIC LICENSE](./LICENSE).
