# Stagify.ai — Image Asset Library

Before/after staging pairs available for Instagram posts. Each pair lives in `assets/<id>/` with a `before.jpg` (empty/original room) and an `after.webp` (Stagify-staged).

**How the routine uses this:** each run I pick an UNUSED (or least-recently-used) pair that matches the day's idea, reference its exact file paths in the Claude Design prompt, and note it must be attached in the Claude Design session. After the post is approved + logged, I mark the pair's "Last used" date here and commit.

**Rule:** don't reuse a pair back-to-back; prefer `Last used = —` (never used) first, then oldest date.

| ID | Room | Style preset | Before | After | Last used |
|----|------|--------------|--------|-------|-----------|
| 083 | Living room | Midcentury | assets/083-living-room-midcentury/before.jpg | assets/083-living-room-midcentury/after.webp | — |
| 084 | Kitchen | Luxury | assets/084-kitchen-luxury/before.jpg | assets/084-kitchen-luxury/after.webp | — |
| 085 | Dining room | Midcentury | assets/085-dining-room-midcentury/before.jpg | assets/085-dining-room-midcentury/after.webp | — |
| 086 | Kitchen | Coastal | assets/086-kitchen-coastal/before.jpg | assets/086-kitchen-coastal/after.webp | — |
| 087 | Living room | Luxury | assets/087-living-room-luxury/before.jpg | assets/087-living-room-luxury/after.webp | — |
| 088 | Dining room | Scandinavian | assets/088-dining-room-scandinavian/before.jpg | assets/088-dining-room-scandinavian/after.webp | — |
| 089 | Living room | Standard | assets/089-living-room-standard/before.jpg | assets/089-living-room-standard/after.webp | — |
| 090 | Living room | Farmhouse | assets/090-living-room-farmhouse/before.jpg | assets/090-living-room-farmhouse/after.webp | — |
| 091 | Bedroom | Modern | assets/091-bedroom-modern/before.jpg | assets/091-bedroom-modern/after.webp | — |
| 092 | Bedroom | Standard | assets/092-bedroom-standard/before.jpg | assets/092-bedroom-standard/after.webp | — |
| 093 | Bedroom | Midcentury | assets/093-bedroom-midcentury/before.jpg | assets/093-bedroom-midcentury/after.webp | — |
| 094 | Kitchen | Luxury | assets/094-kitchen-luxury/before.jpg | assets/094-kitchen-luxury/after.webp | — |
| 095 | Living room | Scandinavian | assets/095-living-room-scandinavian/before.jpg | assets/095-living-room-scandinavian/after.webp | — |
| 096 | Living room | Modern | assets/096-living-room-modern/before.jpg | assets/096-living-room-modern/after.webp | — |
| 097 | Bedroom | Farmhouse | assets/097-bedroom-farmhouse/before.jpg | assets/097-bedroom-farmhouse/after.webp | — |
| 098 | Living room | Coastal | assets/098-living-room-coastal/before.jpg | assets/098-living-room-coastal/after.webp | — |
| 099 | Bedroom | Modern | assets/099-bedroom-modern/before.jpg | assets/099-bedroom-modern/after.webp | — |
| 100 | Bedroom | Farmhouse | assets/100-bedroom-farmhouse/before.jpg | assets/100-bedroom-farmhouse/after.webp | — |
