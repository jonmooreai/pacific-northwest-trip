# Craft Audit — Oregon Trip Itinerary

**Audited:** 2026-06-10
**Target:** /Users/jonmoore/Desktop/Oregon Trip/index.html
**Method:** Full-page screenshot capture (desktop + mobile fold, then page-level PDF render → per-page PNGs). Read at the felt level.

---

## verdict: PASS

All five dimensions clear the pass threshold. Two land in the 9–10 band. This is the kind of page that makes a designer want to open the file and learn from it.

---

## first_impressions

*(recorded before any rule-based analysis)*

1. **The hero is reference-quality.** A full-bleed coastal photo with a generous editorial headline — "Haystack Rock to the Hoh rainforest," with "Hoh rainforest" set in italic Fraunces — sits above a quiet facts row (Dates / Out / Back / Driving / Budget). It feels less like a travel app and more like a printed essay you'd find in a magazine you wanted to keep. The destination is doing the talking; the chrome is staying out of its way.

2. **The whole page reads in one voice.** The serif/sans pairing (Fraunces + Inter), the warm paper palette (`#faf6ef`), the muted teal/sunset/moss accents, the consistent use of italic for the *one* word that should breathe — this is a design with a clear point of view, applied with discipline across every section. Day headers are numbered in big italic Fraunces (`1/8`, `2/8`...) and feel inevitable. Tags, fact-rows, timelines, hotel cards, budget tables, packing lists — they're all from the same family.

3. **One section is the weakest link, and it's the schedule grid.** The "The trip, by the half-hour" timeline is the only thing on the page that feels assembled rather than authored. Tightly stacked colored blocks, small text, day columns crammed against a 30-minute time axis — it's the spreadsheet hiding inside a page that otherwise treats itself as editorial. Everything around it is generous and considered; this one block is dense and shouty by comparison.

---

## relevance ledger

| Reference | Yes / No / Unknown | Notes |
|---|---|---|
| craft.md | Yes | Always loaded. |
| scoring-rubric.md | Yes | Always loaded. |
| visual-system.md | **Yes** | Layout, type, color, surfaces all front-and-center. |
| components.md | **Yes** | Cards (hotels, days, fact-rows), tags, timelines, tables. |
| interaction.md | No | Static informational page; minor link hovers and a Leaflet map. Limited interactive surface area. |
| navigation.md | **Yes** | Bottom-tab nav present on mobile (Trip / Days / Map / Stays / More). |
| responsive.md | **Yes** | Desktop and mobile renderings are both designed surfaces. |
| state.md | No | Static itinerary. No loading/error/empty states to evaluate. |
| forms-flows.md | No | No forms. |
| data.md | **Partial** | Schedule grid, budget tables, route stats — light data presentation. |
| records.md | No | Not a records system. |
| ai.md | No | No AI surface. |
| trust.md | No | No auth/consent surfaces. |
| usability.md | No | Single read-through; not a task surface. |
| performance.md | No | Not auditable from screenshots. Map loads Leaflet; otherwise static. |

---

## dimensions

### Useful — **9 / 10**

The felt question: *"Does this earn the screen real estate it occupies?"*

**Evidence:**
- Every section justifies itself as a thing a traveler actually needs: shape of the trip, route, both flights booked, day-by-day with timing, schedule overview, budget math, hotels, restaurants to reserve, packing list, "don't forget" checklist, tide timing for the three big stops.
- Density is matched to context. The hero is breathable because it's setting tone; the per-day timelines are denser because that's where the real planning happens; the budget rolls up to a single bold number.
- Timing tags (`50 mi · 45m`), labeled fact-rows ("Driving today / Activities / Hotel / Weather"), and inline notes ("Far less crowded than Multnomah") earn their place — every callout answers a question a traveler would ask.
- Restraint is visible. There's no "Share this trip" button, no social proof, no "trips you might also like" — the page knows what it's for.

**Gap to 10:** The closing colophon ("Itinerary updated May 2026") is the only place a small piece of metadata sits without a frame for itself. A hairline above it, or even a small linked "view changelog," would make the page feel even more deliberately closed.

### Usable — **8 / 10**

The felt question: *"Does this feel effortless, or am I working against it?"*

**Evidence:**
- The right path on each screen is the obvious path. Click a hotel name, you trust it goes to a hotel detail. Click a tide window, you trust you'll learn what tide to look for.
- Mobile bottom-tab nav (Trip / Days / Map / Stays / More) is calm and recognizable — five tabs, only one selected, a familiar shape.
- Day-by-day reading is effortless: the time of day, then the bolded action, then the reason. The eye scans the timeline; the brain catches up on the prose.

