<div align="center">

<h1>tvOS Launcher for Android TV</h1>

<p>
  <strong>A More Personal Home for Your TV</strong>
  <br/>
  An elegant Android TV launcher inspired by APtvOS.
</p>

<p>
  Make your TV feel like yours. Arrange your apps, personalize the screen,
  and keep everyday controls close at hand.
</p>

<p>
  <strong>Personalized home screen</strong>
  &nbsp;·&nbsp;
  <strong>Remote-friendly controls</strong>
  &nbsp;·&nbsp;
  <strong>Wallpapers, weather, and more</strong>
</p>

</div>

---

## ✨ About

tvOS Launcher gives Android TV and Google TV a welcoming home screen built around the apps and features you use every day. Organize apps in a dock and grid, set up profiles, choose a look for your screen, and open useful TV controls with your remote.

It brings together personalization, weather, screen saver settings, presentation tools, app management, and optional VPN features. What is available can depend on your TV model, Android version, installed apps, and network connection.

## 🖼️ Explore the Launcher

Each section pairs a short feature overview with a related screen from the project.

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Make the Home Screen Yours</h3>
      <p>Arrange apps in the dock and grid, change their order, and hide apps you do not use. Create profiles with their own names, avatars, and app layouts, so each person can have a home screen that suits them.</p>
      <p>Built-in scenes, personal photos, and supported online sources give you ways to make the background your own.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="artifacts/tv-qa/retest-20261123-full/home-v1082.png" width="100%" alt="tvOS Launcher home screen with app dock, wallpaper, and weather"/>
      <br/><sub>Home screen with wallpaper, weather, and app dock</sub>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Choose Your Background</h3>
      <p>Use built-in scenes, photos from your TV, personal slideshows, or supported Internet wallpaper sources. Image settings help you choose how pictures appear on the screen.</p>
      <p>Show local weather and forecasts, then add optional live effects such as snowfall to the home screen.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="docs/images/home-wallpaper.jpg" width="100%" alt="Launcher app dock displayed over a selected wallpaper"/>
      <br/><sub>App dock displayed over a selected background</sub>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Keep Controls Close</h3>
      <p>Open Control Center for shortcuts to supported TV controls, including Wi-Fi, Bluetooth, TV inputs, audio, sleep timer, AirPlay, and search.</p>
      <p>Choose which shortcuts appear and map supported remote buttons to single, double, triple, or long-press actions. Available controls vary by device.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="docs/images/control-center.jpg" width="100%" alt="Launcher Control Center with quick controls and app dock"/>
      <br/><sub>Control Center shortcuts on the home screen</sub>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Make Idle Time Feel Better</h3>
      <p>Configure the TV screen saver and choose how the launcher behaves when the TV is idle. The home carousel can surface recommendations and news, while screen saver options are managed from Settings.</p>
      <p>Personal photos and supported online image sources can also be used for slideshow features.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="docs/images/idle-carousel.jpg" width="100%" alt="Launcher home carousel showing a news recommendation"/>
      <br/><sub>Home carousel with a regional news item</sub>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Present Content on Your TV</h3>
      <p>Presentation Mode lets you send photos, videos, and web pages from a phone or computer on the same local network. Pair a device with the code shown on the TV, then manage the presentation from its browser.</p>
      <p>For AirPlay receiving, install and configure a compatible receiver app separately; it is not bundled with the launcher.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="docs/images/presentation-empty.jpg" width="100%" alt="Presentation Mode pairing code displayed on the TV"/>
      <br/><sub>Pair a phone or computer with Presentation Mode</sub>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td width="58%" valign="middle">
      <h3>Manage Apps and Settings</h3>
      <p>Install supported APK and XAPK files, organize installed apps, and manage hidden or system apps. Back up and restore launcher settings, check for updates, and use automatic cache cleanup.</p>
      <p>Settings also brings together profiles, screen saver options, AirPlay controls, network features, and other device-specific options.</p>
    </td>
    <td width="42%" align="center" valign="middle">
      <img src="artifacts/tv-qa/retest-20261123-full/settings-root2-v1082.png" width="100%" alt="Launcher settings menu with profiles, screen saver, AirPlay, network, and system options"/>
      <br/><sub>Settings for profiles, screen saver, AirPlay, and the TV</sub>
    </td>
  </tr>
</table>

## 🌐 Languages and Compatibility

The interface is available in English, Vietnamese, Japanese, Chinese, Hindi, Spanish, Thai, Korean, French, and Russian. The app targets Android 7.0 (API 24) and newer. Device support can vary by manufacturer, Android release, system components, and remote-control behavior.

## 🧩 Open-Source Code and Credits

The source tree records the projects and components below. The exact upstream revision or file-by-file reuse map is unavailable for some entries; the project’s [license audit](LICENSE-AUDIT.md) describes those limits. Full notices and license texts are available in [Third-Party Notices](THIRD-PARTY-NOTICES.md) and [`assets/legal/`](assets/legal/).

### Source Code and Bundled Components

