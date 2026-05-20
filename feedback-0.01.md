# GOV.EXE Landing — Feedback v0.01

> Working order below. Each item includes the section, current state, and target state.
> Items will be implemented one at a time for confirmation before moving to the next.

---

## SECTION: Navbar

| # | Item | Current | Target |
|---|------|---------|--------|
| 1 | Nav link label | `Market` | `Opportunity` |
| 2 | Nav link missing | No link to team/parties section | Add `The team` link → `#team` |

---

## SECTION: Hero

| # | Item | Current | Target |
|---|------|---------|--------|
| 3 | Primary CTA | `Read the ask →` → `#ask` | `Read full proposal →` → `https://hydra-voting.intersectmbo.org/votes/cardano-budget-2026/69fd1b97e1ab5d003a0cab6f` |
| 4 | Funding ask stat | `2,335,400 ADA` + `+ 583,850 ADA contingency` | Add rate (ADA/USD 0.25) + USD equivalents split: proposal ~$583,850 USD / contingency ~$145,963 USD |
| 5 | Delivered by stat | `TxPipe + gf Consulting Group` (breaks into two lines) | Must fit a single row — shorten or adjust layout |
| 6 | Institutional partner stat | `Secretariat of Modernization, Province of Entre Ríos` | Add `, Argentina` |

---

## SECTION: What it is

| # | Item | Current | Target |
|---|------|---------|--------|
| 7 | Section `<h2>` | `A single accountable workflow for executing public projects.` | `GOV.EXE brings a public project's full lifecycle into one verifiable workflow.` |
| 8 | Remove paragraph | `The problem is a recognized multilateral priority: the World Bank, OECD, and IDB run dedicated programs...` | Remove entirely (content is covered in the Market/Opportunity section below) |

---

## SECTION: How it works (diagram)

~~Item 9 discarded.~~

---

## SECTION: Why Cardano → renamed "For Cardano"

| # | Item | Current | Target |
|---|------|---------|--------|
| 10 | Section eyebrow | `Why Cardano` | `For Cardano` |
| 11 | Section `<h2>` | `Concrete outputs and engagements — bounded, beyond the pilot.` | `Three concrete mechanisms **that** create value beyond the pilot` |
| 12 | Body text — remove & replace | `We commit to the work, not to adoption outcomes we can't control.` | `The pilot tests whether this public-sector vertical can scale on Cardano through builder uptake, jurisdiction interest, and measurable ROI.` |
| 13 | Card 1 title | `Case study` | `Case study — Institutionally endorsed` |
| 14 | Card 3 title | `LATAM prospecting briefings` | `LATAM prospecting learnings` |
| 15 | Card footnotes alignment | Bottom notes flow freely based on text length | Fix to same baseline height across all three cards (CSS: `margin-top: auto` on `.meta`) |

---

## SECTION: Market → renamed "Opportunity"

| # | Item | Current | Target |
|---|------|---------|--------|
| 16 | Section eyebrow | `Market` | `Opportunity` |
| 17 | Section `id` attribute | `id="market"` | `id="opportunity"` |

---

## SECTION: The pilot (diagram)

| # | Item | Current | Target |
|---|------|---------|--------|
| 18 | Month labels in timeline | `M1, M2, M3 … M9` | `Month 1, Month 2, Month 3 … Month 9` |
| 19 | Vertical spacing in diagram | Milestones and month labels too close | Increase vertical gap between milestone boxes and month labels row |
| 20 | Caption sentence | `…generating the case-study and replication-framework material delivered in M6.` | `…generating the case-study and learnings delivered in M6.` |

---

## SECTION: Parties → renamed "The team"

| # | Item | Current | Target |
|---|------|---------|--------|
| 21 | Section eyebrow | `Parties` | `The team` |
| 22 | Section `id` attribute | `id="partners"` | `id="team"` |
| 23 | TxPipe logo placeholder | `TX` | `TP` |
| 24 | TxPipe description | Bullet: `20+ years building software platforms for institutions, including MiBA (City of Buenos Aires)` | Move into description paragraph; remove from bullet list |
| 25 | TxPipe social link | None | Add X link → `https://x.com/txpipe_tools` |
| 26 | GF Consulting description | Bullet: `Client list: IDB, World Bank, CAF, Fonplata, UNDP, OEI, UNOPS…` | Move into description paragraph; remove from bullet list |
| 27 | GF Consulting social link | None | Add X link → `https://x.com/GeroFrigerio` |

---

## SECTION: The ask

| # | Item | Current | Target |
|---|------|---------|--------|
| 28 | Section `<h2>` | `2,335,400 ADA for a 9-month pilot — with budget caps, audit, and a contingency reserve.` | `2,335,400 ADA for a 9-month pilot — with USD budget caps and a contingency reserve.` |
| 29 | Funding row | `2,335,400 ADA` + `+ 583,850 ADA contingency reserve` | Add ADA/USD rate (0.25) + USD equivalents: proposal ~$583,850 / contingency ~$145,963 |
| 30 | CTA order & hierarchy | 1. Letter of intent (solid/primary) · 2. Preliminary design (secondary) · 3. Full proposal on Hydra-Voting (secondary) | 1. Full proposal on Hydra-Voting (primary/solid) · 2. Letter of intent (secondary) · 3. Preliminary design GitHub (secondary) |

---

## Summary counts

- **Navbar:** 2 items
- **Hero:** 4 items
- **What it is:** 2 items
- **How it works:** 1 item
- **For Cardano:** 6 items
- **Opportunity:** 2 items
- **The pilot:** 3 items
- **The team:** 7 items
- **The ask:** 3 items

**Total: 30 items across 9 sections**

---

## Open questions / scope notes

- ~~**Item 9 (on-chain validators):** Discarded.~~
- ✅ **Items 4 & 29 (USD equivalents):** Confirmed — Proposal: **$583,850 USD** · Contingency: **$145,963 USD** (ADA/USD 0.25).
- ✅ **Item 5 (Delivered by single row):** Fix is a column-sizing issue — adjust `grid-template-columns` in the hero stats to give columns 3 & 4 more proportional width, not abbreviation or font changes.
