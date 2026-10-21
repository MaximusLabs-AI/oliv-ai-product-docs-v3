# Agent run history

How to read an Oliv AI agent's Runs tab and open a run record, with every email the agent sent, the people it touched and each change it made elsewhere.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/

Run history is the record of every time an Oliv AI agent has worked. Each agent's **Runs** tab lists its past runs, newest first, with when each one ran, how it started and how it ended. Press **View** on a row and the full record opens: every email the agent wrote, the people it touched and each change it made elsewhere, with the time.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it is** | A list of every run an agent has made, plus a full record for each run |
| **Where it lives** | **Agents › [agent] › Runs**, on every agent with a detail page |
| **Columns** | **Time**, **Type** and **Status** on every table, plus extra columns on some agents |
| **Run types** | **Auto-triggered** or **Manually run** |
| **Run record shows** | Emails in full, contacts touched, meetings booked, alerts and **Auto-actions logged** |
| **Order** | Newest first |
| **Summary cards** | **Last run** and a weekly run count on the **Overview** tab |

## What agent run history is {#what-it-is}

Run history is how you check that an agent working on its own has done the right thing. It has two layers. The **Runs** tab is the list: one row per run, with a search box above it. The run record is the detail: a wide drawer that opens when you press **View** on a row.

The list's columns depend on the agent. Every table carries **Time**, **Type** and **Status**. Some add more:

| Table | Extra columns | Typical agent |
|---|---|---|
| Basic | None | Most agents |
| Basic with action | **Action** | Agents whose runs carry an action name |
| Contact-oriented | **Contact**, **Company** | Agents whose runs are per person |
| Message-oriented | A title column, sometimes **Channel** | Agents that send messages |

The **Type** column says whether a run was **Auto-triggered** or **Manually run**. The **Status** column shows **Success**, **Sent**, or a phrase naming the step reached in a multi-step sequence. Times appear in a long format with the weekday, date and time, ending in GMT.

## Why agent run history matters {#why-it-matters}

### What it's for {#what-its-for}

Run history shows what an agent actually did, not what it was set up to do. You see who it contacted, what it wrote and what it changed. It's the place to check unattended work after the fact.

### How it helps {#how-it-helps}

- **Every run has a row.** The list holds each run, so a change made overnight has a place to look.
- **Emails are shown word for word.** The record shows each message in full, with the recipient and subject.
- **Changes carry a time.** Each change a run made elsewhere sits on its own card with a timestamp.
- **Escalations stand out.** An amber panel marks work where the agent needed a person to look.

### What happens without it {#without-it}

Without a record of runs, an agent's work is hard to see once it's done. A field changes or an email goes out, and nobody can say which run did it or when. Trust in the agent drops after the first surprise, and teams switch it back to manual.

### Why buyers care {#why-buyers-care}

This matters to the people who answer for what agents do in shared systems. That's usually revenue operations and the managers whose forecasts depend on clean records. It matters most after a rollout, when agents start acting without anyone watching each step.

## The Oliv AI approach to agent run history {#approach}

{/* 5P */}

Imagine a revenue operations manager opening the CRM on a Tuesday morning. One opportunity's close date moved out by a month overnight. The account executive didn't touch it and wants to know who did, before the number goes into the weekly call.

The usual hunt starts in the CRM's field history, which may only show an integration user. From there it's a round of questions to admins and a look through sync settings. That can easily take an hour, and the answer is often a best guess.

When agents work overnight, the question changes. It isn't only who made the change but which run made it, and what else that run did. A list of runs per agent, each with its own full record, answers both at once.

Oliv AI keeps that record on every agent with a detail page. The manager opens the agent, selects **Runs** and finds the overnight row by its time. Pressing **View** opens the run record, which lists each change the run made elsewhere under **Auto-actions logged**. It also shows any emails the run sent and the contacts it touched.

Each row's **Type** column says **Auto-triggered** or **Manually run**, so it's clear whether a person started the run. How other platforms record what their agents did is covered in How agent run history compares, below.

## Open an agent's run history {#open-run-history}

There are two ways in:

- Open the agent from the marketplace and select the **Runs** tab.
- On the agent's **Overview** tab, press **See run history** in the **Runs** section.

The tab is headed **Run history**. Beneath the heading is a search box with the placeholder "Search previous runs", then the table of runs in a bordered box.

The **Overview** tab's **Runs** section also carries two summary cards. **Last run** shows a date, with a line beneath describing how it started. **Weekly Throughout** shows a total run count, split into automated and manual.

## Find a run {#find-a-run}

