# Boggle

A very small Boggle web app with a 4x4 grid, a 3-minute timer, and PWA support.

## Live Version

[https://hamaclem.github.io/boggle/](https://hamaclem.github.io/boggle/)

## How To Play

Open the app in a browser and tap `Boggle`.

Then the app will:

- Shuffle all 16 dice exactly once and place them on the grid
- Choose one random side for each die
- Start a 3-minute timer
- Reset the game when the timer ends

## Install On iPhone / iPad

To use it like an app on Apple devices:

1. Open the app in Safari.
2. Tap `Share`.
3. Tap `Add to Home Screen`.

## Files

- [index.html](/Users/hanna/Documents/coding/boggle/index.html): complete app with HTML, CSS, and JavaScript
- [manifest.json](/Users/hanna/Documents/coding/boggle/manifest.json): PWA metadata
- [sw.js](/Users/hanna/Documents/coding/boggle/sw.js): simple service worker for offline caching
