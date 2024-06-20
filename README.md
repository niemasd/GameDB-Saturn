# GameDB-Saturn
Sega Saturn, part of [GameDB](https://github.com/niemasd/GameDB).

## Structured Downloads
* **[`Saturn.data.json`](https://github.com/niemasd/GameDB-Saturn/releases/latest/download/Saturn.data.json):** All data, structured in the JSON format
* **[`Saturn.data.tsv`](https://github.com/niemasd/GameDB-Saturn/releases/latest/download/Saturn.data.tsv):** All data, structured in the TSV format
* **[`Saturn.release_dates.pdf`](https://github.com/niemasd/GameDB-Saturn/releases/latest/download/Saturn.release_dates.pdf):** Histogram of release dates, stratified by region
* **[`Saturn.titles.json`](https://github.com/niemasd/GameDB-Saturn/releases/latest/download/Saturn.titles.json):** Mapping of serial numbers to game titles, structured in the JSON format

# Notes

## Uniquely Identifying Games

The game folders in [`games`](games) have the structure `T-XXXX`, which is the game code (also known as game ID), which is at offsets `0x30` through `0x39` (inclusive) of the disc header, and which can be used to uniquely identify the game.

# Sources
* [Redump](https://redump.org/)
* [Sega Retro](https://segaretro.org/Category:Saturn_games)
