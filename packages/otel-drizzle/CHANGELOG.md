# @kubiks/otel-drizzle

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
