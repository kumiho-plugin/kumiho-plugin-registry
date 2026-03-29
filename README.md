# kumiho-plugin-registry
Official plugin index for Kumiho.

## Format

- `index.json`: installable plugin catalog
- Each entry uses `kumiho-plugin-sdk/manifest.Manifest` compatible fields
- Optional visual metadata such as `icons.svg` / `icons.png` can be included for plugin card UIs

## Current entries

- `kumiho-plugin-metadata-kitsu`

## Notes

- `kumiho-plugin-metadata-kitsu` is currently registered as a `service` runtime plugin
- Release artifact metadata should be filled after the container image or deployable artifact is published
