# Manifest

## Project Overview

Manifest is a single-file MTG Commander deck viewer and price tracker. The entire app lives in `index.html` — no build tools, no frameworks, no dependencies.

## Architecture

- **Single file**: All HTML, CSS, and JS are in `index.html`
- **API**: Uses the Scryfall API for all card data, images, and pricing
- **Rate limiting**: Built-in 220ms delay between API calls to respect Scryfall limits
- **No backend**: Entirely client-side

## Key Conventions

- Keep everything in the single HTML file unless there's a strong reason to split
- No external dependencies — vanilla JS only
- Support multiple decklist formats: Moxfield, Archidekt, MTGO, Arena
- Price data comes from Scryfall with TCGPlayer integration
- Currency support: USD and AUD (1.56x conversion)
