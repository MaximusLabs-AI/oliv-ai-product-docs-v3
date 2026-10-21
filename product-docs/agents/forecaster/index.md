# Forecaster agent

How Oliv AI's Forecaster agent drafts each rep's forecast, flags the deals that don't add up, learns from closed deals, and how it compares with other sales forecasting software.

- Applies to: Sales leaders, sales managers, revenue operations and quota-carrying reps
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/

Oliv AI's Forecaster agent automates the forecasting process, from collecting deal data to analyzing each deal to the manager's sign-off. It reads your pipeline and builds the forecast before anyone logs in, so reps review and submit instead of typing. It gets more accurate over time by learning from how deals actually close at your company.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Drafts the forecast, pressure-tests every category and rolls it up for leadership |
| **Who it's for** | Sales leaders, sales managers, RevOps and quota-carrying reps |
| **Cadence** | Weekly by default, configurable to monthly or quarterly, with several running in parallel |
| **Forecast categories** | Forecast, Commit, Best Case and Pipeline |
| **Views** | Rep, manager, and admin or observer |
| **Learns from** | Closed deals, pushed deals and your team's feedback on its signals |
| **You connect** | Your CRM: [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho |

## What the Forecaster agent is {#what-it-is}

Oliv AI's Forecaster agent is a forecasting agent for revenue teams. It analyzes every deal in the pipeline against historical performance, company patterns and deal progression signals. It doesn't move deals or change stages itself. It recommends and nudges, and people make the call.

### Three views of the same forecast {#three-views}

- **Rep view.** A pre-drafted forecast across Forecast, Commit, Best Case and Pipeline, with recommended adjustments. The rep reviews, adjusts if needed, and submits.
- **Manager view.** Each rep's submission, with room for separate manager-level adjustments. Managers mark each forecast as reviewed and see the rolled-up team number.
- **Admin or observer view.** Read-only access to the forecast board for executives and RevOps, plus targets, measurements and board settings.

### The signals it raises {#signals}

| Signal | What it tells you |
|---|---|
| **Deal movement** | A deal can move between categories, such as from Best Case to Commit, based on recent progression |
| **Value adjustment** | The likely value differs from the entered amount, based on historical close rates and trajectory |
| **Risk** | A deal has stalled and may not close in the period, flagged for review |
| **Pipeline health** | Coverage for a period is below target, with a recommended fix |

Reps and managers can accept, edit or reject each signal. That feedback trains the agent.

## Why the Forecaster agent matters {#why-it-matters}

### What it's for {#what-its-for}

Oliv AI's Forecaster agent is for teams that want a number they can stand behind on Monday. It takes over the building of the forecast, so people spend their time judging it.

### How it helps {#how-it-helps}

- **Reps stop typing updates.** They open a forecast that is already filled in, check it and submit.
- **Managers review changes, not everything.** Risky commits, sandbagged upside and dead deals are flagged before the call.
- **Leaders see decisions.** The rollup shows what slipped, what moved and why.
- **Accuracy compounds.** Every closed deal makes the next forecast better.

### What happens without it {#without-it}

Without it, the forecast is only as good as each rep's mood that week. Leadership sees a number with no trail behind it: no signals, no reason for the change since last week. A slipping deal shows up when the quarter is already lost, not while there is still time to act.

### Why buyers care {#why-buyers-care}

VPs of Sales, CROs and RevOps leads buy it. The VP of Sales champions it because the weekly rollup burden goes away. RevOps backs it because clean data feeds the model. It pays off most for teams with five or more reps and at least one manager layer.

## The Oliv AI approach to the Forecaster agent {#approach}

{/* 5P */}

It's the last week of the quarter, and a VP of Sales has her commit call with the CRO on Friday. Five managers report to her, each carrying a team number. The CRO wants one figure she can defend, plus the short list of deals it depends on.

The usual run-up is a round of rep updates, manager check-ins and a rollup sheet that comes together late on Thursday. Across a team, that routine can swallow a dozen hours in a week. Even then, the number tends to lean on how hopeful each rep felt.

Yet most of what the commit needs already sits in the pipeline and the calls. Close dates slip, stages stall and deals go quiet, and each of those leaves a trail. The hard part is reading that trail across every deal, every week, without waiting on people.

Oliv AI does that reading with its Forecaster agent. It drafts each rep's forecast before anyone logs in and checks it before the call starts. It flags risky commits, surfaces sandbagged upside and removes dead deals. Managers review only what changed, and the VP gets one rolled-up view with the risk already called out.

Every Monday, an automatic snapshot captures the whole pipeline, so each commit can later be checked against what actually closed. How that learning loop lines up against other forecasting tools is covered in How the Forecaster agent compares, below.

## Set up Forecaster {#set-up}

1. **Connect your CRM.** [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho. Forecaster reads stage, amount, close date and owner for every deal. See the [supported integrations](https://www.oliv.ai/integrations).
2. **Load your roster.** Add reps and managers with the team hierarchy, so forecasts roll up to the right person.
3. **Set targets.** Admins create targets and allocate them quarterly or monthly per rep.
4. **Define your cadence.** Weekly by default, or monthly or quarterly. Settings that configure the Forecaster sit under **Settings › Organisational Settings**.
5. **Add measurements if you need them.** Metrics can be field-mapped or formula-based, such as a pipeline coverage formula.

Most teams are live within two weeks. Reps need no training: they see a pre-drafted view where they'd normally submit by hand.

## Run the weekly forecast {#run-the-forecast}

### For reps {#rep-workflow}

See your target for the period, then review the forecast computed from your pipeline. Check Forecaster's recommended signals, adjust anything you disagree with, and submit with a comment explaining any changes. It takes about 5 to 10 minutes.

### For managers {#manager-workflow}

See every rep's submission at a glance. Review each one against Forecaster's flagged concerns, add your own manager-level adjustments, and mark it reviewed. Then check the rolled-up team forecast. For a team of 5 to 10, that's about 15 to 30 minutes in total. Teams that run [evidence-based forecast commits every Monday](https://www.oliv.ai/blog/run-evidence-based-forecast-commits) start from this rolled-up view.

### Several cadences at once {#cadences}

Monthly, quarterly and pipeline forecasts can run in parallel, each with its own targets and rollup views. If you forecast quarterly but want monthly visibility, Forecaster can show a monthly equivalent of the quarterly number. Weekly manager calls, monthly reviews and quarterly board forecasts all run from the same signals, targets, rollups and snapshots in [Oliv Forecast](https://www.oliv.ai/oliv-forecast).

## Snapshots and how it learns {#snapshots-and-learning}

Every submission creates a timestamped record. Every Monday, an automatic snapshot captures the whole pipeline. When deals close or push, Forecaster compares the forecast value to the actual outcome.

That reconciliation trains the agent. Over time it learns company-specific patterns, such as a deal type that always needs an RFP or a rep who runs two weeks optimistic on timelines. Feedback on its signals trains it too. More on [improving forecast accuracy with AI](https://www.oliv.ai/blog/improve-sales-forecast-accuracy-with-ai).

### Operating modes (Beta) {#operating-modes}

Forecaster's operating modes (Beta) let it take over more of the process as it learns your patterns.

- **AI-Assisted (Beta).** Forecaster recommends and your team decides. Managers see where the agent and the rep disagree.
- **AI-Managed (Beta).** Forecaster generates the full forecast, and your team reviews and adjusts. Reps are largely hands-free.
- **AI-Owned (Beta).** Forecaster produces the forecast, and managers review only flagged areas of uncertainty. No rep involvement is needed.

Teams typically move through all three operating modes (Beta) within 6 to 18 months. Managers stay in the loop in every mode.

### Where results go {#where-results-go}

Forecast submissions, snapshots, signals and adjustments are kept in Oliv AI. If configured, Forecaster syncs the forecast category and adjusted values back to your CRM. Managers get a weekly team forecast summary with flagged deals in [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) or email.

## How Forecaster works with other agents {#works-with}

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) is the data foundation. It pulls from call transcripts and meeting notes to keep stage, close date and amount current, so Forecaster builds from today's deal state. Read why [clean CRM data drives predictability](https://www.oliv.ai/blog/crm-data-strategy-cro-revenue-predictability).

### Deal Driver {#with-deal-driver}

Forecaster surfaces deals that don't add up, such as closing-date conflicts. [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) fills in the context: last touchpoint, open next steps and days since last activity. A manager can review the flagged items in minutes instead of reading the whole pipeline.

### Oliver {#with-oliver}

When leadership needs a cross-deal breakdown, such as why one segment is lagging, [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) runs it. Oliver uses the structured data layer that Forecaster and CRM Manager maintain.

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) is the front-facing master agent for reps. Forecaster stays in the background, drafting the forecast each rep reviews.

## Who uses Forecaster, and how {#who-uses-it}

### Sales leaders {#sales-leaders}

VPs of Sales and CROs get one forecast view, split by motion, with risk already called out. Leadership sees what moved, what slipped and where the gap is before the commit call. More in [Oliv AI for sales leaders](https://www.oliv.ai/blog/oliv-ai-sales-leader-vp-sales-agent-features) and a [CRO's guide to forecast accuracy](https://www.oliv.ai/blog/sales-forecast-accuracy-cro).

### Sales managers {#sales-managers}

Managers review submissions, add their own adjustments and sign off. They spend time on the deals Forecaster flagged, not the whole board. Pair it with the manager visibility in the [Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/). See Oliv AI for [sales managers](https://www.oliv.ai/sales-managers).

### Revenue operations {#revops}

RevOps configures cadences, targets and metrics during onboarding and watches forecast against actual to spot systematic bias. Learn how Oliv AI works for [revenue operations teams](https://www.oliv.ai/revops).

### Account executives {#account-executives}

Reps open a pre-filled forecast, adjust a deal or two and submit in minutes. The rest of their week is in [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## How the Forecaster agent compares {#compare}

Most forecasting tools give reps a board to fill in. Forecaster drafts the rep's forecast, raises signals you accept, edit or reject, and learns from every closed deal, across monthly and quarterly forecasts at once. Oliv AI is the only platform in this table that does all four.

Forecasting features, from each platform's public documentation:

| Platform | Rep's forecast pre-drafted | Signals to accept, edit or reject | Learns from your closed deals | Monthly and quarterly in parallel |
|---|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes | Yes |
| **Gong** | [Rep submits each number](https://help.gong.io/docs/forecast-update-your-forecast) | Partly ([suggested updates in one column](https://help.gong.io/docs/set-up-forecast-boards)) | Yes ([trained on historical deal outcomes](https://help.gong.io/docs/understanding-ai-deal-predictor)) | Yes ([monthly, quarterly or both](https://help.gong.io/docs/configurable-forecast-article-1)) |
| **Outreach** | [Manager edits and submits the call](https://support.outreach.io/support/solutions/articles/159000425492-how-to-use-the-forecast-rollup) | Partly ([risk signals in rollup, Beta](https://support.outreach.io/support/solutions/articles/159000420906-how-to-configure-risk-signals-in-forecast-rollup-beta-)) | Not in docs | Yes ([parallel forecasts](https://support.outreach.io/support/solutions/articles/159000426069-creating-and-editing-forecasts-in-outreach)) |
| **Avoma** | [Reps enter their submission](https://help.avoma.com/forecast-submission-and-history) | Partly ([forecast risk alerts in Slack](https://help.avoma.com/slack-integration-setup-guide)) | Not in docs | Partly ([one period for the whole org](https://help.avoma.com/forecast-settings)) |
| **Fireflies** | Not in docs | Partly ([deal risks flagged early](https://guide.fireflies.ai/articles/6941626485-getting-started-with-fireflies-crm-deal-intelligence)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for the Forecaster agent {#compare-stronger}

- **The forecast is built before anyone logs in.** Forecaster pre-drafts each rep's forecast, so reps review and submit in minutes. In Gong, a panel opens where [you submit your number for the selected category](https://help.gong.io/docs/forecast-update-your-forecast). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **Every signal is a decision you control.** Reps and managers accept, edit or reject each Forecaster signal, and the agent learns from the choice. Avoma sends [forecast risk alerts to Slack with its Revenue Intelligence add-on](https://help.avoma.com/slack-integration-setup-guide). Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Learning comes from your own outcomes.** Forecaster compares each forecast with what closed and learns your company's patterns. Outreach's Scenario Planner [simulates forecast projections from inputs you review and adjust](https://support.outreach.io/support/solutions/articles/159000425531-overview-of-forecasting-and-pipeline-management). Read [how Gong and Outreach compare](https://www.oliv.ai/blog/gong-vs-outreach).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **It recommends, it doesn't move deals.** Forecaster doesn't change deal stages. It recommends and nudges.
- **It isn't deal scoring.** Oliv AI's Deal Insights layer evaluates deal health, and Forecaster consumes those insights.
- **It isn't a real-time alert tool.** Deal Driver handles alerts on deals as they happen.
- **It isn't a coaching tool.** Coach handles rep development.
- **It's only as good as the data.** CRM Manager should be active so deal fields are current before Forecaster analyzes them.
- **Operating modes are Beta.** AI-Assisted, AI-Managed and AI-Owned are all labeled Beta.

## Common questions {#common-questions}

#### How long before Forecaster can run without my input? {#faq-time-to-autonomy}

It depends on your sales cycle. For 3 to 6 month cycles it's usually 6 to 9 months, and for 12 month enterprise cycles, 12 to 18 months. Time savings show up from week one.

#### What if Forecaster makes a bad recommendation? {#faq-bad-recommendation}

You reject it. Forecaster learns from that, and every decision you make helps it recognize your company's patterns.

#### What if a rep or manager disagrees with a signal? {#faq-disagree}

They override it. The system learns from that feedback and adjusts future recommendations.

#### Can we run monthly and quarterly forecasts at the same time? {#faq-cadences}

Yes. Forecaster supports several cadences in parallel, each with separate targets and rollup views.

#### Does this replace my CRM forecast field? {#faq-crm-field}

No. Forecaster can sync values back to the CRM if you configure it, but it's primarily Oliv-based. The CRM stays current without anyone updating it by hand.

#### How is this different from built-in CRM forecasting? {#faq-crm-forecasting}

CRM forecasting relies on reps keeping fields updated by hand. Forecaster removes that dependency by analyzing the pipeline itself and getting smarter every week.

#### We already have a pipeline visibility tool. Do we still need Forecaster? {#faq-existing-tools}

Visibility tools show you the pipeline. Forecaster removes the manual work of building the forecast, which is a different problem. Many teams run it alongside their existing tools.

#### How does setup work? {#faq-setup}

Connect your CRM, set targets and define your cadence. Most teams are live within two weeks, with no rep training.

#### What if our CRM data is messy? {#faq-messy-crm}

Forecaster works with [CRM Manager](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) to keep the pipeline current. If data is incomplete, CRM Manager improves it as it goes, so you don't need a clean CRM to start.

#### Is there a minimum team size? {#faq-team-size}

It delivers the most for teams with five or more reps and at least one manager layer. Smaller teams get the time savings straight away.

#### Does Forecaster send anything to managers? {#faq-notifications}

Yes. Managers get a weekly summary of the team forecast with flagged deals, in [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) or email.

## Related {#related}

- [Forecaster on oliv.ai](https://www.oliv.ai/agents/forecaster): the agent's own page, with its operating modes.
- [The Oliv Forecast app](https://www.oliv.ai/oliv-forecast): forecast boards, deal inspection and scenario modelling.
- [The Monday rollup, retired](https://www.oliv.ai/blog/ai-revenue-forecasting-software): how agentic forecasting replaces the weekly scramble.
- [AI sales forecasting software compared](https://www.oliv.ai/blog/best-ai-sales-forecasting-software): what to weigh across tools.
- [Agentic forecasting webinar](https://www.oliv.ai/leadership-webinar): moving to agent-led forecasting.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): how approval settings work for agent actions.
- [Oliv AI pricing](https://www.oliv.ai/pricing): plans and what each includes.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
