<div align="center">

  <img src="assets/brand/app_logo_wordmark.png" alt="NuvioTV" width="300" />
  <br />
  <br />

  <p>
    A modern Android TV media player powered by the Custom addon(s) ecosystem.
    <br />
    Custom Addon(s) ecosystem • Android TV optimized • Playback-focused experience
  </p>

</div>

## About

NioTV is a modern media player designed specifically for Android TV.

It acts as a client-side playback interface that can integrate with the Custom addon(s) ecosystem for content discovery and source resolution through pre-installed extensions.

Built with Kotlin and optimized for a TV-first viewing experience.

## Installation

### Android TV

Download the latest APK from [GitHub Releases](#) and install on your Android TV device.

## Development

### Prerequisites

- Android Studio (latest version)
- JDK 11+
- Android SDK (API 29+)
- Gradle 8.0+

### Setup

```bash
git clone https://github.com/ExpectedNinja/NioTV.git
cd NioTV
```

### Full Debug Build

```bash
./gradlew :app:compileFullDebugKotlin
./gradlew :app:assembleFullDebug
```

### Running on Emulator or Device

```bash
# Full debug build
./gradlew :app:assembleFullDebug

# Run on connected device
adb shell am start -n com.nuviodebug.com/com.nuvio.tv.MainActivity
```

## Legal & DMCA

NioTV functions solely as a client-side interface for browsing metadata and playing media provided by pre-installed extensions and/or pre-provided sources. It is intended for content the user owns or is otherwise authorized to access.

NioTV is not affiliated with any third-party extensions or content providers. It does not host, store, or distribute any media content.

For comprehensive legal information, including our full disclaimer, third-party extension policy, and DMCA/Copyright information, please visit our **[Legal & Disclaimer Page](#)**.

## Built With

* Kotlin
* Jetpack Compose & TV Material3
* ExoPlayer / Media3
* Hilt (Dependency Injection)
* Retrofit (Networking)
* Gradle
