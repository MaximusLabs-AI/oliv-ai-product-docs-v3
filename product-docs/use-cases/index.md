# AI for sales teams: find your revenue role and the agents and workflows to open first

AI for sales teams, role by role: which agents and workflows account executives, sales managers, SDRs, customer success, RevOps and enablement open first.

- Applies to: Account executives, sales leaders, SDRs, customer success, account managers, revenue operations and enablement
- Status: Live
- Verified: 2026-11-03
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/

You've been asked how AI for sales teams would work here, and the answer depends on who you ask: the rep carrying deals, the manager running the team, or the person who owns the CRM. Don't read these docs in order. If you own deals, open the [account executive use case](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/). If you manage people, open the [pipeline review guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/). If you run the systems, open [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) and the [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/).

## Find your revenue role and what to open first {#finding-your-role}

Find your role in the table, open the first page it names, and follow that page's links to the agents and workflows it depends on. Only account executives have a use case page, so every other role starts from a workflow or agent page. Oliv AI works as a layer on top of your CRM, so every role reads from the same record.

| If you | Open first | Agents you'll work with |
|---|---|---|
| Own deals as an account executive | The account executive use case | Meeting Assistant, CRM Manager |
| Manage a sales team | The pipeline review guide | Deal Driver, Forecaster, Coach |
| Book and run first calls as an SDR or BDR | The meeting preparation guide | Olivia, plus Deal Driver if you lead BDRs |
| Look after accounts in customer success or account management | The Olivia agent page | Olivia, CRM Manager, Portfolio Manager |
| Run the systems in revenue operations | The Oliver agent page, then the CRM upkeep guide | Oliver, CRM Manager, Forecaster |
| Ramp reps in enablement | The Coach agent page | Coach |

Before you send someone a page, check what they would see. On **Home**, open the **Agent Feed** tab and set **Team** to Sales, Sales Development, Customer Success or RevOps. Where the **Role** filter shows, set it to Contributor or Manager. The feed then lists the agents that person uses and the updates those agents posted.

## Which AI agents do account executives work with? {#account-executives}

If you carry deals and your calendar is full of customer meetings, open the [account executive use case](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/) first. It shows how the pieces fit across a deal, so you see the whole job before any single agent.

Oliv AI's Meeting Assistant agent sends a brief before each meeting on an active opportunity, then drafts the follow-up after the call. Oliv AI's CRM Manager agent turns what was said into field updates you approve. Check that your meetings are linked to active opportunities, because Meeting Assistant works only on those. A meeting with no linked opportunity gets no brief.

<figure>

