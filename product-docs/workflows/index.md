# Workflows overview

How Oliv AI's agents carry a deal through the week, from the brief before a meeting and the follow-up after it to CRM upkeep and the weekly pipeline review.

- Applies to: Revenue teams with a connected calendar and CRM
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/

Workflows show Oliv AI's agents working together on one job, from start to finish. Each guide follows a deal through a normal week: preparing for a meeting, recording it and following up, keeping the CRM current, then reviewing the pipeline. The agent pages explain what each agent does on its own. These guides show who does what, and when.

## A deal's week in four workflows {#deal-week}

| When | Guide | What you end up with |
|---|---|---|
| Before a meeting | [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) | A one-screen brief 30 minutes before the call |
| During and after the call | [Record a meeting and follow up](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) | A summary, a drafted follow-up email and proposed CRM updates |
| Between meetings | [Keep the CRM updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) | Accounts, contacts and opportunities kept current from every activity |
| End of the week | [Run a pipeline review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) | A per-rep report before each 1:1, and a rollup for leadership |

The first three are written for the person running the deal. The pipeline review is written for their manager. All four read from the same meetings, calls and emails, so nothing has to be entered twice.

## Before the meeting {#before}

Oliv AI's Meeting Assistant agent sends a brief 30 minutes before every meeting linked to an active opportunity. It covers the deal's status, where you stand on qualification against your methodology, who is in the meeting and a recommended agenda. The brief is designed to fit on one screen and take about 60 seconds to read.

