# ⚽ Timestamped Football Odds incl. Pinnacle — 7 Leagues of Asia & Africa: J1 League, Saudi Pro League, K League 1 + 4 More (free sample)

**Timestamped Soccer Asia & Africa Premium — free sample: 20 matches out of 17,329, from each of the 7 leagues.** Same files,
same columns, same formats as the full product. Only the number of matches differs.

Most football odds datasets give you one closing number per match. The full product gives you
**31,454,431 timestamped quotes** from 5 named bookmakers, pre-match and in-play, with the score
and the match clock the bookmaker sent on its in-play quotes, plus the opening and the closing of every book and
market with the
exact time each was recorded, and 944,160 dated snapshots from 37 more bookmakers.

⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/gxvqou?utm_source=github&utm_medium=repo&utm_campaign=asia_africa_premium&utm_content=readme_top)** — 17,329 matches, 7 top flights, 78 league-seasons, 2016–2026.

---

## In this repository

| Path | What it is |
|---|---|
| `sample/` | The free 20-match sample: same files, same columns as the full product |
| `AsiaAfrica_Verify_Before_You_Buy.ipynb` | *Verify before you buy*: the key figures of the listing recomputed on the **full** product, outputs included |

Also on [Hugging Face](https://huggingface.co/datasets/oliviersportsdata/Asia-Africa-Football-Timestamped-Odds-Pinnacle-Match-Stats), with a table viewer, and on [Kaggle](https://www.kaggle.com/datasets/oliviersportsdata/asia-africa-football-odds-with-pinnacle-sample).

---

## What's in this sample

| Table | Sample | Full product |
|---|---:|---:|
| Odds_Timestamped | 45,751 | 31,454,431 |
| Minute_Stats | 8,491 | 4,287,131 |
| Bookmaker_Snapshots | 1,360 | 944,160 |
| Lineups | 535 | 325,517 |
| Events | 660 | 390,628 |
| Team_Stats | 40 | 34,658 |
| Opening_Closing | 20 | 17,329 |
| Matches | 20 | 17,329 |

The 20 matches: a recent match of each of the 7 leagues (played in September 2026, the one with the most complete
data among the league's latest matches), plus 13 matches chosen for what they show: the final of Japan's 2026 J1 100
Year Vision League (both legs), a group-stage draw settled by a 14-13 shoot-out (shown quote by quote below), the
Shanghai derby of the 2020 title quarter-finals (both legs), one of the 2025 K League promotion-relegation play-offs
(both legs), the Riyadh, Casablanca and Algiers derbies, a Tunisian play-off settled on penalties, a ground the source
places in the wrong country, and a match whose kickoff time in the source is a day late. 1 went to extra
time, 3 to a penalty shoot-out.

| Country | League | Season | Stage | Date (UTC) | Match | Result | Note |
|---|---|---|---|---|---|---|---|
| Algeria | Algerian Ligue Professionnelle 1 | 2025/26 | Regular Season, matchday 17 | 2026-04-01 | MC Alger – USM Alger | 1-0 | Algiers derby |
| Algeria | Algerian Ligue Professionnelle 1 | 2026/27 | Regular Season, matchday 3 | 2026-09-17 | CR Temouchent – JS Kabylie | 1-0 | recent match |
| China | Chinese Super League | 2020 | Quarter-finals, leg 1 | 2020-10-18 | Shanghai Shenhua – Shanghai Port | 0-0 | Shanghai derby, title quarter-final, first leg |
| China | Chinese Super League | 2020 | Quarter-finals, leg 2 | 2020-10-23 | Shanghai Port – Shanghai Shenhua | 1-1 · 1-1 aet · 5-4 pens · agg 1-1 | second leg: extra time, then penalties 5-4 |
| China | Chinese Super League | 2025 | Regular Season, matchday 2 | 2025-03-03 | Qingdao West Coast – Wuhan Three Towns | 2-0 | kickoff in the source: 2025-03-03 06:00 UTC; played 2025-03-02 07:44 UTC, pre-match cut at the real start |
| China | Chinese Super League | 2026 | Regular Season, matchday 18 | 2026-09-12 | Wuhan Three Towns – Henan | 1-1 | recent match |
| Japan | J1 League (100 Year Vision League) | 2026 | Group Stage, matchday 8 | 2026-03-21 | Avispa Fukuoka – Gamba Osaka | 2-2 · 14-13 pens | draw after 90 minutes, shoot-out 14-13: shown quote by quote below |
| Japan | J1 League (100 Year Vision League) | 2026 | Final, leg 1 | 2026-05-30 | Vissel Kobe – Kashima Antlers | 5-0 | J1 100 Year Vision League final, first leg |
| Japan | J1 League (100 Year Vision League) | 2026 | Final, leg 2 | 2026-06-06 | Kashima Antlers – Vissel Kobe | 2-0 · agg 2-5 | final, second leg: Vissel Kobe win 5-2 on aggregate |
| Japan | J1 League | 2026/27 | Regular Season, matchday 7 | 2026-09-12 | Sanfrecce Hiroshima – Cerezo Osaka | 6-1 | recent match |
| Morocco | Botola Pro | 2025/26 | Regular Season, matchday 20 | 2026-05-09 | Raja Casablanca – WAC Casablanca | 0-1 | Casablanca derby |
| Morocco | Botola Pro | 2026/27 | Regular Season | 2026-09-27 | KACM Marrakesh – HUSA Agadir | 2-3 | recent match |
| Saudi Arabia | Saudi Pro League | 2025/26 | Regular Season, matchday 32 | 2026-05-12 | Al-Nassr Riyadh – Al Hilal Riyadh | 1-1 | Riyadh derby |
| Saudi Arabia | Saudi Pro League | 2026/27 | Regular Season, matchday 7 | 2026-09-11 | Al Ahli Jeddah – Al Hazm | 3-1 | recent match |
| South Korea | K League 1 | 2025 | Play-Offs, leg 1 | 2025-12-05 | Bucheon – Suwon FC | 1-0 | promotion-relegation play-off against a K League 2 club, first leg |
| South Korea | K League 1 | 2025 | Play-Offs, leg 2 | 2025-12-08 | Suwon FC – Bucheon | 2-3 · agg 2-4 | second leg: Bucheon win 4-2 on aggregate |
| South Korea | K League 1 | 2026 | Regular Season, matchday 30 | 2026-09-19 | FC Anyang – Ulsan HD | 2-1 | recent match |
| Tunisia | Tunisian Ligue Professionnelle 1 | 2021/22 | Play-Offs | 2022-10-13 | ES Metlaoui – ES Zarzis | 1-1 · 3-1 pens | play-off: penalties 3-1, no extra time in the source (Extra_Time 0) |
| Tunisia | Tunisian Ligue Professionnelle 1 | 2026/27 | Regular Season, matchday 4 | 2026-09-12 | Avenir de La Marsa – Etoile Sportive Sahel | 1-0 | the source puts this ground in 'Waddy, USA': set to La Marsa, Tunisia |
| Tunisia | Tunisian Ligue Professionnelle 1 | 2026/27 | Regular Season, matchday 3 | 2026-09-16 | ES Zarzis – US Monastir | 1-2 | recent match |

The top division of Algeria, China, Japan, Morocco, Saudi Arabia, South Korea and Tunisia:
78 league-seasons in the full product, with season, tournament and stage (regular season,
groups, split rounds, title bracket, play-offs) on every match, matchday on 98.6 % of them (where the
source's numbering is reliable) and leg on every two-legged tie. Japan's 2026 special tournament (the J1
100 Year Vision League, February to June 2026) is delivered as played, with its group-stage shoot-outs. `AsiaAfrica_Coverage.csv`
(in this sample too) gives the coverage of the full product, league by league and season by season.

---

## Book coverage (full product)

Coverage is not uniform. Here is what each book actually priced.

| Book | Quotes | Matches with an FT 1X2 close | First FT 1X2 close | Closing prices on |
|---|---:|---:|---|---|
| Bet365 | 22,664,448 | 16,736 (96.6 %) | 2016-09-08 | all 8 markets |
| Pinnacle | 1,295,298 | 12,974 (74.9 %) | 2018-09-27 | 1X2, total goals; Asian handicap from Jun 2023 |
| Unibet | 2,075,264 | 15,212 (87.8 %) | 2017-04-15 | 1X2, total goals |
| Betfair (Sportsbook) | 4,649,647 | 3,384 (19.5 %) | 2023-11-03 | 1X2 |
| Betsson | 769,774 | 6,812 (39.3 %) | 2022-07-03 | 1X2, total goals |

Split: **24,380,334 in-play** (77.5 %) · **7,074,097 pre-match** (22.5 %).

Markets: full-time 1X2, Asian handicap, total goals and total corners, and the same four for the
first half. Bookmakers are always named, never aggregated. The 37 other bookmakers are in
`Bookmaker_Snapshots`: their first and last pre-match snapshot, each with its time.

### Coverage over time

A bookmaker, or a table, is not in the source for the whole period. Computed month by month on the full product:

| Source | From | Gaps (months when fewer than half of the matches have it) | Stops for |
|---|---|---|---|
| Bet365 | 2016-09-08 | none | - |
| Pinnacle | 2018-09-27 | 2023-09 to 2023-11, 2026-07 to 2026-08 | - |
| Unibet | 2017-04-15 | 2026-07 to 2026-08 | - |
| Betfair (Sportsbook) | 2023-11-03 | 2024-11 to 2025-08, 2026-07 to 2026-08 | - |
| Betsson | 2022-07-03 | 2026-07 to 2026-08 | - |
| Minute-by-minute statistics | 2017-06-10 | 2018-01 to 2019-09, 2026-07 | - |
| Events | 2016-08-28 | none | - |

Bookmakers: an FT 1X2 closing price. A gap is a calendar month (with at least 30 matches) in
which fewer than half of the matches have it. The same table is in the README, and the
[Verify before you buy notebook](https://www.kaggle.com/code/oliviersportsdata/asia-africa-football-odds-verify-before-you-buy) recomputes it from the files.

---

## Said plainly

Stated up front rather than discovered after paying.

- **No lineups for Algeria, Morocco and Tunisia** in the source; Saudi Arabia has them on 48 % of its
  matches, South Korea on 67 %. The odds, the match sheet, the events and the statistics are there.
- **Gaps in time:** Pinnacle 2023-09 to 2023-11 and 2026-07 to 2026-08; Unibet 2026-07 to 2026-08; Betfair (Sportsbook) 2024-11 to 2025-08 and 2026-07 to 2026-08; Betsson 2026-07 to 2026-08; minute-by-minute statistics 2018-01 to 2019-09 and 2026-07. In July and August 2026 (99 % and 100 % of matches), Bet365 is the only book with a closing price on most
  matches.
- **`Kickoff_UTC` is the scheduled kickoff.** On 536 of the 16,216 matches with a Bet365 live clock, the real start
  is 5 to 30 minutes after it. Quotes recorded in between are In-play (no score yet) and the closing price is the
  last quote before the scheduled time: never an in-play price. For 4 matches the source's kickoff is more than
  3 hours later than the real start: pre-match is cut at the real start. For 5 it is more than 3 hours earlier:
  the few quotes recorded in between count as In-play.
- **Score and clock on in-play quotes are the bookmaker's own:** 94.5 % of in-play quotes carry both
  (Bet365 98.9 %, Unibet 99.6 %, Betsson 99.0 %). Pinnacle almost never sends a numeric
  clock (25 of its 79,247 in-play quotes),
  Betfair a full score on 18.5 % of its in-play quotes; nothing is filled in from another book.
- **Minute-by-minute statistics have no recording time before 2021-05-10:** `Timestamp_UTC` and `Epoch` are
  empty on the 3,127 matches played before (26.4 % of the rows); `Minute` and `Value` are always there.
- **A closing quote is the last pre-match price recorded.** Median gap to kickoff on FT 1X2: Pinnacle 4 min, Betfair 6 min, Betsson 10 min, Bet365 22 min, Unibet 1.8 h.
  That is why every book has its own closing time.
- **The other bookmakers' table is a dated snapshot, not a closing price:** the source keeps three
  snapshots per book (first price, around kickoff, last price). Check `Minutes_Before_Kickoff`.
- **Some matches are missing from the source:** the first matchdays of 2016 in 6 of the 7 leagues (Tunisia's
  2016/17 is complete), one 2016 K League 1 Championship Round match, one Algerian match of 2016/17, the K League
  promotion-relegation play-offs before 2025, and 15 matches that the source marks as decided by the federation
  and holds no data for (8 of them in the Chinese Super League, December 2022). Every gap is listed in `sample/README.md`.
- **Home and away swapped by the source** on one of the two matches of 13 pairings (the same home team
  listed twice in a home-and-away round robin): kept as the source gives them, listed in `sample/README.md`.
- **Data starts on 2016-08-28.** The current seasons stop at 2026-09-30.
- **31 source events were removed** (duplicate ids, results awarded or changed by the federation,
  abandoned matches with an awarded result, lower-division matches filed with the league, a phantom listing),
  each listed with its evidence in `sample/README.md`. 4 matches the source flags as decided by the
  federation are kept: their score is the one played on the pitch.
- **Odds are UTC and come from one provider.** No cross-provider reconciliation is claimed.

---

## What in-play looks like, in this sample

Avispa Fukuoka 2-2 Gamba Osaka, J1 100 Year Vision League, group stage, 21 March 2026. Gamba led twice
(11' and 42'); Avispa missed a penalty at 81' and equalised in added time (90+3'). In this format a draw after
90 minutes goes straight to penalties: Avispa won the shoot-out 14-13 and took 2 points. Bet365 full-time 1X2,
in-play, around each goal. Every row is in `sample/odds_timestamped/AsiaAfrica_Odds_Timestamped_JPN.csv.gz`.

| Timestamp (UTC) | Min | Score | Avispa Fukuoka | Draw | Gamba Osaka |
|---|---:|---|---:|---:|---:|
| 2026-03-21T05:36:47Z | 1 | 0-0 | 4 | 3.25 | 1.952 |
| 2026-03-21T05:45:51Z | 10 | 0-0 | 3.6 | 3 | 2.2 |
| 2026-03-21T05:46:15Z | 11 | 0-1 | 8.5 | 4.333 | 1.4 |
| 2026-03-21T05:55:51Z | 20 | 0-1 | 9 | 4 | 1.4 |
| 2026-03-21T05:56:16Z | 21 | 1-1 | 3.5 | 2.75 | 2.375 |
| 2026-03-21T06:16:45Z | 41 | 1-1 | 3.75 | 2.4 | 2.6 |
| 2026-03-21T06:17:05Z | 42 | 1-2 | 11 | 4.333 | 1.363 |
| 2026-03-21T07:24:26Z | 91 | 1-2 | 101 | 8 | 1.083 |
| 2026-03-21T07:25:11Z | 92 | 2-2 | 13 | 1.09 | 15 |
| 2026-03-21T07:26:03Z | 92 | 2-2 | 15 | 1.062 | 17 |
| 2026-03-21T07:26:22Z | 93 | 2-3 | 351 | 13 | 1.04 |
| 2026-03-21T07:26:35Z | 93 | 2-3 | suspended | | |
| 2026-03-21T07:27:52Z | 94 | 2-2 | 21 | 1.025 | 23 |

A 2-3 appears in Bet365's feed at its minute 93 and is withdrawn a minute later: the goal did not stand. The
equaliser is at minute 92 on Bet365's clock and 90+3 in the events table: each counts minutes in its own way,
and both are delivered as the source sent them. Quotes are never smoothed: a suspended market is an empty price
with `Suspended` = 1.

157 in-play Bet365 1X2 quotes on this match alone, 1,858 quotes from
the 5 books in all, and the lineups, the events (the missed penalty included), the team statistics and the
minute-by-minute statistics of the same match in the other tables.

```python
import pandas as pd

o = pd.read_csv("sample/odds_timestamped/AsiaAfrica_Odds_Timestamped_JPN.csv.gz", dtype={"Match_ID": str})
live = o[(o.Match_ID == "11248363") & (o.Book == "Bet365") &
         (o.Market == "FT_1X2") & (o.Phase == "In-play")]
print(live[["Timestamp_UTC", "Minute", "Score_Home", "Score_Away",
            "Price_Home", "Price_Draw", "Price_Away", "Suspended"]].to_string())
```

---

## Eight tables, one key

Everything joins on `Match_ID`. No fuzzy name matching.

| File | One row per | Key content |
|---|---|---|
| `AsiaAfrica_Matches.csv` / `.xlsx` | match | season, tournament, stage, matchday, leg, kickoff, scores HT / 90' / AET / penalties, aggregate, table positions, formations, managers, referee, venue, neutral-venue flag |
| `AsiaAfrica_Opening_Closing_Odds.csv` / `.xlsx` | match | open and close per book and market, each with its time |
| `odds_timestamped/` (7 × `.csv.gz`) | price update | book, market, phase, prices, line, score, clock, suspension, UTC, epoch |
| `bookmaker_snapshots/` (7 × `.csv.gz`) | snapshot | 37 more books: first and last pre-match snapshot, with minutes before kickoff |
| `AsiaAfrica_Team_Stats.csv` / `.xlsx` | match × team | 29 metrics incl. xG |
| `lineups/` (7 × `.csv.gz`) | player × match | starters, subs, shirt, position |
| `events/` (7 × `.csv.gz`) | event | 13 event types with minute and player |
| `minute_stats/` (7 × `.csv.gz`) | stat × minute | running stats minute by minute |

Plus `AsiaAfrica_Coverage.csv` / `.xlsx`: one row per league and season, coverage of every table and book in %.

The complete column dictionary, the seasons, tournaments and stages of every league, the coverage tables and the
integrity notes are in `sample/README.md`, the README shipped with the product.

**Nothing a spreadsheet can reinterpret.** Scores, minutes and shoot-outs are separate integer
columns. Timestamps are full ISO 8601 with the T and the Z, plus an epoch. Formations are digits
(4231 = 4-2-3-1), so 4-4-2 never becomes 4 April 2002. Seasons read 2016/17 or 2019. Every cell
was audited against Excel auto-conversion patterns at write time: zero risky cells. A closing price
is never an in-play price.

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Research, modelling and internal use permitted.
Redistribution and resale of the files are not.

A question before buying: contact@oliviersportsdata.com

---

👉 ⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/gxvqou?utm_source=github&utm_medium=repo&utm_campaign=asia_africa_premium&utm_content=readme_bottom)** 👈

---

*Olivier Sports Data — From Chicken Area 🐔*
Hand-built historical sports market data.
