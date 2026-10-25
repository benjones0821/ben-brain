---
type: note
status: archived
updated: 2026-08-30
source: claude-chat
chat_url: https://claude.ai/chat/342634e3-9a2c-4de5-9d8d-aac09453be53
started: 2026-08-30
---

# Selling NFC review tiles to restaurants

Full transcript of the Claude chat "Selling NFC review tiles to restaurants" (14 messages, 2026-08-30 to 2026-08-30). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Archive Index]]

---

### Ben · 2026-08-30 02:32

OK, I need a way to sell five star review tile using NFC tag basically you tap your phone and it automatically pre-fills a five star review into the Google review section I seen it done before at restaurants and I wanna be able to sell it now to other restaurants so tell me how I can go about it in an ethical way if I should just buy one and sell it to them at a higher price or if I should make it myself and to make it myself how do I even go about doing thatgive me costs and instructions be very detailed be very specific and give it to me in PDF format become an expert researcher on this. Do not make any mistakes. Check your work make sure you did a good job and optimize it.

---

### Claude · 2026-08-30 02:40

I'll research this properly before building anything — there's one part of your idea that needs correcting, and I want to get the current facts right.

> *Claude used web_search: Google review link pre-fill 5 star rating URL parameter possible*

> *Claude used web_search: FTC rule consumer reviews testimonials civil penalty amount 2026 fake reviews*

Good — I have the regulatory picture. Now let me price out the actual hardware.

> *Claude used web_search: NTAG213 NTAG215 NTAG216 bulk price 100 pcs wholesale 2026*

> *Claude used web_search: NFC Google review tap stand price per unit business "review card" reseller white label*

> *Claude used web_search: Google Business Profile prohibited content policy review gating soliciting reviews discouraging negative*

This next bit is critical — there was an April 2026 Google policy change that directly affects this product category. Let me verify it at the source.

> *Claude used web_fetch: https://support.google.com/contributionpolicy/answer/7400114?hl=en*

> *Claude used web_search: NFC Tools app write URL lock tag read-only NDEF permanently prevent overwrite*

> *Claude used web_search: custom printed PVC NFC card manufacturer price per card 500 quantity Alibaba*

I have what I need. Now building the document.

> *Claude used view: /mnt/skills/public/pdf/SKILL.md*

> *Claude used bash_tool: cd /home/claude && python3 -c "import reportlab; print('reportlab', reportlab.Version)" 2>&1; which weasyprint wkhtmltopdf pandoc 2>&1; python3 -c "import weasyprint; print('weasyprint ok')" 2>&1 | ta...*

> *Claude used bash_tool: mkdir -p /home/claude/build && cd /home/claude/build && echo ok*

> *Claude used create_file: /home/claude/build/guide.html*

> *Claude used bash_tool: cd /home/claude/build && wkhtmltopdf --enable-local-file-access --page-size Letter --margin-top 18mm --margin-bottom 20mm --margin-left 16mm --margin-right 16mm --footer-font-size 7 --footer-font-name...*

> *Claude used bash_tool: cd /home/claude/build && wkhtmltopdf --enable-local-file-access guide.html out.pdf; echo "RC=$?"*

> *Claude used bash_tool: cd /home/claude/build && rm -f out.pdf && wkhtmltopdf --enable-local-file-access --page-size Letter --footer-font-size 7 --footer-left "The Tap-to-Review Business" --footer-right "[page] / [topage]" -...*

> *Claude used bash_tool: cd /home/claude/build && pdftotext -layout tap-to-review-business-guide.pdf check.txt && echo "PAGES: $(pdfinfo tap-to-review-business-guide.pdf | grep Pages)" && echo "--- checking for rendering arti...*

> *Claude used bash_tool: cd /home/claude/build && pdftoppm -png -r 65 -f 1 -l 4 tap-to-review-business-guide.pdf pg && ls pg**

> *Claude used view: /home/claude/build/pg-01.png*

