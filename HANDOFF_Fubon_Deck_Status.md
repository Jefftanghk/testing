# Handoff: Fubon Bank Change Management Deck — Status

**Date:** 2026-08-27
**Repo:** `Jefftanghk/testing` (GitHub)
**File:** `[DDHK] Fubon Bank Change Management 1.pptx`
**Status:** ✅ Complete, QA'd, committed and pushed to `main` (commit `085a35f`)

---

## 1. Original task

Update the Deloitte × Fubon Bank "CRMS Phase 2" change management deck:

1. **Slides 1–6**: content confirmed, do not touch. Their design (Deloitte Digital 2021 theme, colors, fonts, divider style) is the design system for everything else.
2. **Slides 16–22** (original numbering, pre-edit): content confirmed, do not touch.
3. **Edit from "Where to Play" onward** (original slides 7–15): use content *ideas* (not layout/colors) from two Salesforce reference decks:
   - `Salesforce Change  Adoption in a Box  Playbook 1.pptx` (25 slides)
   - `Salesforce Change  Adoption in a Box  Playbook 2.pptx` (26 slides)
4. **Original page 10** ("Change Management Success Formula" table): keep only the **yellow-highlighted** deliverables — trim the rest, since the engagement has fewer deliverables than the template implies.
5. **"Next Steps"** section: add a slide asking Fubon to nominate a **Change Champion for each of the three business groups — RBG, IBG, CMG**.
6. Design inspiration for new slides: a Deloitte internal deck `CM Scrapbook_vFINAL01142020 1.pptx` (304 slides) — for **layout motifs only**, not colors. Must still follow the color tone of slides 1–6.

All four source/reference files are in the repo root alongside the target deck.

---

## 2. What was actually done

### Structural changes (25 slides → 28 slides)
- Deleted the original slide 9 ("High-level roadmap") — it was pasted from Playbook 1 in **Salesforce's red/maroon brand colors**, had broken/overlapping text, and clashed with Fubon's navy/teal palette.
- Added 4 new slides (duplicated from good template slides, then rewritten):
  - New **"Where to Play" roadmap** (replaces old slide 9) — duplicated from slide 13's structure, then fully rebuilt as a 5-phase circle diagram.
  - New **"What to Do"** content slide — duplicated from slide 6 (the RBG/IBG/CMG icon-card layout), rewritten.
  - New **"How to Measure"** content slide — duplicated from slide 13 (3-column table layout), rewritten as a KPI scorecard.
  - New **"Next Steps" / Change Champion ask** slide — duplicated from slide 6 again, rewritten.

### Final slide map (28 slides)
| # | Content | Status |
|---|---|---|
| 1–8 | Title, TOC, Playbook framework, Aspiration | **Untouched** (confirmed content) |
| 9 | **NEW**: "High-Level Adoption Roadmap" — 5 circles (Strategy & Assess → Design → Construct → Implement → Operate & Sustain) in the deck's own navy-to-sky-blue ramp, with headline deliverables under each phase | Rebuilt from scratch |
| 10 | "Change Management Success Formula" table | Trimmed to yellow-highlighted deliverables only (~10 items, was ~35); recolored from Salesforce red to Deloitte navy/teal/gold |
| 11 | "How to Win?" divider | Untouched |
| 12 | "'How to Win' Across a Variety of Opportunities" | Fixed a title/subtitle text overlap bug and a mislabeled eyebrow ("Where to play" → "How to win"); filled unused vertical space with a summary band |
| 13 | "Change Management Approach" (pre/post/ongoing table) | Untouched (already solid) |
| 14 | "What to Do?" divider | Untouched |
| 15 | **NEW**: "What Specific Actions Should Fubon Take?" — action cards per RBG/IBG/CMG tied to real Discovery Workshop dates (17/18/22 Jun 2026, from slide 19), plus a "Universal Commitments" list reused from slide 13's own language | New |
| 16 | "How to Measure" divider | Untouched |
| 17 | **NEW**: "How Do We Measure Success?" — KPI scorecard across Readiness Baseline / Go-Live Effectiveness / Sustained Adoption | New |
| 18–24 | Timeline, schedules, workshops, team org chart, critical success factors | **Untouched** (this is the original "slides 16–22" — shifted position by +2 due to the net slide count change) |
| 25 | "Next Steps" divider | Untouched |
| 26 | **NEW**: "Nominate Your Change Champions" — asks for one champion per RBG/IBG/CMG, reuses real contacts from slide 19 (Candy Yeung/RBG, Amy Li/IBG, Kay Law/CMG), explains the Identify→Activate→Manage lifecycle | New |
| 27 | "Q&A" | Untouched |
| 28 | "Thank you" / About Deloitte | Untouched |

⚠️ **Numbering note for whoever picks this up**: original "slides 16–22" (untouched by request) are now at **positions 18–24** because 4 slides were added and 1 removed before them. Don't assume "page 16" still means the same thing.