A first meeting with someone new works differently, because there's no deal history yet. You ask Oliv AI's Olivia agent to prepare you, and she researches the company and the person. You can also ask Olivia for prep at any time on the Home screen's **Ask** tab. Her answer opens with the deal at a glance, then covers who's joining, the risks and the talking points. The [meeting preparation guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/#step-4-first-meeting) covers every kind of prep.

<figure>

![Olivia's answer on the Home Ask tab to a request to get ready for a renewal call. Under Deal at a glance, four cards show the deal stage as Negotiation, the ARR, 23 days since the economic buyer was last touched and a deal health of At Risk.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/home/oliv-ai_014_home_chat_olivia_acme-renewal-prep_deal-at-a-glance-cards-negotiation-180k-arr-23-days-no-economic-buyer-touch-at-risk.webp)

<figcaption>Prep on demand: Oliv AI's Olivia agent starts with the four numbers that tell you how much is riding on the call, before the attendees, risks and talking points.</figcaption>
</figure>

For what the brief agent does on every deal, read the [Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) page.

## During and after the call {#during-and-after}

Oliv AI records the call, then turns it into everything you'd otherwise write by hand. When someone from your company organizes the meeting, Oliv AI records botlessly through the meeting platform. When an external organizer owns it, a note taker joins under your company's name. [Bot and botless recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) explains the choice, and the [Zoom integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) covers Zoom calls in detail.

The meeting summary is ready as soon as the call ends. Oliv AI's Meeting Assistant agent then drafts the follow-up email from the transcript, with the recap, commitments, owners and next steps already written. It also proposes CRM updates and flags qualification gaps. In **Activities › Meetings**, each meeting opens in a drawer with tabs for the overview, action items, meeting insights, the recording, coaching, attendees and CRM updates. The [follow-up guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) walks through reviewing each one, and the [meeting details](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) page shows the recorded call itself.

<figure>

![A meeting's details drawer on the Overview tab, with tabs for Overview, Action Items, Meeting insights, Recording, Coaching, Attendees and CRM Updates. A Key takeaways card and an AI Summary card carry timestamps, and an account updates card shows the deal stage, amount, close date and a Review Deal button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_240_activities-meetings_meeting-details-drawer_overview-tab_key-takeaways-ai-summary-and-deal-updates-card.webp)

<figcaption>After the call, the meeting drawer holds everything the follow-up needs. Each tab covers one job, from the takeaways and tasks to the CRM changes.</figcaption>
</figure>

If your team works in Slack, the summary also arrives there through the [Slack integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/).

## Between meetings {#between-meetings}

Oliv AI's CRM Manager agent reads every meeting, call and email, then updates accounts, contacts, opportunities, activities and tasks in Salesforce, HubSpot or Zoho. Your CRM stays the system of record, and Oliv AI works on top of it.

Each suggested update shows the field, the current value, the proposed value and the moment in the conversation behind it. On a deal's **CRM Updates** tab, you **Accept** or **Reject** each AI suggestion. A meeting's **CRM Updates** tab lists what was written after the call and holds a stage move as a **Pending Update** until you click **Update Deal**. Switch to auto mode once you trust it.

<figure>

![The CRM Updates tab of a meeting drawer: a timeline of changes made after the meeting, with completed updates to the account, a BANT scorecard and two new contacts, and one Pending Update to move the deal to Proposal with an Update Deal button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_246_activities-meetings_meeting-details-drawer_crm-updates-tab_account-deal-bant-and-contact-updates-with-pending-stage-move.webp)

<figcaption>Between meetings, the CRM Updates tab is where you see what Oliv AI's CRM Manager agent wrote and confirm the changes that are still pending.</figcaption>
</figure>

The [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) covers setup and a monthly hygiene check. [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/) decides where each update lands, and the [CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) page covers the agent itself. Connection steps live on the [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) pages.

## The weekly review {#weekly-review}

Oliv AI's Deal Driver agent delivers its reports in **Reports › My Reports**. A **One-on-One Prep** report arrives for each rep on that rep's set day, such as every Thursday or every Friday. A **Morning Brief** covers the team's meetings every weekday. Through the week Deal Driver flags deals that need attention, each with a suggested action, and nudges reps directly when next steps go overdue. Every Monday, a **Pipeline Review** for leadership is ready before the first standup.

<figure>

![Deal Driver's Pipeline Review report open in My Reports, with an inner navigation of Overview, Closed, Closing Soon, Deals at Risk and Quick Wins, and an Overview summarising the pipeline's key opportunities, customer updates and next steps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/reports/oliv-ai_198_reports_my-reports_deal-driver-pipeline-review-report-open-overview-closed-closing-soon-deals-at-risk-quick-wins-stalled-navigation.webp)

<figcaption>The weekly review starts from the Pipeline Review, which groups every deal by status so a manager can jump straight to the deals at risk.</figcaption>
</figure>

Two more agents join the review. Oliv AI's Coach agent follows each rep's 1:1 report minutes later with that rep's coaching goal and weekly progress. Oliv AI's Forecaster agent rolls Deal Driver's signals into the forecast number. The [pipeline review guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) runs the meeting deal by deal. The [Deal Driver](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), [Forecaster](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) and [Coach](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) agent pages explain each agent's part.

## How the workflows connect {#how-they-connect}

Each workflow feeds the next one. The brief draws on what earlier calls captured. The call produces the follow-up and the field updates. Each 1:1 report reads the deal fields CRM Manager keeps current, so the review is only as good as that upkeep.

Oliv AI's Olivia agent sits across all four. You can ask her to prepare you for a call or draft the follow-up from this afternoon's meeting, and she hands the work to the right specialist. Her rules come from the process handbook that Oliv AI's [Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) maintains. The [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) page shows how to ask her. For a role-based view of the same week, read [running deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Before you start {#before-you-start}

Every workflow needs three connections: your calendar, a call recorder and your CRM. Calendar integration is required, because Oliv AI uses it to know which meetings to record. Teams and Google Meet need nothing more once the calendar is connected, and Zoom uses the Oliv AI Zoom app. Most teams are connected within a week.

Seat roles decide which apps each person works in, so check [plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) before you roll out. The full list of connected tools is on [Oliv AI's integrations page](https://www.oliv.ai/integrations). For the reasoning behind automating prep, read [AI meeting preparation tools compared by CRM depth](https://www.oliv.ai/blog/ai-meeting-preparation-tool) and the [CRO's guide to CRM data](https://www.oliv.ai/blog/crm-data-strategy-cro-revenue-predictability).
