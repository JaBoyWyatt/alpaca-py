# Handoff prompt: Zach of All Trades

Paste everything below this line into a new session.

---

You're picking up a live build. My buddy Zach and I (Wyatt) are building **Zach of All Trades**, a handyman business, from zero to fully running. Then I hand it off to Zach. He has nothing yet: no LLC, no domain, no accounts, no brand. The plan is done and approved, and your job is to execute it.

The living plan doc is at https://claude.ai/artifact/6v7P7gyj9uxAgkc7pP2sMG. Read it first if you can reach it. The full text is pasted at the bottom of this prompt in case you can't.

## How I work

Be terse. No em dashes, no padding, no bullet points in chat unless I ask. Don't repeat my question back. Do the work, then tell me what got done and where it lives. Only stop to ask when something is truly blocked on a decision that's mine or Zach's.

## Hard rules

1. Every account is created under Zach's business email and billed to Zach's card. I'm added as admin, never owner. Never create an account under my email (wyatt@skidpro.com) for this business.
2. Never buy anything, publish anything public, send email or texts to real people, or turn on ads without my explicit OK in that message.
3. AI never sends a price on custom work by itself. Zach always approves custom quotes.
4. Every automation gets tested end to end with a fake customer before launch.
5. Prices and costs in the plan are placeholders or from memory. Verify current pricing before quoting it to me as fact.

## Connectors to look for

Load these with tool search before saying something can't be done:
- **GoDaddy:** domain availability and suggestions
- **WP Agent:** builds and edits the WordPress site
- **Zapier:** form to Jobber to email/text glue, plus Claude photo-quote drafting
- **Canva:** logo, truck magnet, cards, yard sign
- **Gmail:** drafts only unless I say send

HubSpot is connected, but we are NOT using it. Jobber is the CRM.

## Where we are

The plan is approved. Nothing is built yet. These open decisions block parts of the build:
- Zach's town or towns. This blocks the domain, the Google Business Profile name ("Zach of All Trades | [Town] Handyman") and every page title.
- Zach's state. This sets the license, bond and insurance rules.
- His top 10 jobs and the prices for the menu (the menu in the plan is a placeholder).
- Whether he's full time or nights and weekends.
- Jobber or FieldPulse after a demo.
- Whether he passes on the 3% card fee.
- Whether navy plus safety orange is OK as the placeholder brand.

## What to do first

1. Ask me only for the town and state if they still aren't answered. Everything else can move in parallel.
2. Once you have the town, pull domain options through GoDaddy (zachofalltrades.com plus town variants) and give me the top 5 with prices. Don't buy.
3. Draft the WordPress site structure and copy: Home, a Services page per top job, Service Area, Reviews, Gallery, About Zach, and Get a Price. Draft only, nothing published.
4. Spec the Get a Price form. Menu lane: 2 to 4 questions, an instant price, a booking slot, and a card on file. Custom lane: required photos plus a description, AI-drafted quote, Zach approves, quote texted with a deposit link. Out of scope lane: polite no plus a referral.
5. Draft every Zapier workflow in the Automations table as a draft, not enabled.
6. Make the Canva placeholder brand kit.
7. Keep a running checklist in the plan doc. Tick items as they're done and add a note under Open decisions when something new comes up.

## Background that shaped the plan

The model for this is Caleb Ingram, North Seattle Handyman, from an UpFlip interview. He did $25k a month solo on about $5k startup and $100 a month of software, and $40k a month with 2 people. He charges $100 an hour and offers both flat worst-case bids and hourly. He found small interior jobs pay better than remodels and targets people with money who don't own a screwdriver. He named the business after the area for Google ranking and asks customers to put "North Seattle handyman" in their reviews. His intake is a required online form with photos, then a Google Form, then Zapier, then email plus his CRM (FieldPulse), so he quotes from pictures without driving out to bid. He uses HomeWise for job-time benchmarks and Yelp ads at about $600 a month as an on/off tap. He's booked 6 weeks out. His worst pain is rescheduling when a job runs long. His three pieces of advice: get started with friends and a website, treat customers like people, and systemize. We copy his system and add 2026 AI on top: an AI receptionist, AI photo-quote drafting, automatic follow-ups, review asks, AI review replies, and AI bookkeeping.

