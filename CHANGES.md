# Bath Again — changed files only (40 files)

Only files that actually changed this session. Upload in two steps so GitHub's
web uploader stays under its limit:

1. `site/assets/` — 36 image files, drag into the repo's existing `site/assets/`
2. `site/` — the 4 HTML files, drag into the repo's `site/`

`BeforeAfterSlider.dc.html`, `FinancingModal.dc.html`, `support.js` and every other
image are unchanged and not included. Do not touch `.github/workflows/`.

After committing, delete `site/assets/team-marco.avif` — it is replaced by
`team-marco.jpg`.

## Copy

- All "48 hours" changed to "72 hours" (index, BathAgain, About, Contact)
- All "pattern" / "patterns" wording changed to "style" / "styles"
  (the `#stone-patterns` anchor id was left alone so existing links keep working)
- Backed for Life: "Every Bath Again product is backed by a Lifetime Warranty —
  because a beautiful bathroom should stay beautiful for as long as you own your home."
- FAQ last question: "your project" changed to "your product"
- "Available in a Variety of Colors" changed to "The Chuco Town Collection"
- A Recent Transformation: BEFORE changed to "OLD GARDEN TUB"; DURING replaced with
  "Tile & sheetrock removed, & studs exposed. Inspection was completed for any damage,
  & dry board installed" (set in Cormorant, sentence case, since it is too long for a caps label)

## Chuco Town Collection names

Alaskan Ivory → Adobe · Azzurra Bay → White Sands · Bardiglio → Desert Storm ·
Black Mist → Scenic Night · Botticino Cream → Mesilla · Calabria → Crazy Cat ·
Calacatta White → Sunset Heights · Creme Travertine → Rio Grande ·
Frost → Manhattan Heights · Golden Beaches → Red Sands · Gray Quartz → Franklin Snow ·
Lincoln Gold → The Plaza Hotel · Mocha Travertine → Hueco Tanks · Taj Mahal → Chamizal ·
Triton → Rio Azul · Veincut Gray → Dripping Falls · White Pearl → Desert Pearl

Filenames were NOT renamed — `stone-full-alaskan-ivory.jpg` still backs the Adobe card, etc.

## Layout

- Header nav now actually sticks: the page wrapper's `overflow: hidden` was silently
  breaking `position: sticky`, changed to `overflow-x: clip`
- Hero titles: removed the solid navy panel behind the heading (the photo scrim remains)
- About / What Sets Us Apart: on screens ≥1100px the grid is 4 columns and the last two
  bullets are centred
- Team photos are 190px squares instead of circles; Linda's is zoomed 1.5x on her face,
  Stephanie's and Marco's are top-aligned

## Images

Replaced in place (same filenames), so the HTML carries `?v=2` / `?v=3` cache-busting
params. New file: `lifestyle-floral-vanity-glass-door.{jpg,webp}`.

- `shower-door-main` was unreferenced in the repo. It is now used in the Shower Doors
  section on the Design page, and on the home page beside "Our Simple Process"
  (that slot previously used room-alaskan-ivory).
- Home page beside "A Reputation You Can Trust" now uses
  lifestyle-floral-vanity-glass-door (previously room-frost).
