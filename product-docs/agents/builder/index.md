# Agent builder overview

The parts every Oliv AI agent is built from, from the marketplace where agents live to the detail page, instructions, tools and run modes, triggers, knowledge and run history.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/

The agent builder is where you see what an Oliv AI agent is and how it works. Every agent with a detail page shows the same parts: its purpose, its actions, what starts it, the files it reads and its past runs. This section explains each part, starting with the marketplace where agents live.

## Where agents live: the marketplace {#marketplace}

Open **Agents** in the main sidebar to reach the marketplace, the single place you see every agent available to you. Each agent is a card with a name, a one-line description and a picture. Pressing a card opens that agent's detail page, and **Back to Marketplace** at the top brings you back.

A search box at the right matches what you type against each agent's name and description. The [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) on oliv.ai shows the pre-built agents grouped by the roles they serve.

### Categories and badges {#categories-and-badges}

Agents are grouped by the revenue team they serve. Five buttons above the grid narrow the list: **All**, **Our Agents**, **Sales**, **Revenue Operations** and **Customer Success**. The category buttons and the search box work together, so an agent must match both to stay listed.

Some cards also carry a **Pre-built** or **Custom** badge, which tells you where that agent came from. A chat with [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) sits on the right of the marketplace, so you can ask about agents without leaving the screen.

## The parts of an agent {#agent-parts}

An agent's detail page opens on its **Overview** tab. It summarizes the agent's goal, triggers, tools, knowledge and recent runs. Each of the other tabs goes into one part in depth.

| Part | Tab | What it tells you |
|---|---|---|
| [Instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) | **Instructions** | The agent's **Objective**, its numbered **Process** steps and its **Output** |
| [Tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) | **Tools** | Each action the agent may take, and how freely it takes it |
| [Triggers and schedules](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) | **Triggers** | The events and fixed times that start the agent on its own |
| [Knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) | **Knowledge** | The files the agent works against, each one open to view |
| [Run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) | **Runs** | Every run, with a full record of what the agent did |

Every agent with a detail page has a **Runs** tab. **Knowledge** appears on 5 of the 8 and **Triggers** on 4.

Read the parts in order and you have the whole agent. The instructions say what it does, the tools say what it may touch, and the triggers say when it acts. The run history shows what actually happened.

## How much freedom an agent has {#autonomy}

Two settings decide how far an agent goes on its own.

- **Per tool.** On the **Tools** tab, **Auto Run** acts without asking, **Requires Approval** waits for a person to confirm, and **Agent Decides** judges whether to ask.
- **Per conversation.** In a chat with [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/), each conversation is set to **Ask before acting** or **Act without asking**.

Every run leaves evidence. Its record lists each email the agent wrote in full, the people it touched and each change it made elsewhere, with the time. So you can [check an agent's past runs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) before you give it more freedom. CRM updates follow the same path, from reviewed to automatic, in [keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/).

## How agents work together {#working-together}

Agents don't work alone. Oliv AI's Olivia agent runs the frontline and routes work to the right specialist agent. Oliv AI's Oliver agent keeps the playbook current and configures which agents are active, what they monitor and what thresholds trigger their actions. Each agent gets the right tools, memory, permissions and guardrails for the job, scoped to the task at hand.

### One shared record {#shared-context}

Every agent and every rep works from the same [context graph](https://www.oliv.ai/context-graph). Agents also start from the data you already have. Olivia reads what's already there, messy data included, and [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) doesn't need a clean CRM to start. When you override one of Forecaster's recommendations, it learns from that feedback.

### Thresholds and delivery {#thresholds-and-delivery}

Some agents let you tune when they speak up. With [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), inactivity windows, field completion requirements and deal value thresholds are configurable per manager or per team. Agents deliver work where people already are: Deal Driver reaches you in [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/), email or the Oliv AI app. Tools in the catalog act in systems such as [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/).

## Custom agents {#custom-agents}

The marketplace on oliv.ai offers pre-built agents designed for specific challenges, and invites you to request a custom agent. Oliv AI's GTM engineering team stays with you after launch. It reviews agent output, tunes the playbook and adds custom agents as your territory, comp or ICP shifts, as the [RevOps page](https://www.oliv.ai/revops) describes. A custom agent has the same parts as every other, so the pages in this section apply to it. The [build vs buy guide](https://www.oliv.ai/build-vs-buy) covers when a custom agent makes sense.

## Next steps {#next-steps}

- [Set run modes on each tool](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): decide which actions wait for a person.
- [Agents overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/): see how Olivia, Oliver and the specialist agents fit together.
- [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/): the agent that moves from reviewed to automatic CRM updates.
- [Run a pipeline review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/): put Deal Driver's per-rep reports to work.
- [Record a meeting and follow up](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/): see several agents act on one call.
