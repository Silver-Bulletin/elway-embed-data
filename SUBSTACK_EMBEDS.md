# Permanent direct Substack embeds

Substack does not allow `silver-bulletin.github.io` as an iframe source. Paste
the complete contents of the corresponding file under `direct/` into the
Substack HTML/code embed instead.

These files are permanent. Their JavaScript fetches the explicitly approved
CSV release from this repository, so future weekly releases do not require any
Substack editing.

Hardened embeds verify each downloaded CSV against the release manifest, keep
only a 24-hour verified emergency cache, and clear legacy unversioned caches.
If neither the hosted release nor its approved Google Sheet can be verified,
the embed shows a temporary-unavailable message instead of rendering the
historical rows bundled with the original chart shell.

| Chart | Direct-paste file |
| --- | --- |
| ELWAY team ratings | `direct/SUBSTACK_01_ELWAY_TEAM_RATINGS.html` |
| ELWAY offense/defense | `direct/SUBSTACK_02_ELWAY_OFFENSE_DEFENSE.html` |
| ELWAY standings | `direct/SUBSTACK_03_ELWAY_STANDINGS.html` |
| ELWAY win totals | `direct/SUBSTACK_04_ELWAY_WIN_TOTALS.html` |
| ELWAY conditional odds | `direct/SUBSTACK_05_ELWAY_CONDITIONAL.html` |
| ELWAY future games | `direct/SUBSTACK_06_ELWAY_FUTURE_GAMES.html` |
| ELWAY margins | `direct/SUBSTACK_07_ELWAY_MARGINS.html` |
| QBERT leaderboard | `direct/SUBSTACK_08_QBERT_LEADERBOARD.html` |
| QBERT game-by-game | `direct/SUBSTACK_09_QBERT_GAME_BY_GAME.html` |
| Compare QB careers | `direct/SUBSTACK_10_QBERT_COMPARE_CAREERS.html` |
| ELWAY team rating trends | `direct/SUBSTACK_11_ELWAY_RATING_TRENDS.html` |
| QBERT depth charts | `direct/SUBSTACK_12_QBERT_DEPTH_CHARTS.html` |
| Best and worst QBs of 2026 | `direct/SUBSTACK_13_QBERT_SEASON_TABLE.html` |
| Lifetime QBERT leaderboard | `direct/SUBSTACK_14_QBERT_LIFETIME_TABLE.html` |
| 2026 quarterback projections | `direct/SUBSTACK_15_QBERT_PROJECTIONS_TABLE.html` |

The seven QBERT embeds show a visible update timestamp in Eastern Time, tied
to the verified data being displayed. Opening a page or searching does not
advance that timestamp. Replace previously pasted HTML once to add this label.

The three complete tables (13–15) preserve the supplied screenshot designs,
including 15-row pages, search, ratings colors, WAR bars, and player highlights.
They include the verified November 14 snapshot and retain it, or a newer
checksum-verified cache, with its original timestamp if a refresh fails. These
three tables check for approved releases on load, every five minutes, and when
the page becomes visible again. The explicit public-feed exporter includes
their three canonical output Sheets; ordinary model/Sheets updates still do
not publish them.
