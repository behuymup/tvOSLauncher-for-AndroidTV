# Third-Party Notices

This file supplements [`NOTICE`](NOTICE). It identifies third-party software,
assets, and runtime data services currently recorded for tvOS Launcher. Each
component retains its own license and copyright notices; this file does not
relicense those components.

The repository's source snapshot has no Git metadata, and some upstream file
mappings are unavailable. Where that limits attribution or license verification,
the uncertainty is stated below. License texts are included under
[`assets/legal/licenses/`](assets/legal/licenses/) where available.

## Software and assets included with the app

| Component | Use in this project | License and notices | Source |
|---|---|---|---|
| tvOS Launcher upstream | Upstream source lineage; exact imported revision and copied-file map are unavailable. | Apache License 2.0. Preserve applicable upstream notices and mark changes to modified files. | [GitHub](https://github.com/techgenius1/tvOS-Launcher) |
| Hume Launcher | Identified as the original launcher codebase; exact imported revision and copied-file map are unavailable. | Apache License 2.0. Upstream NOTICE credits Petrobot. Preserve applicable notices and mark changes to modified files. | [GitHub](https://github.com/petrobot-admin/hume-launcher) |
| CleanYourTV | Device cleanup data in `assets/cleanyourtv/`; exact source revision and file map are unavailable. | MIT. See [`MIT-CleanYourTV.txt`](assets/legal/licenses/MIT-CleanYourTV.txt). | [GitHub](https://github.com/Gathin23/cleanyourtv) |
| Project Nayuki QR Code Generator | Java source under `src/io/nayuki/qrcodegen/`. | MIT. Preserve the source-file notices. See [`MIT-Nayuki.txt`](assets/legal/licenses/MIT-Nayuki.txt). | [GitHub](https://github.com/nayuki/QR-Code-generator) |
| Inter and Inter Display | Bundled font files under `assets/fonts/` (Regular, Medium, SemiBold, and Display Bold). | SIL Open Font License 1.1. See [`OFL-1.1-Inter.txt`](assets/legal/licenses/OFL-1.1-Inter.txt). | [GitHub](https://github.com/rsms/inter) |
| OpenVPN Android library | Android VPN integration; library version 1.1.3, distributed in `libs/openvpn/`. | Apache License 2.0. Attribution to VPNProtocols (`io.github.tim06`). See [`libs/openvpn/NOTICE.md`](libs/openvpn/NOTICE.md). | [GitHub](https://github.com/TIM06/openvpn-android) |
| OpenVPN 3 Core | Native runtime (`libovpn3.so`) distributed with the VPN integration; core version 1.13.1. | Mozilla Public License 2.0. Preserve upstream notices and meet applicable source-distribution requirements. See [`MPL-2.0.txt`](assets/legal/licenses/MPL-2.0.txt) and [`libs/openvpn/NOTICE.md`](libs/openvpn/NOTICE.md). | [GitHub](https://github.com/OpenVPN/openvpn3) |
| Kotlin and kotlinx.coroutines | Runtime dependencies bundled with the OpenVPN Android integration. | Apache License 2.0; retain notices in the corresponding archives. | [Kotlin](https://github.com/JetBrains/kotlin), [kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines) |
| AndroidX libraries | Lifecycle, Core, DataStore, and annotations used by the OpenVPN integration. | Apache License 2.0; retain notices in the corresponding archives. | [AndroidX](https://github.com/androidx/androidx) |
| Okio | Dependency bundled with the OpenVPN Android integration. | Apache License 2.0; Copyright 2013 Square, Inc.; retain notices in the archive. | [GitHub](https://github.com/square/okio) |
| Macintosh Skeletal-derived setup strokes | Derived stroke data in `assets/setup/macintosh-greetings.json`; original font files are not packaged in the app. | **Permission review required.** The included source terms describe personal, non-commercial, educational restrictions. Public APK redistribution permission has not been established. See [`Macintosh-Skeletal-Source-LICENSE.txt`](assets/legal/licenses/Macintosh-Skeletal-Source-LICENSE.txt). | [GitHub](https://github.com/npwitk/Macintosh-Skeletal-Filled) |

## Runtime data services

| Service | Use | Data license and terms | Source |
|---|---|---|---|
| Open-Meteo | Weather forecast and city search requests. | CC BY 4.0 attribution applies to covered data; underlying datasets may retain separate rights. API terms also apply. Confirm the app's eligibility and visible attribution requirements. | [Open-Meteo](https://open-meteo.com/), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), [API terms](https://open-meteo.com/en/terms) |
| MET Norway Locationforecast | Fallback weather forecast requests. | Dataset terms may be CC BY 4.0 or NLOD 2.0 depending on the data. Credit MET Norway and follow its API terms and client-identification requirements. | [API](https://api.met.no/), [data license](https://docs.api.met.no/doc/License.html), [terms](https://docs.api.met.no/doc/TermsOfService) |
| wttr.in | Fallback weather requests. | The server's source-code license does not establish the license for returned weather data. Data provenance, attribution, and service terms remain to be confirmed. | [Service source](https://github.com/chubin/wttr.in) |

## Acknowledged references

The following projects are acknowledged in the project documentation. The current
checkout does not include a file-level map establishing that their code is
bundled in the app; listing a project here does not assert that its code is
included.

- [Couch TV](https://github.com/Seagey/couch-tv) — MIT; see [`MIT-Couch-TV.txt`](assets/legal/licenses/MIT-Couch-TV.txt).
- [McIntosh Writer](https://github.com/jhao941/McIntosh-Writer) — acknowledged reference; exact use and license mapping have not been established in this checkout.
- [Android AirPlay Server](https://github.com/jqssun/android-airplay-server) — compatible companion receiver described in the project documentation; it is distributed separately from this launcher.

## License texts

License texts available in this repository are stored in
[`assets/legal/licenses/`](assets/legal/licenses/). Components may also include
additional notices in their source files or dependency archives; those notices
remain applicable.
