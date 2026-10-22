# Run a pipeline review

How a sales manager runs a weekly deal-by-deal pipeline review with Oliv AI, from each rep's One-on-One Prep report and deal risk alerts to the forecast board, rep nudges and the Monday Pipeline Review.

- Applies to: Sales managers and BDR leads with a connected CRM and team calendar
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/

Oliv AI prepares a sales manager's pipeline review before the meeting starts. Oliv AI's Deal Driver agent writes a **One-on-One Prep** report for each rep before their 1:1, on that rep's own schedule, such as every Thursday. Through the week it flags deals that need attention, each with a suggested action. This guide walks through a deal-by-deal review, from the rep reports to the Monday **Pipeline Review** for leadership.

## At a glance {#at-a-glance}

| | |
|---|---|
| **Who runs it** | Sales managers and BDR leads, with Oliv AI's Deal Driver agent |
| **Per-rep report** | **One-on-One Prep**, on each rep's schedule, such as every Thursday |
| **Daily rhythm** | **Morning Brief** and **Sunset Summary** every weekday, plus live alerts |
| **Each alert carries** | The deal, the signal, context and a suggested action |
| **For leadership** | **Pipeline Review** every Monday, a full view of every deal by status |
| **Where reports live** | **Reports › My Reports**, grouped by the agent that writes them |
| **The forecast** | The **Boards** tab in Forecast, by manager and rep |
| **Set-up** | Connect the CRM and team calendar, then set alert thresholds |

## Before you begin {#before-you-begin}

- **Connect the CRM and the team's calendar.** Deal Driver reads meeting and activity data, plus deal stage, amount, close date and next steps.
- **Have your team roster and hierarchy set.** Reports and alerts follow who reports to whom.
- **Decide your thresholds.** Inactivity windows, field completion requirements and deal value thresholds can be set per manager or per team.
- **Keep the fields current.** Deal Driver's signals are only as good as the data behind them. [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) keeps that data current from calls, emails and meetings.

## Step 1: Set up Deal Driver {#step-1-set-up}

Connect the CRM and the team's calendar, then set alert thresholds. Most managers are live within a week. Reps don't need to change anything: [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) works in the background and shows up for them as follow-up prompts and next-step reminders.

You can also adjust alert sensitivity and the brief format. Every scheduled report appears in **Reports › My Reports**, and briefs, alerts and summaries can also reach the manager through [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) or email.

## Step 2: Start the day with the Morning Brief {#step-2-morning-brief}

Every weekday, Deal Driver's **Morning Brief** opens on an **Overview**: the day's meetings across the team, the key highlights and customer engagement. **Important Meetings** come next, then each rep's meetings. It covers:

- Today's meetings across the team: who is meeting whom, which deal it relates to and what matters about the call.
- Flags for meetings where your attendance or pre-meeting notes would add value.
- Priority deals to watch that day, based on signals from the prior 24 hours.

Each meeting card shows the meeting type and time, checks it against your calendar, and offers **Add me to this call** and **Leave a note**. On review day, the important meetings and priority deals are a good first cut of the agenda.

<figure>

![Reports, My Reports, with Deal Driver's Morning Brief open for the day. The left list shows Pipeline Review, One-on-One Prep and Morning Brief with their schedules. The report shows a navigation of Overview, Important Meetings and each rep's meetings, an Overview with meeting counts and key highlights, and the first important meeting card.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_202_reports_my-reports_deal-driver-morning-brief-report-open-meetings-overview-ten-meetings-three-important-key-highlights-and-important-meetings.webp)

<figcaption>The Morning Brief turns the team's calendar into a short list of meetings that matter, which is where review day starts.</figcaption>
</figure>

## Step 3: Open each rep's One-on-One Prep {#step-3-rep-reports}

Deal Driver compiles a structured view of each rep's pipeline before their 1:1. In **My Reports**, open **One-on-One Prep** and pick the rep. The report shows their total pipeline and deal count, then a **Pipeline Summary** of **Pipeline Health**, **Deal Momentum** and **Areas for Improvement**.

The rest of the report sorts the rep's deals into **Closed Won**, **Closed Lost**, **Closing Soon**, **Quick Wins**, **On Track Deals**, **Deals at Risk**, **Existing Customers** and **Needs Follow Up**. Each deal has a summary and a next step.

<figure>

