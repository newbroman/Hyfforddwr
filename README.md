# Welsh Number Trainer (Hyfforddwr)

A browser-based trainer for understanding and saying Welsh numbers, with listening, typing and voice practice across several number-related topics.

**Live app:** https://newbroman.github.io/Hyfforddwr/

## Features

- Nine practice modes: Numbers, Context (numbers with nouns), Prices, Time, Dates, Gender, Ordinals, Phone Numbers and a Translator.
- Auto Campaign with six levels (Novice to Guru) that raises the number range as you progress, or Manual Practice with min/max sliders.
- Challenge options: negatives, decimals, fractions and mixed numbers, prices with or without pence, dates with or without year and weekday, casual or formal time style.
- Answer by 4, 8 or 12 buttons, or by typing; buttons can show digits or Welsh words.
- Blind Mode (audio only), a speaker button with normal, 0.5x and 0.25x playback, microphone answers, and a hands-free loop that plays Welsh, English, then Welsh again slowly.
- XP, speed bonuses and penalties, streak, daily goal, rank, per-category stats and a Review Mistakes list.
- Light, dark or automatic theme, and built-in help including notes on Welsh mutations (treigladau).

## Using it

Open the live app in a browser. It is a single web page with no manifest or service worker, so it is not installable and needs a connection to load.

Audio uses the browser's speech synthesis with a Welsh (cy-GB) voice, so a Welsh voice needs to be available on the device. Microphone answers use speech recognition, which needs Chrome or Edge. Progress is stored in the browser's local storage.

## Project structure

- `index.html` - the whole app (markup, styles and JavaScript).
- `icon-512.png` - icon image (not currently referenced by the page).

## Development

No build step. From the repository folder run:

```
python3 -m http.server
```

then open http://localhost:8000.

## Notes

This is the Welsh counterpart of Polski Trener Liczb and shares its structure and game modes.

Built by Martin Hollingham.
