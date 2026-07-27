# Revenue Models Reference

12 models. For each: fit conditions, anti-patterns, reference companies, cold-start path.

---

## 1. SaaS Subscription (月订阅/年订阅)

**Fit when:**
- Problem recurs monthly (not a one-time event)
- User needs to log in repeatedly to get value
- You can automate delivery (no manual work per customer)
- ARR > $1K is achievable within 3 months

**Anti-patterns (do NOT use if):**
- Value is delivered once and done (use one-time payment instead)
- Target buyer has no software budget (use consulting instead)
- You need >6 months to prove ROI to customer

**Reference companies:**
- Notion — $8/mo individual, $15/mo business; grew through viral "second brain" community
- Linear — charged from day 1, no free tier, won by having better UX than Jira
- Lemon Squeezy — flat $9/mo; attacked gumroad by bundling tax compliance

**Cold-start path:**
1. Find 5 people with the exact problem on Twitter/LinkedIn/Slack
2. DM: "I built X. Pay me $[price]/mo, I'll set it up for you in 30 min."
3. Get 3 paying before you write another line of code

---

## 2. Usage-Based / Pay-Per-Use (按量计费)

**Fit when:**
- Value scales with usage (API calls, tokens, seats, emails sent)
- Customers can start small and grow naturally
- You have infrastructure costs that scale with usage (don't eat the margin)

**Anti-patterns:**
- Usage is unpredictable — customers hate surprise bills
- Your COGS are fixed (use subscription instead)
- B2C consumers — unpredictable spending causes churn

**Reference companies:**
- Stripe — 2.9% + $0.30 per transaction; no monthly fee, lowers friction to start
- Twilio — pay per SMS/call; grew by removing upfront commitment
- OpenAI API — per-token; makes enterprise easy to justify

**Cold-start path:**
1. Set a floor price (minimum $10/mo) to filter serious users
2. Bill monthly in arrears — reduce friction to start
3. Show real-time usage dashboard on day 1 (reduces bill anxiety)

---

## 3. One-Time Purchase (买断)

**Fit when:**
- Clear, finite deliverable (e.g., a template, a plugin, a report)
- Customer won't need ongoing support
- You want passive income without support overhead
- Price point < $500

**Anti-patterns:**
- Complex software requiring ongoing updates/hosting
- B2B enterprise (they prefer subscriptions for budget reasons)
- You need recurring revenue to survive

**Reference companies:**
- Gumroad creators — templates, ebooks, presets; $0 upfront, 10% cut
- Sketch (pre-subscription era) — won market with $99 one-time vs Adobe's $50/mo
- Figma plugins — one-time or free, used as top-of-funnel for related products

**Cold-start path:**
1. Ship to Gumroad/Lemon Squeezy this week
2. Price at $29–$99 (too cheap = no credibility, too high = no impulse buy)
3. Post in 3 relevant communities with "I made this, here's the problem it solves"

---

## 4. Done-For-You / Productized Service (固定价服务包)

**Fit when:**
- You have expertise that clients can't easily replicate
- You can scope the deliverable clearly (no open-ended engagements)
- Target buyers have budget and a specific outcome they need

**Anti-patterns:**
- You want to scale without adding headcount
- Deliverable varies significantly per client
- You can't say no to custom requests

**Reference companies:**
- Design Joy — $4,995/mo for unlimited design requests; Ryan handles it solo
- Rocketship.vc — productized VC pitch deck review
- Web Profits — fixed-scope SEO packages

**Cold-start path:**
1. Define your package: "I will [deliverable] in [timeframe] for $[price]"
2. DM 10 people who match buyer profile today
3. Do the first one for $0 if needed, get a testimonial, charge full price next

---

## 5. Marketplace / Transaction Fee (交易抽佣)

**Fit when:**
- You connect buyers and sellers who don't know each other
- Transaction value is measurable
- Both sides benefit enough to pay (or one side subsidizes the other)

**Anti-patterns:**
- Cold start is unsolvable (no buyers without sellers, no sellers without buyers)
- Transaction value is too low to justify fee (< $10/transaction)
- You're solo and can't manually bootstrap supply side

**Reference companies:**
- Airbnb — 3% host fee + 14% guest fee; seeded supply by manually listing properties
- Etsy — 6.5% transaction fee; started with handmade crafts niche, expanded
- Toptal — 20%+ margin; won by curating top 3% of developers

**Cold-start path:**
1. Manually create supply side (reach out to 20 potential sellers/providers)
2. Guarantee buyers their first transaction risk-free
3. Charge sellers only after they get paid (align incentives)

---

## 6. Lead Generation / B2B Leads (卖线索)

**Fit when:**
- You have access to high-intent buyers that businesses want to reach
- Niche is specific enough to have premium value (not generic traffic)
- You can verify lead quality (not just lists)

**Anti-patterns:**
- Broad horizontal audience (leads too cheap)
- You're in a market with strict data privacy laws and you lack compliance setup
- You can't demonstrate conversion quality to buyers

**Reference companies:**
- HomeAdvisor — charge contractors $20–$100 per homeowner lead
- G2 — SaaS comparison site; charge vendors for category placement + leads
- Clutch — B2B agency reviews; sell category sponsorships + RFQ leads

**Cold-start path:**
1. Build a niche list (100+ verified contacts in a specific vertical)
2. Sell a test batch of 10 leads to one buyer for $50–$200
3. Prove conversion rate, then expand

---

## 7. Freemium → Paid Upgrade (免费增值)

**Fit when:**
- Product has clear free-to-paid upgrade triggers (storage limit, seat limit, advanced features)
- Distribution is viral or organic SEO-driven (need volume for freemium to work)
- Conversion rate to paid can be > 2% (benchmark: Spotify 26%, Slack 30% of active teams)

**Anti-patterns:**
- Solo founder without distribution — freemium starves you before conversion
- No clear "paid wall" — you give away everything valuable for free
- CAC > LTV at any conversion rate

**Reference companies:**
- Spotify — free with ads → $9.99/mo premium; 26% paid conversion
- Dropbox — free 2GB → paid for more storage; grew through referral
- Slack — free up to 90 days of history → paid for full history + more seats

**Cold-start path:**
1. Define your paid feature BEFORE launching free tier (most people do this backwards)
2. Set paid conversion goal: 30 free users → 1 paid is baseline
3. Track free-to-paid funnel weekly from week 1

---

## 8. Community / Membership (社群会员)

**Fit when:**
- You have an existing audience (>500 engaged followers)
- Members value access to each other, not just to you
- Topic has recurring conversation (not one-time interest)

**Anti-patterns:**
- Starting from zero — community requires existing trust/audience
- You can't commit to consistent presence (community dies without host energy)
- Topic is too broad to create genuine identity

**Reference companies:**
- Lex Fridman (no paywall) vs. Codie Sanchez — charge $500–$1,000/yr for operator community
- On Deck — $1,500–$10,000 cohort; high price signals serious members, filters casuals
- Lenny's Newsletter + community — $150/yr; newsletter drives community, community raises newsletter value

**Cold-start path:**
1. You need 200+ genuine fans before charging
2. Start with a founding member price (50% discount, limited slots)
3. Create ONE recurring event (weekly call, monthly AMA) as the paid anchor

---

## 9. Sponsorships / Advertising (广告赞助)

**Fit when:**
- You have a niche audience that a specific type of advertiser wants to reach
- Audience size > 5,000 (newsletter) or > 50K monthly visits (content)
- You can maintain editorial independence (don't become the ad)

**Anti-patterns:**
- Broad horizontal audience (CPM is $2, not $50)
- You'll compromise content quality for sponsor revenue
- Audience size is too small for meaningful revenue

**Reference companies:**
- Morning Brew — sold at $75M; newsletter sponsorships at $50–$70 CPM
- The Hustle — finance/tech newsletter; sold to HubSpot for $27M
- Indie Hackers — Stripe-owned, sold sponsorships to dev tools

**Cold-start path:**
1. Need 2,000+ engaged subscribers to get first sponsor at $200–$500/edition
2. Cold pitch 10 companies whose ideal customer matches your audience
3. Offer 3 sponsored editions as a trial package

---

## 10. White Label / Licensing (白牌/授权)

**Fit when:**
- You built something other businesses want to offer their customers
- Your tech is more valuable embedded in someone else's product
- You can handle B2B sales (longer cycles, higher ACV)

**Anti-patterns:**
- Your differentiation is the UX/brand (white labeling removes your moat)
- You need fast revenue (B2B licensing cycles = 3–12 months)
- You can't support enterprise contracts (SLAs, security reviews, etc.)

**Reference companies:**
- Twilio white-label communications for hundreds of apps
- Mapbox — Google Maps alternative for apps that want custom map styling
- Stripe Connect — white-label payments infrastructure for platforms

**Cold-start path:**
1. Find 3 businesses currently doing manually what your tech automates
2. Offer a pilot: "I'll set it up, you pay only if it works"
3. Structure as annual license (predictable for both sides)

---

## 11. Consulting / Advisory (顾问咨询)

**Fit when:**
- You have rare expertise that companies need episodically
- Target buyers have >$500/hr consulting budget
- You can land first client through existing network

**Anti-patterns:**
- You want to stop trading time for money within 12 months (start consulting, build product on the side)
- Your expertise is too broad ("I help companies grow") — must be specific
- You can't generate warm intros in target market

**Reference companies:**
- Early Stripe — Collison brothers did free consulting at YC to learn what payments problems existed
- Basecamp — built on consulting revenue before productizing
- McKinsey alumni consulting boutiques — $3,000–$10,000/day

**Cold-start path:**
1. Pick 1 specific outcome you deliver ("I help Series A SaaS companies reduce churn")
2. Email 20 people in your network with a specific offer
3. First engagement at 50% discount for a testimonial

---

## 12. Data / API as Product (数据/API变现)

**Fit when:**
- You have proprietary data others can't easily get
- There's a repeatable use case for the data (not one-off research)
- Technical buyers (developers, analysts) are your target

**Anti-patterns:**
- Data isn't truly proprietary (scraped from public sources anyone can access)
- Use case is too niche for > $50K ARR
- Data freshness requirements are costly to maintain

**Reference companies:**
- Bloomberg Terminal — $24,000/yr per seat; financial data monopoly
- Clearbit — B2B company data API; acquired by HubSpot for ~$150M
- Apify — web scraping platform; charge per compute unit

**Cold-start path:**
1. Export your data sample, reach out to 10 potential API buyers with a test file
2. Charge for a pilot: "$500 for 3 months of data, cancel anytime"
3. If they renew, productize the API; if not, the data isn't valuable enough
