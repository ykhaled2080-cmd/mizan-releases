# MIZAN Releases

Portable Windows releases for MIZAN.

Each stable release provides:

- `Mizan-<version>-portable.zip` - the complete portable application folder.
- `mizan-update.json` - signed update metadata used by the in-app updater.

MIZAN data (offers, presets, preferences) is stored separately under the local user profile and is preserved across updates.

The application is distributed as a portable folder; no Setup installer is required. The updater downloads, verifies and applies releases from this repository.