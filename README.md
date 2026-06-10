# Stuck in Your Head: The Science of Earworms 🎵

A ~7-minute **lightning talk for 2 speakers**, built as a [RevealJS](https://revealjs.com/)
presentation. Topic: *why songs get stuck in your head, and how to get rid of them.*

## How to present

It's a single self-contained file — **just open `index.html` in any browser**.

> ⚠️ Needs an internet connection: RevealJS and all images load from CDNs.

### Optional: run a local server (avoids any browser file:// quirks)

```bash
cd earworm-talk
python3 -m http.server 8000
# then open http://localhost:8000
```

### Keyboard shortcuts (while presenting)

| Key | Action |
|-----|--------|
| `→` / `Space` | Next slide |
| `←` | Previous slide |
| **`S`** | **Open speaker-notes view** (notes + timer + next slide) |
| `F` | Fullscreen |
| `Esc` / `O` | Slide overview |
| `B` | Black-out screen |

The two-speaker hand-off is built into the notes: **Speaker A** presents slides 1–5, **Speaker B**
takes 6–9. Press `S` to see who-says-what for each slide.

## Editing

- Replace `[Speaker A]` / `[Speaker B]` on the title slide (slide 1) with your real names.
- All content and speaker notes live inline in `index.html` — each slide is one `<section>`, and
  the speaker notes are the `<aside class="notes">` block inside it.
- Theme: swap `theme/black.css` in the `<head>` for `night.css`, `moon.css`, or `league.css` to
  change the look.

## Slide map

| # | Slide | Speaker |
|---|-------|---------|
| 1 | Title | A |
| 2 | Hook — "song stuck right now?" (ask the room) | A |
| 3 | What is an earworm? (INMI, ~90%, 15–30s) | A |
| 4 | Why it happens — the Zeigarnik effect | A |
| 5 | Triggers (recent listen / stress / idle mind) | A → hand off |
| 6 | Which songs stick the most | B |
| 7 | How to get rid of it (the payoff) | B |
| 8 | Bonus facts | B |
| 9 | One-line summary + thanks | B |

## Accuracy notes

- The **Zeigarnik effect**, the **chewing-gum** finding, and the **~90% weekly** figure come from
  real published research — present them as fact.
- The **"stickiest songs"** list (Bad Romance, Can't Get You Out of My Head, Bohemian Rhapsody) is
  from surveys/polls — present it as a fun reference, not hard data. (Note baked into slide 6's
  speaker notes.)

## Image credits

All images are from [Unsplash](https://unsplash.com) (free to use), hotlinked via the Unsplash CDN.
If any link breaks, swap the `data-background-image` URL in that slide's `<section>`.

| Slide | Subject | URL |
|-------|---------|-----|
| 1 | Headphones on yellow | `images.unsplash.com/photo-1505740420928-5e560c06d30e` |
| 2 | Cheering crowd | `images.unsplash.com/photo-1501386761578-eac5c94b800a` |
| 3 | Relaxing with a boombox | `images.unsplash.com/photo-1453738773917-9c3eff1db985` |
| 4 | Anatomical brain model | `images.unsplash.com/photo-1559757148-5c350d0d3c56` |
| 5 | Working at a laptop | `images.unsplash.com/photo-1517245386807-bb43f82c33c4` |
| 6 | DJ deck / neon | `images.unsplash.com/photo-1470225620780-dba8ba36b745` |
| 7 | Gummy bears (stand-in for "chew gum") | `images.unsplash.com/photo-1582058091505-f87a2e55a40f` |
| 8 | Kid singing into a mic | `images.unsplash.com/photo-1487180144351-b8472da7d491` |
| 9 | "No Music No Life" neon sign | `images.unsplash.com/photo-1499415479124-43c32433a620` |