---

# FULL PLAN (as of Oct 30, 2026)

## The play

We build Zach a handyman business that runs itself from the first call to the paid invoice, then hand him the keys. A customer finds him on Google, gets a price or a photo quote online in minutes, books a slot, pays by card, and gets asked for a review. AI answers the phone, drafts the quotes, chases the follow ups and keeps the books. Zach just does the work and taps approve.

The target at handoff: every account in Zach's name, every automation tested end to end, $100/hr pricing, 5+ Google reviews, and a one page SOP plus a walkthrough video.

## Caleb's playbook, upgraded for 2026

| Caleb did (about 2021) | We do now |
| --- | --- |
| Named the business after the area for Google | Brand stays Zach of All Trades; Google profile and page titles carry "[Town] Handyman" |
| Required form with photos, read by hand | Same form, but AI reads the photos and drafts the quote for Zach to approve |
| Flat-rate and hourly, priced from experience | Instant prices on the site for menu jobs, HomeWise benchmarks plus AI for the rest |
| Phone calls went to his cell | AI receptionist answers 24/7, quotes menu jobs, books, and texts the quote link |
| Asked customers to put "North Seattle handyman" in reviews | Automated review ask with the town and "handyman" prompted, AI drafts the replies |
| Squarespace site built with his sister | Site built by us, managed through the WordPress connector |
| Rescheduling 25 people when a job ran long was his worst pain | CRM auto texts everyone affected with new slots |
| $600/mo Yelp as an on/off tap | Same, plus Google Local Services Ads (pay per lead, Google Guaranteed badge) |
| Business coach for decisions | This doc plus Wyatt plus Claude |

We copy straight: $100/hr from day one, small interior jobs over remodels, people with money and no tools, and agents and property managers as a free lead source.

## Ownership rules

Every account is created under Zach's business email and paid with Zach's business card from day one. Wyatt gets added as an admin or team member, never the owner. Handoff then means removing Wyatt, with nothing to migrate. Passwords live in a shared 1Password or Bitwarden vault that Zach owns. Two factor goes to Zach's phone. The domain registers in Zach's name, with auto renew on.

## Phase 1: Foundation (Zach's homework, gates going live)

