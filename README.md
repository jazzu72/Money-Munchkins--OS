# Money Munchkins OS

## Overview
Money Munchkins OS — Flutter-based grant application workflow system integrated with Nia Capital OS via a strict API contract. It provides:
- Evidence management
- Compliance tracking
- Owner approval workflows
- Offline fallback support

## Features
- Grant Command Center
- Application Factory
- Evidence Vault
- Owner Approval Center
- Audit Trail Extension
- Offline Mode

## Integration Contract
The integration layer is defined under `lib/core/integrations/nia/`:
- nia_grant_client.dart
- nia_dtos.dart
- nia_adapter.dart
- nia_connection.dart
- nia_errors.dart
- nia_mock.dart
- nia_contract.dart

## Documentation
See [docs/NIA_INTEGRATION_CONTRACT.md](docs/NIA_INTEGRATION_CONTRACT.md) for the full API contract, DTO schemas, connection states, error handling, offline rules, and owner authority boundaries.

## Getting Started
1. Clone the repository
2. Run `flutter pub get`
3. Use `flutter run` to launch the app

## License
This project is licensed under the MIT License.
