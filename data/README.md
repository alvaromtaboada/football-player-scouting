# Input data

The data files are **not included** in this repository. Place them in this folder before running the notebook.

| File | Content | Source |
|---|---|---|
| `FBREF_players_2223.csv` | Player season stats 2022/23 for seven leagues (Premier League, La Liga, Serie A, Bundesliga, Ligue 1, Primeira Liga, Eredivisie). `;`-separated, 3,996 rows. | Compiled from [FBref](https://fbref.com); provided by the thesis supervisor |
| `fbref_to_tm_mapping.csv` | FBref ↔ Transfermarkt player ID mapping (only needed for the market value validation, section 5) | [worldfootballR_data](https://github.com/JaseZiv/worldfootballR_data/tree/master/raw-data/fbref-tm-player-mapping/output) |
| `player_valuations.csv` | Transfermarkt market value history (section 5) | [Kaggle: davidcariboo/player-scores](https://www.kaggle.com/datasets/davidcariboo/player-scores) |

`FBREF_players_2223.csv` is not redistributed here. Any FBref season export with the same columns can be used instead.

If the two Transfermarkt files are missing, section 5 is skipped and the rest of the notebook runs as normal.
