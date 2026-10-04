# Upwork Client Acquisition Playbook

Oct 4, 2026 · @Cedric

Upwork is our main client channel. The BDR runs it every day, account managers deliver, and the owner only sets strategy and takes calls with brands doing $1M+ per month.

## Goal and roles

Target for the first 90 days: 4 new retainer clients and 8 paid audits from Upwork.

| Role | Owns | Time on Upwork |
| --- | --- | --- |
| BDR | Profile upkeep, job search, teardowns, proposals, first replies, discovery calls under $1M/mo, pipeline tracker, weekly report | Full time |
| Senior AM | Discovery calls for $100k to $1M/mo brands, scoping, advisory delivery | 3 to 5 hrs/week |
| AM | Onboarding and delivery once a contract starts, review requests | As clients land |
| Owner | Pricing, offers, monthly 30 min strategy review, calls with $1M+/mo brands only | About 2 hrs/month |

No weekly meetings. The BDR sends a written weekly report (see KPIs) and the owner reads it async.

## Agency profile setup (week 1)

We move from a single freelancer profile to an Agency profile so the BDR can bid and the team can deliver under one brand.

- [ ] Create the Agency profile from the owner's freelancer account (Settings > Create agency). Owner = agency owner.
- [ ] Invite the BDR as Business Manager so they can send proposals, message clients and accept offers. Invite AMs as Agency Members.
- [ ] Set the owner's freelancer profile to "agency only" so earnings and Job Success Score build on the agency.
- [ ] Agency title: "Amazon Growth Agency for 7 and 8 Figure Brands | PPC, P&L, Launches".
- [ ] Overview (first 2 lines show in search): who we help, the result, proof. Example: "We grow profitable Amazon brands. Our operators manage PPC, pricing and launches with the full P&L in view, not ad metrics alone."
- [ ] Five specialized profiles on the BDR and senior AM accounts: Full Account Management, PPC Management, Listings and Creative, Launches and Audits, Fractional Amazon Operator.
- [ ] Portfolio: 6 case studies, each with brand category, starting point, actions, result in numbers (revenue, TACoS, margin), and a screenshot with client details hidden.
- [ ] Skills: Amazon Seller Central, Amazon PPC, Amazon FBA, Amazon Listing Optimization, Amazon Brand Registry, Ecommerce Strategy, Inventory Management.
- [ ] Add a 60 to 90 second intro video from the owner, recorded once and reused.
- [ ] Buy Freelancer Plus (or Agency Plus) for more Connects and visibility into competitor bids.

## Offers and Project Catalog

Every offer starts with a small paid entry project that leads into a retainer. Prices below are placeholders for the owner to approve.

| Offer | Type | Starting price (USD) | What the client gets | Next step |
| --- | --- | --- | --- | --- |
| Account Audit | Catalog, fixed | 500 / 900 / 1,500 | P&L, PPC, listing and inventory review with a 30 day action plan | Full Account Management |
| PPC Audit | Catalog, fixed | 350 / 600 / 1,000 | Wasted spend, structure, bids, TACoS by SKU | PPC Management |
| Listing Optimization | Catalog, fixed | 300 / 600 / 1,200 per ASIN | Keyword research, title, bullets, backend, image brief | Creative retainer |
| Launch Plan | Catalog, fixed | 800 / 1,500 / 2,500 | Niche demand, keyword targets, unit plan, PPC launch structure | Launch management |
| Full Account Management | Retainer | 2,500 to 6,000/mo + optional % of growth | Daily PPC, listings, inventory, reporting |  |
| PPC Management | Retainer | 1,500 to 4,000/mo or % of spend | Daily PPC and weekly reporting |  |
| Fractional Amazon Operator | Retainer | 2,000 to 5,000/mo | Monthly strategy review, written action plan, async Q&A for brands with in-house teams |  |

Fractional Amazon Operator is our answer to jobs like "review the business and give high level direction". The client's team keeps executing; we tell them what to do and why, backed by data.

## Daily job hunting

The BDR sends 8 to 12 strong proposals a day and answers every invite within 1 hour during working hours. Fewer, better proposals beat volume.

**Saved searches (check at 9:00, 13:00, 17:00 client time zone US Eastern):**

- "Amazon PPC", "Amazon advertising", "sponsored products"
- "Amazon account manager", "Amazon FBA manager", "Seller Central"
- "Amazon consultant", "Amazon strategy", "Amazon operator", "fractional"
- "Amazon listing", "A+ content", "Amazon SEO"
- "Amazon launch", "Amazon audit"

