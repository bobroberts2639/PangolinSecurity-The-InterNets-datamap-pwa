# AS Datamap — PWA

Interactive map of the BGP-routed internet as an installable web app.

## Deploy (needs any HTTPS static host)
Easiest: GitHub Pages
1. Create a repo, upload the contents of this folder (index.html at the repo root).
2. Settings -> Pages -> Deploy from branch -> main / root.
3. Open the published URL.

Netlify/Cloudflare Pages: drag-and-drop this folder. Local test: `python3 -m http.server`.

## Install on iPhone / iPad
1. Open the URL in **Safari**.
2. Share button -> **Add to Home Screen**.
3. Launches full-screen standalone with its own icon; works offline after first load.

## Controls (touch)
One finger: pan - Two fingers: pinch zoom - Tap node: info card + bgp.tools link.
Panel: Industry/Region/Blueprint colours, layers (links, contours, grid),
halo styles, hub glyphs, brightness & dust sliders, search.

Data: CAIDA AS Relationships + AS2Org (Jul 2026), Stanford ASdb (Mar 2026). 

Click- through Lookups at bgp.tools .
