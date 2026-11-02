# CMAP Speed Dashboard

- Old URL(s):
  - https://products.highstreet.work/cmap/speed_dashboard/
- New URL: https://high-street-consulting.github.io/cmap-speed-dashboard/
- Migrated: 2026-11-02
- Source: IIS wwwroot folder `wwwroot\cmap\speed_dashboard`
- Framework: ArcGIS Experience Builder 1.17, build 12

## Changes from original

- `web.config` dropped (IIS-only MIME/cache/rewrite rules; GitHub Pages does not use it)
- `*.map` source maps dropped (0 files)
- empty `.nojekyll` added (skip the Jekyll build on GitHub Pages)

No application code was changed.
