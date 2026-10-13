# A320 Startup Simulator (2D)

A browser-based, touch-friendly A320-214 cold-and-dark startup training prototype. The project intentionally uses a **2D instrument-panel interface**—no Three.js, no 3D cockpit, and no model downloads.

## Features

- Cold-and-dark intro screen and cockpit status bar
- Interactive battery, APU, fuel-pump, hydraulic-pump, ADIRS, beacon, and engine-start controls
- Simplified ECAM-style electrical, APU, and engine readouts
- Startup checklist with current-step highlighting
- Simulated APU/engine spool-up timing and switch sounds
- Responsive layout intended for desktop and iPad browsers

## Run it

Open `index.html` in a browser, or publish the repository with GitHub Pages:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`, then save.
4. Open the Pages URL GitHub shows you.

## Important limitations

This is an educational interface prototype, **not** a real or certified Airbus simulator. The system logic, indications, timings, and startup procedure are simplified and should not be used as real-world operating guidance. Several controls are visual/demo controls only.
