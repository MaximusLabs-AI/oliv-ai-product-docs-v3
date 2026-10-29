# Revenue intelligence platform for sales managers: Oliv AI's Deal Driver agent

How Oliv AI's Deal Driver agent works as a revenue intelligence platform for sales managers: what it sends each day and week, which deal risks trigger an alert, how to set it up, and how it compares with other deal intelligence tools.

- Applies to: Sales managers, BDR leads and sales leadership
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/

A revenue intelligence platform should tell a sales manager which deals need attention before the forecast call, not after a rep escalates. Oliv AI does that job with its Deal Driver agent, a deal intelligence agent that keeps sales managers ahead of their team's pipeline without daily standups, manual rep check-ins or digging through CRM reports. Every weekday it sends a **Morning Brief**, fires alerts when something important happens, and closes the day with a **Sunset Summary**. It also prepares a **One-on-One Prep** report for each rep and a **Pipeline Review** every Monday.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Watches the team's pipeline and tells managers what needs attention |
| **Who it's for** | Sales managers, BDR leads and regional heads of sales, plus VP Sales and RevOps |
| **Daily rhythm** | **Morning Brief** and **Sunset Summary** every weekday, plus event-triggered alerts |
| **Weekly rhythm** | **Pipeline Review** every Monday; **One-on-One Prep** for each rep on that rep's own schedule |
| **Where it reaches you** | **Reports › My Reports**, plus Slack or email |
| **Includes** | The Meeting Assistant capability for reps |

## What the Deal Driver agent is {#what-it-is}

Oliv AI's Deal Driver agent is a manager intelligence agent. Managers stay informed at every level, from an individual rep to a single deal to the full team, from one agent. It doesn't write to the CRM. It surfaces signals for the manager to act on.

Deal Driver is also a bundle. It includes the capabilities of [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/): pre-call prep, post-call follow-up and CRM sync for reps. If you're on Deal Driver, your reps already have Meeting Assistant.

<figure>

![Pipeline Review open in Reports, My Reports. The left list shows the Deal Driver card with Pipeline Review (Every Monday), One-on-One Prep with two reps on Every Thursday and Every Friday, and Morning Brief (Weekdays). The report shows status navigation and an Overview with Pipeline Overview, Key Opportunities, Customer Updates and Next Steps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_198_reports_my-reports_deal-driver-pipeline-review-report-open-overview-closed-closing-soon-deals-at-risk-quick-wins-stalled-navigation.webp)

<figcaption>Deal Driver's reports sit together under one card in My Reports, each with its schedule. Pipeline Review is the Monday view of every deal, grouped by status, for leadership updates. Shown with sample data from a demo workspace.</figcaption>
</figure>

### Where the reports live {#where-reports-live}

Open **Reports › My Reports**. The **Deal Driver** card lists its four reports, each with a schedule tag: **Pipeline Review**, **One-on-One Prep**, **Morning Brief** and **Sunset Summary**. The **Reports for** dropdowns above the list set the team and role, such as Sales and Manager.

Each open report has a **Rate this report** button and a date picker. The previous and next arrows step between editions of the same report. Olivia's daily brief also carries a Deal Driver section, such as a check-in draft for a quiet deal, with a **Review draft from Deal Driver** button.

### The daily rhythm {#daily-rhythm}

- **Morning Brief.** Sent every weekday. An Overview covers the day's meetings, key highlights and customer engagement. **Important Meetings** come next, then a section of meetings for each rep.
- **Event-triggered alerts.** A signal during the day when a deal stalls, a stage drifts or a high-value opportunity goes quiet.
- **Sunset Summary.** Sent every weekday as an end-of-day recap of wins, risks and next-step gaps. Its Overview covers meetings, deal progress, notable updates and customer engagement.

Each Morning Brief meeting card shows a type tag, such as **Expansion** or **New Business**, the time and a short note. An availability line compares the meeting with your own calendar. **Add me to this call** and **Leave a note** let you join or brief the rep, and **Review Deal** opens the deal.

<figure>

![The Morning Brief open in My Reports, dated in the date picker. Inner navigation lists Overview, Important Meetings with three accounts, and a meetings section for each of two reps. The Overview shows Meetings Overview, Key Highlights and Customer Engagement, above the first Important Meetings card tagged Expansion.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_202_reports_my-reports_deal-driver-morning-brief-report-open-meetings-overview-ten-meetings-three-important-key-highlights-and-important-meetings.webp)

