# Record a meeting and follow up

How to get a sales call recorded in Oliv AI and send the follow-up, from the meeting summary to the drafted email, the proposed CRM updates and the qualification gaps to check.

- Applies to: Meetings Oliv AI records, and follow-ups on active opportunities
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/

Oliv AI records your sales calls and has the follow-up ready within minutes of the call ending. Oliv AI's Meeting Assistant agent drafts the email from the transcript, with the recap, commitments, owners and next steps already written. It also proposes CRM updates and flags qualification gaps for you to review. This guide covers getting the call recorded, then reviewing and sending everything that comes back.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What you get after a call** | A meeting summary, a follow-up email draft, proposed CRM updates and qualification gap flags |
| **When** | The summary as soon as the meeting ends; the follow-up within minutes |
| **Drafted by** | Oliv AI's Meeting Assistant agent, from the call transcript |
| **The draft covers** | The recap, commitments, owners and next steps |
| **CRM updates proposed** | Stage, amount, close date, qualification fields and next steps |
| **Before anything goes out** | You review, adjust and send |
| **Works on** | Meetings linked to an active opportunity |

## Before you begin {#before-you-begin}

- **Connect your calendar.** Oliv AI needs calendar access to know which meetings to join and record.
- **Connect your CRM.** Proposed updates are written against your deals in [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho.
- **Have the deal in your CRM.** Oliv AI's Meeting Assistant agent works on meetings linked to an active opportunity.
- **[Connect Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) if you use it.** The meeting summary arrives in Slack as soon as the meeting ends, and by email too.

## Step 1: Get the call recorded {#step-1-record}

Oliv AI joins Zoom, Google Meet and Microsoft Teams meetings automatically once your calendar is connected, with the [Oliv AI Zoom app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) installed for Zoom. If you or someone from your company organized the meeting, Oliv AI [records botlessly through the meeting app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/), with no extra participant. If the customer organized it, a note taker joins with your company's name, and the host may need to admit it from the lobby. Either way, every speaker is transcribed and labeled.

## Step 2: Read the meeting summary {#step-2-summary}

The meeting summary is sent immediately after the meeting ends, to Slack and to your email by default. It holds the meeting details: title, date, time, participants and the account. It also covers key takeaways, next steps, talk time and a scorecard.

To [open the full recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) from Slack, click **Open Meeting** in the message. You can also find any recording later by searching the [**Meetings** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/), for example by the date it was held.

## Step 3: Review the follow-up draft {#step-3-review-draft}

Within minutes of the call ending, [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) drafts your follow-up. It isn't a template. The agent reads the transcript and writes from the actual conversation:

| Part | What it covers |
|---|---|
| **Recap** | What was discussed on the call |
| **Commitments** | What was agreed, and by whom |
| **Owners** | Who is doing each next step |
| **Next steps** | What happens next, with specific dates where possible |

Read it through, change anything that needs changing, and send it. Nothing reaches your buyer until you've reviewed it. If you'd rather ask, tell [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) "Draft the follow-up from my call this afternoon" and she drafts it from the transcript.

## Step 4: Approve the CRM updates {#step-4-crm}

From what was said on the call, Oliv AI [proposes deal field updates](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) for your approval:

1. Check the proposed **stage**, **amount** and **close date** against what the buyer told you.
2. Check the qualification fields and the next steps.
3. Approve the updates that are right. [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) writes them, so your pipeline stays current without manual cleanup.

How freely agents act in your CRM is set per action. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains which actions wait for your approval.

## Step 5: Check the qualification gaps {#step-5-gaps}

After every call, Oliv AI flags new information, or notable absences, that affect the deal's qualification status. Gaps show up while there's still time to close them. Turn each one into a question for the next meeting, and it will feed the brief that helps you [prepare for the next meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

## Step 6: Share the moment that matters {#step-6-share}

Sometimes a colleague needs one part of the call, not all of it. In the transcript, [find the minute marker you want](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) and check the box beside the segment. Copy the selected portion and open it in a new tab to start playback from that minute.

## What post-call follow-up in Oliv AI is {#what-it-is}

Post-call follow-up is the work Oliv AI does once a recorded meeting ends, so you don't write the recap or update the CRM from memory. It has four outputs.

| Output | Sent by | When |
|---|---|---|
| **Meeting summary** | Oliv AI, to Slack and email | Immediately after the meeting ends |
| **Follow-up email draft** | Oliv AI's Meeting Assistant agent | Within minutes of the call ending |
| **Proposed CRM updates** | Oliv AI's Meeting Assistant agent, written by Oliv AI's CRM Manager agent | After the recording is processed |
| **Qualification gap flags** | Oliv AI's Meeting Assistant agent | After every call |

Oliv AI's Olivia agent drives the whole post-meeting workflow: follow-up drafted, CRM updates flagged for review and next steps identified. You review and act; she handles the execution. It's the after-call half of an [AI meeting assistant for sales](https://www.oliv.ai/blog/ai-meeting-assistant-for-sales).

## Why post-call follow-up matters {#why-it-matters}

### What it's for {#what-its-for}

Post-call follow-up gets the recap to your buyer while the call is still fresh. It also keeps the CRM in step with what was actually said. You spend the minutes after a call reviewing, not writing.

### How it helps {#how-it-helps}

- **The draft is waiting.** The follow-up is written within minutes of the call ending.
- **It comes from the call.** The transcript, not a template, supplies the recap and next steps.
- **The CRM keeps up.** Field updates are proposed from what was said, ready to approve.
- **Gaps surface early.** Missing qualification details show up after every call, not at the forecast review.

### What happens without it {#without-it}

Without it, the follow-up email takes about 15 minutes after every call. CRM updates depend on what the rep remembers. Qualification gaps come to light at the forecast review, when it's too late to act.

### Why buyers care {#why-buyers-care}

This matters to [account executives](https://www.oliv.ai/account-executives) with calls booked back to back, because the follow-up is the first thing to slip. It matters to sales managers who need deal fields they can trust. It counts most late in a deal, when a slow recap costs momentum.

## The Oliv AI approach to post-call follow-up {#approach}

{/* 5P */}

Imagine an account executive who has just finished a product demo with a buying committee of four. The next meeting starts in twenty minutes. Before then, the AE wants the recap in the champion's inbox, with the pricing question and the security review written down.

The usual fix is a quick email typed from memory, or a note to write it properly that evening. A rushed recap tends to miss who owns what. An evening recap arrives after the buyer has moved on to other things. Meanwhile the CRM still shows last week's stage and close date.

Everything the recap needs was said on the call. Who asked about pricing, what was agreed, and when the security review happens are all in the transcript. Writing the email is mostly a job of finding those lines and putting them in order.

Oliv AI does that job with its Meeting Assistant agent. Within minutes of the demo ending, the draft is written from the transcript, with the recap, commitments, owners and next steps. Proposed CRM updates and qualification gap flags come back alongside it for the AE to approve. The AE reads it on the way to the next call.

The draft is never a template, and nothing reaches the buyer until the AE has read it and pressed send. How other platforms handle the draft and the CRM after a call is covered in How post-call follow-up compares, below.

## How post-call follow-up works with other features {#works-with}

### Meeting prep {#with-prep}

What you approve after one call feeds the brief before the next. Oliv AI's Meeting Assistant agent [sends that brief](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) before every meeting on an active opportunity, with the deal summary, qualification status and a recommended agenda.

### Recording modes {#with-recording-modes}

Who sends the invite [decides how a call is recorded](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/). When your company organizes, Oliv AI records through [Zoom](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) or Microsoft Teams with no bot. When the customer organizes, a note taker joins with your company's name. [Converse](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) also captures phone calls and in-person meetings.

### Manager 1:1s {#with-one-on-ones}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) pairs the per-call summaries with pipeline context before each [manager 1:1](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/). Managers coach from the same picture their reps have.

### Clips {#with-clips}

[Oliv AI's Content Curator agent](https://www.oliv.ai/agents/content-curator) reviews every new recording and [clips the moments your team asked for](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/), such as a well-handled pricing objection.

### Your CRM {#with-crm}

Proposed updates land in [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho once approved. See every connection on [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/).

## Who records and follows up with Oliv AI, and how {#who-uses-it}

These are typical patterns, shown to illustrate how teams use the follow-up.

### Account executives {#account-executives}

An account executive reviews the draft between back-to-back calls, fixes one date and sends it. The CRM updates get approved in the same sitting. It's a core part of how AEs [run their deals in Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Sales development {#sales-development}

A [sales development](https://www.oliv.ai/sales-development) rep finishes a discovery call that turns into an opportunity. The follow-up and the first CRM fields come back ready, so the handoff to the account executive starts with a clean record.

### Account managers {#account-managers}

An [account manager](https://www.oliv.ai/account-management) closes a renewal call with three commitments from the customer. The recap lists each one with an owner, so nothing gets lost before the next check-in.

### Sales managers {#sales-managers}

A [sales manager](https://www.oliv.ai/sales-managers) reads the qualification gap flags across the team's calls. Gaps on late-stage deals become the agenda for that week's 1:1s.

## How post-call follow-up compares {#compare}

Oliv AI's follow-up is drafted from the transcript within minutes, without anyone clicking a button. The proposed CRM updates and qualification gaps come back in the same pass, ready to approve. Oliv AI is the only platform in this table that does all three.

Post-call follow-up, from each platform's public documentation:

| Platform | Follow-up drafted without a click | CRM updates proposed for approval | Qualification gaps flagged after the call |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([button on the call page](https://help.gong.io/docs/about-the-call-page)) | Partly ([one text field on deal boards](https://help.gong.io/docs/how-to-create-and-manage-deal-boards)) | Partly ([separate MEDDICC agent](https://help.gong.io/docs/agent-use-case-and-examples)) |
| **Avoma** | Partly ([click Generate Follow-up Email](https://help.avoma.com/use-avoma-after-meeting)) | [Automated field updates](https://help.avoma.com/import-your-crm-custom-fields-properties-into-pipeline-views) | Yes ([gaps in the deal dashboard](https://help.avoma.com/configure-deal-methodology)) |
| **Fireflies.ai** | Yes ([drafted after every sales call](https://guide.fireflies.ai/articles/2790601073-fireflies-for-sales-your-ai-platform-for-everything-after-the-call)) | Yes ([Autofill CRM review](https://guide.fireflies.ai/articles/1729159683-autofill-crm-for-salesforce-automatically-extract-and-sync-meeting-data-to-contacts-accounts-and-opportunities)) | BANT and MEDDIC scorecards ([AI templates](https://guide.fireflies.ai/articles/2790601073-fireflies-for-sales-your-ai-platform-for-everything-after-the-call)) |
| **Fathom** | Yes ([AI follow-up email drafts](https://help.fathom.video/en/articles/640768)) | [Writes summaries and tasks to CRM](https://help.fathom.video/en/articles/448640) | Scorecard templates by methodology ([AI Scorecards](https://help.fathom.video/en/articles/7906049)) |
| **Outreach** | Partly ([Compose email from the summary](https://support.outreach.io/support/solutions/articles/159000425934-how-to-use-kaia-smart-meeting-and-call-assist)) | Yes ([Deal Agent field recommendations](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) | Partly ([separate Deal Agent](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for post-call follow-up {#compare-stronger}

- **Drafted before you ask.** Oliv AI's Meeting Assistant agent writes the follow-up once the recording is processed. [Avoma documents a Generate Follow-up Email button you click in the meeting](https://help.avoma.com/use-avoma-after-meeting). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Every deal field in one review.** Oliv AI proposes stage, amount, close date, qualification fields and next steps for approval. [Gong fills one text-only CRM field with AI suggested updates on a deal board](https://help.gong.io/docs/how-to-create-and-manage-deal-boards). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Gaps flagged with the draft.** Oliv AI flags qualification gaps after every call, next to the follow-up. [Fathom offers scorecard templates you adapt to a methodology like SPICED](https://help.fathom.video/en/articles/7906049).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Active opportunities only.** The follow-up draft, CRM updates and gap flags cover meetings linked to an active opportunity in your CRM.
- **No recording, no draft.** The draft is built after the recording is processed, so the call has to be recorded first.
- **Drafts wait for you.** Nothing is sent to your buyer and no field is written until you review it.
- **Lobbies can delay recording.** On a meeting the customer hosts, the note taker may need admitting before it can record.
- **Summary messages can be turned off.** If you'd rather not get the Slack and email summaries, disable them on your **Profile Settings** page.

## Common questions {#common-questions}

#### How soon is the follow-up ready? {#faq-how-soon}

Within minutes of the call ending. The meeting summary arrives sooner, immediately after the meeting ends.

#### Is the follow-up email a template? {#faq-template}

No. Oliv AI's Meeting Assistant agent reads the transcript and writes the draft from the actual conversation: what was discussed, what was agreed and what happens next.

#### What does the draft include? {#faq-draft-contents}

The recap, the commitments, the owners and the next steps, with specific dates where possible.

#### Is anything sent without me? {#faq-review}

No. You review the draft, adjust anything that needs changing and send it yourself.

#### Which CRM fields does it propose? {#faq-crm-fields}

Stage, amount, close date, qualification fields and next steps, based on what was said on the call. You approve them before they're written.

#### What's in the meeting summary? {#faq-summary}

The title, date, time, participants and account, plus key takeaways, next steps, talk time and a scorecard. It goes to Slack and email.

#### Can I ask for a follow-up instead of waiting? {#faq-ask-olivia}

Yes. Tell Oliv AI's Olivia agent to draft the follow-up from your call, and she pulls from the meeting transcript to write it.

#### Does it work if the customer hosted the meeting? {#faq-customer-hosted}

Yes. A note taker joins with your company's name, so the call is recorded and the follow-up still comes back to you.

#### Which meetings get a follow-up draft? {#faq-which-meetings}

Meetings linked to an active opportunity in your CRM. If the deal exists and the meeting is on your calendar, the agent runs automatically.

#### Can I share part of a call? {#faq-share-part}

Yes. Select the segment by its minute marker in the transcript, copy it, and open it in a new tab to play from that minute.

## Related {#related}

- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): ask for a follow-up, or anything else on a deal.
- [Meeting Assistant agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/): briefs before and follow-ups after every deal meeting.
- [Sales call notes software](https://www.oliv.ai/blog/sales-call-notes): how call notes tools compare on structure and CRM sync.
- [Taking notes during sales calls](https://www.oliv.ai/blog/how-to-take-meeting-notes-during-sales-calls): what to capture as the call happens.
- [Perfecting the sales follow-up](https://www.oliv.ai/blog/sales-follow-up): what a strong follow-up does for the deal.
- [Plans and pricing](https://www.oliv.ai/pricing): how Oliv AI is priced.
