# mobile-massage

A lightweight web-based mobile massage simulator using the Vibration API.
Adjust total duration, pulse length, rest interval and repeat count. Works best on Android Chrome/Edge/Firefox. iOS Safari does not support `navigator.vibrate`.

## Features
- Adjustable total time, pulse time, rest time and repeats
- Preset modes (gentle / medium / strong / random)
- Remaining time and elapsed time display
- Wake Lock (when supported) to keep screen on during a session
- Pure HTML/CSS/JS, no build step required

## Usage
1. Open `index.html` in a mobile browser (Android recommended).
2. Grant any wake-lock prompt if offered.
3. Press **Start** to begin a session. Use **Stop** to end early.

## Files
- `index.html` — main demo UI and logic using `navigator.vibrate()`.
- `README.md` — this file.
- `LICENSE` — MIT license.

## Development
- No build tool needed. Edit `index.html` directly.
- To test on desktop, open devtools → Sensors → emulate touch + set user agent, but vibration may not run on desktop.

## License
MIT
