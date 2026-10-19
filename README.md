# 🏁 full-course-replay

**Every full race, one page, updated weekly.**

full-course-replay is a curated feed of **full-length motor racing replays** on YouTube: no highlights, no recaps, just the whole race from lights out to the chequered flag. A scheduled task checks for new uploads every week and adds them to the top of the page, so the latest races are always first.

Live page available at [Full Course Replay](https://amalferpoma.github.io/full-course-replay/)

## Series covered

| Series | Notes |
|---|---|
| FIA World Endurance Championship (WEC) | Official channel |
| IMSA WeatherTech SportsCar Championship | Official channel |
| GT World Challenge Europe | Includes the Spa 24 Hours |
| Intercontinental GT Challenge (IGTC) | Official channel |
| Nürburgring 24 Hours | Official channel |
| NASCAR Cup Series | Unofficial uploads accepted when no official one exists |
| NTT IndyCar Series | Unofficial uploads accepted when no official one exists |

## How it works

1. **Weekly scan:** a scheduled task searches YouTube for full-race uploads from the past week across all covered series.
2. **Filtering:** highlights, short recaps and clips are discarded; only complete race broadcasts make the cut. Official channels are always preferred.
3. **Publishing:** new races are added to the top of the feed, sorted by race date, and the page is republished.

## Selection rules

- **Full races only.** If it isn't the complete broadcast, it doesn't go in.
- **Official first.** Videos from the series' or organisers' own channels take priority.
- **Fallback for NASCAR and IndyCar.** These series rarely publish full races officially, so reputable unofficial uploads are used when nothing official exists.
- **Newest on top.** Entries are ordered by race date, most recent first.


## Repository structure

```
full-course-replay/
├── index.html    # The published feed page
└── README.md     # You are here
```

## Disclaimer

full-course-replay does not host or redistribute any video content. It only links to videos publicly available on YouTube. All footage, trademarks and series names belong to their respective owners. Availability of unofficial uploads may change at any time.

---

*Built and maintained by Andrea, with a little help from Claude.*
