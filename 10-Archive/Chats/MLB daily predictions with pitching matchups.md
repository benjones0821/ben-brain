---
type: note
status: archived
updated: 2026-08-31
source: claude-chat
chat_url: https://claude.ai/chat/8770ec4c-6a7c-4c9e-aa3b-451296cf2f1f
started: 2026-08-30
---

# MLB daily predictions with pitching matchups

Full transcript of the Claude chat "MLB daily predictions with pitching matchups" (6 messages, 2026-08-30 to 2026-08-31). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Archive Index]]

---

### Ben · 2026-08-30 15:30

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

### Claude · 2026-08-30 15:32

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used web_search: MLB probable pitchers August 30 2026*

> *Claude used web_fetch: https://oddsguy.ai/mlb/pitchers/today*

> *Claude used web_fetch: https://deepmetricanalytics.com/mlb/probable-pitchers*

> *Claude used web_search: MLB game predictions win probability August 30 2026 slate*

> *Claude used web_fetch: https://www.dimers.com/mlb/predictions*

> *Claude used web_search: Red Sox Sunday August 30 2026 starting pitcher Yankees Ranger Suarez*

> *Claude used web_search: Wrigley Field wind forecast Sunday August 30 2026 Reds Cubs weather*

All 14 starters are confirmed today — no TBDs on the board. No Coors game either (Colorado's in Atlanta), so the park factors that matter most are Wrigley at night and the Trop dome.

## Reasoning

**The one real mismatch: Braves over Rockies (1:35 ET).** Dimers' sim has Atlanta at 67.8%, the highest number on the slate, and it's almost entirely a talent gap — Atlanta's 81-55 against a 52-84 Colorado club that's been dreadful on the road. Worth flagging that the *starter* edge cuts the other way on paper: Mason Adams carries a 2.25 ERA versus Tyler Mahle's 4.54. That's why I'd fade this one heavily in the F5 market relative to the full game — the Braves' advantage comes from the lineup depth and bullpen, not the first three innings.

**Best pitching edge: Wheeler at the Angels (4:07 ET).** Zack Wheeler against Yusei Kikuchi with a 52-84 Angels team behind him is the cleanest ace-vs-mediocrity spot of the day. Model has Philly at 61.2%, and this is the one game where I'd take the F5 number *above* the full game — Wheeler's the most likely arm on the slate to hand off a lead after five.

**Messick over Lugo (1:40 ET).** Parker Messick's 2.54 ERA against Seth Lugo's 4.72, at home, against a 62-75 Royals team. 60.4% full game, and this is my second-favorite F5 spot after Wheeler.

**Milwaukee and Tampa Bay round out the value.** Brewers at 58.5% hosting Texas — Dustin May (4.57) isn't the driver here, the 85-51 record and the bullpen are, so it's a full-game play more than an F5 one. Rays at 58.3% over San Diego with Rasmussen vs. Robbie Ray, indoors at the Trop, which removes weather noise entirely.

**Seattle is the sneaky one.** Dimers has the Mariners at 55% *on the road* in Toronto, which only makes sense when you see Scherzer's 7.40 ERA against Logan Gilbert's 3.37. Toronto's fallen to 67-70. It's not in my top five full-game picks because 55% is thin, but the F5 number should be meaningfully higher than the full game — probably the third-biggest starting-pitcher gap today.

**Games to avoid:** Marlins-Nationals is a literal coin flip (49.5/50.5) and it's the noon game with the least information. Pirates-Cardinals at 51.4/48.6 is the same story. Orioles-Athletics at 52.4% is close enough that a Sutter Health Park bounce decides it. Red Sox-Yankees at 52.5% has a genuine starter edge for Boston (Suárez's underlying numbers are strong; Warren's been hit hard lately) but two elite bullpens compress everything after the sixth — which is exactly why it's a better F5 lean than a full-game one.

**Weather note:** Wrigley at 7:20 is 85° with a 12 mph SSW breeze pushing out toward left and a 29% shower chance. That's a home-run-friendly setup that cuts into Imanaga's 56.8% — I'd shade the Cubs down a couple points and skip it despite the number.

Full Game
1. Braves (vs Rockies) — 68% — confirmed (Mahle / Adams) — 1:35 PM ET
2. Phillies (vs Angels) — 61% — confirmed (Wheeler / Kikuchi) — 4:07 PM ET
3. Guardians (vs Royals) — 60% — confirmed (Messick / Lugo) — 1:40 PM ET
4. Brewers (vs Rangers) — 59% — confirmed (May / Rocker) — 2:10 PM ET
5. Rays (vs Padres) — 58% — confirmed (Rasmussen / Ray) — 1:40 PM ET

First 5 Innings
1. Phillies (vs Angels) — ~64% — confirmed (Wheeler / Kikuchi) — 4:07 PM ET
2. Guardians (vs Royals) — ~62% — confirmed (Messick / Lugo) — 1:40 PM ET
3. Mariners (vs Blue Jays) — ~61% — confirmed (Gilbert / Scherzer) — 1:37 PM ET
4. Braves (vs Rockies) — ~57% — confirmed (Mahle / Adams) — 1:35 PM ET
5. Dodgers (vs Tigers) — ~57% — confirmed (Glasnow / Valdez) — 1:40 PM ET

---

### Ben · 2026-08-31 19:06

Check yesterdays and do again today 
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

### Claude · 2026-08-31 19:08

I'll check how yesterday's picks landed, then work today's slate.

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

> *Claude used fetch_sports_data*

Yesterday's picks are graded. Now let me pull today's slate.

> *Claude used web_fetch: https://oddsguy.ai/mlb/pitchers/today*

> *Claude used web_fetch: https://www.dimers.com/mlb/predictions*

> *Claude used web_search: Giants vs Braves prediction August 31 2026 win probability Bryce Elder Molina*

> *Claude used web_search: Orioles Rockies August 31 2026 starting pitcher Coors Field Bradish*

> *Claude used web_search: Yankees Angels August 31 2026 probable pitchers Ureña Klassen Elmer Rodríguez*

## Yesterday's grade (Aug 30)

**Full Game: 4–1.** Braves ✅ (3-2 in 10), Phillies ✅ (5-2), Guardians ✅ (11-1), Rays ✅ (5-4). Only Milwaukee missed — Texas took it 7-4.

**First 5: 2–1–2.** Guardians ✅ (9-1 through five), Braves ✅ (2-0). Mariners ❌ — Gilbert gave up three and Scherzer went seven scoreless, exactly the wrong side of that 7.40 ERA read. Phillies and Dodgers both **pushed** — Wheeler and Glasnow each pitched well but their teams were tied 1-1 after five and did the damage in the 7th and 8th. Worth noting for the F5 market: an ace edge often shows up as a low-scoring tie, not a lead.

## Today's reasoning

**Two TBDs, and one of them matters.** Baltimore hasn't officially listed a starter at Coors (Bradish is the expected line-up-the-rotation answer but Camden Chat notes it's TBD all the way down the series), and Arizona hasn't posted against Nola. Flagged below.

