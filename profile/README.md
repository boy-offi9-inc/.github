# Boy Offi9 Inc

<p align="center">
  <img src="https://img.shields.io/badge/Independent-Software%20Lab-111111?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20Source-Projects-111111?style=for-the-badge&logo=opensourceinitiative&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-Systems-111111?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Reverse%20Engineering-Research-111111?style=for-the-badge&logo=hackthebox&logoColor=white" />
</p>

<p align="center">
  <strong>We build the tools we wish existed.</strong>
</p>

---

## What this is

Boy Offi9 Inc is an independent software lab. The work runs from focused developer tooling to Android systems to reverse-engineering infrastructure — built to be used, not demoed. Everything public here is maintained; everything half-finished stays private until it earns its way out.

## Flagship

### [hexforge-gateway](https://github.com/boy-offi9-inc/hexforge-gateway) · TypeScript · 13 stars

Self-hosted reverse-engineering workspace API. One gateway orchestrates jadx, apktool, APKiD, frida and adb behind a typed MCP and REST surface, then keeps what it learns in a typed knowledge graph with findings and a verifier. Ten built-in agents, nine AI providers, a pinned Docker runtime, and a redaction model that never lets a secret leave the box. CodeQL clean, 615 tests.

### [apk-unravel](https://github.com/boy-offi9-inc/apk-unravel) · JavaScript · 4 stars

Decompile any APK into a single readable report: permissions tiered by risk, exported components, deep links with a check on whether the target actually handles them, native ABI and 16 KB page-size checks, and a URL/secret scan with custom rules. Runs on Termux as happily as on a laptop. `npm i -g @boy-offi9-inc/apk-unravel`

### [matrix-rain-view](https://github.com/boy-offi9-inc/matrix-rain-view) · Kotlin · 8 stars

Matrix digital rain for Android, drawn live on a Canvas — a standard `View` and a Jetpack Compose composable. Runtime-configurable, touch-reactive, delta-time smooth across 60 and 120 Hz, and zero asset files in your APK. The [demo app](https://github.com/boy-offi9-inc/matrix-rain-demo) wires every property to a live control.

## The rest of the bench

| Project | What it does | Stack |
|---|---|---|
| [reqkit](https://github.com/boy-offi9-inc/reqkit) | Small, composable HTTP helpers — retry with backoff, Retry-After aware | JavaScript |
| [Playfold](https://github.com/boy-offi9-inc/Playfold) | Tiny, framework-agnostic SDK for embedding media players | TypeScript |
| [Tidepull](https://github.com/boy-offi9-inc/Tidepull) | Minimal, from-scratch media downloader — extractors, no bloat | TypeScript |
| [btch-downloader-api](https://github.com/boy-offi9-inc/btch-downloader-api) | No-auth REST API over btch-downloader, sixteen platforms | JavaScript |
| [scifi-ui-kit](https://github.com/boy-offi9-inc/scifi-ui-kit) | Sci-fi HUD components for Android: chamfered panels, glitch text | Kotlin |
| [isomorphic-unzip](https://github.com/boy-offi9-inc/isomorphic-unzip) | Maintained drop-in replacement for the abandoned original | JavaScript |

## How the work splits

**Developer tools** get built when something common is more annoying than it should be — that is where reqkit, Playfold and apk-unravel came from. **Android systems** covers libraries like matrix-rain-view and scifi-ui-kit, plus the Termux and proot automation that mostly lives in private repos. **Reverse engineering** is the deepest thread: hexforge-gateway exists because static analysis of an APK should produce a report you can read, not a folder you have to spelunk.

## Stack

TypeScript · Kotlin · Go · JavaScript · Node.js · Android · Linux

## Contributing

Issues, ideas and pull requests are welcome on any public repo. Each project's README carries its own setup instructions. The house style: small focused commits, tests for behaviour, no surprises in a diff.

---

<p align="center">
  <code>Understand → Build → Break → Improve → Repeat</code>
</p>

<p align="center">
  <sub>Built independently. Open where it makes sense.</sub>
</p>
