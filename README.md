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

---

## Badges

![Build Status](https://img.shields.io/github/actions/workflow/status/jazzu72/Money-Munchkins--OS/flutter.yml?branch=main)
![License](https://img.shields.io/github/license/jazzu72/Money-Munchkins--OS)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![Security Policy](https://img.shields.io/badge/security-policy-blue.svg)

---

## Badges

![Build Status](https://img.shields.io/github/actions/workflow/status/jazzu72/Money-Munchkins--OS/flutter.yml?branch=main)
![License](https://img.shields.io/github/license/jazzu72/Money-Munchkins--OS)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![Security Policy](https://img.shields.io/badge/security-policy-blue.svg)
