# LP75 open sports data

Open data from three small independent sports sites run by Libor Pavlíček (LP75), Czech Republic:
[SazkyWeb.cz](https://sazkyweb.cz), [SazkyTip.cz](https://sazkytip.cz) and [EuroFootballPicks.com](https://eurofootballpicks.com).
Model predictions, season simulations, Czech hockey tables and a public, timestamped record of every tip, including the losing ones.

The files are copies of the data the sites publish themselves under `/data/`; this repository is updated automatically, usually every morning (Central European Time).

## Datasets

| File | What it contains | Source page |
|---|---|---|
| [`sazkyweb/tipy-lp75.json`](sazkyweb/tipy-lp75.json) | Every tip by LP75 with odds, timestamp and result, plus the overall record | [sazkyweb.cz/bilance-tipu-lp75.html](https://sazkyweb.cz/bilance-tipu-lp75.html) |
| [`sazkyweb/dnes.json`](sazkyweb/dnes.json) | Today’s sports programme followed by SazkyWeb | [sazkyweb.cz/tipsport-kurzy-dnes.html](https://sazkyweb.cz/tipsport-kurzy-dnes.html) |
| [`sazkyweb/extraliga-tabulka.json`](sazkyweb/extraliga-tabulka.json) | Czech hockey Extraliga table | [sazkyweb.cz/extraliga-2026-27.html](https://sazkyweb.cz/extraliga-2026-27.html) |
| [`sazkyweb/extraliga-bodovani.json`](sazkyweb/extraliga-bodovani.json) | Czech hockey Extraliga scoring leaders | [sazkyweb.cz/extraliga-2026-27.html](https://sazkyweb.cz/extraliga-2026-27.html) |
| [`sazkyweb/maxa-liga-tabulka.json`](sazkyweb/maxa-liga-tabulka.json) | Czech hockey second tier (Maxa liga) table | [sazkyweb.cz/maxa-liga-2026-27.html](https://sazkyweb.cz/maxa-liga-2026-27.html) |
| [`sazkyweb/maxa-liga-bodovani.json`](sazkyweb/maxa-liga-bodovani.json) | Maxa liga scoring leaders | [sazkyweb.cz/maxa-liga-2026-27.html](https://sazkyweb.cz/maxa-liga-2026-27.html) |
| [`sazkyweb/nhl-cesi-slovaci.json`](sazkyweb/nhl-cesi-slovaci.json) | Czech and Slovak players in the NHL: last game and season stats | [sazkyweb.cz/nhl-2026-27.html](https://sazkyweb.cz/nhl-2026-27.html) |
| [`sazkyweb/simulace-sezony.json`](sazkyweb/simulace-sezony.json) | Season simulations (20,000 runs): title, top 4 and relegation chances in the Premier League, LaLiga, Serie A, Bundesliga and Ligue 1 | [sazkyweb.cz/premier-league.html](https://sazkyweb.cz/premier-league.html) |
| [`sazkyweb/simulace-extraliga.json`](sazkyweb/simulace-extraliga.json) | Czech Extraliga season simulation | [sazkyweb.cz/extraliga-2026-27.html](https://sazkyweb.cz/extraliga-2026-27.html) |
| [`sazkyweb/simulace-maxa.json`](sazkyweb/simulace-maxa.json) | Maxa liga season simulation | [sazkyweb.cz/maxa-liga-2026-27.html](https://sazkyweb.cz/maxa-liga-2026-27.html) |
| [`sazkytip/predikce-vikendu.json`](sazkytip/predikce-vikendu.json) | Weekend football predictions (Czech): expected goals and 1X2 chances | [sazkytip.cz](https://sazkytip.cz/) |
| [`eurofootballpicks/predictions.json`](eurofootballpicks/predictions.json) | Weekend predictions for eight European leagues: xG, 1X2, over 2.5, both teams to score | [eurofootballpicks.com/predictions.html](https://eurofootballpicks.com/predictions.html) |
| [`eurofootballpicks/fpl-fixtures.json`](eurofootballpicks/fpl-fixtures.json) | FPL fixture ratings: expected goals, clean sheet and win chance for every Premier League team over the next three gameweeks | [eurofootballpicks.com/fpl-fixtures.html](https://eurofootballpicks.com/fpl-fixtures.html) |

All files are UTF-8 JSON. Each file says when it was updated; most also say where the data comes from.

## License

[Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You can use the data for anything, including commercially, if you credit the source with a link, for example:
“Data: [SazkyWeb.cz](https://sazkyweb.cz)” or “Data: [EuroFootballPicks.com](https://eurofootballpicks.com)”.

## Notes

- Predictions and simulations come from a simple goals and xG model (Poisson). They are probabilities, not certainties.
- Nothing here is betting advice. Betting is for adults (18+) only and can be addictive.
- Found an error or missing something? Open an issue.

## Česky

Otevřená data webů SazkyWeb.cz, SazkyTip.cz a EuroFootballPicks.com: predikce, simulace sezon, tabulky a bodování extraligy a Maxa ligy, Češi a Slováci v NHL a kompletní bilance tipů LP75 s časovým razítkem. Licence CC BY 4.0 — použití s uvedením zdroje a odkazem. Přehled dat i na [sazkyweb.cz/otevrena-data.html](https://sazkyweb.cz/otevrena-data.html). 18+, sázení může vyvolat závislost.