<figcaption>The Morning Brief opens with the day's meetings, flags the important ones and groups the rest by rep. It's where a manager decides which calls to join before the day starts. Shown with sample data from a demo workspace.</figcaption>
</figure>

The Sunset Summary's meetings line also says whether the notetaker recorded the day's meetings. Its sections then walk through **Closed Won**, **Closed Lost**, **Closing Soon**, **Quick Wins**, **Deals at Risk**, **Existing Customers** and **Needs Follow up**.

<figure>

![The Sunset Summary open in My Reports. Inner navigation lists Overview, Closed Won with one deal, Closed Lost, Closing Soon, Quick Wins, Deals at Risk, Existing Customers, Needs Follow up and one rep's meetings. The Overview shows Meetings Overview, Deal Progress, Notable Updates and Customer Engagement.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_204_reports_my-reports_deal-driver-sunset-summary-report-open-ten-meetings-recorded-deal-progress-notable-updates-and-customer-engagement.webp)

<figcaption>The Sunset Summary closes the day by status, from deals won and lost to deals that need follow-up. Its meetings line also confirms how many of the day's calls were recorded. Shown with sample data from a demo workspace.</figcaption>
</figure>

### The weekly rhythm {#weekly-rhythm}

- **One-on-One Prep.** A snapshot of each rep's pipeline to guide one-on-one coaching. Each rep has their own schedule tag, such as **Every Thursday** or **Every Friday**.
- **Pipeline Review.** Every Monday, a full view of every deal in the pipeline for executive updates. It's ready before the first standup of the week.

A One-on-One Prep report opens with the rep's total pipeline value and deal count. A **Pipeline Summary** follows, covering **Pipeline Health**, **Deal Momentum** and **Areas for Improvement**. Each status section then carries its own value and deal count.

<figure>

![One-on-One Prep open in My Reports for one rep, whose row under One-on-One Prep is highlighted with an Every Thursday tag. The report shows a total pipeline value chip and a deal count chip, a Pipeline Summary with Pipeline Health, Deal Momentum and Areas for Improvement, and the start of Closed Won.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_200_reports_my-reports_deal-driver-one-on-one-prep-report-open-derek-evans-875000-pipeline-10-deals-pipeline-summary-and-closed-won.webp)

<figcaption>One-on-One Prep gives the manager one rep's whole pipeline, status by status, before the meeting. Each rep's report runs on its own day, so 1:1s can start at strategy. Shown with sample data from a demo workspace.</figcaption>
</figure>

Pipeline Review opens with an Overview of **Pipeline Overview**, **Key Opportunities**, **Customer Updates** and **Next Steps**. Its sections run from **Closed** through **Closing Soon**, **Deals at Risk**, **Quick Wins**, **Stalled Deals**, **On Track Deals** and **Existing Customer** to **Needs Follow Up**. Each deal card holds a **Deal Summary**, a **Next Step** and **Review Deal**.

## Why the Deal Driver agent matters {#why-it-matters}

### What it's for {#what-its-for}

Oliv AI's Deal Driver agent is for managers who need to know what is happening in their team's pipeline without asking for it. It removes the lag between what happens in the field and what the manager hears.

### How it helps {#how-it-helps}

- **The day starts briefed.** Meetings, risks and deals that need attention first are surfaced before the day starts.
- **Risk shows up early.** Alerts fire the moment deals stall or stages drift, not when a rep escalates.
- **1:1s start at strategy.** Rep reviews arrive prepped, so the meeting skips twenty minutes of status updates.
- **Reps get time back.** A follow-up is drafted in about five minutes for the rep to review and send.

### What happens without it {#without-it}

A deal can go quiet with no activity, no CRM flag and no alert. A week later, the rep says "it's progressing" at the standup. By day fourteen the deal is cold and the rep escalates, after two or more weeks of invisible risk.

### Why buyers care {#why-buyers-care}

Deal Driver is bought by sales managers, VPs of Sales and regional heads. The sales manager is the main daily beneficiary, because the agent turns time spent on admin into time spent coaching.

## The Oliv AI approach to the Deal Driver agent {#approach}

{/* 5P */}

Think of a regional sales leader with eight account executives and about forty open opportunities. Every Monday she walks the VP of Sales through the region's pipeline. On Friday she starts working out which of those forty deals are really moving.

The usual method is a CRM export, a message to each rep asking for an update, and a skim of recent call notes. It can easily take an evening. Even then, the picture is only as current as the last field each rep remembered to fill in.

The raw signals already exist as the team works. Meetings get held, next steps get set, close dates slip and fields stay blank. What's missing is something that reads those signals every day and rolls them up on a schedule.

Oliv AI handles this with its Deal Driver agent. It monitors all activity on the team's deals and alerts the leader when a deal enters a risk state. Each alert carries the signal, the context and a suggested action. Before the first Monday standup, the Pipeline Review is already prepared.

Managers choose what counts as risk. Inactivity windows, field completion requirements and deal value thresholds can all be set per manager or per team, as listed in the set-up steps. How that rhythm lines up against other pipeline tools is covered in How Oliv AI compares as a revenue intelligence platform, below.

## How revenue intelligence platforms find deal risk {#methods}

Revenue intelligence platforms read the same pipeline in different ways. Most combine two or three of the methods below, and it helps to know which one is behind a warning before you act on it.

### Stage probability and weighted pipeline {#stage-probability}

The oldest method gives each pipeline stage a fixed chance of closing. In HubSpot, the weighted amount in board view is [calculated by multiplying the total amount in each stage by the stage probability](https://knowledge.hubspot.com/object-settings/set-up-and-customize-pipelines). A deal worth 100,000 USD in a stage set to 40% counts as 40,000 USD of weighted pipeline. The method is simple and consistent, but it only knows where a deal sits, not whether anyone is working it.

### Forecast categories {#forecast-categories}

Forecast categories add the rep's judgement. HubSpot's default deal properties [sort deals into Not forecasted, Pipeline, Best case, Commit or Closed won](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties). A category is quick to read on a forecast call. It's also only as current as the rep's last update, which is why managers end up asking for check-ins.

### Activity and engagement signals {#activity-signals}

Activity signals look at what is happening on the deal: meetings held, emails answered, next steps set and close dates moved. A late-stage deal with no meeting for three weeks reads very differently from one with a call booked for Tuesday. This method catches a quiet deal early, because the silence shows up before the stage or the category changes.

### Buyer progress scoring {#buyer-progress}

Gartner argued in a 2019 press release that judging a deal's chance to close from [sales stage completion no longer works](https://www.gartner.com/en/newsroom/press-releases/2019-11-13-gartner-says-the-traditional-linear-sales-process-no-), because B2B buyers repeat buying steps out of order. It recommended measuring deal progress with customer verifiers instead: evidence of what the buyer has done, rather than the stage a rep has selected.

### What Deal Driver is confirmed to watch {#what-deal-driver-watches}

Deal Driver works from activity and data signals. Its documented triggers are a deal with no activity for a set number of days, a close date approaching without progress, Core 4 Fields left empty after a meeting, a stage moving backward or stalling mid-stage, a high-value opportunity going quiet, and a rep pattern such as repeatedly missing next steps. It doesn't write to the CRM, so stage probabilities and forecast categories stay as your team set them. [Forecaster](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) rolls Deal Driver's signals into the number.

## Deal risk alerts and next steps {#deal-risk}

Deal Driver monitors all activity and triggers an alert when:

- A deal enters a risk state, such as no activity for a set number of days or a close date approaching without progress.
- A rep hasn't updated the Core 4 Fields after a meeting.
- A deal stage changes unexpectedly, moving backward or stalling mid-stage.
- A high-value opportunity goes quiet.
- A rep shows a pattern that warrants attention, such as consistently missing next-step fields.

Each alert includes the deal, the signal, the relevant context and a suggested action for the manager.

### Nudges for reps {#rep-nudges}

Deal Driver also nudges reps directly when deals stall, next steps go overdue or activity drops. That catches the gap before a manager needs to step in.

## Meeting support for reps {#meeting-support}

The Deal Driver bundle includes meeting-level support for individual reps.

- **Before the meeting.** About 30 minutes before every meeting on an active opportunity, the rep gets a deal summary, qualification status against the methodology, stakeholder context and a recommended agenda. Qualification follows the framework marked **Active** in **Settings › Qualification Framework**, which lists MEDDPICC, MEDDIC, SPICED, BANT and DRIVE.
- **After the meeting.** Once the recording is processed, the follow-up email is drafted, CRM field updates are proposed and qualification gaps are flagged, all within five minutes of the call ending.

## Pipeline risk in 2026: what sales teams report {#pipeline-risk-2026}

Two pieces of recent research explain why managers are moving from weekly check-ins to daily signals.

Gartner's research note of 3 June 2026, [Focus on 3 Pipeline Metrics to Improve Your Sales Forecast](https://www.gartner.com/en/documents/7952073), says the B2B selling environment has made accurate sales forecasts increasingly difficult. Instead of asking sellers for more input, it points sales leaders to three measures of pipeline health: initial pipeline value, pipeline conversion rate and pipeline slippage rate. Only the abstract is public, and the full method sits behind Gartner's paywall.

Salesforce's [State of Sales announcement for 2026](https://www.salesforce.com/news/stories/state-of-sales-report-announcement-2026/) found that the average seller spends 40% of their time selling, and Gen Z reps only 35%. Those reps lose about two hours a week to manual data entry. The same survey found that 54% of sellers have used AI agents and nearly 9 in 10 plan to by 2027. The figures come from a double-anonymous survey of 4,050 sales professionals, run in August and September 2025. Salesforce sells AI agents itself, so read the adoption figures as a vendor's survey rather than a count of the market.

For a sales manager, the practical point is that data entry is the work reps skip first, and empty fields are exactly what hides deal risk. That's why Deal Driver flags Core 4 Fields left empty after a meeting, and why CRM Manager fills them.

## How to measure pipeline health {#measure-pipeline-health}

Gartner's three measures make a good frame, because each one answers a different question. The definitions below are the common working ones. Gartner's public abstract names the measures but doesn't publish formulas.

| Measure | What it tells you | How it's usually worked out | Where it misleads |
|---|---|---|---|
| **Initial pipeline value** | Whether there's enough pipeline to reach the number | The total amount of open deals expected to close in the period, taken at the start of the period | It counts deals that nobody is working |
| **Pipeline conversion rate** | How much of that pipeline turns into revenue | Value won in the period, divided by initial pipeline value | It arrives at the end of the period, too late to act on |
| **Pipeline slippage rate** | How much pipeline moves out of the period | Value of deals whose close date moved past the period end, divided by initial pipeline value | It only shows once the date has changed |

Weighted pipeline sits beside these as a quick read of expected value, with the stage-probability limits described above. All three of Gartner's measures describe the period after the fact. Mid-quarter, a manager needs the early signs of slippage instead: no activity, a close date near with no progress, and missing next steps. Those are the signals Deal Driver watches.

### What Deal Driver's reports show {#deal-driver-measures}

The One-on-One Prep opens with a rep's total pipeline value and deal count, then a Pipeline Summary of **Pipeline Health**, **Deal Momentum** and **Areas for Improvement**. The Monday Pipeline Review groups every deal into **Closed**, **Closing Soon**, **Deals at Risk**, **Quick Wins**, **Stalled Deals**, **On Track Deals**, **Existing Customer** and **Needs Follow Up**. Read Stalled Deals and Deals at Risk against your slippage rate, because they're the deals most likely to slip next.

## How to find deal risk in a pipeline by hand {#find-deal-risk-by-hand}

Without a revenue intelligence platform, finding risk means pulling the signals together yourself. Most managers do it on a Friday, before the Monday forecast call.

1. Export the open deals expected to close this period from the CRM, with amount, stage, close date, last activity date and next step.
2. Work out each deal's weighted amount (amount times stage probability) and add them up.
3. Sort by last activity date, and mark any deal with no meeting or reply inside a window you choose, such as 14 days.
4. Mark deals whose close date falls in the next 30 days with no next step booked.
5. Check whether any close dates moved since last week, and note the value that moved out of the period.
6. Message each rep about the marked deals, and wait for answers.
7. Total the weighted pipeline again without the marked deals, to see the size of the gap at risk.

The Monday meeting itself is covered step by step in [Run a pipeline review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/).

### The same job with Deal Driver {#same-job-deal-driver}

Deal Driver does steps 3 to 6 continuously instead of once a week. It watches activity and close dates on every deal, alerts the manager when a deal enters a risk state, nudges the rep directly when next steps go overdue, and files the Pipeline Review before the first Monday standup. The manager's part shrinks to step 7 and the decision that follows: which deals to join, rescue or drop.

### Worked example: a quarter's pipeline with slippage {#worked-example}

This is an illustrative calculation with sample figures, not an Oliv AI output. A manager starts the quarter with eight deals, using stage probabilities a team might set in its CRM. All amounts are in US dollars.

| Deal | Amount (USD) | Stage probability | Weighted amount (USD) | Outcome at quarter end |
|---|---|---|---|---|
| A | 200,000 | 20% | 40,000 | Still open |
| B | 150,000 | 40% | 60,000 | Slipped to next quarter |
| C | 120,000 | 60% | 72,000 | Won |
| D | 100,000 | 40% | 40,000 | Slipped to next quarter |
| E | 80,000 | 80% | 64,000 | Won |
| F | 70,000 | 20% | 14,000 | Lost |
| G | 50,000 | 60% | 30,000 | Slipped to next quarter |
| H | 30,000 | 80% | 24,000 | Won |
| **Total** | **800,000** | | **344,000** | |

| Measure | Calculation (USD) | Result |
|---|---|---|
| Initial pipeline value | Sum of all eight amounts | 800,000 |
| Weighted pipeline | Sum of the weighted amounts | 344,000 |
| Slipped value | B + D + G = 150,000 + 100,000 + 50,000 | 300,000 |
| Pipeline slippage rate | 300,000 ÷ 800,000 | 37.5% |
| Won value | C + E + H = 120,000 + 80,000 + 30,000 | 230,000 |
| Pipeline conversion rate | 230,000 ÷ 800,000 | 28.75% |

The weighted pipeline promised 344,000 USD, and 130,000 USD of it sat in the three deals that later slipped. In this example, each of those deals had gone quiet weeks before its close date moved. An alert on the silence reaches the manager when the deal stops moving, not when the date changes at quarter end.

## Set up Deal Driver {#set-up}

1. **Connect your CRM.** Deal Driver reads Deal Insights data: stage, amount, close date and next steps.
2. **Connect your team's calendar.** Meeting and activity data from Oliv feed the Morning Brief and the alerts.
3. **Confirm the team roster and manager hierarchy.** Deal Driver needs both to know whose deals roll up to whom.
4. **Set your alert thresholds.** Choose inactivity windows, field completion requirements and deal value thresholds, per manager or per team.
5. **Adjust the brief format if you want to.** Managers can customize alert sensitivity and brief format.

Most managers are live within a week. Reps don't need to change anything. Deal Driver works in the background and shows up for them as follow-up prompts and next-step reminders.

## How Deal Driver works with other agents {#works-with}

### Coach {#with-coach}

[Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) is the rep development layer. On a rep's 1:1 day, the One-on-One Prep lands first with pipeline status, and Coach follows minutes later with that rep's coaching goal. In My Reports, Coach's **Monthly Review** sits beside it, one for each rep every 30 days.

### Forecaster {#with-forecaster}

[Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) builds on Deal Driver's signals. Deal Driver flags the exceptions, such as close dates without activity, and Forecaster rolls those signals into the number.

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) refreshes deal fields overnight from calls, emails and meetings. It also supplies the Core 4 Fields completion data that triggers gap alerts.

### Portfolio Manager {#with-portfolio-manager}

[Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager) is the customer success equivalent. It applies the same manager-visibility model to the renewal and retention book.

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) is the front-facing master agent for reps. Deal Driver is the manager's tool, though the Meeting Assistant capability inside the bundle serves reps directly.

