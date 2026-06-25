# Wedding invitations

Interactive single-page wedding invitations, served via GitHub Pages:
<https://tomekmaleni.github.io/invitation/>

## Pages

- **`index.html`** — *Marija & Tomislav.* A gilded card hidden behind two doors that swing
  open when you pull the ribbon/bow.
- **`kristina-and-antonio.html`** — *Kristina & Antonio.* The invitation sits inside a real
  (photographed) open envelope built from two transparent layers — a background (envelope back +
  wax seal) and a foreground (front pocket) — with the card in between. Drag anywhere to slide
  the card out; once it passes a threshold it lifts above the whole envelope. The whole thing
  rests on a wooden-desk background.

## Structure

- **`images/`** — optimized web assets used by the pages (`.webp`, plus a `.jpg` for link previews).
- **`assets/`** — original source material (the invitation PDF, reference photos, the envelope
  GIF layers, the desk texture). Git-ignored; converted into `images/*.webp` (the originals are
  often high-res or oddly-named, e.g. AVIF saved as `.jpg`).

No build step — plain HTML/CSS/JS. Open an HTML file directly or serve the folder with any static
server.
