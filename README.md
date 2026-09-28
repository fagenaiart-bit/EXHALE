# Exhale

A small app for overthinking. You talk or type in one continuous stream; Exhale splits it into separate thoughts and pulls each one into a breathing sphere. Press **Exhale** and your head is clear. The thoughts are kept, and **What keeps coming back** shows which ones return, how often, and with which mood. No advice, just a mirror.

Flow: mood and body check-in → stream of thoughts → exhale → mood after.

- Ukrainian and English (toggle in the top bar)
- Voice input through the browser's speech recognition (Chrome, Edge, Safari)
- Installs to the home screen and works offline (PWA)
- Everything is stored only on the device, in the browser's local storage

Visual language comes from the PlaNORA prototype: the jade dot-grid sphere, Plus Jakarta Sans and JetBrains Mono.

## Run locally

Any static server works, for example:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
