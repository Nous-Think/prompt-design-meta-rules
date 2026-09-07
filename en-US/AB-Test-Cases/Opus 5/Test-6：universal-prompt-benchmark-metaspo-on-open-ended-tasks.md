# Universal Prompt Benchmark — MetaSPO on Open-Ended Tasks

> All content below — the test design, responses, and analysis — was originally produced in Chinese and has been translated into English for accessibility.

> Model: Opus 5

# Test Purpose

This test asks: **what happens when a universal prompt optimized on scorable tasks is applied to professional tasks with no standard answer?**

MetaSPO (Meta-learned Self-improving Prompt Optimizer) is a method that uses automated search to optimize system prompts. It iterates over benchmark datasets with known correct answers, searching for the prompt that maximizes model scores. What is used here is its "universal" output — not tailored to any domain, claimed to be effective across tasks.

Test method: this MetaSPO prompt was set as the system prompt, and the same model (Opus 5) was given two previously used tasks (resume rewrite and operations diagnosis). Both results can be compared against other tests' A (baseline) and B (Meta Rules), but the insights in this document rely only on what is contained in this file — the prompt itself, the task inputs, and the two responses.

# MetaSPO Base Prompt

You are a general-purpose advanced assistant. Critically analyze the information provided, considering multiple perspectives, implications, logical relationships, and connections between concepts.  
Adapt your reasoning to different kinds of queries, including factual questions, sentiment-related tasks, and logical deduction. Understand the nuances of the query and choose reasoning appropriate to it.  
When emotion or sentiment matters, recognize both positive and negative elements and form an appropriate overall assessment.  
Present answers clearly and coherently so that reasoning and conclusions are easy to understand. Prioritize clarity and precision.  
Adapt your analysis to the context and details of each inquiry, paying attention to nuances and subtleties that could affect the result. The overall goal is to produce accurate, relevant, and thoughtful responses across diverse tasks.

# Test Prompt 1

I'm getting ready to switch jobs and want to rework my resume. Below is my current work experience section along with some real numbers and projects. Help me turn it into a more compelling version. I'm in digital marketing and mainly targeting brand-side marketing manager roles.

Current version: ABC Digital Marketing | Marketing Planner → Senior Planner (2020–2025)

* Managed client social media accounts
* Planned and executed digital ad campaigns
* Wrote marketing proposals
* Managed two juniors
* Assisted with client brand repositioning project
* Participated as in-house training instructor

