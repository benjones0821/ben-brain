---
type: note
status: done
updated: 2026-08-11
source: claude-chat
chat_url: https://claude.ai/chat/d489ea42-09c6-4ee5-8231-70d81f276494
started: 2026-08-11
---

# AI CRM Services Ranked by Cost

Full transcript of the Claude chat "AI-powered CRM services ranked by cost" (38 messages, 2026-08-11 to 2026-08-11). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Saved Chats]]

---

### Ben · 2026-08-11 20:19

best ai services to build a crm rank by cost

---

### Claude · 2026-08-11 20:20

I'll look up current pricing on the main options.

> *Claude used web_search: AI app builder pricing 2026 Lovable Replit Bolt*

Let me check current pricing directly from a few sources.

> *Claude used web_search: Lovable pricing plans credits*

> *Claude used web_search: Claude Code Cursor pricing plans 2026*

> *Claude used web_search: Base44 pricing Bolt.new pricing tiers 2026*

> *Claude used web_search: Anthropic Claude Haiku Sonnet API pricing per million tokens 2026*

Costs split into three separate line items here, and "cheapest" depends on which one you're actually buying. Ranked low to high within each:

**1. AI app builders — you describe the CRM, it builds it (no code required)**

- **Base44** — $16/mo annual, $20/mo monthly, cheapest entry point. Bundles database, auth, and hosting automatically, which suits CRM work well. Catch: code export, custom domains, and backend functions are locked behind the ~$40/mo tier, and unused credits don't roll over — you also can't buy top-ups, only upgrade.
- **Replit Core** — $20/mo. Built-in PostgreSQL and hosting, the most complete infrastructure of the builders. Best if you want to read and fix the code when the agent gets stuck.
- **Bolt Pro** — $25/mo for 10M tokens, with tokens rolling over one extra month. Strongest for fast visual prototypes, weakest if you need real backend depth.
- **Lovable Pro** — $25/mo (Business $50), 100 credits. Usually the best-looking first output and it wires up Supabase for you. Realistic warning from one review: a CRUD app with auth can eat 30–60 credits on the initial build alone — and a CRM is exactly that.

**2. Coding agents — if you or someone on the team writes code**

- **Cursor** — free Hobby tier, Pro $20/mo, Pro+ $60, Ultra $200, Teams $40/user. Cursor's own guidance is that daily agent users typically need $60–100/mo in total usage.
- **Claude Code** — no separate subscription; it's included in Claude Pro (~$17/mo annual), Max 5x at $100, Max 20x at $200, and Team tiers. On Pro, it draws from the same limit as your regular Claude chats.

These don't include hosting or a database, so add Supabase/Neon plus Vercel or similar on top.

**3. The AI features inside the CRM itself — usage-based, and the one people forget**

Lead scoring, email summarization, and note extraction are per-token. Haiku 4.5 runs $1/$5 per million input/output tokens, Sonnet 5 is $2/$10 through August 31, Opus 5 is $5/$25. Batch requests are 50% off and cache hits cost 10% of base input. Most CRM enrichment is classification and extraction — Haiku territory — so a small team's realistic spend here is single-digit to low-double-digit dollars monthly.

Two things worth knowing before you pick: nearly every builder meters by credits or tokens, so the subscription bundles a pool that feels flat right until it empties and usage charges start. Heavy Replit users have reported $100–300/mo on top of the base plan. Budget 2–4x the sticker price for the build month.

If you want my actual pick: Base44 or Lovable if you won't touch code, Cursor or Claude Code plus Supabase if you will — and it's worth pricing an off-the-shelf CRM like Attio or HubSpot first, since a CRM is one of the most commoditized categories out there and building one only pays off if your data model is genuinely unusual.

---

### Ben · 2026-08-11 20:28

give me a bunch of company names that arent taken for an ai business helper we help business set up ai within their comapnies give me a list of 100

---

### Claude · 2026-08-11 20:29

