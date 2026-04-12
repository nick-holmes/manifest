# Manifest

A lightweight, single-file Magic: The Gathering Commander deck viewer and price tracker.

## Features

- **Multi-format import** — paste decklists from Moxfield, Archidekt, MTGO, or Arena
- **Card previews** — art, oracle text, mana costs, type info
- **Price tracking** — compare prices across TCGPlayer, Card Kingdom, MTGMate, Scryfall, and Gatherer
- **Bulk purchasing** — mass entry links to multiple retailers
- **Browse printings** — see all printings of a card across sets with rarity and release year
- **Commander legality** — highlights banned cards
- **List & grid views** — toggle between compact list and visual grid
- **Zero dependencies** — single HTML file, no build step, no backend

## Usage

Open `index.html` in a browser. That's it.

To load a deck, click "Load new deck" and paste your decklist in any supported format.

## Tech

- Vanilla HTML, CSS, JavaScript
- [Scryfall API](https://scryfall.com/docs/api) for card data, images, and pricing
- Built-in rate limiting to respect API limits
