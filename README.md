# SLD-Launcher
 A car-focused Android launcher for head units and Android Automotive. A neon or simple dashboard with a live road animation that moves at your real speed, a full-screen app popout page, Glass and Classic styles with themes and full colour customisation, casting, and built-in updates.


A home screen for Android head units and Android Automotive cars, plus **SLD Companion**, its
phone app. The launcher gives you a neon dashboard with a road animation that moves at your real
speed, a file manager, a popout page for apps like Google Maps, casting, and the Streaming deck.
The companion streams your phone's screen to the car (or your phone's desktop, where supported),
keeps both apps looking the same, shows your phone's notifications on the car, sends files and
updates the head unit over the network. Everything between the phone and the car is encrypted,
and only phones you've paired can connect.

<img width="1057" height="489" alt="Screenshot 2026-11-10 012021" src="https://github.com/user-attachments/assets/b0c256f6-baa7-4057-b229-e39f1dc9a7df" />
<img width="1047" height="472" alt="Screenshot 2026-11-10 012301" src="https://github.com/user-attachments/assets/cad77023-b7fc-4803-b35d-110fb71b7659" />



## Pages

<img width="618" height="299" alt="Screenshot 2026-11-10 012158" src="https://github.com/user-attachments/assets/b4e4e866-0a48-4a4f-afb8-b9e1eb5518ff" />


Swipe sideways, or tap the dots in the top bar, to move between pages. Turn any of them off in
**Settings → Pages** (at least one stays on).

<img width="655" height="436" alt="Screenshot 2026-11-10 012327" src="https://github.com/user-attachments/assets/090fb0ec-018d-4ba3-a22a-d52297bb2c76" />


| Page | What's on it |
| --- | --- |
| **Files** (the square dot) | A file manager for the head unit's storage and USB drives |
| **Dashboard** | Road animation, speed and trip, weather and Now Playing |
| **Popout** | Another app, such as Google Maps, in a large window inside the launcher |
| **Streaming deck** | Your phone's screen or desktop, through SLD Companion |

## SLD Launcher features

- **Live dashboard.** An animated neon road with your car on it, moving at your actual speed.
  On Android Automotive the speed comes straight from the car's speedometer; everywhere else it
  comes from GPS. It stops animating when you're parked.
