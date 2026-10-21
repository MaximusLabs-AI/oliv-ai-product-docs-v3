# Meeting Assistant agent

What Oliv AI's Meeting Assistant agent sends before each deal meeting, what it drafts and flags after the call, how to set it up, and how it compares with other meeting tools.

- Applies to: Account executives, BDRs, account managers and customer success teams on active opportunities
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/

Oliv AI's Meeting Assistant agent prepares you for every meeting on an active deal and drives the follow-through after it. Thirty minutes before the call, it sends a one-screen brief with the deal status, qualification gaps and a recommended agenda. After the call, it drafts the follow-up email, proposes CRM field updates and flags new qualification gaps.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Prepares you before each deal meeting and drafts the follow-through after it |
| **Who it's for** | Account executives, BDRs and account managers, plus sales managers and customer success leads |
| **Before the meeting** | A one-screen brief, 30 minutes before the call |
| **After the meeting** | A follow-up email draft, proposed CRM updates and qualification gap flags |
| **Runs on** | Every meeting linked to an active opportunity in your CRM |
| **Built from** | Oliv Notetaker recordings and transcripts |
| **Also part of** | The Deal Driver bundle |

## What the Meeting Assistant agent is {#what-it-is}

Oliv AI's Meeting Assistant agent is an action agent for the people who run meetings on open deals. It works only on active opportunities. If the deal exists and the meeting is on your calendar, it runs automatically. First meetings with new contacts get a research brief instead, covered in [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Before the meeting {#before-the-meeting}

The brief arrives 30 minutes before the call. It's built to fit one screen and take about 60 seconds to read.

- **Deal summary.** Stage, amount, close date, last activity and next steps.
- **Qualification status.** Where the deal stands against your methodology, with gaps and open questions highlighted.
- **Stakeholders.** Who's in the meeting, the role each plays, and what they care about based on earlier conversations.
- **Recommended agenda.** Tailored to the deal stage and the qualification gaps.

### After the meeting {#after-the-meeting}

Once the recording is processed, three things are ready for you.

- **A follow-up email draft.** Written from the transcript: what was discussed, what was agreed, and next steps with dates where possible. It isn't a template.
- **Proposed deal field updates.** Stage, amount, close date, qualification fields and next steps, based on what was said.
- **Qualification gap flags.** New information, or notable absences, that change the deal's qualification status.

### Across the life of a deal {#across-meetings}

