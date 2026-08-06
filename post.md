# Stagify.ai — Instagram Post Log

Running log of every Instagram post. Newest rows appended at the bottom.

## Standing preferences (set by user 2026-07-28 — apply to every future run)
- **Single-slide posts only.** One image per post (1080x1350 or 1080x1080). NO carousels / multi-slide decks unless the user reverses this.
- **Go wildly different.** Push beyond clean before/after preset demos. Explore fresh angles — cartoon / comic / pop-art treatments, sports themes, memes, custom-prompt showcases, unexpected room concepts. Keep it convertible (real Stagify capability) and keep the #2563eb / navy / Inter brand anchor, but the vibe can be bold.
- Rotate the fresh angles so we don't twin: e.g. sports man-cave (custom prompt), cartoon sketch→render, meme glow-up, seasonal concepts.
- **Use the real image library (set by user 2026-08-06).** Every run must build the post from ONE real before + ONE real after of the SAME room, pulled from `assets.md` / `assets/` (real Stagify before/after pairs). Pick an unused (or least-recently-used) pair that fits the day's idea, then: (1) reference the two exact file paths in the Claude Design prompt and instruct Design to use the ATTACHED images (before = original, after = staged), and (2) deliver both files to the user via SendUserFile so they can attach them in the Claude Design chat — Claude Design CANNOT read this repo, so the files must be attached there. After a post is approved + logged, mark that pair's "Last used" date in `assets.md` and commit. Don't reuse a pair back-to-back. Top up the library when it runs low.

| Date | Format | Hook | Room/Feature | Angle | Status |
|------|--------|------|--------------|-------|--------|
| Historical | Before/after | — | Warehouse | Empty commercial/industrial space staged | Posted |
| Historical | Feature demo | — | AI Designer | Basic AI Designer functionality showcase | Posted |
| Historical | Feature demo | — | Masking Studio / masking tool | Mentioned masking tool + Masking Studio | Posted |
| Historical | Before/after | — | Bedroom | Multiple bedroom before/afters | Posted |
| Historical | Before/after | — | Living room (Modern) | Basic living room, modern theme | Posted |
| Historical | Before/after | — | Ivy League dorm room | Dorm room staging | Posted |
| Historical | Before/after | — | Nook | Nook staging | Posted |
| Historical | Before/after | — | Gaming room | Gaming room staging | Posted |
| Historical | Before/after | — | Attic | Attic staging | Posted |
| Historical | Before/after | — | Apartment (general) | General apartment before/after | Posted |
| Historical | Before/after | — | Living room / general | Basic before-and-after | Posted |
| 2026-07-29 | Before/after (custom prompt) | "I typed one sentence" | Basement → sports man-cave | Custom text-prompt reveal (per user, posted yesterday) | Posted |
