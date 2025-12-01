````markdown
# TawRay (TawRayNG)

**TawRay** is a personalized and enhanced Android client based on **v2rayNG**, built to provide a smoother, modern, and user-friendly V2Ray/Xray experience — with upcoming account features and a fresh UI identity.

> Forked & customized from: **v2rayNG by 2dust**

---

## ✨ Features
- V2Ray/Xray client for Android
- Supports:
  - **Xray Core**
  - **v2fly (V2Ray) Core**
- Modern purple-blue theme (TawRay UI)
- Refactored package & app identity:
  - Package name: `com.tawana.tawray`
  - App name: **TawRay**
  - Application class: `TawRayApplication`
- Future roadmap:
  - User registration & account system
  - Panel-based config management
  - Optional cloud sync

---

## 📱 Requirements
- Android **5.0+ (API 21+)**
- Kotlin-based project

---

## 📌 About the Author
Developed and maintained by **Tawana Mohammadi (توانا محمدی)**  
Independent AI researcher, data strategist, and educator focusing on **AI ethics, transparency, and human-centered design**.

- 🌐 Website: **tawana.online**
- ✉️ Contact: **info@tawana.online**
- 🧑‍💻 GitHub: **@tawanamohammadi**
- 🧠 ORCID: **0009-0005-6825-6728**
- 🔍 Research Hub: **Tawana Network – Ethical AI & Data Transparency Research Hub**

> Vision: *Ethics in intelligence, transparency in data.*

---

## 🚀 Usage

### GeoIP & GeoSite
- `geoip.dat` and `geosite.dat` are located in:  
  `Android/data/com.tawana.tawray/files/assets`  
  (path might differ depending on your Android device)
- TawRay can download enhanced rule files from:  
  **v2ray-rules-dat by Loyalsoldier**  
  *(requires a working proxy to fetch)*
- You can manually import:
  - domain list: **v2ray-rules-dat**
  - ip list: **geoip**
- Third-party `.dat` files are supported if placed in the same assets folder.

---

## 📚 Wiki & Documentation
Upstream v2rayNG wiki (still valid for TawRay core behavior):  
- https://github.com/2dust/v2rayNG/wiki

TawRay docs will be added here as features expand.

---

## 🛠️ Development Guide

You can build TawRay with **Gradle Wrapper** (no Android Studio required):

```bash
./gradlew assembleDebug
````

APK output:

```
app/build/outputs/apk/debug/app-debug.apk
```

### About Core AAR

The embedded core AAR may be outdated upstream.
You can rebuild core from:

* [https://github.com/2dust/AndroidLibV2rayLite](https://github.com/2dust/AndroidLibV2rayLite)
* [https://github.com/2dust/AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite)

Recommended reading:

* [https://github.com/golang/go/wiki/Mobile](https://github.com/golang/go/wiki/Mobile)
* [https://tutorialedge.net/golang/makefiles-for-go-developers/](https://tutorialedge.net/golang/makefiles-for-go-developers/)

---

## 🧪 Emulator / WSA Notes

TawRay works on Android emulators.
For WSA (Windows Subsystem for Android), grant VPN permission via:

```bash
appops set com.tawana.tawray ACTIVATE_VPN allow
```

---

## 🙏 Credits

This project is based on the great work of:

* **v2rayNG** by 2dust
* Xray core team
* v2fly core team

---

## 📜 License

Same license as upstream v2rayNG.
See `LICENSE` for details.

```
```
