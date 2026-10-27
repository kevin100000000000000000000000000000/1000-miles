# 10,000 Miles

A self-contained browser driving + train simulator.

## Run
Open `index.html` in a modern browser, or upload it to GitHub Pages / Netlify / any static host.

No Node.js, npm, build step, Xcode, or external libraries are required.

## iPad controls
- Left circular control: steering
- GAS / BRAKE: right side
- HB: handbrake
- Camera button: cycles Chase / Dashboard / Hood / Cinematic
- Pause: opens Map, Vehicle, Performance, Graphics, Controls, Save, Main Menu
- Optional tilt steering is in Settings and requests motion permission only when enabled.

## Real performance data
The Performance page measures FPS from `requestAnimationFrame`. It only displays device/browser data available through browser APIs. It does not guess the Apple chip, CPU/GPU utilization, device temperature, or other unavailable hardware details.

## Saving
Progress autosaves to `localStorage` every few seconds during play and on visibility changes.
