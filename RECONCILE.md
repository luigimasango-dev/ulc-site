# Site reconciliation — ulc-site three copies vs canonical rate card

Source of truth for prices/terms: `ULC Master HQ/CANONICAL_RATE_CARD_AND_90DAY_PLAN_2026-08-12.md` (canonical rate card, produced 2026-08-12).
Standing wording (P2 brief, verified 2026-10-18): B-BBEE = "Exempted Micro Enterprise — affidavit on file, 100% black-owned, 135% procurement recognition" + "Level 1 status pending corrected certificate" if a level is referenced; no VAT lines; no success fees / contingency / pay-on-award; 100% prepaid EFT, work starts on proof of payment; co-director never named; no fabricated testimonials, clients or case studies.

Three copies compared:
- A = `C:\Dev\ulc-site\index.html` — the copy deployed live at https://luigimasango-dev.github.io/ulc-site/ (git clone, origin luigimasango-dev/ulc-site, branch main, clean).
- B = `ULC Master HQ/site/index.html`
- C = `ULC Master HQ/website/index.html`

Verdicts: MATCHES | CONTRADICTS | UNCONFIRMED | MISSING.

## Claims table

| Copy | Element | Claim as written | Canonical rate card / standing order | Verdict |
|------|---------|------------------|--------------------------------------|---------|
| A | Page title | "Tender & Compliance Advisory \| Gauteng, South Africa" | Rate card covers tenders + compliance + doc automation + payroll + TPRM/OSINT + leadgen | MISSING (title narrows scope) |
| A | Meta description | "...B-BBEE Exempted Micro Enterprise, 100% black-owned. Katlehong, Gauteng." | Standing wording requires "— affidavit on file, 100% black-owned, 135% procurement recognition" (+ pending certificate) | CONTRADICTS (incomplete B-BBEE wording) |
| A | Hero facts | "B-BBEE — Exempted Micro Enterprise, 100% black-owned" | Same standing wording | CONTRADICTS (incomplete) |
| A | Hero facts | "CIPC registered and in good standing" | CIPC status not independently verified here | UNCONFIRMED |
| A | Hero facts | "SARS income-tax registered" | SARS status not independently verified here | UNCONFIRMED |
| A | Services | "Bid & tender compliance" | Matches rate-card product family (Quick Check, Ready File, Bid Pack Compile, Deadline Watch) | MATCHES |
| A | Services | "JV & consortium facilitation" | Standing order: ULC never bids in its own name; JV sourcing is described in rate card prose but not a priced product | UNCONFIRMED (not a rate-card line) |
| A | Services | "Regulatory & partner due diligence" | Maps to POPIA gap report / B-BBEE estimate / footprint audit | MATCHES (family) |
| A | Services | "Grant applications" — SEDFA, NYDA, dtic, SETAs, WSP/ATR | No grant product on canonical rate card (grants vertical exists separately at 05_Grants but is not a priced line) | CONTRADICTS (not on card) |
| A | Prices | No prices shown anywhere on page | All 10 rate-card lines carry fixed prices (R950 … R6,500) | MISSING |
| A | Company details | B-BBEE status: "Exempted Micro Enterprise · 100% black-owned" | Standing wording | CONTRADICTS (incomplete) |
| A | Company details | Reg 2026/027426/07, Katlehong, Gauteng | Matches CIPC registration number on record | MATCHES |
| A | How we work | "Compliance work is quoted and invoiced on delivery" | Rate card: 100% prepaid EFT; work does not start until proof of payment | CONTRADICTS |
| A | How we work | "Where we broker a joint venture, a success fee applies on award — agreed in writing up front." | Standing order: no success fees, no contingency, no percentage ever | CONTRADICTS |
| A | Canonical link | `<link rel="canonical" href="https://ubuntulabconsultants.co.za/">` | Domain ownership/control not verified; live hosting is GitHub Pages | UNCONFIRMED |
| A | Contact | Email only (ubuntulabs.ai@gmail.com); no phone/WhatsApp | Rate-card order flow relies on WhatsApp 081 827 7123 (published on copy B/C) | MISSING (phone) |
| A | Privacy | Link to privacy.html present, page exists | Privacy link must be kept | MATCHES |
| A | Testimonials / clients / case studies | None present | Must not invent any | MATCHES (none invented) |
| A | VAT | None mentioned | No VAT lines (not VAT registered) | MATCHES |
| B | Hero kicker | "Fixed price · Prepaid EFT · No win fee" | Matches standing order | MATCHES |
| B | Hero sub | "Exempted Micro Enterprise, 100% black-owned. Prices exclude VAT. Work starts on proof of payment." | B-BBEE wording incomplete; VAT correct; prepaid correct | CONTRADICTS (B-BBEE incomplete) |
| B | Prices | R950 Quick Check · R2400 3-pack · R2500 Ready File · R950/mo Deadline Watch · R1500 Call Sheet · R950 "Grant Check" | Grant Check R950 is NOT on canonical rate card | CONTRADICTS (Grant Check) |
| B | Prices (the six that match) | R950 / R2400 / R2500 / R950/mo / R1500 | Match canonical card exactly | MATCHES |
| B | "Most ordered" flag on Quick Check | No sales data exist (ULC booked R0) | Unverifiable marketing claim | UNCONFIRMED |
| B | "40–60 min measured read time" | Not measured anywhere on disk | Unverified claim | UNCONFIRMED |
| B | Deadline Watch | Weekly, every Monday, three sector clusters, capped at 15 | Matches rate card | MATCHES |
| B | Contact | WhatsApp 081 827 7123 published | Published contact; not independently dialled/verified here | UNCONFIRMED |
| B | FAQ refund | "No. The R950 buys the read, not a yes." | Matches "No refund after delivery" | MATCHES |
| B | FAQ briefing | "A passed compulsory briefing closes that tender." | Matches rate-card six-gate briefing foreclosure | MATCHES |
| B | VAT | "Prices exclude VAT" | Matches | MATCHES |
| C | Prices | R950 Quick Check · R2400 3-pack · R2500 Ready File · R6500 Bid Pack Compile · R1,500 B-BBEE Scorecard Estimate · R3,500 Digital Footprint Audit · R1,500 Sector Call Sheet | Seven of ten card lines present and correctly priced | MATCHES (partial) |
| C | Prices — missing lines | Deadline Watch R950/mo, POPIA Data-Flow Gap Report R4500, Ghost Employee Sweep R3500 absent | All three are canonical rate-card lines | MISSING |
| C | B-BBEE (footer) | "Exempted Micro Enterprise · 100% black-owned" | Standing wording | CONTRADICTS (incomplete) |
| C | "No success fees, no percentages" | Explicit limit | Matches standing order | MATCHES |
| C | "We don't tender in our own name" | Explicit limit | Matches standing order | MATCHES |
| C | Pay | Capitec Business, account supplied on invoice | Matches rate-card terms | MATCHES |
| C | Founder | "Luigi Masango ... Founder and director. Katlehong, Gauteng." | Luigi is the founder; co-director not named | MATCHES |
| C | Digital Footprint Audit | Gated behind free pre-scan; thin domains get pre-scan free, no sale | Matches rate card gate | MATCHES |
| C | Sector Call Sheet | "Under 50% coverage, we decline the job" | Matches kill condition | MATCHES |
| C | Privacy | No privacy page or link in this copy | Privacy link must be kept | MISSING |
| C | Specimen block | Placeholder "[tender number]" / "[your company]" content, ribboned "Specimen" | No client PII, clearly marked specimen | MATCHES |
| C | Specimen B-BBEE line | "Level 2 stated as the minimum. An Exempted Micro Enterprise clears this threshold." | Placeholder specimen content; does not claim ULC's own level | MATCHES (specimen only) |

## Consolidated contradiction list (must be fixed in index.next.html)

1. B-BBEE wording incomplete on all three copies — replace with the exact standing wording plus "Level 1 status pending corrected certificate".
2. Copy A: "invoiced on delivery" → must say 100% prepaid EFT, work starts on proof of payment.
3. Copy A: "success fee applies on award" → remove; no success fees ever.
4. Copy A: "Grant applications" service → remove (not a canonical rate-card product).
5. Copy B/C: "Grant Check" R950 → remove (not on card).
6. All copies: no full price list → index.next.html lists all 10 rate-card products at card prices only.
7. Copy A/C: no privacy link/page → keep privacy link in next.
8. Copy A: canonical points at unverified domain ubuntulabconsultants.co.za → keep GitHub Pages canonical or remove.
9. Unverified claims to drop: "Most ordered", "40–60 min measured read time".
10. No testimonials, clients or case studies may be invented (none exist in any copy — keep it that way).
