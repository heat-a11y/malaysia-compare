# malaysia-compare — Bossku punya comparison app

Interactive, side-by-side comparisons of everything Malaysian — from insurance and careers to government initiatives and Bitcoin. Built with ❤️ and a side of Teh Tarik.

![demo](https://img.shields.io/badge/status-live-brightgreen)
![platform](https://img.shields.io/badge/platform-web%20%7C%20android-blue)

## 📱 Get the App

- **Web**: Open `index.html` in any browser
- **Android**: Download the [latest APK](https://github.com/heat-a11y/malaysia-compare/releases)

## 🧩 Modules

| Module | What it does |
|--------|-------------|
| 🛡️ **PERKESO vs Private Insurance** | Pros/Cons toggle + interactive "Which One Do I Need?" calculator |
| 🏛️ **Gov vs Private Sector** | "Choose Your Character" career showdown with animated stat bars |
| 📋 **Government Initiatives** | Report card for My50, JENDELA, PADU, etc. with Rakyat Rating voting |
| ₿ **Fiat vs Bitcoin** | Financial dashboard + inflation calculator (10-year Nasi Lemak price projection) |

## 🎨 Features

- **Light/Dark mode** — Siang / Malam toggle, persisted in localStorage
- **Teh Tarik FAB** — Click the coffee button for a virtual pour + random Malaysian fact
- **Manglish quotes** — Kopitiam chatter cycling in the sidebar
- **Scroll-triggered animations** — Cards reveal as you scroll
- **Fully responsive** — Works on mobile, tablet, and desktop

## 🛠️ Tech Stack

- **HTML + Tailwind CSS** (via CDN) — Styling
- **Lucide Icons** — Iconography
- **Vanilla JavaScript** — All interactivity, no frameworks
- **Android WebView** — APK wrapper (Java + Gradle)

## 🐛 Local Development

Just open `index.html` in a browser — no build step needed.

### Android Build

```bash
cd android
export JAVA_HOME=/path/to/jdk-17
export ANDROID_HOME=/path/to/android-sdk
./gradlew assembleDebug
```

APK output: `android/app/build/outputs/apk/debug/app-debug.apk`

## 📄 License

MIT — Use freely, Bossku. Jangan marah kalau ada silap.
