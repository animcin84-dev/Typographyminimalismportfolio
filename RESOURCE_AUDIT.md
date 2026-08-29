# RESOURCE AUDIT — V5

The uploaded references were reviewed as building blocks, not blindly merged.

## Used conceptually / adapted

- **codrops-sticky-grid-scroll** — column reveal + sticky zoom logic → adapted into the Projects evidence stage using original text/data cards. MIT.
- **Scroll-Transition** — SVG blinds progression → adapted into the case-study claim→evidence interstitial. MIT.
- **RotatingOnScrollAnimations** — 3D scroll response → adapted lightly to Lab and proof cards. MIT.
- **codrops-infinite-scroll-and-content-transition** — reversible thumbnail↔detail idea → used for project index↔case return choreography. MIT.
- **codrops-demo / async page transitions** — transition locking/lifecycle principles informed the existing router. MIT.

## Audited, deliberately not shipped in the preview runtime

- **Swup** — excellent production choice for real multi-page URLs, cache/history/a11y. Not necessary in the single-file preview build. MIT.
- **OGL** — excellent minimal WebGL layer. Not needed for one local shader.
- **Paper Shaders** — excellent lightweight shader library. The preview uses one custom shader instead, keeping runtime surface smaller. Apache-2.0.

This is intentional restraint: adding all libraries would increase weight and make the site feel like a component showcase rather than one authored system.