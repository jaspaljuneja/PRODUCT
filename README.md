# Phase 1 — Problem brief

Product: Personal Finance App · Version 1.0 · April 2026 · PM Portfolio Document

## 1. Problem statement

Right now, we know that around 76% of Americans live paycheck-to-paycheck, only 46% of Americans have just enough emergency savings to cover just 3 months of expenses. And nearly 40% of Americans have less than $500 in cash savings.

![Problem overview](images1/image1.png)

Millions of everyday people across income levels live paycheck to paycheck — not because they don't earn enough, but because they lack a simple, unified tool to understand their money, control their spending, and start building savings. Existing financial apps are either too complex for non-experts, too narrow in scope, or does not recommend the steps of action to be taken by general users. The result: people feel anxious about money, avoid thinking about it, and never make enough savings and mindset of savings.

## 2. Target audience

Primary users: Everyday earners across all age groups — anyone who receives a regular paycheck and struggles to make it last or grow.

- Household income: $30,000 – $90,000/year
- Financial literacy: low to moderate
- Behavior: reactive with money — spend first, save what's left (often nothing)
- Emotional state: stressed or avoidant about finances
- Tech comfort: moderate — comfortable with apps, not financial platforms

Not building for: High net-worth individuals, finance professionals, or businesses.

## 3. Pain points

**Emotional:** Guilt around spending, anxiety about no emergency fund, feeling "behind" financially.

**Practical:** No clear picture of where money goes each month. Savings feel impossible when bills consume the whole paycheck. Investing feels too intimidating. Nothing connects the full financial picture in one place.

**Behavioral:** Budgets get abandoned within weeks. Apps show data but don't guide action. No small wins to build momentum.

## 4. Competitive landscape

| **App** | **Strengths** | **Gaps** |
| --- | --- | --- |
| Mint (shut down 2023) | Simple unified view | Gone — left ~3.6M users with nowhere to go |
| Copilot | Beautiful UI, smart tracking | No investing, premium price |
| Robinhood | Easy investing | No budgeting or savings features |
| NerdWallet | Great content | Not a tracking tool, no personalization |
| Huntington | Tells spending using Visuals | Does not recommend & prioritize savings and next step of action. |

Our gap: No app combines simple budgeting, savings goals, and beginner investment guidance in one jargon-free experience. And does not recommend next step of actions. But we will guide users and show recommendations on saving strategy with goals.

## 5. Opportunity sizing

- TAM: Personal finance app market — $1.57B (2023), projected $3.7B by 2030
- SAM: ~157M US adults living paycheck to paycheck (60% of Americans)
- SOM: 0.5% of SAM in Year 1 = ~785,000 users. At $7/month = ~$65M ARR potential

## 6. Product hypothesis

*"We believe that everyday earners who live paycheck to paycheck need a single, jargon-free app that connects their spending, saving, and investing — so they can take small, confident steps toward financial stability without feeling overwhelmed."*

We'll know it's working when:

- Users open the app 3x per week on average
- 40%+ of users set up a savings goal within the first week
- Users report feeling "more in control" after 30 days (in-app survey)

## 7. Key assumptions to validate

- Users will pay for premium if it includes personalized investment recommendations
- The post-Mint audience is still actively looking for a replacement
- Simplicity is a bigger differentiator than feature depth for this audience
- Users are willing to connect bank accounts for automated tracking

---

## Next step: Phase 2 — User personas

Most people I spoke didn't have clear idea on how to start saving. They were confused, agitated, and felt stuck and guilty that they feel trapped.

![User persona diagram 1](images1/image2.png)

![User persona diagram 2](images1/image3.png)

![User persona diagram 3](images1/image4.png)

So with above interviews and cards, I will keep in mind to make app that is savings focused and has visuals and easy to use, use clear wording no/less finance jargons, integrate venmo and apple pay. Also provide HYSA which gives good return on their savings.

---

## Phase 3 – User Stories

- As Aisha, I want a jargon free app, so that I don't feel overwhelmed when I first use it.
- As Diana, I want a recommendation tips every time I open my account about saving my money.

![User story 1](images1/image5.png)

![User story 2](images1/image6.png)

![User story 3](images1/image7.png)

![User story 4](images1/image8.png)

---

## Phase 4 – Prioritization

![Prioritization diagram](images1/image9.png)

| User Story | Priority | Rationale |
| --- | --- | --- |
| US-01 — Bank account connection | Must have | Core value prop. Without it the app has no data and can't function. |
| US-06 — Safe to spend number | Must have | Single most differentiating feature. High impact, low build effort. |
| US-05 — Overspend alert | Must have | Drives daily engagement. Simple push notification — low effort. |
| US-04 — Spending breakdown | Must have | Core budgeting view. Users expect this — no differentiation without it. |
| US-07 — Savings goals | Must have | Primary retention driver. Users who set a goal are 3x more likely to return. |
| US-03 — Jargon-free onboarding | Should have | Critical for Aisha persona. High effort but protects day-1 retention. |
| US-02 — Variable income setup | Should have | Necessary for Diana persona. Without it she churns immediately. |
| US-09 — Investing 101 content | Should have | Low effort to produce. Builds trust before asking users to invest. |
| US-08 — Micro savings suggestion | Could have | Nice-to-have for Diana. Adds delight but not a blocker for v1 launch. |
| US-10 — Retirement indicator | Could have | High value for Marcus but complex to build accurately. Better in v2. |
| US-11 — Investment recommendations | Won't have (v1) | Requires regulatory compliance (financial advice laws). Too risky for v1. |

---

## Phase 5 – Product Roadmap

![Product roadmap](images1/image10.png)

Here, we have defined what user story to start with when it starts and how long will it take to complete. It's a strategy plan rather than just a to-do list.

---

## Phase 6 – Success Metrics + OKRs (Objectives and Key Results)

In this phase, we basically see how our product is performing in the market. Are user's liking it, we collect feedback from the user. And then if needs to tweak the product its goes again in the next sprint or next release.

**v1 · Q1** Prove the core product delivers real value to everyday users

- KR1: Reach 1,000 weekly active users within 8 weeks of launch
- KR2: 40% of new users set a savings goal within their first week
- KR3: Day-7 retention rate of 35% or above
- KR4: Average onboarding completion rate of 70%+

**v2 · Q2** Deepen engagement and expand to underserved user segments

- KR1: Reach 10,000 weekly active users
- KR2: 60% weekly retention (users return at least once per week)
- KR3: Variable income users have equal retention to fixed income users
- KR4: NPS score of 40+ across all three personas

**v3 · Q3–Q4** Build a sustainable, monetized product

- KR1: Reach 50,000 weekly active users
- KR2: 5% of active users convert to paid tier ($7/month)
- KR3: Achieve $210,000 ARR by end of year 1
- KR4: Churn rate below 8% per month on paid tier
