# A320 Training Lab

A browser-first A320 cockpit-training prototype designed to work on an iPad browser and desktop browsers.

## Current prototype

- Three.js cockpit scene with a flight-deck shell, windshield, main displays, center pedestal, and overhead controls
- Touch/click interaction for simplified switches
- Captain / first-officer / overhead viewing modes
- Simplified electrical, APU, fuel-pump, ignition, and engine-start state model
- Guided training flow
- Single-file app: `index.html`

## Run it

The page imports Three.js from jsDelivr, so an internet connection is required.

### GitHub Pages

1. Open this repository's **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and the **/(root)** folder, then save.
5. Wait for GitHub Pages to publish the site. The URL will appear in the Pages settings.

If Pages is not enabled, opening `index.html` in GitHub's code viewer will show the source, not run the simulator.

## Limitations

This is an early visual and interaction prototype, not a certified training device or a flight simulator. Switch states are simplified; engine start is not yet driven by a realistic aircraft systems model. The geometry, displays, camera behavior, touch ergonomics, and responsive performance need further testing on the target iPad.

## Roadmap

1. Improve cockpit proportions and seat/camera position.
2. Make the overhead panel and pedestal easier to operate by touch.
3. Add proper PFD / ND / ECAM canvas displays.
4. Implement coherent electrical, APU, pneumatic, fuel, and engine-start dependencies.
5. Add basic aircraft movement and flight controls after the cockpit interactions are stable.
