# Scrap & Steel — desktop builds

Public download host for **Scrap & Steel** Windows installs and patch PCKs.

The launcher reads `scrapsteel_version.json` from the website and downloads:

- Full install zip: `scrapsteel_<version>.zip`
- Optional patch: `patch_<version>.pck`

Releases are published with `tools/publish_desktop_build.ps1 -PublishGitHub`.