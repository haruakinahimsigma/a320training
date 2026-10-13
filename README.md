# A320 Startup Simulator (2D)

A touch-friendly browser prototype for exploring an A320-style cockpit workflow. The interface has two switchable views:

- **Cockpit** — a 2D forward instrument panel with stylized PFD/ND/ECAM displays, an FCU strip, center pedestal, and a small MCDU mock-up.
- **Overhead** — the startup simulator's interactive overhead switches, APU and engine-start controls, ECAM-style readouts, and checklist.

Use the **COCKPIT** and **OVERHEAD** buttons in the top bar to move between the two views. Both views share the same simulated aircraft state, so battery/APU/engine actions in the overhead are reflected in the cockpit's engine indications.

## Run it

Open `index.html` in a browser, or publish the repository with GitHub Pages:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`, then save.
4. Open the Pages URL GitHub shows you.

## Important limitations

This is an educational UI prototype, **not** a real or certified Airbus simulator. The cockpit screens, flight values, and system logic are simplified; some cockpit controls are mock-ups, and the startup procedure should not be used as real-world operating guidance.
