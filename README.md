# Speed Timer

A countdown timer that looks and works like a normal timer app, with a hidden control that runs it faster, from 1× up to 100,000×. Made for filming time-lapse style shots of a timer.

**Try it:** https://rohitboora05.github.io/timer/ (or scan the QR code with your phone camera)

<img src="qr.png" alt="QR code for the Speed Timer link" width="260">

`https://rohitboora05.github.io/timer/`

Nothing to install and no account needed. It runs in the browser on iPhone, iPad, Android and computers, and keeps working offline after the first visit.

## Install it like an app (optional)

| Device | Steps |
|---|---|
| iPhone / iPad | Open the link in Safari → Share → Add to Home Screen → Add |
| Android | Open the link in Chrome → ⋮ menu → Install app (or Add to Home screen) |

Opened from the Home Screen, it runs without the browser toolbar. On Android it opens fully full screen.

## How to use

1. Scroll the wheels to set hours, minutes and seconds, then tap **Start**.
2. **Pause**, **Resume** and **Cancel** work like any timer.
3. **Hidden speed controls:** double-tap the **Stopwatch** button at the bottom. (A single tap does nothing.)
   - **Speed:** type a number, drag the slider, or tap a preset (1× to 100,000×).
   - **Auto speed:** for example "Pass 8 h 0 m in 4 s", then **Set**. It works out the speed for you.
   - **Speed ramp:** starts at 1× and eases up to your speed (2 s by default), so it looks natural on camera.
   - Tap **Done** or outside the panel to hide it. Nothing is left on screen.
4. **Full screen in the browser:** tap the corner-arrows button at the top left. It only appears where the browser supports it; on iPhone use Add to Home Screen instead.

Keyboard (computer, or iPad with a keyboard): **Space** start/pause, **Esc** cancel, **F** full screen.

Speed and settings are remembered on each device.

## Recording tips

- Use the device's built-in screen recording.
- iPhone / iPad: turn off Low Power Mode, which limits Safari to 30 frames per second. The status bar (clock, battery) stays visible in web apps, so crop it in your editor.
- Android: full screen hides the status bar and navigation bar.
- The screen stays awake while a timer is showing (on iPhone/iPad from the Home Screen this needs iOS/iPadOS 18.4 or later).

## Publish your own copy

1. Create a public GitHub repository, for example `timer`.
2. Upload all the files from this folder.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After about a minute your link is `https://<your-username>.github.io/<repository>/`. Replace `qr.png` with a QR code for your link.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app (HTML, CSS and JavaScript in one file) |
| `manifest.webmanifest` | Name, icon and full-screen settings for Add to Home Screen |
| `sw.js` | Offline support |
| `icon-180.png`, `icon-192.png`, `icon-512.png` | App icons |
| `qr.png` | QR code for the live link |
| `TESTING.md` | Checklist for testers |

## License

MIT. See [LICENSE](LICENSE).
