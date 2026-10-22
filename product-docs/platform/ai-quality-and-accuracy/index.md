# AI quality and accuracy

How Oliv AI keeps agent output reviewable, from approvals and run modes to run records and the source moment behind every CRM update.

- Applies to: Revenue operations, sales leaders and anyone deciding how much an agent may do on its own
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/platform/ai-quality-and-accuracy/

Oliv AI's agents read your calls, emails and CRM, then act on what they find. This page explains how you stay in control of that work. It covers where you approve changes before they land, how run modes set an agent's freedom, what each run record shows, and how every CRM update points back to the moment in a conversation that caused it.

## At a glance {#at-a-glance}

| Control | Where you set or see it | What it guards |
|---|---|---|
| **Ask First** and **Auto-Pilot** | CRM Manager's control mode | Whether CRM updates wait for a person |
| **Auto Run**, **Requires Approval**, **Agent Decides** | Each tool on an agent's **Tools** tab | Whether one action runs on its own |
| **Ask before acting** and **Act without asking** | Beneath the message box with Olivia or Oliver | How freely a super agent acts in one conversation |
| Run history | An agent's **Runs** tab | Every time the agent worked, and what it changed |
| Source moment | Each proposed CRM update | The part of the conversation the update came from |

## Review before anything changes {#review-before-change}

Most agent output that changes a system of record goes through a person first. You decide when that review can stop.

### CRM updates {#crm-updates}

Oliv AI's CRM Manager agent has two control modes. **Ask First** means you review each update before it's written. **Auto-Pilot** means unreviewed updates apply automatically, so the pipeline stays current without anyone acting. By default, every suggested update surfaces for review before anything reaches your CRM.

For each suggestion, the rep can **Accept**, **Edit and accept**, or **Reject**. Managers can see pending update counts per deal from the deal board. Once accuracy thresholds are met, RevOps confirms the switch to auto mode. The [workflow for keeping the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) walks through that review step by step, and the [CRM Manager agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) covers the agent itself.

Oliv AI's Meeting Assistant agent works the same way after a call. It reads the call, finds what changed, and proposes updates for approval. The [Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) then hands approved changes to CRM Manager to write.

### Process and playbook changes {#process-changes}

Oliv AI's Oliver agent keeps your process handbook: ICP, personas, methodology and approval rules. It surfaces patterns and drafts recommendations, but all handbook updates require human approval. Oliver never applies a change silently.

A proposed change waits behind **Review Changes** until someone approves it. Only then does it show as **Merged**. More on how that works is on the [Oliver agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/).

### Coaching and forecasts {#coaching-and-forecasts}

Oliv AI's Coach agent drafts monthly recommendations for each rep, each with evidence attached. A manager can accept a recommendation as written, edit it or override it. Nothing reaches the rep until the manager has reviewed it. The [Coach agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) has the full cycle.

Oliv AI's Forecaster agent shows its signals for rep or manager review. Reps and managers can accept, edit or reject each one, and that feedback trains the agent. The [Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) explains how signals roll up into the forecast.

## Run modes on agent tools {#run-modes}

A tool is one action an agent is allowed to take, such as updating a CRM record or sending an email. Every tool an agent holds carries one of three settings:

| Run mode | What it does |
|---|---|
| **Auto Run** | The tool acts without asking |
| **Requires Approval** | The tool needs a person's confirmation |
| **Agent Decides** | The agent judges whether to ask |

The mode is set per tool, on each agent, so changing one tool changes nothing else. Auto Run is the default for any tool that doesn't state another mode. That matters most for tools that write: Auto Run on a CRM, mailbox or channel tool means the agent may write to that system without asking.

