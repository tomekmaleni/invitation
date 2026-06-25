# Wedding invitations

Interactive single-page wedding invitations, served via GitHub Pages:
<https://tomekmaleni.github.io/invitation/>

## Pages

- **`index.html`** — *Marija & Tomislav.* A gilded card hidden behind two doors that swing
  open when you pull the ribbon/bow.
- **`kristina-and-antonio.html`** — *Kristina & Antonio.* Starts as a wax-sealed envelope — a
  photographed close-up of the flap with the K&A wax seal — resting on a textured backdrop; drag it
  and it gives way to the open envelope. The invitation then sits inside a real (photographed) open
  envelope built from two transparent layers — a background (envelope back + wax seal) and a
  foreground (front pocket) — with the card in between. Drag anywhere to slide the card out; once
  it passes a threshold it lifts above the whole envelope.
  - The backdrop comes in three interchangeable versions, each its own file with its own
    link-preview thumbnail: **`kristina-and-antonio.html`** (warm olive-wood grain),
    **`kristina-and-antonio-olive-branch.html`** (cream plaster framed by an olive branch), and
    **`kristina-and-antonio-dark-desk.html`** (dark wooden planks).

## Structure

- **`images/`** — optimized web assets used by the pages (`.webp`, plus `.jpg`s for link previews).
- **`assets/`** — original source material (the invitation PDF, reference photos, the envelope
  GIF layers, the desk texture). Git-ignored; converted into `images/*.webp` (the originals are
  often high-res or oddly-named, e.g. AVIF saved as `.jpg`).

No build step — plain HTML/CSS/JS. Open an HTML file directly or serve the folder with any static
server.
