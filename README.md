# Skyreach

An endless vertical jumper that runs in the browser. One HTML file, no build step,
no dependencies, no backend — open it and play.

**Play:** _(deploy link goes here)_

## Running it

Open `index.html` in a browser. That's it.

For a local server (needed on some mobile browsers):

```bash
npx serve .
```

## What's in it

- Canvas game loop with procedural character rendering — every character, hat,
  cape and trail is drawn in code, no image assets
- Zones that cross-fade as you climb, each with its own hazards
- XP, levels, a spark currency, 60+ unlockable cosmetics
- Daily challenges, login streaks and achievements
- Progress saved to `localStorage`, with a versioned migration
- Mobile-first: touch controls, safe-area insets, no zoom

## Status

Preview build. In-app purchases are stubbed and not connected to anything.

## License

MIT