**Top of the board: deGrom vs. the Athletics (8:05 ET).** Dimers has Texas at 62.6%, the highest number on the slate, and it's the cleanest ace mismatch — Jacob deGrom against rookie Gage Jump and a 53-84 A's club. This is my best full-game *and* F5 spot; the gap only widens if you weight the first three innings.

**Braves at home, riding a seven-game streak (6:05 ET).** Market has Atlanta around -158/-170, which de-vigs to roughly 61%. The real driver isn't Bryce Elder's 3.95 ERA — it's that San Francisco is using **Anthony Molina as an opener** (9.1 career MLB innings, 6.60 ERA) with a 4.35 bullpen behind him. Atlanta is 48-23 at home against a Giants team 23-45 on the road. That opener setup is why I like the F5 here even more than the full game.

**Astros and Red Sox round out the solid tier.** Houston at 58.7% hosting a White Sox team that's cooled — Peter Lambert vs. Anthony Kay is close on paper, so this is more a lineup/home play than an F5 one. Boston at 57.0% is the opposite: Payton Tolle (3.08) against George Kirby (4.04) is a genuine starter edge, so it grades better in the F5 market than the full game.

**Sneaky F5: Padres at Cincinnati (6:40 ET).** San Diego's only 54.8% for the full game, but Michael King (3.38) against Brady Singer (4.74) is a bigger gap than that number suggests. Great American is a bandbox and the Reds bullpen compresses things late — take the innings where King is on the mound.