> *Claude used view: /home/claude/build/pg-02.png*

> *Claude used view: /home/claude/build/pg-04.png*

Layout is solid. Adding page numbers and refining the cover.

> *Claude used str_replace: /home/claude/build/guide.html*

> *Claude used create_file: /home/claude/build/finish.py*

> *Claude used bash_tool: cd /home/claude/build && python3 finish.py 2>&1 | grep -v XDG*

> *Claude used bash_tool: cd /home/claude/build && rm -f pg*.png && pdftoppm -png -r 60 -f 1 -l 1 /mnt/user-data/outputs/tap-to-review-business-guide.pdf c && pdftoppm -png -r 60 -f 9 -l 9 /mnt/user-data/outputs/tap-to-review-...*

> *Claude used view: /home/claude/build/c-01.png*

> *Claude used view: /home/claude/build/m-09.png*

> *Claude used view: /home/claude/build/z-16.png*

Caught a grammatical error in the closing box. Let me fix it and proofread the full text.

> *Claude used str_replace: /home/claude/build/guide.html*

> *Claude used bash_tool: cd /home/claude/build && python3 - <<'EOF' import re, html t = open('guide.html').read() body = t.split('<body>')[1] body = re.sub(r'<style.*?</style>', '', body, flags=re.S) txt = html.unescape(re.su...*

> *Claude used bash_tool: cd /home/claude/build && python3 finish.py 2>&1 | grep -v XDG && pdftotext /mnt/user-data/outputs/tap-to-review-business-guide.pdf - | grep -i "brief the staff"*

> *Claude used present_files*

16 pages, sourced throughout. One thing up front, because it changes the product:

**The pre-filled five stars has to go.** Two reasons, and they're independent:

1. **It doesn't work anymore.** The old URL tricks that pre-selected a rating were closed by Google. What you saw at that restaurant was almost certainly a tag opening the review form *directly* — fast enough to feel like magic, but with empty stars.

2. **It'd be a violation even if it worked.** Google's policy bans attempts to influence the rating, and the FTC's Consumer Review Rule (effective Oct 2024) carries civil penalties up to $53,088 per violation. The FTC sent its first warning letters in Dec 2025 and moved to actual enforcement during 2026. As the person supplying the mechanism, you'd be a more attractive target than any single restaurant.

The good news: the honest version is a better business. Compliance is your differentiator, since most Amazon competitors still use "get 5-star reviews" language that won't age well.

What's in the guide:

- **Costs**: NTAG213 chips at ~$0.10 in 100s; assembled stand ~$6.44/unit; factory-custom printed cards $0.35–0.75 landed at 500 MOQ (sourced from supplier listings)
- **Buy vs. build**: start reselling, bridge through assembly, go custom at ~100 units. Includes the trap most resellers miss — many cheap stands route through the vendor's own dashboard, so you're reselling someone's SaaS and every tag dies if they do
- **Full build steps**: three ways to get the review link, why to use password protection instead of hard-locking, the ferrite layer for metal counters, an 8-point test checklist
- **Pricing**: $79–$399 packages at 84–91% margin, plus the $19–99/mo recurring layer that's the real business
- **A compliance card** to ship in every box — allowed scripts vs. violations, verbatim-ready
- **Sales playbook**: target restaurants at 3.9–4.4 stars with under 150 reviews, plus objection handling

One detail worth flagging: Google's April 2026 update added clauses banning staff review quotas and requests to name specific employees. Also, sudden review spikes get filtered as manipulation — so phase rollouts and set that expectation at the point of sale, in writing.

---

### Ben · 2026-08-30 11:21

What would the piece look like

---

### Claude · 2026-08-30 11:22

> *Claude used visualize:read_me*

Here's the countertop version — the format that sells best:

> *Claude used visualize:show_widget*

A few deliberate choices in that layout:

**What's missing is the point.** No row of filled stars, no "5-star" wording, nothing asking how the visit went. The star graphic is the most common mistake on competitor products — it's a visual instruction to rate five, which is exactly the "attempting to influence the rating" language in Google's policy. If you want a star motif, outline-only is the ceiling.

**The tap zone sits in the upper-left, not dead center.** An iPhone's NFC antenna is at the top of its back, so when someone holds the phone to the target, the body extends upward. Put the circle low and the phone hits the counter before the antenna reaches the chip. The concentric arcs are the standard NFC wave — people recognize it without a caption.

**The QR is a fallback, not a fallback plan.** Roughly a fifth of guests will have NFC off, a case too thick, or an older Android. Same destination, no separate link to maintain.

Two things not visible here:

- **Underside label**: client name, install date, and the raw `g.page` link. That's your anti-lock-in promise made physical.
- **Ferrite layer** behind the tag if it's going on a steel counter.

The card version is this same layout squeezed to CR80 — drop the business name line, keep the tap circle and QR side by side.

Want me to spec the card format too, or mock up the compliance insert that goes in the box?

---

### Ben · 2026-08-30 11:22

What do I need to buy and where

---

### Claude · 2026-08-30 11:23

Let me check current sourcing on the two items I haven't priced yet.

> *Claude used web_search: ferrite anti-metal NFC shielding sticker sheet buy 100 pcs price*

> *Claude used web_search: acrylic sign holder 4x6 slant back bulk 24 pack price countertop*

Here's the starter kit — everything to build and sell your first 25 stands, roughly **$150–230** total.

**Buy now**

| Item | Qty | Cost | Where |
|---|---|---|---|
| NTAG213 stickers, 30–35mm | 100 pk | $9–14 | Walmart, Amazon, eBay |
| Acrylic slant-back sign holders, 4×6 | 24 pk | $45–55 | Amazon, eBay, Displays2Go |
| Cardstock for inserts | 1 pk | $10–25 | Staples, or print at Vistaprint |
| Ferrite shielding sheet, 200×300mm | 1–2 | $10–15 | Amazon (search "RFID ferrite sheet anti-metal") |
| Isopropyl wipes + craft knife | — | $10 | Anywhere |
| Used Android phone with NFC | 1 | $60–120 | Only if you don't have one |

NFC Tools (the writing app) is free on both platforms.

**The slant-back holder is the trick.** You slip a printed cardstock insert into the front and stick the tag to the inside back. No adhesive on the visible face, inserts are reprintable for pennies, and it already looks like retail signage. Much better than gluing vinyl to a blank.

**Four buying notes that will save you money:**

- **Get NTAG213, not 215.** Same job, half the price. The 215 premium exists because of the Amiibo hobby market, not because it's better for you.
- **Antenna size beats chip spec.** A 35mm tag reads noticeably further than a 25mm one. This is what makes your product feel good.
- **Order a small test batch first.** Some cheap listings ship NTAG clones that write fine but behave oddly. Buy 100, verify with a reader app, then reorder from whoever was genuine.
- **Consider pre-laminated anti-metal tags** instead of DIY ferrite layering — they cost more per tag but skip a fiddly step.

**Optional, ~$15/year:** a short domain plus a free Cloudflare redirect, if you want the tap-counting and remote-link-change layer from Section 5.

**Don't buy yet:** anything from Alibaba. Wait until you've sold ~100 units and know which format moves. A 500-piece custom run at $0.15–0.30 each is the right move at month four, not week one.

Want me to spec the insert artwork at print dimensions so you can send it straight to a printer?

---

### Ben · 2026-08-30 11:24

Why do I need all this stuff I thought I just need a tag and display paper

---

### Claude · 2026-08-30 11:24

You're right, and I over-specced that list. The true minimum is:

- **NFC tags** — 100 for ~$10
- **A free app** — NFC Tools
- **Paper** — printed on whatever you have
- **Something to stand it up**

That's about $15 and you can build a working unit tonight.

Here's what the rest of the list was actually for, so you can decide yourself:

**Acrylic holder** — not needed to make it *work*, needed to make it *sellable*. A restaurant won't pay $79 for paper taped to a counter. But buy a 6-pack, not 24. Prove someone pays before you own inventory.

**Ferrite sheet** — only matters if the tag goes on metal. Skip it. Buy it the first time a steel counter kills a tag, which may never happen.

**Android phone** — my mistake. iPhone 7 and later write tags fine. It's just slower in batches. Skip.

**Isopropyl, craft knife** — household stuff. Not a purchase.

So the honest version: **tags, a few sign holders, and paper.** Around $25.

The reason I front-loaded the rest is that the gap between "a tag that works" and "a thing a restaurant hands money for" is mostly finish quality — and that gap is where people who try this usually stall out. But you don't need to solve that on day one. Build one ugly working unit, show it to a restaurant, and let their reaction tell you what to spend on next.

---

### Ben · 2026-08-30 11:35

Give me step by step instructions. Do I need the ferrite shield?

---

### Claude · 2026-08-30 11:35

**Ferrite: no, not yet.** You need it only if the tag ends up on or directly against metal. Wood, laminate, stone, glass, painted MDF — all fine, no shield.

The test takes five seconds: hold a written tag flat against the actual counter and try to scan it. If it reads, you're done. If it doesn't, that counter is steel and you need a ferrite layer between the tag and the surface. Most restaurant host stands and bar tops are wood or stone. Buy it when a counter defeats you, not before.

**Step by step**

1. **Get the review link.** Google Maps on your phone → find the business → Reviews → "Write a review" → copy the URL from the address bar. Don't tap any stars. Use an incognito browser tab so your own account isn't baked in.

2. **Verify it.** Paste it into a fresh tab. Confirm the right business name, address and photo come up. Chains and moved businesses have duplicate listings — this is where people go wrong.

3. **Install NFC Tools.** Free, iPhone or Android.

4. **Write the tag.** Open the app → **Write** → Add a record → choose **URL/URI** → paste the link (keep the `https://`) → tap Write → hold your phone against the tag until it confirms.

   Use URL/URI, not Text. A text record won't open a browser.

5. **Read it back.** Move the phone away, then scan the tag fresh. Confirm the stored URL is exactly right.

6. **Test it cold.** Close the app entirely. Tap the tag with your phone like a normal customer would. A banner should appear and open the review form with empty stars. Try a second phone if you have one.

7. **Assemble.** Print your insert, slide it into the sign holder, stick the tag to the inside of the back panel — centered behind where your artwork says "tap here."

8. **Label the underside.** Business name, date, and the raw Google link in small print. Costs nothing, and it's what lets a client fix things without you.

**Optional, once it works:** set a write password in NFC Tools so nobody can overwrite your tag. Don't use the "Lock" function — that's permanent and turns any mistake into scrap.

The whole loop is about ten minutes the first time, under three once you have a rhythm.

---

### Ben · 2026-08-30 11:36

So for assembly give me links for everything I need

---

### Claude · 2026-08-30 11:37

> *Claude used web_search: NFC Tools wakdev official app download page*

Here are the ones I can point you to directly:

**The app (this is the one that matters — clones exist)**

- Android: [play.google.com/store/apps/details?id=com.wakdev.wdnfc](https://play.google.com/store/apps/details?id=com.wakdev.wdnfc)
- iPhone: [wakdev.com/en/apps.html](https://www.wakdev.com/en/apps.html) — links to the official App Store listing
- Developer's own page: [wakdev.com](https://www.wakdev.com/en/) — publisher is "wakdev"

Free version does everything you need. Skip the $3.99 Pro unless you're batching hundreds.

**Sign holders**

- [Marketing Holders 4×6 slant-back, Amazon](https://www.amazon.com/Marketing-Holders-Advertisements-Awareness-Lot/dp/B07K4Y87PP)
- [Displays2Go 4×6 countertop holders](https://www.displays2go.com/FLP/4-x6-countertop-sign-holders) — cheaper per unit at quantity
- Walmart carries the NIUBEE line in 6- and 20-packs

**Tags**

- [Walmart NFC tags category](https://www.walmart.com/c/kp/nfc-tags) — filter for NTAG213, 100-piece packs run $9–14

I'd rather not hand you a specific tag ASIN. That category churns constantly — listings die, sellers swap chips, prices move weekly. Search **"NTAG213 NFC stickers 100 pcs"** on Amazon or eBay and pick a listing with real review volume and a US or fast-shipping warehouse. Same for ferrite if you ever need it: **"RFID ferrite sheet anti-metal"**.

**Free and already have it**

- Google Maps (for the review link)
- Whatever printer you own, plain cardstock

One caution on the tag purchase: buy one 100-pack before committing to more. Some cheap listings ship NTAG clones that write fine but behave oddly on iPhone. Verify with the app's read function — it'll tell you the actual chip type — then reorder from whoever was honest.

---

### Ben · 2026-08-30 13:49

I’d like to get everything from Amazon make a short pdf on what to buy how to build and how much to sell for and provide links to options verifying they are real and in stock and put a product picture on the pdf too

---

### Claude · 2026-08-30 13:54

Let me try to verify current Amazon listings before building anything.

> *Claude used web_fetch: https://www.amazon.com/Marketing-Holders-Advertisements-Awareness-Lot/dp/B07K4Y87PP*

> *Claude used web_search: Amazon NTAG213 NFC tags stickers 100 pcs blank programmable*

> *Claude used web_search: Amazon 4x6 acrylic sign holder slant back 12 pack clear countertop*

Amazon blocks automated page access, so let me be straight about what I can and can't confirm — I'll build that limitation into the document rather than pretend otherwise.

> *Claude used create_file: /home/claude/build/amz.html*

> *Claude used bash_tool: cd /home/claude/build && wkhtmltopdf --enable-local-file-access --page-size Letter --quiet amz.html amz_raw.pdf && pdfinfo amz_raw.pdf | grep Pages && pdftoppm -png -r 62 amz_raw.pdf a && ls a*.png*

> *Claude used view: /home/claude/build/a-1.png*

> *Claude used view: /home/claude/build/a-2.png*

The illustration is too small and page 2 is half empty. Fixing both.

> *Claude used str_replace: /home/claude/build/amz.html*

> *Claude used str_replace: Let pricing section flow onto page 2 instead of forcing a new page*

> *Claude used str_replace: /home/claude/build/amz.html*

> *Claude used bash_tool: cd /home/claude/build && rm -f a*.png && wkhtmltopdf --enable-local-file-access --page-size Letter --quiet amz.html amz_raw.pdf 2>/dev/null && pdfinfo amz_raw.pdf | grep Pages && pdftoppm -png -r 62 a...*

> *Claude used view: /home/claude/build/a-2.png*

> *Claude used view: /home/claude/build/a-3.png*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's/@page { size: Letter; margin: 16mm 15mm 18mm 15mm; }/@page { size: Letter; margin: 14mm 15mm 14mm 15mm; }/; s/font-size: 9.4pt; line-height: 1.48;/font-size: 9.2pt; ...*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's|<svg width="670" height="306"|<svg width="620" height="284"|' amz.html && sed -i 's|<div class="fig">|<div class="fig" style="margin:2mm 0;">|' amz.html && wkhtmltop...*

> *Claude used bash_tool: cd /home/claude/build && rm -f a*.png && pdftoppm -png -r 55 -f 3 -l 3 amz_raw.pdf a && echo "--- page3 text ---" && pdftotext -f 3 -l 3 amz_raw.pdf - | head -20*

Only the footnote is spilling. Merging it back.

> *Claude used str_replace: /home/claude/build/amz.html*

> *Claude used bash_tool: cd /home/claude/build && wkhtmltopdf --enable-local-file-access --page-size Letter --quiet amz.html amz_raw.pdf 2>/dev/null && pdfinfo amz_raw.pdf | grep Pages && rm -f a*.png && pdftoppm -png -r 62 a...*

> *Claude used bash_tool: cd /home/claude/build && pdftotext -f 3 -l 3 amz_raw.pdf - | head -10*

Page 3 is now blank — I'll strip it and add page numbers.

> *Claude used create_file: /home/claude/build/finish_amz.py*

> *Claude used bash_tool: cd /home/claude/build && python3 finish_amz.py 2>&1 | grep -v XDG*

> *Claude used bash_tool: cd /home/claude/build && rm -f f*.png && pdftoppm -png -r 62 /mnt/user-data/outputs/tap-to-review-amazon-build-sheet.pdf f && ls f*.png*

> *Claude used view: /home/claude/build/f-1.png*

> *Claude used view: /home/claude/build/f-2.png*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's/@page { size: Letter; margin: 14mm 15mm 14mm 15mm; }/@page { size: Letter; margin: 14mm 15mm 20mm 15mm; }/' amz.html && python3 finish_amz.py 2>&1 | grep -v XDG*

> *Claude used bash_tool: cd /home/claude/build && rm -f f*.png && pdftoppm -png -r 62 -f 2 -l 2 /mnt/user-data/outputs/tap-to-review-amazon-build-sheet.pdf f*

> *Claude used view: /home/claude/build/f-2.png*

> *Claude used str_replace: /home/claude/build/finish_amz.py*

> *Claude used bash_tool: cd /home/claude/build && python3 finish_amz.py 2>&1 | grep -v XDG && rm -f f*.png && pdftoppm -png -r 62 /mnt/user-data/outputs/tap-to-review-amazon-build-sheet.pdf f && ls f*.png*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's/font-size: 9.2pt; line-height: 1.42;/font-size: 8.9pt; line-height: 1.38;/' amz.html && python3 finish_amz.py 2>&1 | grep -v XDG*

> *Claude used bash_tool: cd /home/claude/build && pdftotext -f 3 -l 3 /mnt/user-data/outputs/tap-to-review-amazon-build-sheet.pdf - | head*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's|<svg width="620" height="284"|<svg width="530" height="243"|' amz.html && python3 finish_amz.py 2>&1 | grep -v XDG*

> *Claude used bash_tool: cd /home/claude/build && sed -i 's|<h2><span class="n">3</span>What to sell it for</h2>|<h2 class="pb"><span class="n">3</span>What to sell it for</h2>|' amz.html && python3 finish_amz.py 2>&1 | grep ...*

> *Claude used view: /home/claude/build/f-3.png*

> *Claude used present_files*

Three pages: what to buy, how to build, what to charge.

Two things I couldn't do the way you asked, so I handled them differently:

**Stock and price aren't verified.** Amazon blocks automated access to product pages — I got a hard refusal when I tried to load them. What I have is real: seven listings that appeared in live search results today, with their ASINs. But I can't confirm any of them is in stock right now or at what price. That caveat is printed in a red box at the top of page 1, and every item has a fallback search term underneath so a dead link doesn't strand you.

**The picture is a drawing, not a product photo.** I can't pull Amazon's product photography into a document — those images are the sellers' copyrighted work. So I drew the assembly instead: holder + insert + tag = finished unit, exploded. It's arguably more useful anyway, since it shows where the tag goes, which no product photo would.

The numbers: about **$37** for your first six units, roughly **$3.10 each**, selling at **$79–$349** depending on package. You'll have 94 spare tags, so after the first batch your only real cost is sign holders.

One thing worth acting on before ordering: the tags and holders ship from different sellers, so order both today and they'll likely arrive on different days. Order the tags first if you want to practice writing them on a scrap of paper taped to a mug while you wait for the acrylic.
