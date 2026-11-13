# CV Studio — Desktop & installable app (download)

**Download page: https://romal10.github.io/cv-studio-desktop/**

Public download page for **CV Studio**. The application source code is **private**; this repository only hosts the download information, the licence and release files.

## What you get
- **Works offline.** The desktop app opens without internet.
- **Your CV stays on your device.** Choose *only on this device* or *online*. Putting it online (for share links and online features) and taking it back to local are one tap each, and the app always tells you where your CV lives.
- **Local AI helper.** The app checks and sets up a local AI (Ollama) on your computer — no API key, text stays on the device.
- **Managed installs.** Your organisation's administrator can see which devices have the app and can block access if something happens.

## Download
**Latest: [v0.1.0 (pre-release)](../../releases/tag/v0.1.0)**

| Device | File |
|---|---|
| **Mac, Apple chip** (M1 / M2 / M3 / M4) | `CV-Studio-0.1.0-mac-apple-silicon.dmg` |
| **Mac, Intel chip** | `CV-Studio-0.1.0-mac-intel.dmg` |
| **Windows 10/11, 64-bit** | `CV-Studio-Setup-0.1.0-windows.exe` |
| **iPad / iPhone** | Open CV Studio in Safari → Share → *Add to Home Screen* |
| **Android / other browsers** | Open CV Studio in Chrome or Edge → *Install app* |

Check your download against `SHA256SUMS.txt` on the release page.

### First launch — these builds are not signed yet
- **Mac:** open the `.dmg`, drag *CV Studio* to Applications, then **right-click the app → Open → Open**. If macOS still blocks it: System Settings → Privacy & Security → *Open Anyway*.
- **Windows:** SmartScreen shows "Windows protected your PC" → **More info → Run anyway**.
- The Apple Silicon build and the Windows installer have had limited testing. Please report problems via Issues.

## Privacy
Your CV is stored on your device unless you choose to put it online. The app reports to your administrator: device name, system, app version, local-AI status and basic activity (for example "app started", "CV put online"). It does not send your CV content for this.

## Licence
[MIT](LICENSE) — for the files in this repository.
