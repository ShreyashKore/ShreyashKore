# Shreyash Kore

**Senior mobile engineer — Android · Kotlin Multiplatform · Flutter · React Native**

I build cross-platform apps and the developer tools that make them easier to ship. Kotlin and Dart most days, TypeScript and Node.js on the backend.

[gyanoba.com](https://gyanoba.com) · [LinkedIn](https://www.linkedin.com/in/shreyashkore/) · [X](https://twitter.com/ShreyashKore) · [YouTube](https://www.youtube.com/channel/UCoTuYVuoLypuiy8LIGJGn4A)

<table>
<tr align="center" valign="top">
<td width="25%">
<a href="https://github.com/ShreyashKore/wonderous_compose"><img src="https://raw.githubusercontent.com/ShreyashKore/wonderous_compose/main/readme_images/app-icon.webp" width="64" alt="Wonderous Compose app icon"></a><br>
<b><a href="https://github.com/ShreyashKore/wonderous_compose">Wonderous Compose</a></b><br>
<sub>Compose Multiplatform app on 5 platforms</sub><br>
<img src="https://img.shields.io/github/stars/ShreyashKore/wonderous_compose?style=flat-square&label=%E2%98%85&labelColor=24292f&color=24292f" alt="stars">
</td>
<td width="25%">
<a href="https://github.com/ShreyashKore/inspektor"><img src="https://raw.githubusercontent.com/ShreyashKore/inspektor/main/images/inspektor.png" width="64" alt="Inspektor logo"></a><br>
<b><a href="https://github.com/ShreyashKore/inspektor">Inspektor</a></b><br>
<sub>HTTP inspection library for Ktor</sub><br>
<img src="https://img.shields.io/github/stars/ShreyashKore/inspektor?style=flat-square&label=%E2%98%85&labelColor=24292f&color=24292f" alt="stars">
</td>
<td width="25%">
<a href="https://github.com/ShreyashKore/kexcel"><img src="https://raw.githubusercontent.com/ShreyashKore/kexcel/main/art/logo.png" width="64" alt="Kexcel logo"></a><br>
<b><a href="https://github.com/ShreyashKore/kexcel">Kexcel</a></b><br>
<sub>Excel for Kotlin Multiplatform, no Apache POI</sub><br>
<img src="https://img.shields.io/github/stars/ShreyashKore/kexcel?style=flat-square&label=%E2%98%85&labelColor=24292f&color=24292f" alt="stars">
</td>
<td width="25%">
<a href="https://github.com/ShreyashKore/eagly"><img src="https://raw.githubusercontent.com/ShreyashKore/eagly/main/assets/app_icon.png" width="64" alt="Eagly app icon"></a><br>
<b><a href="https://github.com/ShreyashKore/eagly">Eagly</a></b><br>
<sub>Android &amp; iOS log viewer for the desktop</sub><br>
<img src="https://img.shields.io/github/stars/ShreyashKore/eagly?style=flat-square&label=%E2%98%85&labelColor=24292f&color=24292f" alt="stars">
</td>
</tr>
</table>

<sub>Also: <a href="https://github.com/ShreyashKore/ejs_editor">EJS Editor</a> · <a href="https://github.com/ShreyashKore/ComposeGoodies">ComposeGoodies</a> · <a href="https://github.com/ShreyashKore?tab=repositories">all repositories</a></sub>

---

<img align="right" width="430" alt="Wonderous Compose running on Android, iOS and the web, showing the Taj Mahal screen" src="https://raw.githubusercontent.com/ShreyashKore/wonderous_compose/main/readme_images/banner.png">

### Wonderous Compose

<sub>**Kotlin · Compose Multiplatform · WASM**</sub>

A port of gskinner's Wonderous to **Compose Multiplatform** — one Kotlin codebase running on Android, iOS, desktop and the browser via WASM. Built to find out how far Compose can be pushed on animation-heavy, art-directed UI: parallax, shared-element transitions and custom illustration work included.

[Repository](https://github.com/ShreyashKore/wonderous_compose) · [Try it in the browser](https://shreyashkore.github.io/wonderous-compose-wasm/)

<br clear="all">

<img align="left" width="430" alt="Inspektor showing HTTP request and response details inside an Android app and on desktop" src="https://raw.githubusercontent.com/ShreyashKore/inspektor/main/images/cover.png">

### Inspektor

<sub>**Kotlin Multiplatform · Ktor**</sub>

An **HTTP inspection library for Ktor**, in the spirit of Chucker. Drop it into a client and inspect requests, headers and bodies from inside the running app — then go further and **override or mock responses** without touching the backend. Published on Maven Central for Android, iOS, desktop and web.

[Repository](https://github.com/ShreyashKore/inspektor) · [Maven Central](https://central.sonatype.com/artifact/com.gyanoba.inspektor/inspektor)

<br clear="all">

### Kexcel

<sub>**Kotlin Multiplatform · Office Open XML**</sub>

Every other Kotlin Excel library wraps Apache POI, which is JVM-only. **Kexcel parses and writes `.xlsx` itself, in pure Kotlin**, so the same spreadsheet code runs in `commonMain` on JVM, Android and iOS — styling, formulas, merged cells and all.

```kotlin
val excel = Excel.createExcel()
val sheet = excel["Sheet1"]

sheet.updateCell(CellIndex.indexByString("A1"), TextCellValue("Revenue"))
sheet.updateCell(CellIndex.indexByString("B1"), FormulaCellValue("=SUM(B2:B12)"))

val bytes: ByteArray = excel.encode()
```

[Repository](https://github.com/ShreyashKore/kexcel) · [Documentation](https://shreyashkore.github.io/kexcel/) · [Maven Central](https://central.sonatype.com/artifact/com.gyanoba.kexcel/kexcel)

<br clear="all">

<img align="right" width="430" alt="Eagly desktop app showing filtered Android device logs" src="https://raw.githubusercontent.com/ShreyashKore/eagly/main/docs/screenshots/logs_screen.png">

### Eagly

<sub>**Flutter · Dart · macOS, Windows, Linux**</sub>

A **desktop log viewer for Android and iOS devices**, for developers and QA who need device logs without a terminal. `adb` and `libimobiledevice` are bundled, so there is nothing to install: multi-device tabs, live filtering, wireless debugging, screen mirroring, iOS crash logs and log import/export.

[Repository](https://github.com/ShreyashKore/eagly) · [Download](https://github.com/ShreyashKore/eagly/releases)

<br clear="all">

<table>
<tr>
<td width="33%"><img alt="Eagly wireless debugging setup" src="https://raw.githubusercontent.com/ShreyashKore/eagly/main/docs/screenshots/wireless-debugging.png"></td>
<td width="33%"><img alt="Eagly screen mirroring a connected device" src="https://raw.githubusercontent.com/ShreyashKore/eagly/main/docs/screenshots/screen-mirroring.png"></td>
<td width="33%"><img alt="Eagly iOS crash log details" src="https://raw.githubusercontent.com/ShreyashKore/eagly/main/docs/screenshots/ios-crashlogs-details.png"></td>
</tr>
</table>

---

### Toolbox

|  |  |
| --- | --- |
| **Android & Kotlin** | Kotlin, Java, Jetpack Compose, Coroutines, Ktor, Gradle |
| **Cross-platform** | Compose Multiplatform, Flutter/Dart, React Native/TypeScript |
| **Backend & web** | Node.js, TypeScript, Next.js, REST, GraphQL |
| **Tooling** | GitHub Actions, IntelliJ Platform, Maven Central publishing |

I started on native Android with Java, moved through Jetpack Compose to Compose Multiplatform, and ship Flutter and React Native alongside it — so cross-platform decisions get made on trade-offs rather than on whichever framework I happen to know.

Open to interesting cross-platform work — [say hello](https://www.linkedin.com/in/shreyashkore/).
