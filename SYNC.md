# vectorcraft-web

Standalone static web build of [storytold/vectorcraft](https://github.com/storytold/vectorcraft), the vector illustration app. Serve this
folder's contents from any static host; see HOSTING.md (from upstream) for server settings.

This repo holds only the released web bundle (Apache-2.0, see LICENSE-APACHE). A scheduled GitHub Action
(`.github/workflows/sync.yml`) checks upstream's latest release every 6 hours and, when the version
in `UPSTREAM_VERSION` is behind, replaces the bundle and commits it. Run it by hand from the Actions tab.