1. Open the agent and select **Runs**.
2. Scan the table. Rows are listed newest first, and the order can't be changed.
3. To narrow the list, type in the search box. The table filters as you type and ignores case.
4. Read the **Type** column to see whether the run was **Auto-triggered** or **Manually run**.
5. Read the **Status** column to see how the run ended.

The search box matches different columns on different agents. On most tables it matches the time, type and status, plus the action where there is one. On the contact-oriented table it matches only the contact, company and status. Search there by name, not by date.

## Read a run record {#read-a-run-record}

1. Press **View** at the end of the row. The record slides in from the right as a wide drawer, headed **Run History**.
2. Read the header facts: the date and time, how the run started, how it ended, and on some agents the action it performed.
3. Check beneath for the account the run concerned. The account owner appears as a chip with a crown icon.
4. Look for an amber alert panel. It appears when the agent needed a person to look at something, with a title and a short explanation.
5. Look for a calendar card. It appears when the run booked a meeting, showing the date, title, time and attendees.
6. Read **Top Identified Contacts** down the left: each person's name, job title and sometimes an **active** or **dormant** mark. Press a contact to jump to that person's email.
7. Read the emails in the main pane. Each sits under an **Email Sent** banner and is shown in full: recipient, subject, body and closing.
8. Scroll to **Auto-actions logged** at the foot. Each change the run made elsewhere is a card with a timestamp and a description.
9. Close the drawer with the round button outside its top-left corner, or press the dimmed page behind it.

### Records for sequence agents {#sequence-records}

On an agent that runs a sequence, the record is a numbered timeline instead of contacts and emails. Each step carries a day label, a **Completed** or **Upcoming** badge, a title, a description and a preview of what was sent. It's the only place in the product where you can see what an agent still intends to do.

## How agent run history works with other features {#works-with}

### Tools and run modes {#with-tools}

A tool's run mode decides whether the agent acts alone or waits for a person. Run history shows the result of that choice after the fact. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains how to set each tool to **Auto Run**, **Requires Approval** or **Agent Decides**.

### Olivia and specialist agents {#with-olivia}

When one agent drafts an email for another, the record names it with a "Drafted by" line beneath the email. That's how you see work [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) passed to a specialist, shown under the agent that did it.

### Open in Gmail {#with-gmail}

Beneath each email sits an **Open in Gmail** link. It opens Gmail's compose screen in a new browser tab, with the recipient, subject and body already filled in. It doesn't send anything. On the message-oriented record, a **Copy** button copies the message instead.

### The Agent Feed {#with-agent-feed}

Run history is per agent. The Agent Feed shows every agent's work in one stream. Use the feed to watch work as it happens, and the **Runs** tab to look back at one agent in detail.

### Deal and meeting work {#with-deal-work}

When a run sends email or books a meeting, both appear in its record. Manager alerts work differently: [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) surfaces signals for managers and doesn't write to the CRM itself. Account executives can open the same run records for agents working their deals, alongside the routine in [running deals with Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Who uses agent run history, and how {#who-uses-it}

These are typical patterns, shown to illustrate how run history is used.

### Revenue operations {#revenue-operations}

A revops lead checks the **Runs** tab after a field changes without explanation. **Auto-actions logged** shows the change and its time, and the **Type** column shows whether anyone started the run by hand. It's part of [how revenue operations runs autonomous agents](https://www.oliv.ai/blog/revenue-operations-ai) without losing track of them.

### Sales leaders {#sales-leaders}

A sales manager opens an agent that emails customers and reads what it sent that week, before a round of 1:1s. Every message is shown in full, so the manager can coach on what customers actually received. It's useful prep alongside a [weekly forecast commit](https://www.oliv.ai/blog/run-evidence-based-forecast-commits).

### Customer success and account management {#customer-success}

A customer success manager checks which contacts an agent touched on a renewal account. **Top Identified Contacts** marks each person **active** or **dormant**, and the emails show what each one was sent.

### Enablement {#enablement}

An enablement lead uses run records as worked examples. A sequence agent's timeline shows each step marked **Completed** or **Upcoming**, which helps new reps see how a sequence unfolds before they run one. The [meeting preparation workflow](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) is a good companion read.

## How agent run history compares {#compare}

Oliv AI keeps a list of every run on each agent, and every row opens a full record of that run. The record shows each email the agent sent in full and lists each change it made elsewhere with a timestamp. Oliv AI is the only platform in this table that does all three.

Agent run records, from each platform's public documentation:

