# Agent instructions

What an Oliv AI agent's instructions are, how to read its Objective, Process and Output on the Instructions tab, and how to trace each process step to the tool it uses.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/

Every Oliv AI agent with a detail page carries a written statement of what it is for and how it goes about its work. The **Instructions** tab shows it in three parts: **Objective**, **Process** and **Output**. Each process step names the tools it uses, and pressing a tool takes you straight to it.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What instructions are** | A written statement of what an agent does and how |
| **Where they live** | **Agents › [agent] › Instructions**, the second tab after **Overview** |
| **Sections** | **Objective**, **Process**, **Output** |
| **Process steps** | 3 to 7 per agent, each with a title and a description |
| **Output items** | 1 to 4 per agent, where the agent has any |
| **Tool chips** | Inside each step; pressing one opens that tool on the **Tools** tab |
| **Navigation** | A contents list down the left |

## What agent instructions are {#what-it-is}

Instructions are how you understand an agent before you trust it. They spell out, in plain prose, what the agent is trying to achieve, the steps it takes and what it hands back. Every agent that has a detail page carries them.

| Section | What it says | Always shown |
|---|---|---|
| **Objective** | A short paragraph on what the agent is trying to achieve | Yes |
| **Process** | A numbered list of steps, each with a short title and a description | Yes, with at least one step |
| **Output** | A numbered list of what the agent produces, each with a title and a description | Only when the agent has output items |

Within a step's description, each tool the step uses appears as a small bordered chip with the tool's name and icon. A step may carry a main tool chip and further chips below it, one per line, each with its own description. That lets you see which outside action each part of the agent's work depends on.

The tab opens with a header card carrying the agent's picture, its name and its one-line description. The **Overview** tab carries a separate, shorter **Goal** statement.

## Why agent instructions matter {#why-it-matters}

### What it's for {#what-its-for}

Instructions tell you what an agent will do before it does it. They lay out the agent's aim, its method and its results in words a sales team can read. They also show which tool each step relies on.

### How it helps {#how-it-helps}

- **The method is in writing.** **Process** lists every step in order, with a title and a description.
- **Results are named up front.** **Output** says what the agent produces, so nobody guesses.
- **Steps lead to tools.** Pressing a tool chip opens that tool and its approval setting.
- **Long instructions stay easy to move through.** The contents list jumps to any section or step.

### What happens without it {#without-it}

Without written instructions, an agent's method is a guess. A leader can't tell whether it follows the way the team sells. Reps get output with no account of how it was reached, and trust in the agent fades.

### Why buyers care {#why-buyers-care}