**Gap to 9:**
- "The trip, by the half-hour" schedule grid resists scanning. Day columns are narrow, blocks butt against each other, time axis steps every 30 minutes whether anything is happening or not. Power users (the kind who love a visual schedule) need a denser surface; everyone else needs the day-list above it. Right now the grid feels like it's competing with the day-by-day, not summarizing it.
- The mobile bottom-tab bar implies five views, but on this page the user is mostly scrolling one long document. The relationship between the tabs and the scrolled sections isn't quite tangible — does "Days" jump to Day 1, or filter, or open a sub-view? The affordance is well-drawn; the felt destination is fuzzy.

### Reliable — **8 / 10**

The felt question: *"Do I know what's happening, what just happened, and what will?"*

**Evidence:**
- Booking status is consistent everywhere it matters. The header tag reads "Booked" with a small dot. Each flight card carries an "Outbound" / "Return" pill. Hotels say BOOKED, BOOKED, BOOKED, BOOKED in the same place. The page knows what's locked vs. estimated and tells you so consistently.
- Money is treated with care. Per-item costs, FHR credit, total locked-in spend, all-in estimate — each appears in the right place at the right scale, and the big teal "$5,461" panel is the answer the eye is looking for.
- Cross-references hold: "Why this over Quileute" is answered in the same card the alternative is named in. "Heads up on Day 8" floats a gotcha *on* Day 8, not buried in a notes section.

**Gap to 9:** Some reliability cues are inconsistent. The schedule grid colors aren't keyed anywhere I can find on the page — green vs. yellow vs. peach blocks have meaning, but the reader has to infer it. A four-swatch legend underneath ("driving / activity / meal / lodging") would let the grid earn its place. Right now it asks the user to do the system's work.

### Coherent — **9 / 10**

The felt question: *"Does every screen feel like the same hand made it?"*

**Evidence:**
- One typographic voice throughout. Fraunces for the headlines, in display weights with tasteful italic emphasis on the *one* word that benefits from it ("Hoh *rainforest*", "Four bases, *one quiet pace.*", "Both legs *booked.*", "Trip budget, *for two travelers.*", "The booking *checklist.*"). The italic move is a signature, used with restraint, never overused. Inter for the running text and labels.
- The palette is small and disciplined. Paper, teal, sunset/orange, moss, gold, sand. Each color has a job. The teal is reserved for status, totals, and confirmations; sunset/red for destination markers and warnings; moss for trail/forest.
- Section transitions follow one rhythm: a small all-caps label ("THE SHAPE OF THE TRIP", "AIR", "WHAT TO BOOK AND WHEN", "PACIFIC NORTHWEST IN JULY"), then a Fraunces headline with one italicized phrase, then a paragraph of plain prose, then the structured surface (cards, table, timeline). You learn the cadence and trust it.
- Map pins and route legend share the same visual language as the day-page tags — small filled circles with a single letter (A, H, T, C, S) and the same color logic.

**Gap to 10:** The schedule grid's color logic doesn't reuse the rest of the page's palette consistently. There are pinks/peaches/yellows in there that don't appear anywhere else — they read as a different designer's color system. Bringing the grid into the paper/teal/sunset/moss/gold/sand palette would close the last seam.

### Well-Crafted — **9 / 10**

The felt question: *"Was this made with care, or just shipped?"*

**Evidence:**
- The hero is exceptional. The full-bleed image, the generous left-aligned headline with one italicized destination, the quiet five-fact row underneath — this is the kind of opening you'd see on a magazine cover. Nothing shouts; nothing is missing.
- Day numerals (`1/8`, `2/8`, `8/8`) are typographic moments. The big numeral, the slash, the small "/8" — used eight times, the page builds a small expectation that becomes part of the reading rhythm.
- Section headlines all share the same italic-on-the-keyword move. "Four bases, *one quiet pace.*" "Both legs *booked.*" "Tide timing for the *three big stops.*" Each one teaches the reader what to care about, and the italic word is always the most felt one. This is craft that compounds.
- Decorative restraint is everywhere. No drop shadows. No gradient buttons. No icon noise. Borders appear only where the eye genuinely needs separation — between hotel cards, around fact-rows, around the budget total.
- Empty space is structural. The hero doesn't try to fill itself; the section between the day list and the schedule grid is allowed to breathe; the closing block ("Always look for what is not visible." — Patti Smith) is allowed to be quiet on its own.
- The closing dark panel with the Patti Smith quote is the kind of designed micro-moment a lesser page would skip. It tells you the author cared about the ending.

