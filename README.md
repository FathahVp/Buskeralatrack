# 🚌 BusTrack Kerala — APK Build Guide

## Step 1: GitHub-ൽ Repository ഉണ്ടാക്കുക

1. **github.com** → Login
2. **"New repository"** button click ചെയ്യുക
3. Repository name: `bustrack-kerala`
4. **Public** select ചെയ്യുക (free build-ന്)
5. **"Create repository"** click ചെയ്യുക

---

## Step 2: Files Upload ചെയ്യുക

Repository page-ൽ **"uploading an existing file"** link click ചെയ്യുക.

ഈ folder structure upload ചെയ്യുക:
```
bustrack_kerala/
├── .github/
│   └── workflows/
│       └── build.yml        ← ⭐ IMPORTANT
├── lib/
│   ├── main.dart
│   ├── models/
│   │   └── route_model.dart
│   ├── providers/
│   │   └── bus_provider.dart
│   ├── screens/
│   │   ├── home_screen.dart
│   │   ├── passenger_screen.dart
│   │   ├── driver_screen.dart
│   │   ├── cell_tower_screen.dart
│   │   └── crowdsource_screen.dart
│   └── widgets/
│       ├── route_map_widget.dart
│       └── search_bar_widget.dart
├── android/
│   └── app/
│       └── src/main/
│           └── AndroidManifest.xml
└── pubspec.yaml
```

> **Tip:** Drag & drop ആണ് ഏറ്റവും easy

---

## Step 3: Build Start ആകും (Automatic!)

Files upload ആയ ഉടൻ:
1. GitHub → **"Actions"** tab click ചെയ്യുക
2. **"Build BusTrack Kerala APK"** workflow കാണാം
3. Yellow circle = building ⏳
4. Green tick = done ✅ (5–10 minutes)

---

## Step 4: APK Download ചെയ്യുക

1. Actions tab → Latest run click ചെയ്യുക
2. Page bottom-ൽ **"Artifacts"** section
3. **"bustrack-kerala-release"** download ചെയ്യുക
4. ZIP extract ചെയ്യുക → **app-release.apk** കിട്ടും!

---

## Step 5: Phone-ൽ Install ചെയ്യുക

1. APK file phone-ലേക്ക് copy ചെയ്യുക
2. Phone Settings → **"Install unknown apps"** enable ചെയ്യുക
3. APK file tap ചെയ്ത് install ചെയ്യുക

---

## ⚠️ Build Error വന്നാൽ

Actions tab-ൽ red X കണ്ടാൽ → Click ചെയ്ത് error message copy ചെയ്ത് share ചെയ്യൂ, fix ചെയ്യാം!

---

## 📱 App Features

| Feature | Description |
|---|---|
| 🔍 Search | Bus number / Route / Stop name |
| 📍 Live Tracker | Real-time bus position |
| 🔔 Alarm | Destination alarm with sound |
| 📡 Cell Tower | Offline triangulation |
| 💾 Offline Mode | Download & use without internet |
| 👥 Community | Crowdsourced reports |

**Routes:** Perinthalmanna → Kozhikode, Palakkad, Thrissur, Ernakulam, Trivandrum, Pala
