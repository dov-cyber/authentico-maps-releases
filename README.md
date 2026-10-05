# Authentico Maps Runtime - installers

This repository holds only the installer packages of the Authentico Maps Runtime
WordPress plugin, one GitHub Release per version (`v<version>`), each with
`Authentico-Maps-<version>.zip` and its `.sha256`.

No source code, no map data, no documentation lives here. Releases are published
by the release workflow of the private repository `dov-cyber/authentico-maps` from
a commit on its `main` branch; the installer SHA-256 is recorded there in
`runtime/RELEASE-<version>.json` and must match before a release is published.
The plugin's update check reads the latest release here and refuses a package
whose SHA-256 differs from the published one.

Nothing is committed to this repository by hand.
