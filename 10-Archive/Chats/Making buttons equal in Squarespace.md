---
type: note
status: archived
updated: 2026-08-07
source: claude-chat
chat_url: https://claude.ai/chat/7c75f5d8-9e96-4d99-8edf-0a88038624d4
started: 2026-08-07
---

# Making buttons equal in Squarespace

Full transcript of the Claude chat "Making buttons equal in Squarespace" (6 messages, 2026-08-07 to 2026-08-07). Tool calls are shown as one line; tool output and Claude's internal reasoning are left out.

Related: [[Archive Index]]

---

### Ben · 2026-08-07 18:54

how would i go about making these buttons equal in squarespace

*[file: Screenshot 2026-08-07 at 2.53.59 PM.png]*

---

### Claude · 2026-08-07 18:54

Squarespace buttons auto-size to their text, so "Gallop" will always be narrower than "Pageant" unless you force a width. There's no native setting for it — you need Custom CSS (available on Business plan and above).

**The CSS**

Go to Website → Website Tools → Custom CSS and add:

```css
.sqs-block-button-element {
  min-width: 200px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

@media screen and (max-width: 767px) {
  .sqs-block-button-element {
    min-width: 140px;
  }
}
```

`min-width` rather than `width` means longer labels won't get clipped if you add an event later. Adjust 200px until "Pageant" (your longest) fits comfortably — that's your floor.

**Scoping it to just this section**

The snippet above hits every button block on the site. If you only want it on the Homecoming page, wrap it in a section ID:

```css
[data-section-id="YOUR_ID_HERE"] .sqs-block-button-element {
  min-width: 200px;
}
```

Right-click a button → Inspect, then scroll up in the markup to find the `<section>` tag and copy its `data-section-id`. The Squarespace ID Finder Chrome extension does this without the dev tools if you'd rather.

**If you're not on Business plan**

The workaround is padding the shorter labels with non-breaking spaces (Option+Space on Mac) inside the button text — `&nbsp;&nbsp;Gallop&nbsp;&nbsp;`. It's fiddly and you'll be eyeballing it, but it doesn't require CSS access.

One thing worth checking first: if those five buttons are in a Fluid Engine section, make sure each block occupies the same number of grid columns before you touch CSS. Uneven blocks plus a min-width can push things around at tablet breakpoints.

---

### Ben · 2026-08-07 18:58

its for all the buttons to make them even with each other

---

### Claude · 2026-08-07 18:58

Then the first snippet is what you want — no section ID needed. Drop this into Website → Website Tools → Custom CSS:

```css
.sqs-block-button-element {
  min-width: 200px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

@media screen and (max-width: 767px) {
  .sqs-block-button-element {
    min-width: 140px;
  }
}
```

Set the number by your longest label. Right now that's "Pageant," so 200px probably has room to spare — try 160px first and bump up until nothing wraps to a second line. Buttons with longer text than the min-width will still expand past it, which is why `min-width` beats a fixed `width`.

Two things that may bite you:

**Small buttons look oversized.** The rule catches every button block sitewide, including any "Learn More" or footer buttons. If you only want the large size class, target it specifically:

```css
.sqs-block-button-element--large { min-width: 200px; }
```

Squarespace tags buttons as `--small`, `--medium`, or `--large`, so you can set different minimums per size.

**Buttons inside Summary or Gallery blocks** sometimes use different class names and won't pick this up. If a stray button ignores the rule, inspect it and check what class it's actually carrying.

If your five event buttons are in a Fluid Engine section, also make sure each block spans the same number of grid columns — otherwise at tablet width the min-width can fight the grid and push blocks onto separate rows.

---

### Ben · 2026-08-07 18:58

its just for this page though

---

### Claude · 2026-08-07 18:59

Easiest way is to skip Custom CSS entirely and use per-page code injection — it's scoped to that page by definition, no IDs to hunt down.

Go to Pages → hover the Homecoming page → gear icon → Advanced → Page Header Code Injection, and paste:

```html
<style>
  .sqs-block-button-element {
    min-width: 200px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }

  @media screen and (max-width: 767px) {
    .sqs-block-button-element {
      min-width: 140px;
    }
  }
</style>
```

Same tier requirement as Custom CSS (Business plan or above), so if one is available to you, the other is too.

**Alternative: collection ID in Custom CSS**

If you'd rather keep all your styling in one place, Squarespace puts a collection ID on the `<body>` tag of every page. Right-click anywhere on the Homecoming page → Inspect, look at the `<body>` tag, and copy the `id` — it'll look like `collection-6512a3f9b...`. Then in Custom CSS:

```css
#collection-YOUR_ID_HERE .sqs-block-button-element {
  min-width: 200px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}
```

Note that the ID stays the same even if you rename the page or change the URL slug, so this won't silently break on you later.

Start around 160px and raise it until "Pageant" sits comfortably without wrapping — that's your longest label, so it sets the floor.
