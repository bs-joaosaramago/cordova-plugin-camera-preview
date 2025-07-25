# Changelog

## MASTER BRANCH (RECOMMENDED) - UNRELEASED
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.14.0...master)
- Nothing yet

## v0.14.0 - LATEST RELEASED VERSION
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.13.0...v0.14.0)
- [#709](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/709) - Remove unused permissions `READ_MEDIA_IMAGES` and `READ_MEDIA_VIDEOS`
- [#707](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/707) - Fixes to prevent null pointer and runtime errors
- [#701](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/701) - Fix Camera preview not going to back in Ionic Capacitor

## v0.13.0 - July 23, 2024 - LATEST RELEASED VERSION
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.12.3...v0.13.0)
- [#699](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/commit/21961100181c97dcbf59e72749d6cf2add7f05ef) - Null pointer exception fixes
- [#689](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/689) - Improve error handling for Android
- [#688](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/688) - Fix exceptions thrown around flash types when calling setParameters on Android. We now check supported flash mode types and only enable the modes that are found.
- [#687](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/687) - Add Android 33+ required permissions for media image and media video permissions
- [#676](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/676) - Ensure `toBack` behaves correctly on Android

## v0.12.3
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.12.2...v0.12.3)
- [#654](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/654) - Fix memory leak when taking multiple snapshots

## v0.12.2 - Apr 15, 2021
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.12.1...v0.12.2)
- [#639](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/639) - Typescript definition fix
- [#633](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/633) - Fix app crash with `startRecordVideo` after allowing the `RECORD_AUDIO` permission prompt.
- [#630](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/630) - For Android, make both camera and autofocus non-required for the library. This is an application level concern.

## v0.12.1 - Oct 21, 2020
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.12.0...v0.12.1)
- [#624](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/issues/624) - Remove unused coefficient argument from the `calculateTapArea` method of the Android code
- [#619](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/619) - Fix compiler errors in startRecordVideo by declaring final variables
- [#615](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/615) - Correctly handle torch mode in getFlashMode

## v0.12.0 - May 4, 2020
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.11.2...v0.12.0)
- [#605](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/605) - Improve memory usage when capturing multiple photos for both Android and iOS
- [#587](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/587) - Add video recording functionality for Android
- [#599](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/599) - Use androidx package instead of legacy android support package
- [#606](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/606) - Remove `android:required` from manifest to avoid conflict with other plugins

## v0.11.2 - February 12, 2020
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.11.1...v0.11.2)
- [#582](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/582) - Add support for Android devices without Autofocus which can increase the amount of devices for which app installation is allowed by about (~4k at time of)
- [#583](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/583) - Fix typescript error CameraPreview.d.ts is not a module

## v0.11.1 - November 19, 2019
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.11.0...v0.11.1)
- [#573](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/573) - Fetch number of cameras immediately before switching cameras in Android
- [#428](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/issues/428) - Fix mispelling of `continuous` within iOS source code for focus modes (was `cotinuous` before)
- [#568](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/568), [PR #570](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/570) - Resolves plugin interaction issues when toBack is set and other plugins like cordova-plugin-googlemaps are changing the layout

## v0.11.0 - May 20, 2019
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.10.0...v0.11.0)
- [#525](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/525) - Add function `takeSnapshot` for quick image captures
- [#441](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/441) - Add android only option `storeToFile` for storage in temporary file instead of base64
- [#524](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/524) - Add iOS support for `storeToFile`
- [#396](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/pull/396) - Add function `getCameraCharacteristics`
- Allow `startCamera` to allow no options object when only callback is provided
- Add Changelog

## v0.10.0 - June 13, 2018
- [View Diff](https://github.com/cordova-plugin-camera-preview/cordova-plugin-camera-preview/compare/v0.9.0...v0.10.0)
- Merge in features and fixes from various forks

## v0.9.0 - May 9, 2017

## v0.0.8 - March 30, 2015

## v0.0.6 - February 4, 2015

## v0.0.3 - January 12, 2015

## v0.0.2 - January 7, 2015
