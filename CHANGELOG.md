# :warning: This project has moved to [github.com/braze-inc/braze-roku-sdk](https://github.com/braze-inc/braze-roku-sdk)

## 0.0.4

##### Changed
- Replaced the `GetModel` method with the more precise `GetModelDetails().ModelNumber`

##### Fixed
- Replaced the deprecated `GetVersion` Roku API method with `GetOSVersion`.

## 0.0.3

##### Fixed
- Fixed the polarity on `ad_tracking_enabled` sent to Braze via device info.

## 0.0.2

##### Fixed
- Fixed an issue with device Id generation.

## 0.0.1

##### Added
- Initial release.
- Supports logging custom events, purchases, setting default and custom user attributes, session tracking, and user identity management.
