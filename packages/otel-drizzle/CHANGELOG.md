# @kubiks/otel-drizzle

## 2.0.2

### Patch Changes

- [`8501cf3`](https://github.com/kubiks-inc/otel/commit/8501cf3f00a1b4da021a907fcf6924dfe9ae508a) Thanks [@alex-holovach](https://github.com/alex-holovach)! - update README

## 2.0.1

### Patch Changes

- [`8c1f41e`](https://github.com/kubiks-inc/otel/commit/8c1f41eeb253a746c0b913b9a34d0af888e60fee) Thanks [@alex-holovach](https://github.com/alex-holovach)! - update repo URL

- [`b385007`](https://github.com/kubiks-inc/otel/commit/b385007e44b410a2ef97aeb8bcc1667233031ed7) Thanks [@alex-holovach](https://github.com/alex-holovach)! - update package.json

## 2.0.0

### Major Changes

- [`7abe73d`](https://github.com/kubiks-inc/otel/commit/7abe73d58ed133fae975684e3493ea83218dde97) Thanks [@alex-holovach](https://github.com/alex-holovach)! - Initial release of @kubiks/otel-drizzle - OpenTelemetry instrumentation for Drizzle ORM

  - Automatic span creation for all database queries
  - Support for PostgreSQL, MySQL, and SQLite
  - Configurable query text capture and truncation
  - Full OpenTelemetry semantic conventions support
  - Zero-configuration setup with one line of code

## 1.0.0

### Major Changes

- Initial release of Drizzle ORM instrumentation package
- Automatic tracing for all Drizzle database queries
- Support for PostgreSQL, MySQL, and SQLite
- Configurable query text capture with sanitization
- Full OpenTelemetry semantic conventions compliance
- Comprehensive test coverage

### Features

- Network peer attributes (`net.peer.name` and `net.peer.port`) for better observability
- Configurable database connection information in spans
- Proper span status codes (OK/ERROR) following OpenTelemetry standards
- Exception recording with full stack traces
