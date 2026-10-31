# Top 25 Hoops

### ▶ Open the site: **[ncaawb.netlify.app](https://ncaawb.netlify.app)**

Live scores, odds, box scores and the AP poll for every announced game of the preseason AP Top 25 in women's college basketball, opening tip through the end of the regular season. It's a website, so there's nothing to download or install. Open the link on any phone or computer.

## What's on it

- **Calendar** of every game, with team filters and a "Top 25 clashes" view of ranked-vs-ranked matchups
- **Live scores** that refresh every 15 seconds during games, with the quarter and clock, a progress bar and score flashes
- **Final scores** and each team's top scorer on every finished game
- **Odds**: spread, moneyline and over/under (DraftKings, via ESPN), with movement since the line opened and whether the favorite covered
- **Game details**: scoring by quarter, win probability, game leaders, ESPN's matchup predictor, full box score, team stat comparison and play-by-play
- **AP Top 25** from ESPN each week, with movement, points, first-place votes, records and others receiving votes
- **Teams**: game log, season stats and player averages built from every box score, and the roster with photos
- **Box scores** for every game: live during the game (refreshing every 15 seconds), final afterward, and a preview of each team's top players before tip
- **Player pages**: tap any player in a box score, roster or leaders list for her photo and bio, this season's averages, recent games, full game log by season, and career stats by season with home/away splits
- **My teams**: star the teams you follow. They lead the team list, get a star on the calendar, have their own filter, and the top card follows their next game
- **Game alerts** for your teams (and optionally every Top 25 clash): tip-off, close game late, and final score. Alerts come while the site is open in a tab or as a home-screen app; on iPhone, add it to your Home Screen first
- **Live view**: every game today side by side with scores, clock, win probability and the latest play
- **Standings** for the SEC, ACC, Big Ten, Big 12 and Big East, with conference and overall records, streaks, home/away and record vs. the AP Top 25
- **Stat leaders** among players on the Top 25 teams: points, rebounds, assists, steals, blocks, 3s, shooting percentages, double-doubles and minutes, filterable by conference
- **Search** any team or player (press **/** on a computer)
- **Postseason**: conference tournament and NCAA Tournament games appear on the calendar as ESPN schedules them, and the **Bracket** view shows the whole tournament with live scores (last season's bracket is there now)
- Full-screen game, team and player pages
- Team logos, light and dark mode, and drag-to-scroll on anything that moves sideways
- Tip times and TV networks fill in from ESPN as they're announced
- All times Eastern. "Today" rolls over at 4 AM ET, so late games stay on the night they were played.

## Add it to your phone's home screen

**iPhone:** open **[ncaawb.netlify.app](https://ncaawb.netlify.app)** in Safari, tap **Share** (the square with an up arrow), then **Add to Home Screen**, then **Add**.

**Android:** open the link in Chrome, tap the **⋮** menu, then **Add to Home screen** (or **Install app**).

It opens full-screen like an app. Without signal it still opens and shows the last scores you loaded.

## How it works

The whole site is one page, `index.html`. Scores, odds, box scores, play-by-play, rosters and the poll come straight from ESPN's public feeds in your browser. Finished game days and box scores are saved in the browser, so they only download once.

- `sw.js` lets the site open offline and keeps the last scores you loaded
- `manifest.webmanifest`, `icon-*.png` and `splash-*.png` make it installable, with launch screens for iPhone
- `_headers` tells Netlify which files browsers should re-check and which they can keep

Every change pushed to `main` is published automatically by Netlify within about a minute.

Odds are for reference only.