![One-on-One Prep report for one rep in My Reports. The rep's row is selected under Deal Driver with an Every Thursday tag. The report shows the total pipeline and deal count, a Pipeline Summary of Pipeline Health, Deal Momentum and Areas for Improvement, a status navigation and the start of Closed Won.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_200_reports_my-reports_deal-driver-one-on-one-prep-report-open-derek-evans-875000-pipeline-10-deals-pipeline-summary-and-closed-won.webp)

<figcaption>One-on-One Prep gives the manager a rep's whole pipeline, sorted by what needs attention, so the 1:1 can skip the status recap.</figcaption>
</figure>

Minutes later, [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) follows with that rep's coaching goal and weekly progress. You walk into each conversation with both status and development context. For prep on the customer meetings themselves, reps get their own brief, covered in [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

## Step 4: Work deal by deal {#step-4-deal-by-deal}

Go through each rep's flagged deals in turn. Deal Driver monitors all activity and raises an alert when:

- A deal enters a risk state, such as no activity for a set number of days, or a close date approaching without progress.
- A rep hasn't updated the Core 4 Fields after a meeting.
- A deal stage changes unexpectedly, moving backward or stalling mid-stage.
- A high-value opportunity goes quiet.
- A rep shows a pattern that warrants attention, such as consistently missing next-step fields.

For the whole team, Deal Driver's **Pipeline Review** lists every deal by status, including **Deals at Risk**, **Stalled Deals** and **Needs Follow Up**. Each section opens with a **Deals Overview**, and each deal card has a **Deal Summary**, a **Next Step** and **Review Deal** to open the deal.

<figure>

![Deal Driver's Pipeline Review open in My Reports under an Every Monday tag. A navigation lists Overview, Closed, Closing Soon, Deals at Risk, Quick Wins, Stalled Deals, On Track Deals, Existing Customer and Needs Follow Up. The Overview covers the pipeline, key opportunities, customer updates and next steps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_198_reports_my-reports_deal-driver-pipeline-review-report-open-overview-closed-closing-soon-deals-at-risk-quick-wins-stalled-navigation.webp)

<figcaption>Pipeline Review is the deal-by-deal agenda: jump straight to the at-risk and stalled sections instead of walking the healthy deals.</figcaption>
</figure>

For each flagged deal:

1. Read the alert. It names the deal, the signal, the relevant context and a suggested action.
2. Ask the rep about the signal, not the status. The status is already on the page.
3. Agree the next step and who owns it.
4. Move to the next flagged deal. Deals without a flag can wait for the next review.

## Step 5: Check the forecast {#step-5-forecast}

[Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) rolls Deal Driver's signals into the number: close dates without activity, confidence without engagement and stalled next steps. As the manager:

1. Open **Apps › Forecast › Boards**. Pick the board, then **Quarterly**, **Monthly** or **Weekly**, and the period.
2. Expand your row to see each rep's **Target Attainment**, **Pipeline Coverage**, **Commit Forecast** and **Most Likely Forecast**, with the change since last week.
3. Click a manager's name to drill into that team, and use the back arrow to return.
4. Open a rep's submission drawer. Add a manager-level adjustment to **Commit** and a comment explaining it.
5. In the deal tabs, accept or dismiss each suggested category move.

<figure>

![Forecast Boards tab in monthly view for October. A leader's row sits at the top, a manager's row is expanded, and five reps appear indented beneath it, each with target attainment against target, pipeline coverage, commit forecast and most likely forecast, with changes in green or red.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/forecast/oliv-ai_162_forecast_boards-tab_monthly-view-manager-row-expanded-brian-davis-team-jordan-lee-alice-roberts-sarah-reed-kevin-turner.webp)

<figcaption>Expanding a manager's row puts each rep's number next to the team roll-up, so the forecast conversation follows the same rep order as the review.</figcaption>
</figure>

<figure>

![Forecast board drilled into one manager's team. The manager is pinned as the top row with a back arrow, and six reps are listed below with target attainment, pipeline coverage, commit forecast and most likely forecast for the month.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/forecast/oliv-ai_163_forecast_boards-tab_monthly-view-drilled-into-brian-davis-team-back-arrow-reps-attainment-coverage-commit-most-likely.webp)

<figcaption>Drilling in narrows the board to one manager's team, which is the view a first-line manager walks through rep by rep.</figcaption>
</figure>

<figure>

![Best Case Deals tab of a manager's submission drawer. A group titled Move Down to Pipeline lists three deals with a total, each with stage, next step, a red risk reason and a dark Pipeline button with a down arrow. A second group, Move up to Most Likely, starts below with an up-arrow button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/forecast/oliv-ai_168_forecast_submission-drawer_brian-davis_best-case-deals-tab_move-down-to-pipeline-3-deals-230000-and-move-up-to-most-likely-with-risk-reasons.webp)

<figcaption>Suggested moves go both ways, down for stalled deals and up for ready ones, and each carries the risk reason to raise with the rep.</figcaption>
</figure>

Forecaster's **Weekly Forecast** in **My Reports** then compares the team's forecast with the AI forecast and lists the deals likely to slip. The [Oliv Forecast overview](https://www.oliv.ai/oliv-forecast) covers the forecasting side in more depth.

## Step 6: Let follow-through run {#step-6-follow-through}

After the review, the agents keep the agreed next steps moving:

- **Rep nudges.** Deal Driver nudges reps directly when deals stall, next steps go overdue or activity drops, before you need to step in.
- **Evening voice check-in (Beta).** Each evening, Oliv AI's Voice Agent (Beta) reaches out to team members with targeted questions. They answer by voice, with no forms to fill in.
- **Sunset Summary.** Every weekday evening, Deal Driver recaps wins, risks and next-step gaps: deals won or lost, meetings held and their outcomes, deals newly flagged at risk and open situations to follow up. It also notes whether the day's meetings were recorded.
- **Monday Pipeline Review.** The week starts with a ready-to-review summary of every deal for leadership, prepared before the first standup.

## What a pipeline review with Oliv AI is {#what-it-is}

A pipeline review with Oliv AI is your usual deal review, with the preparation done by agents. Oliv AI's Deal Driver agent keeps managers informed at every level, from individual rep to deal to the full team. It runs on a daily and a weekly rhythm:

| Rhythm | What arrives | When |
|---|---|---|
| **Morning Brief** | Today's team meetings, meetings worth joining, priority deals | Every weekday morning |
| **Live alerts** | A deal, its signal, context and a suggested action | When something needs attention |
| **Sunset Summary** | Wins, losses, meeting outcomes, new risks, next-step gaps | Every weekday evening |
| **One-on-One Prep** | Each rep's pipeline by status, with a summary and next step per deal | On each rep's schedule, such as every Thursday |
| **Pipeline Review** | Every deal in the pipeline by status, for executive updates | Every Monday |

Each report opens in **Reports › My Reports** with a date picker to page through past editions and **Rate this report**. The same structure works for BDR and AE teams. Cadence and field configurations differ, but the briefs, alerts and rep reports work the same way.

## Why a pipeline review with Oliv AI matters {#why-it-matters}

### What it's for {#what-its-for}

A pipeline review is where a manager decides which deals need help this week. With the prep done ahead of time, the meeting goes on those decisions. The status part is already on the page when the meeting starts.

### How it helps {#how-it-helps}

- **Reports arrive before the meeting.** Each rep's pipeline view is ready before the 1:1, with nothing to pull.
- **Risk shows up early.** Alerts fire when deals stall or stages drift, not when a rep finally mentions it.
- **Every alert suggests a move.** The deal, the signal and a suggested action come together.
- **Follow-through doesn't depend on memory.** Reps get nudged when next steps go overdue.

### What happens without it {#without-it}

Without prep, the first twenty minutes of each 1:1 go on status updates. A deal can go quiet for two weeks or more before anyone notices. By the time the rep escalates, momentum is gone and the deal is hard to save.

### Why buyers care {#why-buyers-care}

This matters to first-line sales managers and BDR leads, who run these reviews every week. It also matters to VPs of Sales and regional heads, who inherit the numbers. It counts most in the last weeks of a quarter, when a missed slip changes the forecast.

## The Oliv AI approach to pipeline reviews {#approach}

{/* 5P */}

Picture a first-line sales manager with six reps and a standing Thursday review. It runs ninety minutes, about fifteen per rep. The goal is to go deal by deal and leave with a clear next step on every opportunity that's slipping.

Most managers prep by pulling a CRM report per rep and reading recent call notes. In the meeting, reps often walk through every deal, including the healthy ones. The time tends to run out before the stuck deals get real attention.

Most of that time is lookup, not judgment. Which deals went quiet, which close dates moved and which fields are blank are all facts the system already holds. Hand the lookup to an agent, and the meeting can start at the problem deals.

Oliv AI's Deal Driver agent does the lookup before Thursday. Each rep's prep report lands before the manager's first meeting, with deal health, activity and flagged items. Alerts through the week mark the deals that changed. After the review, nudges keep the agreed next steps from slipping. The manager spends the fifteen minutes per rep on the two or three deals that need a decision, and the healthy ones get a nod.

Every alert includes the deal, the signal, relevant context and a suggested action for the manager. How other platforms support a weekly pipeline review is covered in How a pipeline review with Oliv AI compares, below.

## How a pipeline review works with other features {#works-with}

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) refreshes deal fields overnight from calls, emails and meetings. Deal Driver then flags risk from what actually happened, not from stale entries. It also supplies the Core 4 Fields completion data behind the gap alerts.

### Meeting support for reps {#with-meeting-support}

Before every meeting on an active opportunity, reps get a brief with the deal summary, qualification status, stakeholders and an agenda. After the call, the [follow-up email is drafted](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) and [CRM updates are proposed](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/). Account executives see this in [running deals with Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Olivia for reps {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) is the front-facing agent for reps, while Deal Driver is the manager's tool. Reps work with Olivia day to day, and the manager sees the outcome in the review. During the review, the **Ask** button on the Forecast board opens Olivia beside it.

### Portfolio Manager for customer success {#with-portfolio-manager}

Customer success managers have an equivalent: Oliv AI's Portfolio Manager agent. It applies the same manager-visibility model to the renewal and retention book instead of the pipeline.

### Agent permissions {#with-tools}

Agents that update records or send email do it through tools. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains how to make those actions wait for approval.

## Who runs pipeline reviews with Oliv AI, and how {#who-uses-it}

These are typical patterns, shown to illustrate how teams use the review rhythm.

### Sales managers {#sales-managers}

A sales manager reads each rep's prep report over coffee and lists the flagged deals. The review covers only those, and standups get shorter because the morning brief already covers the day. The [sales manager's daily guide](https://www.oliv.ai/blog/oliv-ai-sales-manager-daily-use-guide-features) walks through the rest of the week.

### BDR leads {#bdr-leads}

A BDR lead runs the same review on an outbound pipeline. The morning brief, rep alerts and rep reports work the same way, with cadence and fields set for the BDR motion.

### VPs of Sales and regional heads {#sales-leadership}

A VP of Sales starts the week with the Monday Pipeline Review instead of stitching leadership reviews together by hand. Flagged deals point at the conversations worth having with each manager. It pairs with a habit of [evidence-based forecast commits](https://www.oliv.ai/blog/run-evidence-based-forecast-commits).

### Revenue operations {#revenue-operations}

A RevOps lead sets the inactivity windows and field completion rules with each manager, so alerts match how the team sells. Clean fields from CRM Manager keep those alerts honest. It's a practical step toward [better forecast accuracy](https://www.oliv.ai/blog/improve-sales-forecast-accuracy-with-ai).

## How a pipeline review with Oliv AI compares {#compare}

Oliv AI delivers a pipeline report for each rep before the week's 1:1s and nudges reps when next steps go overdue. It also prepares a Monday pipeline summary for leadership before the first standup. Oliv AI is the only platform in this table that does all three.

Pipeline review support, from each platform's public documentation:

| Platform | Per-rep pipeline report before each 1:1 | Rep nudges when next steps go overdue | Monday pipeline rollup for leadership |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([board to check before 1:1s](https://help.gong.io/docs/recipe-focus-on-deals-that-need-your-attention)) | Partly ([overdue to-do filter](https://help.gong.io/docs/find-and-organize-your-to-dos)) | Partly ([weekly digest from a deal board](https://help.gong.io/docs/faqs-for-deals)) |
| **Outreach** | Partly ([pipeline summary per rep](https://support.outreach.io/support/solutions/articles/159000425547-sales-manager-workflows-for-rep-coaching-and-1-1-s)) | Partly ([overdue tasks in reports](https://support.outreach.io/support/solutions/articles/159000423739-outreach-insights-sequence-performance-report-overview)) | Partly ([forecast rollup for managers](https://support.outreach.io/support/solutions/articles/159000425492-how-to-use-the-forecast-rollup)) |
| **Avoma** | Not in docs | Not in docs | Partly ([forecast board you open](https://help.avoma.com/know-your-forecast-board)) |
| **Fireflies.ai** | Not in docs | Not in docs | Not in docs |
| **Fathom** | Not in docs | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for pipeline reviews {#compare-stronger}

- **Each rep's report arrives on its own.** Oliv AI's Deal Driver agent prepares a report for each rep on that rep's schedule, before the 1:1. [Gong recommends checking a deal board weekly, particularly before 1:1s and pipeline reviews](https://help.gong.io/docs/recipe-focus-on-deals-that-need-your-attention). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Overdue next steps reach the rep.** Deal Driver nudges reps directly when next steps go overdue. [Outreach reports count incomplete tasks at least one calendar day overdue](https://support.outreach.io/support/solutions/articles/159000423739-outreach-insights-sequence-performance-report-overview). See [how Outreach compares with Gong](https://www.oliv.ai/blog/gong-vs-outreach).
- **A summary prepared for leadership.** Oliv AI's Monday Pipeline Review is ready before the first standup. [Avoma's forecast board is viewed by deal stage or forecast category](https://help.avoma.com/know-your-forecast-board). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **A rollup built for the week, not a board subscription.** Oliv AI prepares the Monday summary for leadership automatically. [Gong subscribers receive a weekly digest of deals through the deal board](https://help.gong.io/docs/faqs-for-deals). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Data quality sets the ceiling.** Deal Driver's signals are only as good as the CRM data behind them. Run Oliv AI's CRM Manager agent alongside it.
- **Deal Driver doesn't write to the CRM.** It surfaces signals for the manager to act on. Field updates belong to CRM Manager.
- **It isn't the forecast.** Pipeline projection and accuracy belong to [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/).
- **It isn't coaching.** Rep development belongs to [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/).
- **Customer success uses a different agent.** CS managers use Oliv AI's Portfolio Manager agent for the renewal book.
- **Set-up takes about a week.** Most managers are live within a week of connecting the CRM and calendar.
- **Voice check-ins are Beta.** The evening voice check-in is part of the Voice Agent (Beta).

## Common questions {#common-questions}

#### When does the per-rep report arrive? {#faq-report-timing}

On each rep's schedule, such as every Thursday, before the manager's 1:1 with that rep. It covers deal health, activity levels, stuck deals and what to focus on next week.

#### Will this replace my daily standup? {#faq-standup}

For many teams, yes. When the morning brief surfaces what's new, the standup becomes a strategy conversation instead of a status check. Some managers drop it.

#### Can I change what triggers an alert? {#faq-alert-thresholds}

Yes. Inactivity windows, field completion requirements and deal value thresholds can be set per manager or per team.

#### What's in each alert? {#faq-alert-contents}

The deal, the signal, the relevant context and a suggested action for the manager.

#### Does it work for BDR teams? {#faq-bdr}

Yes. Sales managers and BDR leads use it the same way. Cadence and field configurations differ, but the structure is the same.

#### What does leadership get? {#faq-leadership}

The Pipeline Review every Monday: a full view of every deal in the pipeline, sorted by status, prepared before the first standup.

#### Do reps need to do anything differently? {#faq-reps}

No. Deal Driver works in the background. Reps see it as follow-up prompts and next-step reminders.

#### Where do briefs and reports arrive? {#faq-channels}

In **Reports › My Reports**, under the agent that writes each one. Alerts and summaries can also reach managers through Slack or email.

#### Can I look back at last week's report? {#faq-past-reports}

Yes. Each report has a date picker with previous and next arrows, so you can page back through past editions.

#### What happens after the review? {#faq-after-review}

Reps get nudges when deals stall or next steps go overdue. The Sunset Summary and the Monday Pipeline Review keep the manager and leadership current.

#### Is there an equivalent for customer success? {#faq-customer-success}

Yes. Customer success managers use Oliv AI's Portfolio Manager agent, which applies the same model to the renewal and retention book.

## Related {#related}

- [Deal Driver agent guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): every alert, brief and report the agent sends.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Olivia agent guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): the agent reps work with day to day.
- [Account executive guide to running deals](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): the rep side of the same pipeline.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): control which agent actions need approval.
- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the brief reps get before each call.
- [Agentic forecasting webinar](https://www.oliv.ai/leadership-webinar): how leaders move forecasting to agents.
- [Deal intelligence software](https://www.oliv.ai/blog/deal-intelligence): how AI predicts pipeline risk.
- [Pipeline analytics software](https://www.oliv.ai/blog/pipeline-analytics-software): tools for stage and coverage analysis.
- [Why the board deck takes all weekend](https://www.oliv.ai/blog/sales-forecast-accuracy-cro): a CRO's guide to forecast accuracy.
