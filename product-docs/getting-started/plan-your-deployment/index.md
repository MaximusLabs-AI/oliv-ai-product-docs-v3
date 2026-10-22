# Plan your deployment

A 30-day plan for rolling Oliv AI out across sales and customer success, from choosing who runs the setup and lining up admin access to the first brief, the process handbook and the day-30 review.

- Applies to: Revenue operations leads planning an Oliv AI rollout
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/getting-started/plan-your-deployment/

Rolling Oliv AI out across sales and customer success takes about a month, and most of it runs in parallel. Reps get their first brief before their next meeting, while your process handbook and the manager agents come online over the following weeks. This guide gives revenue operations a week-by-week plan: who runs the setup, which admins you need, what to switch on first and what to check at day 30.

## At a glance {#at-a-glance}

| | |
|---|---|
| **Who plans it** | A revenue operations lead, with a sales or CS leader to sign off the handbook |
| **Set-up paths** | **You Run It** (2 to 4 sessions) or **We Run It** (live in 2 weeks) |
| **First value** | A brief 30 minutes before the next meeting on the calendar |
| **Process handbook** | Built with Oliv AI's onboarding team in 1 to 2 weeks |
| **Tailored models** | Live within 1 day of the proof of value kickoff |
| **Admins you need** | CRM, calendar or Microsoft 365, Zoom and Slack |
| **Rep training** | None for forecasting or deal alerts; reps keep working as they do now |

## Before you begin {#before-you-begin}

- **Name an owner.** One revenue operations lead runs the plan. A sales or leadership stakeholder checks the handbook for accuracy during onboarding.
- **Gather what you have.** Bring your existing handbook, playbooks and methodology decks, even if they're messy or incomplete. Oliv AI's onboarding team works from them.
- **Find your admins.** Some connections need an admin on the other side. The table in Step 2 lists who to book.
- **Decide your seat roles.** Each person gets the plan that fits their work. [Plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) helps you map your team before you invite anyone.
- **Don't clean the CRM first.** Oliv AI reads what's already there, messy data included.

## Step 1: Choose who runs the setup {#step-1-choose-a-path}

Oliv AI offers two set-up paths. Pick one before kickoff, because it decides how much of your team's time the rollout takes.

| | You Run It | We Run It |
|---|---|---|
| **Time to onboard** | 2 to 4 sessions | Live in 2 weeks |
| **Who maintains the playbooks** | Your revenue operations team, working with Oliver directly | Oliv AI's operators, on your behalf |
| **Prompts to write** | Yours to write and change | None |
| **Control** | Full control over every update | Updates handled for you |

Choose **You Run It** if your revenue operations team wants to own every rule change. Choose **We Run It** if the team is stretched and you'd rather review than build. Either way, [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) holds the result.

## Step 2: Line up admin access {#step-2-admin-access}

Book the admins you need in week one, so no connection waits on a calendar invite.

| Connection | Who you need | Why |
|---|---|---|
| **Salesforce** | A Salesforce admin | Installs the Oliv AI package for all users from the admin install link |
| **HubSpot** | Whoever connects the HubSpot integration | Connects it in the Oliv AI web app and shares the HubSpot URL |
| **Calendar** | Each user, by logging in to the Oliv AI web app | Required: without it, Oliv AI can't take notes in meetings |
| **Outlook add-in** | Your Microsoft 365 administrator, if add-ins are off | Add-ins for Outlook must be activated before people can install them |
| **Zoom** | A Zoom admin | Grants the permission that lets meetings record when the host isn't there |
| **Slack** | A Slack workspace admin, if your workspace needs approval | Approves the Oliv AI app or a Slack Connect channel |

If the Slack app or Slack Connect can't be approved in time, onboarding carries on and messages go by email until Slack is connected. The [Salesforce guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and the [Zoom guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) cover those two installs step by step.

## Step 3: Connect the stack in week one {#step-3-connect}

Connect the CRM first. Oliver needs it for schema alignment, and every agent reads pipeline and deal history from it. Salesforce, [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) and Zoho are supported.

Then connect calendars, your call recorder and Slack or Teams. Calendars tell Oliv AI which meetings are coming. The recorder is the main source of live context, whether that's Oliv AI's own notetaker or a tool you already use. Email is optional but adds context between meetings. Most teams are connected within a week, and the [integrations overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/) shows how each connection fits.

## Step 4: Build the process handbook {#step-4-handbook}

