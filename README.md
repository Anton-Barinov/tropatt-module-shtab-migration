# Миграция из Shtab.app

Безопасный импорт официальных CSV/XLSX-экспортов Shtab.app в TropaTT

A module for the [TropaTT](https://github.com/Anton-Barinov/TropaTT) self-hosted CRM and work platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Module info

| Field | Value |
|---|---|
| Module | `crm.shtab-migration` |
| Version | `1.1.0` |
| Category | `migration` |
| Core | `>=1.0.0` |
| Required permissions | project.manage, task.manage, import.manage |
| Author | [Anton Barinov](https://github.com/Anton-Barinov) |

## Installation

1. In TropaTT open **Admin → Modules → Install**.
2. Choose one of:
   - **Install from URL:** `https://github.com/Anton-Barinov/tropatt-module-shtab-migration/releases/download/v1.1.0/crm.shtab-migration-1.1.0.zip`
   - **Upload archive:** download the release `.zip` and upload it manually.
3. Activate the module and configure it in **Admin → Modules**.

> The archive contains the module files at its root (`manifest.json` + `api/` + `web/`).
> For manual install, place the files under `modules/crm.shtab-migration/` of your TropaTT installation.

## Repository layout

- `upload/` — the module itself (what gets installed).
- `LICENSE` — MIT license.
- `SECURITY.md` — how to report vulnerabilities.

## Requirements

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

## License

[MIT](LICENSE) © Anton Barinov
