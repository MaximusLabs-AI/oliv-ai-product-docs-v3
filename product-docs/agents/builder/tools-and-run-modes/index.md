# Agent tools and run modes

What an Oliv AI agent's tools are, how to set each tool's run mode to Auto Run, Requires Approval or Agent Decides, and which systems the tool catalog draws on.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/

A tool is one action an agent is allowed to take, such as looking up a record, drafting an email or posting to a channel. Every agent in the [Oliv AI agent marketplace](https://www.oliv.ai/agents-marketplace) with a detail page lists its tools on a **Tools** tab. Each tool carries a run mode that decides how much freedom the agent has with it: **Auto Run**, **Requires Approval** or **Agent Decides**.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What a tool is** | One action an agent is allowed to take |
| **Where tools live** | **Agents › [agent] › Tools**, on every agent with a detail page |
| **Run modes** | **Auto Run**, **Requires Approval**, **Agent Decides** |
| **Default mode** | **Auto Run**, for any tool that doesn't store a mode of its own |
| **Set for** | One tool on one agent at a time |
| **Tool catalog** | Salesforce, HubSpot, Gmail, Google Calendar, Outlook, LinkedIn and Slack |
| **Conversation setting** | **Ask before acting** or **Act without asking**, on Oliv AI's Olivia and Oliver agents |

## What agent tools and run modes are {#what-it-is}

Tools are what turn an agent from something that reads into something that acts. Each tool has a name, an icon and a one-sentence summary of what it does, and the agents described in the product hold between 3 and 8 tools each. The actions cover reading records, creating and updating them, logging calls, meetings and emails, sending and drafting email, managing calendar events and posting to channels.

The run mode is the second half. It sits on each tool card as a dropdown, and it applies to that one tool on that one agent. Changing it on one tool changes nothing else.

| Run mode | Icon | What the agent does with the tool |
|---|---|---|
| **Auto Run** | A filled lightning mark, indigo | Acts without asking |
| **Requires Approval** | A warning circle, rose | Waits for a person to confirm first |
| **Agent Decides** | A question mark, gray | Judges whether to ask |

### Where tool actions come from {#tool-sources}

The tool catalog groups actions by the system they come from. These are the same [apps Oliv AI works alongside](https://www.oliv.ai/integrations), from your CRM to your inbox.

| System | Tools offered | What they cover |
|---|---|---|
| **Salesforce** | 34, in 6 groups | **Lookup / Search**, **Create / Update**, **Associations**, **Activities**, **Pipeline / Forecast**, **Utility** |
| **Hubspot** | 31, in 6 groups | **Lookup / Search**, **Create / Update**, **Associations**, **Activities**, **Marketing**, **Utility** |
| **Gmail** | 9 | Send, retrieve, search, reply, draft, attach, label, read threads, delete |
| **Google Calendar** | 9 | Create, list, update and cancel events, read calendar details, find free slots |
| **Outlook** | 9 | Send, retrieve, search, reply, draft, attach, read calendar events, categorize, delete |
| **LinkedIn** | 9 | Read public profile, company and post information, and comment on a post |
| **Slack** | 5 | Send a message, read messages, create a channel, invite users, upload a file |

## Why agent tools and run modes matter {#why-it-matters}

### What it's for {#what-its-for}

Tools decide what an agent may do in your systems, and run modes decide how freely it does it. Together they're where you read and set an agent's permission to act. You make that call one action at a time, not once for the whole agent.

### How it helps {#how-it-helps}

- **Every action sits in one list.** Each card names the action and says in a sentence what it does, so nothing an agent can do is hidden.
- **Risk is set where it lives.** A record lookup and a stage update on the same agent can run under different modes.
- **Writes can wait for a person.** **Requires Approval** holds an action until someone confirms it.
- **Routine reads stay quick.** **Auto Run** lets low-risk actions happen without a prompt.

### What happens without it {#without-it}

Without a per-action setting, an agent's freedom is all or nothing. Either it writes to your CRM, mailbox and channels unchecked, or it only reads and every update still falls to a person. The first puts the records your forecast depends on at risk. The second loses most of the time the agent was meant to save.

### Why buyers care {#why-buyers-care}

This matters most to the people who own the systems agents write to: [revenue operations teams](https://www.oliv.ai/revops) and CRM admins. It matters at rollout, when a team first lets an agent change records or send mail. It matters again each time an agent gains a new tool, because a tool that stores no mode starts on **Auto Run**.

## The Oliv AI approach to agent tools and run modes {#approach}

{/* 5P */}

Picture a revenue operations lead getting ready to switch on an agent for a sales team of 40. The agent can look up Salesforce opportunities, log calls and change fields such as stage and close date. Lookups worry nobody. A wrong stage change, though, lands straight in Monday's forecast call.

The common answer is a single switch for the whole agent. Teams often keep it read-only for weeks and paste its suggestions into the CRM by hand. That probably feels safe. It also means the agent saves little time, and the pile of suggestions grows with every rep added.

The risk isn't spread evenly across the agent. It sits in the handful of actions that write to shared records or reach customers. Reading a record can't break anything, so it makes sense to hold back only the actions that can.

Oliv AI puts the control on each tool instead of on the agent. Every card on an agent's **Tools** tab carries its own run mode. The RevOps lead leaves lookups on **Auto Run** and sets stage and close date updates to **Requires Approval**. Call logging goes on **Agent Decides** while the team watches how the agent behaves.

You can see the setting on the tab itself. The three modes always appear in the same order, and each keeps one icon and color on the button and in the menu. How other platforms handle an agent's freedom to act is covered in How agent tools and run modes compare, below.

## Open an agent's tools {#open-tools}

There are three ways in:

- From the agent's detail page, select the **Tools** tab.
- On the **Overview** tab, press one of the agent's tool pills.
- On the [**Instructions** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/), press a tool chip inside a process step. The **Tools** tab opens with that tool scrolled into view.

The tab has two columns. A sidebar down the left holds **Add Tool** above the list of the agent's tools. The main pane on the right shows the same tools as cards, in the same order. Press a tool's name in the sidebar and its card scrolls into view.

## Set a tool's run mode {#set-run-mode}

1. Open the agent and select **Tools**.
2. Find the tool. Scroll the main pane, or press the tool's name in the sidebar.
3. Read the card: the tool's name as a heading, with a sentence beneath saying what it does.
4. Press the dropdown at the right of the card. It shows the tool's current mode with its icon.
5. Choose **Auto Run**, **Requires Approval** or **Agent Decides**. The menu closes and the button shows the new mode.
6. Repeat for each tool you want to change. To close the menu without changing anything, press anywhere outside it.

### Choosing a mode {#choosing-a-mode}

| Mode | A good fit for |
|---|---|
| **Auto Run** | Actions that only read, such as searching records or reading a public LinkedIn profile |
| **Requires Approval** | Actions that change shared records or reach customers, such as updating an opportunity or sending an email |
| **Agent Decides** | Actions where you're happy for the agent to judge when a check is worth it |

If you're weighing [how much an AI agent should do alone](https://www.oliv.ai/blog/ai-crm-trust-governance-risk-revops-evaluation), start writes on **Requires Approval** and widen them once you trust the output.

## Browse the tool catalog {#tool-catalog}

Press **Add Tool** at the top of the sidebar to open the catalog, a panel headed **Add Tool**. It shows the actions an agent could be given, grouped by the system they come from.

1. Pick a system in the list on the left. **Salesforce** is selected when the panel opens.
2. Read the main pane. It lists that system's tools under category headings, such as **Lookup / Search** or **Create / Update** for a CRM, and **Actions** for Gmail, Google Calendar, Outlook, LinkedIn and Slack.
3. Read each card: the tool's name, with a one-line description beneath.
4. Close the panel with the **×** at the top right, or press the dimmed page behind it.

The catalog is the same whichever agent you opened it from.

## How agent tools and run modes work with other features {#works-with}

### The Overview tab {#with-overview}

The **Overview** tab lists an agent's tools as pills. The **Tools** tab is where you set each tool's run mode.

### Instructions {#with-instructions}

The process steps on the [**Instructions** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/) name the tools each step uses. Pressing a tool chip there takes you to that tool's card, which is the quickest way to check the mode of a tool a step depends on.

### Olivia and Oliver conversations {#with-super-agents}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) and [Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) carry their own autonomy setting beneath the message box: **Ask before acting** or **Act without asking**. It covers a whole conversation, opens on **Ask before acting**, and is separate from any tool's run mode. Choosing **Act without asking** for Oliver shows a **High Risk** warning above the message box.

### Drafted emails and run records {#with-run-records}

An agent's [run records](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) show both outcomes of a run mode: emails sent automatically, and emails drafted and left for a person to send. That's where you see how [an agent that acts differs from a copilot that suggests](https://www.oliv.ai/blog/ai-agents-vs-ai-copilots).

## Who uses agent tools and run modes, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the settings are used.

### Revenue operations {#revenue-operations}

Before a rollout, a revops team walks each agent's **Tools** tab and lists every tool that writes to [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) or [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/). Those go to **Requires Approval** first. Read-only lookups stay on **Auto Run**, so the [CRM work agents take on](https://www.oliv.ai/blog/revops-automation) starts with a person checking each write.

### Sales development {#sales-development}

A [sales development team](https://www.oliv.ai/sales-development) lets an agent read public LinkedIn profiles and company posts on **Auto Run**. Sending email from Gmail or Outlook stays on **Requires Approval**, so no first touch reaches a prospect unseen. That keeps [AI outreach from burning through the target list](https://www.oliv.ai/blog/ai-sdr-tools).

### Customer success and account management {#customer-success}

A [customer success team](https://www.oliv.ai/customer-success) lets an agent post account updates to an internal [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) channel on **Auto Run**. Anything addressed to the customer, such as a reply in Gmail, waits on **Requires Approval**.

### Enablement {#enablement}

An enablement lead uses the one-line summaries on each tool card to brief new reps on what each agent may do in their accounts. The colored icons make it easy to point out which actions run unattended and which wait for a person.

## How agent tools and run modes compare {#compare}

Oliv AI sets an agent's freedom to act on each tool, with a choice of three modes. One of them lets the agent itself judge whether a check is needed. Its tools act in the systems revenue teams work in, from CRM records to email, calendars and Slack. Oliv AI is the only platform in this table that does all three.

Agent permissions, from each platform's public documentation:

| Platform | Approval choice for each agent action | Agent judges when to ask | Agent actions in connected apps |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Not in docs | Not in docs | [Outputs stay inside Gong](https://help.gong.io/docs/about-agents) |
| **Outreach** | Partly ([fixed check before record changes](https://support.outreach.io/support/solutions/articles/159000435308-outreach-product-release-notes-september-2026)) | Not in docs | Partly ([read-only connector tools](https://support.outreach.io/support/solutions/articles/159000432173-mcp-connectors)) |
| **Fireflies.ai** | Partly ([allow or block per app](https://guide.fireflies.ai/articles/7673197830-connect-a-custom-mcp-server-to-askfred)) | Not in docs | Yes ([custom connectors](https://guide.fireflies.ai/articles/1512776728-global-askfred-get-answers-from-past-meetings-connected-apps-and-web-search)) |
| **Avoma** | Not in docs | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for agent tools and run modes {#compare-stronger}

- **Approval set per action.** Oliv AI gives each tool its own run mode, so lookups and writes on one agent can differ. [Outreach's Omni pauses for confirmation before any change to a Prospect, Account or Opportunity record](https://support.outreach.io/support/solutions/articles/159000435308-outreach-product-release-notes-september-2026).
- **Agents that act beyond their own app.** Oliv AI's tools update CRM records, send email and post to Slack. [Gong's help center says its agents generate outputs within Gong Assistant and do not perform actions in external systems](https://help.gong.io/docs/about-agents). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **Writes as well as reads.** Oliv AI's catalog includes **Create / Update** tools for Salesforce and HubSpot. [Outreach's help center says only read-only tools are supported over its connectors at this time](https://support.outreach.io/support/solutions/articles/159000432173-mcp-connectors).
- **A middle setting between asking and acting.** With **Agent Decides**, the agent judges whether to ask before it uses a tool. [Fireflies.ai documents choosing which permissions AskFred has in each connected app](https://guide.fireflies.ai/articles/7673197830-connect-a-custom-mcp-server-to-askfred).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **One tool at a time.** There's no bulk control, and no agent-wide or workspace-wide default mode.
- **Auto Run is the default.** A tool that stores no mode shows **Auto Run**. Check new tools before an agent goes live.
- **Tools can't be removed or reordered.** There's no delete control on a tool card or in the sidebar.
- **Tools have no settings of their own.** There are no parameters, field mappings or filters, so you can't limit a tool to certain records or fields.
- **No connection status.** The tab doesn't show whether a tool's system is connected.

## Common questions {#common-questions}

#### What is a tool in Oliv AI? {#faq-what-is-a-tool}

A tool is one action an agent is allowed to take, such as finding a record, drafting an email or posting to a channel. Each one is listed on the agent's **Tools** tab with a one-line summary.

#### What run mode does a new tool start on? {#faq-default-mode}

**Auto Run**, unless the tool stores a different mode. That means the agent acts without asking, so set writes to **Requires Approval** if you want a person to check them.

#### What's the difference between Requires Approval and Agent Decides? {#faq-approval-vs-decides}

With **Requires Approval**, a person confirms before the agent uses the tool. With **Agent Decides**, the agent judges for itself whether to ask first.

#### Can I set every tool on an agent at once? {#faq-bulk}

No. Each tool is set on its own card, one at a time. There's no agent-wide or workspace-wide default.

#### Which systems can tools come from? {#faq-systems}

Seven: [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/), plus Gmail, Google Calendar, Outlook, LinkedIn and [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/). Salesforce offers 34 tools and HubSpot 31; Slack offers 5 and the others 9 each.

#### Can I remove a tool from an agent? {#faq-remove}

No. There's no delete control on the tool card or in the sidebar.

#### Is Ask before acting the same as Requires Approval? {#faq-ask-before-acting}

No. **Ask before acting** covers a whole conversation with Oliv AI's Olivia or Oliver agent. **Requires Approval** covers one tool on one agent, and the two are set separately.

#### Can I limit a tool to certain records or fields? {#faq-limit-records}

No. Tools carry no parameters, field mappings or filters.

## Related {#related}

- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): how agents send a brief before your calls.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Browse agents in the marketplace](https://www.oliv.ai/agents-marketplace): the agents whose tools this page describes.
- [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/): the agent that writes field updates back to your CRM.
- [How the agents are built](https://www.oliv.ai/oliv-tech): the platform layer each agent's tools run on.
- [AI agents for RevOps](https://www.oliv.ai/blog/ai-agents-for-revops): where agents fit in a revenue operations team.
- [Salesforce automation explained](https://www.oliv.ai/blog/salesforce-automation): how agent actions compare with flows and rules.
- [Agentic sales automation](https://www.oliv.ai/blog/agentic-sales-automation): what changes when software acts, not just suggests.
- [Connected apps](https://www.oliv.ai/integrations): the systems Oliv AI connects to.
