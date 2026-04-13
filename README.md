# Prayer Tracker

A daily Bible reading guide and prayer tracker based on **The Bible in a Year** reading plan by Ascension / Fr. Mike Schmitz, following Jeff Cavins' *Great Adventure Bible Timeline*.

## Features

- **365-day reading plan** with 4 sections per day: Period, First Reading, Second Reading, and Psalms/Proverbs/Song
- **ESV scripture text** loaded on-demand via the bolls.life API — tap any reading to open a full-screen reader
- **Per-section checkboxes** to track completion of each reading
- **Notes** for each reading section, auto-saved as you type
- **Day Complete** indicator when all readings are checked off
- **Progress bar** showing total days completed out of 365
- **Period navigation** — tap the period label to jump between the 15 periods of salvation history
- **Day picker** — tap the day number to jump to any day
- **Reading history log** — view all days with status filters (Complete, In Progress, Not Started)
- **Swipe navigation** between days on mobile
- **Dark/light mode** via system preference
- **Offline-capable** — all data stored in localStorage

## Reading Plan Periods

| Period | Days |
|--------|------|
| Early World | 1–5 |
| Patriarchs | 6–26 |
| Egypt and Exodus | 27–51 |
| Desert Wanderings | 52–80 |
| Conquest and Judges | 81–98 |
| Messianic Checkpoint | 99–105 |
| Royal Kingdom | 106–153 |
| Messianic Checkpoint | 154–161 |
| Divided Kingdom | 162–182 |
| Exile | 183–257 |
| Messianic Checkpoint | 258–266 |
| Return | 267–281 |
| Maccabean Revolt | 282–312 |
| Messianic Fulfillment | 313–321 |
| The Church | 322–365 |

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — no frameworks, no build tools
- [bolls.life API](https://bolls.life/api/) for ESV scripture text
- localStorage for progress, notes, and current day

## Usage

Open `index.html` in any browser. No server required.

## Data Source

The 365-day reading plan in `data.js` is based on the official reading plan from [Ascension Press](https://ascensionpress.com/bibleinayear) (© 2021 Ascension).