Licensing rules vary by state, so check his state's contractor board before the first paid job.
- [ ] Form an LLC, then get an EIN (free, irs.gov)
- [ ] Open a business checking account; no personal money through the business
- [ ] General liability insurance, $1M coverage (Caleb pays about $4k a year as a GC; handyman tier is usually less)
- [ ] Contractor license or registration plus bond if the state requires it (Caleb's $10k bond runs about $250 a year)
- [ ] Google Workspace on the new domain: zach@ and quotes@
- [ ] Business phone line on OpenPhone or Quo, which supports the AI receptionist and texting
- [ ] Password manager vault, shared with Wyatt
- [ ] Buy the domain (needs the town decision first)

## Tech stack

Jobber is the backbone. FieldPulse is the backup if Zach likes it better in a demo. Skip HubSpot.

| Job | Tool | Why |
| --- | --- | --- |
| CRM, quotes, scheduling, invoices | Jobber | One app for the whole job, phone app, client portal, online booking |
| Payments | Jobber Payments (card, ACH, tap to pay) | Next day deposits, one dashboard |
| Financing on big jobs | Wisetack via Jobber | Customer pays monthly, Zach paid in full |
| AI receptionist | Jobber AI Receptionist, or OpenPhone AI if cheaper | Answers 24/7, books |
| Website | WordPress via WP connector | Editable from Claude, easy handoff |
| Instant quote form | Custom form on site, feeding Jobber | Prices menu jobs, takes photos for the rest |
| Photo quote drafting | Zapier plus Claude | Reads photos, drafts line items from Zach's price book |
| Glue | Zapier | Same as Caleb, now with AI steps |
| Books and taxes | QuickBooks Online, synced from Jobber | AI categorizes |
| Job time benchmarks | HomeWise | "Book time for handymen" |
| Design | Canva | Logo, magnet, cards, signs |
| Passwords | 1Password or Bitwarden | Clean handoff |

## Website and instant quotes

The site exists to turn a Google search into a booked, priced job without Zach touching his phone. Every page pushes to one button, Get a Price. Pages: Home, Services (one per top service, town in the title), Service Area, Reviews, Gallery, About Zach, Get a Price. Use real photos of Zach and his truck.

The form has three lanes:
1. **Menu jobs** (TV mount, faucet, ceiling fan, door, furniture assembly): 2 to 4 questions, a firm price on screen, pick a slot, card on file. Booked with no human.
2. **Custom jobs** (drywall, carpentry, honey-do): photos and a description required. AI drafts the quote and texts it to Zach. Zach edits or approves, and the customer gets the quote by text within 2 hours with one-tap approve and a deposit.
3. **Out of scope** (licensed electrical or plumbing, remodels): polite no plus a referral.

The flow runs Google or a call (AI answers), then the Get a Price form, then the menu question. Yes goes to instant price, booked with card on file. No goes to AI drafts the quote from photos, Zach approves, then it's texted with a deposit. Both lanes end at job done and paid by tap to pay, then an automatic review ask the next day.

## The AI layer

- **AI receptionist:** answers every call, quotes menu jobs, books into Jobber, texts the quote link, escalates emergencies to Zach. No voicemail.
- **Photo quote drafting:** Claude reads the photos against the price book and HomeWise times. It drafts a worst-case hourly and a flat price, and flags anything it can't see. Zach always approves.
- **Follow ups:** unanswered quotes get nudged at 2 and 5 days, in Zach's voice.
- **Reviews:** the ask goes out the day after payment, with the town and "handyman" prompted. AI drafts every reply.
- **Rescheduling:** when a job runs long, every affected customer gets new slots by text.
- **Google Business posts:** a weekly before and after made from job photos.
- **Bookkeeping:** QuickBooks AI categorizes from the bank feed and receipt photos.

## Automations (test each with a fake customer before launch)

| When this happens | This runs | Built in |
| --- | --- | --- |
| Quote form submitted | Client and request in Jobber, email and text to Zach, row to lead sheet | Zapier |
| Custom form has photos | Claude drafts quote line items into Jobber as a draft | Zapier |
| Call missed or after hours | AI receptionist answers; a hangup gets a text back with the quote link | Jobber / OpenPhone |
| Quote sent, no answer in 2 days | Follow up text, second at 5 days | Jobber |
| Quote approved | Deposit request over $500, visit booked, confirmation | Jobber |
| Day before visit | Reminder with Zach's photo and arrival window | Jobber |
| Zach taps On My Way | ETA text | Jobber |
| Job marked complete | Invoice with tap to pay | Jobber |
| Invoice unpaid at 3 and 7 days | Polite reminder | Jobber |
| Invoice paid | Review ask next day; sync to QuickBooks | Jobber |
| New Google review | AI drafted reply emailed to Zach | Zapier |
| 6 months after last job | "Anything on the list?" check in | Jobber |
| Monday 7am | Week summary: jobs, open quotes, unpaid, revenue | Zapier |

## Payments

All money runs through Jobber Payments into business checking: card, ACH, Apple Pay, tap to pay. No checks or Venmo. Menu jobs keep a card on file and get charged at completion. Custom jobs over $500 take a 25% deposit. Jobs over $2,000 offer Wisetack. The 3% card fee is passed on, or ACH is free, which is Zach's call.

## Pricing

He charges $100/hr with a 2 hour minimum on custom work, plus flat menu prices. Adjust to the local market once we know the town. Custom bids get a flat price at worst case, with hourly offered as the likely cheaper option. Benchmark against HomeWise.

Placeholder menu (Zach signs off before launch):

| Menu job | Starting price | Notes |
| --- | --- | --- |
| TV mount, up to 65", drywall | $199 | Brick, stone or wire concealment extra |
| Ceiling fan swap, existing box | $189 | Fan supplied by customer |
| Faucet replace | $179 | Customer supplied |
| Toilet replace | $249 | Haul away included |
| Interior door hang | $199 | Prehung |
| Furniture assembly | $100/hr | 1 hour minimum |
| Drywall patch, up to 12" | $229 | Texture and paint included |
| Honey-do list, half day | $425 | 4 hours, materials extra |

## Marketing and reviews

1. **Google Business Profile:** verify it, list every service, set the service area, post 20+ real photos. Day one priority.
2. **First 10 reviews:** friends and family jobs done for real at a discount, then every paid job. Town plus "handyman" in the text.
3. **Local Services Ads:** on once insurance and the background check clear, off when booked 3+ weeks out.
4. **Yelp, Nextdoor, Facebook:** identical name, address and phone. Yelp ads at about $600/mo only when the schedule is thin.
5. **Realtors and property managers:** a one page partner sheet plus a 10% repeat client rate.
6. **Truck magnet:** phone, "Get a price in 60 seconds", and a QR code to the form.

## Brand (placeholder)

Navy plus safety orange, a bold condensed sans for headings, a clean sans for body. The Canva kit covers the logo (wordmark plus monogram), truck magnet, business card, yard sign, invoice header and review card. The voice is friendly, on time, no BS. Tagline idea: "One call. Whatever's broken."

## Launch timeline (8 weeks)

- Weeks 1 to 2, Foundation: LLC, EIN, bank, insurance, license, domain, email, phone.
- Weeks 2 to 4, Build: Jobber, price book, site and quote form, Zapier and AI steps.
- **Gate:** insurance active before any paid job.
- Weeks 4 to 6, Soft launch: 5 fake customer runs, friends and family jobs, first 10 reviews.
- **Gate:** 5 test runs pass before ads go live.
- Weeks 6 to 8, Live and handoff: Google profile live, Local Services Ads, SOP, video, handoff.

## Monthly cost (approximate, verify at signup)

| Tool | Approx $/mo |
| --- | --- |
| Jobber, tier with online booking and automations | $120 to $200 |
| AI receptionist add-on | $50 to $100 |
| Zapier | $20 to $30 |
| Phone line | $15 to $25 |
| QuickBooks Online | $35 |
| Workspace, WP hosting, Canva, password manager, domain | $40 to $60 |
| Card processing | about 3% per charge |

The total is about $250 to $400 a month. Ads are variable spend. One time costs: LLC filing, insurance, license and bond, and magnets.

## Handoff checklist

- [ ] Every account owned by Zach's email, billed to Zach's card
- [ ] Five fake customers run through every lane: menu, custom photo, after hours call, unpaid invoice, review
- [ ] Zach has run 3 real jobs end to end himself
- [ ] One page SOP from request to paid
- [ ] 10 minute screen recording of Jobber on his phone
- [ ] Price book and menu signed off by Zach
- [ ] Wyatt removed from admin roles; vault items revoked

## Open decisions

- [ ] Town or towns covered (blocks domain, GBP name, page titles)
- [ ] State (license, bond, insurance)
- [ ] Top 10 jobs and anything he won't touch
- [ ] Full time or nights and weekends
- [ ] Jobber or FieldPulse
- [ ] Pass on the card fee or eat it
- [ ] Navy and orange OK as placeholders
