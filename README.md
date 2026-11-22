# rackmere-data

Public, data-only bundle for the "Data Center Siting: Rackmere" apps (no code, no secrets).

- `manifest.json` - layer list with sha256, size, version, as-of date, refresh interval, source, licence and attribution.
- `layers/<id>.json` - one file per layer.
- `datasources.json` - the source registry shown in the app.

Each layer keeps the licence and attribution of its source (see the manifest). Derived values are educational and approximate.
Refreshed weekly by a scheduled job. Maintained by the app publisher.
