# Upstream provenance

- Project: https://github.com/AppFlowy-IO/appflowy-editor
- Source commit: 01eccc6ee36bd07698bd80915289fe7070478cd2
- Hosted snapshot: appflowy_editor 6.1.0-zotpaper.1
- Packaging date: 2026-11-16
- Runtime lib/ and assets/ are byte-identical to the source commit.
- LICENSE retains the upstream AGPL-3.0 / MPL-2.0 dual-license text.
- Local packaging changes are limited to pubspec metadata, development dependency removal, an image compatibility constraint, documentation, publication exclusions and a commit hook.

The published source includes the full covered runtime source and license. Recipients retain the rights granted by the upstream licenses.

## Dependency compatibility

The snapshot constrains image to `>=4.10.2 <4.11.0`, matching the current ZotPaper lockfile. A fresh resolution of image 4.11.0 with archive 4.0.9 fails compilation because ZLibDecoder.decodeLazy is missing. This is a manifest constraint only; upstream runtime source is unchanged.
