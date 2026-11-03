# AI agent instructions: how to read an agent's process and trace each step to its tool

How to read AI agent instructions in Oliv AI: the Objective, Process and Output on the Instructions tab, and how to trace each process step to the tool it uses.

- Applies to: Every agent with a detail page
- Status: Live
- Verified: 2026-11-03
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/instructions/

Before an agent does a real run, you should be able to read exactly what it will do, and AI agent instructions are where you read it. Oliv AI puts them on an **Instructions** tab on every agent with a detail page, in three parts: **Objective**, **Process** and **Output**. Each step names its tools, and pressing one opens its card, where the run mode shows whether that action needs a person's approval.

<figure>

![Instructions tab of Oliv AI's Multithreader agent: a contents list at left with Objective, five numbered Process steps and two Output items, and at right the agent's header card, its Objective and the first three Process steps, each with a tool chip.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_041_agent-detail_multi-threader_instructions-tab_objective-process-output-contents-list-steps-with-tool-chips.webp)

<figcaption>The Instructions tab sets out an agent's method in writing. The contents list on the left jumps to each part, and every step names the tool that carries it out.</figcaption>
</figure>

## At a glance {#at-a-glance}

| | |
|---|---|
| **What instructions are** | A written statement of what an agent does and how |
| **Where they live** | **Agents › [agent] › Instructions**, the second tab after **Overview** |
| **Sections** | **Objective**, **Process**, **Output** |
| **Process steps** | Typically 3 to 6 per agent, each with a title and a description |
| **Output items** | Typically 1 to 3 per agent, where the agent has any |
| **Tool chips** | Inside each step; pressing one opens that tool on the **Tools** tab |
| **Navigation** | A contents list down the left |

## What agent instructions are {#what-it-is}

Instructions are how you understand an agent before you trust it. They spell out, in plain prose, what the agent is trying to achieve, the steps it takes and what it hands back.

| Section | What it says | Always shown |
|---|---|---|
| **Objective** | A short paragraph on what the agent is trying to achieve | Yes |
| **Process** | A numbered list of steps, each with a short title and a description | Yes, with at least one step |
| **Output** | A numbered list of what the agent produces, each with a title and a description | Only when the agent has output items |

Within a step's description, each tool the step uses appears as a small bordered chip with the tool's name and icon. A step can carry two chips when it uses two tools, such as one for an inbox and one for team chat. That lets you see which outside action each part of the agent's work depends on.

<figure>

![The complete Multithreader instructions: a header card, an Objective, five Process steps from assessing buying committee strength to notifying the owner, each with a tool chip, and two Output items, including a Slack notification template with placeholders for the owner, deal and drafts link.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_042_agent-detail_multi-threader_instructions-tab_objective-five-step-process-and-output-with-slack-message-template_full-length.webp)

<figcaption>A full set of instructions reads top to bottom: what the agent aims for, the five steps it takes, and what it hands back, down to the wording of its Slack message.</figcaption>
</figure>

Steps can hold more than plain prose:

- **Conditions.** A step title can set a rule, such as "If coverage is weak, then find new stakeholders".
- **Criteria.** A step can list its rules under bold labels, such as **Territory** and **Company size**.
- **Mentions.** A routing step can name a rep pool as an @-mention chip, such as **@enterpriseAE**.
- **Highlights.** Key values, such as when the agent should start, are picked out in bold or color.
- **Templates.** An output can give the exact message the agent sends, with placeholders such as `{{deal_name}}`.

<figure>

