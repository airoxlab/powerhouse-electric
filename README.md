# Power House Electric — Chino

Single-page sample site for a newly licensed C-10 electrical contractor in
Chino, California (Inland Empire). Built as a free sample for a warm SMS lead
who is currently trying to build a site himself.

## Business details

| | |
|---|---|
| Business | Power House Electric |
| Owner | **Not public** — ask him |
| Phone | (626) 485-7345 (mobile — call and text both offered) |
| Location shown | Chino, CA |
| Website | None |
| Google / Facebook / Instagram / Yelp | **None** — not listed anywhere |

## ⚠️ Licence NOT independently verified — do this before sending

**The CSLB database was down when this was built (2026-10-12).** The licence
detail page at `LicenseDetail.aspx?LicNum=1158711` loads, but returns no
business record — no name, status, classification or bond.

This was confirmed to be an outage, not a problem with his licence: a **control
query against EVJ Painting #1134654** — verified active two days earlier —
**also returned no record** in the same session. Four attempts over the build,
all empty. CSLB's database is documented as unavailable Sunday 8pm to Monday
6am, and today is Monday.

**Every licence claim on this page comes from the brief, not from my own check:**

- C-10 Electrical, #1158711, status CLEAR/active
- Issued 07/28/2026, expires 07/31/2028
- $25,000 bond, American Contractors Indemnity #101077633
- Workers' comp **exempt** (no employees)

**Re-run the check before sending him the link.** The script is at
`scratchpad/lic-ph2.js`; it fills `#MainContent_LicNo` and clicks
`#MainContent_Contractor_License_Number_Search`. If anything differs from the
above — particularly the status — the licensing section and the hero pill need
correcting first. Every other site in this collection had its licence confirmed
first-hand; this one is the exception and should not stay that way.

As with the other comp-exempt contractors, the site says **"licensed & bonded"**
and never "insured", and frames the exemption as "owner-operated — the person
who holds the licence is the person doing the work."

## The pitch context

From the SMS thread (Oct 10), in his own words:

> "I just started my company, I am actually working on that, I should have one soon"
> ...
> "How much do you charge?" → quoted $300 setup + $99/month, no contract
> → **"Sample yeah I'll check it out"**

He asked the price himself, heard it, and still wanted the sample. That is a
strong signal. **He is also building a site himself right now**, so this needs to
reach him before he finishes or buys a DIY builder. Speed is the whole play.

## What was deliberately not built

- **No reviews or testimonials.** Licensed July 2026, no listings, no reviews
  anywhere. Nothing honest to show.
- **No years-in-business or job-count claims.** The business is ~2.5 months old.
- **No owner name.** Not published anywhere.
- **No "insured" claim** — comp-exempt.
- **No 24/7 or response-time promise** — nothing supports it.
- **No street address.** 13151 Yorba Ave **#80** is a unit number and almost
  certainly where he lives; the site shows "Chino, CA" and a service area only.
- **Residential scope only.** His focus is unknown, so the six services are the
  standard residential C-10 offering. Needs confirming.

## Turning "brand new" into an asset

A two-month-old company has no reviews and no history, which is the obvious
weakness. Rather than hide it, the process section carries a short band:

> **A new company, not a new electrician** — "Power House Electric is a newly
> licensed business, and that is exactly why the licence number is printed at the
> top of this page. Check it at cslb.ca.gov before you let anyone touch your
> panel — we would rather you did."

It is honest, it pre-empts the objection, and it makes the one hard credential he
does have do the work. Note it says *a new company, not a new electrician* — he
almost certainly has trade experience predating the licence, but nothing public
confirms it, so the page implies rather than claims it. **If he gives you a
number of years, that line should be rewritten to state it outright.**

## Images

`img/` — seven stock photos (Unsplash). He has no photos of his own anywhere.
Disclosed under the gallery and in the footer, with the caption noting his own
job photos will replace them as work is completed.

## Design

Fourth electrician in this collection, so it needed a fourth distinct identity:

| Site | Look |
|---|---|
| Rockbottom Electric | Dark near-black + voltage yellow, industrial |
| Dan's Electrical | Warm cream + brass, serif, high-end residential |
| Arcline Electric | Light, deep navy + arc blue, clean and technical |
| **Power House Electric** | **Graphite + high-vis orange, utility/substation** |

- Palette from the name — a power house: graphite `#24282B`, high-vis safety
  orange `#E8601C`, warm copper and steel accents.
- Chakra Petch (technical display, uppercase headings) + Manrope (body).
- Inline SVG mark: a house outline with a bolt through it.
- Square-cornered cards with a top accent rule, for a utility feel rather than
  the rounded softness of the other three.
- Eight sections: hero, credential strip, services, process + new-business band,
  work gallery, service areas, licensing, contact.
- **Call and text both offered** throughout (`tel:` and `sms:`) — it is a mobile
  number and new tradespeople often pick up texts faster.
- Full dark mode, sticky header, `scroll-margin-top` anchors, reduced-motion
  respected, inline CSS, no build step.
- Sendra visit-tracking script before `</body>`.

## Open questions for the client

1. **His name** — so the site can have an owner story.
2. **Years of experience** before the licence — would strengthen the
   new-business band considerably.
3. **Job photos** — even phone pictures of panels or installs.
4. **What he focuses on** — residential service, panels, EV chargers, solar?
5. **Which cities** he actually wants work in.
6. **Logo**, if he has one. The house-and-bolt mark is a placeholder.

## The bigger opportunity

He is **not on Google Maps at all** — a search for "Power House Electric Chino"
returns only unrelated companies (HW Power, Power Amp Electric, Power System
Services), and his phone number brings up nothing. When someone in Chino searches
"electrician", 20+ competitors appear and he does not.

For a business this new, **a verified Google Business Profile is worth more than
the website**, and the two together are the real starter kit. Pitch them as one.

Note these are **different companies**: powerhouseelectric.us (Salinas),
powerhouseelectricalllc.com (licence 1112719), powerhouseelectricpa.com
(Pennsylvania). None is him.