**Coors, and why I'm passing.** Baltimore-Colorado is the one park factor tonight: total opened 10.5-11, Coors runs ~13% above league average, and Bradish's walk rate is exactly the wrong profile at altitude. Baltimore's 56.6% is a legitimate number and they've won five of seven, but between the TBD starter and the fact that Bautista and Helsley are both on the IL, the variance is too high for a top-five slot.

**Games to avoid:** Phillies-Diamondbacks at 51.8/48.2 is a coin flip, and the pitching actually runs the wrong way for my side (Nola's 5.03 vs. Pfaadt's 2.69, with Arizona still unconfirmed). Miami-Washington has no clean model number and two mediocre teams. And I'm skipping Yankees-Angels despite the 56.7%: sources disagree on the Angels starter — MLB.com lists Walbert Ureña (2.94 ERA), while Pinstripe Alley and CBS both have Mitch Farris. Dimers built its number off a third name entirely, so that 56.7% probably isn't priced on the pitcher who actually takes the ball. Brewers-Cubs at 53.4% is a real matchup (Clay Holmes at 2.51 is legit) but too thin to rank.

Full Game
1. Rangers (vs Athletics) — 63% — confirmed (deGrom / Jump) — 8:05 PM ET
2. Braves (vs Giants) — 61% — confirmed (Elder / Molina) — 6:05 PM ET
3. Astros (vs White Sox) — 59% — confirmed (Lambert / Kay) — 8:10 PM ET
4. Red Sox (vs Mariners) — 57% — confirmed (Tolle / Kirby) — 6:45 PM ET
5. Rays (vs Mets) — 57% — confirmed (Seymour / Stock) — 6:40 PM ET

First 5 Innings
1. Rangers (vs Athletics) — ~63% — confirmed (deGrom / Jump) — 8:05 PM ET
2. Braves (vs Giants) — ~62% — confirmed (Elder / Molina) — 6:05 PM ET
3. Red Sox (vs Mariners) — ~58% — confirmed (Tolle / Kirby) — 6:45 PM ET
4. Padres (vs Reds) — ~57% — confirmed (King / Singer) — 6:40 PM ET
5. Rays (vs Mets) — ~56% — confirmed (Seymour / Stock) — 6:40 PM ET

---

### Ben · 2026-08-31 19:20

Marlins Washington over

---

### Claude · 2026-08-31 19:21

> *Claude used web_search: Marlins Nationals August 31 2026 total over under Gusto Dion prediction*

Marlins-Nationals is at **8.5** most places (a few books at 9), with the Over around -120 to -122. Here's the honest split, because the models don't agree on this one.

**The Over case is mostly about bullpens, not starters.** Neither guy goes deep — Gusto hasn't reached the sixth in five straight turns, and Dion has never been asked past the fifth, with Washington likely scripting an opener in front of him. That means relievers cover eight to ten innings between the two clubs. Washington's pen is the weak link: 4.94 ERA, 1.46 WHIP, 1.36 HR/9, with Kranick (7.41 since returning) and Cosgrove (7.71) both having worked Sunday's ninth. Nationals home games have gone over at a 41-27-2 clip this season.

**The Under case is the bats.** Miami has hit .211 over its last ten games at 6.9 hits per contest, and Xavier Edwards is day-to-day with a thumb injury — that's their OBP and speed guy out of the top of the order. Miami is at a .693 OPS against lefties for the season and .640 in August, which is a bad draw against Dion. One computer forecast projects the game at 3.98–3.22 and puts the over at just 41% on a 9-run total.

**Where I land:** it's a lean, not a conviction. The Over needs Washington's pen to get exposed early, which is the likeliest single path to a crooked number, but it's fighting two offenses that have genuinely stopped hitting. If you're taking it, 8.5 is meaningfully better than 9 here — that half run is doing real work in a game projected around 7. First pitch 6:45 PM ET on FS1.