Oliv AI's onboarding team works with your revenue operations lead to translate existing playbooks, CRM configuration and methodology into Oliver's structured format. This typically takes one to two weeks. The handbook covers:

1. **Who you sell to.** Your ICP and the signals that qualify an account.
2. **Who you sell to inside each account.** Your persona library.
3. **How you qualify.** MEDDPICC, BANT, SPICED or your own framework, and the fields each stage requires.
4. **Who approves what.** Pricing desk triggers and the deal size where manager sign-off starts.
5. **How proofs of concept run.** What makes one eligible, what success looks like and how long it should last.
6. **How proposals and territories work.** Review steps, approvals and who owns which pipeline.

Your stakeholder checks each section for accuracy. Once it's in place, every agent works inside those rules from day one, and a change goes live only after a person signs it off.

## Step 5: Switch on first value for reps {#step-5-first-value}

Reps don't wait for the handbook to finish. [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) delivers deal context, risk and next steps 30 minutes before the next meeting on the calendar, with no waiting period. For meetings on an active deal, [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) adds qualification status and a recommended agenda, as the [meeting preparation guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) shows.

At the same time, start [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) in **Ask First** mode. From the first meeting, call or email it proposes updates, and each one waits for review before anything reaches the CRM. Your reps learn what it gets right while nothing changes without them.

## Step 6: Add managers and customer success {#step-6-managers}

In weeks two to four, bring the manager agents online. Each has its own set-up time:

| Agent | What you set | Typical time to live |
|---|---|---|
| **Deal Driver** | Connect the CRM and team calendar, then set alert thresholds | Most managers are live within a week |
| **Forecaster** | Set targets and define your forecast cadence | Most teams are live within two weeks |
| **Coach** | Pick pre-built scorecards or bring your own criteria | First monthly review within two weeks |
| **Portfolio Manager** | Connect CRM, recordings, email, calendar and engagement data | Depends on your integrations |

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) works in the background, so reps don't need to change anything. [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) needs no rep training; reps see a pre-drafted view where they'd normally submit by hand. [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) needs about ten calls per rep to find a real pattern. For customer success, Oliv AI's Portfolio Manager agent builds a briefing of each CSM's book before every scheduled 1:1.

## Step 7: Review at day 30 {#step-7-review}

1. **Check the CRM updates.** Look at what reps accepted and rejected. Once accuracy thresholds are met, revenue operations confirms the switch to auto mode, as the [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) explains.
2. **Read the first coaching review.** Coach's monthly review shows whether the scorecards match how you want calls run.
3. **Watch a pipeline review.** Managers should open their 1:1s with Deal Driver's report, as in the [pipeline review workflow](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/).
4. **Tell Oliver what changed.** Anything you learned in the month goes to Oliver as a process update, and every connected agent picks it up after sign-off.

## What a deployment plan for Oliv AI is {#what-it-is}

A deployment plan is the order in which you connect tools, build rules and switch on agents, so each team gets value as early as possible. Oliv AI splits it into two tracks that run at once.

| Track | What happens | Who's involved | When |
|---|---|---|---|
| **Value track** | Briefs, follow-ups and proposed CRM updates start flowing | Reps, from their first meeting | Week one |
| **Process track** | The handbook is built, models are tailored, manager agents switch on | Revenue operations, Oliv AI's onboarding team, managers | Weeks one to four |