| Platform | Run list on each agent | Full text of each email sent | Each change logged with a time |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Yes ([Runs tab for automated agents](https://help.gong.io/docs/create-an-automated-agent)) | Not in docs | Partly ([actions taken per run](https://help.gong.io/docs/create-an-automated-agent)) |
| **Outreach** | Yes ([activity feed for each agent](https://support.outreach.io/support/solutions/articles/159000420910-monitor-the-progress-of-revenue-agent)) | Not in docs | Yes ([what the agent did and when](https://support.outreach.io/support/solutions/articles/159000420910-monitor-the-progress-of-revenue-agent)) |
| **Fireflies.ai** | Partly ([voice agent calls saved](https://guide.fireflies.ai/articles/4919306982-how-to-set-up-automated-calls-with-fireflies-voice-agents)) | Not in docs | Not in docs |
| **Avoma** | Not in docs | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for agent run history {#compare-stronger}

- **Every message, word for word.** Oliv AI's run record shows each email with its recipient, subject and full body. [Gong records every automation execution in Run history](https://help.gong.io/docs/understanding-automations). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Manual and automatic runs told apart.** Each Oliv AI row says **Auto-triggered** or **Manually run**. [Gong's troubleshooting guide uses Run history to confirm whether an automation triggered](https://help.gong.io/docs/troubleshooting-automation-run-issues). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **One record per run, with the people it touched.** Oliv AI lists each run's contacts beside the emails they received. [Outreach documents execution history at run and account level for scheduled Research Agent runs](https://support.outreach.io/support/solutions/articles/159000425162-schedule-workflows-for-research-agent). See [how Outreach compares with Gong](https://www.oliv.ai/blog/gong-vs-outreach).
- **A record on every agent, not one agent type.** Oliv AI keeps run history on every agent with a detail page. [Fireflies.ai saves the recording, transcript and summary after each voice agent call](https://guide.fireflies.ai/articles/4919306982-how-to-set-up-automated-calls-with-fireflies-voice-agents).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **The cause isn't named.** A run is marked automatic without saying which [trigger or schedule](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) started it.
- **No duration or inputs.** A run doesn't record how long it took or which records the agent read before acting.
- **Read-only.** There's no send, approve, reject, edit or re-run control in a run record.
- **No export.** Run history and run records can't be exported, downloaded or printed.
- **No sort, date filter or paging.** The list is one scrolling table, newest first.
- **Gmail only.** **Open in Gmail** has no Outlook equivalent.

## Common questions {#common-questions}

#### How do I see what an agent has been doing? {#faq-see-activity}

Open the agent and select **Runs**. Each row is one run, and **View** opens the full record of what that run did.

#### How do I tell whether a run was automatic or started by hand? {#faq-auto-or-manual}

Read the **Type** column. It says **Auto-triggered** or **Manually run**.

#### Can I see which trigger started a run? {#faq-which-trigger}

No. The **Type** column says a run was automatic but not which [trigger or schedule](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) set it off.

#### How do I see what the agent changed in other systems? {#faq-changes}

Open the run record and scroll to **Auto-actions logged**. Each change is a card with its own timestamp and a description.

#### Can I read the emails an agent sent? {#faq-emails}

Yes. Every email is shown in full under an **Email Sent** banner: recipient, subject, body and closing.

#### What statuses can a run have? {#faq-statuses}

**Success**, **Sent**, or a phrase naming the step reached in a multi-step sequence.

#### Can I undo or re-run something from the record? {#faq-undo}

No. The run record is read-only. It has no send, approve, edit or re-run control.

#### Can I export run history? {#faq-export}

No. There's no export or download for the list or for a run record.

#### Can I filter runs by date? {#faq-date-filter}

No. The search box matches text in the row, and there's no date filter or sort control.

#### Where do I see how many times an agent has run? {#faq-run-count}

On the **Overview** tab. The **Runs** section shows a total run count, split into automated and manual.

#### Can I see what a sequence agent will do next? {#faq-upcoming}

Yes. A sequence agent's record lists each step as **Completed** or **Upcoming**.

## Related {#related}

- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): choose which actions an agent takes alone.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Olivia agent guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): the agent that hands work to specialists.
- [Deal Driver agent guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): pipeline alerts and 1:1 reports for managers.
- [Account executive guide to running deals](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): how reps use agents day to day.
- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the brief agents send before calls.
- [Autonomous agents for RevOps](https://www.oliv.ai/blog/revenue-operations-ai): how revops teams run agents across the process.
- [Agents versus alert bots](https://www.oliv.ai/blog/vonlabs-review): why agents that act need a record of what they did.
- [Revenue intelligence platforms compared](https://www.oliv.ai/blog/best-revenue-intelligence-software-platforms): where agent oversight fits in the category.
- [Agentforce user feedback](https://www.oliv.ai/blog/salesforce-agentforce-reviews-analyzed): what teams report about trusting CRM agents.
