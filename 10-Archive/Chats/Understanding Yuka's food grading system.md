---
type: note
status: archived
updated: 2026-08-12
source: claude-chat
chat_url: https://claude.ai/chat/20e1f936-db9c-4dfb-815a-c9b4216d7e87
started: 2026-08-11
---

# Understanding Yuka's food grading system

Full transcript of the Claude chat "Understanding Yuka's food grading system" (16 messages, 2026-08-11 to 2026-08-12). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Archive Index]]

---

### Ben · 2026-08-11 01:23

Are you familiar with the app yucca and how it grades its foods based on their ingredients

---

### Claude · 2026-08-11 01:24

> *Claude used web_search: Yuka app food scoring methodology*

You probably mean **Yuka** (no "c"s) — the French barcode-scanning app. Yes, I'm familiar with it.

It scores food products 0–100, weighted three ways: nutritional quality is 60%, presence of additives is 30%, and organic certification is a 10% bonus. Below 20 is "Bad," 20–50 "Poor," 50–75 "Good," and 75+ "Excellent," shown with color coding — green, yellow, red.

Worth knowing how each piece works:

- **Nutrition (60%)** is based on Nutri-Score, which grades products on calories, sugar, saturated fat, sodium, fiber, protein, and fruit/vegetable/legume/nut content.
- **Additives (30%)** are each assigned a risk level — risk-free, limited, moderate, or high — drawing on EFSA and IARC recommendations plus independent studies. For some additives Yuka cites specific studies; for others it applies a precautionary approach.
- **Organic (10%)** is a flat bonus for certified products.

One caveat if you're using it to make decisions: the organic bonus has drawn criticism from nutritionists given thin evidence of a nutritional benefit over conventionally grown food, and the app doesn't account for hyperpalatability. The additive penalties are also more precautionary than the nutrition half, which rests on a validated system. So the 60% is the solid part; the other 40% is more of an editorial judgment call.

---

### Ben · 2026-08-11 01:24

Can you grade this

*[file: photo.jpeg]*

---

### Claude · 2026-08-11 01:24

> *Claude used web_search: Premier Protein Bananas & Cream shake ingredients list*

> *Claude used web_search: Yuka score Premier Protein shake rating app*

**Yuka would almost certainly rate this red — likely somewhere in the 0–25 range ("Bad" to "Poor").** Not because of the nutrition, but because of the additives.

Here's the breakdown by Yuka's own logic:

**Nutrition (60%):** Actually decent. 30g protein, 160 cal, 1g sugar, low saturated fat. But Yuka scores drinks on the stricter beverage scale, where almost nothing but water scores well — so this doesn't earn as much as you'd expect.

**Additives (30%):** This is what sinks it. The label lists sucralose, acesulfame potassium, and carrageenan — all three of which Yuka flags at its higher risk tiers. Yuka scored Barebells protein milkshakes 0/100, citing four high-risk additives including sucralose, which the app links to cardiovascular disease, diabetes, and cancer risk. Premier Protein has a nearly identical additive profile.

**Organic (10%):** No bonus.

My honest read: this is a case where Yuka's grade and reality diverge quite a bit. Yuka's system scores a KitKat or Snickers at 30/100 — higher than many protein shakes, which should tell you something. The sucralose and carrageenan evidence is real but contested and mostly from high-dose or animal studies. If your goal is 30g of protein for 160 calories in a shelf-stable bottle, this does that job well.

The reasonable middle ground: it's a fine convenience option, not something to drink four of a day.

---

### Ben · 2026-08-11 01:26

Now check this

*[file: photo.jpeg]*

---

### Claude · 2026-08-11 01:26

> *Claude used web_search: Core Power Elite 42g vanilla ingredients list fairlife*

**Also red on Yuka — probably a bit higher than the Premier, but still in the "Bad/Poor" band, roughly 10–30.**

Same story, same culprits: the label lists acesulfame potassium, carrageenan, sucralose, plus cellulose gel and cellulose gum. Sucralose and ace-K are the two Yuka penalizes hardest, and having both plus carrageenan caps the score no matter how good the nutrition looks.

Where it beats the Premier Protein:
- **Ingredient base is real food.** It's filtered lowfat milk with everything else under 1% — not water plus isolated protein powders.
- **Less additive clutter overall** — no DATEM, no phosphate stabilizer stack, no artificial flavors.
- **Nutritionally denser:** 42g protein for 230 calories, with the natural milk sugar rather than nothing.

The nutrition half won't save it, though — Nutri-Score puts milk-based drinks on the beverage scale, which is unforgiving of anything that isn't water.

If I'm picking between the two photos you've shown me: this one, fairly comfortably. Fewer additives, whole-milk base, more protein. Yuka will still flash red at you, but the gap between these two products is bigger than the gap in their scores would suggest.

---

### Ben · 2026-08-11 01:27

Why is it so bad

---

### Claude · 2026-08-11 01:27

> *Claude used web_fetch: https://help.yuka.io/l/en/article/ijzgfvi1jq-how-are-food-products-scored*

Here's the actual mechanic, and it explains almost everything: if Yuka considers even one additive high-risk, the product's maximum possible score is capped at 49/100 — in that situation the additive criterion can account for far more than its nominal 30%.

Yuka classifies sucralose as high-risk. So the moment sucralose appears on the label, the shake is mathematically locked out of green territory regardless of everything else. Then the remaining additives — ace-K, carrageenan, the celluloses — chip away at what's left of that 49. That's how you get a bottle of ultra-filtered milk with 42g of protein landing near the bottom of the scale.

Two things compound it:

- **Nutri-Score treats milk-based drinks on the beverage scale**, where the reference point is water. A 230-calorie shake gets graded against that, not against other shakes.
- **The cap is binary.** One high-risk additive at trace level scores the same as a product loaded with them. There's no dose sensitivity.

