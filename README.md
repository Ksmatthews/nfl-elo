# NFL Elo Ratings

A simple, 538-style Elo model for the NFL: power rankings, win probabilities, and point spreads for every game.

**How it works:** every team started 2016 at 1500. After each game, the winner takes rating points from the loser, with more points for upsets and bigger margins. Ratings move a third of the way back toward average each offseason. The full method is on the page's Method tab.

**Data:** scores and schedules load automatically from [nflverse](https://github.com/nflverse/nfldata) each time the page opens, so the ratings stay current without manual updates.

**Features**
- Current power rankings, with each team's record and movement this season
- Win probability and projected spread for every upcoming game
- What-if scores for unplayed games (saved only on your device)
- Adjustable K-factor, home-field advantage, and offseason regression

The whole site is one file, `index.html`, with no build step.
