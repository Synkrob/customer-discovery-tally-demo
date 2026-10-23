# Customer Discovery Tally - SMASH Dance Studios public demo-only concept

This isolated, buildless prototype lives beside the existing Synk preview and does not modify the website shell or visual-directions comparison.

Run from the workspace root:

```powershell
node .\preview-server.mjs 4181 .\prototype-customer-discovery-tally
```

Open <http://127.0.0.1:4181/> locally, or use the published GitHub Pages demo when available.

The first working example is SMASH Dance Studios with a black/yellow accent. The compact header uses the supplied local SMASH logo; no background photo is used. Platform marks are stored locally under `assets/platforms/` and are used only as secondary icons; Apple Maps uses the available Apple mark because the selected source did not expose a separate Apple Maps glyph, and ChatGPT uses the OpenAI mark. Assets were downloaded from the Simple Icons static SVG distribution (project site: https://simpleicons.org/; license: https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md; disclaimer on brand/trademark rights: https://github.com/simple-icons/simple-icons/blob/develop/DISCLAIMER.md). No runtime external calls are made. The concept is intentionally local-only: simulated demo login and Staff/Management role switch, sample data, no real access control, no backend, no account creation, no uploads, and no customer records. It includes the full approved source set, separate Returning customer status tally, and two owner-only custom source slots. Results use San Antonio business-local date semantics (America/Chicago). Google Search and Google Maps now have separate new source IDs; legacy sample answers remain shown as the distinct `Google Search / Maps` combined label. Alkaline Water Leon Valley is queued for a later pass and is not implemented here.

The Synk site direction decision is recorded separately: Warm Editorial was selected for the future Synk build. This tally prototype does not modify the Synk website or visual-directions comparison.

Website is included as a new text-only source with stable ID `website`; existing sample counts and legacy source records remain unchanged.

Public demo notice: this copy is a fictional sample-data demonstration only. The Staff/Management switch is simulated, not security; there is no authentication, shared storage, backend, customer record, payment, or production access control.
