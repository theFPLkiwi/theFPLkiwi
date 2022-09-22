# theFPLkiwi
Kiwi shared stats/resources

Find me on [Twitter](https://twitter.com/theFPLkiwi) as @theFPLkiwi, [reddit](https://www.reddit.com/u/theFPLkiwi), [ko-fi](https://ko-fi.com/thefplkiwi), or Discord in the FPL Analytics Community & FPL Review servers.

Files

1. Old_Seasons : Contains past data for hindsight optimisation as well as previous seasons' weekly projections.

2. FPL_projections : Weekly projections for the current FPL (Fantasy Premier League) season. PLEASE NOTE that not all players are represented and some players are given ID 0. The missing players are deemed to have left the league so all minutes and points are 0, although in reality they still have an FPL ID and may be selectable in-game. The players with ID 0 are players who might get some minutes but are not in the actual game yet for whatever reason, whether they are back from loan, youth players, or recent transfers. They are given a price of £3.0 due to not being in the game yet. When using this data in a solver designed to work with fplreview data, it may be necessary to remove these 0 IDs and insert the missing IDs with all 0s.

3. FanTeam projections : Weekly projections for the current FanTeam season. FanTeam uses slightly different scoring and pricing to FPL so merits a separate model.

4. 2022_IDs : A small file containing only fbref, FPL, and FanTeam IDs matched to aid in modelling

5. ID_Dictionary : A larger dictionary file that contains player IDs & names from FFScout, fbref, FPL, FanTeam as well as teams, prices & positions from the latter two and DoB for any age-related stats/modelling.

NOTE: This data can be used with Sertalp's solver via the instructions here: https://github.com/theFPLkiwi/webpage/blob/main/README.md