![Instructions tab of Oliv AI's Quick Qualifier agent: a contents list with Objective and five Process steps, and a pane showing the Objective, an Enrich lead and company tool chip, disqualifying criteria under bold Territory and Company size labels, and routing rules with an @enterpriseAE pool chip.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_075_agent-detail_quick-qualifier_instructions-tab_objective-process-pull-context-qualify-route-script-log-to-crm.webp)

<figcaption>Instructions can carry real rules: who to disqualify by territory and size, and which rep pool gets each lead, named as an @-mention chip. The territory and size limits on screen are sample rules, not defaults.</figcaption>
</figure>

## Why agent instructions matter {#why-it-matters}

### What it's for {#what-its-for}

Use the tab to decide whether an agent is ready for your team. Compare its steps with how your team sells, then check which tool each step relies on. If a step doesn't match, you know before reps see its output.

### How it helps {#how-it-helps}

- **The method is in writing.** **Process** lists every step in order, with a title and a description.
- **Results are named up front.** **Output** says what the agent produces, so nobody guesses.
- **Steps lead to tools.** Pressing a tool chip opens that tool and its approval setting.
- **Long instructions stay easy to move through.** The contents list jumps to any section or step.

### What happens without it {#without-it}

Without written instructions, an agent's method is a guess. A leader can't tell whether it follows the way the team sells. Reps get output with no account of how it was reached, so they have nothing to check it against.

### Why buyers care {#why-buyers-care}

[Sales leaders](https://www.oliv.ai/sales-managers) feel this most, because they answer for how their team sells. They need the written steps when deciding whether to back an agent. They need them again when the sales method changes, because the steps should still match it.

## The Oliv AI approach to agent instructions {#approach}

{/* 5P */}

Imagine a sales director who has spent a year getting her team to qualify every deal the same way. Reps confirm the pain, the decision process and the economic buyer before a deal moves on. Now she wants an agent working those deals, and she wants that method in its steps.

Often an agent arrives as a black box with a one-line summary. Leaders tend to judge it by its first few outputs, which may take weeks to gather. By then reps have formed a view, and a step that skips the method is hard to spot.

The method is a sequence, so the agent's work should read as one. If its steps are written down in order, a leader can lay them beside the qualification method and check each one. Any gap shows up on the page, not in a lost deal.

Oliv AI writes each agent's method out on its **Instructions** tab. The sales director reads **Process** step by step against her method. Where a step relies on a tool, she presses its chip and checks how freely it acts.

Each step has a title and a description, and its tools appear as chips inside the text. The tab shows the agent's method, not what happened on a live deal, so she still checks real runs once it's working. The comparison further down shows how other platforms describe what an agent does.

## Read an agent's instructions {#read-instructions}

1. Open the agent from the [agent marketplace](https://www.oliv.ai/agents-marketplace) and select the **Instructions** tab, the second tab after **Overview**.
2. Read the header card at the top: the agent's picture, name and one-line description.
3. Read **Objective**, a short paragraph on what the agent is trying to achieve. If that isn't the job you want done, stop here.
4. Read **Process**. Each numbered step has a short title in bold and a description beneath. Note any step that's missing or out of order for how your team sells.
5. Read **Output**, if the agent has one: a numbered list of what it produces.

## Trace a step to its tool {#trace-to-tool}

1. Find a tool chip inside a step's description. It's a small bordered pill with the tool's name and icon.
2. Press the chip. The page switches to the **Tools** tab with that tool scrolled into view.
3. Read the tool's card: what it does, and its run mode, such as **Auto Run** or **Requires Approval**.

The run mode decides whether that action needs a person's approval, as the guide to [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains.

<figure>

![The complete instructions of Oliv AI's Comms Manager agent: five Process steps, the first carrying two chips, Monitor inbox and Monitor Teams and Slack, then Read deal context, Prioritize message, Draft reply and Notify seller, and three Output items ending in a manager escalation.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_094_agent-detail_comms-manager_instructions-tab_five-process-steps-three-outputs-48-hour-manager-escalation_full-length.webp)

<figcaption>Every chip names a tool you can trace. Here the Draft reply step also states its own rule in words: never send without the seller's approval.</figcaption>
</figure>

## Move around with the contents list {#contents-list}

The contents list runs down the left of the tab. The text pane on the right scrolls on its own.

- **Top-level entries**, such as **Objective**, **Process** and **Output**, appear in darker, heavier text. Pressing one scrolls to that section.
- **Indented entries** name each process step and output item, in lighter text. Pressing one scrolls to it and marks it as the active entry. Pressing it again clears the mark.

Long entries are cut short with an ellipsis, so the list stays one line per step.

<figure>

![Instructions tab of Oliv AI's Product Release Messenger agent: a contents list with Objective, three Process steps and one Output item, some cut short with an ellipsis, beside a pane showing the Objective and three steps with Monitor Slack channel, Read Slack message and Draft email chips.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_118_agent-detail_product-release-messenger_instructions-tab_outline-objective-detect-release-announcement-understand-items-draft-email.webp)

<figcaption>The contents list mirrors the instructions. On a short agent like this one, three steps and one output fit in view at once.</figcaption>
</figure>

## How to check what an AI agent will do before it runs {#methods}

You have four ways to check an agent, and each one catches something different. Work through them in this order, because the first three happen before the agent touches a live record.

### Read the written process {#check-written-process}

Reading catches a step that's missing, out of order or at odds with how your team sells. It also shows you what the agent hands back. It misses how the agent behaves on a messy real deal.

Don't let clear writing settle the question. Writing about AI chat interfaces, Nielsen Norman Group warns that [people who don't know the limits see a confident, plausible explanation and trust the output](https://www.nngroup.com/articles/explainable-ai/). Written instructions aren't chat answers, but the same habit applies. A tidy description is where your check starts, not where it ends.

### Trace each step to what it can touch {#check-what-it-touches}

Tracing shows which steps only read and which ones write or send. It won't show how far a single write travels in the connected system, so ask what else depends on the field.

HubSpot shows why this matters. [Moving a deal into a closed-won or closed-lost stage sets its close date to today](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties) unless that automation is turned off. Its [weighted amount is the amount multiplied by the deal probability](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties), so a change to either one moves that figure too. One step on the page can change more than one number in a report.

### Judge the approval points {#check-approval-points}

Approval settings show where a person stands between the agent and your customer, but not whether that person really reads what they're approving.

Putting approval on every step isn't the safe answer. Nielsen Norman Group's guidance on confirmation dialogs says [if you warn people too much, they stop paying attention](https://www.nngroup.com/articles/confirmation-dialog/), and it saves them for actions that cannot be undone or carry serious consequences. That guidance is about software dialogs, but an approval queue asks people the same question. Keep approval for the steps you'd hate to see go wrong.

### Review real runs afterward {#check-real-runs}

Run records show what the agent actually did on a real deal. They come too late to stop anything, so they back up the first three checks and don't replace them.

### What Oliv AI shows for each check {#what-oliv-shows}

Oliv AI gives you a screen for each of the four. The **Instructions** tab holds the written process, and its chips lead to the **Tools** tab. The dropdown on each tool card shows the run mode. The [**Runs** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/) lists past runs, and each record logs the changes that run made elsewhere, with a timestamp. Deciding what a write can reach, and which steps deserve approval, stays with you.

## How to measure how much an agent does on its own {#measure-autonomy}

Once you've traced the steps, you can put two numbers on the agent. Neither one tells you the agent is safe. They tell you where to spend your reading time.

- **Action share.** Steps that write or send, divided by all the steps in **Process**. A higher share means more of the work reaches your CRM, inbox or chat channels.
- **Steps acting alone.** Steps that write or send with no person's approval in front of them. This is the number that sets your reading order.

### Where these counts mislead {#measure-weak-spots}

Both numbers count steps, and steps aren't equal. A note on a CRM record and an email to a buyer each count as one, so read what a step touches before you rank it. A step with two chips can read with one tool and send with the other, so count it by the stronger action. A step with no chip has no tool to trace, so mark it for a closer read.

Run modes shift the count as well. **Auto Run** is the default for a tool with no stored mode, and **Agent Decides** leaves the choice to the agent. For a strict check, count **Agent Decides** as acting alone.

The result is also a snapshot. The tab keeps no version history and has no export, so keep your own dated table. Run mode changes are saved, so recount whenever someone changes one.

### Where you find the counts in Oliv AI {#measure-in-oliv}

You build both numbers from two screens. **Process** and the contents list give you the steps. Each chip gives you the tool, and the dropdown at the right of its card gives you the run mode. **Auto Run** on a CRM, mailbox or channel tool means the agent may write to that system without asking, so look for those tools first.

## How to check an agent's process by hand {#check-by-hand}

Without a tab like this one, the same check is a spreadsheet job:

1. Ask whoever built or sold the agent for its process, as the steps it runs in order. A one-line summary won't do.
2. Put each step on its own row, in that order.
3. Beside each step, write the tool or connection it uses. If nobody can name one, mark it unknown and treat it as acting.
4. Mark each tool as read only, or as write or send.
5. For each write or send, find out whether a person must approve it, and who that person is.
6. Count all the steps, the ones that act, and the ones that act alone.
7. Read the steps that act alone first. Note which field or which person each one reaches.
8. Date the sheet, and repeat the check when the agent or its settings change.

Steps 3 and 5 are where this usually stalls. The tool list and the approval settings often sit somewhere other than the process, so you end up chasing answers and the sheet goes stale.

### The same job in Oliv AI {#same-job-in-oliv}

Oliv AI puts steps 1 to 3 and step 5 on screen. The **Instructions** tab lists the numbered steps, each chip names the tool, and pressing the chip shows that tool's run mode. Steps 4, 6 and 7 are still your judgment, because you decide what counts as acting and what to read first. Step 8 stays with you too, since the tab keeps no history.

### Worked example: tracing a six-step agent {#worked-example}

This is an illustrative calculation with sample figures, not an Oliv AI output, and it claims no saving. A RevOps lead reads an agent with 6 process steps before rollout and traces each one to its tool.

| Step | What the tool does | Type | Run mode | Acts alone? |
|---|---|---|---|---|
| 1 | Reads the deal record | Read | Not relevant | No |
| 2 | Reads recent call notes | Read | Not relevant | No |
| 3 | Reads the email thread | Read | Not relevant | No |
| 4 | Reads the account's open deals | Read | Not relevant | No |
| 5 | Sends a follow-up email to the buyer | Send | **Requires Approval** | No |
| 6 | Writes the next step to the CRM record | Write | **Auto Run** | Yes |

| Count | Working | Result |
|---|---|---|
| All process steps | Counted from **Process** | 6 |
| Steps that only read | Steps 1, 2, 3 and 4 | 4 |
| Steps that write or send | 6 - 4 | 2 |
| Action share | 2 / 6 | 33% |
| Actions needing approval | Step 5 | 1 |
| Steps acting alone | 2 - 1 | 1 |

Step 6 gets checked first, because it's the only action with no person in front of it. The lead reads which field it writes, asks what else depends on that field, and decides whether **Auto Run** should stay. Step 5 comes next, to confirm who approves the email. The four reading steps come last. The 33% is neither good nor bad on its own. Its job is to tell the lead that 2 of the 6 steps deserve the closest reading.

## How agent instructions work with other features {#works-with}

### Tools and run modes {#with-tools}

Instructions name the tools; the **Tools** tab sets how freely each one runs. Reading a step and then its tool's mode shows you both what the agent does and how much it does unasked.

### The Overview tab {#with-overview}

The **Overview** tab gives a short **Goal** statement and lists the agent's tools as pills. The **Instructions** tab is the longer account of the same agent.

### Knowledge and triggers {#with-knowledge-and-triggers}

On agents that have them, the [**Knowledge** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/) lists the files an agent works against, and the [**Triggers** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) lists what starts it.

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

## How Oliv AI compares for AI agent instructions {#compare}

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

### Why Oliv AI is the stronger choice for AI agent instructions {#compare-stronger}

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

#### What do AI agent instructions contain? {#faq-contents}

Three parts. **Objective** is a short paragraph on the agent's aim, **Process** is its numbered steps with their tools, and **Output** lists what it produces, where it has output items.

#### Where do I see what an agent actually does? {#faq-where}

Open the agent and select the **Instructions** tab, the second tab after **Overview**. Read **Process** for the steps it takes, in order.

#### Can I edit an agent's instructions? {#faq-edit}

Not from the **Instructions** tab. It has no text field, **Edit** or **Save** control, so the instructions are read-only there.

#### How do I tell which tools a step uses? {#faq-which-tools}

Tool names appear as small chips inside each step's description. Pressing one opens that tool on the **Tools** tab.

#### How do I check whether a step needs approval? {#faq-approval}

Press the tool chip in that step. The **Tools** tab opens on that tool, and its run mode shows whether the action needs a person's approval.

#### How many steps does an agent's process have? {#faq-how-many-steps}

Typically between 3 and 6. To see an agent's own number, count the numbered steps under **Process**.

#### Why does one agent have no Output section? {#faq-no-output}

The **Output** section is hidden when an agent has no output items stored.

#### Can I see who wrote the instructions, or when they changed? {#faq-author}

No. No author, version or date is recorded on the tab.

#### How is the Goal on the Overview tab different? {#faq-goal}

The **Goal** on the **Overview** tab is a short statement kept separately from the instructions. The **Instructions** tab is the full account, in three sections.

#### Why does this agent have no Instructions tab? {#faq-no-tab}

Only agents with a detail page have instructions, so an agent without one has nothing to show.

#### Should every step that acts need approval? {#faq-every-step-approval}

Usually not. If people approve everything, they [stop paying attention](https://www.nngroup.com/articles/confirmation-dialog/), so keep approval for steps with serious consequences. Check each step's tool on the **Tools** tab to see its current run mode.

#### What does Agent Decides mean when I'm checking a step? {#faq-agent-decides}

**Agent Decides** means the agent judges whether to ask a person. For a strict check, count that step as one that may act alone, and read it early.

#### Do the instructions show what an agent did on a real deal? {#faq-real-run}

No. They describe the agent's method. To see what happened on a past run, open the agent's [run history](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/run-history/), which lists each run with a link to its full record.

#### How do I keep a record of what I checked? {#faq-keep-record}

Keep your own dated table of steps, tools and run modes. The **Instructions** tab has no export, copy-all or version history, so your table is the record to compare against later.

## Further reading {#further-reading}

- [Explainable AI in chat interfaces, Nielsen Norman Group](https://www.nngroup.com/articles/explainable-ai/): why a confident explanation can earn more trust than it should.
- [Confirmation dialogs, Nielsen Norman Group](https://www.nngroup.com/articles/confirmation-dialog/): when a prompt to confirm helps, and when people start ignoring it.
- [HubSpot's default deal properties](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties): which HubSpot deal fields update on their own, useful when you weigh a CRM write.

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

*Updated 3 November 2026: added ways to check an agent before it runs, two counts of what it does alone, the check by hand and a worked example.*
