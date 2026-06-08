# Birthday Card

An interactive birthday card built with vanilla HTML, CSS & JavaScript. No frameworks, no dependencies — just open `index.html` and enjoy.

## Features

- **Envelope opening** — tap to reveal the card with a flip animation
- **Constellation** — the recipient's name rendered as twinkling stars on canvas
- **17 Star cards** — each hides a personal reason, tap to flip and discover
- **Typewriter letter** — a love letter typed out character by character
- **Birthday cake** — blow out the candles with a tap
- **Balloon mini-game** — pop balloons to reveal wishes
- **Fireworks finale** — canvas-based particle fireworks
- **Background music** — Happy Birthday melody via Web Audio API
- **Sakura petals & sparkle trail** — ambient floating effects
- **Easter eggs** — long-press the name for confetti, shake device for surprises

## Customization

Edit the `CONFIG` object at the top of `birthday.js`:

```js
const CONFIG = {
  name: "Em Yêu",           // Recipient name
  signature: "...",          // Closing signature
  candleCount: 5,            // Number of candles
  reasons: [...],            // Star card messages
  letterLines: [...],        // Typewriter letter content
  balloonWishes: [...]       // Balloon pop messages
};
```

## Usage

Open `index.html` in a browser, or deploy to GitHub Pages:

```
Settings → Pages → Source: main branch → Save
```

Then visit `https://<username>.github.io/birthday-card/`

## Tech

Vanilla JS with canvas animations, Web Audio API, IntersectionObserver, and Web Animations API. Optimized with a single `requestAnimationFrame` loop, Page Visibility API pause, resize debouncing, and CSS containment.

## License

MIT
