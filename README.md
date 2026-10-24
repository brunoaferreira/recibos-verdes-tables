# Recibos Verdes: rule tables

Year tables (IRS, IVA, retenção, Segurança Social) used by the Recibos Verdes: Simulador app, published with GitHub Pages at
`https://brunoaferreira.github.io/recibos-verdes-tables/tables/`.

The app downloads `tables/manifest.json`, then each newer `<year>.json`, checks its sha256 against the manifest and validates it before use.

This repository is written by CI from the main (private) repository. Do not edit it by hand.