- **[Hume Launcher](https://github.com/petrobot-admin/hume-launcher)** — the launcher codebase this project identifies as its starting point. Apache License 2.0.
- **[tvOS Launcher upstream](https://github.com/techgenius1/tvOS-Launcher)** — upstream project lineage recorded in the project NOTICE. Apache License 2.0; the exact imported revision and file mapping are not available in this checkout.
- **[CleanYourTV](https://github.com/Gathin23/cleanyourtv)** — source for bundled TV device cleanup profiles and related safety rules. MIT License.
- **[Project Nayuki QR Code Generator](https://github.com/nayuki/QR-Code-generator)** — Java QR code source in `src/io/nayuki/qrcodegen/`. MIT License.
- **[Inter](https://github.com/rsms/inter)** — bundled Inter and Inter Display font files. SIL Open Font License 1.1.
- **[OpenVPN 3 Core](https://github.com/OpenVPN/openvpn3)** — native VPN runtime. Mozilla Public License 2.0. The Android AAR and dependency versions are listed in [`libs/openvpn/NOTICE.md`](libs/openvpn/NOTICE.md); the [Maven Central record](https://central.sonatype.com/artifact/io.github.tim06/openvpn) identifies the OpenVPN Android package.
- **Kotlin, AndroidX, and Okio** — bundled dependencies used by the OpenVPN Android components; see the component versions and notices in [`libs/openvpn/NOTICE.md`](libs/openvpn/NOTICE.md). Their source projects are [Kotlin](https://github.com/JetBrains/kotlin), [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines), [AndroidX](https://github.com/androidx/androidx), and [Okio](https://github.com/square/okio).

### Asset with Separate Use Restrictions

- **[Macintosh Skeletal Filled](https://github.com/npwitk/Macintosh-Skeletal-Filled)** — source of the Macintosh-derived stroke data used for the setup greeting. The included source terms limit use to personal, non-commercial, educational purposes; permission for public APK redistribution is not established. See the [license audit](LICENSE-AUDIT.md) before redistribution.

### Acknowledged References and Companion Apps

- **[Couch TV](https://github.com/Seagey/couch-tv)** and **[McIntosh Writer](https://github.com/jhao941/McIntosh-Writer)** are acknowledged references. This checkout does not establish that their code is included in the app.
- **[Android AirPlay Server](https://github.com/jqssun/android-airplay-server)** is a separate compatible receiver app described in the install guide. It is not bundled with tvOS Launcher.

### Runtime Data Services

These services provide data or media at runtime; their server code and their returned content have separate terms. Check each provider’s current conditions and the attribution shown in the app.

- Weather: [Open-Meteo](https://open-meteo.com/), [MET Norway](https://api.met.no/), and [wttr.in](https://github.com/chubin/wttr.in).
- Artwork and wallpaper sources include museum collections, Wikimedia Commons, Openverse, NASA, Bing, Apple Aerials, Amazon’s image catalog, and the project’s [wallpaper repository](https://github.com/behuymup/tvOSLauncher-for-AndroidTV).
- Other network features use news feeds, entertainment metadata services, geolocation providers, and VPN Gate. Details are in the source and the in-app legal information.

## 📚 Documentation

- [Getting started](docs/getting-started.md)
- [Feature guide](docs/features.md)
- [Install and permissions](docs/install.md)
- [Presentation Mode](docs/presentation.md)
- [Integrated VPN](docs/vpn.md)
- [Architecture](docs/architecture.md)
- [TV focus and performance QA](docs/tv-performance-qa.md)
- [Contributing](CONTRIBUTING.md)
- [License audit](LICENSE-AUDIT.md)
- [Third-party notices](THIRD-PARTY-NOTICES.md)

## 🛠️ Build

Requirements: JDK 17 or newer, Android SDK Build Tools `35.0.0`, platform `android-36`, and the SDK’s R8 tool (the defaults in `build.sh`). Release builds require the maintainer release keystore. R8 shrinks unused dependency code in both variants and obfuscates app-owned names in Release while preserving Android and reflection entry points. Debug builds retain app-owned names for local debugging. Set `ENABLE_R8=0` to use D8 for diagnostics. Override SDK versions with `BUILD_TOOLS_VERSION` and `COMPILE_SDK_VERSION` when using another installed SDK.

From macOS or Linux:

```sh
RELEASE_KEYSTORE=/path/to/tvos-release.jks RELEASE_KEYSTORE_PASS=... VERSION_CODE=... VERSION_NAME=... ./build.sh
```

For local development, run `BUILD_VARIANT=debug ./build.sh`; debug APKs cannot update release installs and should not be distributed. The signed APK is written to `build/tvos-home.apk`; the build code increments from the existing output unless `VERSION_CODE` is set. Intermediate files are removed after a successful build; set `KEEP_BUILD_INTERMEDIATES=1` to retain them. See [Getting started](docs/getting-started.md) for SDK setup and install steps. On Windows, use `build.ps1` with the same `RELEASE_KEYSTORE` and `RELEASE_KEYSTORE_PASS` variables for releases, or `BUILD_VARIANT=debug` for development.

## ⚖️ License

The root [LICENSE](LICENSE) and [NOTICE](NOTICE) preserve the project’s Apache-2.0 terms and upstream credits. Third-party components have their own licenses and notices; review the [license audit](LICENSE-AUDIT.md) and [Third-Party Notices](THIRD-PARTY-NOTICES.md) before redistributing the app or its source.

`LICENSE-PROPRIETARY.txt` applies only to original modifications whose rights Huy Mup can license. It does not replace third-party terms. License texts are included under [`assets/legal/`](assets/legal/) for offline reading.

---

<div align="center">
  <strong>tvOS Launcher</strong>
  <br/>
  <sub>Make your TV experience uniquely yours.</sub>
</div>