**Apply only when the job passes these filters:**

| Check | Apply | Skip |
| --- | --- | --- |
| Payment | Verified | Unverified |
| Client spend | $1k+ spent, or new client with clear revenue numbers in the post | $0 spent and vague post |
| Hire rate | 40%+ | Under 20% with many posts |
| Budget | $25+/hr or $500+ fixed | Under that |
| Brand size | Mentions revenue, ad spend or team | "Starting my first product" |
| Proposals so far | Under 20, or any job under 1 hour old | 50+ and over 2 days old |

**Red flags, skip:** asks for free work, wants account login before a contract, "guaranteed results", wholesale or arbitrage only, review manipulation.

**Connects:** budget about 600 per month. Boost only on jobs that score A in the tracker (verified, $10k+ spent, brand doing $50k+/mo). Max boost: 2x the base cost.

## Teardown and proposal system

Every proposal over $1,000 or any retainer job opens with 3 facts about the client's own listings. That is what makes us different from the 40 generic bids.

**Pre-proposal teardown (20 minutes, BDR, public data only):**

1. Find the brand: from the post, the client's past jobs, or by searching the product type on Amazon.
2. Pull the storefront and ASINs with the Scrape Creators `amazon_shop` tool in Claude.
3. Run the `rank-readiness` skill on the hero ASIN and its main keyword. It scores indexing, conversion, price and relevance against page 1.
4. Note 3 specific findings, e.g. "not indexed for 'bamboo cutting board set'", "rating 4.2 vs page 1 average 4.6", "main image shows 1 of 3 boards in the set".
5. Optional for $1M+/yr brands: run the `ads-spy` skill on 2 competitors to show what ads are working in their niche.

**Proposal structure (under 180 words):**

1. **Hook (2 lines):** one finding from their listing plus what it costs them.
2. **Fit:** one line on a similar brand we helped, with a number.
3. **Plan:** 3 bullets on what we would do in the first 30 days.
4. **Proof:** link one matching portfolio case study.
5. **Call to action:** "I recorded a 3 minute video walking through your listing. Want me to send it, or should we jump on a 15 minute call?"

**Loom script (3 minutes, BDR records):** screen share the listing, show the 3 findings, show one quick win, end with the call ask. No pitch deck.

**Templates:** keep one base template per offer in the shared drive. Always rewrite the hook. Never send a template untouched.

**Screening question answers:** keep a bank for the common ones (experience with brands like ours, how you report, how you price, tools you use). Answer in 2 to 3 sentences with a number.

## Worked example: home and kitchen brand, $1M/yr

The job: an FBA home and kitchen brand at about $1M/yr ($83k/mo) with $10k to $12k/mo PPC spend (12% to 14% of revenue). It already has teams for PPC, account management and supply chain, and wants an operator for high level direction on PPC profit, SKU economics and pricing, launches, inventory and sourcing, and growth.

Offer to pitch: **Fractional Amazon Operator**. Call owner: **senior AM** ($83k/mo is under the $1M/mo bar).

Proposal (fill the brackets from the teardown):

```markdown
Hi [Name],

I looked at [hero product] before writing this. It ranks on page 1 for [keyword A] but is not indexed for [keyword B], which carries roughly [x]% of the niche's searches. With $10k to $12k a month in ads, that is likely where part of your spend is leaking.

We advise 7 figure physical product brands that already have execution teams. Last year we helped [similar brand] cut TACoS from [x]% to [y]% while growing revenue [z]%, by fixing SKU level pricing and cutting ads on low margin variants.

In the first 30 days I would:
- Build a SKU level P&L (landed cost, fees, ad spend) and flag every SKU losing money after ads
- Review PPC for redundant spend and campaigns bidding on terms you already win organically
- Check inventory cover and reorder points against your sales trend, so launches don't starve the core line

Your teams keep running day to day. You get one written action plan per month, a 60 minute review call, and async answers in between.

Case study: [link]

I recorded a 3 minute walkthrough of your listing. Want me to send it, or should we talk for 15 minutes this week?

[BDR name], on behalf of [Agency]
```

Why it works: it proves we looked at their account, speaks P&L (not only ads), respects their existing teams, and asks for a small next step.

## Qualification and call routing

The BDR asks for monthly revenue before booking any call. Monthly revenue decides who takes the call.

**Ask in the first reply:**