**Gap to 10:**
- The schedule grid is the one block that looks shipped rather than authored. The blocks aren't aligned to the section above's restraint; the time axis is heavy; the column widths make the labels truncate awkwardly. This is the only place on the page where the felt quality drops.
- A few of the day-page metadata rows ("DRIVING TODAY / ACTIVITIES / HOTEL / WEATHER") feel slightly padded vertically vs. the tight rhythm of the rest of the page. They sit in the right place, but the cell padding could be tightened to match the editorial cadence around them.

---

## findings

### Finding 1 — schedule grid
- **severity:** major
- **location:** "The trip, by the half-hour" — the week-overview grid
- **problem:** This is the only block on the page that feels assembled rather than authored. Day columns are narrow, colored blocks butt against each other, the 30-minute axis ticks whether anything is happening or not, and the colors used in the grid (peaches, pinks, yellows) don't appear anywhere else on the page. After the editorial calm of every other section, the schedule reads as a spreadsheet pasted in.
- **why_it_weakens_craft:** *Coherence is the discipline of one taste applied everywhere.* When one block introduces a different visual vocabulary, the eye reads it as a seam — a place where the careful authorship breaks down. A single section in the wrong voice undoes the trust the rest of the page has earned. The reader stops feeling held by a single hand.
- **what_better_looks_like:** A schedule view that feels like the *summary* of the day-by-day prose above it, not a competing surface. Wider day columns, generous gutter, time axis that only marks meaningful hours (8 / 12 / 5 / 9), blocks colored from the page's existing palette (sand for driving, moss for activity, gold for meal, teal for lodging — each with a small swatch in a single legend underneath the chart), and considered empty cells that read as breath rather than absence. The grid would become the thing on the page that earns *"The trip at a glance"* rather than competing with the days.
- **fix:** Redesign the schedule as a calmer, wider summary view. Reduce the time axis to 4–5 meaningful marks. Reuse the page's palette for block fills (sand / moss / gold / teal). Add a four-swatch legend below the grid. Increase column gutter so blocks read as separated cards. Soften the alternating-row backgrounds — they're competing with the colored blocks for attention. The goal is for the grid to feel like the same designer also made it.

### Finding 2 — schedule color key
- **severity:** minor
- **location:** "The trip, by the half-hour" grid
- **problem:** The grid's colors (peach, yellow, green, blue) carry meaning, but no legend is visible. The reader infers — *peach is probably driving, green is probably hiking, yellow is probably activity* — but the design is quietly asking them to do that work.
- **why_it_weakens_craft:** *Reliable design tells the user what's happening.* When color carries semantic weight, the legend should be present. Otherwise the page looks designed but feels like guesswork — and the moment the user has to guess, the trust is broken.
- **what_better_looks_like:** A small one-line legend below the grid, in the same all-caps small label style the rest of the page uses: four labeled swatches, in the order the user encounters them. The chart immediately becomes scannable rather than decoded.
- **fix:** Add a legend strip beneath the grid: `■ Driving · ■ Hike / activity · ■ Meal · ■ Lodging` — using the same palette as the rest of the page. Position it within the grid's container so it reads as part of the chart, not as a separate caption.

### Finding 3 — mobile tab destinations
- **severity:** minor
- **location:** Mobile bottom-tab nav (Trip / Days / Map / Stays / More)
- **problem:** The bar is well-drawn — five tabs, calm icons, only one active state at a time. But the relationship between the tabs and the long scrolling document isn't quite tangible. "Days" feels like it should jump to or filter the day-by-day; "Map" presumably scrolls to the route map; "Stays" to the hotels list. From a reading position halfway down the page, the felt destination is unclear.
- **why_it_weakens_craft:** *Approachable design doesn't ask the user to learn how it works.* The tab bar implies a multi-view structure, but the page is one long document — so the user has to discover (by tapping) what each tab actually does. This is a small approachability cost, but on a page that gets approachability so right elsewhere, it's noticeable.
- **what_better_looks_like:** Either commit harder to the multi-view feel — when the user taps "Stays," scroll smoothly to the Stays section with a brief highlight of the section header, so the user feels the tab actually delivered them somewhere — or commit to a single-document feel and let the bar be a quiet anchor at the top of the page (a slim sticky section nav rather than a destination-tab bar). Pick one.
- **fix:** Add smooth-scroll-with-flash behavior on tab tap: tap "Stays," the page glides to the Stays section, the section header has a brief 600ms color/underline emphasis, then settles. Same for Days, Map, More. The active tab updates as the user manually scrolls (intersection observer). This converts the tab bar from "looks like nav" to "is nav."