![Home on the Agent Feed tab with Team set to Sales and Role to Contributor. The Agents list ticks Olivia, Prospector, Deal Assistant, Gold Digger and CRM Manager, and six updates appear under TODAY, from Olivia's morning brief to a CRM Manager field-update summary.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_030_home_agent-feed_team-sales-role-contributor_filters-and-today-timeline-six-updates-olivia-prospector-meeting-assistant-gold-digger-crm-manager.webp)

<figcaption>The account executive's view: the agents that prep meetings, find accounts and keep the CRM current all report into one feed.</figcaption>
</figure>

Next, read the [Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) and [CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) pages, in that order. Use the [recording and follow-up guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) for what happens after each call.

## Which AI agents do sales managers work with? {#sales-leaders}

If you run a team and your week turns on pipeline reviews, 1:1s and a forecast number, open the [pipeline review guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) first. It puts three agents together in one weekly meeting. Skip it and you get three agent pages with no meeting to connect them.

You work from the same deals as your reps, seen at team level. Oliv AI's Deal Driver agent sends a morning brief, an alert when a deal needs attention, and a prep report for each rep before their 1:1. Oliv AI's Forecaster agent pre-drafts each rep's forecast, and you add your adjustments before the team number rolls up. Oliv AI's Coach agent scores every recorded call and recommends three goals per rep each month, and you set one.

<figure>

![Home on the Agent Feed tab with Team set to Sales and Role to Manager. Three updates appear under TODAY: Olivia's morning brief, a Forecaster post that four deals shifted forecast categories overnight, and an Oliver note on stalled Proposal deals.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_024_home_agent-feed_team-sales-role-manager_olivia-brief-forecaster-category-shifts-oliver-stalled-proposal-update.webp)

<figcaption>Switching the role to Manager adds the forecast and process agents to the feed, which is the team-level view this section describes.</figcaption>
</figure>

Once the meeting makes sense, open the [Deal Driver](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), [Forecaster](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) and [Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) pages.

## Where do SDRs and BDRs start with AI agents? {#sales-development}

If you book and run first calls, preparation and capture matter most, so open the [meeting preparation guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) first. Oliv AI's Olivia agent researches the company and the person before a first meeting, and the guide shows that brief. Then check the [Zoom integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/), which records those calls, whoever hosts them.

If you lead BDRs, add Oliv AI's Deal Driver agent. Its briefs and reports work across BDR and AE pipelines, so you use it the same way sales managers do.

## Which AI agents do customer success managers work with? {#customer-success}

If you look after a book of accounts and need the history before a call, open the [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) page first. Oliv AI's Olivia agent has the full account history ready before every call, and the page shows how to ask her for it. Oliv AI's CRM Manager agent tracks renewals, QBRs and CS check-ins as well as sales cycles.

When you take over an account, start with the recorded handover call, which gives you its summary and next steps. If your team runs its day from a shared channel, set up the [Slack integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/). If a customer asks for no meeting bot, check who organizes the call before you agree, because Oliv AI records botlessly when your company organizes it.

If you manage the team, add [Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager). It's the customer success equivalent of Deal Driver, applied to the renewal book, and in your feed it posts the 1:1 agenda with the accounts at renewal risk. Read more for [customer success](https://www.oliv.ai/customer-success) and [account management](https://www.oliv.ai/account-management) teams.

<figure>

![Home on the Agent Feed tab with Team set to Customer Success and Role to Manager. The Agents list ticks Oliver and Portfolio Manager. Under YESTERDAY, Portfolio Manager posts a 1:1 agenda covering accounts with renewal risk, and Oliver posts two updates on renewals and stalled deals.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_029_home_agent-feed_team-customer-success-role-manager_yesterday-group-portfolio-manager-1-1-agenda-oliver-renewal-and-process-updates.webp)

<figcaption>For a customer success manager, the feed leads with renewal risk: the 1:1 agenda and the account patterns worth acting on.</figcaption>
</figure>

## How does RevOps use AI agents day to day? {#revops}

If you set the rules and keep the data clean, open [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) first. It keeps the process handbook: your ICP, personas, approval workflows and sales methodology. Then open the [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) and [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/), which cover how updates reach the right fields. The [Salesforce integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) page covers the install.

Day to day, work from the RevOps feed. It shows Oliver's review with changes ready to approve, the count of updates Oliv AI's CRM Manager agent applied and held for review, and category shifts from Oliv AI's Forecaster agent.

<figure>

![Home on the Agent Feed tab with Team set to RevOps, with Oliver, CRM Manager and Forecaster ticked and Timeline set to Today. Three updates appear: Oliver's quarterly revenue review with playbook and agent changes to review, CRM Manager's field updates from the day's calls, and Forecaster's overnight category shifts.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_027_home_agent-feed_team-revops_filters-and-today-timeline_oliver-q3-revenue-review-crm-manager-field-updates-forecaster-category-shifts.webp)

<figcaption>RevOps sees the process, data and forecast agents side by side, with each change that needs a decision flagged for review.</figcaption>
</figure>

When an agent starts at the wrong moment, check its [agent triggers](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/). When you need to know what an agent did, open [run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/), which shows each run. If you're planning a rollout, start with [plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) so each person gets the seat they need.

## Where do enablement managers start with AI agents? {#enablement}

If you ramp reps and keep training current, open the [Coach page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) first. It shows how call scores turn into one goal per rep each month. Then use the [clip library](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) to collect the moments you describe, such as pricing objections, from real calls. Add the background reading an agent works against, such as a buying-committee profile or a solution deck, to its [agent knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/).

## What to open after your first page {#how-docs-are-organized}

When your first page leaves you with a question, choose the next page by that question:

| Your question | Open |
|---|---|
| What does this agent do, and how do I set it up? | The agent's own page |
| How do I get one job done from start to finish? | A workflow guide, which follows the job across agents |
| What does Oliv AI do for my role? | Your role's section on this page |
| What connects to Oliv AI, and who needs which seat? | The integrations, apps and plans pages |

If someone on your team wants the wider case before they pick a role, send them the post on [AI for sales teams](https://www.oliv.ai/blog/ai-for-sales-teams).
