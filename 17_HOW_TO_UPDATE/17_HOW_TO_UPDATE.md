# How to Update — DITTO

**Project:** `DITTO`
**Category:** FACTORY_MANUFACTURING
**Domain:** factory manufacturing and automation
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
DITTO --version
DITTO check-update
```

### Applying Updates
```bash
pip install --upgrade DITTO
```

### Rolling Back
```bash
pip install DITTO==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
