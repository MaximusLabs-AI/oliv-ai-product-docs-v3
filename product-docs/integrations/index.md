# Integrations overview

The tools Oliv AI connects to, from your CRM and calendar to Zoom and Slack, what each connection is for, and which ones have their own setup guide.

- Applies to: Revenue operations, admins and anyone connecting Oliv AI to their tools
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/

Oliv AI connects to the tools your revenue team already uses and works as a layer on top of them. Your CRM stays the system of record. Your calendar tells Oliv AI which meetings to capture, your video tool carries the recording, and Slack brings summaries and alerts to where your team works. This page shows how the connections fit together and which ones have a full guide.

## What connects to what {#categories}

| Category | Tools | What Oliv AI does with it | Guide |
|---|---|---|---|
| **CRM** | Salesforce, HubSpot, Zoho | Pulls records in and writes conversation insights back | [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) |
| **Calendar** | Gmail and Outlook calendars | Tells Oliv AI which meetings to join; required | Covered below |
| **Video conferencing** | Zoom, Microsoft Teams, Google Meet | Records meetings for summaries and follow-ups | [Zoom](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) |
| **Collaboration** | Slack, Microsoft Teams, Google Chat | Sends meeting reminders, summaries and agent alerts | [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) |

Four of these have their own page today: Salesforce, HubSpot, Zoom and Slack. The rest are described here as far as setup goes.

## Your CRM {#crm}

Oliv AI pulls in your accounts, contacts and opportunities, then fills them back with what customers said. Salesforce, HubSpot and Zoho work out of the box. Additional CRMs are available on request, so contact Oliv AI's sales team if yours isn't listed.

- **Salesforce.** A Salesforce admin installs the package for all users. The [Salesforce setup guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/#connect-salesforce) covers the install, review settings and cleaning up existing data.
- **HubSpot.** You connect from the HubSpot integration in the Oliv AI web app, then share your HubSpot URL. The [HubSpot setup guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/#connect-hubspot) also shows Oliv AI fields on deal records.

Oliv AI's CRM Manager agent does the writing. By default every update waits for review before it reaches the CRM. [CRM field mapping](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/) decides which field each update lands in, and the [CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) page covers approvals and auto mode. For how two-way sync enriches your records without replacing them, read about [the context graph and CRM sync](https://www.oliv.ai/blog/bi-directional-crm-sync-ai).

## Calendar and meeting recording {#calendar-and-recording}

Calendar integration is required. Without it, Oliv AI can't take notes during your meetings. You connect a Gmail or Outlook calendar by logging in to the Oliv AI web app.

Once the calendar is connected, Oliv AI joins Microsoft Teams and Google Meet calls with no further setup. Zoom uses the Oliv AI Zoom app. When someone from your company organizes the meeting, Oliv AI can record botlessly through the meeting platform. When an external organizer owns it, a note taker joins under your company's name. [Bot and botless recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) explains the choice. The [Zoom guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/#set-up) covers both Zoom apps, including CRM fields inside the meeting window.

Oliv AI joins external calls automatically. You can manage that from the Oliv AI web app or from your Google or Outlook calendar, using the Chrome extension or the Outlook add-in. Everything recorded lands in the [Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/), and you can find a past call in the [meetings list](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/).

## Slack and other channels {#slack-and-channels}

Once Slack is connected, three meeting messages start on their own: a summary of tomorrow's meetings, a prep summary before each call and a meeting summary straight after it. They also go to your email by default. The [Slack guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/#set-up) covers setup and how to turn them off.

Agents post to the same channels. Oliv AI's Deal Driver agent sends managers its alerts, briefs and summaries through Slack, email or the Oliv platform. Oliv AI's Olivia agent works through Slack, Teams or the Oliv AI product itself, as the [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) page shows. For Microsoft Teams, Oliv AI sends an invitation to a shared channel.

## Other sources of context {#other-sources}

Meetings are one source among several. Oliv AI also captures email from Gmail and Outlook, phone calls, and in-person meetings recorded with Plaud, a wearable recorder. For account data beyond conversations, Oliv AI connects to Snowflake, Databricks, Redshift and BigQuery. That adds product usage, support tickets, billing history and onboarding completion to each account.

These sources don't have a setup guide in these docs. [Oliv AI's integrations page](https://www.oliv.ai/integrations) lists the categories it works with and has a way to request an integration. [Context capture](https://www.oliv.ai/context-capture) shows every channel Oliv AI captures.

## How agents use the connections {#agents-and-connections}

Every agent reads and writes through the tools above. Oliv AI's Meeting Assistant agent needs your calendar, a call recorder and your CRM before it sends its first brief, as the [meeting preparation guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) explains. The [CRM upkeep guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) shows CRM Manager writing back after each call.

Agents you build use the same connections. Each tool an agent holds is one action in a connected system, and its run mode decides whether the agent asks first. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) covers those settings, and [agent triggers](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/) can start an agent when a CRM deal changes. Seat roles decide which apps each person uses, so check [plans and seat roles](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) before you connect a whole team. For a wider plan, the [RevOps integration blueprint](https://www.oliv.ai/blog/revenue-intelligence-integration-revops-crm-slack-email) covers calls, email, Slack and the CRM together.