Real numbers and achievements (but I don't know how to work them in):

* Ran social media for 4–6 clients simultaneously (FB+IG), spanning beauty brand "LURE," chain gym "動次," organic food brand "綠田," and 3C accessories brand "MATZ"
* When I took over "LURE"'s IG, it had 12K followers; two years later it was at 87K — no bought followers, mainly through Reels and KOL collaborations
* FB/Google Ads monthly budget ~NT$1.5–2.5M (all clients combined), ROAS averaged above 3.5; for "動次" membership ads, I optimized CPA from NT$680 down to NT$320
* Led two juniors — one was a fresh graduate whom I trained to the point of handling clients independently
* In 2023, "綠田" was transitioning from traditional retail to e-commerce; I wrote the entire digital transformation marketing strategy, including website traffic acquisition, social content repositioning, and ad account restructuring — within three months, monthly website revenue went from NT$150K to NT$850K
* The brand repositioning was for "MATZ" — shifting from budget 3C accessories to a design-forward brand identity. I led the new visual identity, social media tone adjustment, and collaborations with five design-focused KOLs. Brand search volume grew 240% in three months
* Internal training covered Meta ad operations and GA4 basics for new hires, roughly four cohorts totaling ~20 people
* Tools: Meta Business Suite, Google Ads, GA4, Looker Studio, Canva, Notion

# MetaSPO Response 1

<details>
<summary>Expand full response</summary>

Let me explain my revision rationale before giving you the rewrite.

Your current version reads like a job description — it lists what you did. But for a brand-side manager role, the reader is looking for evidence of ownership over business outcomes. Agency-background candidates typically face three concerns: they can only execute, not set strategy; they lack ownership of business numbers; and they default to project-based thinking rather than long-term brand stewardship. Your actual track record refutes all three, but the original version buries every bit of it — especially "assisted with client brand repositioning," when you actually led it.

So the rewrite does three things: **verb upgrades** (assisted/participated → led/rebuilt), **case-based framing** (each bullet is one project plus one result, not a list of duties), and **reordering** (business-impact items first, community management later).

## Revised Version

**ABC Digital Marketing** | Marketing Planner → Senior Planner (2020–2025)

Led full-scope digital marketing for 4–6 brand clients across four consumer verticals — beauty, chain fitness, organic food, and 3C accessories — managing monthly ad budgets of NT$1.5–2.5M with overall ROAS steadily maintained above 3.5.

**| Brand Digital Transformation: Organic Food "綠田" (2023)**  
Led the e-commerce transformation strategy for a traditional-retail brand: rebuilt website traffic acquisition funnels, repositioned social content pillars, and restructured the ad account architecture. Monthly website revenue grew from NT$150K to NT$850K within three months (+467%).

**| Brand Repositioning: 3C Accessories "MATZ"**  
Led the repositioning from price-driven to design-driven brand identity, covering new visual identity development, social media tone overhaul, and a collaboration program with five design-focused KOLs. Brand search volume grew 240% in three months.

**| Long-Term Community Growth: Beauty "LURE"**  
Built a growth model centered on Reels content strategy and KOL collaborations after taking over the IG account. Grew followers from 12K to 87K over two years (+625%) with no follower growth ads deployed throughout.

**| Performance Optimization: Chain Gym "動次"**  
Restructured audience segmentation and creative testing framework for membership conversion ads, reducing CPA from NT$680 to NT$320 (−53%).

**| Team Leadership & Talent Development**  
Led two planners on day-to-day project execution; developed one from a fresh graduate to independently managing client accounts. Served as in-house instructor for Meta ad operations and GA4 workshops across four cohorts (~20 trainees).

**Tools** | Meta Business Suite, Google Ads, GA4, Looker Studio, Notion

## Three Numbers You'll Definitely Be Grilled On

These don't go in the resume, but you need answers ready — otherwise strong numbers become liabilities:

**綠田's NT$150K → NT$850K**: They will ask, "How much did the ad budget grow at the same time?" If revenue grew 5.6× while the budget only grew 1.5×, put that sentence directly in the resume — it's a completely different caliber of achievement. If the budget also grew 5×, prepare to defend with gross margin or ROAS trends.

**MATZ's 240%**: What's the base? Going from 100 to 340 and going from 5,000 to 17,000 carry very different weight. Have an absolute number ready, or pair it with a supporting metric (organic traffic, inbound inquiries).

**LURE's 87K followers**: A brand-side marketing manager will regard follower count as a vanity metric. If you have engagement rate, social-driven revenue, or average Reels reach, those numbers are worth more than the follower figure.

## Two Areas to Add (Currently Blank)

**Cross-functional collaboration.** Half a brand-side manager's job is coordinating with sales, channel, product, and customer service teams. Your work on 綠田 (retail-to-e-commerce) and 動次 (chain locations) almost certainly involved coordination with store operations or channel teams, yet the resume says nothing about it. Think of a concrete instance of "coordinated with client's X department" and add one line.

**Budget planning vs. budget execution.** Right now the resume says you "managed NT$1.5–2.5M" — that's executor language. If you were involved in annual budget proposals, media mix allocation, or discussions with clients about how to split the budget, change it to "planned and allocated." That's the keyword for manager-level roles.

One more thing: "Senior Planner → Marketing Manager" is a level jump. Your people-management experience (2 reports + developed one to independence) is buried at the bottom of your own ordering, but it's the recruiter's most direct evidence of whether you can step into a management role. I kept it last because of resume convention, but in interviews, bring it up proactively — don't wait to be asked.

</details>

# Test Prompt 2

# Operations Diagnosis and Strategic Recommendations
## Role
Ground the analysis in expertise across retail operations management, consumer behavior analysis, and supply chain strategy — but don't limit it to these if broader knowledge improves response quality.
## Background
We are a mid-sized chain bakery brand with 8 years of history, operating 12 stores in northern metropolitan areas, with annual revenue of approximately NT$280M and roughly 180 employees.  
**Recent one-year operating data:**

- Total revenue YoY +6%, but excluding 2 newly opened stores, same-store revenue YoY −3%
- Customer traffic YoY −8%, but average transaction value YoY +12% (from NT$185 to NT$207)
- Core product line (European bread series) revenue share dropped from 45% to 38%; pastries and cakes rose from 25% to 33%
- Delivery platform revenue share rose from 12% to 22%, but delivery order gross margin is only 18% (in-store gross margin is 52%)
- Raw material costs YoY +14% (mainly imported flour and butter)
- Labor costs YoY +11% (minimum wage increase + 40% baker turnover rate)
- ~60K members, but monthly active members (at least one purchase) only 12K

**Known issues:**

- Three legacy store leases expire within 8 months; landlords have signaled 15–25% rent increases
- Two new stores have not yet reached breakeven (6 months in, running ~NT$150K/month loss per store)
- Bakers are hard to recruit and turnover is high; 2 stores have been forced to shorten operating hours due to staffing shortages
## Task
Diagnose the structural problems behind these data points and provide operational adjustment recommendations for the next 12 months.
## Quality Requirements
- Distinguish "symptoms" from "root causes" — the data presents symptoms; diagnosis must point to the structural drivers behind them
- Recommendations must account for resource realities (cash flow pressure, staffing shortages) — strategies that are theoretically correct but operationally infeasible have no value
- The lease-expiration decisions must be specifically addressed in the recommendations — these are time-pressured hard decision points
- If any data signals deserve deeper investigation but lack sufficient information, state what additional data is needed to confirm the judgment
## Output Structure
Include: diagnostic framework (problem structure and causal relationships), prioritized action sequence (with time dimension), resource reallocation recommendations, and hypotheses requiring further validation. If there are other critical dimensions not mentioned above, proactively address them.

# MetaSPO Response 2

<details>
<summary>Expand full response</summary>

## I. Data Reconciliation First: The Data Contains Contradictions, and the Contradictions Are the First Clue

Before making any diagnosis, let me check whether these numbers are internally consistent.

**Contradiction one: traffic and ticket size don't add up to revenue.** Customer traffic −8% and average transaction value +12% should yield roughly +3% (0.92 × 1.12). But same-store revenue is −3% while total revenue is +6%. The three figures are pairwise incompatible. Three possible explanations: traffic/ticket figures are chain-wide while the −3% is same-store only; or delivery orders are counted as "one customer visit" (one order, multiple items) inflating the ticket-size denominator; or the new stores are cannibalizing nearby legacy stores. **These three explanations point to entirely different root causes and must be clarified first** (see Section V).

**Contradiction two: the +12% in average transaction value is probably not good news.** Break it apart: delivery share went from 12% to 22%, and delivery orders naturally carry larger baskets due to minimum-order thresholds and delivery-fee amortization. Simultaneously, pastries and cakes (higher unit price, often purchased whole) rose from 25% to 33%. These two compositional shifts alone are sufficient to fully explain the 12% ticket growth. In other words, **the rise in transaction value and the decline in traffic are not "one good, one bad" — they are two surfaces of the same structural shift.** Until same-channel, same-category ticket sizes are confirmed to have also risen, this cannot be treated as evidence of pricing power or upselling success.

**Recalculating absolute values (back-solving from this year's NT$280M to last year's ~NT$264M):**

| Item | Last Year | This Year | Absolute Change |
|---|---|---|---|
| European bread series | NT$119M | NT$106M | **−10.5%** |
| Pastries and cakes | NT$66M | NT$92M | +40% |
| Delivery channel | NT$32M | NT$62M | +94% |
| **In-store (non-delivery)** | **NT$232M** | **NT$218M** | **−6.1%** |

**Gross margin recalculation:**  
Last year's blended gross margin ≈ 0.88 × 52% + 0.12 × 18% = **47.9%**, gross profit ~NT$127M.  
This year ≈ 0.78 × 52% + 0.22 × 18% = **44.5%**, gross profit ~NT$125M.

**Revenue +6%, yet gross profit approximately −1.5%.** Meanwhile, labor is +11%, raw materials +14%, three stores face rent hikes, and the two new stores are burning ~NT$3.6M annually. Using mid-sized bakery cost-structure benchmarks (labor ~25%, rent ~10–12%, other operations and overhead ~8–10%), this company is **most likely already at or below the operating breakeven line.** This estimate must be verified against actual financials, but it sets the boundary for everything that follows: **any initiative requiring significant capital expenditure, or one that won't generate cash until after month twelve, does not qualify for discussion right now.**

## II. Diagnostic Framework: One Primary Causal Chain, Two Accelerator Chains

### Primary chain: Skilled-labor attrition → Quality instability → High-frequency customer loss → Passive category drift → Margin erosion

A 40% baker turnover rate is not an HR issue — it sits upstream of the P&L. The reasoning:

1. European bread is the most **technically dependent** item across the entire product line: sourdough management, fermentation judgment, shaping by hand, oven-temperature intuition — all tacit knowledge that cannot be documented. When bakers rotate, batch-to-batch quality variance appears immediately.
2. European bread is simultaneously the **high-frequency repurchase** category — a "buy three times a week" habitual product. Pastries and cakes are occasion-driven — birthdays, gifts, holidays.
3. Therefore, unstable bread quality → habitual customers leave → **traffic (frequency) declines.** Those who remain and those newly acquired are occasion-driven → transaction value rises, cake share rises.
4. More critically: two stores have already shortened operating hours due to staffing. **This means the "European bread decline" may not be a demand-side phenomenon at all, but a supply-side self-fulfilling prophecy** — if bread sells out by 3 PM, or the evening shift produces nothing, what the POS records is "bread isn't selling." This is a fork point that must be immediately verified using stockout rates and sellout timestamps.
5. The category structure thus shifts from high-frequency/low-ticket to low-frequency/high-ticket. But **the occasion-driven market has no moat**: competitors include chain cake specialists, convenience-store desserts, and online-delivery cakes — all competing on promotions and seasonal campaigns. The brand's eight-year asset is in European bread. That asset is leaking, and the water is flowing into a far more crowded pool.

**Diagnostic conclusion: this is not a "declining traffic" problem — it is a "the brand's high-frequency anchor is being lost to production capacity failure" problem.**

### Accelerator chain A: The delivery channel has been repriced by platforms, and the company has not responded at all

The 18% delivery gross margin can be reverse-engineered: in-store gross margin of 52% implies COGS of ~48%. If delivery records revenue at gross and deducts platform commission as a cost, then 52% − commission = 18%, yielding a **commission rate of ~34%** — squarely within the typical fee range for Taiwan's platforms.

The fact that this equation holds is itself a conclusion: **delivery prices are completely identical to in-store prices; the company has not passed on a single dollar.** A ten-percentage-point channel shift (~NT$28M in revenue moving from 52% to 18% margin) erodes approximately **NT$9.5M in gross profit** on its own — enough to consume most of the net profit.

And with customer traffic simultaneously declining, these delivery sales are **most likely not incremental but channel migration by existing customers** — the same customer, one-third of the margin. This is the worst kind of "growth."

### Accelerator chain B: Dormant member base left idle, eliminating the only owned tool to counter traffic decline

60K members, 12K monthly active — a 20% activity rate. Bakery is one of the few retail categories with "weekly repurchase" potential; this rate is low. The 48K dormant members represent **demand that can be reached without paying platform commissions, without adding floor space, and without adding headcount** — yet is not being used. When traffic declines, this is the only lever that can push back immediately and is cash-positive.

### How the three chains interlock

Staffing shortages → shortened hours and quality instability → in-store experience deteriorates → customers shift to delivery (the platform's convenience masks the store's unreliability) → delivery share rises → margins decline → cash pressure increases → even less funding for baker retention → staffing shortages worsen. **This is a positive-feedback downward spiral, not three independent problems.** The action sequence below therefore prioritizes interventions that can sever multiple loops simultaneously.

## III. Prioritized Action Sequence (12 Months)

### Wave 1: M0–M3 | Stanch Bleeding and Build Tables — Zero Capex, Cash-Positive

**A1. Delivery channel pricing separation (highest single-item return, lowest execution cost)**  
First, check whether the platform contract contains a price-parity clause — the only legal prerequisite. If not (most contracts allow it), raise platform prices by 15–20%.

| Price markup | Delivery gross margin |
|---|---|
| 0% (current) | 18% |
| +15% | 24.3% |
| +20% | 26.0% |

Even assuming 15% order-volume loss, delivery gross profit can still increase from ~NT$11.1M to ~NT$16M. **Order-volume loss here is not purely a cost** — low-margin orders that migrate back to in-store yield a double benefit.

**A2. Aggressive delivery SKU rationalization**  
The delivery menu should be a "subset redesigned for transport" — selected on **transport durability + low COGS ratio**, not the in-store bestseller list. A hard-crust European bread sitting in a cardboard box for 25 minutes delivers a damaged brand experience; these items should be delisted outright. This also reduces pick-and-pack disruption at the store level.

**A3. Build store-level four-wall P&L statements (prerequisite for everything else)**  
Calculate per store: revenue − food cost − store-level labor − rent − utilities. **Do not allocate headquarters overhead.** Without this table, the lease decisions eight months out can only be made on intuition. This must be completed by end of M1, not "when there's time."

**A4. Baker retention triage (before any recruiting)**  
Stop the bleeding before hiring. Identify the top 15–20 bakers with critical technical skills and hold one-on-one retention conversations. Restructure compensation as "base + skill-tier premium + staged retention bonus" (staging is the point — a lump sum does not change the stay-or-leave decision).

Cost comparison: with ~50 bakers and 40% turnover, annual departures are ~20. Fully loaded replacement cost per baker (recruiting, training, capacity loss, waste, customer attrition from quality drops) is conservatively NT$150–250K, totaling **NT$3–5M annually** — the same order of magnitude as the two new stores' annual losses, yet never managed as an explicit line item.

**A5. Dormant member reactivation (cash-positive traffic tool)**  
Segment 48K dormant members by "time since last purchase" and "primary category purchased." Key design principle: **incentives must be tied to high-frequency categories like European bread rather than blanket discounts** — the goal is rebuilding habits, not buying a single transaction. Reactivating 5–10% would yield ~NT$6–12M in incremental annual revenue, with post-incentive net gross-profit contribution of ~NT$2.2–4.4M.

### Wave 2: M3–M6 | Structural Decisions with Hard Deadlines

**B1. Lease decisions (decision deadline = M4, non-negotiable)**  
Eight months to expiry means the effective decision window is only three to four months: negotiations take 6–8 weeks; if relocating, finding and fitting out a new site takes 4–6 months; if closing, orderly wind-down requires 60–90 days.

Apply a three-tier filter to each store using the four-wall P&L:

- **Rent-to-revenue ratio**: the healthy range for bakeries is ~8–12%. If a store is already at 12% and faces a 25% increase to 15%, the store is structurally unviable — unless it has strategic value described below.
- **Strategic value**: Is it a brand flagship? Does it anchor central production volume? **Is it a delivery coverage node** (closing it may forfeit an entire delivery zone's revenue)?
- **Cannibalization**: Distance from the new stores. If a new store is in the same trade area, the actual revenue loss from closing the old one is far below its book figure.

Negotiation levers and alternatives (in priority order):

1. **Convert to percentage rent** — a base rent below the current level + 8–10% of revenue above a threshold. This shifts risk to the landlord and is rational for both sides in a declining-revenue environment; landlords facing vacancy risk have higher acceptance rates.
2. **Trade a longer lease (5 years) for a smaller increase**, with a capped escalation schedule.
3. **Downsize and reformat** — convert the store to a smaller footprint serving pickup and delivery fulfillment, trading revenue per unit area for lower rent. This also addresses the staffing problem (smaller stores need fewer people).
4. **Relocate within the trade area** — an eight-year brand with 12 stores is a credible anchor tenant; this carries real negotiating power in small-to-mid-sized trade areas.
5. **Close** — if the four-wall contribution is negative and there is no strategic value, closing is a cash- and staffing-release action, not a failure. **The baker freed up by closing one store may be exactly what is needed to restore full hours at the two stores currently operating on shortened schedules.**

**B2. Production architecture: satellite-store model (low-capex version)**  
A central kitchen is the structural solution to staffing shortages, but a brand-new facility is a capital expenditure the current cash position may not support. Low-cost alternative: designate 2–3 stores with surplus capacity and space as "hub stores" that centrally produce dough, handle fermentation, and prepare semi-finished goods for 3–4 surrounding "satellite stores," which handle only final baking and service.

Effect: skilled-labor requirement drops from "every store needs a baker" to "one baker per three to four stores," and quality consistency improves dramatically. This is the intervention that simultaneously addresses A4 (staffing) and the primary chain (quality).

**Prerequisite check: What are the current central production capacity and utilization rates?** If a central kitchen already exists and utilization is below 70%, this is near-zero cost and should be moved up to Wave 1.

**B3. Category strategy: defend European bread, but only the core**  
A deliberate strategic choice must be made rather than letting the category structure continue to drift passively. My judgment is **defend** — European bread drives purchase frequency, differentiates the brand, and represents eight years of accumulated assets. But defend through **contraction, not expansion**:

Cut the long-tail European bread SKUs (most eight-year brands accumulate 40+ items, with the bottom half contributing less than 15% of revenue); concentrate resources on 8–12 hero items and push them to peak consistency. The cascading effects of fewer SKUs: lower technical dependency (new bakers ramp up faster), lower waste, simplified procurement, and improved output uniformity. **This is the most underestimated move in this case — it simultaneously improves quality, staffing, and cash, and its cost is negative.**

Do not suppress pastries and cakes, but examine how much of their growth comes from seasonal peaks (Mid-Autumn Festival, Christmas, Mother's Day) — seasonal revenue is not base demand and cannot serve as a strategic foundation.

**B4. Set a stop-loss line for the new stores**  
Six months without breakeven is still within normal range for bakeries (typical: 6–12 months). What matters is not the absolute loss but the **trajectory**: is the monthly loss narrowing month over month? If the monthly loss has been flat at NT$150K for three consecutive months, the issue is a structural error in site selection or store format, not a ramp-up period.

Pre-commit now: **M9 checkpoint** — if the loss-narrowing trajectory has not reached the projected path for "breakeven by M12," an automatic decision triggers (reformat or exit), with no further month-by-month deferrals. The value of pre-commitment is avoiding sunk-cost capture of judgment.

### Wave 3: M6–M12 | Rebuild Frequency, Reduce Platform Dependency

**C1. Bread subscription / pre-order program**  
Weekly subscription, in-store pickup. This single move solves four problems simultaneously: locks in repurchase frequency, collects cash upfront, dramatically improves production forecasting (directly reducing waste), and completely bypasses platform commissions. This is a structural countermeasure to channel-power shift, not just a marketing campaign.

**C2. Owned ordering channel (LINE Official Account + scheduled pickup)**  
The goal is to migrate "pickup-type" delivery customers off the platform. These customers already live near the store; they chose the platform only for interface convenience. Even migrating just 20% — on NT$62M in delivery revenue, that is ~NT$12.4M shifting from 18% to 52% margin, yielding ~NT$4.2M in incremental annual gross profit.

**C3. B2B wholesale (launch only after production stabilizes)**  
Coffee shops, offices, hotel supply. Margins are lower than retail, but orders are stable, predictable, and drive high capacity utilization — and **regular production schedules** have real impact on baker retention (steady production rhythms are more retentive than the peak-and-trough volatility of retail). This must be sequenced after B2; doing B2B with unstable capacity is self-destructive.

## IV. Resource Reallocation

**Stop investing in:**

- New store development (freeze for at least 12 months)
- Chain-wide blanket discount promotions (with margins already compressed, discounts are selling products that already don't make money)
- Raw material inventory, training, and shelf space for long-tail European bread SKUs
- Platform-subsidized revenue growth (this is paying commissions to buy vanity topline numbers)

**Redirect to:**

- **Baker retention and skills ladder**: NT$3–5M annually (this is not new budget — it is converting what is currently being spent unconsciously as "recruiting fees + training costs + waste + quality-driven customer loss" into deliberate, front-loaded investment)
- **Hub/satellite store conversion**: minor capex for equipment and workflow adjustments, ~low-six-figure range per hub cluster
- **Member engagement and owned ordering channel**: low cost, high return, but requires one dedicated headcount
- **Headcount freed by store closures**: prioritize redeployment to the two stores operating on shortened hours — **these two stores' reduced hours are an actively bleeding wound, and they are also a possible phantom source of the "European bread decline" in the data**

**Cash-flow sequencing logic:** A1 (platform pricing) and A5 (member reactivation) generate cash in M1–M3 → this cash funds A4 (baker retention) and B2 (satellite conversion) → B2 reduces staffing dependency, which gives B1's closure option deployment flexibility → Wave 3's subscription and owned-channel programs take over as the growth engine from M6 onward. **The sequence cannot be skipped, because each wave's funding source is the previous wave.**

## V. Hypotheses Requiring Further Validation

Ranked by "if the answer differs, the recommendation changes materially":

**Tier 1: Would change the diagnosis itself**

1. **Is the European bread decline demand-side or supply-side?** Pull stockout rates and sellout-time distributions by store. If most stores sell out of bread by afternoon, or the stores with shortened hours show markedly lower bread output than the same period last year, then "category decline" is a self-fulfilling capacity problem, and B3's strategic direction and resource allocation change completely. **This is the single highest-priority validation.**

2. **What is the composition of the traffic decline — fewer people, or the same people coming less often?** Use member data to decompose "traffic" into "unique visitors" and "visit frequency." If frequency is falling, the primary-chain diagnosis holds (habit disruption); if new-customer acquisition has dried up, the problem tilts toward trade-area competition or brand aging, requiring a different prescription.

3. **The true composition of the +12% in average transaction value.** Requires same-channel, same-category comparable ticket sizes. Specifically: compare in-store-only and European-bread-only tickets. If those are flat or declining, the 12% is entirely a compositional illusion, and the company is actually losing pricing power.

4. **Data definitions: are traffic/ticket figures same-store or chain-wide? Is a delivery order counted as one customer visit?** This determines how the Section I contradictions resolve. If delivery orders count as one visit, the true in-store traffic decline is **far greater than 8%**, and the situation is worse than it appears.

**Tier 2: Would change execution approach**

5. **Are delivery customers new or migrated?** Cross-reference by phone number or member ID across channels. If 70%+ are existing in-store customers, the pricing-increase risk from A1 drops sharply (they are paying for convenience with low price sensitivity), and C2's migration potential is substantial.

6. **Platform contract terms**: price-parity clauses, commission tiers, exclusivity clauses, algorithmic penalties for price differentials. This is A1's only legal risk point.

7. **Store-level four-wall P&L** (prerequisite for B1, already listed under action A3).

8. **Month-by-month loss curves for the two new stores**, not six-month averages.

9. **Substantive exit interviews with departing bakers**: Is it compensation, early-morning shifts, career-path ceiling, or on-site management? The prescriptions for these four causes are entirely different, and the second and fourth cannot be solved with pay increases.

10. **Current central production capacity and utilization rate** — determines whether B2 is a low-cost solution or a capex commitment.

**Tier 3: Quantitative completion**

11. **Waste rates by category and by store** (see next section).
12. **Member RFM distribution**, and whether the 12K monthly actives are themselves declining (if monthly actives are also shrinking, the problem is worse than the static 20% activity rate suggests).
13. **Geographic distance and trade-area overlap between new and old stores** (cannibalization verification).

## VI. Proactive Additions: Dimensions Absent from the Data That May Determine Success or Failure

**1. Waste rate — bakery's largest hidden source of cash loss, entirely absent from the data.**  
Fresh bakery waste typically runs 5–12% of production value. At NT$280M, that is NT$14–33M — **larger than the impact of any single action item above.** And waste rates are directly correlated with SKU count, demand-forecast accuracy, and baker stability, so the true payoff of B3 (SKU rationalization) and C1 (subscription program) may be significantly underestimated above. This metric should be added to the management dashboard immediately.

**2. Cash position and balance sheet are entirely unknown.**  
Debt structure, repayment schedule, lease deposits, existing capex commitments, bank covenant conditions — these determine whether the "12-month" timeframe actually exists. If the runway is shorter than 12 months, the action sequence must be compressed, and B1's closure option should be moved earlier, not later. **Confirm this before adopting any recommendation.**

**3. Have raw material cost increases been passed through?**  
Raw materials +14%; maintaining margins requires ~5–7% in price adjustments. In-store margins remain at 52%, which looks like the cost has been absorbed, but it needs to be confirmed whether this was achieved through portion downsizing (shrinkflation). If so, this is eroding customer trust, and layered on top of the primary chain's quality instability, the risk compounds.

**4. Food safety risk is being structurally amplified.**  
High turnover + shortened hours + rush production + rising proportion of junior staff — this is the textbook precondition for a food safety incident. For an eight-year brand, the cost of one incident exceeds the combined impact of every issue discussed above. Recommend adding **routine SOP and cold-chain audits** to Wave 1 — this is low-cost insurance, not an optional enhancement.

**5. Competitive landscape data is entirely absent.**  
Is the −8% traffic decline an industry-wide phenomenon (convenience-store bakeries, hypermarket bakeries, neighborhood artisan bakeries expanding) or a market-share loss? The two call for opposite prescriptions: the former requires format and cost-structure adjustment; the latter requires product competitiveness repair. Recommend a one-time trade-area field survey (two-year change in bakery locations within 500 meters of each store).

**6. Middle management and organizational capability.**  
180 people, 12 stores, 8 years — the typical bottleneck at this scale is "the founder remains the sole operational decision node." The action sequence above runs 8–10 parallel workstreams simultaneously; **without district-manager-level leaders who can own store-level P&L accountability, the plan will naturally decay during execution.** If this layer does not currently exist, Wave 1 should include one additional item: designate 2–3 senior store managers to take on area responsibility, with four-wall P&L as their performance basis (A3 conveniently provides this tool).

**7. Seasonality has not been stripped out.**  
How much of the +40% in pastries and cakes came from holiday peaks? If growth after removing Mid-Autumn, Christmas, and Mother's Day is modest, the optimistic reading of "successful category-structure transformation" does not hold, and the conviction behind B3's defend-European-bread judgment grows stronger.

**If you want me to go deeper, the highest-value next step is**: obtain the store-level four-wall P&L statements and European bread stockout rates. The former turns the lease decisions from intuition into calculation; the latter determines whether the entire diagnostic primary chain holds. Everything else can wait — these two cannot.

</details>

# Test Insights

## Methodology

The analysis below relies solely on material contained in this file — the prompt itself, the task inputs, and the two responses. No quantitative cross-test comparisons are made, though readers may draw their own against other tests.

## Reading the Prompt First

Nine sentences. Pull apart the verb and object of each: critically analyze **the information provided**; adapt your reasoning to **different kinds of queries**; understand the nuances of **the query**; recognize both positive and negative **elements**; present **answers** clearly; prioritize clarity and precision; adapt your analysis to **the context and details of each inquiry**.

The object of every sentence is the input — the prompt, the information, the context. Not a single sentence takes the model's own output as its object. It demands that the model look carefully at the question; it does not demand that the model look carefully at what it writes: no "verify that claims you add are supported," no "label assumptions as assumptions," no "check whether your conclusions hold."

Two more signals. "Considering … connections between concepts" rewards linking things together without penalizing incorrect links. The "precision" in "prioritize clarity and precision" is most cheaply satisfied by numbers — writing precisely is not the same as computing correctly. And the sentence "when emotion or sentiment matters, recognize both positive and negative elements" is entirely irrelevant to these two tasks — it survived in the prompt because the optimization benchmark included sentiment-classification items.

Having read the prompt, a prediction can be written before seeing the outputs: it will make responses more structured than baseline; it will diligently inspect what the prompt provides (e.g., catching numerical contradictions); it will not inspect what it adds on its own; it will produce many connections and many precise-looking numbers. The two tasks below test whether this prediction holds.

## The Resume Task

Start with what it did right. It diagnosed the original version as a "job description" rather than "evidence of ownership over business outcomes," listed three concerns brand-side employers have about agency-background candidates (execution-only, no number ownership, project mindset), gave three revision actions (verb upgrades, case-based framing, reordering), and corrected "assisted with brand repositioning" to what the user actually did — "led." It flagged three numbers that will draw interview scrutiny (綠田's simultaneous ad-budget growth, MATZ's base rate, LURE's follower count as a vanity metric), recommended adding cross-functional collaboration and budget planning, and noted that Senior Planner to Marketing Manager is a level jump. All of this is useful.

Then, a sentence-by-sentence comparison against the input to identify what the response added on its own.

"Overall ROAS **steadily** maintained above 3.5" — the input said "ROAS **averaged** above 3.5." An average of 3.5 could come from volatile swings between 2 and 6; "steadily" is a word the response added, and it changes what can be challenged in an interview.

"**No follower growth ads deployed throughout**" — the input said "no bought followers during that period." In the original Chinese, the user's phrase (沒有買粉) refers to purchasing fake followers; the response's phrase (未投放粉絲增長廣告) means never running any follower-growth advertising campaigns. These are different claims. If asked in an interview, "So you never ran a single follower campaign?", the user might not be able to answer.

"Led **full-scope digital marketing** for 4–6 brand clients" — the input said "ran social media for 4–6 clients (FB+IG)." Social media management was upgraded to full-scope digital marketing.

"Restructured **audience segmentation and creative testing framework**" for membership conversion ads — the input said "I optimized it and CPA went from 680 to 320," with no mention of how. Audience segmentation and creative testing are methods the response supplied on the user's behalf.

Canva was removed from the tools list without explanation.

Now look at the interview preparation. It warned the user that three numbers could become liabilities if they can't withstand scrutiny — a correct warning. But the words the response itself added — "steadily," "no follower growth ads throughout," "full-scope," "audience segmentation" — are each the same kind of liability, and it warned about none of them. It also did not prepare a defense for the CPA 680 → 320 figure — of the four metrics, that one is the most likely to be probed for attribution methodology and measurement window.

In one sentence: it set thresholds for the user's numbers but set none for its own additions. This is exactly what the prompt predicted — the object is the input, not the output.

## The Operations Diagnosis Task

Start with what it did right, including several elements unique to this response. The Section I data reconciliation caught that multiplying traffic and ticket-size changes does not yield the reported revenue, and offered three explanations — the third, "new stores cannibalizing nearby legacy stores," is a genuinely valuable angle. The absolute-value recalculation table is correct; the blended gross margin shift from 47.9% to 44.5% and the "revenue +6%, gross profit −1.5%" figure check out; the estimate that the company is "most likely at or below operating breakeven," computed from its own stated cost benchmarks (labor ~25%, rent 10–12%, other 8–10%), lands at roughly −0.5%, which is consistent. A1's upfront check for platform price-parity clauses is a legal prerequisite others are likely to miss. B4's pre-committed M9 checkpoint to avoid sunk-cost capture is well designed. Section V's validation hypotheses are ranked by "if the answer differs, the recommendation materially changes"; Section VI raises the unknown balance sheet ("whether the 12-month timeframe actually exists"), unstripped seasonality, and middle management gaps with a concrete action (designate 2–3 senior store managers for area responsibility). These are substantive contributions.

Now examine how it arrived at its conclusions.

**Assumptions used to derive numbers are then validated by those same numbers.** Accelerator chain A: "In-store gross margin of 52% implies COGS of ~48%. If delivery records revenue at gross and deducts platform commission as a cost, then 52% − commission = 18%, yielding a commission rate of ~34% — squarely within the typical fee range for Taiwan's platforms. The fact that this equation holds is itself a conclusion: delivery prices are completely identical to in-store prices; the company has not passed on a single dollar." The first step of the derivation assumes delivery and in-store prices are identical (hence the same 48% COGS), calculates a 34% commission, and because 34% looks like a plausible platform fee, concludes prices are identical. The assumption is fed in and read back out. If delivery prices had already been marked up 15% and the commission were 38% plus packaging costs, the same 18% margin results. "Completely identical" and "not a single dollar" are definitive conclusions drawn from a compatibility check.

**The body presents conclusions that the appendix lists as unverified.** Accelerator chain A continues: "Customer traffic is simultaneously declining, **which means** these delivery sales are mostly not incremental but channel migration by existing customers … this is the worst kind of growth." Section V, item 5: "Are delivery customers new or migrated? Cross-reference by phone number across channels." The same proposition is written as a conclusion in Section II and as an open question in Section V. The same pattern appears in the primary chain: Section II constructs "bread quality instability → habitual customer loss" as the primary causal chain and makes the strategic choice to "defend European bread" in B3; Section V, item 1 says "whether the European bread decline is demand-side or supply-side … B3's strategic direction and resource allocation change completely — this is the single highest-priority validation." It recognizes where the fork is, but the plan is written along one branch — the other exists only in the appendix. Readers who only read the body (most will) receive a conclusion that its own appendix flags as undetermined.

**Connections are held up by rhetoric.** Primary chain, point 5: "The occasion-driven market has no moat: competitors include chain cake specialists, convenience-store desserts, and online-delivery cakes … the brand's eight-year asset is in European bread; that asset is leaking, and the water is flowing into a far more crowded pool." This reads compellingly, but the input contains no competitive data — Section VI, item 5 itself acknowledges "competitive landscape data is entirely absent." Moat, leaking, crowded pool: three unsupported judgments connected into a single image. The prompt asks for "connections between concepts" — this is the cheapest way to deliver them.

**Borrowed statistics.** B3: "Most eight-year brands accumulate 40+ items, with the bottom half contributing less than 15% of revenue." The input contains no SKU data; this sentence is an industry generalization written as a statement about this specific company.

**The same link, stripped of its conditions in a later section.** B1, item 5: closing one store and the freed-up bakers "**may be exactly** what is needed to restore full hours at the two stores with shortened schedules." Section IV, resource reallocation: "Headcount freed by store closures: prioritize redeployment to the two stores operating on shortened hours" — "may be exactly" has disappeared. For this link to hold, three things must be true: the freed bakers must possess the skill level to run a full production shift solo; they must be willing to change their commute for an early-morning shift (in a market with 40% turnover, they can walk at any time); and the closure decision arrives after M4, while the shortened-hours losses accrue daily starting now. None of the three is addressed.

**The NT$9.5M figure's hidden assumption.** "A ten-percentage-point channel shift (~NT$28M in revenue moving from 52% to 18% margin) erodes approximately NT$9.5M in gross profit" — the arithmetic is correct, but it assumes that the NT$28M would have occurred identically in-store had delivery not existed, i.e., delivery is 100% substitutional. This assumption is not stated, and Section V, item 5 is precisely the validation needed for it.

**The owned channel is placed six months out.** A1 in Wave 1 raises platform prices by 15–20%, creating a price differential that incentivizes delivery customers to migrate to self-pickup. C2's LINE-based pickup ordering doesn't arrive until M6–M12. The price differential appears first; the channel to catch the migration comes online six months later. This is not necessarily wrong, but it is an unaddressed sequencing gap.

**Certainty is not graded.** The word "完全" (completely/entirely) appears 11 times: "完全相同" (completely identical), "完全沒有反應" (completely unresponsive), "完全解釋" (completely explain), "完全不同的病因" (completely different root causes), "完全繞過" (completely bypass) — computed figures, assumed ones, and speculated ones are all delivered with the same adverb. The reader cannot distinguish "the three figures are pairwise incompatible" (calculated) from "not passed on a single dollar" (inferred) as different confidence levels.

**What it did not touch.** No dates (seasonal peaks are mentioned only in Section VI as something to strip out, never as campaigns to capture); no check on whether the 52% gross margin includes or excludes labor — it directly sets COGS at 48%; waste rate is flagged but not quantified; B2B gets one paragraph saying "launch only after production stabilizes"; no named owners and no delivery dates for any action.

## Taken Together

The predictions derived from reading the prompt were confirmed in both tasks. It diligently inspected what the prompt provided: the resume task caught that "assisted" was actually "led"; the operations task caught the numerical contradiction and offered three explanations. It did not inspect what it added: the resume task introduced "steadily," "no follower growth ads throughout," "full-scope," and "audience segmentation"; the operations task used assumptions to prove assumptions, stated conclusions in the body while listing them as open questions in the appendix, and used rhetoric to link unsupported judgments into a coherent picture.

This asymmetry is invisible on scorable tasks. Scorable tasks have standard answers; the model's output is compared against the answer, and incorrect connections cost points, so what the optimization process learns is "make the output look like reasoning." On tasks with no standard answer, what the model adds is what the user takes away — the words on the resume will be challenged in interviews; the "completely identical" in the operations plan will be taken into negotiations. The prompt concentrates all its inspection effort on the input side, but the user bears the consequences on the output side.

What it adds over baseline is real: structure, interview preparation, cannibalization, contract clauses, balance sheet, seasonality, pre-commitment. The additional risk it introduces over baseline is also real: more precise numbers, more confident connections, attached to equally unverified assumptions. Asking for "connections" and "precision" yields more linking, more precise writing, and not necessarily more accurate thinking.

## Additional Observations

**The prompt's object determines the direction of inspection.** The core finding of this analysis compresses to one sentence: MetaSPO's nine sentences all take the input as their object (the information provided, the query, each inquiry) — not one takes the model's own output as its object. The result is that the model diligently inspects what the prompt provides and does not inspect what it adds. This contrasts with Test 5 (detail-demanded version) — whose two requirements take "action guidance" (the model's output) as their object but demand only that it "carry operational specifics," not that it "verify correctness." Each prompt is missing half: MetaSPO lacks "look at yourself"; the detail-demanded version lacks "check whether it's right."

**Length coordinates for the resume task.** The MetaSPO resume-task output measured 1,055 characters, with the resume body at 356 characters. For comparison with Test 3: baseline A's full output was 979 characters with a resume body of 361 characters; Meta Rules B's full output was 3,957 characters with a resume body of 697 characters (including a personal summary). MetaSPO's full output length falls between A and B but skews toward A (1.08× A), and the resume body is virtually identical to A (0.99× A). A notable finding: MetaSPO's resume body and baseline A's resume body are nearly the same length, even though MetaSPO's structure is better (it has section headers). This suggests the resume body has an intrinsic length baseline that is largely independent of the prompt — the real differentiation comes from material outside the body (personal summary, interview defense kit, evaluation rubric).

**Length coordinates for the operations diagnosis task.** The MetaSPO operations diagnosis output measured 5,214 characters. For comparison with Test 1: baseline A was 4,360 characters; Meta Rules B was 13,535 characters. MetaSPO is 1.20× A and 0.39× B. It is 20% longer than baseline but less than 40% of Meta Rules. This aligns with the MetaSPO prompt's characteristics — it improves structure (more organized than baseline) but does not improve completeness (each node still stops at the directional level), because nothing in the prompt demands "expand to the point of executability."

**The count of "完全" (completely) is a useful quality signal.** The analysis above noted 11 instances of "完全" in the operations diagnosis. This observation generalizes: in professional analytical writing, the ratio of high-frequency certainty adverbs (完全/completely, 必然/necessarily, 一定/certainly, 顯然/obviously) to uncertainty markers (可能/possibly, 若/if, 視……而定/depending on, 待確認/pending verification) serves as a simple quality-control readout. Baseline A on the same task uses fewer certainty adverbs — not because it is more cautious, but because it makes fewer judgments overall. Meta Rules B has the highest judgment density but keeps certainty adverbs controlled — many judgments, but each tagged with a confidence level. MetaSPO's problem is not that it judges too much, but that every judgment is written in the same register of certainty, leaving the reader unable to distinguish which claims are computed from data and which the model believes ought to be true.
