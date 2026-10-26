# Dotboard

A split flap, dot matrix board for your screen: world clocks, a big clock, a countdown with year progress, and your own rotating sign. Eight color themes, four sizes, full screen mode.

Every character is drawn as a glowing 5×7 dot grid and flips like an airport departures board when it changes.

## Use it as an app

* **Mac:** open the site in Safari, then **File › Add to Dock**.
* **iPhone / iPad:** open it in Safari, then **Share › Add to Home Screen**.

Settings (cities, countdown, messages, theme) are stored on each device in the browser. Nothing is sent anywhere.

## Run locally

It is plain HTML, CSS and JavaScript with no build step:

```
python3 -m http.server 8000
```

then open http://localhost:8000.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | App name, colors and icons for installing |
| `sw.js` | Service worker so it keeps working offline |
| `icon-*.png` | App icons |
