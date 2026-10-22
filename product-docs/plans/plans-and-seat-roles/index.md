# Plans and seat roles

The four role-based Oliv AI plans, what each one adds, the add-ons that sit on top, and how to decide which person on your team needs which seat role.

- Applies to: Revenue operations and anyone planning an Oliv AI rollout
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/

Oliv AI sells seats by role. There are four plans, Amplify, Converse, Sell and Grow, and each person gets the one that matches the apps their work needs. This page explains what each plan includes, how the plans stack, and how to assign seat roles across a revenue team. Prices aren't listed here; they're on [Oliv AI's pricing page](https://www.oliv.ai/pricing).

## At a glance {#at-a-glance}

| Plan | Built around | Typical roles |
|---|---|---|
| **Amplify** | Putting customer context to work | C-suite, Product, Operations, Engineering |
| **Converse** | Capturing customer conversations | BDRs and SDRs, Product Marketing, Customer Support |
| **Sell** | Managing opportunities | Account Executives, Sales Engineering, Partnerships |
| **Grow** | Retaining and growing accounts | Customer Success, Account Management, Solution Engineering, Onboarding |

Plans are cumulative. Converse includes Amplify, Sell includes Converse, and Grow includes Sell.

## How the plans stack {#how-plans-stack}

Each plan carries everything in the plan below it, then adds one layer:

1. **Amplify** gives every role the super agents, [Oliver](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) and [Olivia](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/), plus questions and reviews across customer context, and building custom agents.
2. **Converse** adds conversation capture: online meetings, email, in-person meetings and phone calls.
3. **Sell** adds the Forecast app, with sales methodologies and deal risks.
4. **Grow** adds the Retain app, with customer health scorecards and churn risks.

You can use all four plans together in one company. Assign each team member by the apps they need, rather than buying one plan for everyone.

## The four seat roles {#seat-roles}

### Amplify {#amplify}

Amplify is for people who use customer context but don't run calls or own deals. C-suite, Product, Engineering, Operations and Product Marketing can use Oliv AI's Oliver and Olivia agents. They can ask questions of customer context, review conversations, opportunities and accounts, and build custom agents.

[Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) configures how agents work. [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) coordinates their tasks across your team.

### Converse {#converse}

Converse is the conversation intelligence plan, and you can buy it on its own. It can be deployed across your customer-facing organization. It includes:

- [Online meeting capture, botless or bot-based](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) (bot-based capture is an add-on)
- Email capture and optional [Slack capture](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/)
- In-person meeting capture through the mobile app
- Phone call capture, meeting transcription, and [AI summaries and action items](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/)
- A [conversation library with search](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/), and meeting notes in the CRM

More on the app itself on the [Converse page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/). In the web app, captured conversations sit under **Activities**, as **Meetings** and **Calls**, and the meetings list has **My meetings** and **Team meetings** views.

<figure>

![Activities menu open from the sidebar, listing Meetings, highlighted, and Calls, over the Meetings list on My meetings with a Team meetings tab. Columns show Meeting, Duration, a Meeting with dropdown, Next Step and AI Summary.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/navigation/oliv-ai_238_navigation_sidebar_activities-flyout-open-meetings-highlighted-calls-over-my-meetings-list.webp)

<figcaption>Where a Converse seat's captured conversations land: meetings and calls under Activities, each meeting with an AI-written next step and summary.</figcaption>
</figure>

### Sell {#sell}

Sell adds opportunity management through the Forecast app. It's built for account executives, sales engineering and partnerships. On top of everything in Converse, it includes:

- Opportunity grids and deal health and risks
- Sales methodology tracking against the framework you activate: **MEDDPICC**, **MEDDIC**, **SPICED**, **BANT** or **DRIVE**
- Buying committee tracking
- Revenue forecast boards, forecast submissions and weekly pipeline snapshots, on the Forecast app's **Boards** and **Submissions** tabs
- Deal change history

The [Forecast app page](https://www.oliv.ai/oliv-forecast) shows these views, and [sales methodology tracking](https://www.oliv.ai/sales-methodology) covers the frameworks.

### Grow {#grow}

Grow adds account management through the Retain app. It's built for customer success, account management, solution engineering and onboarding. On top of everything in Sell, it includes:

- Customer grids and customer health scorecards
- Churn risks and retention forecast boards
- Product usage tracking and support ticket tracking
- White space tracking and customer stakeholder tracking

More on Oliv AI for [customer success teams](https://www.oliv.ai/customer-success) and for [account management](https://www.oliv.ai/account-management).

## Assign seat roles across your team {#assign-roles}

Picture a revenue operations lead planning a rollout for a 34-person revenue org. Sales development has five SDRs, and support has two agents who answer customer calls. Sales has nine AEs, two sales engineers and a partnerships manager. Post-sale has five CSMs and two onboarding specialists. Around them sit a CRO, two product managers, two RevOps analysts, two engineers and a product marketer who sits in on customer calls.

Count each person once, in the group that fits their work. A sorting like this one follows the role examples on the pricing page:

| Group | People in this example | Seat role |
|---|---|---|
| Sales development and support | 5 SDRs, 2 support agents | **Converse** |
| Pre-sales | 9 AEs, 2 sales engineers, 1 partnerships manager | **Sell** |
| Post-sales | 5 CSMs, 2 onboarding specialists | **Grow** |
| Leadership, product, operations, engineering | CRO, 2 product managers, 2 RevOps analysts, 2 engineers | **Amplify** |
| Product marketer on customer calls | 1 product marketer | **Converse** |

The product marketer is the judgment call. The role examples are a guide, and a customer-facing product marketer can use Converse when they need conversation capture. The same logic works in reverse: give someone Sell or Grow only when they'll work in the Forecast or Retain app.

### What people see in the product {#in-product-views}

Inside Oliv AI, the **Agent Feed** on Home filters by **Team** (**Sales**, **Sales Development**, **Customer Success**, **RevOps**) and **Role** (**Contributor** or **Manager**). Each combination shows the agents that group uses. These are views, not seat roles: use them to check that the seat you pick fits the work each person does.

<figure>

![Agent Feed Filters panel with Team options Sales, Sales Development, Customer Success and RevOps, Role options Contributor and Manager, an Agents list of ticked checkboxes, and Timeline options from Today to Last 30d above a Clear All Filters button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_020_home_agent-feed_filters-panel_team-role-agents-select-all-timeline-today-7d-14d-30d-clear-all-filters_panel-only.webp)

<figcaption>The team and role filters show which agents each group relies on, a quick way to sanity-check the seat role you give each person.</figcaption>
</figure>

### Questions to ask for each person {#questions-per-person}

1. **Do they run customer conversations that should be captured?** If yes, they need at least Converse.
2. **Do they own or forecast opportunities?** If yes, they need Sell, which brings the Forecast app.
3. **Do they own renewals, health or expansion for live customers?** If yes, they need Grow, which brings the Retain app.
4. **Do they only read context, ask questions or build agents?** Amplify covers that work.

For how an AE spends a day with the Sell plan's agents, see [running deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Add-ons {#add-ons}

Add-ons are priced separately from the four plans. Each one is added per person, so only the people who need it carry it.

### Enable {#enable}

Enable evaluates customer conversations against coaching scorecards to identify where a rep needs help. It's an add-on, priced separately from the plans. In the app, its **Library** tab holds clip libraries, each **Public** or **Private**, and its **People** tab shows each rep's pacing for managers.

### Engage {#engage}

Engage runs email and LinkedIn outreach from Oliv AI. Add it to Converse, Sell or Grow for team members who connect with prospects and customers. It includes one connected primary mailbox and LinkedIn automation. In the app, Engage has **Inbox**, **Dialer**, **Plays**, **Flows**, **Signals** and **Experiments** tabs. You can add more on top:

- **Dialer.** One US phone number, with calling minutes to the US and Canada. The **Dialer** tab runs **Power** and **Parallel** sessions.
- **WhatsApp, Telegram or Instagram.** Choose the channels you need, priced per channel.
- **Extra mailboxes.** Additional warm email mailboxes to scale outreach.

### Capture add-ons {#capture-add-ons}

Bot-based meeting capture is an add-on on Converse, Sell and Grow. A meeting assistant joins the call, including [externally hosted meetings](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) when permitted. Slack, WhatsApp and LinkedIn capture are also listed as add-ons.

### Plaud recordings {#plaud}

In-person meeting capture works through the mobile app on Converse. Sell and Grow also support Plaud recordings. Plaud hardware is purchased separately.

## Agent actions {#agent-actions}

Agent actions are billed separately from app subscriptions, on every plan. An agent action is a task an agent completes, such as researching an account or updating a CRM record. Your total depends on agent usage.

| Agent | Example actions |
|---|---|
| [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) | Prepare forecast, update forecast category |
| [Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager) | Flag renewal risk, prioritize customers, draft next steps |
| [Oliv AI's Prospector agent](https://www.oliv.ai/agents/prospector) | Rank target accounts, identify contacts, prepare outreach |
| [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) | Review pipeline, draft follow-ups, flag risks |
| [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) | Create records, update fields, sync next steps |

During a proof of concept, Oliv AI estimates agent spend at your expected volume. It then assesses return on investment against time saved and business value before rollout. [Custom agents you build](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/) follow the same model; [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) covers what an agent can do in connected apps.

## Compare against your current tools {#cost-calculator}

The pricing page includes a calculator for your own team. Enter the number of people in each group, Converse, Sell, Grow and Amplify. It compares the Oliv AI apps in their plan with named tools, using the same seat counts.

The calculator states its assumptions. Its figures are comparison assumptions, not vendor quotes, because coverage and contracts differ. Platform fees are excluded. For the thinking behind replacing per-seat tools with agents, see [build versus buy for revenue AI](https://www.oliv.ai/build-vs-buy).

## Limits and things to know {#limits}

- **Prices live on the pricing page.** This page describes plans and roles only; current prices are on the pricing page.
- **Role examples are a guide.** Assign by the apps a person needs, not by job title alone.
- **Add-ons aren't in the plans.** Enable, Engage, bot-based capture and the extra capture channels are priced separately.
- **Agent usage is separate.** Agent actions are billed apart from seats, and the total depends on what your agents do.
- **Hardware is separate.** Plaud hardware is purchased separately from any plan.
- **Calculator figures are assumptions.** They aren't vendor quotes, and platform fees are excluded.

## Common questions {#common-questions}

#### Do viewers and admins need a Sell or Grow seat? {#faq-viewers}

No. Amplify covers C-suite, Product, Engineering, Operations and Product Marketing. They can use Oliver and Olivia, ask questions of customer context, review conversations, opportunities and accounts, and build custom agents.

#### Can I buy only conversation intelligence? {#faq-ci-only}

Yes. Converse is the conversation intelligence plan, and it can be deployed across your customer-facing organization.

#### Can different people in one company be on different plans? {#faq-mixed-plans}

Yes. Use Amplify, Converse, Sell and Grow together across your company, and assign each team member by the apps they need.

#### Does a higher plan include the lower ones? {#faq-cumulative}

Yes. Converse includes Amplify, Sell includes Converse, and Grow includes Sell.

#### Which plan does a sales engineer need? {#faq-sales-engineer}

The pricing page puts pre-sales Sales Engineering under Sell, and post-sales Solution Engineering under Grow.

#### Which plan adds forecasting? {#faq-forecasting}

Sell. It brings the Forecast app, with revenue forecast boards, forecast submissions, weekly pipeline snapshots and deal change history. [Pipeline reviews with the Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) build on the same data.

#### Which plan adds customer health and churn risk? {#faq-health}

Grow. It brings the Retain app, with customer health scorecards, churn risks and retention forecast boards.

#### What does Engage include? {#faq-engage}

One connected primary mailbox and LinkedIn automation. Dialer, WhatsApp, Telegram, Instagram and extra warm email mailboxes are added separately.

#### How are agent actions charged? {#faq-agent-actions}

Separately from app subscriptions, based on agent usage. During a proof of concept, Oliv AI estimates the spend at your expected volume and assesses the return against time saved.

#### Do we need to replace Salesforce or HubSpot? {#faq-crm}

No. Oliv AI works with your existing CRM. It brings the context together and [keeps your systems updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/).

#### Is in-person meeting capture included? {#faq-in-person}

Yes, through the mobile app from Converse up. Sell and Grow also support Plaud recordings, with the hardware purchased separately.

## Related {#related}

- [Oliv AI pricing](https://www.oliv.ai/pricing): current prices for every plan and add-on.
- [The agent marketplace](https://www.oliv.ai/agents-marketplace): the agents that agent actions run on.
- [Oliv AI for revenue operations](https://www.oliv.ai/revops): how RevOps runs the rollout and the process the agents follow.
- [Oliv AI for sales development](https://www.oliv.ai/sales-development): what Converse seats do for SDR teams.
- [Oliv AI for sales teams](https://www.oliv.ai/sales): how Sell seats support account executives and managers.
- [Oliv AI for onboarding teams](https://www.oliv.ai/onboarding): where onboarding specialists fit under Grow.
- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): one workflow that runs on captured conversations and CRM data.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
