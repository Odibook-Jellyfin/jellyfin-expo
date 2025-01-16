<h1 align="center">Jellyfin Mobile</h1>
<h3 align="center">Part of the <a href="https://jellyfin.org">Jellyfin Project</a></h3>

---

<p align="center">
<img alt="Logo banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/branding/SVG/banner-logo-solid.svg?sanitize=true"/>
<br/><br/>
<a href="https://github.com/jellyfin/jellyfin-expo/blob/master/LICENSE"><img alt="MPL-2.0 license" src="https://img.shields.io/github/license/jellyfin/jellyfin-expo"></a>
<a href="https://github.com/jellyfin/jellyfin-expo/releases"><img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-expo.svg"/></a>
<a href="https://translate.jellyfin.org/projects/jellyfin/jellyfin-expo/?utm_source=widget">
<img alt="Translation Status" src="https://translate.jellyfin.org/widgets/jellyfin/-/jellyfin-expo/svg-badge.svg"/>
</a>
<a href="https://codecov.io/gh/jellyfin/jellyfin-expo">
<img alt="Codecov" src="https://img.shields.io/codecov/c/github/jellyfin/jellyfin-expo?token=Wk8RS9tDnb">
</a>
<br/>
<a href="https://opencollective.com/jellyfin"><img alt="Donate" src="https://img.shields.io/opencollective/all/jellyfin.svg?label=backers"/></a>
<a href="https://features.jellyfin.org"><img alt="Feature Requests" src="https://img.shields.io/badge/fider-vote%20on%20features-success.svg"/></a>
<a href="https://matrix.to/#/+jellyfin:matrix.org"><img alt="Chat on Matrix" src="https://img.shields.io/matrix/jellyfin:matrix.org.svg?logo=matrix"/></a>
<br/><br/>
<a href="https://apps.apple.com/us/app/jellyfin-mobile/id1480192618?mt=8"><img width="135" src="https://linkmaker.itunes.apple.com/en-us/badge-lrg.svg?releaseDate=2020-02-09&kind=iossoftware&bubble=ios_apps" alt="Download on the App Store"/></a>
</p>

Jellyfin Mobile is a mobile app built with [Expo](https://expo.io/) primarily targeting iOS devices. We welcome all contributions and pull requests! If you have a larger feature in mind please open an issue so we can discuss the implementation before you start. We use [GitHub Projects](https://github.com/jellyfin/jellyfin-expo/projects) as a general roadmap for releases.

## Translations

Translations can be improved very easily from our [Weblate](https://translate.jellyfin.org/projects/jellyfin/jellyfin-expo/) instance. Look through the following graphic to see if your native language could use some work!

<a href="https://translate.jellyfin.org/engage/jellyfin/?utm_source=widget">
<img alt="Detailed Translation Status" src="https://translate.jellyfin.org/widgets/jellyfin/-/jellyfin-expo/multi-auto.svg"/>
</a>

## Build Process

### Getting Started

1. Clone or download this repository.

   ```sh
   git clone https://github.com/jellyfin/jellyfin-expo.git
   cd jellyfin-expo
   ```

2. Install build dependencies using **npm** in the project directory.

   ```sh
   npm install
   ```

3. Start the build tools.

   ```sh
   npm start
   ```

4. Follow the directions in the terminal or browser window to open on a device or emulator.

## FAQ

### What is the difference between this and other Jellyfin app projects?

| App Name | Status | Platforms | Description |
|:-:|:-:|:-:|-|
| [Jellyfin Mobile](https://github.com/jellyfin/jellyfin-expo) | ✅ Active | iOS, iPadOS | The app in this repository. It is a web wrapper based on Expo (React Native) with some native enhancements. It is available on the [App Store](https://apps.apple.com/us/app/jellyfin-mobile/id1480192618?mt=8) for iPhone and iPad. |
| [Swiftfin](https://github.com/jellyfin/swiftfin) | ✅ Active | iOS, iPadOS, tvOS | Swiftfin is a modern video client. Designed in Swift to maximize direct play with the power of VLC and look native on all classes of Apple devices. The beta is available on the [App Store](https://apps.apple.com/us/app/swiftfin/id1604098728). |
