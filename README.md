# CV Studio Apps: downloads

**Download site: https://romal10.github.io/cv-studio-desktop/**

Public download pages for the **CV Studio** apps for Windows, Mac (Apple chip and Intel), iPhone, iPad and Android. The app source code is **private**; this repository only hosts the download pages, the licence of those pages and the release files.

| App | Download page |
|---|---|
| CV Studio: Lebenslauf, Bewerbungen und Karriere | [romal10.github.io/cv-studio-desktop/apps/cv-studio/](https://romal10.github.io/cv-studio-desktop/apps/cv-studio/) |
| Rabta: Chat, Anrufe und Meetings | [romal10.github.io/cv-studio-desktop/apps/rabta/](https://romal10.github.io/cv-studio-desktop/apps/rabta/) |
| Kairos Kalender: Termine und Buchungen | [romal10.github.io/cv-studio-desktop/apps/kairos/](https://romal10.github.io/cv-studio-desktop/apps/kairos/) |
| FRISO Salon: Salon-App für Friseure | [romal10.github.io/cv-studio-desktop/apps/friso/](https://romal10.github.io/cv-studio-desktop/apps/friso/) |
| AROS Restaurant: Restaurant OS | [romal10.github.io/cv-studio-desktop/apps/aros/](https://romal10.github.io/cv-studio-desktop/apps/aros/) |
| EVENTO Events: Veranstalter-App | [romal10.github.io/cv-studio-desktop/apps/evento/](https://romal10.github.io/cv-studio-desktop/apps/evento/) |
| CV Studio Shop: Shop für Geschäftskunden | [romal10.github.io/cv-studio-desktop/apps/shop/](https://romal10.github.io/cv-studio-desktop/apps/shop/) |
| CV Studio Berater: Portal für Karriereberater | [romal10.github.io/cv-studio-desktop/apps/consultant/](https://romal10.github.io/cv-studio-desktop/apps/consultant/) |
| CV Studio Unternehmen: Portal für Unternehmen | [romal10.github.io/cv-studio-desktop/apps/company/](https://romal10.github.io/cv-studio-desktop/apps/company/) |
| Steuer-Assistant | [romal10.github.io/steuer-assistant-download](https://romal10.github.io/steuer-assistant-download/) |

## Files
Each app has its own release, tagged `<app>-v<version>` (for example `rabta-v0.2.0`), with a Windows installer, a Mac DMG for Apple Silicon, a Mac DMG for Intel and `SHA256SUMS.txt`. Check your download against the checksums on the release page.

## First launch: the builds are not signed yet
- **Mac (macOS 15 and newer):** open the app once, click *Done* on the warning, then System Settings → Privacy & Security → *Open Anyway*. Shortcut: `xattr -dr com.apple.quarantine "/Applications/<App>.app"`
- **Mac (macOS 14 and older):** right-click the app → *Open* → *Open*.
- **Windows:** SmartScreen shows "Windows protected your PC" → *More info* → *Run anyway*.
- Requires macOS 11 or newer, Windows 10/11 (64-bit).

## Phones and tablets
Android: APKs of the Flutter apps (one per app, plus the CV Studio hub app). The open-source app shell is at [romal10/cv-studio-mobile](https://github.com/romal10/cv-studio-mobile). iPhone/iPad: open the app in the browser and install it: iPhone/iPad in Safari via Share → *Add to Home Screen*, Android in Chrome via *Install app*.

## Local AI
On Windows and Mac the apps can set up a free local AI (Ollama) on request. It is not available on iPhone, iPad and Android.
