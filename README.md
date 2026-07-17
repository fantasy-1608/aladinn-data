# Aladinn Data

Public data repository for [Aladinn](https://github.com/fantasy-1608/Aladinn) Chrome Extension.

Contains clinical decision support (CDS) drug interaction databases, remote configuration, and update manifests for OTA delivery.

## Contents

- `cds-data/` — CDS knowledge base (drug interactions, contraindications, lab rules)
- `remote-config.json` — Remote feature flags and kill switch configuration
- `remote-config.sig` — Ed25519 signature for config verification
- `update.json` — Extension version manifest for self-update

## ⚠️ Note

This repository contains **data only** — no source code. The Aladinn extension source code is maintained separately.
