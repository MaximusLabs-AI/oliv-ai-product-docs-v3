# No code AI agent builder: how an Oliv AI agent is set up and how much it may do alone

Before an agent acts on your CRM and inbox, use this no-code AI agent builder guide to check what it does, how much it may do alone, when it starts, what it reads and what it did.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/

Oliv AI is a no-code AI agent builder, so you set up agents without writing code. Before you let one touch your CRM and inbox, you want to know what it will do without asking. Open **Agents** in the sidebar, press **View Agent** on the agent you're checking, and go to the tab that answers your question. If this is your first look at an agent, work through its tabs in the order below.

This page works with the agents already in your marketplace. If none of them fits the job, the section on custom agents below tells you who to ask.

## Open the tab that answers your question {#agent-parts}

Each agent's detail page opens on **Overview**, which summarizes its goal, triggers, tools, knowledge and recent runs. Start there for a quick read, then take the tab that matches your question.

<figure>

![Overview tab of Oliv AI's Multithreader agent: tabs from Overview to Runs with a Run Agent button at the top right, then a header card, a Goal, one trigger chip, five tool chips, three knowledge file chips and the start of a Runs card.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_039_agent-detail_multi-threader_overview-tab_goal-triggers-tools-knowledge-summary-cards-run-agent-button.webp)

<figcaption>The Overview tab is the summary of an agent. Each card on it, from triggers to knowledge, has a tab of its own that goes into detail.</figcaption>
</figure>

| Your question | Open | What to check there |
|---|---|---|
| What will this agent do? | [Instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) | The **Objective**, the numbered **Process** steps and the **Output**. Each step names the tool it uses. |
| How much may it do alone? | [Tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) | The run mode on each action: **Auto Run**, **Requires Approval** or **Agent Decides**. |
| When does it start? | [Triggers](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) | The events and fixed times that start it without anybody pressing anything. |
| What does it read? | [Knowledge](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) | The files it works against. Press **View** to open one, or add your own. |
| What has it done? | [Run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) | Each run, whether it was **Auto-triggered** or **Manually run**, with the full record behind **View**. |

Every agent's page has **Overview**, **Instructions**, **Tools** and **Runs**. **Triggers**, **Knowledge** and **Data** appear only on agents that use them, so don't hunt for a tab that isn't there. Some agents add a tab of their own, such as **Moments** on Oliv AI's Content Curator agent, or **Sequence** on an agent that runs outreach in steps. **Run Agent** at the top right starts a run by hand.

### Go through a new agent in this order {#check-order}

1. **Read [the instructions](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/).** Confirm the job is the one you expected, because you can read this tab but not edit it. If the steps don't suit you, look for another agent or request a custom one. Press a tool's name in any step to jump to that tool, so you can see which action the step relies on.
2. **Set the tools.** A run mode applies to one tool on one agent, and changing it changes nothing else. A tool with no stored mode runs on **Auto Run**, so go through every card rather than assume anything waits for a person.
3. **Read [the triggers](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/).** An agent with an Auto Run tool and a trigger can act with no person involved at any point. Skip this step and the first you hear of an action may be its run record.
4. **Check [the knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/).** These are the background the agent works against, so an out-of-date deck shapes its work. A file can't be removed from an agent, so look it over before you upload it.
5. **Read the runs.** Do this before you loosen any run mode. A run says it was **Auto-triggered**, not which trigger started it.

## Decide how much an agent may do alone {#autonomy}

Say an agent holds tools that update CRM records and send email, and your team wants to know who signs off. Two settings decide that.

- **Per tool.** On the **Tools** tab, **Auto Run** acts without asking, **Requires Approval** waits for a person to confirm, and **Agent Decides** judges whether to ask.
- **Per conversation.** In a chat with [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) or Oliv AI's Oliver agent, each conversation is set to **Ask before acting** or **Act without asking**. It opens on **Ask before acting**. Setting Oliver to act without asking lets him change your settings, so switch only when you mean that.

### Check the runs before you give more freedom {#before-more-freedom}

Start any tool that writes to your CRM or sends email on **Requires Approval**. Then [read the agent's past runs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/). A record shows what that run produced: each email in full with the contacts the agent picked, a clipped call with its transcript, each step of an outreach sequence, or a drafted reply with the deal context behind it.

Move a tool to **Agent Decides** or **Auto Run** only once those records look right. If they don't, leave it waiting for a person and go back to the instructions and knowledge files. Oliv AI's Multithreader agent shows a useful pattern: it fires on its own when a deal's stage is set to Proposal, and it leaves its outreach as drafts for the seller to review. CRM updates follow the same path, from reviewed to automatic, in [keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/).

## Find the agents available to your team {#marketplace}

Open **Agents** in the main sidebar. The marketplace is the single place you see every agent available to you, each as a card with a picture, a name, a short description and one button. Press **View Agent** to open that agent's detail page, and **Back to Marketplace** to return. **Clone Agent** appears on template agents, as the way to take one as a starting point.

<figure>

![The Agents marketplace on the All filter: five filter buttons and a Search box above a grid of agent cards such as Multithreader, Quick Qualifier and Comms Manager with a Custom badge, each with View Agent or Clone Agent, and Oliver's chat panel at the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_031_agents-marketplace_all-tab_nine-agent-cards-view-agent-and-clone-agent-buttons-category-filters-search-oliver-chat-panel-open.webp)

<figcaption>The marketplace is where every agent starts. Cards show what each agent does and whether you view it or clone it, with Oliv AI's Oliver agent on hand for questions.</figcaption>
</figure>

If you don't know an agent's name, type what it does in the search box at the right. Search matches each agent's name and description. To see the pre-built agents grouped by the roles they serve, use the [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) on oliv.ai.

<figure>

![The Agents marketplace with renewal typed in the Search box and the All filter selected. Two cards remain: Renewal Radar with a Clone Agent button, and QBR Builder with a Pre-built badge and a View Agent button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_038_agents-marketplace_agents-page_search-box-typed-renewal_all-tab-filtered-to-renewal-radar-and-qbr-builder.webp)

<figcaption>Search matches the description as well as the name. Typing renewal keeps Renewal Radar by its name and QBR Builder by its description.</figcaption>
</figure>

### Narrow the list by team and badge {#categories-and-badges}

Agents are grouped by the revenue team they serve. Use the five buttons above the grid to narrow the list: **All**, **Our Agents**, **Sales**, **Revenue Operations** and **Customer Success**. The buttons and the search box work together, so an agent must match both to stay listed. If the list looks too short, set the button back to **All** first.

A **Pre-built** or **Custom** badge on a card tells you where that agent came from. For a question about agents, use the chat with [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) on the right of the marketplace, so you don't leave the screen. The panel has its own new chat and history buttons, a suggested question to start from and the **Ask before acting** setting under the message box.

<figure>

![The Agents marketplace filtered to Customer Success: seven cards with View Agent buttons. QBR Builder, Portfolio Manager and Meeting Assistant carry a Pre-built badge, and the other four carry a Custom badge. Oliver's chat panel sits at the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agents-marketplace/oliv-ai_037_agents-marketplace_agents-page_customer-success-category-tab-selected_seven-agent-cards-qbr-builder-portfolio-manager-meeting-assistant-pre-built-and-custom-badges.webp)

<figcaption>A category button narrows the grid to one team's agents. Pre-built and Custom badges mark where each agent came from, and both kinds open the same detail page.</figcaption>
</figure>

## Check what sits around the agent {#working-together}

An agent's tabs show you one agent. When its behavior depends on the rest of your setup, look here next.

To change which agents are active, what they monitor or what thresholds trigger their actions, go to Oliv AI's Oliver agent. RevOps managers talk to Oliver in natural language to define and update the sales process, and Oliver keeps the playbook current. Oliv AI's Olivia agent runs the frontline and routes work to the right specialist agent. Each agent gets the tools, memory, permissions and guardrails for the job, scoped to the task at hand.

### If your CRM data is messy {#shared-context}

You can still start. Every agent and every rep works from the same [context graph](https://www.oliv.ai/context-graph), and Olivia reads what's already there, messy data included. [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) doesn't need a clean CRM to start. When you override one of Forecaster's recommendations, it learns from that feedback.

### If alerts come too often or in the wrong place {#thresholds-and-delivery}

Look for the agent's thresholds first. With [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), inactivity windows, field completion requirements and deal value thresholds are configurable per manager or per team. Then check where the agent delivers its work: Deal Driver reaches you in [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/), email or the Oliv AI app. Tools in the catalog act in systems such as [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/), so read the page for the system an agent will write to.

## Request a custom agent when nothing fits {#custom-agents}

If no card fits the job, ask for one. The marketplace on oliv.ai offers pre-built agents designed for specific challenges, and invites you to request a custom agent. Oliv AI's GTM engineering team stays with you after launch. It reviews agent output, tunes the playbook and adds custom agents as your territory, comp or ICP shifts, as the [RevOps page](https://www.oliv.ai/revops) describes.

A custom agent has the same parts as every other, so check it in the same order. If you're still weighing up your options, [this build vs buy post](https://www.oliv.ai/blog/build-vs-buy-sales-ai) covers when a custom agent makes sense.

## Next steps {#next-steps}

- If you're ready to decide which actions wait for a person, [set run modes on each tool](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).
- If you're planning who gets which agent and when, follow the [30-day rollout plan](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/getting-started/plan-your-deployment/).
- If you need the whole lineup first, open the [agents overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/) to see how Olivia, Oliver and the specialist agents fit together.
- If CRM updates are your first concern, open [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/), the agent that moves from reviewed to automatic updates.
- If you want to see agents at work on a deal, [run a pipeline review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) with Deal Driver's per-rep reports, or [record a meeting and follow up](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/).
