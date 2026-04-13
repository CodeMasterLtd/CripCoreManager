# 🚓 CripCore Manager

A modern manager for **Grand Theft Auto V + LSPDFR** to safely manage mods, plugins, scripts, and profiles.

---

## ✨ Features

### 🔁 Profile Switching
- Instantly switch between:
  - Game Build 1 setup  
  - Game Build 2 setup  
  - Game Build Dev setup  
- Keeps all mod setups completely separate  
- Uses fast folder linking (no manual copying)

---

### 🧩 Plugin & Script Management
- Enable / Disable plugins and scripts with one click  
- No need to manually rename `.dll` or `.asi` files  
- Visual status:
  - 🟢 Enabled  
  - 🔴 Disabled  

---

### 💾 Backup & Restore System
- Backup critical game files:
  - `GTA5.exe`
  - `GTAVLauncher.exe`
  - `GTAVLanguageSelect.exe`
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
│   ├── Game Build 1/
│   │   ├── mods/
│   │   ├── plugins/
│   │   ├── scripts/
│   │   ├── ELS/
│   │   └── lspdfr/
│   ├── Game Build 2/
│   │   ├── mods/
│   │   ├── plugins/
│   │   ├── scripts/
│   │   ├── ELS/
│   │   └── lspdfr/
│   ├── Game Build Dev/
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
   into a profile folder (**Game Build 1** / **Game Build 2** **Game Build Dev**) located in `CripCore_Profiles`  

4. Remove them from the main GTA directory 
Do not change profile's unless you have done all the above... If you failed to do so. Don't come at me.. Your fault you lost your files. No going back now. Start again. 

---

### 🔁 Switching Profiles
1. Open CripCore  
2. Click **Game Build 1** or **Game Build 2** or **Game Build Dev** 
3. Mods and other files are swapped instantly  

---

### 🧩 Managing Plugins & Scripts
- Go to **Plugins** or **Scripts** tab  
- Click to toggle:
  - Enabled = 🟢  
  - Disabled = 🔴  

---

### 💾 Creating a Backup
1. Enter a backup name or choose one 
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

- Full mod manager UI  
- Update enhancements
- Much more, but feel free to suggest 

---

## 👨‍💻 Author

**Smurfy**  
Crip Developments 🚀  
https://discord.gg/85yyacGGEh

---
