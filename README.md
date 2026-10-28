# Transformations – a Capybara game

A puzzle game for practising transformations of functions, aligned to the language of VCE Mathematical Methods.

Transform the blue graph until it lies on the gold target, using translations, dilations and reflections. There are 13 levels, each with 8 problems:

1. Translations parallel to the y-axis
2. Translations parallel to the x-axis
3. Reflections
4. Dilations from the x-axis
5. Dilations from the y-axis
6. Combined transformations
7. Negative factors inside
8. The full form y = A f(n(x + b)) + c
9. Backwards: back to the parent
10. Backwards: inside the function
11. Backwards: graph to graph
12. Read the graph
13. Predict from notation

Instruction is optional on every level.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` | Lets the game be installed as an app |
| `sw.js` | Lets the game run offline |
| `icons/` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publishing on GitHub Pages

1. Create a new **public** repository on GitHub, e.g. `transformations`.
2. Choose **Add file → Upload files** and drag in everything in this folder, including the `icons` folder. Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
4. After a minute or two the game is live at `https://<your-username>.github.io/transformations/`.

## Installing as an app

Open the GitHub Pages address once while online. Then:

- **iPhone/iPad (Safari):** Share → Add to Home Screen
- **Android (Chrome):** ⋮ → Add to Home screen / Install app
- **Windows/Mac (Edge or Chrome):** the install icon in the address bar

After that it works offline.

## Updating the game

1. Upload the new `index.html` to the repository.
2. Open `sw.js` and change `VERSION` (e.g. `transformations-v1` → `transformations-v2`). Commit.

Devices pick up the new version the next time the game is opened online.

## Progress

Progress and the sound setting are stored in the browser on each device. Nothing is sent anywhere.
