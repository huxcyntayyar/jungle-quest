# Jungle Quest

A 3D jungle runner game that runs in the browser. Guide the explorer 3.4 km through the rainforest, past rivers, chasms and ancient ruins, to reach the lost temple. Collect coins and gems along the way.

The whole game is one file, `index.html`, with the 3D engine (three.js r128) built in, so it needs no build step and no internet downloads.

## Controls

- **Phone:** tilt left and right to switch lanes. Tap the screen or flick the phone upward to jump. If motion sensors aren't available, touch controls turn on automatically.
- **Keyboard:** ← → or A D to switch lanes, Space or ↑ to jump, P to pause.

## Play it on GitHub Pages

1. Upload `index.html` to the root of this repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, then choose the `main` branch and the `/ (root)` folder. Click **Save**.
4. After a minute or two the game is live at `https://<your-username>.github.io/<repo-name>/`.

GitHub Pages serves over HTTPS, which iPhones require before a page can use the motion sensors.