Check each tool before you switch an agent on. The [tools and run modes guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) shows where the control sits. The [agent builder overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/) explains how tools fit alongside [an agent's instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) and [the triggers that start it](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/).

## The conversation setting on super agents {#super-agent-setting}

Oliv AI's Olivia agent and Oliv AI's Oliver agent carry a second, separate control. It sets how freely the super agent acts for a whole conversation: **Ask before acting** or **Act without asking**. It sits beneath the message box and opens on **Ask before acting**.

With Olivia on **Ask before acting**, she aligns on her approach before taking actions. Setting Oliver to **Act without asking** shows a **High Risk** warning above the message box, because Oliver can then change your settings. The [Olivia agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) covers working with her day to day.

## Run records {#run-records}

Run history is the record of every time an agent has worked. It's how you check that an agent on auto-pilot has been doing the right thing. The **Runs** tab lists past runs with when each started, how it started and how it ended. It also shows whether a run was automatic or manual, so you can see how much the agent did on its own.

Pressing **View** on a run opens its full record:

- **The people it touched.** A **Top Identified Contacts** panel lists them.
- **Every email in full.** Each one sits under an **Email Sent** banner, with recipient, subject and body.
- **Meetings it booked.** A calendar card shows the date, time and attendees.
- **Changes it made elsewhere.** Under **Auto-actions logged**, each change has a timestamp and a description.
- **Work that needed a person.** An amber alert panel marks what the agent escalated, separate from what it did alone.

When one agent produces work for another, the email carries a **Drafted by** line naming the agent that wrote it. That matters when Oliv AI's Olivia agent hands a task to a specialist. The [run history guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) explains each table and the record drawer.

## The source moment behind each update {#source-moments}

Every CRM update includes its source: the exact moment in the conversation that triggered it. The **Agent Updates** tab shows the field, its current CRM value, the proposed value and that reasoning. A full history of how each field has been updated is kept and visible.

So when a close date moves, you can read the line the buyer said before you accept it. The same holds for the custom fields in your [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/), whether you run [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) or [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/).

Other agents attach evidence too:

- **Expansion signals.** When Oliv AI's Gold Digger agent spots one, its notification carries what was said, who said it, which account and the exact moment in the recording.
- **Account risk.** Every flag from Oliv AI's Portfolio Manager agent comes with the evidence behind it: the signal, the account context and a recommended next action.
- **Coaching goals.** Oliv AI's Coach agent grounds each goal in the rep's own call data and deal outcomes, so the evidence is there to discuss.

## Speaker attribution {#speaker-attribution}

The [Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) transcribes and labels every speaker on a recorded call. Oliv AI's context graph then connects each conversation, message and activity to the right people, account and opportunity. Your agents know who said what, and which deal it belongs to.

That attribution is what lets a [meeting summary](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) or a proposed field update name the buyer behind a statement. For how transcription tools differ on accuracy, Oliv AI's guide to [meeting transcription software](https://www.oliv.ai/blog/meeting-transcription-software) compares the field.

## What the AI reads before it answers {#what-the-ai-reads}

Oliv AI's answers draw on your own conversations, records and playbook. Three design choices shape how it reads them:

1. **Whole conversations, not fragments.** Every meeting, email and note is read end to end, with no chunking. Signals are precomputed per deal, per account and per contact.
2. **Your playbook first.** Every agent reads the process graph before it acts. An agent working from it understands gaps and proceeds with caution, looping in a person instead of acting on outdated knowledge.
3. **Conflicts shown, not hidden.** When two of your sources disagree, the process graph documents the conflict. It also knows when a question needs routing to a person rather than an answer.

For why this matters to RevOps, Oliv AI's post on [autonomous CRM hygiene](https://www.oliv.ai/blog/crm-data-quality-automation-revops) sets out the data-quality case.

## Feedback that improves results {#feedback}

Your reviews do more than gate one change. Oliv AI's Forecaster agent learns from every signal you accept, edit or reject. Oliv AI's Portfolio Manager agent learns when you dismiss a flag that doesn't match your read. Oliv AI's Oliver agent watches what is winning in the field and drafts the next process update for your review.

## A review-first rollout {#review-first-rollout}

This pattern keeps every write visible until your team trusts the agents:

1. **Start CRM updates on Ask First.** Reps accept, edit or reject each suggestion for the first weeks.
2. **Set write tools to Requires Approval.** Leave read-only lookups on Auto Run.
3. **Read run history weekly.** Open a few records and check the emails and logged changes.
4. **Watch acceptance by rep.** Oliv AI's CRM Manager agent sends a weekly governance summary with acceptance rate by rep and flags requiring review.
5. **Switch to auto per area.** When accuracy thresholds are met, RevOps confirms the move to Auto-Pilot.

The [record and follow up workflow](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) shows the post-call review in practice, and [Slack notifications](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) tell reps when updates are waiting.

## Limits and things to know {#limits}

- **Two controls, two places.** Tool run modes are set per tool on each agent. The conversation setting is set per conversation with Olivia or Oliver. Changing one leaves the other as it was.
- **Auto Run is the starting point.** A tool with no stated mode runs as Auto Run, so review write tools before an agent goes live.
- **Auto modes skip review.** On **Auto-Pilot** or **Auto Run**, changes land without a person in the loop. Run history is where you check them afterward.
- **Run records are read-only.** A record shows what a run did. Approval happens in the review step, not in the record.
- **Oliver's warning is specific.** The **High Risk** warning appears for Oliver on **Act without asking**, because Oliver can change settings.

## Common questions {#common-questions}

#### Can an agent change my CRM without my approval? {#faq-crm-approval}

Only if you allow it. By default, every suggested update surfaces for review before anything reaches your CRM. RevOps confirms the switch to auto mode once accuracy thresholds are met.

#### How do I see why an agent proposed a change? {#faq-why-change}

Each proposed update includes its source, the exact moment in the conversation that triggered it. The **Agent Updates** tab shows the field, current value, proposed value and that reasoning.

#### What's the difference between Requires Approval and Ask before acting? {#faq-two-controls}

**Requires Approval** is a run mode on one tool of one agent. **Ask before acting** is a setting for a whole conversation with Olivia or Oliver. They're separate controls.

#### Which run mode does a new tool use? {#faq-default-mode}

Auto Run, unless the tool states another mode. Set write tools to **Requires Approval** if you want a person to confirm each action.

#### How do I check what an agent did on its own? {#faq-check-auto-work}

Open the agent's **Runs** tab. It shows whether each run was automatic or manual, and **View** opens the full record, including logged changes with timestamps.

#### Can I see which agent wrote an email? {#faq-drafted-by}

Yes. When one agent produces work for another, the email carries a **Drafted by** line naming the agent that wrote it.

#### Does Oliv AI know who said what on a call? {#faq-speakers}

Yes. Converse transcribes and labels every speaker, and the context graph ties each conversation to the right people, account and opportunity.

#### Does the AI read whole calls or snippets? {#faq-whole-calls}

Whole calls. Every meeting, email and note is read end to end, with no chunking, and signals are precomputed per deal, account and contact.

#### Will Oliver change our process on its own? {#faq-oliver-changes}

No. Oliver drafts recommendations, but all handbook updates require human approval. A change shows as **Merged** only after someone approves it.

#### Do agents learn from my corrections? {#faq-learning}

Some do. Forecaster learns from the signals you accept, edit or reject. Portfolio Manager learns from the flags you dismiss.

#### What happens when two sources disagree? {#faq-conflicts}

The process graph documents the conflict instead of hiding it. An agent facing a gap loops in a person rather than acting on outdated knowledge.

## Related {#related}

- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): set each tool's freedom to act.
- [Agent run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/): read every run and what it changed.
- [Keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/): the review-then-auto path for CRM writes.
- [Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/): process changes that wait for your approval.
- [CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/): the agent that writes approved updates.
- [Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): risk alerts grounded in your qualification framework.
- [Agents overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/): every documented agent.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
