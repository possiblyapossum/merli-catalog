# Merli product catalog

Public Singapore retail-banking product data (card earn rules, deposit rates, mortgages, loans, FX) used by the
Merli app for over-the-air rate updates. The app downloads `catalog.json`, validates it, and uses it only if it
parses and its `version` is newer than the one it has.

This file is generated from the (private) app repository with `tools/publish_catalog.sh`; do not edit it here.

General information only, not financial advice. Rates change; verify with the provider.