## Who uses Deal Driver, and how {#who-uses-it}

### Sales managers {#sales-managers}

A sales manager reads the Morning Brief before the standup and each rep's One-on-One Prep before their 1:1. Many shorten the daily standup, and some drop it. More on Oliv AI for [sales managers](https://www.oliv.ai/sales-managers) and a [day in a sales manager's workflow](https://www.oliv.ai/blog/oliv-ai-sales-manager-daily-use-guide-features).

### BDR leads {#bdr-leads}

BDR leads use Deal Driver the same way as sales managers. The Morning Brief, rep activity alerts and One-on-One Prep reports work across BDR and AE pipelines, with different cadence and field settings. See how Oliv AI supports [sales development teams](https://www.oliv.ai/sales-development).

### VPs of Sales and regional heads {#sales-leadership}

Leaders get the Pipeline Review every Monday, ready before the first standup of the week. Read how a VP of Sales can [stop deals slipping unseen](https://www.oliv.ai/blog/deal-slippage-prevention-vp-sales).

### Revenue operations {#revops}

RevOps sets the alert thresholds and keeps the CRM data behind them accurate. More on how Oliv AI works for [revenue operations](https://www.oliv.ai/revops).

## How Oliv AI compares as a revenue intelligence platform {#compare}

Most deal intelligence tools give managers somewhere to look. Deal Driver tells them when to look, sends a 1:1 report for every rep each week, and wraps each weekday in a Sunset Summary. Oliv AI is the only platform in this table that does all three.

Deal intelligence features, from each platform's public documentation:

| Platform | Deal risk alerts | Per-rep 1:1 report each week | End-of-day summary for the manager |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Yes ([AI Deal Monitor warnings](https://help.gong.io/docs/customize-your-deal-warning-settings)) | Partly ([deal board to check before 1:1s](https://help.gong.io/docs/recipe-focus-on-deals-that-need-your-attention)) | Not in docs |
| **Avoma** | Yes ([AI-powered health alerts](https://help.avoma.com/import-your-crm-custom-fields-properties-into-pipeline-views)) | Not in docs | Not in docs |
| **Fireflies** | Yes ([Deal Intelligence risks](https://guide.fireflies.ai/articles/6941626485-getting-started-with-fireflies-crm-deal-intelligence)) | Not in docs | Not in docs |
| **Outreach** | Partly ([Deal Health score](https://support.outreach.io/support/solutions/articles/159000426278-deal-health-overview)) | Partly ([pipeline summary for 1:1 reviews](https://support.outreach.io/support/solutions/articles/159000425547-sales-manager-workflows-for-rep-coaching-and-1-1-s)) | Not in docs |
| **Fathom** | Partly ([answers on deal risks](https://help.fathom.video/en/articles/5363457)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger revenue intelligence platform for sales managers {#compare-stronger}

- **The 1:1 report comes to you.** Deal Driver compiles each rep's pipeline on that rep's own schedule and files it in the manager's My Reports. Gong [recommends checking a deal board weekly, particularly before 1:1s and pipeline reviews](https://help.gong.io/docs/recipe-focus-on-deals-that-need-your-attention). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **An alert with a next move.** Each Deal Driver alert carries the deal, the signal, the context and a suggested action. Avoma's Deal Health [produces a 0 to 100 risk score with a Low, Medium or High classification](https://help.avoma.com/deal-health). Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **A daily rhythm, not a weekly check.** Deal Driver sends a Morning Brief and a Sunset Summary every weekday. Gong's [pipeline generation dashboard recipe says it should be viewed weekly](https://help.gong.io/docs/pipeline-generation-dashboard-recipe). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **It doesn't update CRM fields.** Deal Driver surfaces data quality gaps. CRM Manager makes the updates.
- **It isn't the forecast.** Forecaster handles pipeline projection and accuracy. Deal Driver handles real-time visibility and alerts.
- **It isn't a coaching tool.** Coach handles rep development.
- **It's built for sales teams.** Customer success managers use Portfolio Manager instead.
- **Signals depend on the data.** Deal Driver's signals are only as good as the data behind them, which is why CRM Manager matters.

## Common questions {#common-questions}

#### Will Deal Driver replace my daily standup? {#faq-standup}

For many managers, yes. When reps get their own activity alerts and you have a Morning Brief, the standup becomes a strategy conversation. Some managers drop it.

#### Can I customize what triggers an alert? {#faq-alert-triggers}

Yes. Inactivity windows, field completion requirements and deal value thresholds are all configurable per manager or per team.

#### Does it work for BDR teams? {#faq-bdr-teams}

Yes. Sales managers and BDR leads use it the same way. Cadence and field settings differ, but the structure is the same.

#### How does the One-on-One Prep report work? {#faq-thursday-report}

Each rep gets their own report on their own schedule, such as Every Thursday or Every Friday. It shows the rep's pipeline total, a Pipeline Summary and every deal by status.

#### We already have a pipeline visibility tool. Do we still need Deal Driver? {#faq-existing-tools}

Visibility tools show you the pipeline. Deal Driver tells you when to look, what to pay attention to and what to do. Many teams run both.

#### Do I need Meeting Assistant separately? {#faq-meeting-assistant}

No. [Meeting Assistant](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) is included in Deal Driver, so your reps already have it.

#### Does Deal Driver write to the CRM? {#faq-crm-writes}

No. It sends alerts, briefs and summaries to [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/), email or **Reports › My Reports** in Oliv AI. [CRM Manager](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) handles field updates.

#### Does it work for customer success managers? {#faq-cs-managers}

It's designed for sales managers and BDR leads. Customer success managers have an equivalent agent, Portfolio Manager.

#### How long does setup take? {#faq-setup-time}

Connect your CRM and your team's calendar, then set your alert thresholds. Most managers are live within a week.

#### Do reps need to change how they work? {#faq-reps}

No. Deal Driver works in the background and shows up for reps as follow-up prompts and next-step reminders.

#### What is a revenue intelligence platform? {#faq-revenue-intelligence-platform}

A revenue intelligence platform reads sales activity, such as meetings, emails and CRM changes, and turns it into signals about deals, reps and the forecast. Oliv AI does this with agents: Deal Driver for deal risk, Forecaster for the number and Coach for rep development.

#### How is revenue intelligence different from deal intelligence? {#faq-deal-intelligence}

Deal intelligence is the part of revenue intelligence that looks at single deals: their risk, momentum and next steps. Revenue intelligence also covers the forecast and rep performance. Deal Driver is Oliv AI's deal intelligence agent.

#### Which pipeline metrics show deal risk early? {#faq-pipeline-metrics}

Gartner points to initial pipeline value, pipeline conversion rate and pipeline slippage rate. Slippage is the clearest measure of risk, but it only shows once a close date moves. Inactivity and missing next steps show the same risk earlier.

#### Does Deal Driver change my stage probabilities or forecast categories? {#faq-forecast-categories}

No. Deal Driver doesn't write to the CRM, so stage probabilities and forecast categories stay as your team set them. Forecaster uses Deal Driver's signals when it builds the forecast.

## Further reading {#further-reading}

- [Focus on 3 Pipeline Metrics to Improve Your Sales Forecast](https://www.gartner.com/en/documents/7952073) (Gartner, 3 June 2026): the three measures of pipeline health Gartner recommends tracking.
- [Gartner says the traditional linear sales process no longer exists](https://www.gartner.com/en/newsroom/press-releases/2019-11-13-gartner-says-the-traditional-linear-sales-process-no-) (Gartner, 13 November 2019): why stage-based close probability misreads how B2B buyers move.
- [State of Sales 2026 announcement](https://www.salesforce.com/news/stories/state-of-sales-report-announcement-2026/) (Salesforce): time spent selling, AI agent adoption and how the survey was run.
- [State of Sales report](https://www.salesforce.com/sales/state-of-sales/) (Salesforce): the report's headline findings on agents and growth.
- [Set up and customize pipelines](https://knowledge.hubspot.com/object-settings/set-up-and-customize-pipelines) (HubSpot Knowledge Base): how stage probability produces the weighted amount.
- [HubSpot's default deal properties](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties) (HubSpot Knowledge Base): deal probability, forecast category and forecast amount defined.

## Related {#related}

- [Deal Driver on oliv.ai](https://www.oliv.ai/agents/deal-driver): the agent's own page, with its weekly cadence.
- [The Olivia agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): the front-facing agent reps work with.
- [Sales pipeline software guide](https://www.oliv.ai/blog/sales-pipeline-software): how pipeline tools differ and what to weigh.
- [Pipeline analytics software](https://www.oliv.ai/blog/pipeline-analytics-software): stage and conversion analytics compared.
- [Deal intelligence explained](https://www.oliv.ai/blog/deal-intelligence): how AI predicts pipeline risk.
- [Oliv AI pricing](https://www.oliv.ai/pricing): plans and what each includes.
- [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): the rep's side of the same deals.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.

*Updated 29 October 2026: added how revenue intelligence platforms find deal risk, 2026 research on pipeline risk, how to measure pipeline health, the manual method with a worked example, four more questions and further reading.*
