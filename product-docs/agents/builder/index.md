# Agent builder overview

The parts every Oliv AI agent is built from, from the marketplace where agents live to the detail page, instructions, tools and run modes, triggers, knowledge and run history.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/

The agent builder is where you see what an Oliv AI agent is and how it works. Every agent with a detail page shows the same parts: its purpose, its actions, what starts it, the files it reads and its past runs. This section explains each part, starting with the marketplace where agents live.

<figure>

![The Agents marketplace on the All filter: five filter buttons and a Search box above a grid of agent cards such as Multithreader, Quick Qualifier and Comms Manager with a Custom badge, each with View Agent or Clone Agent, and Oliver's chat panel at the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_031_agents-marketplace_all-tab_nine-agent-cards-view-agent-and-clone-agent-buttons-category-filters-search-oliver-chat-panel-open.webp)

<figcaption>The marketplace is where every agent starts. Cards show what each agent does and whether you view it or clone it, with Oliv AI's Oliver agent on hand for questions.</figcaption>
</figure>

## Where agents live: the marketplace {#marketplace}

Open **Agents** in the main sidebar to reach the marketplace, the single place you see every agent available to you. Each agent is a card with a picture, a name, a short description and one button. **View Agent** opens that agent's detail page, and **Back to Marketplace** at the top brings you back. **Clone Agent** appears on template agents, as the way to take one as a starting point.

A search box at the right matches what you type against each agent's name and description. The [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) on oliv.ai shows the pre-built agents grouped by the roles they serve.

<figure>

![The Agents marketplace with renewal typed in the Search box and the All filter selected. Two cards remain: Renewal Radar with a Clone Agent button, and QBR Builder with a Pre-built badge and a View Agent button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_038_agents-marketplace_agents-page_search-box-typed-renewal_all-tab-filtered-to-renewal-radar-and-qbr-builder.webp)

<figcaption>Search matches the description as well as the name. Typing renewal keeps Renewal Radar by its name and QBR Builder by its description.</figcaption>
</figure>

### Categories and badges {#categories-and-badges}

Agents are grouped by the revenue team they serve. Five buttons above the grid narrow the list: **All**, **Our Agents**, **Sales**, **Revenue Operations** and **Customer Success**. The category buttons and the search box work together, so an agent must match both to stay listed.

Some cards also carry a **Pre-built** or **Custom** badge, which tells you where that agent came from. A chat with [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) sits on the right of the marketplace, so you can ask about agents without leaving the screen. The panel has its own new chat and history buttons, a suggested question to start from and the **Ask before acting** setting under the message box.

<figure>

![The Agents marketplace filtered to Customer Success: seven cards with View Agent buttons. QBR Builder, Portfolio Manager and Meeting Assistant carry a Pre-built badge, and the other four carry a Custom badge. Oliver's chat panel sits at the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_037_agents-marketplace_agents-page_customer-success-category-tab-selected_seven-agent-cards-qbr-builder-portfolio-manager-meeting-assistant-pre-built-and-custom-badges.webp)

<figcaption>A category button narrows the grid to one team's agents. Pre-built and Custom badges mark where each agent came from, and both kinds open the same detail page.</figcaption>
</figure>

## The parts of an agent {#agent-parts}

An agent's detail page opens on its **Overview** tab. It summarizes the agent's goal, triggers, tools, knowledge and recent runs. A **Run Agent** button at the top right starts a run by hand. Each of the other tabs goes into one part in depth.

<figure>

![Overview tab of Oliv AI's Multithreader agent: tabs from Overview to Runs with a Run Agent button at the top right, then a header card, a Goal, one trigger chip, five tool chips, three knowledge file chips and the start of a Runs card.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_039_agent-detail_multi-threader_overview-tab_goal-triggers-tools-knowledge-summary-cards-run-agent-button.webp)

<figcaption>The Overview tab is the summary of an agent. Each card on it, from triggers to knowledge, has a tab of its own that goes into detail.</figcaption>
</figure>

| Part | Tab | What it tells you |
|---|---|---|
| [Instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) | **Instructions** | The agent's **Objective**, its numbered **Process** steps and its **Output** |
| [Tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) | **Tools** | Each action the agent may take, and how freely it takes it |
| [Triggers and schedules](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) | **Triggers** | The events and fixed times that start the agent on its own |
| [Knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) | **Knowledge** | The files the agent works against, each one open to view |
| [Run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) | **Runs** | Every run, with a full record of what the agent did |

Every agent's page has **Overview**, **Instructions**, **Tools** and **Runs**. **Triggers**, **Knowledge** and **Data** appear only on agents that use them. Some agents add a tab of their own, such as **Moments** on Oliv AI's Content Curator agent, or **Sequence** on an agent that runs outreach in steps.

Read the parts in order and you have the whole agent. The instructions say what it does, the tools say what it may touch, and the triggers say when it acts. The run history shows what actually happened.

## How much freedom an agent has {#autonomy}

Two settings decide how far an agent goes on its own.

- **Per tool.** On the **Tools** tab, **Auto Run** acts without asking, **Requires Approval** waits for a person to confirm, and **Agent Decides** judges whether to ask.
- **Per conversation.** In a chat with [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/), each conversation is set to **Ask before acting** or **Act without asking**.

Every run leaves evidence. Its record shows what that run produced: each email the agent wrote in full with the contacts it picked, a clipped call with its transcript, each step of an outreach sequence, or a drafted reply with the deal context behind it. So you can [check an agent's past runs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) before you give it more freedom. CRM updates follow the same path, from reviewed to automatic, in [keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/).

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
