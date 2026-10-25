---
type: note
status: done
updated: 2026-08-20
source: claude-chat
chat_url: https://claude.ai/chat/ff3e4504-a101-4b15-b5bc-89ea82005e03
started: 2026-08-20
---

# MLB Daily Predictions

Full transcript of the Claude chat "MLB daily predictions and pitching matchups" (2 messages, 2026-08-20 to 2026-08-20). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Saved Chats]] · [[MLB Daily Predictions (2)]]

---

### Ben · 2026-08-20 15:03

MLB Daily Predictions
Look into all of today’s MLB games. Use pitching matchups (and flag any starter that’s TBD vs confirmed), team quality/form, ballpark, and weather where it matters. Then give me two things, in this order:
1. Reasoning section — Rank the games and explain your picks. Cover the key drivers (ace pitching edges, mismatches, coin-flip games to avoid, any park/weather factors like Coors). Keep it to the games that matter for my picks.
2. Copy-paste list at the very end — Format exactly like this, no extra text:
Full Game
1. Team (vs Opponent) — XX% — confirmed/TBD (Pitcher / Pitcher) — TIME ET
2. … (top 5)
First 5 Innings
1. Team (vs Opponent) — ~XX% — confirmed/TBD (Pitcher / Pitcher) — TIME ET
2. … (top 5)
Rules:
* Use real model-based win probabilities for Full Game; label First 5 as your estimates weighted toward starting pitching.
* All times in ET.
* Mark any TBD starter with ⚠️.
* I’m a fan, not betting — skip the gambling disclaimers, just give me the picks.

---

### Claude · 2026-08-20 15:04

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used web_search: MLB probable pitchers August 20 2026*

> *Claude used web_fetch: https://www.mlb.com/probable-pitchers/2026-08-20*

> *Claude used web_fetch: https://baseballsavant.mlb.com/probable-pitchers*

> *Claude used web_search: MLB game projections win probability August 20 2026*

> *Claude used web_fetch: https://www.fanduel.com/research/mlb-betting-odds-08-20-2026*

> *Claude used web_search: MLB weather report today August 20 2026 wind forecast ballparks*

**No Coors today, and no TBDs — all 18 starters are confirmed.** Nine games, four in domes (Tropicana, American Family Field, Globe Life, Daikin), so weather only touches five.

## Reasoning

**The three games worth actually caring about**

**Houston (vs LAA), 8:10 PM** — the cleanest spot on the board. Market and numberFire land in the same place (~63%), which almost never happens today. Astros are .500 but the Angels are 50-77 and Grayson Rodriguez has been hittable against this lineup (84 career PA, .340 wOBA). Peter Lambert has quietly owned Angels hitters (.184, 34% K). Roof closed, no variables.

**Texas (vs WSH), 8:05 PM** — this is where the models split hard. The market has Texas around 61%; numberFire actually favors Washington at 50.2%. That gap is almost entirely a deGrom disagreement — he's 8-8 with a mediocre-looking 3.95 ERA, which is dragging the projection system down, but his stuff and his career line vs. this Nats roster (.091, .080 wOBA) say otherwise. I'm siding with the market and shading it to ~57%. Best F5 edge on the slate.

**Tampa Bay (vs TOR), 1:10 PM** — Rays are 76-50 and hosting a 62-66 Toronto club. But the pitching matchup argues the other way: Shane Bieber has smothered this Rays roster historically (.160, .244 wOBA), while Ian Seymour's 4.50 ERA and .325 opponent AVG vs. Blue Jays hitters is a real soft spot. That's why I have Tampa at ~65% full game but only ~55% first five — the edge is roster depth and bullpen, not the starter.

**The middle tier**

**Cleveland (vs SF)** — market says 64%, numberFire says 53%. Gavin Williams over Landen Roupp is a genuine edge and San Francisco is 52-74, but Cleveland's own offense is the reason for the model's hesitation. Split the difference at ~59%.

**Milwaukee (vs SEA)** — best record in baseball at 78-49, but Robert Gasser (4.54) is the worse starter here against George Kirby. Full-game lean is fine; the F5 is not. Fade it in the five-inning market.

**Coin flips to skip**

- **Braves at White Sox** — devigged market is 50.4/49.6. Grant Holmes projects for a 6.25 ERA in this spot and Kay has handled Braves hitters. Genuinely no edge either direction.
- **Yankees at Orioles** — Cole vs. Bradish is close to a wash, and Bradish's career line vs. New York (.191, 36% K) is better than most people assume. Wind 7 mph blowing in from the north at Camden suppresses the one thing that would decide it. ~53% is not a pick, it's a shrug.
- **Athletics at Royals** — two sub-.500 teams, Dobnak vs. a rookie, wind blowing in at Kauffman. Numbers say 50/50.
- **Cardinals at Reds** — the one place I'd take the underdog side in F5 only: McGreevy has been excellent against this Reds roster (.103, .201 wOBA in 43 PA), but Cincinnati's home-field and bullpen flip the full game back their way. That divergence is intentional.

Two of the five outdoor games carry some rain-delay risk, none look like postponement threats.

---

Full Game
1. Houston (vs Los Angeles Angels) — 63% — confirmed (Peter Lambert / Grayson Rodriguez) — 8:10 PM ET
2. Tampa Bay (vs Toronto) — 65% — confirmed (Ian Seymour / Shane Bieber) — 1:10 PM ET
3. Cleveland (vs San Francisco) — 59% — confirmed (Gavin Williams / Landen Roupp) — 1:10 PM ET
4. Texas (vs Washington) — 57% — confirmed (Jacob deGrom / Andrew Alvarez) — 8:05 PM ET
5. Milwaukee (vs Seattle) — 56% — confirmed (Robert Gasser / George Kirby) — 2:10 PM ET

First 5 Innings
1. Texas (vs Washington) — ~59% — confirmed (Jacob deGrom / Andrew Alvarez) — 8:05 PM ET
2. Houston (vs Los Angeles Angels) — ~57% — confirmed (Peter Lambert / Grayson Rodriguez) — 8:10 PM ET
3. Cleveland (vs San Francisco) — ~56% — confirmed (Gavin Williams / Landen Roupp) — 1:10 PM ET
4. Tampa Bay (vs Toronto) — ~55% — confirmed (Ian Seymour / Shane Bieber) — 1:10 PM ET
5. St. Louis (vs Cincinnati) — ~54% — confirmed (Michael McGreevy / Brady Singer) — 12:40 PM ET