### Design system reused (so new work stays consistent)
- Theme: `DeloitteDigital2021`. Fonts: **Open Sans Light** (titles), **Open Sans** (body).
- Palette (hex): `dk2` D0D0CE · `lt2` 53565A (Deloitte gray) · `accent1` E3E48D (pale olive) · `accent2` A0DCFF (sky blue) · `accent3` 9DD4CF (soft teal) · `accent4` 62B5E5 (medium blue) · `accent5` 6FC2B4 (teal-green) · `accent6` 00ABAB (Deloitte signature teal) · Deloitte green `046A38` (title-slide accent only).
- **Ramp motif**: slide 4's framework circles use `schemeClr accent4` with `lumMod`/`lumOff` variants to create a 5-step dark-navy→pale-sky-blue gradient. This same technique was reused for the new roadmap slide's circles and the recolored slide 10 table — worth reusing again for consistency if more slides are added.
- Section dividers: black background + swirl/metallic 3D render image (already in the template's media), white title text, white Deloitte Digital logo top-right.
- Content slides: white background, small-caps gray eyebrow (`NN  SECTION NAME`) top-left, Deloitte + Fubon logos top-right, footer `N | © 2026. For information, contact Deloitte Advisory (Hong Kong) Limited.`

### Source material citations (exact slide numbers)
Traced precisely by re-reading the raw `markitdown` text dumps of both playbooks (not just agent summaries):

| New Fubon content | Source | What was there |
|---|---|---|
| "Identify → Activate → Manage" champion lifecycle (slide 26) | Playbook 1, **slide 20** ("Change Agent Network") | Direct paraphrase of the identify/activate/manage lifecycle language |
| Champion "ideal profile" framing | Playbook 1, **slide 21** ("Roles & Responsibilities") | "Roles range from advisor... to point-of-contact in a specific market" |
| "Go-Live Assessment score (Go/No-Go)" metric | Playbook 1, **slide 23** | Go/no-go decision framing |
| "Stakeholder sentiment (pulse survey)" metric | Playbook 2, **slide 3** ("Pulse Survey") | Sentiment-by-role/department framing |
| Adoption Metrics framing (logins, training attendance) | Playbook 2, **slide 14** ("Adoption Metrics") | Direct source of the metric categories |
| "Post Go-Live Assessment score" | Playbook 2, **slide 16** | Behavioral change / KPI outcomes framing |

**Important**: the "Where to Play" 5-phase table (Strategy & Assess/Design/Construct/Implement/Operate) was **already** in the Fubon deck before this session started (it was pre-copied from Playbook 1 slide 12 by whoever built the original deck) — this session only recolored/trimmed it, did not import it fresh. The "Universal Commitments" list on the What to Do slide, the workshop dates, and the named contacts (Candy Yeung, Amy Li, Kay Law) were all reused from **Fubon's own existing slides 13 and 19**, not from the Playbooks.

---

## 3. Environment notes (if continuing in a fresh session)

- This sandbox's LibreOffice install was missing `libreoffice-impress`, `libreoffice-draw`, and `poppler-utils` — **no pptx could render to PDF/images at all** until these were installed via `apt-get install libreoffice-impress poppler-utils`. If a new agent needs to visually QA the deck and hits `Error: source file could not be loaded` from `soffice`, this is almost certainly the cause.
- `markitdown[pptx]` was also not preinstalled; `pip install "markitdown[pptx]"` was needed for text-dump QA.
- The deck's slide masters carry a **think-cell** OLE control object (`progId="TCLayout.ActiveDocument.1"`) — this looked like a corruption/render-blocker at first but is normal for a real Deloitte deck; it was a red herring, not something to "fix."
- Full pptx skill workflow (unzip → edit slide XML → `add_slide.py` for duplication → `clean.py` for orphan cleanup → `validate.py` → LibreOffice render → `pdftoppm`) was used throughout; see `.claude/skills/synced/pptx/SKILL.md` if this environment has it.

---

## 4. Git status

- Branch `claude/github-test-folder-files-g1qy8d`: commit `10c744d` — the deck redesign.
- Branch `main`: fast-forwarded to include a scrapbook commit, then merged the redesign branch in — commit `085a35f` ("Merge Fubon deck redesign into main"). **Pushed successfully to `origin/main`.**
- No open PR — changes went straight to `main` at the user's explicit request.

---

## 5. Open items / things a follow-up agent or the user should sanity-check

- **No formal client/user sign-off yet on the new narrative content** (the What to Do / How to Measure / Champion-ask slides were authored based on the brief and QA'd visually by this session, but the specific wording hasn't been reviewed by the user turn-by-turn).
- The champion-nomination deadline "10 Jun 2026" (ahead of the 17–22 Jun workshops) was **invented** as a reasonable placeholder — not confirmed by Fubon or the user. Flag for confirmation.
- Slide 10's table rows were tightened once for spacing but could still be polished further if the user wants a denser/lighter look.
- If more slides are added later, reuse the `accent4` lumMod/lumOff ramp and the existing divider/content layouts (189/190/191 for layout, master 5) rather than introducing new ones — the original deck already has 224 slide layouts and 6 masters from being assembled out of multiple source decks; adding more bloat should be avoided.
