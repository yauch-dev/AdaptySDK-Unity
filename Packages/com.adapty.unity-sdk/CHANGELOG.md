# Changelog
All notable changes to this package will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.17.0] - 2026-07-02

### Added

- `AdaptyProfile.AppliedAttributionSources` — attribution sources applied to the profile (e.g. Apple Search Ads), available for segmentation.
- `AdaptyUIUserAction.OpenIn` — for `OpenUrl` actions, indicates whether the link should open in an in-app or external browser.

### Changed

- Migrated the SDK to a Unity Package Manager layout; install via Git URL with `?path=/Packages/com.adapty.unity-sdk`.
- Updated native SDK dependencies and the cross-platform contract to 3.17.2 (iOS and Android).
