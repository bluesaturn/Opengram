# Opengram

**Opengram** is a free, fully open-source messaging app for Android, compatible with the [Telegram](https://telegram.org) network.

This project is based on the official [Telegram Android client](https://github.com/DrKLO/Telegram), which is licensed under [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).  
Unlike the original version, Opengram is **completely Google-free** and uses **[UnifiedPush](https://unifiedpush.org/)** for push notifications instead of Firebase Cloud Messaging (FCM).

---

## ✨ Features

- ✅ Fully compatible with Telegram's API and backend
- 🛡️ 100% open-source (GPL-2.0)
- 🚫 No Google Play Services or Firebase dependencies
- 📲 Push notifications via **UnifiedPush**
- ⚙️ Built on **TDLib** (Telegram Database Library)
- 🔄 Actively tracking upstream updates (manual sync with latest Telegram client)

---

## 🚧 Disclaimer

Opengram is **not affiliated with Telegram Messenger LLP**.  
"Telegram" is a registered trademark of its respective owner.

This app is a **community-driven** rebuild of the official Telegram Android client with enhanced privacy goals and Google-free infrastructure.

---

## 📦 Installation

You can install the latest release by downloading the APK from the [Releases](https://github.com/yourusername/opengram/releases) page.  
Every release includes SHA256 checksums for verification.  
You can also use [Obtanium](https://github.com/ImranR98/Obtainium) for automatic updates.

---

## 🧪 UnifiedPush Support

To receive push notifications, Opengram uses the [UnifiedPush protocol](https://unifiedpush.org/).  
You'll need a supported UnifiedPush distributor (e.g. [ntfy](https://github.com/binwiederhier/ntfy), [UP-FCM-distributor](https://github.com/UnifiedPush/FCM-distributor), etc.).

---

## 🛠️ Building

Coming soon. Full build instructions will be documented in the `BUILDING.md` file.

---

## 📄 License

This project is released under the **GNU GPL v2.0**.  
See [LICENSE](LICENSE) for full text.

---

## ❤️ Credits

- [Telegram Android Client](https://github.com/DrKLO/Telegram)
- [UnifiedPush Project](https://unifiedpush.org/)
- [TDLib – Telegram Database Library](https://github.com/tdlib/td)