So "so bad" is really "flagged," not "measured as harmful." A product with sucralose and one with none can differ by 50+ points while being nutritionally near-identical. Which is worth knowing if you're using the score to choose between products in the same aisle — it's often telling you about a single ingredient's presence, not the overall food.

---

### Ben · 2026-08-12 01:23

Do this

*[file: photo.jpeg]*

---

### Claude · 2026-08-12 01:23

**This is the one Yuka actually rates 0/100** — Barebells milkshakes are the example I mentioned earlier. Your label confirms why.

**Additives (the cap):** sucralose is there, so the 49-point ceiling applies immediately. Then acesulfame potassium, carrageenan, dipotassium phosphate, potassium carbonate, and artificial flavors stack on top. That's five to six flagged ingredients — more than either of the previous two shakes — which drives the score from the 49 cap down toward zero.

**Nutrition (60%):** on paper this is the best of the three. 24g protein for 130 calories, 2g total sugar, 0g added, 1.5g saturated fat. The weak spot is 200mg sodium, which the beverage scale penalizes fairly hard.

**Organic:** no bonus.

So: 0–10, bottom of the scale.

Ranking your three by Yuka's math, worst to best: Barebells → Premier Protein → Core Power. Ranking them by what's actually in the bottle, I'd put Core Power first (milk base, fewest additives, 42g protein), then Barebells (leanest macros, but a longer additive list), then Premier. The scores and the reality don't line up cleanly, mostly because the cap flattens everything with sucralose into the same red zone.

---

### Ben · 2026-08-12 01:42

How about optimal nutrition double chocolate protein powder

---

### Claude · 2026-08-12 01:42

> *Claude used web_search: Optimum Nutrition Gold Standard Whey Double Rich Chocolate ingredients list*

> *Claude used web_search: Yuka acesulfame potassium E950 risk level high risk rating*

Different situation, and the answer depends on which version you scan.

**US formula:** Protein blend (whey isolate, concentrate, peptides), cocoa processed with alkali, lecithin, natural and artificial flavor, acesulfame potassium, lactase. Ace-K is the only sweetener — no sucralose. That matters a lot, because sucralose is what triggers Yuka's 49-point ceiling. Ace-K sits a tier below in Yuka's system, so it costs you points but doesn't hard-cap the score.

**UK/EU formula:** has both sucralose and acesulfame K, plus xanthan gum. That one gets capped.

So the US tub should land meaningfully higher than any of the three ready-to-drinks you've photographed — likely low-to-mid range rather than near-zero. Two caveats: Yuka sometimes doesn't score protein powders at all (they can fall under supplements), and powders are scored per 100g, which distorts things since nobody eats 100g of protein powder.

The broader point from this whole thread: what's actually separating these products in Yuka's eyes is mostly *which sweetener the manufacturer picked*. ON's US version is nutritionally similar to the shakes but will score better because it uses ace-K instead of sucralose. That's a real distinction in Yuka's model but a fairly thin one in terms of what it tells you about the food.

---

### Ben · 2026-08-12 01:42

U.S. formula

---

### Claude · 2026-08-12 01:42

**Estimate: roughly 45–65 — yellow/orange territory, possibly nudging into "Good."** Far and away the best of the four you've asked about.

Why it does better:

**Nutrition (60%):** Scored per 100g, this is a strong Nutri-Score. About 77g protein per 100g, low sugar, low saturated fat, moderate sodium. Protein maxes out the positive points. It also gets graded on the *solid food* scale, not the punishing beverage scale that dragged down all three shakes.

**Additives (30%):** One flagged additive — acesulfame potassium. Yuka penalizes it, but it doesn't trigger the 49-point cap the way sucralose does. Lecithin and lactase are green. "Natural and artificial flavor" isn't an E-number so Yuka mostly ignores it.

**Organic:** no bonus.

Two things could change the number: Yuka may classify it as a supplement and decline to score it entirely, and if it does score it, the per-100g basis is arguably flattering here (you're consuming 31g, not 100g).

Practical takeaway across everything you've scanned: the powder wins on Yuka's math *and* on substance — you control what it's mixed with, there's no carrageenan or phosphate stabilizer package, and it's cheaper per gram of protein. The ready-to-drinks are buying you convenience, and Yuka is charging them heavily for the sucralose that comes with it.

---

### Ben · 2026-08-12 15:26

Do Starbucks egg white pepper bites

---

### Claude · 2026-08-12 15:26

> *Claude used web_search: Starbucks Egg White Roasted Red Pepper Sous Vide Egg Bites ingredients list*

**Estimate: 50–70 — likely green or high yellow.** The best score of anything you've asked about.

One practical note first: Yuka scans barcodes, so the in-café version isn't scannable. The grocery/Costco packaged version is, and that's what these ingredients come from.

**Additives — no cap triggered.** The flagged ones are carrageenan, mono and diglycerides, and natamycin, mostly riding in via the cottage cheese and Monterey Jack. All sit in Yuka's limited-to-moderate tiers. Locust bean gum, guar gum, and citric acid are green dots. Nothing here is high-risk, so the 49-point ceiling never applies — which is the whole difference between this and the shakes.

**Nutrition — decent but not spotless.** 170 cal, 12g protein, 4.5g saturated fat, and about 500mg sodium for two bites. Sodium is the main thing costing points; the vegetable content and protein earn some back. And this is on the solid-food scale, which is much more forgiving than the beverage scale.

**Organic:** no bonus.

Where this lands in your running list: egg bites > ON whey (US) > Core Power > Premier > Barebells. Notably, that ordering now roughly matches how I'd rank them on substance too — which happens whenever no sucralose is involved to distort the math.