As meetings stack up on a deal, Meeting Assistant keeps an updated picture of the opportunity. That picture doesn't depend on a rep typing notes after every call. It's what makes [better sales follow-ups](https://www.oliv.ai/blog/sales-follow-up) possible without extra admin.

## Why the Meeting Assistant agent matters {#why-it-matters}

### What it's for {#what-its-for}

Oliv AI's Meeting Assistant agent is for anyone who runs meetings on live deals. It handles the prep before each call and the paperwork after it. That leaves the time in between for thinking about the customer.

### How it helps {#how-it-helps}

- **You walk in ready.** The brief lands half an hour early and reads in about a minute.
- **The email is already written.** The draft comes from the real conversation, so you edit rather than start from a blank page.
- **The CRM keeps pace.** Changes heard on the call come back as proposed updates you approve.
- **Gaps show up early.** Missing qualification details are flagged after every call, while there's time to fix them.

### What happens without it {#without-it}

Reps lose 15 to 20 minutes rebuilding context before each call. Each follow-up email takes another 15 minutes. CRM updates rely on memory, so fields drift out of date. Qualification gaps surface at the forecast review, when it's too late to act on them.

### Why buyers care {#why-buyers-care}

VPs of Sales and sales managers are the usual buyers. Account executives champion it, because they get time back before and after every call. The value grows with deal volume, since there's more for the gap tracking to catch.

## The Oliv AI approach to the Meeting Assistant agent {#approach}

{/* 5P */}

Say a customer success manager has just wrapped a quarterly business review with three people from one account. The operations director wants a rollout plan. The finance lead asked for usage numbers before the renewal talk. The admin raised two open support issues, and the renewal opportunity is sitting in the CRM.

Most CSMs write that recap later in the day, from memory and a page of scribbles. Pleasing three readers in one email can eat close to half an hour. Small promises tend to slip, and the renewal record often stays exactly as it was before the call.

Yet nothing in that recap is new information. Every ask, owner and date was said out loud on a recorded call. The real job is turning the transcript into an email and a few field changes while the meeting is still fresh.

Oliv AI does that with its Meeting Assistant agent. When the recording is processed, it drafts the follow-up from the transcript with the recap, commitments, owners and next steps. It also proposes field updates for the renewal and flags any qualification gaps the call exposed. The CSM reads it, adjusts a line or two and sends it.

The draft lands within minutes of the call ending, and each CRM change arrives as a proposal to approve rather than a silent write. How that set of outputs lines up against other meeting tools is covered in How the Meeting Assistant agent compares, below.

## Set up Meeting Assistant {#set-up}

1. **Connect your calendar.** Meeting Assistant looks for meetings linked to an active opportunity.
2. **Connect your call recorder.** Use your existing recording tool or Oliv AI's own recorder. The follow-up and gap flags are built from recordings and transcripts, which [Oliv AI's Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) captures with call recording and transcription.
3. **Connect your CRM.** [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho. This is where the deal context comes from and where approved updates go. See the full list of [supported integrations](https://www.oliv.ai/integrations).
4. **Confirm your methodology.** MEDDPICC, BANT, SPICED, MEDPICS or your company's own framework. Meeting Assistant maps every call against the one your team runs.

Most teams are connected within a week. You don't need a clean CRM to start: [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) fills in missing or stale fields from call history as it goes.

## Review and send the follow-up {#review-the-follow-up}

The follow-up is a draft, not an automatic send. Read it, adjust anything that needs changing, and send it yourself. The [pre-meeting brief for any active deal or customer](https://www.oliv.ai/agents/meeting-assistant) works the same way: it informs you, and you decide what happens next.

### Approve the proposed field updates {#approve-updates}

The agent reads the call, finds what changed, and proposes updates for approval. That keeps stage, close date and next steps current without chasing anyone. Approval settings for agent actions in general are explained in [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).

### Act on the qualification gaps {#act-on-gaps}

Gap flags appear after every call, so reps and managers can act before missing details hurt the deal. Your team's framework decides what counts as a gap, so it helps to agree on your [sales methodology](https://www.oliv.ai/sales-methodology) first.

## How Meeting Assistant works with other agents {#works-with}

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) writes the field updates that Meeting Assistant surfaces. Meeting Assistant proposes, and CRM Manager keeps the pipeline current without manual cleanup.

### Deal Driver {#with-deal-driver}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) adds pipeline context before every manager 1:1: what changed, what's stuck and which deals need attention. Meeting Assistant summarizes what happened on each call, so managers coach from the same context their reps have.

### Forecaster {#with-forecaster}

[Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) uses the deal qualification data that Meeting Assistant helps keep current. Better data after each call feeds a more grounded pipeline projection.

### Coach {#with-coach}

[Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) is developmental and works on recordings after the fact. Meeting Assistant is operational and works before and right after the call.

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) is the front-facing master agent for reps. Meeting Assistant works in the background around each call, so the brief and follow-up arrive without anyone asking.

## Who uses Meeting Assistant, and how {#who-uses-it}

### Account executives {#account-executives}

Account executives are the main users. They get the brief before each deal meeting and the drafted follow-up after it, so prep and recap stop eating the gaps between calls. The full rep workflow is in [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Account managers and customer success {#account-managers-cs}

Account managers and CSMs use it on meetings tied to a renewal or expansion opportunity. A check-in with several stakeholders ends with the recap already drafted. See how Oliv AI supports [customer success teams](https://www.oliv.ai/customer-success) and [account management](https://www.oliv.ai/account-management).

### BDRs {#bdrs}

BDRs use it on meetings tied to an active opportunity. They get the same brief before the call and the same drafted follow-up after it. More on Oliv AI for [sales development teams](https://www.oliv.ai/sales-development).

### Sales managers {#sales-managers}

Sales managers see the same call summaries their reps do before each 1:1. Combined with Deal Driver, the meeting opens on the deal, not on a retelling of it. Read how Oliv AI works for [sales managers](https://www.oliv.ai/sales-managers).

## How the Meeting Assistant agent compares {#compare}

Most meeting tools draft a follow-up email. Meeting Assistant also proposes CRM updates for approval, flags qualification gaps and summarizes each call for the manager's 1:1, all from the same recording. Oliv AI is the only platform in this table that does all four.

After-the-call features, from each platform's public documentation:

| Platform | Follow-up drafted from the call | CRM updates proposed for approval | Qualification gaps flagged after each call | Call summary for the manager's 1:1 |
|---|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes | Yes |
| **Gong** | Yes ([follow-up email from the call page](https://help.gong.io/docs/about-the-call-page)) | Partly ([one text field on deal boards](https://help.gong.io/docs/how-to-create-and-manage-deal-boards)) | Partly ([separate MEDDICC agent](https://help.gong.io/docs/agent-use-case-and-examples)) | Partly ([deal board to check before 1:1s](https://help.gong.io/docs/recipe-focus-on-deals-that-need-your-attention)) |
| **Outreach** | Yes ([Smart Email Assist follow-up](https://support.outreach.io/support/solutions/articles/159000425405-outreach-product-release-notes-may-2024)) | Yes ([Deal Agent field recommendations](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) | Partly ([methodology in the Deal Agent](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) | Partly ([deal questions to cut 1:1 admin](https://support.outreach.io/support/solutions/articles/159000425405-outreach-product-release-notes-may-2024)) |
| **Fireflies** | Yes ([follow-up after every sales call](https://guide.fireflies.ai/articles/2790601073-fireflies-for-sales-your-ai-platform-for-everything-after-the-call)) | Yes ([Autofill CRM review](https://guide.fireflies.ai/articles/1729159683-autofill-crm-for-salesforce-automatically-extract-and-sync-meeting-data-to-contacts-accounts-and-opportunities)) | Partly ([BANT and MEDDIC scorecards](https://guide.fireflies.ai/articles/2790601073-fireflies-for-sales-your-ai-platform-for-everything-after-the-call)) | Not in docs |
| **Avoma** | Yes ([auto-generated follow-up email](https://help.avoma.com/share-meeting-notes)) | [Automated field updates](https://help.avoma.com/import-your-crm-custom-fields-properties-into-pipeline-views) | Yes ([gaps in the deal dashboard](https://help.avoma.com/configure-deal-methodology)) | Not in docs |
| **Fathom** | Partly ([drafted when you prompt Ask Fathom](https://help.fathom.video/en/articles/6220097)) | [Writes summaries and tasks to CRM](https://help.fathom.video/en/articles/448640) | Partly ([MEDDPICC deal summary template](https://help.fathom.video/en/articles/3239809)) | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for the Meeting Assistant agent {#compare-stronger}

- **One recording, every output.** Meeting Assistant turns each call into a follow-up, CRM proposals and gap flags at once. Gong puts [generating a follow-up email among the call page actions](https://help.gong.io/docs/about-the-call-page), while [a MEDDICC agent shows where the gaps are](https://help.gong.io/docs/agent-use-case-and-examples). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **Gaps flagged on every call.** Meeting Assistant maps each call against the methodology your team runs. Avoma's Deal Methodology [surfaces compliance and gaps in the deal dashboard](https://help.avoma.com/configure-deal-methodology) once an admin configures it. Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **The manager gets the call context without asking.** Before every 1:1, Meeting Assistant summarizes what happened on each call. Outreach's manager workflows suggest you [use pipeline summary to review a rep's opportunities](https://support.outreach.io/support/solutions/articles/159000425547-sales-manager-workflows-for-rep-coaching-and-1-1-s) and pull that context together yourself. Read [how Gong and Outreach compare](https://www.oliv.ai/blog/gong-vs-outreach).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **It works on active opportunities.** Meetings with no linked opportunity don't get a deal brief. First meetings with new contacts are handled by research before the first call.
- **It proposes, it doesn't send.** You review, adjust and send the follow-up yourself, and field updates wait for approval.
- **It isn't a forecasting agent.** Meeting Assistant surfaces field updates. Forecaster uses them for pipeline projection.
- **It isn't a coaching tool.** Meeting Assistant is operational. Coach handles rep development.
- **It needs recordings.** The follow-up, field updates and gap flags come from Oliv Notetaker recordings and transcripts.

## Common questions {#common-questions}

#### How long is the pre-meeting brief? {#faq-brief-length}

One screen, about 60 seconds to read. It covers the deal summary, qualification status, stakeholder context and a recommended agenda.

#### What sales methodologies does it support? {#faq-methodologies}

MEDDPICC, BANT, SPICED, MEDPICS or your company's custom qualification framework. Meeting Assistant maps every call against whichever one your team runs.

#### Does it work for every meeting, or only some? {#faq-which-meetings}

Every meeting linked to an active opportunity in your CRM. If the deal exists and the meeting is on your calendar, it runs automatically.

#### Is the follow-up email a template? {#faq-template}

No. Meeting Assistant reads the recording transcript and drafts from the actual conversation: what was discussed, what was agreed and what happens next. You review it, adjust it and send it.

#### How soon after the call is the follow-up ready? {#faq-timing}

The follow-up is drafted within minutes of the call ending, once the recording is processed.

#### Does it change CRM fields on its own? {#faq-crm-changes}

No. It proposes updates for approval. CRM Manager then writes the updates Meeting Assistant surfaces.

#### I'm already on Deal Driver. Do I need this separately? {#faq-deal-driver}

No. Meeting Assistant is included in Deal Driver, so if you're on Deal Driver, your reps already have it.

#### What does it need connected? {#faq-integrations}

Your calendar, your call recording tool or Oliv AI's own recorder, and your CRM: [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho. Most teams are connected within a week.

#### What if our CRM data is incomplete? {#faq-messy-crm}

Meeting Assistant works with CRM Manager to keep deal fields current. If data is missing or stale, CRM Manager fills it in from call history, so you don't need a clean CRM to start.

#### Is there a minimum team size? {#faq-team-size}

No. It delivers value for individual reps straight away. Qualification gap tracking gets more useful as deal volume grows.

#### Can customer success teams use it? {#faq-customer-success}

Yes, on meetings linked to an active opportunity, such as a renewal or expansion. Customer success and account management are among the teams it's built for.

## Related {#related}

- [Meeting Assistant on oliv.ai](https://www.oliv.ai/agents/meeting-assistant): the agent's own page, with the brief and follow-up examples.
- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the step-by-step guide to the brief and first-meeting research.
- [The Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): the manager bundle that includes Meeting Assistant.
- [The AE deal workflow](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): how a rep's week runs across agents.
- [AI meeting assistants for sales](https://www.oliv.ai/blog/ai-meeting-assistant-for-sales): how meeting tools differ on prep and follow-up.
- [Sales call notes software](https://www.oliv.ai/blog/sales-call-notes): transcription and structured notes compared.
- [Oliv AI pricing](https://www.oliv.ai/pricing): plans and what each includes.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
