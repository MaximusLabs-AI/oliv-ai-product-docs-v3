# AI follow-up email: how to review the draft after a recorded call and approve CRM updates

How to get a sales call recorded in Oliv AI and send the follow-up, from the meeting summary to the drafted email, the proposed CRM updates and the qualification gaps to check.

- Applies to: Meetings Oliv AI records, and follow-ups on active opportunities
- Status: Live
- Verified: 2026-11-03
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/

You've just finished a customer call and want an accurate AI follow-up email and the CRM updates to check within minutes, before your next meeting. Oliv AI's Meeting Assistant agent drafts that email from the transcript, with the recap, commitments, owners and next steps already written. It also proposes CRM updates and flags qualification gaps for you to review, and you send the email yourself. This guide covers getting the call recorded, then reviewing and sending everything that comes back.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What you get after a call** | A meeting summary, a follow-up email draft, proposed CRM updates and qualification gap flags |
| **When** | The summary as soon as the meeting ends; the follow-up within minutes |
| **Drafted by** | Oliv AI's Meeting Assistant agent, from the call transcript |
| **The draft covers** | The recap, commitments, owners and next steps |
| **CRM updates proposed** | Stage, amount, close date, qualification fields and next steps |
| **Where you review it** | **Activities › Meetings** or **Activities › Calls**, in a drawer with tabs for the summary, tasks, insights, recording and CRM changes |
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

To [open the full recording](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) from Slack, click **Open Meeting** in the message. You can also find any meeting later in **Activities › Meetings**. The [Meetings list](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) has **My meetings** and **Team meetings** tabs, with **Search**, **Group**, **Fields**, **Sort** and **Filter**.

<figure>

![The Meetings list on the My meetings tab, a grid of captured meetings with columns for Meeting, Duration, Meeting with, Next Step and AI Summary. Each row has a meeting-type dropdown such as Prospect, Customer, Candidate or Colleague and a colour-coded next step.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_239_activities-meetings_meetings-list_my-meetings-tab_grid-with-meeting-type-next-step-and-ai-summary-columns.webp)

<figcaption>The Meetings list already shows each call's next step and AI summary, so you can see what needs following up before you open a single meeting. The durations and dates here come from a demo account.</figcaption>
</figure>

Each row shows the meeting's **Next Step** and **AI Summary**, and a **Meeting with** dropdown that classes it as Prospect, Customer, Candidate or Colleague. Click a row to open the meeting. Its **Overview** tab holds:

- **Key takeaways**, each with timestamps that jump to that moment in the recording;
- an **AI Summary**, in headed sections with their own timestamps;
- an updates card for the account, with the deal's stage, amount and close date and a **Review Deal** button.

<figure>

![A meeting's details drawer on the Overview tab, with tabs for Overview, Action Items, Meeting insights, Recording, Coaching, Attendees and CRM Updates. A Key takeaways card and an AI Summary card carry blue timestamps, and an account updates card shows the deal stage, amount, close date and Review Deal.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_240_activities-meetings_meeting-details-drawer_overview-tab_key-takeaways-ai-summary-and-deal-updates-card.webp)

<figcaption>The Overview tab is the in-app version of the meeting summary. Every takeaway links back to the moment it came from, and the seven tabs split the rest of the follow-up work. The account, figures and dates on this screen are sample data.</figcaption>
</figure>

### Check the action items {#step-2-action-items}

The **Action Items** tab turns the call's commitments into tasks. Three cards at the top show the **Next meeting**, the **Next action** and the **Next follow-up**, each with a status such as **Accepted** or **Overdue**. Below them, a **Tasks** table lists each task with an **Assignee**, a **Due Date** and a timestamp back to the moment it was agreed.

<figure>

![The Action Items tab of a meeting drawer. Cards for Next meeting, marked Accepted, Next action with a date, and Next follow-up, marked Overdue, sit above a Pending tasks table under Our tasks, with four tasks, an assignee and a due date for each, and Add task at the bottom.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_241_activities-meetings_meeting-details-drawer_action-items-tab_next-meeting-next-action-follow-up-and-our-tasks-table.webp)

<figcaption>Action Items is where a call's commitments become tasks with owners and due dates. Each task links back to the moment in the call where it was agreed. The dates are demo values, so the Overdue mark says nothing about a real deal.</figcaption>
</figure>

Tick a task when it's done, switch the status filter from **Pending**, or **Add task** by hand. Phone calls in **Activities › Calls** get the same tab, split into **Our tasks** and **Their tasks**, so you can see what the buyer owes as well.

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

From what was said on the call, Oliv AI [proposes deal field updates](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) and records them on the meeting's **CRM Updates** tab:

1. Open **CRM Updates**. A timeline lists every change made after the call, such as a refreshed account summary, a scorecard update or a new contact. A green check marks the ones already done.
2. Find any **Pending Update**, such as a move to a new stage. Check it against what the buyer told you, then click **Update Deal** to confirm it.
3. Open the changed records with **View Account**, **View Deal** or **View Contact**. On the deal itself, the **CRM Updates** tab lists **AI Suggestions** to **Accept** or **Reject**, with the current CRM value beside each one.

<figure>

![The CRM Updates tab of a meeting drawer: a vertical timeline of changes made after the meeting. Completed entries, marked with green checks, update the account, a BANT scorecard and two new contacts, while one Pending Update to move the deal to Proposal has an Update Deal button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_246_activities-meetings_meeting-details-drawer_crm-updates-tab_account-deal-bant-and-contact-updates-with-pending-stage-move.webp)

<figcaption>CRM Updates shows what reached your CRM after the call and what is still waiting. A stage move stays pending until you confirm it with Update Deal.</figcaption>
</figure>

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) writes the updates, so your pipeline stays current without manual cleanup.

