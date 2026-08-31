# Music City by Night — Census & Domain

A Tableau dashboard visualising player character demographics for **Music City by Night**, a
*Vampire: The Masquerade* 5th Edition play-by-post Discord server set in Nashville, Tennessee.

**Live dashboard:** [View on Tableau Public](#)

## What it shows

- **Children of the Night** — clan breakdown, as a treemap
- **Allegiances of Nashville** — sect breakdown, as a donut
- **Oceans of Time** — generational makeup, as a bar chart
- **Domains** — claimed territory across Nashville, as a Google My Maps embed

Plus KPI tiles for active characters and active players. Selecting a sect filters the other views.

## Data

`mcbn_roster.xlsx` — one row per active character (n = 40), with columns for character name,
player, clan, age category, and sect.

## Running it

Open `Music_City_by_Night__Census___Domain.twbx` in
[Tableau Desktop](https://www.tableau.com/products/desktop) or the free
[Tableau Public Edition](https://www.tableau.com/products/public/download). The packaged
workbook bundles the data and images, so nothing else is needed. The Domains map requires an
internet connection to render.

## Notes

The roster is a point-in-time snapshot and does not update automatically.

*Vampire: The Masquerade* is a trademark of Paradox Interactive. This is an unofficial fan
project with no affiliation.
