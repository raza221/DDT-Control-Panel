# DDT Control Panel

A modern easy-to-use control panel for Destiny Damage Tracker.  
This application provides an easy-to-use GUI for configuring settings, selecting bosses, and controlling the DDT overlay without interacting directly with AutoHotkey scripts.

---

## Features

- Modern, clean GUI (CustomTkinter)
- System tray support (runs in background)
- Boss selection with automatic engine launch
- Full settings editor with explanations for every option
- Native Windows font picker for overlay font selection
- Close-to-tray behavior (no accidental shutdowns)
- Portable, no installer required

---

**Important:**  
- Do **not** move files out of the `bin` folder.  
- The control panel expects everything except itself to be inside `bin`.

---

## How to Use

### First Launch
1. Extract the DDT folder anywhere on your system.
2. Run **`DDT Control Panel.exe`**.
3. The app will appear and a tray icon will be created.

---

### Selecting a Boss
1. Choose a boss from the dropdown at the top.
2. Click **Start Tracking**.
3. The DDT overlay will appear in Destiny 2 automatically.

This is equivalent to selecting a boss and pressing **OK** in the old AHK GUI.

---

### Stopping or Restarting
- **Stop Engine** – Completely stops the DDT engine.
- **Restart** – Restarts the engine using the currently selected boss.
- **Reload Boss List** – Reloads `boss_health.txt` without restarting the engine.

---

## Settings

All settings are edited directly in the GUI.  
Each option has a **`?` icon** explaining what it does.

### Important Notes
- Settings are saved automatically.
- Some settings (resolution, window layout, font) require an engine restart.
- Use **Restart** after changing settings to ensure they apply correctly.

---

## Tray Icon Behavior

- Closing the window (❌) **minimizes to tray**
- Tray menu options:
  - **Show Control Panel** – Reopens the window
  - **Exit** – Fully closes the control panel and stops the engine

The DDT engine itself does **not** show a tray icon.

---

## Customization

### Changing Overlay Font
- Go to **Display → GUI Text Font**
- Click **Choose…**
- Select any Windows font
- Restart the engine to apply

### Editing Boss Health Values
- Open `bin/boss_health.txt`
- Edit or add bosses as needed
- Click **Reload Boss List** in the GUI

---

## Troubleshooting

### Overlay Not Appearing
- Ensure Destiny 2 is running and in focus
- Confirm the correct resolution settings are enabled
- Restart the engine after changing settings

### Control Panel Won’t Start Engine
- Ensure `bin/DDT.exe` exists
- Do not rename files inside `bin`
- Run the control panel from the same folder as `bin`

---

## Requirements

- Windows 10 / 11
- Destiny 2 (PC)
- No additional installs required (portable)

---

## Credits

**DDT-GUI Made by Raza**

**DDT Updated by ModerNik**

**DDT Made by A2TC**

---

## Disclaimer

This tool is provided as-is for educational and personal use.  
Use at your own discretion.
