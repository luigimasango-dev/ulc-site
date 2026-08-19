# ULC website — one page, ready to host

Built 2026-08-01. Fixes the problem that cost a real deal: Cara Hartley (Palmer
Development Group) checked ULC before replying, found no verifiable public
footprint, and declined. Every serious prospect does the same thing.

`index.html` is self-contained — no build step, no dependencies, no external
requests. Drop it anywhere.

## What is on it, and why nothing else is

Only facts that are verified on file:

- Reg **2026/027426/07** (CIPC, "IN BUSINESS")
- **B-BBEE Level 4 EME, 100% procurement recognition** (cert 9450437961, expires **11 Jan 2027**)
- SARS income-tax registered
- Founder: Luigi Masango. Katlehong, Gauteng.
- Contact: ubuntulabs.ai@gmail.com

**No client names, no logos, no testimonials, no track-record claims, no
statistics.** Not modesty — a prospect doing due diligence is checking whether
ULC is real, and an unverifiable claim on the page is worse than a plain one.
Add case studies once there are real ones to add.

Co-director Lesedi Siyabonga Majake is deliberately not named (silent partner).

## Before it goes live — two things

1. **The B-BBEE certificate expires 11 January 2027.** Diarise it. The page states
   the level, so it becomes a false claim the day it lapses.
2. **Get a real email address on a real domain.** `ubuntulabs.ai@gmail.com` on a
   tender enquiry undercuts the whole point of having a site. A domain with one
   forwarding mailbox is roughly R150/year.

## Hosting — pick one, all free

**Netlify Drop** (fastest, ~2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag the `ulc-site` folder onto the page
3. You get a live URL immediately; add a custom domain under Site settings → Domain management

**Cloudflare Pages** — https://pages.cloudflare.com → Direct Upload → upload the folder.
Free SSL, and the best option if you buy the domain through Cloudflare too.

**GitHub Pages** — push this folder to a repo, then Settings → Pages → deploy from branch.

## Domain

`ubuntulabconsultants.co.za` is set as the canonical URL in the HTML. If you
register something different, update the `<link rel="canonical">` and the
`og:` tags in `index.html`. A `.co.za` runs about R100–150/year — try
domains.co.za, Afrihost, or Cloudflare Registrar.

## After it is live

- Put the URL in your email signature and on every outreach template
- Create a LinkedIn **Company** page pointing at it — that is the second thing
  prospects check, and it is free
- Add the URL to the ULC capability statement

## Structured data

The page carries JSON-LD (`ProfessionalService`) with the registration number,
location and contact, so search engines can render it as a real business rather
than an unattributed page. Keep it in sync if the details change.
