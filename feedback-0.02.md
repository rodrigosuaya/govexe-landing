# GOV.EXE Landing — Feedback v0.02

## Items addressed

| # | Section | Issue | Fix applied |
|---|---------|-------|-------------|
| 1 | Hero + Ask | Remove USD conversion from contingency line (≈ $145,963) | Removed from both hero stat and ask grid; proposal USD equivalent (≈ $583,850) kept |
| 2 | All twocol sections | Description text was aligning to the eyebrow label top, not the h2 title | Restructured all 5 sections (What it is, How it works, Opportunity, For Cardano, The pilot): eyebrow now sits above the two-column grid so h2 and description start at the same height |
| 3 | For Cardano | h2 had "that" in bold (`<strong>`) and was missing a closing period | Removed bold, added period: "Three concrete mechanisms that create value beyond the pilot." |
| 4 | For Cardano — cards | Footer notes were at different heights across the three cards | Fixed with `flex: 1` on `.mech p` — paragraph fills available space, pinning the footer note to the same baseline in all cards regardless of content length |
| 5 | Pilot diagram | Rail and month labels were too close to milestone boxes; the visual gap was only between the label text and the boxes, not the timeline line itself | Lowered the rail + milestone circles from y=120 to y=142, creating a clear visual gap between the milestone boxes and the timeline |
| 6 | Pilot diagram | Month labels were placed below their own tick mark, not between marks | Decoupled tick marks (10 boundary lines) from labels (9 text elements); labels now centred between consecutive boundary marks |
| 7 | Pilot diagram | "Outputs & learnings shipped" title and list items were small | Header font 11→13px, list items 11.5→12.5px |
| 8 | Section order + Navbar | "For Cardano" appeared before "Opportunity" in both the page and the nav | Swapped: order is now What it is → How it works → Opportunity → For Cardano → The pilot → The team → The ask |
