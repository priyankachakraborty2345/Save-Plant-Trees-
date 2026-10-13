# WE FOR EARTH – Learn, Plant and Track Trees

A free, open-source web prototype where youth **learn** about climate and trees, **plant** a sapling, and **check in** on it until it grows.

By Priyanka Chakraborty, founder of SAVE & PLANT TREES! (started 2020). Blog: https://save-trees-plant-trees.blogspot.com

## Problem
Many tree drives focus on planting day, with little follow-up. Young people also need simple, local climate learning.

## Solution: Learn → Plant → Check in
- **Learn:** 4 short lessons, each with a 3-question quiz (climate, trees, planting care, saving water and waste)
- **Native trees of Assam:** a short guide (Hollong, Nahar, Bamboo)
- **Plant and track:** pledge a tree, log species, place and status
- **Survival check-ins:** every 30 days mark the tree as Alive, Needs care or Lost. The dashboard shows how many trees are alive at the last check-in, not only how many were planted
- **Green Points:** +5 for adding a tree, +2 for a check-in, +10 for finishing a lesson quiz

## What is different
Digital tree monitoring already exists in India, for example in large government drives. WE FOR EARTH is built for youth and schools: it joins short lessons, planting and check-ins in one free, simple tool, with a guide to native trees of Assam.

## Tech stack
HTML, CSS and JavaScript. No installation. Data is saved in the user's browser (localStorage) in this prototype.

## Live demo
https://priyankachakraborty2345.github.io/we-for-earth2026/

## Setup (3 steps, no coding needed)
**Requirements:** any modern web browser (Chrome, Edge, Firefox, Safari). Nothing else to install.
1. Download this repository: green **Code** button > **Download ZIP**, then unzip it.
2. Open the file `index.html` in your browser (double-tap or double-click it).
3. Use the app: **Learn** tab for lessons, **Plant & Track** tab to add trees and check in.

**Optional (run on a local server):** with Python installed, open a terminal in the folder and run `python -m http.server 8000`, then visit `http://localhost:8000`.

**Deploy your own copy (free):** fork this repository, then Settings > Pages > Branch `main` > Save.

## Environment variables
None. This prototype needs **no API keys, no database and no server**. All data is stored in the user's own browser (localStorage).

## Tests
Manual test cases are in `test-cases.md` (14 cases covering forms, check-ins, quizzes, points and saved data). Sample data is in `sample-data.csv`.

## Files
- `index.html` – the prototype
- `technical-design.md` – design document
- `sample-data.csv` – sample data
- `test-cases.md` – test cases
- `LICENSE` – MIT License

## UN SDGs
SDG 4, 11, 13, 15, 17

## Future scope
Shared online database, photo upload for check-ins, school and city leaderboards, check-in reminders, Assamese and Hindi language support.

## Sources
- UN Sustainable Development Goals: https://sdgs.un.org/goals
- Official State symbols of Assam (State Tree: Hollong): https://rajbhavan.assam.gov.in/about-us/symbols-assam
- PTI via ThePrint (6 Aug 2026), DDA digital plantation monitoring: https://theprint.in/india/dda-launches-real-time-digital-system-to-monitor-23-lakh-sapling-plantation-drive/3007382/
- Assam State Biodiversity Board, Biodiversity of Assam (Hollong, Nahar, bamboo species): https://asbb.assam.gov.in/taxonomy/term/5811

## License
MIT License
