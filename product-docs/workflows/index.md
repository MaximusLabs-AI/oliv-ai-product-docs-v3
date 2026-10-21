# Workflows overview

How Oliv AI's agents carry a deal through the week, from the brief before a meeting and the follow-up after it to CRM upkeep and the weekly pipeline review.

- Applies to: Revenue teams with a connected calendar and CRM
- Status: Live
- Verified: 2026-10-21
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

A first meeting with someone new works differently, because there's no deal history yet. You ask Oliv AI's Olivia agent to prepare you, and she researches the company and the person. The [meeting preparation guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/#step-4-first-meeting) covers both kinds of meeting. For what the brief agent does on every deal, read the [Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) page.

## During and after the call {#during-and-after}

Oliv AI records the call, then turns it into everything you'd otherwise write by hand. When someone from your company organizes the meeting, Oliv AI records botlessly through the meeting platform. When an external organizer owns it, a note taker joins under your company's name. [Bot and botless recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) explains the choice, and the [Zoom integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) covers Zoom calls in detail.

The meeting summary is ready as soon as the call ends. Oliv AI's Meeting Assistant agent then drafts the follow-up email from the transcript, with the recap, commitments, owners and next steps already written. It also proposes CRM updates and flags qualification gaps. The [follow-up guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) walks through reviewing each one, and the [meeting details](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) page shows the recorded call itself. If your team works in Slack, the summary also arrives there through the [Slack integration](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/).

## Between meetings {#between-meetings}

Oliv AI's CRM Manager agent reads every meeting, call and email, then updates accounts, contacts, opportunities, activities and tasks in Salesforce, HubSpot or Zoho. Your CRM stays the system of record, and Oliv AI works on top of it.

By default every suggested update waits for review before anything reaches the CRM. Each one shows the field, the current value, the proposed value and the moment in the conversation behind it. You accept, edit or reject it, then switch to auto mode once you trust it. The [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) covers setup and a monthly hygiene check. [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/) decides where each update lands, and the [CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) page covers the agent itself. Connection steps live on the [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) pages.

## The weekly review {#weekly-review}

Oliv AI's Deal Driver agent sends a per-rep 1:1 report every Thursday, ready before the manager's first meeting of the day. Through the week it flags deals that need attention, each with a suggested action. It also nudges reps directly when next steps go overdue. On Monday, a pipeline summary for leadership is ready before the first standup.

Two more agents join the review. Oliv AI's Coach agent follows the Thursday report minutes later with each rep's coaching goal and weekly progress. Oliv AI's Forecaster agent rolls Deal Driver's signals into the forecast number. The [pipeline review guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) runs the meeting deal by deal. The [Deal Driver](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), [Forecaster](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) and [Coach](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) agent pages explain each agent's part.

## How the workflows connect {#how-they-connect}

Each workflow feeds the next one. The brief draws on what earlier calls captured. The call produces the follow-up and the field updates. The Thursday report reads the deal fields CRM Manager keeps current, so the review is only as good as that upkeep.

Oliv AI's Olivia agent sits across all four. You can ask her to prepare you for a call or draft the follow-up from this afternoon's meeting, and she hands the work to the right specialist. Her rules come from the process handbook that Oliv AI's [Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) maintains. The [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) page shows how to ask her. For a role-based view of the same week, read [running deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Before you start {#before-you-start}

Every workflow needs three connections: your calendar, a call recorder and your CRM. Calendar integration is required, because Oliv AI uses it to know which meetings to record. Teams and Google Meet need nothing more once the calendar is connected, and Zoom uses the Oliv AI Zoom app. Most teams are connected within a week.

Seat roles decide which apps each person works in, so check [plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) before you roll out. The full list of connected tools is on [Oliv AI's integrations page](https://www.oliv.ai/integrations). For the reasoning behind automating prep, read [AI meeting preparation tools compared by CRM depth](https://www.oliv.ai/blog/ai-meeting-preparation-tool) and the [CRO's guide to CRM data](https://www.oliv.ai/blog/crm-data-strategy-cro-revenue-predictability).
