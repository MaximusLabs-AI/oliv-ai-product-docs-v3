# Agents overview

How Oliv AI's agents fit together, from Olivia and Oliver, the two agents you talk to, to the specialist agents they hand work to and the parts every agent is built from.

- Applies to: All revenue teams
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/

Agents are the product at Oliv AI. You talk to two of them, Oliv AI's Olivia agent and Oliv AI's Oliver agent. They pass focused work to specialist agents for deals, the CRM, meetings, forecasts and coaching. Every agent works as a layer on top of the CRM you already use, and keeps it updated.

## How the agents fit together {#how-agents-fit}

Oliv AI's agents work in three layers. At the front, Oliv AI's Olivia agent runs the work and Oliv AI's Oliver agent sets the rules. Oliver configures how the agents work, and Olivia coordinates their tasks across your team.

| Layer | Agents | What the layer does |
|---|---|---|
| **The agents you talk to** | Olivia and Oliver | Answer questions, hand off work and keep the process rules |
| **Specialist agents** | Deal Driver, CRM Manager, Meeting Assistant, Forecaster, Coach | Each owns one job and reports back |
| **Agent parts** | Instructions, tools, triggers, knowledge, run history | What every agent is built from, and the record of what it did |

All of them read from one shared record. Oliv AI wires your CRM, calls, email, tickets and product usage into one [context graph](https://www.oliv.ai/context-graph). Every agent and every rep works from that same graph.

## The two agents you talk to {#olivia-and-oliver}

Which one you work with depends on whether you run deals or run the process.

### Olivia runs the work {#olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) is the one reps, SDRs, CSMs and account managers talk to. You ask in plain language about a deal, a meeting or your pipeline. She answers, or hands the task to a specialist agent and reports back. Each conversation is set to **Ask before acting**, the default, or **Act without asking**. Her [role across the revenue team](https://www.oliv.ai/agents/olivia) is set out on oliv.ai.

### Oliver keeps the rules {#oliver}

[Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) is for RevOps managers and revenue leaders. It keeps the process handbook, from your ICP and personas to your methodology and approval rules, and every other agent works inside it. You describe a change in plain language. Oliver proposes the update, waits for a person to sign it off, then passes it to every agent that depends on it. Its [approach to your sales process](https://www.oliv.ai/agents/oliver) is on oliv.ai, and its chat also sits beside the **Agents** marketplace.

## The specialist agents {#specialist-agents}

Each specialist agent owns one job. It does that job in the background and delivers the result where you already work, such as Slack, email or the Oliv AI app.

- [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) watches the team's pipeline for sales managers. It sends a morning brief, alerts during the day when a deal needs attention, and a summary at the end of the day. Each week it also prepares a 1:1 report for every rep.
- [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) writes what changed after each meeting, call and email to Salesforce, HubSpot or Zoho. Reps review each update with the moment behind it, until RevOps switches the agent to **Auto-Pilot**. First, [map your custom CRM fields](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/) so each update lands in the right place.
- [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) sends a one-screen brief 30 minutes before each deal meeting. After the call, it drafts the follow-up email, proposes CRM updates and flags qualification gaps.
- [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) drafts each rep's forecast from the pipeline before anyone logs in. It flags the deals that don't add up and learns from how your deals actually close.
- [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) scores every recorded call against your scorecards. Each month it recommends three behaviors per rep, the manager picks one goal, and Coach tracks it weekly.

The [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) groups agents by the roles they serve, from SDRs to RevOps.

## Where agents get their context {#where-context-comes-from}

An agent can only act on what it can read. Three sources feed it.

- **Conversations.** The [Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) captures online meetings, phone calls, email and Slack. [Bot and botless recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) decides how each meeting is recorded.
- **Your CRM.** Deals, contacts and fields come from [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) or [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/), and agents write updates back.
- **Your tools.** Meetings come in through [the Zoom integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/), and [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) is where many agents deliver their work.

You don't need a clean CRM to start. Oliv AI's Olivia agent reads what's already there, messy data included.

## Inside every agent {#inside-an-agent}

Every agent with a detail page is built from the same five parts. The [agent builder overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/) explains how they fit together.

- [Agent instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) state the agent's objective, the steps it follows and what it produces.
- [Tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) list the actions an agent may take, each set to **Auto Run**, **Requires Approval** or **Agent Decides**.
- [Triggers and schedules](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) are the events and fixed times that start an agent without anyone pressing anything.
- [Knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) are the documents an agent works against, such as an ICP document or a solution deck.
- [Run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) records every run, with each email the agent wrote and each change it made.

## Where to start {#next-steps}

- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): get the deal brief before each call.
- [Record a meeting and follow up](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/): turn a finished call into a follow-up and CRM updates.
- [Keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/): move from reviewed updates to automatic ones.
- [Run a pipeline review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/): walk into each 1:1 with a per-rep report.
- [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): see how the agents share one AE's week.
- [Plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/): match each person on your team to a seat role.
