# Zoom

How Oliv AI records Zoom calls, picks between botless recording and a visible note taker, keeps recording when the host is absent, and puts CRM fields inside Zoom.

- Applies to: Sales development, account executives, customer success and Zoom admins
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/

Oliv AI's Zoom integration records your Zoom calls and turns them into summaries, follow-ups and deal updates. When your company hosts the call, Oliv can record botlessly through Zoom itself. When someone else hosts, a note taker joins under your company's name. A separate Zoom app puts Oliv inside the meeting window, so you can [update CRM fields](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) while you talk.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Records Zoom calls and feeds them to Oliv AI's agents |
| **Who it's for** | SDRs, account executives, customer success managers and Zoom admins |
| **Two Zoom apps** | **Oliv - Meeting bot** for recording, **Oliv.ai** for use during the call |
| **Recording modes** | Botless on calls your company hosts, a visible note taker on calls others host |
| **Needs** | A connected calendar, plus a Zoom admin for host-free recording |
| **After the call** | Summary and next steps, a follow-up draft and a shareable recording |

## What the Zoom integration is {#what-it-is}

The Zoom integration connects your Zoom account to Oliv AI. It is how [Oliv AI's Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) captures Zoom calls: it joins Zoom, Meet and Teams automatically and labels every speaker. Once a call ends, the summary and next steps are ready, and a follow-up draft follows within minutes. Every recorded Zoom call then sits under **Activities** › **Meetings**.

<figure>

![The Meetings list under Activities with My meetings selected and Team meetings beside it, a Search box and Group, Fields, Sort and Filter controls, and rows showing each meeting's duration, Meeting with type, Next Step and AI Summary.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_239_activities-meetings_meetings-list_my-meetings-tab_grid-with-meeting-type-next-step-and-ai-summary-columns.webp)

<figcaption>Where your recorded Zoom calls end up: one list of captured meetings, each with its duration, who it was with, the agreed next step and a short AI summary.</figcaption>
</figure>

### The two Zoom apps {#two-apps}

Oliv offers two apps on the Zoom marketplace.

- **Oliv - Meeting bot.** Adds a meeting bot that records your meetings with your consent. After the meeting, it analyzes the call and surfaces the meeting details for you.
- **Oliv.ai.** The richer in-meeting app. It has the bot join the call, cuts the steps needed for recording consent, and shows Oliv inside Zoom so you can edit CRM fields directly.

### How Oliv AI picks a recording mode {#recording-modes}

When botless recording is turned on for your organization, [Oliv chooses the method by who organized the meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/).

- **Your company organized it.** Oliv records directly through Zoom. No Oliv participant joins, though everyone still sees Zoom's own recording indicator.
- **Someone outside your company organized it.** The note taker joins as a visible participant, shown with your company's name. If the meeting has a waiting room, someone may need to admit it.

## Why the Zoom integration matters {#why-it-matters}

### What it's for {#what-its-for}

The Zoom integration is for teams that run their customer calls on Zoom. It makes sure each call is recorded and handed to Oliv AI's agents. The agents then prepare the next call and handle the follow-up.

### How it helps {#how-it-helps}

- **Calls get recorded without a reminder.** Once you log in, Oliv starts joining and summarizing your Zoom calls.
- **Hosted calls stay clean.** On calls your company organizes, no extra participant appears in the room.
- **The host can be late.** With a Zoom admin's permission, recording goes ahead even if the host never joins.
- **Deal updates happen in the meeting.** The in-meeting app lets you edit deal data during the call.

### What happens without it {#without-it}

Calls that are never recorded leave no transcript behind. The follow-up rests on what the rep wrote down, and the CRM gets whatever the rep remembers to type. Agents that prepare the next meeting have nothing to read from the last one.

### Why buyers care {#why-buyers-care}

Sales development leaders care first, because first calls are where qualification starts and handoffs begin. Account executives care on every active deal. Zoom admins care at rollout, since they grant the permissions that decide how calls get recorded.

## The Oliv AI approach to the Zoom integration {#approach}

{/* 5P */}

Picture a sales development team of ten that books every first call on Zoom. Some calls sit on an SDR's own Zoom account. Others run on the prospect's link. Often an account executive joins halfway, and now and then the SDR who booked the call is out sick.

The usual habit is to have each SDR press record, or invite a recorder, at the start of every call. That tends to break on busy days. A call hosted by the prospect may never get recorded, and a call whose host is missing can go unrecorded too. The handoff to the account executive then runs on a few typed notes.

Nothing about the call itself has changed. It is still a Zoom meeting on a calendar, with a known organizer. So the recording can follow the calendar and the organizer, instead of depending on someone remembering a button.

Oliv AI does this through Zoom. It records calls your company organizes botlessly through Zoom, and joins calls others organize as a visible note taker under your company's name. Once a Zoom admin grants shared access, Oliv records even when the host isn't present. The recording then feeds the agents that brief the account executive.

You can see what each Zoom app is allowed to do. Every permission it asks Zoom for is listed in plain words in Permissions Zoom asks for. The features they enable are covered in How Oliv AI compares for Zoom meeting recording for sales, below.

## Set up the Zoom integration {#set-up}

1. **Connect your calendar.** Calendar integration is required for Oliv to work. Without it, Oliv can't take notes during your meetings.
2. **Log in to Oliv.** Sign in at web.oliv.ai and set up your account. Oliv starts joining and summarizing your Zoom calls.
3. **Install the Oliv.ai Zoom app.** Open web.oliv.ai/apps/zoom-meeting-bot. That's all the in-meeting app needs.
4. **Choose auto-record if you host.** By default, Oliv asks the host for permission to record. To auto-record meetings you host, use the same page.

### Record when the host isn't on the call {#admin-recording}

A Zoom admin has to complete these steps, because they grant the needed permissions.

1. **Open the meeting bot settings.** Go to web.oliv.ai/apps/zoom-meeting-bot.
2. **Grant admin permissions.** Check the **Permissions** box on the page.
3. **Enable shared access.** Click **Allow** to turn on the Shared Access Permission.
4. **Tell the Oliv team.** They finish the remaining setup on the backend.

### Turn on botless recording {#botless-setup}

[Botless recording is set up per organization](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/). If it isn't on for your team yet, contact Oliv Support and connect your Zoom admin with them. They'll help enable it.

## Use Oliv AI during a Zoom call {#in-meeting}

With the **Oliv.ai** app installed, you can open Oliv directly in the Zoom window. From there, you can update the deal data for the account while you talk. You can also see the important moments you highlighted through Oliv during the meeting.

Once the call is done, the recording shows up in the Oliv app, where you can share it. The meeting's **Recording** tab has the player, a speaker **Timeline** with talk time and engagement, and **Chapters**, **Transcripts** and **Comments**, with **Clip** and **Share** under the player.

<figure>

![A meeting details drawer on the Recording tab, with a video player, Add Comment, Clip and Share buttons, a speaker Timeline showing talk time and engagement per person, and Chapters, Transcripts and Comments sub-tabs listing chapter cards with timestamps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_243_activities-meetings_meeting-details-drawer_recording-tab_blank-player-add-comment-clip-share-timeline-and-chapters.webp)

<figcaption>What a recorded Zoom call becomes in Oliv AI: the recording split into chapters and a transcript, with speaker stats and controls to clip or share a moment.</figcaption>
</figure>

CRM changes that come out of the call are listed on the meeting's **CRM Updates** tab. Completed writes carry a check, and a stage move waits as a **Pending Update** until you press **Update Deal**.

<figure>

![A meeting details drawer on the CRM Updates tab, a timeline with Account Updated, Pending Update: Move to Proposal with an Update Deal button, Opportunity Updated: BANT Scorecard and Contact Created entries, each with a View link.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_246_activities-meetings_meeting-details-drawer_crm-updates-tab_account-deal-bant-and-contact-updates-with-pending-stage-move.webp)

<figcaption>Alongside the fields you edit inside Zoom, this tab records every CRM change made from the call and holds a stage move until someone confirms it.</figcaption>
</figure>

The app also matches the Zoom meeting you're in to its calendar event, so the call lands on the right meeting.

## Manage or stop the note taker {#manage-note-taker}

Oliv joins external calls automatically. You can stop it from joining a call in five ways:

1. The Oliv AI Chrome extension or the Oliv AI Outlook add-in.
2. The **Meetings** page in Oliv AI, under **Activities**.
3. The link to remove it in the meeting preparation summary, by email or in Slack.
4. The link to remove it in the Zoom chat.
5. Removing it directly from Zoom.

To remove the whole Zoom integration, send Oliv a message through Intercom in the Oliv app.

## Permissions Zoom asks for {#permissions}

| App | Zoom permission | What it allows |
|---|---|---|
| **Oliv - Meeting bot** | user_zak:read | The Oliv bot joins the calls you want it to |
| **Oliv.ai** | meeting:read | Reads the meeting you're in and matches it to its calendar event |
| **Oliv.ai** | user:read | Keeps track of the meeting recordings you own |
| **Oliv.ai** | meeting_token:read:local_recording | Shows you the recording in Oliv after the call, ready to share |
| **Oliv.ai** | zoomapp:inmeeting | Opens the Oliv app directly in the Zoom window |

## Find a Zoom recording later {#find-recordings}

If Oliv sends you a [Slack message](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) about a meeting, click **Open Meeting** in it to jump to the call in Oliv. You can also go to **Activities** › [**Meetings**](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) and search for it, on **My meetings** or **Team meetings**.

To share part of a call, open its [**Recording** tab](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/), find the moment in **Chapters** or **Transcripts**, and press **Clip**. If you need ideas for what to capture, read about [taking notes during sales calls](https://www.oliv.ai/blog/how-to-take-meeting-notes-during-sales-calls).

## How Zoom works with Oliv AI's agents {#works-with}

### Meeting Assistant {#with-meeting-assistant}

[Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) runs on recordings and transcripts from the Oliv Notetaker. Thirty minutes before each call on an active deal, it sends a brief. After the call, it [drafts the follow-up email](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) and flags CRM field updates. See how that plays out when you [prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Researcher {#with-researcher}

Oliv AI's Researcher agent handles first calls with people you haven't met. Thirty minutes before the meeting, it sends three bullets on the company and the person, plus an icebreaker. Researcher is packaged within [the Prospector bundle](https://www.oliv.ai/agents/prospector).

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) answers questions about deals and accounts. Recorded Zoom calls are part of the context she reads from.

### Deal Driver and Coach {#with-deal-driver-coach}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) bundles Meeting Assistant for reps, so each recorded call feeds the manager's view. Oliv AI's Coach agent lists Zoom as one of the call sources it can [score for coaching](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/). Each scored call gets a **Coaching** tab with a grade, skill scores out of 5 and a **MEDDPICC Scorecard**.

<figure>

![A meeting details drawer on the Coaching tab, with a left list of Summary, Meeting Stats and skill groups scored out of 5, a Summary card with Improvement Required and Strength notes and a grade gauge, and a MEDDPICC Scorecard radar chart.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_244_activities-meetings_meeting-details-drawer_coaching-tab_b-plus-summary-skill-scores-and-meddpicc-radar-chart.webp)

<figcaption>A recorded Zoom call scored by Oliv AI's Coach agent: an overall grade, a score per skill and qualification coverage on one radar, ready for the next one-to-one.</figcaption>
</figure>

### Content Curator {#with-content-curator}

Oliv AI's Content Curator agent needs the Oliv Notetaker to be recording, because it [clips moments from those calls](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) for enablement.

## Who uses the Zoom integration, and how {#who-uses-it}

### Sales development {#sales-development}

SDRs book first calls on Zoom and leave the recording to Oliv. The account executive who takes the deal next gets the call, not a summary typed from memory. See how Oliv AI supports [sales development teams](https://www.oliv.ai/sales-development).

### Account executives {#account-executives}

Account executives use the in-meeting app to update deal fields while the customer is still talking. After the call, they review the drafted follow-up. The full day is laid out in [running deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Customer success and account management {#customer-success}

CSMs record renewal and check-in calls the same way. Those recordings feed the agents that watch account health. More on Oliv AI for [customer success](https://www.oliv.ai/customer-success) and [account management](https://www.oliv.ai/account-management).

### Zoom admins and revenue operations {#zoom-admins}

A Zoom admin grants the shared access that lets Oliv record when the host is absent. RevOps can review what each app may do in the permissions table above. See Oliv AI for [revenue operations](https://www.oliv.ai/revops).

## How Oliv AI compares for Zoom meeting recording for sales {#compare}

Oliv AI records Zoom calls your company hosts without a bot, and keeps recording when the host is absent once a Zoom admin grants access. Its in-meeting app also lets you edit CRM fields without leaving Zoom. Oliv AI is the only platform in this table that does all three.

Zoom recording features, from each platform's public documentation:

| Platform | Botless recording on Zoom | Records with the host absent | CRM fields edited inside Zoom |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Yes ([native Zoom recording](https://help.gong.io/docs/set-up-native-zoom-recording)) | Yes ([bot records without the host](https://help.gong.io/docs/set-up-zoom-recording-with-the-gong-bot)) | Partly ([notes and moments in the app](https://help.gong.io/docs/use-the-gong-app-for-zoom)) |
| **Avoma** | Yes ([Zoom Cloud Recording option](https://help.avoma.com/avoma-integration-with-zoom)) | Partly ([joins on behalf of an attendee](https://help.avoma.com/connect-zoom-for-recording)) | Partly ([notes app inside Zoom](https://help.avoma.com/avoma-for-zoom-apps)) |
| **Fathom** | Yes ([botless Zoom recording](https://help.fathom.video/en/articles/2462209)) | Not in docs | Not in docs |
| **Fireflies** | Yes ([capture without a bot](https://guide.fireflies.ai/articles/1208704416-getting-started-with-the-fireflies-desktop-app)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for Zoom meeting recording for sales {#compare-stronger}

- **CRM fields, not just notes, inside Zoom.** The Oliv.ai Zoom app shows Oliv in the meeting so you can edit CRM fields directly. Gong's app for Zoom is for [taking notes, marking important moments and following the conversation](https://help.gong.io/docs/use-the-gong-app-for-zoom). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **Recording that doesn't wait for a person.** After a Zoom admin grants shared access, Oliv records even when the host is not present. Avoma Assistant [joins on behalf of someone from your organization who is in the meeting](https://help.avoma.com/connect-zoom-for-recording). Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Calls hosted by others still get recorded.** When someone outside your company organizes the call, Oliv joins as a visible note taker under your company's name. Gong notes that under its organizer-only rule, [a call organized by someone outside your team may not record automatically](https://help.gong.io/docs/troubleshooting-unrecorded-calls). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Consent comes first.** By default, Oliv asks the host for permission to record. Without it, Oliv can't summarize the meeting.
- **Waiting rooms need a click.** On calls hosted by someone else, the note taker may need to be admitted from the waiting room.
- **Botless recording needs setup.** Oliv Support enables it with your Zoom admin. Until then, the note taker joins as a visible participant.
- **Host-free recording needs a Zoom admin.** Only a Zoom admin can grant shared access, and the Oliv team then finishes the setup.
- **Your calendar must be connected.** Without calendar integration, Oliv can't take notes in your meetings.
- **Removal goes through Oliv.** To remove the integration, message Oliv through Intercom in the Oliv app.

## Common questions {#common-questions}

#### Do I need both Zoom apps? {#faq-both-apps}

No. **Oliv - Meeting bot** covers recording and summaries. Add the **Oliv.ai** app if you want Oliv inside the Zoom window during calls, where you can edit CRM fields.

#### Will the prospect see an Oliv participant on the call? {#faq-visible-bot}

It depends on who organized the call. On calls your company organizes, with botless recording on, no Oliv participant appears. On calls others organize, the note taker joins under your company's name.

#### Can Oliv record if the host never joins? {#faq-host-absent}

Yes, once a Zoom admin grants shared access at web.oliv.ai/apps/zoom-meeting-bot and tells the Oliv team. Recording then goes ahead regardless of whether the host is there.

#### Does Oliv record without asking? {#faq-consent}

By default, Oliv asks the host for permission to record. If you're the host, you can switch to auto-record from the meeting bot page.

#### Why didn't my call get recorded? {#faq-not-recorded}

Check that your calendar is connected and that the host gave permission to record. If someone else hosted, the note taker may have been waiting in the lobby for someone to admit it.

#### How do I stop the note taker joining one call? {#faq-stop-one-call}

Use the link in the Zoom chat, the link in your meeting preparation summary, or the **Meetings** page under **Activities**. You can also remove it directly in Zoom.

#### What can I do inside Zoom during a call? {#faq-in-meeting}

With the **Oliv.ai** app, you can open Oliv in the Zoom window, update deal data and see the moments you highlighted through Oliv.

#### Where do I find a recording after the call? {#faq-find-recording}

Click **Open Meeting** in the Slack message about the call, or search **Activities** › **Meetings**. On the call's **Recording** tab, **Clip** cuts a moment and **Share** sends the meeting.

#### Which Zoom permissions does Oliv ask for? {#faq-permissions}

The meeting bot asks for user_zak:read to join calls. The **Oliv.ai** app asks for meeting:read, user:read, meeting_token:read:local_recording and zoomapp:inmeeting. Each one is explained in the permissions table.

#### Does it work for Microsoft Teams and Google Meet too? {#faq-other-platforms}

Yes. For Teams and Google Meet, no separate integration is needed. Oliv joins those meetings automatically once your calendar is connected.

#### How do I remove the Zoom integration? {#faq-remove}

Send Oliv a message through Intercom in the Oliv app, and the team removes it for you.

## Related {#related}

- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): what the brief before a recorded call contains.
- [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): recorded calls in a full selling day.
- [Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): the manager's view built on each call.
- [Olivia agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): ask questions across your recorded calls.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): what a custom agent can do with your apps.
- [Meeting Assistant agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/): the agent that preps and follows up each deal call.
- [Converse, Oliv AI's capture app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/): how calls, phone and in-person meetings are captured.
- [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/): every tool Oliv AI connects to.
- [Meeting transcription software compared](https://www.oliv.ai/blog/meeting-transcription-software): how transcription accuracy differs.
- [Meeting recorders for productivity](https://www.oliv.ai/blog/meeting-recorder-picks-for-productivity): choosing a recorder for your team.
- [Oliv AI pricing](https://www.oliv.ai/pricing): plans and what each includes.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
