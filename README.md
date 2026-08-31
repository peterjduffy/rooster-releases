# Rooster releases

Signed, notarised downloads for [Rooster](https://rooster.cam) - local,
transcript-first video editing for Mac.

This repository holds release assets and nothing else. There is no source here;
Rooster's source is private. What each release carries is the disk image the
website links to and the in-app updater fetches, which is the same file either
way.

- **Download the latest version:** <https://rooster.cam/download>
- **Update feed** (read by the app, not by people): <https://rooster.cam/appcast.xml>

Every image is signed with an Apple Developer ID certificate, notarised by
Apple and stapled, so it opens on a Mac that has never run Rooster and on one
with no network. Updates carry an EdDSA signature that the copy you already have
verifies before it installs anything.

Rooster is early software under active development.
