# Halcyon × Leverage Edu — Outreach Package

**For:** Rushan Khan, CFO, Halcyon Medical Billing LLP
**Prepared:** 06 May 2026
**Status:** Ready to send

A complete outreach package for the Leverage Edu partnership pitch — proposals, PDFs, lead list, and the email Rushan should send.

---

## What's in this repo

| Path | What it is |
|---|---|
| [`proposals/`](proposals/) | 5 fully-designed HTML proposal documents (each loads instantly in any browser) |
| [`pdfs/`](pdfs/) | The same 5 proposals as PDFs (for direct attachment to the email) |
| [`leads/leverage-edu-contacts.csv`](leads/leverage-edu-contacts.csv) | 30+ named contacts at Leverage Edu, grouped by tier |
| [`email/email-rushan-to-leverage.md`](email/email-rushan-to-leverage.md) | The exact email to send, with subject lines, body, send timing, and follow-up plan |
| [`research/leverage-edu-briefing.md`](research/leverage-edu-briefing.md) | The full research file we built the pitch on |

---

## Quick links to the 5 proposals (read these first)

| # | Volume | Pages | Best for | Live link | PDF |
|---|---|---|---|---|---|
| I | **The Alumni Engine** | 7 | Partnerships team — leading with the alumni-as-referral angle | [HTML](proposals/v1-alumni-engine.html) | [PDF](pdfs/Halcyon-Leverage-v1-alumni-engine.pdf) |
| II | **The Employer Bundle** | 7 | Leverage Careers commercial team — bundling Halcyon to US clinic accounts | [HTML](proposals/v2-employer-bundle.html) | [PDF](pdfs/Halcyon-Leverage-v2-employer-bundle.pdf) |
| III | **The Diaspora Channel** | 7 | CMO — co-marketing into Indian-American physicians | [HTML](proposals/v3-diaspora-channel.html) | [PDF](pdfs/Halcyon-Leverage-v3-diaspora-channel.pdf) |
| IV | **The IPO Narrative** | 5 | Akshay + CFO — short, banker-framed memo | [HTML](proposals/v4-ipo-narrative.html) | [PDF](pdfs/Halcyon-Leverage-v4-ipo-narrative.pdf) |
| V | **Master Deck** | 10 | All three surfaces in one document — recommended attachment | [HTML](proposals/v5-master-deck.html) | [PDF](pdfs/Halcyon-Leverage-v5-master-deck.pdf) |

---

## What Rushan needs to do — 9-step checklist

> ⚠️ **Read this in order. Don't skip steps. The full outreach should take ~30 minutes of focused work.**

1. **Read the email draft first** — open [`email/email-rushan-to-leverage.md`](email/email-rushan-to-leverage.md). Note the 10 recipients (5 TO + 5 CC + 1 BCC) and the three subject-line options.

2. **Skim the Master Deck (Volume V)** — open [`proposals/v5-master-deck.html`](proposals/v5-master-deck.html) in your browser to make sure you're comfortable owning every claim in it. Anything you'd word differently — flag it before sending.

3. **Verify the 10 email addresses** — paste them into Hunter.io's email verifier or NeverBounce. The pattern is `firstname@leverageedu.com` for senior leadership and `firstname.lastname@leverageedu.com` for ICs. Anchor against `akshay@leverageedu.com` (confirmed working) — if that resolves, the rest of the pattern likely does too.

4. **Pick a subject line** — three options listed in the email draft. **Recommendation: option A** (most strategic-specific). If you want it to feel personal to Akshay, use option C.

