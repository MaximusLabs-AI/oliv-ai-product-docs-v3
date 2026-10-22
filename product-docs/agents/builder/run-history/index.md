# Agent run history

How to read an Oliv AI agent's Runs tab and open a run record, from every email the agent wrote and the people it picked to a sequence's steps or a drafted reply.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/

Run history is the record of every time an Oliv AI agent has worked. Each agent's **Runs** tab lists its past runs, newest first, with when each one ran, how it started and how it ended. Press **View** on a row and the full record opens, showing what that run produced: every email the agent wrote and the people it picked, a sequence's steps, a drafted reply or a clipped call.

<figure>

![Runs tab of Oliv AI's Multithreader agent: a Run history heading, a Search previous runs box and a table with Time, Type and Status columns, listing ten runs, most Auto-triggered and two Manually run, all marked Success, each with a View link.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_048_agent-detail_multi-threader_runs-tab_run-history-table-time-type-status-view-links-auto-triggered-and-manually-run.webp)

<figcaption>The Runs tab is the list layer of run history. Each row is one run, with when it ran, how it started and how it ended.</figcaption>
</figure>

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it is** | A list of every run an agent has made, plus a full record for each run |
| **Where it lives** | **Agents › [agent] › Runs**, on every agent with a detail page |
| **Columns** | **Time**, **Type** and **Status** on every table, plus extra columns on some agents |
| **Run types** | **Auto-triggered** or **Manually run**; **Auto Trigger** or **Manual** on some agents |
| **Run record shows** | What the run produced: emails in full with their contacts, sequence steps, a drafted reply and its deal context, or a clipped call |
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

<figure>

![Runs tab of Oliv AI's Quick Qualifier agent: a Run history table with Time, Type, Status and Action columns. Seven Auto-triggered runs all show Success, and the Action column names the rep each lead was routed to, with a View link per row.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_079_agent-detail_quick-qualifier_runs-tab_run-history-seven-auto-triggered-successes-routed-to-reps-view-links.webp)

<figcaption>The basic-with-action table adds one column. Here Action shows where each run sent its lead, so the routing is readable without opening a record.</figcaption>
</figure>

The **Type** column says whether a run was **Auto-triggered** or **Manually run**. Some agents label the same thing **Auto Trigger** or **Manual**. The **Status** column shows how the run ended:

- **Success** or **Sent**, for a finished run;
- **Draft ready** or **No reply needed**, on an agent that drafts replies;
- the step a sequence reached, such as **Completed Step 2**, then **Escalated to CSM** or **Sequence Completed**.

On the message-oriented table, **Channel** names where the message came from, such as Gmail, Slack or Teams, with a colored dot. Times appear in a long format with the weekday, date and time, ending in GMT. A few tables use relative times instead, such as "Today, 07:58 AM".

## Why agent run history matters {#why-it-matters}

### What it's for {#what-its-for}

Run history shows what an agent actually did, not what it was set up to do. You see who it contacted, what it wrote and what it changed. It's the place to check unattended work after the fact.

### How it helps {#how-it-helps}

- **Every run has a row.** The list holds each run, so a change made overnight has a place to look.
- **Emails are shown word for word.** The record shows each message in full, with the recipient and subject.
- **Changes carry a time.** Each change a run made elsewhere sits on its own card with a timestamp.
- **Drafts show their sources.** A drafted reply lists the deal context it was written from.

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

Each row's **Type** column says **Auto-triggered** or **Manually run**, so it's clear whether a person started the run. How other platforms record what their agents did is covered in How Oliv AI compares for AI agent audit trails, below.

## Open an agent's run history {#open-run-history}

There are two ways in:

- Open the agent from the marketplace and select the **Runs** tab.
- On the agent's **Overview** tab, press **See run history** in the **Runs** section.

The tab is headed **Run history**. Beneath the heading is a search box with the placeholder "Search previous runs", then the table of runs in a bordered box.

The **Overview** tab's **Runs** section also carries two summary cards. **Last run** shows a date, with a line beneath describing how it started. The second card shows the week's run count, split into automated and manual.

<figure>

![The full Overview tab of the Multithreader agent: goal, trigger, tool and knowledge cards, then a Runs section with a See run history link and two cards, Last run with a date and time on trigger, and a weekly count of runs split into automated and manual.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_040_agent-detail_multi-threader_overview-tab_goal-triggers-tools-knowledge-and-runs-last-run-weekly-throughput_full-length.webp)

<figcaption>The Runs section of the Overview is the way in. See run history opens the Runs tab, and the two cards show at a glance how recently and how often the agent ran.</figcaption>
</figure>

## Find a run {#find-a-run}

1. Open the agent and select **Runs**.
2. Scan the table. Rows are listed newest first, and the order can't be changed.
3. To narrow the list, type in the search box. The table filters as you type and ignores case.
4. Read the **Type** column to see whether the run was **Auto-triggered** or **Manually run**.
5. Read the **Status** column to see how the run ended.

The search box matches different columns on different agents. On most tables it matches the time, type and status, plus the action where there is one. On the contact-oriented table it matches only the contact, company and status. Search there by name, not by date.

<figure>

![Runs tab of an agent with a contact-oriented table: Contact, Company, Time, Type and Status columns for five Auto Trigger runs, with statuses Completed Step 2, Completed Step 3, Escalated to CSM, Sequence Completed and Completed Step 1, each with a View link.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_113_agent-detail_module-activator_runs-tab_run-history-contact-company-time-type-status-completed-step-escalated-to-csm-sequence-completed.webp)

<figcaption>On a contact-oriented table each row is one person in a sequence. Status shows the step reached, so search by name to find the run you need.</figcaption>
</figure>

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

<figure>

![A run record drawer headed Run History over the Runs tab: the run's date, Auto-triggered and Success at the top, a fictional account with its owner chip, Top Identified Contacts listing five people with job titles, and an Email Sent card showing the first contact's email in full with To, Subject and body.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-builder/oliv-ai_072_agent-builder_multithreader_runs-tab_run-record-drawer-dunder-mifflin-top-identified-contacts-email-sent-to-vp-of-sales.webp)

<figcaption>Steps 2 to 7 in one drawer: the header facts, the account and owner, the contacts the run picked, and each email shown word for word.</figcaption>
</figure>

### Records for sequence agents {#sequence-records}

On an agent that runs a sequence, the record is a numbered timeline instead of contacts and emails. The header names the contact and company. Each step carries a day label with its channel, a **Completed** or **Upcoming** badge, a title, a description and a preview of what was sent. A sent step also shows how it landed, such as "Opened - No Reply". It's the only place in the product where you can see what an agent still intends to do.

<figure>

![A sequence run record: the contact, company, date and Auto-triggered at the top, then a four-step timeline. A Day 0 email and a Day 3 in-app prompt are marked Completed, with Opened and Displayed outcomes, and Day 7 and Day 14 steps are marked Upcoming.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_115_agent-detail_module-activator_run-record-drawer_four-step-sequence-email-in-app-create-qbr-draft-upcoming-sms-and-call-escalate-to-csm_full-length.webp)

<figcaption>A sequence record reads as a timeline. Completed steps show what was sent and how it landed; Upcoming steps show what the agent will do next.</figcaption>
</figure>


### Records for drafts and clips {#draft-and-clip-records}

Other agents produce other records:

- **A drafted reply.** A **Draft · Gmail** label sits above the draft's **To**, **Subject** and body. A **Deal context used:** box lists the facts the draft relied on. **Review draft in Gmail** opens it, and **Copy** copies it.
- **A clipped call.** The record shows the call's title and length, a video player with **Add Comment** and **Share**, a speaker **Timeline**, and a transcript you can search by speaker. **Ask AI** answers questions about the call, and **View Clip Library** and **View Slack Alert** open where the clip went.
- **A release email.** An **Email** section shows the audience chip with its contact count, the subject and body with merge fields, and a **Copy** action.

## How agent run history works with other features {#works-with}

### Tools and run modes {#with-tools}

A tool's run mode decides whether the agent acts alone or waits for a person. Run history shows the result of that choice after the fact. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains how to set each tool to **Auto Run**, **Requires Approval** or **Agent Decides**.

### Olivia and specialist agents {#with-olivia}

When one agent drafts an email for another, the record names it with a "Drafted by" line beneath the email. That's how you see work [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) passed to a specialist, shown under the agent that did it.

### Open in Gmail {#with-gmail}

Beneath each email sits an **Open in Gmail** link. It opens Gmail's compose screen in a new browser tab, with the recipient, subject and body already filled in. It doesn't send anything. A drafted reply carries **Review draft in Gmail** instead, and message records carry a **Copy** button.

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

## How Oliv AI compares for AI agent audit trails {#compare}

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

### Why Oliv AI is the stronger choice for AI agent audit trails {#compare-stronger}

- **Every message, word for word.** Oliv AI's run record shows each email with its recipient, subject and full body. [Gong records every automation execution in Run history](https://help.gong.io/docs/understanding-automations). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Manual and automatic runs told apart.** Each Oliv AI row says **Auto-triggered** or **Manually run**. [Gong's troubleshooting guide uses Run history to confirm whether an automation triggered](https://help.gong.io/docs/troubleshooting-automation-run-issues). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **One record per run, with the people it touched.** Oliv AI lists each run's contacts beside the emails they received. [Outreach documents execution history at run and account level for scheduled Research Agent runs](https://support.outreach.io/support/solutions/articles/159000425162-schedule-workflows-for-research-agent). See [how Outreach compares with Gong](https://www.oliv.ai/blog/gong-vs-outreach).
- **A record on every agent, not one agent type.** Oliv AI keeps run history on every agent with a detail page. [Fireflies.ai saves the recording, transcript and summary after each voice agent call](https://guide.fireflies.ai/articles/4919306982-how-to-set-up-automated-calls-with-fireflies-voice-agents).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **The cause isn't named.** A run is marked automatic without saying which [trigger or schedule](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) started it.
- **No duration or inputs.** A run doesn't record how long it took or which records the agent read before acting.
- **No approve or re-run.** A record can hand a draft to Gmail or copy it, but it has no approve, reject, edit or re-run control.
- **No export.** Run history and run records can't be exported, downloaded or printed.
- **No sort, date filter or paging.** The list is one scrolling table, newest first.
- **Gmail hand-off only.** **Open in Gmail** and **Review draft in Gmail** have no Outlook equivalent.

## Common questions {#common-questions}

#### How do I see what an agent has been doing? {#faq-see-activity}

Open the agent and select **Runs**. Each row is one run, and **View** opens the full record of what that run did.

#### How do I tell whether a run was automatic or started by hand? {#faq-auto-or-manual}

Read the **Type** column. It says **Auto-triggered** or **Manually run**, or **Auto Trigger** or **Manual** on some agents.

#### Can I see which trigger started a run? {#faq-which-trigger}

No. The **Type** column says a run was automatic but not which [trigger or schedule](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) set it off.

#### How do I see what the agent changed in other systems? {#faq-changes}

Open the run record and scroll to **Auto-actions logged**. Each change is a card with its own timestamp and a description.

#### Can I read the emails an agent sent? {#faq-emails}

Yes. Every email is shown in full under an **Email Sent** banner: recipient, subject, body and closing.

#### What statuses can a run have? {#faq-statuses}

**Success** and **Sent** on most agents. An agent that drafts replies adds **Draft ready** and **No reply needed**. A sequence shows the step reached, such as **Completed Step 2**, then **Escalated to CSM** or **Sequence Completed**.

#### Can I undo or re-run something from the record? {#faq-undo}

No. A record can open a draft in Gmail or copy it, but it has no approve, edit or re-run control.

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
