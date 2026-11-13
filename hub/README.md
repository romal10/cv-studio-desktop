# CV Studio Apps: downloads

**Download site: https://romal10.github.io/cv-studio-desktop/hub/**

Public download pages for the **CV Studio** apps for Windows, Mac (Apple chip and Intel), iPhone, iPad and Android. The app source code is **private**; this repository only hosts the download pages, the licence of those pages and the release files.

| App | Download page |
|---|---|
| CV Studio: Lebenslauf, Bewerbungen und Karriere | [romal10.github.io/cv-studio-desktop/hub/apps/cv-studio/](https://romal10.github.io/cv-studio-desktop/hub/apps/cv-studio/) |
| Rabta: Chat, Anrufe und Meetings | [romal10.github.io/cv-studio-desktop/hub/apps/rabta/](https://romal10.github.io/cv-studio-desktop/hub/apps/rabta/) |
| Kairos Kalender: Termine und Buchungen | [romal10.github.io/cv-studio-desktop/hub/apps/kairos/](https://romal10.github.io/cv-studio-desktop/hub/apps/kairos/) |
| FRISO Salon: Salon-App für Friseure | [romal10.github.io/cv-studio-desktop/hub/apps/friso/](https://romal10.github.io/cv-studio-desktop/hub/apps/friso/) |
| AROS Restaurant: Restaurant OS | [romal10.github.io/cv-studio-desktop/hub/apps/aros/](https://romal10.github.io/cv-studio-desktop/hub/apps/aros/) |
| EVENTO Events: Veranstalter-App | [romal10.github.io/cv-studio-desktop/hub/apps/evento/](https://romal10.github.io/cv-studio-desktop/hub/apps/evento/) |
| CV Studio Shop: Shop für Geschäftskunden | [romal10.github.io/cv-studio-desktop/hub/apps/shop/](https://romal10.github.io/cv-studio-desktop/hub/apps/shop/) |
| CV Studio Berater: Portal für Karriereberater | [romal10.github.io/cv-studio-desktop/hub/apps/consultant/](https://romal10.github.io/cv-studio-desktop/hub/apps/consultant/) |
| CV Studio Unternehmen: Portal für Unternehmen | [romal10.github.io/cv-studio-desktop/hub/apps/company/](https://romal10.github.io/cv-studio-desktop/hub/apps/company/) |
| Steuer-Assistant | [romal10.github.io/steuer-assistant-download](https://romal10.github.io/steuer-assistant-download/) |

## Files
Each app has its own release, tagged `<app>-v<version>` (for example `rabta-v0.2.0`), with a Windows installer, a Mac DMG for Apple Silicon, a Mac DMG for Intel and `SHA256SUMS.txt`. Check your download against the checksums on the release page.

## First launch: the builds are not signed yet
- **Mac (macOS 15 and newer):** open the app once, click *Done* on the warning, then System Settings → Privacy & Security → *Open Anyway*. Shortcut: `xattr -dr com.apple.quarantine "/Applications/<App>.app"`
- **Mac (macOS 14 and older):** right-click the app → *Open* → *Open*.
- **Windows:** SmartScreen shows "Windows protected your PC" → *More info* → *Run anyway*.
- Requires macOS 11 or newer, Windows 10/11 (64-bit).

## Phones and tablets
Open the app in the browser and install it: iPhone/iPad in Safari via Share → *Add to Home Screen*, Android in Chrome via *Install app*.

## Local AI
On Windows and Mac the apps can set up a free local AI (Ollama) on request. It is not available on iPhone, iPad and Android.
