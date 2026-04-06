# 🚓 CripCore Manager

A modern manager for **Grand Theft Auto V + LSPDFR** to safely manage mods, plugins, scripts, and profiles.

---

## ✨ Features

### 🔁 Profile Switching
- Instantly switch between:
  - 🇬🇧 BRITISH setup  
  - 🇺🇸 AMERICAN setup  
- Keeps all mod setups completely separate  
- Uses fast folder linking (no manual copying)

---

### 🧩 Plugin & Script Management
- Enable / Disable plugins and scripts with one click  
- No need to manually rename `.dll` files  
- Visual status:
  - 🟢 Enabled  
  - 🔴 Disabled  

---

### 💾 Backup & Restore System
- Backup critical game files:
  - `GTA5.exe`
  - `GTAVLauncher.exe`
  - `PlayGTAV.exe`
- Restore instantly if a GTA update breaks your mods  

---

### 🧠 Version Detection
- Reads directly from `versionInfo.txt`
- Displays:
```

GTA Version: v1.0.xxxx.x
Launcher: x.x.x.x

```

---

### 🛡️ Compatibility Check
- Automatically checks if your setup is:
  - ✅ Fully Compatible  
  - ⚠️ Partial  
  - ❌ Not Supported  

---

### 🖥️ Modern UI
- Clean sidebar layout  
- Real-time status updates  
- Simple, user-friendly design  

---

## 📂 Required GTA Structure

```

GTA V/
├── CripCore_Profiles/
│   ├── BRITISH/
│   │   ├── mods/
│   │   ├── plugins/
│   │   ├── scripts/
│   │   ├── ELS/
│   │   └── lspdfr/
│   ├── AMERICAN/
│   │   ├── mods/
│   │   ├── plugins/
│   │   ├── scripts/
│   │   ├── ELS/
│   │   └── lspdfr/
│   └── CripCore_Exported_Profiles/
└── CripCore_VersionBackups/

```

---

## 🚀 How to Use

### 🔧 Setup
1. Run CripCore as **Administrator**
2. The tool create's `CripCore_Profiles`
3. Move your:
   - `mods`
   - `plugins`
   - `scripts`
   - `ELS`
   - `lspdfr`  
   into a profile folder (**BRITISH** or **AMERICAN**) located in `CripCore_Profiles`  

4. Remove them from the main GTA directory  

---

### 🔁 Switching Profiles
1. Open CripCore  
2. Click **BRITISH** or **AMERICAN**  
3. Mods are swapped instantly  

---

### 🧩 Managing Plugins & Scripts
- Go to **Plugins** or **Scripts** tab  
- Click to toggle:
  - Enabled = 🟢  
  - Disabled = 🔴  

---

### 💾 Creating a Backup
1. Enter a backup name  
2. Click **Create Backup**  

---

### ♻️ Restoring a Backup
1. Select a backup  
2. Click restore  
3. Game files are instantly restored  

---

## ⚠️ Notes

- Always run as **Administrator**  
- Keep your main GTA directory clean  
- Backups only include EXE files  
- Recommended to disable GTA auto-updates  

---

## 💡 Future Features

- Plugin conflict detection  
- Full mod manager UI  
- Profile import/export improvements  

---

## 👨‍💻 Author

**Smurfy**  
Crip Developments 🚀  
https://discord.gg/85yyacGGEh

---
