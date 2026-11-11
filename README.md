# A.T. Thaseen Ibrahim — Creative Portfolio

**Live site:** https://thaseenportfolio.github.io/

This GitHub Pages repository deploys the V8 Kinetic Atelier portfolio through the
[Publish V8 Kinetic Atelier](https://github.com/thaseenportfolio/thaseenportfolio.github.io/actions/workflows/publish-v8.yml)
GitHub Actions workflow.

The portfolio's source files and images are maintained in
[thaseenportfolio/thaseen-portfolio](https://github.com/thaseenportfolio/thaseen-portfolio).
The publishing workflow copies the site from that repository and deploys to this
free GitHub Pages address.

## Latest mobile refinement — 11 November 2026

- Rebalanced mobile headings and portrait spacing for phone screens.
- Replaced the clipped four-image motion stage on phones with a contained two-column gallery.
- Kept desktop parallax and original project artwork unchanged.
- Improved readable captions, contact typography, and touch-oriented navigation.
- Site source revision: `ee6358644376e4dc0b9a783f63e3debd2a768c70`.


To publish later source changes, run the existing **Publish V8 Kinetic Atelier**
workflow from the repository's Actions tab.


## V8.3 final motion refinement — 11 November 2026

- Restored independent touch-safe scroll motion to IMAGINE, VISUALISE and DELIVER.
- Preserved the V8.2 readable two-column portfolio gallery with bounded image movement on mobile.
- Added a visible ON/OFF indicator for the mobile motion toggle.
- Preserved desktop parallax, mobile typography containment and reduced-motion behavior.
- Source CSS commit: `5f108151b8bdb3a2949c7eeaaa7e75ebfbefae7c`.
- Source JS commit: `e4811483f97178499918368f46dc77196edf7f13`.


## V8.4 mobile motion correction

- Added independently visible kinetic drift on phones when Motion is enabled.
- Added versioned CSS/JS URLs to avoid stale cached mobile effects.
- Retained scroll response, Motion ON/OFF toggle, and reduced-motion accessibility.
- Tested mobile animation and toggle with Chromium at 390px width with no script errors or horizontal overflow.