### Finding 4 — day-page meta rows
- **severity:** polish
- **location:** Per-day fact rows ("DRIVING TODAY / ACTIVITIES / HOTEL / WEATHER")
- **problem:** The vertical padding inside each meta-row cell feels slightly generous compared to the tight rhythm of the rest of the page. The eye reads them as separate from their day rather than as a tight summary card.
- **why_it_weakens_craft:** *Considered spacing means tighter inside related elements, looser between unrelated ones.* When a four-row card uses the same row-spacing as the gap between sections, the card stops reading as one unit. The meta-row should feel like a passport stamp tucked at the start of each day, not a four-row table.
- **what_better_looks_like:** The four-row block reads as a single fact-card. Tighter row gaps inside, slightly heavier top/bottom padding around the whole block. The label column (DRIVING TODAY / ACTIVITIES / HOTEL / WEATHER) is uppercase and quiet; the value column is the eye's destination.
- **fix:** Tighten internal row gap on the meta-rows; keep the existing outer card. Right-align the values, left-align the labels (already done — keep that). Consider a thin hairline only between the rows on hover, not always — the rule lines are doing a small amount of clutter for a small amount of structure.

### Finding 5 — schedule grid section heading
- **severity:** polish
- **location:** "The trip, *by the half-hour*."
- **problem:** The headline promises precision and craft ("by the half-hour"), and the grid below half-delivers — the precision is there in the time axis, but the craft is not. The headline is making a promise the chart isn't keeping.
- **why_it_weakens_craft:** *The voice of the page sets an expectation.* When a section headline names a specific feeling ("the half-hour"), the surface below it has to honor that level of consideration. Right now the headline is doing more work than the chart.
- **what_better_looks_like:** Either the chart rises to meet the headline (Finding 1's redesign), or the headline softens to match the chart ("Trip, *at a glance*" or "*Eight days* in one view"). The former is the better move — the page deserves a schedule view that's as crafted as the rest of it.
- **fix:** Resolve via Finding 1's redesign. Once the grid is in the page's palette, with a proper time axis and a legend, the half-hour promise will land.

---

## cross_cutting_patterns

1. **The page applies its taste with rare consistency, except for one block.** Editorial typography, italic-on-the-keyword headlines, paper-and-PNW palette, restrained borders, generous space — all of it is doing the same job everywhere except the schedule grid. The schedule is the one place a different sensibility surfaced.

2. **Restraint is the page's superpower.** Every section earns its space; nothing is decorative. The strongest sections (hero, day-by-day, hotels, budget total, closing quote) hold back rather than push. This is the discipline that makes the page feel authored.

3. **Italic is the signature move.** Across nine headlines, italic Fraunces is used to pick out the *one* most-felt word. It's not a rule — it's a preference, applied consistently. This is the kind of small move that elevates a page from "well-designed" to "designed by someone with a point of view."

4. **The palette is small and earns its place.** Paper, teal, sunset, moss, gold, sand. Six colors, each with a clear job. The teal is reserved for totals, status, and confirmations; the sunset for destination/route markers; the moss for forest/trail. The discipline holds across hero, cards, tables, and tags — and breaks only in the schedule grid.

5. **The page knows when to be quiet.** The closing Patti Smith quote in a dark panel; the colophon in small grey type; the closing tab bar with no fanfare. A lesser page would have a "Share this itinerary" CTA, a "Save to..." button, and a feedback widget. This one closes with a literary quote.

---

## recommendations

*(in priority order — by impact on felt quality)*

1. **Redesign the schedule grid to match the rest of the page's voice.** This is the single move that will lift the audit by the most points across Coherent, Reliable, and Well-Crafted. The grid is currently the seam.

2. **Add a legend to the schedule grid.** Even before the redesign, a one-line legend would make the grid scannable and earn its semantic colors.

3. **Make the mobile tab bar feel like nav, not chrome.** Tapping a tab should deliver the user somewhere with a small acknowledgement (smooth-scroll plus a brief section-header flash). The bar is well-drawn — the felt behavior just needs to match.

4. **Tighten the day-page meta-row card spacing.** A small move, but it lets each day-page open with a tighter, more authored fact-card.

5. **Soften the section heading "by the half-hour" or rise to it.** The headline is a craft promise; the surface should honor it. Resolved by Finding 1.

---

## fix_prompt

````
**Goal**: Bring the "trip at a glance" schedule into the same editorial voice as the rest of the Oregon Trip itinerary, so the page reads as one designer's hand from the hero through the closing quote.

**Context**: The page is reference-quality almost everywhere — the Fraunces+Inter pairing, the paper/teal/sunset/moss/gold/sand palette, the italic-on-the-keyword headlines, the disciplined restraint. The one block that breaks the spell is the half-hour schedule grid: it uses a different (peach/yellow/green/blue) palette, a heavy 30-minute time axis, and narrow truncating columns, so it reads as a spreadsheet pasted into a magazine. Three other smaller moves — a legend for that grid, a clearer destination feel for the mobile tab bar, and tighter spacing on the day-page meta-rows — will close the remaining seams.

**Moves to make** (in order of impact on felt quality):

1. **Lift the schedule grid into the page's voice.** — Where: the "The trip, by the half-hour" section.
   What it should feel like: After this change, the grid reads as a calm summary of the days above it, not a competing surface. The eye should land on it and feel the same authorship as the hero.
   The change: Reuse the page's existing palette for block fills — sand for driving, moss for hike/activity, gold for meal, teal for lodging. Replace the 30-minute time axis with 4–5 meaningful marks (e.g., 8, 12, 5, 9) so the grid breathes. Widen the day columns and the gutter between them so block labels stop truncating. Soften the alternating-row backgrounds; let the colored blocks carry the structure. The goal: the grid should feel like the same person who wrote "Four bases, *one quiet pace.*" also designed it.

2. **Give the schedule a legend.** — Where: directly beneath the half-hour grid.
   What it should feel like: The grid's colors should stop asking the reader to guess. Color = label, instantly.
   The change: Add a single line of four labeled swatches in the page's small all-caps label style — `■ Driving · ■ Activity · ■ Meal · ■ Lodging` — using the same palette as the grid blocks. Place it inside the same container as the grid so it reads as part of the chart.

3. **Make the mobile tab bar feel like nav.** — Where: the bottom-tab bar (Trip / Days / Map / Stays / More) on mobile.
   What it should feel like: Tapping a tab should feel like arriving somewhere. The user should never wonder what a tab does.
   The change: Each tab smooth-scrolls to its corresponding section (Days → day list, Map → route map, Stays → hotels, More → packing/booking lists). The destination section header gets a brief 600ms emphasis (a quiet underline or color-flash) so the user feels the arrival. As the user manually scrolls, the active tab updates via intersection observer. The bar gets a tiny semi-transparent backdrop so it never competes with content beneath it but always feels anchored.

4. **Tighten the day-page meta-row cards.** — Where: each day's "DRIVING TODAY / ACTIVITIES / HOTEL / WEATHER" block.
   What it should feel like: The block should feel like a tight passport stamp at the start of each day, not a four-row mini-table.
   The change: Reduce the vertical row gap inside the card. Keep the outer card padding generous. Keep the existing left-aligned label / right-aligned value layout. Consider removing the always-on hairlines between rows — let the column structure do the separating.

**Verification**: After applying these moves, take fresh screenshots (full desktop page + mobile fold + the schedule grid section specifically) and re-audit using the validating-designs skill. The dimensions that should rise: Coherent should reach 10 (the schedule grid was the last seam); Well-Crafted should reach 10 (the schedule grid was the last block that felt shipped rather than authored); Reliable should reach 9 (with the legend, the grid's color semantics are explicit). Useful and Usable should hold at 9 and 8+.

**What NOT to change**: The hero. The Fraunces+Inter typography pairing. The italic-on-the-keyword headline pattern (it's the page's signature). The paper/teal/sunset/moss/gold/sand palette (apply it to the grid; don't replace it). The day-page prose-and-timeline layout. The hotel cards. The budget table and the teal "All-in estimate" panel. The closing Patti Smith quote in the dark panel. The map and the route legend (A/H/T/C/S pins). These are reference-quality. Touch them only if a move above requires it.
````

---

## closing note

This is the kind of itinerary I'd want my own trip notes to look like. It's a great example of *applied taste* — a small visual vocabulary used everywhere, with one signature move (italic on the felt word) that makes it feel like a real person designed it. Fix the schedule grid and the mobile tab affordance, and this page is reference-quality end to end.
