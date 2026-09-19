# Phone Mouse — Downloads

Use your Android phone as a trackpad for your Windows laptop, over the USB cable.

No Wi-Fi, no Bluetooth, no account, no internet connection.

**[Visit the website →](https://anshthakur0999.github.io/Phone-Mouse-Releases/)** · **[Download the latest release →](https://github.com/anshthakur0999/Phone-Mouse-Releases/releases/latest)**

| Download | For |
|---|---|
| `PhoneMouse-1.0.0.apk` | Your Android phone (8.0 or newer) |
| `PhoneMouseSetup-1.0.0.exe` | Your Windows laptop (10 or 11, 64-bit) |

You need both — the phone app and the Windows companion.

---

## Setup

### 1. Install the Windows app

Run `PhoneMouseSetup-1.0.0.exe`. It runs in your system tray; there's no window.

The installer is not code-signed, so Windows SmartScreen may warn you.
Click *More info → Run anyway*.

### 2. Turn on USB debugging on your phone

1. **Settings → About phone**
2. Tap **Build number** seven times until you see "You are now a developer"
   - On Xiaomi/Redmi/POCO: **Settings → About phone → MIUI version**
3. **Settings → System → Developer options**
   - On Xiaomi/Redmi/POCO: **Settings → Additional settings → Developer options**
4. Turn on **USB debugging**
5. On Xiaomi/Redmi/POCO, also turn on **Install via USB**

### 3. Install the phone app

Copy `PhoneMouse-1.0.0.apk` to your phone and open it. Your phone will ask you to
allow installing from this source — expected for an app outside the Play Store.

---

## Using it

1. Plug your phone into your laptop with the USB cable
2. If your phone shows **"Allow USB debugging?"**, tick *Always allow from this
   computer* and tap **Allow**
3. Open **Phone Mouse** on your phone

When all three checklist items are green, tap **Start using as mouse**.

| Gesture | Result |
|---|---|
| Drag one finger | Move the cursor |
| Tap | Left click |
| Two-finger tap | Right click |
| Two-finger drag | Scroll |

---

## Troubleshooting

**The checklist never goes all green.** Most often a charge-only USB cable — many
cheap cables carry no data. Try a different one.

**Connected, but the cursor doesn't move.** Close and reopen the phone app. If that
fails, right-click the tray icon → **Exit** and relaunch from the Start Menu.

**Scrolling doesn't work in one window.** Turn on **Settings → Bluetooth & devices →
Mouse → Scroll inactive windows when hovering over them**.

**Cursor too fast or slow.** Adjust **Pointer speed** in the app's Settings.

---

## Privacy

Phone Mouse sends nothing anywhere. No account, no telemetry, no internet connection
at any point. The only data crossing the cable is cursor movements and clicks.

---

## Known limitations

- Windows only, USB only, one phone at a time
- Vertical scrolling only
- The two middle checklist items turn green together — the app can't tell
  "USB debugging is off" apart from "the Windows app isn't running"

---

This repository hosts the downloads and the project page. Found a bug?
[Open an issue](https://github.com/anshthakur0999/Phone-Mouse-Releases/issues).