I can't verify availability for 100 names — that needs a live domain and USPTO check, and anything I claimed here would be stale by the time you read it. So I've weighted this list toward coined words and unusual pairings, which have much better odds than the obvious stuff. Check each one at a registrar plus [tmsearch.uspto.gov](https://tmsearch.uspto.gov) before you get attached.

**Coined words (best availability odds)**
1. Adoptiq
2. Enablr
3. Instilla
4. Augmenta
5. Praxio
6. Deploya
7. Implementia
8. Kaptiv
9. Fluenta
10. Adaptiv Works
11. Embedra
12. Scalera
13. Novaturn
14. Aptivo
15. Cognita Works
16. Werkstra
17. Intellra
18. Sagentic
19. Corvex
20. Ovanta

**Plain-English pairings**
21. Quiet Deployment
22. Working Intelligence
23. Practical Intelligence
24. The Adoption Company
25. Second Shift AI
26. First Deployment
27. Ready State
28. Steady State AI
29. Standard Practice
30. House Model
31. Common Practice AI
32. Daily Practice
33. Plain Machine
34. Honest Automation
35. Sensible Machines
36. Modest Machines
37. Quiet Machines
38. Real Deployment
39. Actual Intelligence
40. Business As Usual AI

**Trade and craft metaphors**
41. Millwright AI
42. Toolmaker Group
43. Ironwright
44. Journeyman AI
45. Bench & Rule
46. Plumbline AI
47. Keystone Works
48. Joinery AI
49. Mortise
50. Tenon Labs
51. Anvilworks
52. Forgehouse
53. Whetstone AI
54. Loomcraft
55. Warp & Weft
56. Kilnhouse
57. Smithline
58. Groundwork Intelligence
59. Bricklayer AI
60. Sawhorse Systems

**Navigation and guidance**
61. Waypoint Intelligence
62. Throughline AI
63. Compass Draw
64. Pathfold
65. Wayfinder Works
66. Ridgeline AI
67. Portage AI
68. Fordline
69. Landfall AI
70. Bearing & Course
71. Truenorth Works
72. Beacon Fold
73. Lodestar Works
74. Cairnstone
75. Deadreckon

**Latin and classical**
76. Fabrica AI
77. Novum Works
78. Facere Labs
79. Opera Prima
80. Adhibeo
81. Pro Tempore
82. Instrumenta
83. Ratio Works
84. Ars Machina
85. Modus Works
86. Vera Machina
87. Primum Labs
88. Concinnity
89. Solvitur
90. Fabrile

**Short and mechanical**
91. Ledgerline
92. Switchboard AI
93. Dialtone
94. Crankset
95. Ratchet Works
96. Cogwork
97. Spindle AI
98. Torque House
99. Gearline
100. Keelworks

A few honest flags: anything in the "plain-English" block using common words is likelier to hit a trademark conflict in consulting or software classes even when the .com is free, and I'd bet against **Ratchet**, **Spindle**, and **Switchboard** being clear. The coined-word block is where your real odds are, and it's also where you can get an exact-match .com without paying a domain squatter four figures.

One thing worth weighing as you narrow down: names that lean on "AI" as a suffix tend to age badly. Your clients are hiring you because AI is currently hard and unfamiliar — in five years that's plumbing, and a name built around the trade you actually practice (adoption, deployment, making it stick) outlasts the label on the technology.

---

### Ben · 2026-08-11 20:29

our names are adi ethan ben

---

### Claude · 2026-08-11 20:30

Nice — founder-derived names age well for exactly the reason I mentioned last time: they don't expire when the technology stops being novel. Same caveat, check each before you commit.

**Initials (A, B, E)**
1. Abe — genuinely clean, reads as a name not an acronym
2. Abe Works
3. Abe & Partners
4. Bea Systems — flag: close to the old BEA Systems, likely a conflict
5. Aebe
6.三 no — **Ternary** (three of you, and it's a real technical term)

**Blends of two names**
7. Bethan — Ben + Ethan, a real Welsh name, elegant
8. Benthan — reads like a surname
9. Adeben — Adi + Ben
10. Adethan
11. Ethadi
12. Benadi
13. Nadeb
14. Ethanbe
15. Abethan
16. Bethadi

**Words hidden in your combined letters** (a, d, i, e, t, h, a, n, b, e, n)
17. Adhibent — Latin, roughly "they apply" or "they put to use." Every letter comes from your three names. My favorite on this list.
18. Abinet
19. Bandeth
20. Beadwork — from BE + AD
21. Beadline
22. Habiten
23. Tenabi
24. Denabi
25. Binate
26. Nadith
27. Bandit — all your letters, but the vibe is wrong for enterprise clients
28. Adbe — flag: too close to Adobe, don't

**Three-part composites**
29. Adethben — honestly clunky, included for completeness
30. Aden & Beth
31. Adi Ethan Ben — the literal law-firm structure, works better than people expect
32. AEB Group
33. Beth Aden
34. Adenbeth

**Surname-style inventions**
35. Adenby
36. Bethani Group
37. Ebandi
38. Nabeth
39. Adenthal
40. Bethaden

My picks from this: **Adhibent** if you want something with weight and a story you can tell in a first meeting, **Bethan** if you want something warm and pronounceable that clients remember after one call, and **Abe** if you want the shortest path to a memorable brand — though a three-letter .com is almost certainly gone, so you'd be looking at abe.works, abeworks.com, or similar.

One structural thought: the literal partnership format (option 31) signals something the coined words don't — that three named people are accountable for the work. For a services business where clients are nervous about handing over their internal processes, that's worth more than a clever name.

---

### Ben · 2026-08-11 20:31

leeds gold jones are our last names

---

### Claude · 2026-08-11 20:31

Best raw material yet — and one thing jumps out immediately: **Leeds is a homophone for "leads."** For a company selling to businesses, that's either a gift or a permanent spelling correction on every phone call. Worth deciding early which.

**Classic partnership**
1. Leeds Gold Jones
2. Gold Leeds Jones
3. Jones Gold Leeds
4. LGJ Partners
5. Leeds & Gold
6. Gold & Jones
7. Leeds Gold
8. Gold Jones Partners

**Gold-forward** (by far your strongest single word)
9. Gold Standard — literally sitting in your surnames, and it's precisely what you're selling
10. Goldline
11. Goldwork
12. Goldleaf AI
13. Goldseam
14. Goldrule
15. Gold & Grain
16. Assay — what you do to gold, and it means "to test and evaluate"
17. Karat Works
18. Fine Gold — the technical term for unalloyed gold
19. Bullion Works
20. Touchstone — the stone used to test gold's purity, and it already means "a standard of quality"

**Leeds / leads wordplay**
21. Leeds Line
22. Leedsworth
23. True Leeds
24. Leeds & Co
25. Leedsmith

**Blends and inventions**
26. Goldleeds
27. Leedsgold
28. Jonesgold
29. Goldsmith Jones
30. Leedsmith Gold
31. Golden Jones
32. Jones & Seam

**Trade-metaphor hybrids** (picking up the craft direction from earlier)
33. Goldsmith Works
34. Crucible — where gold is refined, strong fit for transformation work
35. Smeltworks
36. Refinery Jones
37. Assay Group
38. Hallmark Works — a hallmark literally certifies gold's purity
39. Ingot
40. Millwright Gold

**My picks:** **Touchstone** is the standout — it's a real gold term hidden in your name, it already means "benchmark of quality," and it says what a consultancy does without saying AI. **Assay** is the sharper, shorter version of the same idea. **Leeds Gold Jones** is the safest and most credible for enterprise buyers.

**Honest flags on this batch:** *Gold Standard* is a phrase in wide commercial use and will be crowded in consulting trademark classes even if a domain variant is free. *Goldsmith* collides with a very well-known executive-coaching brand — I'd avoid it for a business-advisory firm specifically. *Jones* is among the most common surnames in the English-speaking world, so it gives you almost no trademark protection standing alone. And *Leeds* will read as the English city to any UK or European client, which matters if you plan to sell there.

If it were my firm, I'd run **Touchstone** with the partnership name as the legal entity — Leeds Gold Jones LLC trading as Touchstone. You get the credibility of three named partners on the contract and a brand that doesn't need explaining.

---

### Ben · 2026-08-11 20:32

tropical type of words one word names

---

### Claude · 2026-08-11 20:32

Tropical words carry warmth and growth, which is a real asset for a consultancy — though it's a slightly odd fit for enterprise AI buyers, so I've flagged the ones that could read as a beach resort or a juice brand.

**Plants and growth**
1. Verdant
2. Canopy
3. Frondly
4. Liana
5. Bromel
6. Epiphyte
7. Rootstock
8. Understory
9. Buttress — from buttress roots, and it already means structural support
10. Heliconia
11. Palmwork
12. Mangrove
13. Bamboo
14. Ceiba
15. Kapok
16. Banyan — one tree that becomes a whole grove, strong metaphor for scaling
17. Tamarind
18. Papaya
19. Guava
20. Lychee

**Spices and trade goods**
21. Cardamom
22. Nutmeg
23. Clove
24. Vanilla — flag: means "plain" in English, exactly wrong for you
25. Turmeric
26. Saffron
27. Cinnabar
28. Allspice
29. Cassia
30. Anise
31. Copal
32. Sandalwood

**Geography and water**
33. Lagoon
34. Atoll
35. Isthmus
36. Reefline
37. Delta — flag: airline plus a large trademark footprint
38. Estuary
39. Tidewater
40. Archipel
41. Shoal
42. Trade Winds
43. Monsoon
44. Doldrums — beautiful word, but it means stagnation
45. Latitude

**Sun, heat, climate**
46. Solstice
47. Equator
48. Tropic
49. Zenith — flag: crowded, an old TV brand
50. Meridian — flag: heavily used in consulting and banking
51. Sunward
52. Torrid
53. Ember

**Birds and fauna**
54. Toucan
55. Macaw
56. Quetzal
57. Iguana
58. Cicada
59. Kingfisher
60. Hummingbird
61. Manta

**Coined tropical**
62. Verdia
63. Tropica
64. Canopia
65. Selva — Spanish for rainforest
66. Terrarium
67. Solara
68. Palmara
69. Bahia
70. Isla

**My picks:** **Banyan** — a single tree that spreads into an entire connected grove, which is exactly what embedding AI across a company looks like. **Canopy** is the runner-up: it implies covering and shelter, and it's already common in B2B naming so it won't read as frivolous. **Buttress** is the sleeper — a tropical-root word that literally means structural support, and almost nobody has used it.

**Flags worth knowing:** the fruit names (papaya, guava, lychee, mango-adjacent) will consistently read as food or beverage brands, which fights against enterprise credibility. **Banyan** and **Canopy** both already appear in financial services and software, so trademark clearance in your class is the real question, not domain availability. And bear in mind the tropical direction abandons the founder-name equity you had with Touchstone or Leeds Gold Jones — worth being deliberate about, since the tropical route buys you memorability but gives up the "three accountable partners" signal that tends to close deals in advisory work.

---

### Ben · 2026-08-11 20:34

space related

---

### Claude · 2026-08-11 20:34

Fair warning up front: space is the most picked-over naming territory in tech. Nearly every clean one-word option is taken by a rocket company, a VC fund, or a SaaS product. So I've weighted toward the obscure end — orbital mechanics terms, deep-sky catalog objects, and navigation words that haven't been strip-mined.

**Orbital mechanics** (best odds — technical, rarely used)
1. Apsis
2. Perigee
3. Apogee — flag: used by several funds
4. Periapsis
5. Barycenter — the shared center two bodies orbit, good partnership metaphor
6. Syzygy
7. Libration
8. Precession
9. Inclination
10. Ephemeris
11. Deltavee
12. Sidereal
13. Prograde
14. Escape Velocity
15. Perihelion
16. Aphelion
17. Anomaly — real orbital term, but the plain-English meaning works against you
18. Nodal
19. Vernier
20. Injection Burn

**Navigation and reckoning**
21. Astrolabe
22. Sextant
23. Azimuth
24. Declination
25. Parallax
26. Culmination
27. Transit
28. Occultation
29. Alidade
30. Gnomon

**Structures and hardware**
31. Gantry
32. Umbilical
33. Payload
34. Aperture
35. Reticle
36. Coronagraph
37. Interferometer
38. Truss
39. Airlock
40. Cupola

**Deep sky and catalog objects**
41. Messier
42. Caldwell
43. Bode
44. Herschel
45. Lagrange — the stable point between two bodies, excellent metaphor
46. Oort
47. Kuiper
48. Roche
49. Chandra
50. Hubble — flag: heavily used

**Stars and constellations**
51. Vega — flag: car, and crowded
52. Rigel
53. Altair
54. Deneb
55. Mizar
56. Alcor — the companion star to Mizar, historically used as a vision test
57. Capella
58. Antares
59. Bellatrix — flag: Harry Potter association is now dominant
60. Sirius — flag: satellite radio
61. Canopus
62. Arcturus
63. Spica
64. Zubeneschamali — included because it's magnificent, not because you should use it

**Physical phenomena**
65. Aurora — flag: extremely crowded
66. Corona — flag: beer, plus pandemic association
67. Penumbra
68. Umbra
69. Sublime — the actual physics term for solid to gas
70. Accretion
71. Nucleosynthesis
72. Redshift — flag: Amazon product
73. Albedo
74. Terminator — the day/night line on a planet, but the film association is total
75. Zodiacal

**My picks:** **Barycenter** is the strongest for you specifically — it's the point three bodies orbit around, which is a genuinely apt three-partner metaphor, and it's technical enough that it's almost certainly clear. **Lagrange** is the runner-up: a stable point that lets you park something permanently, which is a nice description of successfully embedded AI. **Alcor** and **Mizar** are clean, short, pronounceable, and far less picked over than the famous star names.

**The category-level flag:** space names signal ambition and scale, but they're also the default choice for AI startups right now, so you'd be entering an extremely noisy field. Compared to **Touchstone** — which sits inside your actual surnames and means "standard of quality" — a space name gives you less differentiation for more trademark risk. Worth being honest that the last three directions have each been further from something only you could own.

---

### Ben · 2026-08-11 20:34

aura related

---

### Claude · 2026-08-11 20:35

Two flags before the list. **Aura** itself is heavily occupied — there's a well-known digital security and identity company, a smart frame brand, and a meditation app all using it, so the bare word is off the table. And "aura" has been running hot as internet slang for a couple of years now ("aura points," "aura farming"), which reads as young and jokey — fine for a consumer app, awkward on a proposal to a CFO. Worth being deliberate about.

**Direct variants and coinages**
1. Aurelis
2. Auralis
3. Aurent
4. Aurexa
5. Auravant
6. Aurio
7. Auren
8. Aurastack
9. Auralux
10. Aurabound
11. Aurava
12. Aurwork

**Latin roots** (aurum = gold, aura = breeze/glow, aurora = dawn)
13. Aurum — ties back to Gold in your surnames, which is a real advantage
14. Aureate
15. Aurelian
16. Aurifer — Latin for "gold-bearing"
17. Aurific
18. Aurora — flag: extremely crowded
19. Aurelius — flag: strong Marcus Aurelius association, plus several funds
20. Auric
21. Aurality
22. Aurige

**Glow and emanation**
23. Nimbus — the halo in classical art, also a cloud
24. Halo — flag: the game franchise dominates
25. Lumen
26. Luminance
27. Effulge
28. Radiance
29. Glimmer
30. Suffuse
31. Corona — flag: beer, plus pandemic association
32. Gloriole — the technical art term for a halo
33. Mandorla — the almond-shaped halo in religious art, genuinely obscure
34. Vesica

**Atmosphere and presence**
35. Ambient
36. Emanate
37. Presence
38. Numen — Latin for a presiding spirit or divine presence
39. Numina
40. Pneuma — Greek for breath or spirit
41. Anima
42. Ether
43. Aether
44. Zephyr
45. Miasma — beautiful sound, but it means a noxious cloud

**Light physics**
46. Refract
47. Diffuse
48. Umbral
49. Penumbral
50. Luminal
51. Photic
52. Iridesce
53. Chroma
54. Spectra
55. Prismatic

**Field and energy**
56. Fieldwork
57. Resonant
58. Vector Field
59. Fluxline
60. Magnetite
61. Lodestone — the naturally magnetic rock, and it shares a root with "lodestar"

**My picks:** **Aurum** is the standout — it's the Latin for gold, so it quietly carries Gold's surname into the brand, it sounds premium, and it's aura-adjacent without being the crowded word itself. **Nimbus** and **Lodestone** are the next best: both are real objects with real meanings, both sound solid rather than mystical.

The general risk with this whole category is that aura-family names lean spiritual and ephemeral, and you're selling operational rigor to businesses. **Aurum** and **Lodestone** survive that tension because they're metals; **Numen**, **Pneuma**, and **Radiance** don't.

If you want, I can pressure-test your top three or four finalists across all six directions — sound, spelling on a phone call, trademark crowding, and how they'd read on a slide in front of a client.

---

### Ben · 2026-08-11 20:36

more

---

### Claude · 2026-08-11 20:37

More in the aura vein, digging into less obvious corners:

**Halo and corona physics**
1. Antisolar
2. Sundog — the real name for the bright spots flanking a low sun
3. Parhelion — the technical term for a sundog
4. Glory — the ring of light around a shadow cast on cloud
5. Brocken
6. Airglow — the faint permanent glow of the night atmosphere
7. Zodiacal
8. Gegenschein
9. Heiligenschein — German, the halo around your own shadow on dewy grass
10. Alpenglow

**Bioluminescence and natural light**
11. Foxfire — the glow of fungus on rotting wood
12. Noctiluca
13. Lucifer — flag: obviously
14. Luciferin — the actual compound that makes fireflies glow
15. Photophore
16. Milky Seas — the rare glowing-ocean phenomenon
17. Wisp
18. Ignis
19. Elmo — from St. Elmo's fire, the glow on ship masts
20. Corposant — the older English name for the same thing

**Perception and the felt sense**
21. Qualia — the felt quality of an experience
22. Gestalt
23. Salience
24. Affect
25. Valence
26. Percept
27. Apperception
28. Sensorium
29. Umwelt — the perceptual world an organism inhabits
30. Gravitas

**Mineral and metal glow**
31. Lustre
32. Sheen
33. Patina
34. Chatoyant — the cat's-eye shimmer in gemstones
35. Adularescent
36. Opaline
37. Schiller — the metallic shimmer in certain minerals
38. Labradorite
39. Vermeil — gold over silver, ties to Gold again
40. Gilt

**Warmth and radiant heat**
41. Kindle — flag: Amazon owns this space
42. Emberline
43. Smolder
44. Thermal
45. Insolation — the technical term for incoming solar radiation
46. Irradiance
47. Blackbody
48. Firelight
49. Hearthglow
50. Caldera

**Coined, aura-adjacent**
51. Auracle — aura + oracle, though it may read as "auricle," the ear
52. Auravia
53. Lumina
54. Luminari
55. Aurastone
56. Glowform
57. Radia
58. Nimbra
59. Auralith
60. Emberaura

**Best of this batch:** **Chatoyant** and **Schiller** are the genuinely rare ones — real optical terms, almost certainly clear, though Chatoyant is hard to spell over the phone. **Vermeil** keeps the gold thread going and sounds expensive. **Umwelt** and **Qualia** are the intellectual picks; they'd land well with a technical buyer and confuse everyone else. **Airglow** and **Alpenglow** are the most pronounceable.

Realistically, this is the point where breadth stops helping. You've now got roughly 350 options across six directions, and the constraint isn't supply — it's that you three have to agree, and then run clearance. My honest read is that **Touchstone**, **Aurum**, and **Leeds Gold Jones** are still the three strongest things to come out of any of these lists, because each one is anchored to something only you have. If you name four or five finalists, I'll stress-test them properly instead of adding a seventh category.

---

### Ben · 2026-08-11 20:38

periodic table related

---

### Claude · 2026-08-11 20:38

Element names are a well-worked seam in tech naming, so the common ones are gone — but the periodic table is deep, and the obscure lanthanides and the technical vocabulary around them are much cleaner.

**Precious and noble metals** (keeps the Gold thread)
1. Aurum — already my pick from last round, Latin for gold
2. Iridium — flag: satellite network
3. Osmium
4. Rhodium
5. Ruthenium
6. Palladium — flag: crowded, several funds and a well-known analytics firm's neighbor
7. Rhenium
8. Electrum — the natural gold-silver alloy, and a lovely word
9. Argentum
10. Vermeil

**Lanthanides** (the least picked-over shelf)
11. Praseodym
12. Neodym
13. Samarium
14. Gadolin
15. Terbium
16. Dysprosium — from the Greek for "hard to get at," which is a nice quiet joke
17. Holmium
18. Erbium
19. Thulium
20. Ytterbium
21. Lutetium
22. Cerium
23. Yttria
24. Scandia

**Structural and refractory**
25. Tantalum
26. Niobium
27. Hafnium
28. Zirconia
29. Vanadium
30. Tungsten
31. Wolfram — flag: Wolfram Research owns this outright
32. Molybden
33. Titania
34. Chromia

**Noble gases**
35. Xenon — flag: crowded
36. Krypton — flag: Superman
37. Argon — flag: several software products
38. Neon — flag: very crowded
39. Radon — flag: it's a health hazard
40. Helion — a helium nucleus, and far cleaner than Helium itself

**Periodic-table vocabulary** (strongest category here)
41. Valence — bonding capacity, and it means "the power to combine"
42. Isotope
43. Covalent — a bond formed by sharing, good partnership metaphor
44. Lattice
45. Alloy — flag: used, but the meaning is perfect for what you do
46. Crucible
47. Catalyst — flag: extremely crowded in consulting
48. Reagent
49. Substrate
50. Nucleon
51. Orbital
52. Periodic
53. Atomic Number
54. Mendeleev
55. Actinide
56. Transuranic
57. Halide
58. Amalgam
59. Ductile
60. Malleable

**Symbol-based** (two-letter plays)
61. AuAg — gold and silver
62. Element 79 — gold's atomic number
63. Seventy Nine
64. Au Works
65. Group Eleven — the column gold sits in
66. Period Six

**My picks:** **Covalent** is the best fit on this list — it means a bond where partners share rather than one giving to the other, which is precisely the pitch for embedding AI inside a client's team rather than doing it for them. **Electrum** is the aesthetic winner and keeps Gold's name alive. **Valence** is short, real, and means combining power.

**Flags:** most element names ending in *-ium* now read as either a crypto token or a biotech, so they carry a category signal you may not want. **Element 79** and **Group Eleven** are cute but require explanation every time, which is a tax you pay forever.

This is now seven directions and something like 400 names. The honest constraint isn't options anymore — it's that **Touchstone**, **Aurum**, **Covalent**, and **Leeds Gold Jones** keep outperforming anything a new category produces, because each is anchored to either your actual names or your actual work. Name your finalists and I'll pressure-test them on trademark crowding, phone-call spelling, and how each reads on a slide in front of a client.

---

### Ben · 2026-08-11 20:40

one word super tuff become a complete naming expert

---

### Claude · 2026-08-11 20:40

Here's how a professional namer actually attacks "one word, tough." Toughness in a name comes from four things: **hard consonants** (k, g, t, d, b, x), **one or two syllables**, **short vowels**, and a **real referent** — something that exists in the physical world and takes force. Soft names die on the last one. Every name below is built to those rules.

**Tools that cut and shape**
1. Adze
2. Maul
3. Broadaxe
4. Chisel
5. Auger
6. Rasp
7. Bandsaw
8. Punchwork
9. Drift — the tool that forces a hole open
10. Grubaxe

**Metal under force**
11. Forge
12. Quench
13. Temper — heat-treating for toughness, and it's a real character word
14. Anneal
15. Draw — the actual term for pulling metal into wire
16. Swage
17. Upset — the forging term for compressing hot metal
18. Billet
19. Slag
20. Bloom — the raw iron mass from a furnace

**Stone and earth**
21. Granite
22. Basalt
23. Gabbro
24. Bedrock
25. Cragwork
26. Scree
27. Quarry
28. Boulderworks
29. Hardpan
30. Ballast

**Structural load**
31. Girder
32. Truss
33. Rebar
34. Keystone
35. Buttress
36. Piling
37. Abutment
38. Cantilever
39. Bulwark
40. Anchorage

**Machines that grip and drive**
41. Ratchet
42. Torque
43. Crank
44. Winch
45. Capstan
46. Clamp
47. Vise
48. Gearbox
49. Piston
50. Flywheel

**Old English brutes**
51. Grit
52. Brunt
53. Stark
54. Blunt
55. Steadfast
56. Hardwrought
57. Ironclad
58. Doughty — archaic for brave and stubborn
59. Fastness — a stronghold
60. Withstand

**Coined hard**
61. Kordax
62. Bexton
63. Draxos
64. Vertek
65. Kovar — a real alloy name
66. Torvex
67. Braxis
68. Gantrik
69. Durak
70. Kesteel

---

**Now the expert part — how to judge these.**

The four names on that list that would survive professional scrutiny are **Bulwark**, **Bedrock**, **Anneal**, and **Temper**. Here's why, and the reasoning transfers to anything you consider.

**Semantic fit beats sound.** A tough name has to be tough *about the right thing*. **Anneal** means heating metal so it becomes less brittle and more workable — that is exactly what a company does when it absorbs a new technology. **Temper** is the same idea with a character double-meaning. **Maul** and **Ratchet** sound tough but describe damage and grinding. Wrong story.

**Toughness is easy; distinctiveness is hard.** Trademark strength runs on a spectrum: coined words are strongest, arbitrary words next, suggestive after that, and descriptive words get almost no protection. **Bedrock** and **Keystone** are suggestive and heavily crowded — you'd be fighting for a narrow slice. The coined block (61–70) has the best legal protection but zero built-in meaning, so you pay to teach it.

**The three-channel test.** Every finalist has to survive: said aloud on a bad phone line, typed from memory into a browser, and printed on a slide next to your client's logo. **Doughty** fails channel two. **Gabbro** fails channel one. **Bulwark** passes all three and means "a defensive structure that holds."

**Clearance order.** Domain check first because it's free and instant, then USPTO at tmsearch.uspto.gov in classes 35 and 42 — business consulting and software services, which is where you'll live. A free .com with a live mark in your class is a trap, not a win.

**My call:** **Bulwark** is the strongest one-word tough name for this business. It's short, hard-consonant, unmistakably solid, and it means protection through structure — which is what a company hiring you actually wants when it's nervous about AI. **Anneal** is the more sophisticated pick if you want something that rewards explanation.

I'd still rank **Touchstone** above both, because it means "the standard against which quality is measured" and it came out of your own surnames. But if tough is the brief, Bulwark is the answer.

---

### Ben · 2026-08-11 20:41

i want an x at the end

---

### Claude · 2026-08-11 20:41

Before the list, the two things a namer would tell you about terminal -x, because they'll shape which of these you pick.

The -x suffix peaked hard around 2014–2019 and is now the single most crowded ending in tech naming. It reads fast and technical, but it also reads *dated* to anyone who's been watching brands — and critically, it gives you almost no trademark distinctiveness, because examiners and courts treat a bolted-on X as a weak differentiator. **Aurex** does not reliably clear you past an existing **Aura** mark. Names where the X is *structural* to the word rather than a suffix hold up much better.

**X-native words** (strongest — X belongs there)
1. Apex
2. Vertex
3. Vortex — crowded
4. Matrix — very crowded
5. Nexus — crowded
6. Codex
7. Index
8. Helix — crowded
9. Silex — Latin for flint
10. Culex
11. Murex — the sea snail that produced imperial purple dye
12. Fornax — the furnace constellation
13. Pollux
14. Styx
15. Onyx
16. Borax
17. Thorax
18. Larynx
19. Phalanx — a tight formation that holds, good partnership metaphor
20. Sphinx

**Built from your surnames**
21. Goldex
22. Aurex
23. Aurumx
24. Leedex
25. Jonex
26. Ledex
27. Auralex — flag: existing acoustics brand
28. Goldrex

**Tough-direction hybrids**
29. Bulwarx — loses the word, don't
30. Forgex
31. Anvex
32. Temprex
33. Ironx
34. Craggex
35. Girdex
36. Torqex
37. Grittex
38. Steelx
39. Anneax
40. Bedrox

**Coined, clean-sounding**
41. Adoptix
42. Enablix
43. Deployx
44. Praxix
45. Kaptix
46. Novarex
47. Solvex
48. Ventrix
49. Cognex — flag: existing public company, avoid
50. Adaptrix
51. Instillex
52. Fluentx
53. Werkx
54. Ternx
55. Bethanx

**Latin and Greek roots ending in X**
56. Radix — the root
57. Calyx
58. Pyx — the container for something precious
59. Ilex
60. Lynx
61. Rex — too common, and it means king, which is a posture problem
62. Crux — the essential point, and short
63. Flux
64. Nix — means "nothing," wrong signal
65. Sax
66. Latex — no
67. Sulcx
68. Vernix — it's the coating on a newborn, look it up before using it

**My picks:** **Codex** and **Crux** are the two I'd actually put in front of a client — both are real words where the X is load-bearing, both are short, both mean something relevant (a codex is an authoritative book of knowledge; a crux is the decisive point). **Phalanx** is the tough-brief answer and the three-partner metaphor is genuinely apt. **Radix** is the clean, underused technical pick.

**Flags:** Codex now has a strong association with an OpenAI product, which is either helpful or confusing depending on your positioning — worth a real decision, not an accident. Anything in block 41–55 is a coined -x and will need clearance, but those have your best odds. And I'd skip every name in block 29–40 that mangles a real word into an X ending; **Bulwarx** and **Anneax** lose the meaning that made the originals good and gain nothing.

Straight assessment: this constraint costs you more than it gives. **Touchstone**, **Covalent**, and **Bulwark** all outperform every name on this page on distinctiveness and on how they'd age. If the X is non-negotiable, take **Crux** or **Codex** — real words, not suffixes.

---

### Ben · 2026-08-11 20:42

give me a company slogan for a business that helps businesses incorportate ai within their company wherever needed

---

### Claude · 2026-08-11 20:42

Slogans work differently from names — a name can be abstract, but a tagline has to make a promise. Here they are sorted by the promise each one makes, since that's the real choice.

**The "we make it stick" promise** (my strongest angle for you)
1. AI that stays after we leave.
2. We don't install AI. We embed it.
3. Built to outlast the pilot.
4. From pilot to practice.
5. The part after the demo.
6. Adoption, not deployment.
7. We finish what the pilot started.

**The "where it actually helps" promise**
8. AI where it earns its place.
9. Only where it works.
10. The right AI in the right places.
11. We find the parts worth automating.
12. AI, applied precisely.
13. Not everywhere. Where it matters.

**The "we handle the hard part" promise**
14. You know your business. We know the machine.
15. The hard part, handled.
16. We do the wiring.
17. Your work, faster. Your rules, intact.
18. We make the introduction.

**Short and confident**
19. AI, made ordinary.
20. Make it routine.
21. Practical intelligence.
22. Quietly transformative.
23. Intelligence, installed.
24. Everyday AI.

**Skeptic-friendly** (good if your buyers are burned out on hype)
25. No hype. Just throughput.
26. Fewer slides. More systems.
27. We're not here to sell you AI.
28. Proof before promises.
29. The unglamorous part of AI.

**Partnership-forward** (fits three named founders)
30. Three people who've done this before.
31. We stay until it's yours.
32. Beside you, not above you.

---

**My pick: "AI that stays after we leave."**

It works because it names the specific failure your buyers have already lived through — the consultant left and the tool died — and positions you against it in seven words. It's a promise a competitor can't casually copy without sounding like they're admitting the same problem.

Runner-up: **"From pilot to practice."** Tighter, more professional, and it maps cleanly onto how companies actually talk about this internally.

**Pairing note:** the slogan should do work the name doesn't. With **Touchstone**, you want a tagline about *fit and judgment* — "AI where it earns its place" — because Touchstone already implies standards. With **Bulwark** or **Covalent**, go with "AI that stays after we leave," since those names signal solidity but not the aftercare.

One honest flag: number 27 is memorable but risky. It's a strong opener in a room, and a confusing line on a website where visitors have three seconds to work out what you sell.

---

### Ben · 2026-08-11 20:42

longer and more specific

---

### Claude · 2026-08-11 20:42

Longer taglines earn their length by naming a specific situation — the buyer should read it and think "that's my company." Sorted by which pain each one names.

**The failed pilot**
1. Most companies have run an AI pilot. Almost none have kept one running.
2. Your team tried ChatGPT for a month and quietly stopped. We fix the reason why.
3. The pilot worked. Then the champion left, and so did the tool. We build for what happens after.
4. Every company we meet has three abandoned AI projects. We're the fourth one that works.

**Where to actually apply it**
5. We spend the first two weeks finding the twelve processes worth automating — and the forty that aren't.
6. Not every problem in your business needs AI. We tell you which four do, then we build those.
7. We map your workflows before we touch a model, because the expensive mistake is automating the wrong thing well.
8. AI in the back office, in the pipeline, in the parts of your company nobody demos.

**Handover and independence**
9. We embed AI into your operations, train your people to run it, and leave you a system you own outright.
10. Six months in, your team should be shipping without us. That's the whole job.
11. We don't want a permanent seat at your table. We want your operations team to stop needing one.
12. No black boxes, no vendor lock-in, no quarterly retainer for something you should own.

**Anti-hype, for skeptical buyers**
13. No transformation decks. We pick one workflow, prove the numbers, then do the next one.
14. We'd rather ship one system that saves four hours a week than present a roadmap that saves nothing.
15. If AI isn't the answer for your business, we'll tell you in week one and send you the invoice for one week.
16. Our first deliverable is a list of things you shouldn't build.

**Practitioner credibility**
17. Three operators who've deployed AI inside real companies, not three consultants who've read about it.
18. We've done this inside finance teams, ops teams, and sales teams — and we know which one breaks first.
19. We write the code, sit with your staff while they use it, and stay until the workarounds stop.

**Full positioning statements** (for a homepage hero, not a business card)
20. We help mid-sized companies find the parts of their operations that AI genuinely improves, build those systems, and train the team to run them without us.
21. Practical AI implementation for companies that are past the excitement and want to know what it actually costs, what it actually saves, and what it actually breaks.
22. We embed AI where it earns its place in your business — then hand you the keys, the documentation, and a team that knows how to drive it.

---

**My pick: number 9.** It's the clearest full-sentence version of your differentiator, it names three concrete deliverables (embed, train, own), and "outright" quietly kills the lock-in objection before a prospect raises it.

For a homepage, I'd pair a short line with a longer one: **"AI that stays after we leave"** as the headline, then **number 5** or **number 9** as the subhead. That structure — punchy promise, specific proof — converts better than either alone.

Two flags. Number 15 is a genuinely strong trust play, but only make it if you'll honor it; a promise like that gets tested. And number 4 is memorable in a pitch and slightly insulting in print — save it for a room, not a website.

---

### Ben · 2026-08-11 20:42

now create names that give a good ring to these slogans

---

### Claude · 2026-08-11 20:43

The test for a lockup is whether the name and the line say *different* things. If the name already means "we stay," the tagline shouldn't repeat it — it should say what you actually do. Here are pairs built that way.

**Names that mean staying power** (pair with a *specific-deliverable* line)

1. **Bulwark** — *We embed AI into your operations, train your people to run it, and leave you a system you own outright.*
2. **Anneal** — *We spend the first two weeks finding the twelve processes worth automating, and the forty that aren't.*
3. **Keelworks** — *Six months in, your team should be shipping without us. That's the whole job.*
4. **Bedstone** — *No black boxes, no lock-in, no retainer for something you should own.*
5. **Ballast** — *The pilot worked. Then the champion left. We build for what happens after.*
6. **Steadwork** — *We stay until the workarounds stop.*
7. **Holdfast** — the actual name for a mounting bracket, and it reads as a promise

**Names that mean judgment and fit** (pair with an *aftercare* line)

8. **Touchstone** — *AI that stays after we leave.*
9. **Assay** — *Our first deliverable is a list of things you shouldn't build.*
10. **Plumbline** — *Not everywhere. Where it matters.*
11. **Sightline** — *We map your workflows before we touch a model.*
12. **Bench & Rule** — *We'd rather ship one system that saves four hours a week than present a roadmap that saves nothing.*
13. **Caliper** — *We tell you which four problems need AI, then we build those.*

**Names that mean bonding and integration** (pair with an *independence* line)

14. **Covalent** — *We don't want a permanent seat at your table.*
15. **Weldline** — *From pilot to practice.*
16. **Grafthouse** — *We hand you the keys, the documentation, and a team that knows how to drive it.*
17. **Dovetail** — *Adoption, not deployment.*
18. **Inlay** — *We embed AI where it earns its place, then get out of the way.*

**Plain names that let the line carry everything**

19. **Leeds Gold Jones** — *Three operators who've deployed AI inside real companies, not three consultants who've read about it.*
20. **Second Shift** — *AI in the back office, in the pipeline, in the parts of your company nobody demos.*
21. **Working Practice** — *AI, made ordinary.*
22. **The Adoption Company** — *Most companies have run an AI pilot. Almost none have kept one running.*
23. **House Model** — *No transformation decks. One workflow, proven numbers, then the next one.*

**Short-and-hard names** (pair with a *skeptic* line)

24. **Crux** — *If AI isn't the answer for your business, we'll tell you in week one.*
25. **Grit Works** — *Fewer slides. More systems.*
26. **Forgehouse** — *We do the wiring.*
27. **Aurum** — *Proof before promises.*

---

**My pick: Touchstone / "AI that stays after we leave."**

The name means "the standard you measure against," the line makes the durability promise, and neither repeats the other. It also happens to sit inside your surnames, which no competitor can replicate.

**Strong runner-up: Bulwark**, with the long line as a subhead — hard consonants, unmistakable meaning, and the specificity underneath does the convincing.

Two flags. **Assay** and **Caliper** are excellent for a technical buyer and will lose a non-technical one — check who signs your contracts. And avoid pairing a solidity name with a solidity line: **Bulwark / "Built to outlast the pilot"** is redundant, and you'd be wasting the only two lines of copy most prospects will ever read.

---

### Ben · 2026-08-11 20:44

How do you like aurange

---

### Claude · 2026-08-11 20:45

Mixed, and one problem is bigger than the others.

**What works:** it carries the *aur-* gold root, so it keeps the Gold thread from your surnames — the same reason Aurum ranked well. It sounds French and slightly premium. And "range" is buried in there, which quietly suggests breadth of capability. Four syllables of pleasant sound.

**The serious problem: Orange.** Say "Aurange" out loud on a phone call and most listeners hear *Orange*. That's not a small overlap — Orange S.A. is a European telecom giant with an aggressive trademark enforcement record, and phonetic similarity is exactly the test examiners apply. If you plan to sell anywhere in the UK or Europe, this is a real clearance risk in classes 35 and 42, not a theoretical one. Even if you cleared it, you'd spend years being misheard.

**The second problem: pronunciation is undecided.** Is it aw-RANJ, OR-ahnzh, or AW-rain-j? A name that three people pronounce three ways loses the phone-call test permanently. You'd be spelling it on every intro call for the life of the company.

**The third, smaller one:** the *-ange* ending reads soft and cosmetic. It's a fragrance or a skincare line before it's an AI implementation firm. That fights the credibility you need with an operations buyer.

**If you like the sound, keep the root and change the tail:**

- **Auranth** — same opening, hard ending, no Orange collision
- **Aurange** → **Aurang** — drops the silent-e softness, but now reads Indonesian
- **Aurenge** — worse, doubles the ambiguity
- **Aurant** — clean, Latin-feeling, one clear pronunciation
- **Aurange Works** — the modifier doesn't fix the phonetic issue

**My honest verdict:** it's the weakest of the names you've gravitated toward, and **Aurum** does the same job better — same gold root, one obvious pronunciation, no telecom giant next door, and it sounds like metal rather than fruit.

If it's the *sound* you're drawn to rather than the meaning, tell me and I'll build a set around that phonetic shape without the Orange problem.

---

### Ben · 2026-08-11 20:46

Find one that is unique and hasn’t been used before and is super cool and give me a list

---

### Claude · 2026-08-11 20:46

One honest line first: I can't verify "hasn't been used" — that needs a live registrar and USPTO check. What I *can* do is weight heavily toward invented words and near-forgotten technical terms, where the odds are genuinely good rather than wishful.

**The one I'd actually give you: Remanence.**

It's the physics term for the magnetization a material keeps *after the external field is removed*. That is, precisely and literally, "AI that stays after we leave." It's a real word with a real meaning, it sounds expensive, it's four syllables of pure signal, and I've never seen it used as a company name in this space. Lockup: **Remanence — the part that stays after we go.**

**Rare real words, near-unused**
1. Remanence
2. Hysteresis — a system that keeps the shape of what happened to it
3. Adhibent — Latin, "they apply it to use"
4. Concinnity — the fitting-together of parts into a harmonious whole
5. Anneal
6. Umwelt
7. Chatoyant
8. Vermeil
9. Alcor
10. Barycenter
11. Mandorla
12. Foxfire
13. Sublime
14. Culmination
15. Holdfast

**Coined from meaning** (built from Latin roots, so they carry sense)
16. Aurient — *aurum* + orient: gold, and to give bearings
17. Insita — from *insitus*, grafted or implanted
18. Manent — from *manere*, to remain
19. Fabrile — of the craftsman
20. Solvence
21. Ferrant
22. Verrant
23. Aptivance
24. Instaura — from *instaurare*, to establish and renew
25. Duratos
26. Perstant — from *perstare*, to stand firm
27. Nexant
28. Kindral
29. Sedulon — from *sedulus*, persistent and diligent
30. Vestigent

**Pure invention** (best clearance odds, zero built-in meaning)
31. Kelvara
32. Orvane
33. Tesserene
34. Volandra
35. Cindral
36. Marrowe
37. Halcyn
38. Vantris
39. Obrean
40. Selvant

**My top four:** **Remanence**, **Hysteresis**, **Aurient**, **Concinnity**.

Hysteresis is the sleeper — it means a system whose current state depends on its history, which is a beautiful description of a company that's genuinely absorbed something. It's also hard to spell on a phone call, which is the tax.

Aurient keeps the gold root from your surnames and means "to give someone their bearings," so it works with a judgment-flavored line: *Aurient — we tell you which four problems need AI.*

Check Remanence first. If the .com is gone, remanence.works or the shortened **Remanent** are live options, and I'd still take either over anything in the invented block.

---

### Ben · 2026-08-11 20:48

Latin

---

### Claude · 2026-08-11 20:49

Latin is the right instinct for this business — it reads as durable and serious, which is exactly the register a nervous operations buyer wants. Grouped by what each one actually promises.

**Remaining and persisting** (your core differentiator)
1. **Manent** — "they remain." Short, clean, and it's the Latin engine under Remanence.
2. Permanet — it endures throughout
3. Perstant — they stand firm
4. Restat — it remains
5. Durabile
6. Sedulon — from *sedulus*, persistent and diligent
7. Firmitas — steadfastness, structural solidity
8. Constantia
9. Perdurans
10. Maneo — "I remain," first person, quietly personal

**Applying and putting to work**
11. **Adhibent** — "they apply it to use." Every letter comes from Adi, Ethan, Ben.
12. Applica
13. Utendo — by using
14. Instaura — to establish and renew
15. Inserere — to graft in, to embed
16. Insita — grafted, implanted
17. Adhaerens — adhering, sticking to
18. Innata — inborn, become natural
19. Conserere — to join together, to interweave
20. Aptare — to fit, to make suitable

**Craft and making**
21. **Fabrica** — the workshop, the act of construction
22. Fabrile — belonging to the craftsman
23. Opifex — the maker, the workman
24. Artifex — the skilled practitioner
25. Faber — the craftsman
26. Struere — to build up in layers
27. Machina
28. Ferramenta — iron tools
29. Officina — the workshop
30. Incus — the anvil

**Judgment and standards** (pairs with the Touchstone angle)
31. **Probare** — to test, to prove, to approve
32. Probitas
33. Examen — the tongue of a balance scale, hence examination
34. Libra — the scale itself
35. Norma — the carpenter's square, hence "standard"
36. Regula — the rule, the straightedge
37. Modus — the measure, the method
38. Ratio — reckoning, method, reason
39. Index — the one that points
40. Arbiter — the one who judges

**Gold and metal** (keeps the surname thread)
41. **Aurum**
42. Aurifer — gold-bearing
43. Obrussa — the fire-test for gold's purity, and genuinely obscure
44. Electrum
45. Metallum
46. Fornax — the furnace
47. Aes — bronze, and the root of "esteem"
48. Ferrum

**Foundations**
49. Fundamentum
50. Substruct
51. Radix — the root
52. Basis
53. Fulcrum — the point everything pivots on
54. Ancora — the anchor
55. Statera — the balance

---

**My top three, ranked:**

**Manent** — one word, two syllables, means "they remain," and it collapses your entire differentiator into six letters. Lockup: *Manent — the part that stays after we go.* Pronounceable on a phone call, spellable from hearing, and almost certainly clear.

**Adhibent** — means "they apply it to use," and it's an anagram of your three first names. That's a founding story you tell once and every client repeats. Slightly harder to spell aloud, which is the only knock.

**Obrussa** — the ancient fire-assay for testing gold's purity. It's the Latin cousin of Touchstone, it nods to Gold, and I'd be genuinely surprised if anyone has taken it.

**Flags:** *Fabrica*, *Libra*, *Index*, *Machina*, and *Ratio* are all heavily used — Libra especially, given the Meta currency project. And a general caution: Latin names need a plain-English tagline doing all the explaining, so budget your subhead accordingly. *Manent* with *"We embed AI into your operations, train your people, and leave you a system you own outright"* is a strong pairing precisely because the line is so concrete.

---

### Ben · 2026-08-11 20:49

Use instantdomainsearch.com and look for one that’s good

---

### Claude · 2026-08-11 20:50

Let me try.

> *Claude used web_fetch: https://instantdomainsearch.com*

> *Claude used search_mcp_registry*

I fetched the site but couldn't run live checks through it — Instant Domain Search returns results as you type via JavaScript, so a page fetch only gives me their marketing copy, not availability data.

Two ways forward. You can paste this shortlist straight into their [bulk domain search](https://instantdomainsearch.com/bulk-domain-search), which takes a list at once:

```
remanence.com
manent.com
obrussa.com
aurient.com
covalent.com
touchstone.com
bulwark.com
anneal.com
hysteresis.com
adhibent.com
concinnity.com
holdfast.com
barycenter.com
electrum.com
```

Or I can check them myself — there's a domain connector available that would let me run availability directly and report back on all fourteen.

> *Claude used suggest_connectors*

Connect that and I'll check the whole shortlist for you.

---

### Ben · 2026-08-11 20:52

Give me a huge list of potential names that aren’t being used that end in -ia or -x

---

### Claude · 2026-08-11 20:53

Weighted toward invented words and obscure Latin, since that's where availability actually lives. One quick expert note: both endings are crowded, but *-ia* has aged better than *-x* — it reads institutional rather than 2016-startup.

## Ending in -IA

**Built on "remain"** (your core promise)
1. Manentia
2. Perstantia
3. Restantia
4. Duratia
5. Firmitia
6. Sedulia
7. Perdurantia
8. Constia
9. Remania
10. Maneria

**Gold roots** (keeps the surname thread)
11. Aurentia
12. Aurifia
13. Obrussia
14. Electria
15. Vermelia
16. Aurmia
17. Karatia
18. Aurelia — flag: crowded
19. Aurantia — flag: orange in Latin, same trap as Aurange
20. Fornacia

**Craft and application**
21. Adhibia
22. Fabricia
23. Opifia
24. Artifia
25. Instauria
26. Insitia
27. Aptaria
28. Utendia
29. Struentia
30. Ferramentia

**Judgment and standards**
31. Probia
32. Normia
33. Regulia
34. Examia
35. Stateria
36. Libria
37. Modia
38. Arbitia
39. Calipria
40. Rationia

**Structure and solidity**
41. Fulcria
42. Radicia
43. Ancoria
44. Basaltia
45. Granitia
46. Trussia
47. Girdia
48. Ballastia
49. Keelia
50. Bulwaria

**Light and aura**
51. Lumenia
52. Nimbia
53. Auralia
54. Refractia
55. Chromia
56. Spectria
57. Penumbria
58. Iridia
59. Photia
60. Glorielia

**Orbital and celestial**
61. Apsidia
62. Barycia
63. Lagrania
64. Perigia
65. Siderea
66. Ephemia
67. Precessia
68. Nodalia
69. Syzygia
70. Alcoria

**Tropical**
71. Canopia
72. Verdia
73. Selvia
74. Liania
75. Kapokia
76. Banyania
77. Frondia

**Pure invention**
78. Velantia
79. Torvia
80. Kelvaria
81. Orvania
82. Cindria
83. Vantria
84. Obrenia
85. Marovia
86. Halcynia
87. Tesseria
88. Volandia
89. Corvia
90. Aptivia
91. Solvia
92. Ferrantia
93. Kindralia
94. Nexavia
95. Braxia
96. Sarnia
97. Delvaria
98. Ostravia
99. Lumaria
100. Quentia

## Ending in -X

**Real Latin words** (X is structural, not bolted on)
101. **Pontifex** — literally "bridge-builder." Flag: papal association, but the meaning is close to perfect for you.
102. Opifex — the maker
103. Artifex — the skilled practitioner
104. Simplex
105. Fornix — an arch
106. Salix — willow
107. Frutex
108. Grex — the herd, the group
109. Dux — the leader
110. Vellex
111. Silex — flint
112. Murex
113. Radix — the root
114. Calyx
115. Pyx — the vessel for something precious
116. Ilex
117. Cortex — flag: crowded
118. Varix
119. Rumex
120. Carex

**Coined on your roots**
121. Manex
122. Manix
123. Aurix
124. Aurax
125. Aurox
126. Adhibex
127. Obrux
128. Fabrex
129. Probex
130. Normex
131. Instaurex
132. Insitex
133. Fulcrex
134. Sedulex
135. Duratex — flag: existing building-materials firm

**Coined, clean**
136. Solvex
137. Ventrix
138. Aptrix
139. Praxix
140. Kaptrix
141. Verrex
142. Torvex
143. Braxix
144. Corvex
145. Kelvex
146. Orvex
147. Delvex
148. Vantrex
149. Selvex
150. Nexrant

**My picks from this batch:** **Manentia** is the strongest — it means "remaining, enduring," it's the -ia form of your best concept, and it sounds like a firm that's been around fifty years. **Pontifex** is the most interesting -x by a distance, because "bridge-builder" is literally the job; the Vatican association is the only thing to weigh. **Obrussia** and **Aurentia** both carry gold quietly. **Silex** and **Radix** are the cleanest short real-word options.

**Avoid:** Aurantia (the Orange problem again), Duratex, Cortex, Aurelia, and anything in the coined -x block that ends in *-trix*, which now reads distinctly early-2000s.