- **Speed, weather and Now Playing cards.** Weather from [Open-Meteo](https://open-meteo.com/)
  (no API key needed); media controls for whatever is playing. Choose mph or km/h and °C or °F
  in **Settings → Measurements**.
- **Trip meter.** The speed card shows this trip's driving time and distance. A new trip starts
  by itself after the car has been parked for 2 hours; long-press the card to reset it.
- **Speed warning.** Set a limit in **Settings → Measurements → Speed warning** and the speed turns
  red, with one soft chime, when you go over it. (It's your own limit: the launcher doesn't know
  the road's speed limit.)
- **Popout page.** Shows an app in a window over the page. It opens only when you press its
  button and closes when you leave the page; press the button again and the app carries on where
  it was. Hold the card to choose a different app.

<img width="1045" height="478" alt="Screenshot 2026-11-10 012101" src="https://github.com/user-attachments/assets/784cd2cb-44fe-4bef-9462-be586f3f240c" />
<img width="1046" height="474" alt="Screenshot 2026-11-10 012315" src="https://github.com/user-attachments/assets/421c5a91-c487-4a3b-a9b4-adc0f3993d67" />
<img width="1045" height="484" alt="Screenshot 2026-11-10 012048" src="https://github.com/user-attachments/assets/535ef8ab-d4e9-4385-b2b7-dee1de72cf05" />

- **Files page.** Browse internal storage, SD cards and USB drives. Open, rename, copy, cut,
  paste and delete files, create folders, and install APKs.

<img width="1044" height="475" alt="Screenshot 2026-11-10 011915" src="https://github.com/user-attachments/assets/435addff-d306-4f7a-b4ab-31f64911b115" />
<img width="1047" height="476" alt="Screenshot 2026-11-10 012306" src="https://github.com/user-attachments/assets/e4ec2628-3131-42e7-a77f-47f0592ff00e" />

- **Streaming deck.** Shows your phone's screen and plays its sound on the head unit. Control
  the phone by touching the picture, with Back, Home and Recents buttons and a full-screen mode.
  With desktop mode, the car gets your phone's own desktop instead, with windows and an app grid.
  Files sent from the phone land in **Downloads › SLD Companion**.

<img width="733" height="331" alt="Screenshot 2026-11-10 053229" src="https://github.com/user-attachments/assets/1e731ec5-df78-407c-9a90-3ee9183b8109" />
<img width="377" height="783" alt="Screenshot 2026-11-10 053215" src="https://github.com/user-attachments/assets/b5e17090-1fa6-474f-b704-91369c904e88" />



- **Phone notifications.** Messages and other alerts from a connected phone pop up as a banner at
  the top for a few seconds. Tap one to close it. Switch them off on the car in
  **Settings → Streaming deck**.
- **Casting.** Apps that cast with DLNA / UPnP (BubbleUPnP, VLC, Plex, Kodi and many gallery and
  music apps) can play videos, music and photos on the head unit. See [Casting](#casting) below.
- **Fits the screen.** The layout adapts to small or short head-unit screens, so the cards and
  buttons always fit.
- **Two styles, light and dark.** *Glass* (translucent cards on a glowing gradient wallpaper) or
  *Classic* (flat cards), each in light and dark mode. The look stays in sync with SLD Companion
  both ways.
- **Themes.** Ready-made themes, each with a light and a dark version, in
  **Settings → Appearance → Themes**. Save your own, use ones saved on a connected phone, and
  share a look as a short **theme code** that anyone can type in to get the same colours.
- **Automatic light/dark.** Switches to light at sunrise and dark at sunset, wherever the car is.
- **Colour customisation.** Tap the brush in the top bar to change the background gradient,
  wallpaper glows, glass tint, accent, date text, road edges, lane markings, the car's glow and
  under-glow, and even the car's paint. Colours are saved separately for light and dark mode.

<img width="620" height="424" alt="Screenshot 2026-11-10 012124" src="https://github.com/user-attachments/assets/c14789e3-8229-4bc2-a6b8-c4b0e419cb7e" />


- **Driving profiles.** **Day**, **Night** and **Passenger** each remember a look, which pages are
  shown and (where the head unit allows it) the volume, and switch them all in one tap. Use
  **Save current setup as…** to store what's on screen in one of them.
- **Built for the car.** Landscape, usable while driving on Android Automotive, a lite mode for
  slower head units, a customisable dock (long-press an app in the drawer to add it), phone and
  music shortcuts, and an app to open automatically on start-up.

<img width="608" height="292" alt="Screenshot 2026-11-10 012212" src="https://github.com/user-attachments/assets/e343f2dd-ac93-4289-a039-3a3ce364be09" />


- **Setup help.** A first-run checklist walks you through the permissions. On head units with
  no settings screen for a permission, the launcher can switch it on itself through USB
  debugging; it asks first, and otherwise shows the command to run.

- **USB debugging tools.** **Settings → USB debugging (ADB)** shows what's on, can turn it on and
  off, and can find hidden developer and factory menus.

  <img width="612" height="402" alt="Screenshot 2026-11-10 012148" src="https://github.com/user-attachments/assets/6162ab27-9320-4389-963e-7de706812b9b" />

- **Updates itself** from GitHub, or from your phone when the car has no internet.

<img width="624" height="253" alt="Screenshot 2026-11-10 012219" src="https://github.com/user-attachments/assets/f53937c6-ded2-41bd-9982-cb6be4ef24dd" />


## SLD Companion features

- **Connect** to the head unit over Wi-Fi or USB tethering. It finds head units automatically, or
  you can type the address. The first time, you pair the two with a 6-digit code (see
  [Security](#security)).
- **Stays connected** in the background, with a quiet notification, until you tap
  **Disconnect**.
- **Connect automatically** when the car is near. Pair the car's Bluetooth once (Android 12+) and
  the companion connects by itself whenever the phone connects to the car; without it, a
  "car is nearby" notification offers to connect.
- **Home-screen widget** with the connection status, Connect / Disconnect, the Streaming deck and
  Appearance.
- **Mirror** your phone's screen and sound when you choose, with optional touch control from the
  car's screen.
- **Desktop mode.** Your phone's desktop on the car's screen, with its own windows, separate from
  what's on the phone, plus the phone as a trackpad and keyboard. Needs Android 16 or newer and a
  phone that supports it; the companion checks and tells you if yours doesn't.
- **Notifications on the car.** Switch on **Show notifications on the car** and your messages pop
  up on the head unit while connected. Silent and private notifications stay on the phone.
- **Send to car.** Share a link to SLD Companion and choose **Send to car**: videos and music play
  on the head unit, and YouTube and web pages open in their app there.
- **Same look as the launcher.** Change the style, light/dark mode, theme or colours on either
  side and the other follows. The **Appearance** screen has the themes, theme codes, automatic
  light/dark, a theme made from one of your photos, and a wallpaper photo that's sent to the car.
- **Send files** to the head unit over the network, mirroring or not, or share them to SLD
  Companion from any app.

  <img width="405" height="875" alt="Screenshot 2026-11-10 013038" src="https://github.com/user-attachments/assets/09ebb57d-7736-4236-9179-8be0874d5ff5" />

- **Update the head unit** from your phone: it downloads the latest SLD Launcher and sends it over
  the network, so the car doesn't need internet. The Updates card shows which launcher version
  the head unit has.
- **Command Center:** one-tap setup of the launcher's permissions, screenshots, an app manager,
  logs and a terminal, all over the head unit's ADB.
- **Updates itself** from the same GitHub releases.

## Security

- **Pairing.** A phone can only connect to a head unit it has been paired with. The first time you
  tap **Connect**, both screens show the same 6-digit code; check they match and confirm on both.
  After that the phone connects straight in. Remove paired phones on the head unit in
  **Settings → Streaming deck**.
- **Encrypted.** Everything between the phone and the car (settings, files, notifications and the
  mirrored screen and sound) is encrypted with TLS. Each device has its own key, kept in Android's
  secure key store.
- **Update both apps together.** SLD Launcher and SLD Companion 1.6 and newer only connect to each
  other. An older companion is asked to update, and an older launcher shows as "too old".
- **Casting** is limited to connected, paired phones by default (see [Casting](#casting)).

## Requirements

| | SLD Launcher | SLD Companion |
| --- | --- | --- |
| Android | 7.0 (API 24) or newer | 10 (API 29) or newer |
| Tested on | Android 10, Android 15 (Automotive), Android 17 | Android 17 |
| Screen | Landscape (head units; tablets work too) | Any phone |
| Desktop mode | | Android 16 or newer, on phones that support it |

The popout page also needs freeform windows switched on (see below).

## Installing

Download both apps from the latest [release](https://github.com/S1lentD3v/SLD-Launcher/releases):

- **SLD-Launcher-*version*.apk** for the head unit. Install it, then choose **SLD Launcher** as the
  home app when Android asks (or in **Settings → Apps → Default apps → Home app**).
- **SLD-Companion-*version*.apk** for your phone.

## Setting up

### Popout page

The popout page shows another app in a window, which needs Android's **freeform windows**
feature. Most head units have it switched off, so enable it once with
[adb](https://developer.android.com/tools/adb):

```sh
adb shell settings put global enable_freeform_support 1
adb reboot
```

The reboot is required; Android only reads this setting at start-up. Without it, the popout app
opens full screen.

**Rounded corners** on the popout window need *Display over other apps*. The setup checklist asks
for it; on Android Automotive, which has no settings screen for it, the launcher offers to switch
it on through USB debugging, or you can run:

```sh
adb shell appops set com.silentsoftware.carlauncher SYSTEM_ALERT_WINDOW allow
```

### Files page

The Files page needs **All files access** (Android 11 and newer) or the storage permission
(older). Where there's no settings screen for it (Android Automotive), the launcher offers to
switch it on through USB debugging, or you can run:

```sh
adb shell appops set com.silentsoftware.carlauncher MANAGE_EXTERNAL_STORAGE allow
```

### Streaming deck

1. Put the phone and head unit on the same Wi-Fi, or connect them by USB with **USB tethering**
   on.
2. Open SLD Companion, pick your head unit (or enter its address) and tap **Connect**.
3. The first time, both screens show a 6-digit code. Check they match and confirm on both.
4. Open the **Streaming deck**, choose **Phone screen** and tap **Start mirroring**, then accept
   Android's screen-sharing prompt. Or choose **Desktop (beta)**.

Options:

- **Touch control** (in the companion) lets you control the phone from the car. It's switched on
  once in the phone's Accessibility settings.
- **Sound** plays the phone's audio in the car.
- **Stream settings** set the bitrate, sharpness and frame rate, separately for the phone screen
  and the desktop.
- On the head unit, **Settings → Streaming deck** has an audio delay slider to line the sound up
  with the picture, a high frame rate (60 fps) switch, the phone notifications switch, and the
  list of paired phones.

**Desktop mode** needs a one-time setup with the phone's **Wireless debugging** (Developer
options): tap **Set up** on the Desktop page and enter the pairing code from the notification.

### Casting

**Settings → Casting** on the head unit:

- **Let apps cast to this head unit (DLNA).** The head unit shows up as
  "SLD Launcher (*model*)" in apps that cast with DLNA / UPnP.
- **Let any device on the network cast.** Off by default: only phones paired with the head unit
  and connected with SLD Companion right now can see it and cast. Turn it on to let anyone on the
  same Wi-Fi or hotspot cast, as DLNA normally works.

Casting never pauses while driving, so passengers can watch.

### Command Center

The Command Center connects to the head unit's ADB over the network, on port 5555. The head unit
must have network ADB on (for example `adb tcpip 5555` from a computer), and shows **Allow USB
debugging?** the first time. (Wireless debugging pairing is used for desktop mode on the phone,
not for the head unit.)

<img width="400" height="858" alt="Screenshot 2026-11-10 013613" src="https://github.com/user-attachments/assets/7a495e33-9721-4f11-9d6e-604e1e8b3b9e" />
<img width="405" height="861" alt="Screenshot 2026-11-10 013624" src="https://github.com/user-attachments/assets/785d614d-637e-43f6-aacb-bbbf7d2ac8dd" />
<img width="403" height="866" alt="Screenshot 2026-11-10 013619" src="https://github.com/user-attachments/assets/cc61844e-2667-4122-bfab-451d663b8bca" />
<img width="408" height="865" alt="Screenshot 2026-11-10 013730" src="https://github.com/user-attachments/assets/20c5d90a-0db9-4662-8555-0e705272e5bf" />




## Android Automotive

- The car's own speed is used when you allow the **car speed** permission (asked alongside
  location).
- The launcher is marked as safe to use while driving.
- Android Automotive keeps its own system bar (with climate controls) at the bottom; the launcher
  works alongside it.
- The car sets the volume itself, so driving profiles keep only the look and pages there.
- Production cars usually only allow apps from Google Play, so sideloading may not be possible on
  them. Aftermarket head units are fine.

## Updates

Both apps update themselves from [GitHub Releases](https://github.com/S1lentD3v/SLD-Launcher/releases).

- **SLD Launcher** checks about once a day. When there's a newer version, an update button
  appears in the top bar; tap it, then **Update now**. Updates only install while the car is
  parked, and **Settings → Updates** lets you check manually or install automatically when parked.
- **Head units without internet:** SLD Companion shows when the head unit is behind and can send
  it the update over the network. The head unit asks first and checks it like any other update.
- **SLD Companion** checks for its own updates; use **Check for updates** on its Updates card.

The first update asks you to allow **Install unknown apps** and to confirm the install. Every
download is checked against its SHA-256 and the app's signing key before it's installed.

## Permissions

Everything is optional except where noted. If you skip a permission, only the feature that
needs it stops working.

### SLD Launcher (head unit)

| Permission | What it's for |
| --- | --- |
| **Location** (precise) | Speed from GPS, the trip meter, local weather, and sunrise and sunset for automatic light/dark |
| **Car speed** (Android Automotive) | Speed from the car's own speedometer instead of GPS |
| **Notification access** | Now Playing: shows and controls whatever music is playing |
| **All files access** (Android 11+) / **Storage** (older) | The Files page |
| **Display over other apps** | Rounded corners on the popout window |
| **Install unknown apps** | Installing launcher updates, and APKs from the Files page or sent from your phone |
| **Home app** (default launcher) | Makes SLD Launcher your home screen |
| Internet, network state | Weather, casting and update checks |
| Local network | Lets SLD Companion find and connect to the head unit (asked on Android 17+) |
| Wi-Fi multicast | Letting casting apps find the head unit |
| See all apps | The app drawer, the dock, and finding hidden developer and factory menus |
| Close background apps, reorder tasks | Tucking the popout app away when you leave its page |
| Change secure settings (optional) | The USB debugging switch in **Settings → USB debugging**. Only granted if you allow it there |

On head units with no settings screen for a permission (Android Automotive, for example), the
launcher can switch it on itself through USB debugging. It always asks first, and otherwise
shows the command to run.

### SLD Companion (phone)

| Permission | What it's for |
| --- | --- |
| **Screen capture** (asked each time) | Phone screen mirroring |
| **Microphone** (record audio) | Sending your phone's sound to the car. Only app audio is captured, never the microphone |
| **Notifications** | The connection and mirroring notifications, "car is nearby", and entering the pairing code for desktop mode |
| **Notification access** (optional) | Notifications on the car. Only used while that switch is on |
| **Accessibility** (Touch control) | Controlling the phone from the car's screen. Optional; switched on in Accessibility settings |
| **Wireless debugging** (Developer options) | Desktop mode only: a one-time pairing so the companion can create the desktop screen. Android 16+ only |
| **Car Bluetooth** (companion device, Android 12+) | Optional: connecting by itself when the phone connects to the car's Bluetooth |
| **Install unknown apps** | Installing SLD Companion updates |
| Local network, Wi-Fi multicast | Finding head units on your Wi-Fi (local network is asked on Android 17+) |
| Internet, network state | Connecting to the head unit and checking for updates |
| Foreground service | Staying connected, and keeping mirroring and desktop mode running while you use other apps |
| Run at start-up | Re-arming automatic connecting after the phone restarts |

## Project structure

### `app` (SLD Launcher)

| File | What it does |
| --- | --- |
| `MainActivity.kt` | The home screen: pages, cards, dock, app drawer and settings menus |
| `SwipePager.kt` | The swipeable pages |
| `ScreenFit.kt` | Fits the layout to small and short screens |
| `RoadView.kt` | The animated road and car |
| `MapWindow.kt`, `PopoutFrameOverlay.kt` | The popout app window and its rounded corners |
| `MapPanel.kt` | The built-in Google Map |
| `FileExplorer.kt` | The Files page |
| `mirror/MirrorReceiver.kt` | Streaming deck: the secure link and pairing, the phone's screen or desktop, its sound, touch and the app grid |
| `mirror/FileReceiver.kt` | Receiving files and launcher updates from the phone |
| `mirror/MirrorProtocol.kt` | The phone ↔ head unit protocol (kept in sync with the companion's copy) |
| `PhoneBanner.kt` | The phone notification banner |
| `cast/Casting.kt`, `cast/DlnaRenderer.kt`, `cast/Scpd.kt` | Casting: the DLNA renderer, and who's allowed to cast |
| `cast/CastPlayer.kt`, `cast/CastActivity.kt`, `cast/LinkOpener.kt` | The cast player, its screen, and links sent with Send to car |
| `DrivingProfiles.kt` | Day, Night and Passenger profiles |
| `TripMeter.kt` | The trip time and distance on the speed card |
| `AppRepository.kt`, `AppGridAdapter.kt`, `Shortcut.kt` | The app drawer and the dock |
| `MediaMonitor.kt`, `MediaListenerService.kt` | Now Playing |
| `VehicleSpeed.kt`, `LocationTracker.kt` | Car speed and GPS |
| `WeatherRepository.kt` | Weather from Open-Meteo |
| `Theming.kt`, `Glass.kt` | Styles and colour customisation |
| `Prefs.kt` | Saved settings |
| `Updater.kt`, `UpdatedReceiver.kt` | Self-updates from GitHub |
| `SpecialAccess.kt`, `SelfAdb.kt` | Switching permissions on through USB debugging |
| `DevOptionsFinder.kt` | Finding hidden developer and factory menus |

### `companion` (SLD Companion)

| File | What it does |
| --- | --- |
| `MainActivity.kt` | The main screen |
| `HeadUnitLink.kt` | The live, encrypted connection to the head unit, and pairing |
| `LinkService.kt`, `LinkWidget.kt` | Staying connected in the background, and the home-screen widget |
| `AutoConnect.kt`, `CarBluetooth.kt` | Connecting automatically when the car is near |
| `CarNotifications.kt` | Notifications on the car |
| `StreamingActivity.kt`, `StreamSettings.kt` | The Streaming deck screen and each mode's stream settings |
| `MirrorService.kt` | Streaming to the car: screen and sound capture, the video encoder, reconnects |
| `TouchService.kt` | Touch control from the car's screen |
| `TrackpadActivity.kt` | The phone as a trackpad and keyboard for desktop mode |
| `desktop/DesktopServer.java` | Desktop mode's helper: creates the desktop screen, encodes it, and passes on touches and sound |
| `desktop/DesktopAccess.kt`, `desktop/DesktopPairing.kt` | Wireless debugging pairing, and starting the helper |
| `desktop/DesktopSupport.kt` | Checks whether the phone can run desktop mode |
| `desktop/DesktopApps.kt` | The phone's apps, for the app grid on the car |
| `MirrorProtocol.kt` | The phone ↔ head unit protocol (kept in sync with the launcher's copy) |
| `cast/SendToCarActivity.kt` | Send to car |
| `LinkFiles.kt`, `ShareActivity.kt` | Sending files |
| `LauncherUpdate.kt`, `Updater.kt` | Updating the head unit, and itself |
| `AdbActivity.kt`, `Adb*Panel.kt` | The Command Center: setup, actions, apps and terminal tabs |
| `AppearanceActivity.kt` | The Appearance screen |
| `Look.kt`, `CardPager.kt` | Applies the shared look; swipeable cards |

### `style`

The look both apps share, and the secure link:

| File | What it does |
| --- | --- |
| `Glass.kt` | Glass drawables and dialogs |
| `Appearance.kt` | The appearance store both apps keep in sync |
| `ThemePresets.kt`, `ThemeCode.kt`, `SavedThemes.kt` | Ready-made themes, theme codes, and saved themes |
| `PhotoTheme.kt`, `Wallpaper.kt` | A theme from a photo, and the wallpaper photo |
| `SunTimes.kt` | Sunrise and sunset for automatic light/dark |
| `ColorPicker.kt` | The colour picker |
| `SecureLink.kt` | Device keys, TLS and the pairing code |

### `Betas`

`phone-desktop-mode` is a prototype that shows a phone's desktop mode on the launcher's
streaming page.
