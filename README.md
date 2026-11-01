# Миграция из Shtab.app

Безопасный импорт официальных CSV/XLSX-экспортов Shtab.app в TropaTT

A module for the [TropaTT](https://github.com/Anton-Barinov/TropaTT) self-hosted CRM and work platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Details

| Field | Value |
|---|---|
| Module Code | `crm.shtab-migration` |
| Version | `1.1.0` |
| Category | Migration |
| Core Compatibility | `>=1.0.0` |
| Author | [Anton Barinov](https://github.com/Anton-Barinov) |

## Installation

### Method 1: TropaTT Marketplace (Recommended)

1. In your TropaTT CRM, navigate to **Admin → Modules → Marketplace**.
2. Search for **Миграция из Shtab.app** (`crm.shtab-migration`).
3. Click **Install**.

### Method 2: Manual ZIP Upload

1. Download `crm.shtab-migration-1.1.0.zip` from the [Releases](https://github.com/Anton-Barinov/tropatt-module-shtab-migration/releases) tab.
2. In TropaTT CRM, navigate to **Admin → Modules**.
3. Click **Upload Module** and select the downloaded ZIP file.
4. Activate and configure the module in **Admin → Modules**.

## Repository Layout

- `upload/` — Module source code and assets installed into CRM (`manifest.json`, `api/`, `web/`).
- `LICENSE` — MIT License.
- `SECURITY.md` — Security policy.
