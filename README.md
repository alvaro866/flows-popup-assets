# flows-popup-assets

Public static assets (3D models, images) for Flows Wave popups, served via jsDelivr:
`https://cdn.jsdelivr.net/gh/alvaro866/flows-popup-assets@<commit>/<popup>/<file>`

**Only public, freely licensed media goes here. Never code, config, keys or customer data.**

Popups pin a commit and check each file's SHA-256 before using it, so files are never changed in place:
add new versions as new files/commits.

## olympus-rush/
All CC0 (public domain):
- `sky_6144.jpg`, `bust.glb`, `horse.glb`, `vase.glb` - Poly Haven (polyhaven.com)
- `zeus.glb` - Greenough seated statue, Smithsonian Open Access 3D (3d.si.edu)

## olympus-rush-v3/
All CC0. `titan-hi.glb` / `titan-lo.glb`: Greenough seated statue, Smithsonian Open Access 3D (3d.si.edu), optimised with gltf-transform.
`music.mp3`: "QaziJamJam (orchestral battle theme)" by Emma M. Andersson (looneybits), OpenGameArt.org (https://opengameart.org/content/qazijamjam-orchestral-battle-theme), CC0. Other files: same Poly Haven sources as olympus-rush/.

## duck-dash/
Duck Dash demo minigame (Flows Wave popup).
- `*.webp`: original art generated for Flows with ChatGPT image generation; free to use in Flows popups.
- `*.ogg`: CC0 sound effects and music from OpenGameArt.org (rubberduck, Kenney, 0new4y, Tozan, LokiF); per-file sources in `duck-dash/LICENSES.md`.
- `lilita-one-latin.woff2`: Lilita One by Juan Montoreano, SIL Open Font License 1.1 (`duck-dash/OFL.txt`).