1. Roughly what are you doing per month on Amazon right now?
2. What is your monthly ad spend?
3. How many active ASINs, and which marketplaces?
4. Who handles PPC, listings and inventory today?
5. What would make the next 6 months a win for you?

| Monthly revenue | Who takes the call | Offer to lead with |
| --- | --- | --- |
| Under $30k | BDR (or decline if budget is under $1,000/mo) | Catalog audit or listing project |
| $30k to $100k | BDR, AM joins for scoping | PPC Management or Account Management |
| $100k to $1M | Senior AM | Account Management or Fractional Operator |
| $1M+ | Owner, BDR prepares the brief | Custom scope |

**Discovery call (30 minutes):** 5 min their goals, 10 min walk the teardown, 10 min their numbers (margin, TACoS, stock), 5 min proposed offer and next step. Send a written recap within 2 hours.

**Owner handoff for $1M+/mo brands:** the BDR sends the owner a one page brief 24 hours before the call: brand, revenue, ad spend, team, the 3 teardown findings, what they asked for, proposed price. The owner only shows up and closes.

## Closing, onboarding and the advisory toolkit

We close on a paid first step, then use the same toolkit for every client so any AM can give senior level advice.

**Closing:**

- Audits: fixed price contract, one milestone, delivered in 7 days.
- Retainers: monthly fixed price milestones (cleaner for JSS than hourly), 3 month minimum.
- At audit handoff, the AM presents the action plan and offers the retainer that carries it out. Target: 50% of audits convert.

**Onboarding checklist (AM, first 5 days):**

- [ ] Seller Central user permissions (never the owner login)
- [ ] Advertising console access
- [ ] Connect Scale Insights and Titan for the account
- [ ] COGS and landed cost per SKU from the client
- [ ] Kickoff call: goals, team contacts, how they want reports
- [ ] BDR posts the handoff note in ClickUp and steps out

**Advisory toolkit: which tool answers which client question**

| Client question | Tool | Output for the monthly report |
| --- | --- | --- |
| Is our PPC profitable? | Scale Insights `get_executive_brief`, `get_redundant_spend`, `get_ppc_exact_coverage` | Wasted spend in $, campaigns to cut or move |
| Which SKUs lose money? | Scale Insights `get_underwater_products`; Titan `get_product_performance_summary` | SKU P&L table, price or ad changes per SKU |
| Where is free organic upside? | Scale Insights `get_organic_upside`, `get_sqp_intelligence` | Top searches to rank for and their profit value |
| Should we launch this product? | `niche-demand` and `landscape-sheets` skills | Go or no go with units needed to rank |
| Is it ready for a ranking push? | `rank-readiness` skill | Red, yellow, green scorecard |
| Are we going to stock out? | Scale Insights `get_inventory_data`; Titan AWD tools | Weeks of cover, reorder dates |
| Can we source cheaper? | `supplier-intelligence` skill | Supplier shortlist and RFQ emails |
| What ads work in our niche? | `ads-spy` skill | Creative brief from competitor winners |

Any bid or budget change the tools propose is reviewed by the AM and approved by the client's team before it goes live. We advise; their team executes unless we hold a management retainer.

## Reviews, KPIs and escalation

A high Job Success Score is the asset that makes every future proposal cheaper to win, so we protect it.

**Reviews and JSS:**

- Ask for feedback right after a visible win, never cold at contract end.
- Close finished fixed price contracts within 7 days of delivery; never leave them open.
- Unhappy client: AM calls within 24 hours and offers a fix before any refund talk. Disputes go to the owner.
- Keep 2 to 3 small fixed price projects running so the score keeps updating.

**Weekly report (BDR to owner, written, every Friday):**

| KPI | Target |
| --- | --- |
| Proposals sent | 50+ |
| Proposal view rate | 40%+ |
| Reply rate | 15%+ |
| Discovery calls held | 4+ |
| Contracts won | 1+ |
| Win rate (won / calls) | 25%+ |
| Connects spent | Under 150 |
| New MRR added | Running total vs 90 day goal |
| Audit to retainer conversion | 50% |

**Monthly 30 minute strategy review (owner):** which offers win, which job types to drop, pricing changes, case studies to add.

**Escalate to the owner only for:**

- Brands doing $1M+ per month
- Deals above $8,000/mo or 12 month terms
- Discounts over 15% or custom pricing
- Disputes, refunds or JSS risks
- Anything that touches Amazon terms of service
