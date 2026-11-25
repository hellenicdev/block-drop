# Block Drop

[![Live demo](https://img.shields.io/badge/demo-live-19336e?style=flat-square)](https://hellenicdev.eu/block-drop/) [![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

A simple falling-blocks puzzle game inspired by Tetris, playable in the browser.

**Play it live:** <https://hellenicdev.eu/block-drop/>

## Features

- Classic falling-block gameplay with line clears, score and next-piece preview
- Keyboard and touch controls, with a full-screen layout on mobile
- Multi-language interface (language switcher in the footer)
- No sign-up, no install: it runs entirely in the browser

## How to play

- Move with the arrow keys (or the on-screen buttons on mobile)
- Rotate pieces to fill complete rows
- Full rows clear and earn points; the game ends when the stack reaches the top

## Run locally

The game ships as a pre-built bundle, so there is no build step. Serve the folder with any static server:

```sh
git clone https://github.com/hellenicdev/block-drop.git
cd block-drop
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Tech

- React 19 (pre-built production bundle in `script.js`)
- Tailwind CSS
- Vanilla CSS for layout tweaks (`style.css`)

## License

MIT. See [LICENSE](LICENSE).

## Credits

Made by [HellenicDev](https://hellenicdev.eu). More projects at <https://hellenicdev.eu>.

If you enjoy it, you can support the work here:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S31XB030)
