# Pokemon Region Overview

This project is a lightweight single-page HTML app that shows a full Pokemon overview grouped by region. Users can browse the Pokedex, search for a Pokemon, open a full-screen detail view, switch to a coloring-page style image, play the Pokemon cry, and print the selected Pokemon.

## Project Context

This is an experimental personal project that was vibe coded with Codex. It is intended as a playful prototype to explore fast iteration, interactive ideas, and AI-assisted development in a simple single-file app.

## Latest Published Page

The latest published version of the page is available here:

- [Open the live Pokemon page](https://wassinki.github.io/pokemon/pokemon.html)

## What It Does

- Displays Pokemon grouped by region:
  Kanto, Johto, Hoenn, Sinnoh, Unova, Kalos, Alola, Galar, and Paldea.
- Lets users search by Pokemon name or Pokedex number.
- Opens a full-screen overlay with:
  basic Pokemon information, flavor text, type, height, weight, color, shape, habitat, base happiness, and capture rate.
- Supports English and Dutch text in the detail panel.
- Offers a coloring mode that turns the image into a print-friendly black-and-white plate.
- Plays the Pokemon sound effect when available.
- Prints the currently opened Pokemon view.

## Project Structure

This repository currently contains a single application file:

- `pokemon.html`

The page includes its own HTML, CSS, and JavaScript, so there is no build step or install process.

## How To Run

Open pokemon.html in a modern browser.

You can also serve it locally with a simple static server if you prefer, for example:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000/pokemon.html](http://localhost:8000/pokemon.html).

## External Data Sources

The app depends on external online resources:

- Pokemon list and Pokemon details from [PokeAPI](https://pokeapi.co/)
- Pokemon images from [HybridShivam/Pokemon](https://github.com/HybridShivam/Pokemon)
- Pokemon cries from [PokeAPI cries](https://github.com/PokeAPI/cries)

Because of this, an internet connection is required for the full experience.

## Main Interaction Flow

1. Open the page.
2. Browse Pokemon by region or use the search field.
3. Click a Pokemon card.
4. In the full-screen view you can:
   switch language, toggle coloring mode, play sound, print, or close the overlay.

## Notes

- The app currently covers Pokemon `#1` through `#1025`.
- The page is designed as a self-contained prototype and does not use a framework.
- Basic self-checks are included in the browser console via `runSelfTests()`.
