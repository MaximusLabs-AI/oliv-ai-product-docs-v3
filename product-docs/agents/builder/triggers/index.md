# Agent triggers

What an Oliv AI agent's triggers and schedules are, where to read them on the Triggers tab, and how the trigger picker and the schedule form are laid out.

- Applies to: Agents with a Triggers tab
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/

A trigger is the event that starts an Oliv AI agent without anybody pressing anything, such as a deal reaching a stage in your CRM. Each agent in the [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) that has a **Triggers** tab lists those events as cards. The same tab holds the agent's schedules, the fixed times it acts at.

<figure>

![Triggers tab of Oliv AI's Multithreader agent: a Triggers section with the line Triggers allow your agent to work on auto-pilot, an Add Trigger button and one card, Deal enters Proposal Stage in Salesforce, then an empty Schedule messages section with a Set Schedule button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_044_agent-detail_multi-threader_triggers-tab_deal-enters-proposal-stage-in-salesforce-trigger-add-trigger-and-set-schedule-buttons.webp)

<figcaption>The Triggers tab answers what starts an agent. Each card names the event in one line and explains when the agent fires; schedules sit in their own section below.</figcaption>
</figure>

## At a glance {#at-a-glance}

| | |
|---|---|
| **What a trigger is** | The event that starts an agent on its own |
| **Where triggers live** | **Agents › [agent] › Triggers** |
| **What a card shows** | The source's icon, the event in one line, when the agent fires, and a menu button |
| **Schedules** | The **Schedule messages** section of the same tab |
| **Schedule frequencies** | **Daily**, **Every Week**, **Monthly**, **Yearly** |
| **How automatic runs show** | **Auto-triggered** or **Auto Trigger** in the run history, apart from **Manually run** or **Manual** |
| **Also shown on** | The **Overview** tab, as trigger pills, including on agents with no **Triggers** tab |

## What agent triggers are {#what-it-is}

The **Triggers** tab answers one question: what makes this agent start work by itself? Its own description puts it plainly: "Triggers allow your agent to work on auto-pilot." The tab has two sections, stacked in one column.

| Section | What it lists | Button |
|---|---|---|
| **Triggers** | The events the agent watches for, one card each | **Add Trigger** |
| **Schedule messages** | The fixed times the agent acts at, one card each | **Set Schedule** |

A trigger card has three parts: a small icon for the source the event comes from, the event as a one-line title, and a longer explanation of when the agent fires. The explanation can be one sentence or a short list. A menu button (⋮) sits at the card's right.

Agents carry between 1 and 5 triggers each, and they start from many kinds of event:

| Event that starts the agent | Example |
|---|---|
| A deal's stage is set to Proposal in [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) | Oliv AI's Multithreader agent |
| A tracked lead starts a new session on your website | Oliv AI's Quick Qualifier agent |
| Company Insights detects a funding signal on an account | Oliv AI's Momentum Reviver agent |
| A new customer email in Gmail or Outlook, a message in a shared Teams or Slack Connect channel, a deadline, or a message unanswered for 24 hours | Oliv AI's Comms Manager agent |
| A meeting is completed | Oliv AI's Content Curator agent |
| A release announcement in a [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) channel | Oliv AI's Product Release Messenger agent |

<figure>

![Triggers tab of Oliv AI's Quick Qualifier agent: one trigger card, New website session, which fires when a tracked lead starts a new session on the website, with an Add Trigger button above and an empty Schedule messages section with Set Schedule below.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_078_agent-detail_quick-qualifier_triggers-tab_new-website-session-trigger-add-trigger-schedule-messages-set-schedule.webp)

<figcaption>A trigger can come from outside the CRM. This agent starts the moment a tracked lead begins a new website session.</figcaption>
</figure>

<figure>

![Triggers tab of Oliv AI's Momentum Reviver agent: one card, When funding signal is detected from Company Insights, explained as two bullets about a strong company signal on an account and other events that suggest fresh budget, with Add Trigger and Set Schedule buttons.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_086_agent-detail_momentum-reviver_triggers-tab_funding-signal-from-company-insights-trigger-add-trigger-set-schedule.webp)

<figcaption>A card's explanation can be a short list. Here it spells out which signals count as fresh budget before the agent wakes up.</figcaption>
</figure>

Take the Multithreader agent as an example. It has one trigger: it fires on its own when a deal's stage is set to Proposal in the connected CRM. It can also be started by hand with **Run Agent**.

## Why agent triggers matter {#why-it-matters}

### What it's for {#what-its-for}

Triggers decide when an agent starts work on its own. They tie the agent to a moment in your systems, such as a stage change, instead of to someone remembering to run it. Schedules do the same for fixed times.

### How it helps {#how-it-helps}

- **Work starts when the event happens.** An agent can begin the moment a deal reaches a stage.
- **Every start is written down.** Each card names the event and says in a sentence when the agent fires.
- **Automatic runs are labeled.** The [run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) marks them **Auto-triggered**, so they stand apart from runs a person started.
- **Events and times sit together.** One tab lists an agent's triggers and its schedules.

### What happens without it {#without-it}

Without a trigger, every run starts with a person. Someone has to spot the stage change, open the agent and press run. In a busy week that run comes late or never. The deals that most needed the work are often the ones it misses.

### Why buyers care {#why-buyers-care}

This matters most to [revenue operations teams](https://www.oliv.ai/revops), who own the stage definitions in the CRM. It matters when a team first lets agents start unattended. It matters again whenever the stage process changes, because a trigger is where an agent can begin with no person present.

## The Oliv AI approach to agent triggers {#approach}

{/* 5P */}

Picture a revenue operations manager whose team has just redrawn the opportunity stages. The new rule says every deal that reaches Proposal needs a wider buying committee before pricing goes out. Around sixty deals a quarter cross that line, spread over several teams.

The usual fix is a saved CRM report and a reminder. Someone checks the report on Monday and nudges each deal owner in chat. That probably works for a while. But a deal that hits Proposal on a Tuesday can wait six days, and the check quietly stops when its owner goes on leave.

The stage change is already the signal. The CRM records the moment a deal moves, so the work can start from that moment rather than from somebody's calendar. What the team needs is a way to tie the agent to the event itself.

Oliv AI starts the agent from the event. Oliv AI's Multithreader agent fires on its own when a deal's stage is set to Proposal in the connected CRM. It then judges whether the buying committee is broad enough and drafts outreach for the seller to review. The RevOps manager reads that trigger on the agent's **Triggers** tab before rolling the agent out.

Each trigger is written out on the tab. Every card shows the source system's icon, the event in one line and a sentence on when the agent fires. Runs it starts appear in the run history as **Auto-triggered**. How other platforms start agents on their own is covered in How Oliv AI compares for event-triggered AI agents, below.

## Read an agent's triggers {#read-triggers}

1. Open the agent and select the **Triggers** tab. You can also press one of the trigger pills on the **Overview** tab, which opens the same tab.
2. Read the first section, headed **Triggers**. Its description reads "Triggers allow your agent to work on auto-pilot."
3. Read each card. The icon shows the system the event comes from. The title names the event, and the line beneath says when the agent fires.
4. Scroll down to **Schedule messages** to see any fixed times the agent acts at.

On some agents, the **Overview** tab also carries a plain-language sentence above the trigger pills. It explains what kind of event wakes the agent. It's collapsed to one line, and pressing it expands the rest.

## Browse the trigger picker {#trigger-picker}

Press **Add Trigger** at the right of the **Triggers** heading to open the picker. It opens as a panel headed **Triggers**, over a dimmed page.

1. Type in the search box, marked "Search triggers...". It narrows both groups as you type, matching any part of a system's name and ignoring case.
2. Read the **Most popular** group: a fixed list of 11 systems, each shown with its logo, two to a row. They are Microsoft Outlook, Google Mail, Google Calendar, Salesforce, HubSpot, Freshdesk, ZoomInfo, Relevance Meeting Bot, LinkedIn, WhatsApp and Telegram.
3. Read the **All triggers** group beneath it, a longer list that starts with WhatsApp Business, Airtable and Aircall. A **Show more** link sits at its foot.
4. Close the picker with the **×** at the top right, or press the dimmed page behind it.

The picker is the same whichever agent you opened it from.

<figure>

![The Triggers picker opened from Add Trigger: a Search triggers box above a Most popular group of 11 systems, two to a row: Microsoft Outlook, Google Mail, Google Calendar, Salesforce, Hubspot, Freshdesk, ZoomInfo, Relevance Meeting Bot, LinkedIn, WhatsApp and Telegram.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_065_agent-detail_multi-threader_triggers-tab_add-trigger-picker-modal_search-triggers-most-popular-outlook-google-mail-calendar-salesforce-hubspot-zoominfo-linkedin.webp)

<figcaption>The picker lists the systems a trigger can come from. Search narrows both groups, and the most common sources sit at the top.</figcaption>
</figure>

## Set a schedule {#set-schedule}

A schedule lets an agent act at fixed times, alongside its event triggers. The section explains itself as "Schedule allow your agent to schedule future actions."

1. Open the agent's **Triggers** tab and scroll to **Schedule messages**.
2. Press **Set Schedule**. A form headed **Set Schedule** opens. A line at the top shows the timezone the schedule uses.
3. Type a name in the **Name** field, marked "Enter text...".
4. Choose how often in the first **Schedule** dropdown: **Daily**, **Every Week**, **Monthly** or **Yearly**. It opens on **Every Week**.
5. Fill in the dropdowns that appear to its right, such as **Select day** and **Select time**. They change with the frequency, as the table below shows.
6. Press **Finish**.

<figure>

![The Set Schedule form with the frequency dropdown open on four choices, Daily, Every Week, Monthly and Yearly, beside unset Select day and Select time dropdowns, with an empty Name field above and a Finish button at the bottom right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_068_agent-detail_multi-threader_triggers-tab_set-schedule-form_frequency-dropdown-open-daily-every-week-monthly-yearly-options.webp)

<figcaption>Step 4: the frequency comes first. The day and time dropdowns beside it follow whichever of the four you choose.</figcaption>
</figure>

| Frequency | Further dropdowns |
|---|---|
| **Daily** | Hour, then minute, at quarter-hours (**:00**, **:15**, **:30**, **:45**) |
| **Every Week** | Day of the week, then a time at half-hour steps |
| **Monthly** | Day of the month (**1** to **31**), then a time |
| **Yearly** | Month, then day of the month, then a time |

A fixed time can also show as a trigger. Oliv AI's Comms Manager agent lists "Morning inbox sweep, weekdays 7:30 AM" among its trigger pills.

## How agent triggers work with other features {#works-with}

### Tools and run modes {#with-tools}

A trigger decides when an agent starts. How freely it then acts is set by each tool's run mode, covered in [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/). An agent with a trigger and an **Auto Run** tool can act with no person involved at any point.

### Run history {#with-run-history}

The run history on the agent's **Runs** tab records each run's type: **Auto-triggered** or **Auto Trigger** for runs that started on their own, **Manually run** or **Manual** for the rest. That's where you see a trigger at work, as the [run history guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) in this documentation explains.

### The Overview tab {#with-overview}

The **Overview** tab lists the agent's triggers as pills under a **Triggers** heading. Pressing a pill opens the **Triggers** tab, so it's a quick way to check what starts an agent you're about to rely on. Agents with no **Triggers** tab still list their triggers here, each pill with its own icon.

<figure>

![Overview tab of the Comms Manager agent, which has no Triggers tab: a Goal, then a Triggers card with five pills, New customer email in Gmail or Outlook, New message in a shared Teams or Slack Connect channel, A deadline in the message or the deal, Backstop: customer message unanswered for 24 hours, and Morning inbox sweep, weekdays 7:30 AM.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_091_agent-detail_comms-manager_overview-tab_goal-five-triggers-six-tools-watches-gmail-outlook-teams-slack-connect.webp)

<figcaption>One agent can carry several triggers. Here five pills cover new messages, deadlines, an unanswered-message backstop and a weekday morning sweep.</figcaption>
</figure>

### Deal work that starts from a stage {#with-deal-work}

A stage-based trigger fits the deal work agents already do between calls. It sits alongside the [day-to-day deal flow for account executives](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/) and the brief an agent sends when you [prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

## Who uses agent triggers, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the tab is used.

### Revenue operations {#revenue-operations}

Before a rollout, a revops team walks each agent's **Triggers** tab and lists which agents can start on their own. It then checks those agents' tools, since a trigger plus an **Auto Run** tool means unattended action. The [Oliv AI guide for RevOps](https://www.oliv.ai/blog/revenue-operations-ai) covers where this fits in the wider process.

### Account executives and sales leaders {#account-executives-and-sales-leaders}

When an agent's draft lands on a deal, an [account executive](https://www.oliv.ai/account-executives) can open the run history and see it marked **Auto-triggered**. The trigger card then explains which deal event started it, such as reaching Proposal. [Sales managers](https://www.oliv.ai/sales-managers) use the same cards to explain agent activity in 1:1s.

### Customer success and account management {#customer-success}

A [customer success team](https://www.oliv.ai/customer-success) reads the **Schedule messages** section to see when an agent acts at a fixed time, such as every week on a set day. That sits next to the event triggers on the same tab, so the whole picture is in one place.

### Enablement {#enablement}

An enablement lead uses the one-sentence descriptions on trigger cards to brief new reps. Reps learn which deal events will start an agent on their opportunities, before the first draft arrives.

## How Oliv AI compares for event-triggered AI agents {#compare}

Oliv AI lets one agent carry several event triggers, such as a deal reaching a stage in the CRM, and fixed-time schedules on the same tab. Runs that start on their own are labeled in the agent's run history. Oliv AI is the only platform in this table that does all four.

Agent start rules, from each platform's public documentation:

| Platform | Starts when a CRM deal changes | Several triggers on one agent | Event triggers and schedules on one agent | Automatic runs marked in run history |
|---|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes | Yes |
| **Gong** | Yes ([brief when a deal reaches a stage](https://help.gong.io/docs/understanding-automations)) | [One trigger per agent](https://help.gong.io/docs/create-an-automated-agent) | Partly ([schedules are one trigger type](https://help.gong.io/docs/understanding-automations)) | Yes ([Run history per automation](https://help.gong.io/docs/troubleshooting-automation-run-issues)) |
| **Outreach** | Yes ([opportunity updated event](https://support.outreach.io/support/solutions/articles/159000430471-agent-studio-overview)) | Not in docs | Partly ([event or a scheduled time](https://support.outreach.io/support/solutions/articles/159000430471-agent-studio-overview)) | Yes ([Runs tab for each schedule](https://support.outreach.io/support/solutions/articles/159000425162-schedule-workflows-for-research-agent)) |
| **Fireflies.ai** | [After each meeting](https://guide.fireflies.ai/articles/8965294647-setting-up-multi-meeting-ai-apps) | Not in docs | Partly ([per-meeting or scheduled skill](https://guide.fireflies.ai/articles/4941026890-build-your-own-ai-skill-to-automate-meeting-workflows-summaries-and-insights)) | Not in docs |
| **Avoma** | Not in docs | Not in docs | Partly ([scheduled prompts](https://help.avoma.com/scheduled-prompts-in-ask-avoma)) | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for event-triggered AI agents {#compare-stronger}

- **Several triggers on one agent.** Oliv AI agents carry between 1 and 5 triggers each. [Gong's help center says each automated agent uses one trigger](https://help.gong.io/docs/create-an-automated-agent). See [Oliv AI as a Gong alternative](https://www.oliv.ai/blog/gong-vs-oliv).
- **Events and schedules in one place.** Oliv AI lists an agent's event triggers and its schedules on one **Triggers** tab. [Outreach documents scheduled Research Agent runs as their own scheduled workflows](https://support.outreach.io/support/solutions/articles/159000425162-schedule-workflows-for-research-agent). See [how Gong and Outreach compare](https://www.oliv.ai/blog/gong-vs-outreach).
- **Started by a deal event, not only the clock.** Oliv AI's Multithreader agent fires when a deal's stage is set to Proposal. [Avoma's scheduled prompts run a question on a recurring basis](https://help.avoma.com/scheduled-prompts-in-ask-avoma). See [Avoma vs Oliv AI](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Automatic runs you can pick out.** Oliv AI's run history marks each run **Auto-triggered** or **Manually run**. [Fireflies.ai documents skills that run after every meeting or on a schedule](https://guide.fireflies.ai/articles/8965294647-setting-up-multi-meeting-ai-apps).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Not every agent has the tab.** Only some agents show a **Triggers** tab. For the others, the trigger pills on the **Overview** tab say what starts them.
- **No pause or off switch.** A trigger or schedule can't be paused from the tab, and there's no agent-wide off switch.
- **No conditions or filters.** A trigger can't be narrowed to a team, a region or a deal size.
- **No firing record on the card.** There's no last-fired time, firing count or failure marker on any trigger.
- **Runs don't name their trigger.** The run history says a run was **Auto-triggered**, not which trigger or schedule started it.

## Common questions {#common-questions}

#### What is a trigger in Oliv AI? {#faq-what-is-a-trigger}

A trigger is the event that starts an agent on its own, with nobody pressing anything. The tab puts it as "Triggers allow your agent to work on auto-pilot."

#### How do I see what starts an agent? {#faq-see-triggers}

Open the agent and select **Triggers**. Each card names the event and explains when the agent fires. You can also press a trigger pill on the **Overview** tab.

#### Can an agent start when a deal changes stage? {#faq-deal-stage}

Yes. Oliv AI's Multithreader agent, for example, fires on its own when a deal's stage is set to Proposal in the connected CRM.

#### Can one agent have more than one trigger? {#faq-several-triggers}

Yes. Agents carry between 1 and 5 triggers each. One agent starts on new customer messages, deadlines, a 24-hour backstop and a weekday morning sweep.

#### What's the difference between a trigger and a schedule? {#faq-trigger-vs-schedule}

A trigger starts the agent when an event happens. A schedule starts it at a fixed time, set as **Daily**, **Every Week**, **Monthly** or **Yearly**. Both sit on the **Triggers** tab.

#### How do I tell whether a trigger fired? {#faq-did-it-fire}

Open the agent's run history. Runs that started on their own are marked **Auto-triggered**. The run doesn't say which trigger was responsible.

#### Can I pause or remove a trigger? {#faq-pause}

No. A trigger can't be paused or disabled from the tab, and there's no off switch for the whole agent.

#### Can I limit a trigger to certain deals or people? {#faq-filters}

No. A trigger carries a title and a description and nothing you can configure, so it can't be narrowed by team, region or deal size.

#### Why does this agent have no Triggers tab? {#faq-no-tab}

Only some agents offer one. Their triggers still show as pills on the **Overview** tab.

## Related {#related}

- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): decide how freely a triggered agent acts.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): how Oliv AI's Deal Driver agent works on open deals.
- [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): ask Oliv AI's Olivia agent about deals and pipeline.
- [Prepare a brief before each call](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the meeting workflow agents support.
- [How account executives run deals](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): where agent work fits in an AE's week.
- [Sales process automation by stage](https://www.oliv.ai/blog/sales-process-automation): what to automate at each deal stage.
- [AI sales workflow automation](https://www.oliv.ai/blog/ai-sales-workflow-automation): how agents and workflows fit together.
- [Why deals slip without warning](https://www.oliv.ai/blog/deal-slippage-prevention-vp-sales): the pipeline gaps stage triggers address.
- [Oliv AI implementation guide for RevOps](https://www.oliv.ai/blog/oliv-ai-revops-implementation-admin-guide): set-up and admin for revops teams.
- [Connected apps](https://www.oliv.ai/integrations): the systems Oliv AI connects to.