The tracks meet in the handbook. Oliv AI's Oliver agent keeps the rules, and Oliv AI's Olivia agent runs inside them for every rep. Behind both, Oliv AI tailors its signal models to your company. It researches what you sell, takes in your enablement materials and writes tailored prompts, so each model surfaces only the signals that matter to your motion. A tailored version is live within 1 day of the proof of value kickoff. For the wider architecture, read the [RevOps guide to agentic AI](https://www.oliv.ai/blog/agentic-ai-implementation-revops-data-architecture).

## Why a deployment plan matters {#why-it-matters}

### What it's for {#what-its-for}

A plan puts the right agent in front of the right team in the right week. Reps see value early, and managers get agents built on rules you've agreed.

### How it helps {#how-it-helps}

- **Reps feel it first.** The first brief lands before the next meeting, so adoption starts on day one.
- **Admins are booked early.** CRM, Zoom and Slack approvals don't stall the rollout in week three.
- **Rules come before scale.** Managers get alerts and forecasts that follow one agreed process.
- **Trust is earned.** CRM updates start in review, and auto mode waits until the numbers say so.

### What happens without it {#without-it}

Without a plan, a rollout tends to switch everything on at once. Reps get alerts before the rules behind them are agreed. Managers see forecasts built on fields nobody mapped. The first impression is noise, and some teams never come back from that.

### Why buyers care {#why-buyers-care}

This matters most to revenue operations leads, who own the rollout and answer for its results. It matters to sales and CS leaders too, who need their teams working in it within the month. It counts most when the contract starts close to a quarter or renewal season, because there's no slack for a slow start.

## The Oliv AI approach to deployment {#approach}

{/* 5P */}

Say a revenue operations lead has just signed with Oliv AI for 25 account executives and a customer success team of eight. Leadership wants both teams using it by the end of the month. She has a methodology deck from last year, a CRM full of half-filled fields and one free afternoon a week.

The usual route is to clean the CRM, write the playbook down properly and then train everyone at once. Each of those steps can take weeks on its own. By the time they're done, the quarter has moved on and the team has lost interest.

Nothing about the agents needs a finished playbook before reps can start. A brief only needs a calendar, a recorder and a CRM. The rules can be built alongside, as long as someone owns them and nothing changes without sign-off.

Oliv AI runs both tracks for her. Reps get their first brief before their next meeting, while Oliv AI's onboarding team turns her deck into Oliver's handbook in one to two weeks. If she picks We Run It, Oliv AI's operators maintain the playbooks on her behalf.

The proof of value adds one more piece: a tailored version of Oliv AI is live within 1 day of kickoff. How other platforms handle setup and tailoring is covered in How deployment compares, below.

## How the deployment plan works with other features {#works-with}

### Seat roles {#with-seat-roles}

Plans are sold by role, so the rollout order often follows them. Account executives and CSMs on the deal apps come first, and managers follow as their agents switch on. [Seat roles explained](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/#seat-roles) shows which apps each person gets.

### Field mapping {#with-field-mapping}

Custom fields on your opportunity record need a home before CRM Manager can fill them. [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/) is set up during onboarding, alongside the handbook.

### Approval settings {#with-approvals}

Agents that write to your CRM, calendar or mailbox can ask before acting. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains how to keep early rollouts on approval and relax it later.

### Recording {#with-recording}

When your company organizes a meeting, Oliv AI can record without a visible bot. [Bot and botless recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) explains what customers see, which helps when you brief the team.

## Who uses the deployment plan, and how {#who-uses-it}

These are typical patterns, shown to illustrate how teams roll Oliv AI out.

### Revenue operations {#revenue-operations}

A revenue operations lead owns the plan end to end. She books the admins, works with Oliv AI's onboarding team on the handbook and decides when CRM Manager moves to auto mode. Afterwards she keeps the rules current through Oliver.

### Sales leaders {#sales-leaders}

A VP of Sales signs off the qualification rules in the handbook. Two weeks later, first-line managers open their 1:1s with Deal Driver's report, and the forecast follows within the month.

### Customer success leaders {#customer-success-leaders}

A head of customer success brings the CSMs on in week one for briefs and follow-ups. Portfolio Manager's 1:1 briefings follow once recordings and CRM data are flowing.

### Enablement {#enablement}

An enablement manager picks Coach's starting scorecards and reads the first monthly review. It's a quick way to see where new hires need help, as covered in [cutting new-hire ramp time](https://www.oliv.ai/blog/sales-new-hire-ramp-time-coaching-onboarding).

## How deployment compares {#compare}

Oliv AI's onboarding team builds your process handbook with your revenue operations lead, and you can hand ongoing upkeep to Oliv AI's operators. Signal models are tailored to your company within a day of the proof of value kickoff. Oliv AI is the only platform in this table that does all three.

Setup and onboarding, from each platform's public documentation:

| Platform | Vendor team builds your process setup with you | Vendor-run option for ongoing upkeep | Tailored to your company within a day |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([onboarding consultant for data import](https://help.gong.io/docs/explainer-aligning-analytics-reports-with-historical-data)) | Not in docs | Partly ([AI trackers you build yourself](https://help.gong.io/docs/create-ai-trackers)) |
| **Outreach** | Partly ([billable services projects](https://support.outreach.io/support/solutions/articles/159000425834-outreach-glossary)) | Not in docs | Not in docs |
| **Fireflies.ai** | Partly ([guided onboarding on Enterprise](https://guide.fireflies.ai/articles/4771323041-learn-about-fireflies-enterprise-plan)) | Not in docs | Not in docs |
| **Avoma** | Partly ([designated CSM on higher plans](https://help.avoma.com/do-i-get-a-dedicated-customer-success-manager-with-my-plan)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for deployment {#compare-stronger}

- **Your process, built with you.** Oliv AI's onboarding team turns your playbooks and methodology into Oliver's handbook in one to two weeks. [Gong documents working with an onboarding consultant to bring in historical CRM data](https://help.gong.io/docs/explainer-aligning-analytics-reports-with-historical-data). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Upkeep you can hand off.** On the We Run It path, Oliv AI's operators maintain the playbooks for you. [Outreach describes its professional services as billable projects](https://support.outreach.io/support/solutions/articles/159000425834-outreach-glossary). See [Gong vs Outreach, and where Oliv AI fits](https://www.oliv.ai/blog/gong-vs-outreach).
- **Tailored on day one.** Oliv AI tailors its signal models within 1 day of the proof of value kickoff. [Gong documents AI trackers that you write and publish yourself](https://help.gong.io/docs/create-ai-trackers). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **Support that sets things up.** Oliv AI's onboarding team builds the handbook with your revenue operations lead. [Avoma documents a designated customer success manager on its Organization and Enterprise plans](https://help.avoma.com/do-i-get-a-dedicated-customer-success-manager-with-my-plan). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).

*Competitor details checked against each vendor's public documentation on 22 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **The calendar comes first.** Oliv AI can't take notes in meetings until calendars are connected, so that step can't be skipped or delayed.
- **Some steps need an admin.** Salesforce, Zoom recording without the host and, in some workspaces, Slack all need an admin on your side.
- **Handbook changes need a person.** Oliver drafts updates and surfaces patterns, but every change waits for human sign-off.
- **Reps don't work with Oliver.** Revenue operations and leaders do. Reps work with Olivia, who follows Oliver's rules.
- **Coaching needs call volume.** Coach looks for about ten calls per rep before it reports a pattern.
- **Auto mode is a decision.** CRM Manager starts in review. Revenue operations confirms the switch to auto mode once accuracy thresholds are met.

## Common questions {#common-questions}

#### How long does an Oliv AI rollout take? {#faq-how-long}

Reps get value in the first week, from their first brief. The handbook takes one to two weeks, and the manager agents are typically live within one to two weeks of being connected.

#### When do reps see something useful? {#faq-first-value}

Before their next meeting. Oliv AI's Olivia agent delivers deal context, risk and next steps 30 minutes before the next meeting on the calendar, with no waiting period.

#### How much of my team's time does setup take? {#faq-team-effort}

On the You Run It path, onboarding takes 2 to 4 sessions with your revenue operations team. On We Run It, there are no prompts to write and Oliv AI's operators maintain the playbooks.

#### Do we need to clean the CRM before we start? {#faq-clean-crm}

No. Oliv AI reads what's already there, messy data included. Oliv AI's CRM Manager agent fills missing or stale fields from call history as it goes.

#### Which admin access do we need? {#faq-admin-access}

A Salesforce admin for the package install, a Zoom admin for recording without the host, and a Slack admin if your workspace needs approval. Each user connects their own calendar by logging in.

#### Is there a proof of value? {#faq-proof-of-value}

Yes. A tailored version of Oliv AI is live within 1 day of the proof of value kickoff. Oliv AI researches your company and writes tailored prompts for each signal model.

#### Do reps need training? {#faq-rep-training}

Not for forecasting or deal alerts. Reps see a pre-drafted forecast view where they'd normally submit by hand, and Deal Driver works in the background.

#### Can we use our own sales methodology? {#faq-methodology}

Yes. Oliver captures MEDDPICC, BANT, SPICED or a proprietary framework, and every agent then follows it.

#### When should CRM updates go automatic? {#faq-auto-mode}

When the team trusts them. Updates start in review, and revenue operations confirms the switch to auto mode once accuracy thresholds are met.

#### Do the models keep up after launch? {#faq-models-after-launch}

Yes. Human feedback and quarterly re-research track new offerings, positioning and buyer personas as your company changes.

## Related {#related}

- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Agents overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/): what each Oliv AI agent does, before you decide the rollout order.
- [Slack integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/): the meeting messages your team gets once Slack is connected.
- [Customer onboarding with Oliv AI](https://www.oliv.ai/onboarding): how onboarding teams use Oliv AI agents with their own customers.
- [Plans and pricing](https://www.oliv.ai/pricing): how Oliv AI is priced.