How freely agents act in your CRM is set per action. [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains which actions wait for your approval.

## Step 5: Check the qualification gaps {#step-5-gaps}

After every deal call, Oliv AI flags new information, or notable absences, that affect the deal's qualification status. Gaps show up while there's still time to close them.

Open the meeting's **Meeting insights** tab to see them. A row of chips, from **Metrics** and **Economic Buyer** to **Champion** and **Additional Fields**, follows your qualification framework. Click a chip to jump to its section, where each card holds what was said, with timestamps. Where nothing was said, the card says so instead of guessing.

<figure>

![The Meeting insights tab of a meeting drawer, with chips for Metrics, Economic Buyer, Decision Criteria, Decision Process, Paper Process, Identify Pain, Champion and Additional Fields. Cards under Metrics and Economic Buyer hold evidence from the call with timestamps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_242_activities-meetings_meeting-details-drawer_meeting-insights-tab_meddpicc-sections-metrics-and-economic-buyer.webp)

<figcaption>Meeting insights files what the buyer said under each qualification criterion. A card that says nothing was discussed is the gap to raise on the next call. Any figures on these cards are made up for the demo.</figcaption>
</figure>

Turn each gap into a question for the next meeting, and it will feed the brief that helps you [prepare for the next meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

## Step 6: Share the moment that matters {#step-6-share}

Sometimes a colleague needs one part of the call, not all of it. Open the meeting's **Recording** tab, find the moment in **Chapters** or **Transcripts**, then use the buttons under the player:

- **Clip** cuts the key moment, which then sits in your clip libraries.
- **Share** sends the meeting to a colleague.
- **Add Comment** pins a note to that point in the call, and **Comments** shows your team's notes.

<figure>

![The Recording tab of a meeting drawer: a video player with Add Comment, Clip and Share buttons beneath it, a speaker Timeline showing each person's talk time and engagement, and a Chapters list with titles, timestamps and a sentence for each chapter.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_243_activities-meetings_meeting-details-drawer_recording-tab_blank-player-add-comment-clip-share-timeline-and-chapters.webp)

<figcaption>The Recording tab is where you cut and share the moment that matters. Chapters and the speaker timeline help you find it without replaying the whole call. Its talk-time numbers are illustrative.</figcaption>
</figure>

A phone call's **Recording** tab plays the audio with a **Transcript** and **Comments** beside it, a **Timeline** of talk time and engagement, and **Add Comment**. The [meeting details page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) covers every tab in depth.

<figure>

![The Recording tab of a phone call's drawer: an audio waveform player with play, a time readout and volume, a speaker Timeline with talk time and engagement for each person, an Add Comment button, and a speaker-labelled Transcript with timestamps on the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-calls/oliv-ai_250_activities-calls_call-details-drawer_recording-tab_audio-waveform-player-talk-time-timeline-and-transcript.webp)

<figcaption>Phone calls get the same replay and transcript as meetings, with comments you can attach to a moment. Use it to check a commitment before you send the follow-up. The times and percentages shown are sample values.</figcaption>
</figure>

## What post-call follow-up in Oliv AI is {#what-it-is}

Post-call follow-up is the work Oliv AI does once a recorded meeting ends, so you don't write the recap or update the CRM from memory. It has five outputs.

| Output | Sent by | When |
|---|---|---|
| **Meeting summary** | Oliv AI, to Slack and email | Immediately after the meeting ends |
| **Takeaways, summary and tasks** | Oliv AI, on the meeting's Overview and Action Items tabs | Once the recording is processed |
| **Follow-up email draft** | Oliv AI's Meeting Assistant agent | Within minutes of the call ending |
| **Proposed CRM updates** | Oliv AI's Meeting Assistant agent, written by Oliv AI's CRM Manager agent | After the recording is processed |
| **Qualification gap flags** | Oliv AI's Meeting Assistant agent | After every deal call |

Oliv AI's Olivia agent drives the whole post-meeting workflow: follow-up drafted, CRM updates flagged for review and next steps identified. You review and act; she handles the execution. It's the after-call half of an [AI meeting assistant for sales](https://www.oliv.ai/blog/ai-meeting-assistant-for-sales).

## Why post-call follow-up matters {#why-it-matters}

### What it's for {#what-its-for}

Post-call follow-up gets the recap to your buyer while the call is still fresh. It also keeps the CRM in step with what was actually said. You spend the minutes after a call reviewing, not writing.

### How it helps {#how-it-helps}

- **The draft is waiting.** The follow-up is written within minutes of the call ending.
- **It comes from the call.** The transcript, not a template, supplies the recap and next steps.
- **The CRM keeps up.** Field updates are proposed from what was said, ready to approve.
- **Gaps surface early.** Missing qualification details show up after every deal call, not at the forecast review.

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

The draft is never a template, and nothing reaches the buyer until the AE has read it and pressed send. How other platforms handle the draft and the CRM after a call is covered in How Oliv AI compares for AI follow-up emails, below.

## How a follow-up email gets written after a sales call {#methods}

There are four common ways to get this email written. Each one fails in its own way, so knowing them tells you what to look for when a draft lands in front of you.

### From memory {#from-memory}

You type the recap straight after the call, from what you recall. This catches whatever struck you most, and it's quick. It tends to miss who owns what, especially with the next meeting already on your mind. Nielsen Norman Group explains that [working memory has limited capacity](https://www.nngroup.com/articles/working-memory-external-memory/), and that overloading it can slow a task or cause mistakes.

### From a template {#from-template}

You paste a saved email and fill in the blanks. This catches structure, so you won't forget to ask for the next meeting. It misses everything specific to this buyer, because the blanks still come from your memory or your notes.

### From your own notes {#from-notes}

You work from what you typed during the call. This catches the commitments you wrote down at the time. It misses whatever was said while you were talking, and the note often doesn't say who agreed to what.

### From the transcript {#from-transcript}

You work from the words actually spoken, with each speaker labeled. This catches who said what, including the small promises you'd otherwise lose. It misses anything outside the call, such as a hallway chat or a decision you made afterwards. That part is still yours to add.

### Which of these Oliv AI does {#which-oliv-does}

Oliv AI uses the transcript. Oliv AI's Meeting Assistant agent reads it and writes the draft from the actual conversation, so no template sits underneath. You then add what the call didn't cover before you send.

## What to check before you send or approve {#what-to-check}

Read the draft as your buyer would, then test it against the call. These are the errors to catch, because the buyer will act on what you send.

| What goes wrong | What to check | Where to check it |
|---|---|---|
| A date doesn't match what was said | Every date in the next steps | The timestamp on the task in **Action Items** |
| A task sits with the wrong person | Each owner against who agreed to it | **Assignee** in the **Tasks** table |
| A commitment is missing | The draft against the list of takeaways | **Key takeaways** on the **Overview** tab |
| The recap overstates what was agreed | Any line that sounds firmer than the buyer did | **Transcripts** on the **Recording** tab |
| Something meant for your team only is in the recap | Anything said before the buyer joined, or about your own side | Your own read of the draft |

### The subject line {#subject-line}

Check the subject line last. Nielsen Norman Group's guidance, written for email newsletters, says people [often read only the first few words](https://www.nngroup.com/articles/email-subject-lines/) of a subject line. So start with the deal or the next step, not with "Following up on our call".

### The CRM updates {#check-crm}

Approve against what the buyer said, not what you hoped they meant. Three fields deserve a second look on every call:

- **Close date.** In HubSpot, this is [the day the deal is expected to close](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties). Approve a new date only if the buyer gave you a reason for it.
- **Stage.** HubSpot [updates a deal's probability when a user moves it to a new stage](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties), and [weighted amount in board view depends on stage probability](https://knowledge.hubspot.com/object-settings/set-up-and-customize-pipelines). A stage move you wave through can therefore change the number your manager reads.
- **Next step.** Make sure the field matches the next step in your email, so the record and the buyer see the same plan.

What happens across the rest of the record is the job of [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/), so look there for field rules and hygiene.

## How to measure follow-up speed after a call {#measure-follow-up}

Two measures tell you how fast your follow-up really goes out. Log the hours between the call ending and the email leaving your outbox, then work out:

- **Same-day share:** the calls whose follow-up went out the same day, divided by all calls.
- **Median hours:** the middle value when you sort the gaps from shortest to longest.

Both have weak spots. Same-day share counts a 10-minute reply and an end-of-day reply as equal. The median ignores how late your worst emails were, so read the mean beside it, because a large gap between the two means a few calls ran very late. Neither one tells you whether the email was right, which is why the checks above come first.

### Where to find the timings {#where-timings}

The meeting's drawer shows its date, start time and length, and your sent folder shows when the email left. On the **Action Items** tab, the **Next follow-up** card carries a status such as **Overdue**, which gives you a quick flag between logging sessions.

## How to write a follow-up email after a sales call by hand {#write-by-hand}

If a call wasn't recorded, or you just want to know what the draft is replacing, this is the manual job:

1. Block the 15 minutes the email usually takes, right after the call and before your next meeting.
2. Go through your notes and write down what was agreed, by whom and by when.
3. Write the recap in two or three sentences, using the buyer's words for the problem.
4. List each commitment with one owner and one date. Where no date was set, propose one and say it's a proposal.
5. Write a subject line that starts with the deal or the next step.
6. Send the email, then log the hours since the call ended.
7. Open your CRM and update the stage, amount, close date, qualification fields and next steps from the same notes.
8. Write down anything the buyer didn't answer, because that's your agenda for the next call.

### What a sales follow-up email should include {#what-to-include}

Keep it to four things: a short recap, what each side committed to, who owns each item, and the next steps with dates. If the buyer could forward it to a colleague who missed the call and that person would know what happens next, it's done. For more on what a strong follow-up does for the deal, read about [perfecting the sales follow-up](https://www.oliv.ai/blog/sales-follow-up).

### The same job with an AI follow-up email in Oliv AI {#same-job-oliv}

Oliv AI takes over the writing and leaves you the judgment. Steps 2 to 4 become a read-through of a draft written from the transcript within minutes of the call ending. Step 7 becomes approving the proposed updates on the **CRM Updates** tab, and step 8 becomes reading the **Meeting insights** tab. Steps 5 and 6 stay with you: you check the subject line and you send the email.

### Worked example: hours from call end to follow-up sent on 10 calls {#worked-example}

This is an illustrative calculation with sample figures, not an Oliv AI output, and it claims no time saving from Oliv AI. A rep logs the hours between each call ending and the follow-up going out.

| Call | Hours from call end to email sent | Sent |
|---|---|---|
| 1 | 0.5 | Same day |
| 2 | 1 | Same day |
| 3 | 1 | Same day |
| 4 | 2 | Same day |
| 5 | 3 | Same day |
| 6 | 4 | Same day |
| 7 | 6 | Same day |
| 8 | 20 | Late |
| 9 | 24 | Late |
| 10 | 48 | Late |
| **Total** | **109.5** | **7 of 10 same day** |

| Measure | Arithmetic | Result |
|---|---|---|
| Same-day share | 7 ÷ 10 | 70% |
| Median | The middle two values are 3 and 4, so (3 + 4) ÷ 2 | 3.5 hours |
| Mean | 109.5 ÷ 10 | 10.95, about 11 hours |
| Hours in the three late calls | 20 + 24 + 48 | 92 of the 109.5 hours |

The median says a typical email goes out in 3.5 hours, which looks healthy. The mean of about 11 hours is roughly three times that, because three calls carry 92 of the 109.5 hours. So don't try to speed up every email. Look at calls 8, 9 and 10, find what they have in common, and fix that.

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

## How Oliv AI compares for AI follow-up emails {#compare}

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

### Why Oliv AI is the stronger choice for AI follow-up emails {#compare-stronger}

- **Drafted before you ask.** Oliv AI's Meeting Assistant agent writes the follow-up once the recording is processed. [Avoma documents a Generate Follow-up Email button you click in the meeting](https://help.avoma.com/use-avoma-after-meeting). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Every deal field in one review.** Oliv AI proposes stage, amount, close date, qualification fields and next steps for approval. [Gong fills one text-only CRM field with AI suggested updates on a deal board](https://help.gong.io/docs/how-to-create-and-manage-deal-boards). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).
- **Gaps flagged with the draft.** Oliv AI flags qualification gaps after every deal call, next to the follow-up. [Fathom offers scorecard templates you adapt to a methodology like SPICED](https://help.fathom.video/en/articles/7906049).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Active opportunities only.** The follow-up draft, CRM updates and gap flags cover meetings linked to an active opportunity in your CRM.
- **No recording, no draft.** The draft is built after the recording is processed, so the call has to be recorded first.
- **Emails wait for you.** Nothing is sent to your buyer until you review the draft and send it.
- **Stage moves wait for you.** A change of deal stage stays a **Pending Update** until you confirm it. Other updates, such as a refreshed account summary or a new contact, show on the **CRM Updates** tab once written.
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

No email is. You review the draft, adjust anything that needs changing and send it yourself. The meeting's CRM Updates tab shows each CRM change, and holds stage moves until you confirm them.

#### Which CRM fields does it propose? {#faq-crm-fields}

Stage, amount, close date, qualification fields and next steps, based on what was said on the call. A stage move waits for you to click Update Deal, and deal suggestions wait for Accept or Reject.

#### What's in the meeting summary? {#faq-summary}

The title, date, time, participants and account, plus key takeaways, next steps, talk time and a scorecard. It goes to Slack and email.

#### Can I ask for a follow-up instead of waiting? {#faq-ask-olivia}

Yes. Tell Oliv AI's Olivia agent to draft the follow-up from your call, and she pulls from the meeting transcript to write it.

#### Does it work if the customer hosted the meeting? {#faq-customer-hosted}

Yes. A note taker joins with your company's name, so the call is recorded and the follow-up still comes back to you.

#### Which meetings get a follow-up draft? {#faq-which-meetings}

Meetings linked to an active opportunity in your CRM. If the deal exists and the meeting is on your calendar, the agent runs automatically.

#### Can I share part of a call? {#faq-share-part}

Yes. On the meeting's Recording tab, find the moment in Chapters or Transcripts, then use Clip to cut it or Share to send the meeting.

#### How do you write a follow-up email after a sales call? {#faq-write-follow-up}

Write it right after the call. Recap the conversation in a few sentences, list each commitment with an owner and a date, then state the next step. Check every date against what was said before you send it.

#### What should a sales follow-up email include? {#faq-email-contents}

A short recap, what each side committed to, who owns each item, and the next steps with dates. A colleague who missed the call should be able to read it and know what happens next.

#### Can AI send follow-up emails automatically? {#faq-send-automatically}

Not in this workflow. Oliv AI's Meeting Assistant agent drafts the follow-up email from the transcript, and you review it, adjust it and send it yourself.

#### What if the draft gets something wrong? {#faq-draft-wrong}

Change it before you send it. If you aren't sure what was said, use the timestamps on the meeting's Action Items tab or find the moment in Transcripts on its Recording tab, then correct the draft to match.

## Further reading {#further-reading}

- [Working memory and external memory](https://www.nngroup.com/articles/working-memory-external-memory/): Nielsen Norman Group on why holding too much in your head leads to slower work and mistakes.
- [Email subject lines](https://www.nngroup.com/articles/email-subject-lines/): Nielsen Norman Group's advice on front-loading a subject line, written for newsletters.
- [HubSpot's default deal properties](https://knowledge.hubspot.com/properties/hubspots-default-deal-properties): how HubSpot defines close date and deal probability.
- [Set up and manage object pipelines](https://knowledge.hubspot.com/object-settings/set-up-and-customize-pipelines): how HubSpot uses stage probability to work out weighted amount.

## Related {#related}

- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): ask for a follow-up, or anything else on a deal.
- [Meeting Assistant agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/): briefs before and follow-ups after every deal meeting.
- [Sales call notes software](https://www.oliv.ai/blog/sales-call-notes): how call notes tools compare on structure and CRM sync.
- [Taking notes during sales calls](https://www.oliv.ai/blog/how-to-take-meeting-notes-during-sales-calls): what to capture as the call happens.
- [Perfecting the sales follow-up](https://www.oliv.ai/blog/sales-follow-up): what a strong follow-up does for the deal.
- [Plans and pricing](https://www.oliv.ai/pricing): how Oliv AI is priced.

*Updated 3 November 2026: added the ways a follow-up gets written, what to check before you send or approve, how to measure follow-up speed, the manual method and a worked example.*