5. **Compose the email in Gmail/your client** —
   - **FROM:** outreach@halcyonmedbilling.com
   - **REPLY-TO:** rushan@halcyonmedbilling.com (set this in your email client's settings — important so replies route to you, not the outreach inbox)
   - Body: copy-paste the body section from the email draft. The HTML version preserves formatting; the plain-text fallback is provided for clients that strip styling.
   - Attach `pdfs/Halcyon-Leverage-v5-master-deck.pdf` directly. Keep the other 4 as links in the body — too many attachments looks like spam.

6. **Send Tuesday 12 May at 09:30 IST** — this is 05:00 UTC, 06:00 BST, 19:00 ET-prior-day. Lands in Delhi inboxes at start-of-day. Avoid Mondays (overflow) and Fridays (deferred). If 12 May doesn't work, target any Tue–Wed before 19 May.

7. **First follow-up: Friday 22 May** — short, one-line bump on the same thread, reply-all. The exact text is in the email draft, section "Sending notes for Rushan."

8. **Second follow-up: Tuesday 26 May** — final reach before the 27 May deadline named inside the proposals. Same thread.

9. **If silent across all 10 by 30 May** — fall to the Tier-2 list (Aman, Digvijay, Aditya, Bharti, Sudipta) with the **IPO Narrative (Volume IV)** as the lead doc. Different anchor, different audience, different shot.

---

## How the proposals were built (so you can edit if needed)

- All 5 are static HTML — no build step. Open the `.html` file in any browser to see the live version.
- They share `proposals/_styles.css` — edit the CSS once and all five update.
- They follow Halcyon's existing **DESIGN.md** design system (navy + gold, Inter font, no rounded corners).
- Each "page" inside the HTML is a fixed 11×8.5-inch slide (US Letter landscape) — that's why the PDF exports cleanly with one slide per page.
- To regenerate any PDF after editing, run:
  ```
  /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome \
    --headless --disable-gpu --no-pdf-header-footer \
    --print-to-pdf=pdfs/Halcyon-Leverage-vN-name.pdf \
    file://$(pwd)/proposals/vN-name.html
  ```

---

## Lead list — top 5 to send to (ranked)

The full list is in [`leads/leverage-edu-contacts.csv`](leads/leverage-edu-contacts.csv) (30+ named contacts). Top 5 to put on the TO line of your first email:

1. **akshay@leverageedu.com** — Akshay Chaturvedi, Founder & CEO (confirmed working)
2. **anurag.kamandula@leverageedu.com** — Sr. Director, Global Demand & University Partnerships (best title-match for the pitch)
3. **rachit@leverageedu.com** — COO, Platform Business (owns Fly Finance + Fly Homes — the "adjacent monetisation" thinker)
4. **sandeep.upadhyay@leverageedu.com** — Chief Business Officer
5. **shriya.raina@leverageedu.com** — Senior Manager, Partnerships (most likely to actually open & route)

CC list (5): Aditya Arora (CFO), Ambesh Tiwari (CMO), Aman Arora (Co-founder), Nippun Sharma (SVP Sales), Pushhkar Mishra (B2B Partnerships).

---

## What we know about Leverage Edu (the short version)

The full briefing is in [`research/leverage-edu-briefing.md`](research/leverage-edu-briefing.md). The 60-second summary:

- **Indian study-abroad ed-tech.** ₹375 Cr FY26 revenue (+112% YoY), now EBITDA-positive, 155K+ students placed cumulatively, 60+ offices in 27 countries.
- **₹2,000–3,000 Cr IPO in 12–18 months** (Inc42, April 2026). Bankers tapped.
- **Nursing/Healthcare is now an explicit growth vertical.** Leverage Careers signed an MoU with Tamil Nadu Skill Development Corporation in 2025 to train and globally place 120+ nurses/year — including USA H1B-sponsored RN placements.
- **They already run a partner-affiliate program** with UTM-tracked dashboards and monthly payouts. So a Halcyon channel is **configuration, not a build**.
- **The CEO Akshay Chaturvedi** personally speaks for both Leverage Edu and Leverage Careers on every nursing announcement — he's the right top-of-funnel target.

---

## Questions / changes

If anything in the proposals needs to change — a number, a claim, a tone — message Naitik directly and we'll regenerate the affected docs. The HTML is plain text, the PDFs are 30 seconds to re-export.

— *Halcyon team · 06 May 2026*
