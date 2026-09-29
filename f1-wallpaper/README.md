# F1 Live Wallpaper for macOS

An animated F1 night-race wallpaper: spinning wheels, sparks off the plank, a blinking rain light, and a parallax city with floodlights. It's a single HTML file (`index.html`) with no dependencies.

## Set it as your Mac wallpaper (free, using Plash)

macOS can't use a custom animated wallpaper on its own, so this uses **Plash**, a free, open-source app that shows a web page as your desktop wallpaper.

1. Download `index.html` from this folder to your Mac, for example into `~/Pictures/F1/`.
2. Install **Plash** from the Mac App Store (search "Plash", by Sindre Sorhus).
3. Open Plash. Its icon appears in the menu bar. Click it and choose **Add Website…**
4. For the URL, choose the local file (or type `file:///Users/<you>/Pictures/F1/index.html`).
   Add options to the end if you like, for example:
   `file:///Users/<you>/Pictures/F1/index.html?color=orange&number=4&clock=1`
5. Optional: in Plash **Settings**, turn on **Launch at login** and set **Opacity** to 100%.

## Options

| Option   | Values                                                            | Default |
|----------|-------------------------------------------------------------------|---------|
| `color`  | `red`, `orange`, `silver`, `blue`, `green`, `pink`, or a hex like `%23ff0000` | `red`   |
| `number` | Car number (1–2 characters)                                       | `16`    |
| `speed`  | Animation speed (`0.5` is calmer, `2` is faster)                  | `1`     |
| `clock`  | `1` shows a clock and date in the top-right corner                | off     |

## Battery tip

Any animated wallpaper uses some CPU and GPU. In Plash you can turn on **Deactivate while on battery**, or use `speed=0.5`.
