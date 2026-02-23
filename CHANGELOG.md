# @opensourceframework/next-compose-plugins

## 2.3.1

### Patch Changes

- e700978: Fixed critical babel-traverse vulnerability by removing legacy babel-core@6.26.3 dependency. Upgraded jest from 24.7.1 to 29.7.0 to address form-data vulnerability.
  - Removed babel-core@6.26.3 (had critical babel-traverse vulnerability GHSA-67hx-6x53-jw92)
  - Upgraded jest from 24.7.1 to 29.7.0
  - All 27 tests pass with 98.98% line coverage

## 2.3.0

### Minor Changes

- 35fd460: Initial fork from cyrilwanner/next-compose-plugins with Next.js 15+ compatibility
