# Mobile QA checklist

V6 has an explicit phone treatment at `max-width: 700px`.

Test before shipping:
- iPhone-style 390x844 and Android-style 412x915 viewports.
- Portrait first; landscape should remain usable, not necessarily identical.
- Every project has an always-visible visual and `OPEN CASE` affordance on touch.
- No hover is required for navigation or understanding.
- Lenis, custom cursor, project-card 3D and the case WebGL signal field are disabled on coarse/touch pointers.
- Safe areas use `env(safe-area-inset-*)`.
- Case metadata becomes a two-column grid; Source gets a full-width row.
- Evidence cards are reduced from nine to six on phone to preserve rhythm/performance.
- `prefers-reduced-motion` still removes transition-heavy behavior.