This matters most to [sales leaders](https://www.oliv.ai/sales-managers), who answer for how their team sells. It matters before an agent reaches the team, when a leader decides whether to back it. It matters again when the sales method changes, because the steps should still match it.

## The Oliv AI approach to agent instructions {#approach}

{/* 5P */}

Imagine a sales director who has spent a year getting her team to qualify every deal the same way. Reps confirm the pain, the decision process and the economic buyer before a deal moves on. Now she wants an agent working those deals, and she wants that method in its steps.

Often an agent arrives as a black box with a one-line summary. Leaders tend to judge it by its first few outputs, which may take weeks to gather. By then reps have formed a view, and a step that skips the method is hard to spot.

The method is a sequence, so the agent's work should read as one. If its steps are written down in order, a leader can lay them beside the qualification method and check each one. Any gap shows up on the page, not in a lost deal.

Oliv AI writes each agent's method out on its **Instructions** tab. **Objective** states the aim, **Process** lists the numbered steps, and **Output** names what the agent produces. The sales director reads **Process** step by step against her method. Where a step relies on a tool, she presses its chip and checks how freely it acts.

The steps are on the tab for anyone to read. Each one has a title and a description, and the tools it uses appear as chips inside the text. How other platforms describe what an agent does is covered in How agent instructions compare, below.

## Read an agent's instructions {#read-instructions}

1. Open the agent from the [agent marketplace](https://www.oliv.ai/agents-marketplace) and select the **Instructions** tab, the second tab after **Overview**.
2. Read the header card at the top: the agent's picture, name and one-line description.
3. Read **Objective**, a short paragraph on what the agent is trying to achieve.
4. Read **Process**. Each numbered step has a short title in bold and a description beneath.
5. Read **Output**, if the agent has one: a numbered list of what it produces.

Steps are numbered from 1 in the order they're stored.

## Trace a step to its tool {#trace-to-tool}

1. Find a tool chip inside a step's description. It's a small bordered pill with the tool's name and icon.
2. Press the chip. The page switches to the **Tools** tab with that tool scrolled into view.
3. Read the tool's card: what it does, and its run mode, such as **Auto Run** or **Requires Approval**.

The run mode decides whether that action needs a person's approval, as the guide to [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains. Every chip opens the **Tools** tab, wherever it sits in a step.

## Move around with the contents list {#contents-list}

The contents list runs down the left of the tab. The text pane on the right scrolls on its own.

- **Top-level entries**, such as **Objective**, **Process** and **Output**, appear in darker, heavier text. Pressing one scrolls to that section.
- **Indented entries** name each process step and output item, in lighter text. Pressing one scrolls to it and marks it as the active entry. Pressing it again clears the mark.

## How agent instructions work with other features {#works-with}

### Tools and run modes {#with-tools}

Instructions name the tools; the **Tools** tab sets how freely each one runs. Reading a step and then its tool's mode shows you both what the agent does and how much it does unasked.

### The Overview tab {#with-overview}

The **Overview** tab gives a short **Goal** statement and lists the agent's tools as pills. The **Instructions** tab is the longer account of the same agent.

### Knowledge and triggers {#with-knowledge-and-triggers}

On agents that have them, the [**Knowledge** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) lists the files an agent works against, and the [**Triggers** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) lists what starts it. Read them with the instructions to see the full picture of an agent.

### Deal work {#with-deal-work}

Instructions are where you check how an agent handles the deal work it takes on. That includes the [brief before a customer call](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) and the [daily deal work an account executive runs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Who uses agent instructions, and how {#who-uses-it}

These are typical patterns, shown to illustrate how the tab is used.

### Account executives and sales leaders {#account-executives-and-sales-leaders}

A front-line manager reads an agent's **Process** before a team meeting and walks reps through each step. An [account executive](https://www.oliv.ai/account-executives) checks **Output** to know what the agent will hand over on a deal.

### Revenue operations {#revenue-operations}

A [revenue operations team](https://www.oliv.ai/revops) presses every tool chip in an agent's **Process**. It lists the steps that write to the CRM or reach customers, then checks each tool's run mode before a rollout.

### Enablement {#enablement}

An enablement lead uses **Objective**, **Process** and **Output** as a ready-made outline when training reps on a new agent. The contents list makes it easy to jump to the step a rep asks about.

### Customer success and account management {#customer-success}

A [customer success team](https://www.oliv.ai/customer-success) reads the instructions of agents that work its accounts. It checks the steps before a renewal, so nobody is surprised by what the agent sends.

## How agent instructions compare {#compare}

Oliv AI writes each agent's method out in three parts: what it aims for, the numbered steps it takes and what it produces. Each step names the tools it uses, and each tool links to its approval setting. Oliv AI is the only platform in this table that does all three.

Agent instructions, from each platform's public documentation:

| Platform | Objective, process and output written out | Each step names the tools it uses | Step links to the tool's approval setting |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([one free-text Instructions prompt](https://help.gong.io/docs/create-an-on-demand-agent)) | Partly ([actions run in sequence](https://help.gong.io/docs/create-an-automated-agent)) | Not in docs |
| **Outreach** | Partly ([pre-defined MEDDPICC fields and prompts](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) | Not in docs | Not in docs |
| **Fireflies.ai** | Partly ([one set of instructions per skill](https://guide.fireflies.ai/articles/6161594443-learn-about-ai-skills-create-automated-workflows-from-your-meetings)) | Not in docs | Not in docs |
| **Avoma** | Partly ([saved prompts in a Prompt Library](https://help.avoma.com/prompt-library)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for agent instructions {#compare-stronger}

- **A method you can read in order.** Oliv AI shows each agent's **Process** as numbered steps, each with a title and a description. [Gong's agent builder asks for a prompt describing what you want the agent to do](https://help.gong.io/docs/create-an-on-demand-agent). See [Oliv AI as a Gong alternative](https://www.oliv.ai/blog/gong-vs-oliv).
- **Steps tied to the tools they use.** Oliv AI draws each tool as a chip inside the step that uses it. [Outreach's Deal Agent starts MEDDPICC users on pre-defined fields and prompts](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview). See [how Gong and Outreach compare](https://www.oliv.ai/blog/gong-vs-outreach).
- **Instructions kept on the agent.** Oliv AI keeps the **Objective**, **Process** and **Output** on each agent's own tab. [Avoma keeps prompts in a central Prompt Library for Global Ask Avoma](https://help.avoma.com/prompt-library). See [Avoma vs Oliv AI](https://www.oliv.ai/blog/avoma-vs-oliv-ai).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Read-only.** There's no text field, **Edit** or **Save** control anywhere on the tab.
- **No history.** There's no version history, author or last-changed date.
- **No export.** You can't export, print or copy the instructions as a block.
- **No search.** The text can't be searched; the contents list is the way to move around it.
- **Only agents with a detail page.** An agent without a detail page has no **Instructions** tab.
- **Output can be missing.** An agent with no output items shows no **Output** heading at all.

## Common questions {#common-questions}

#### Where do I see what an agent actually does? {#faq-where}

Open the agent and select the **Instructions** tab. **Objective** says what it's for, **Process** lists its steps and **Output** lists what it produces.

#### Can I edit an agent's instructions? {#faq-edit}

Not from the **Instructions** tab. It has no text field, **Edit** or **Save** control, so the instructions are read-only there.

#### How do I tell which tools a step uses? {#faq-which-tools}

Tool names appear as small chips inside each step's description. Pressing one opens that tool on the **Tools** tab.

#### How do I check whether a step needs approval? {#faq-approval}

Press the tool chip in that step. The **Tools** tab opens on that tool, and its run mode shows whether the action needs a person's approval.

#### How many steps does an agent's process have? {#faq-how-many-steps}

Between 3 and 7 across the agents in the product.

#### Why does one agent have no Output section? {#faq-no-output}

The **Output** section is hidden when an agent has no output items stored.

#### Can I see who wrote the instructions, or when they changed? {#faq-author}

No. No author, version or date is recorded on the tab.

#### How is the Goal on the Overview tab different? {#faq-goal}

The **Goal** on the **Overview** tab is a short statement kept separately from the instructions. The **Instructions** tab is the full account, in three sections.

#### Why does this agent have no Instructions tab? {#faq-no-tab}

Only agents with a detail page have instructions, so an agent without one has nothing to show.

## Related {#related}

- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): set the approval mode for each tool a step uses.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): ask Oliv AI's Olivia agent about deals and pipeline.
- [Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): how Oliv AI's Deal Driver agent works on open deals.
- [Your playbook, written for agents](https://www.oliv.ai/process-graph): how Oliv AI captures your revenue process.
- [Sales methodology](https://www.oliv.ai/sales-methodology): how Oliv AI supports the way your team sells.
- [MEDDIC sales methodology guide](https://www.oliv.ai/blog/meddic-sales-methodology): training on MEDDIC and making it stick.
- [Auto-scoring MEDDIC, BANT and SPICED](https://www.oliv.ai/blog/sales-methodology-automation-auto-score-meddic-bant-spiced-from-calls): qualification scored from calls.
- [The AI adoption ladder for revenue teams](https://www.oliv.ai/blog/gtm-ai-maturity-model): from one-off prompts to agents.
- [Oliv AI for sales leaders](https://www.oliv.ai/blog/oliv-ai-sales-leader-vp-sales-agent-features): how each agent helps a sales leader.
