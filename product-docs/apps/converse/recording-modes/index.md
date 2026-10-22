# Recording modes: bot and botless

How Oliv AI decides whether to record a meeting botlessly through Zoom or Microsoft Teams or with a visible note taker, how to prepare your meetings for recording, and how it compares with other recorders.

- Applies to: Anyone whose meetings Oliv AI records, plus the admins who set recording up
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/

Oliv AI records your meetings in one of two ways, and it picks the way for you based on who organized the meeting. When someone from your company is the organizer, Oliv AI records botlessly, through [Zoom](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/) or Microsoft Teams itself. When someone outside your company is the organizer, a visible note taker joins the call, named after your company. This page explains both modes and how to prepare your meetings so they record.

## At a glance {#at-a-glance}

| | |
|---|---|
| **The two modes** | Botless recording through the meeting app, or a visible note taker |
| **Who decides** | Oliv AI, from who organized the meeting |
| **Your company organizes** | Botless: no Oliv participant on the call |
| **Someone outside organizes** | A note taker joins, shown with your company's name |
| **What attendees see** | The meeting app's own recording indicator, or the named note taker |
| **Needs** | A connected calendar, and botless recording enabled for your organization |
| **Platforms named** | Zoom and Microsoft Teams |
| **Phone calls** | A **Record call** toggle and a **Recording method** of **One-way** or **Two-way** in the Power Dialer |

## What recording modes are {#what-it-is}

A recording mode is how Oliv AI captures a meeting. When native or botless recording is enabled for your organization, Oliv AI chooses the method based on who organized the meeting. You don't pick a mode per call.

| | Botless recording | Note taker |
|---|---|---|
| **Used when** | You or someone from your company organized the meeting | Someone outside your company organized the meeting |
| **How it records** | Directly through the video conferencing platform | The note taker joins as a participant |
| **What attendees see** | The meeting app's recording indication, and no separate Oliv participant | A participant shown with your company's name |
| **Before it starts** | Nothing to admit | May need admitting from a waiting room or lobby |

Botless recording happens inside the meeting app, such as Zoom or Microsoft Teams. The note taker is Oliv AI's visible way of joining a call to take notes, so you can focus on the conversation.

Whichever mode records it, the meeting lands in **Activities › Meetings** with its duration, type, next step and AI summary.

<figure>

![Meetings list on the My meetings tab with a badge of 10, showing recorded meetings in a grid with Meeting title and date, Duration, a Meeting with dropdown such as Prospect or Customer, a colour-coded Next Step and the start of an AI Summary.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_239_activities-meetings_meetings-list_my-meetings-tab_grid-with-meeting-type-next-step-and-ai-summary-columns.webp)

<figcaption>Botless or note taker, every recorded meeting ends up in the same Meetings list, so the mode changes how a call is captured but never where you find it.</figcaption>
</figure>

### Recording phone calls {#phone-calls}

Phone calls placed from the Power Dialer in [Engage](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/engage/) have their own recording controls. Once a call connects, the contact card shows a **Record call** toggle and a **Recording method** choice of **One-way** or **Two-way**. Pause, mute and **End Call** sit beside them.

<figure>

![Power Dialer during a live call. Under the contact card, a Record call toggle is switched on and a Recording method row offers One-way or Two-way, with Two-way selected, above pause, mute and a red End Call button. The tailored call plan fills the left side.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/engage/oliv-ai_134_engage_power-dialer_in-call-controls_record-call-toggle-on-recording-method-one-way-two-way-pause-mute-and-end-call-beside-call-plan.webp)

<figcaption>For dialer calls the rep sets recording on the call itself, with the Record call toggle and a choice of recording method, rather than through the meeting organizer rule.</figcaption>
</figure>

## Why recording modes matter {#why-it-matters}

### What it's for {#what-its-for}

Recording modes let you capture every customer meeting while keeping the call itself clean. When you host, nothing extra sits in the participant list. When a customer hosts, attendees can see clearly who is recording.

### How it helps {#how-it-helps}

- **No bot on calls you host.** The meeting app records, so no Oliv participant appears.
- **No setting to remember.** The organizer decides the mode, so there's nothing to switch per call.
- **Clear when you're a guest.** On someone else's meeting, the note taker carries your company's name.
- **Recorded either way.** Whoever organized it, the meeting is captured.

### What happens without it {#without-it}

Without a choice of mode, every recorded call gets a bot in the participant list. Some customers ask for it to leave, and the call goes unrecorded. Others accept it but feel watched. The cost is gaps in the record of your most important accounts.

### Why buyers care {#why-buyers-care}

This matters to account managers and customer success teams, whose customers often set the tone on calls. It matters to revenue operations, who answer IT and security questions about recorders. It counts most with enterprise customers who have strict meeting policies.

## The Oliv AI approach to recording modes {#approach}

{/* 5P */}

Picture an account manager with a renewal review on the calendar next week. The customer's IT lead has asked, politely, that no meeting bot join their calls. The account manager still wants a recording, because an expansion conversation will follow. Notes from this call will shape that proposal.

The usual answer is to switch the recorder off and take notes by hand, or to ask the customer for an exception. Either way, something tends to get lost. It's either the record of the call or a little goodwill. Hand-written notes also miss the exact words a customer used about budget or scope.

What the customer objects to is an extra participant, not a record of the meeting. The host already controls how a meeting app records. So the real question is who sends the invite. If your company hosts, the meeting app can do the recording itself.

Oliv AI answers it from the invite. When the account manager organizes the meeting, Oliv AI records through Zoom or Microsoft Teams directly, with no Oliv participant on the call. When the customer organizes, the note taker joins visibly, named after the account manager's company. Nobody has to change a setting before the call.

Attendees on a botless call still see the meeting app's own recording indicator, so nobody is recorded without knowing it. How that organizer rule stacks up against other recorders is covered in How recording modes compare, below.

## Prepare your meetings for recording {#prepare}

Whichever mode applies, a few things need to be in place before Oliv AI can record.

1. **Connect your calendar.** Calendar integration is required for Oliv AI to work. Without it, the note taker can't take notes during your meetings.
2. **Connect your video platform.** For Microsoft Teams and Google Meet, no extra integration is needed: Oliv AI joins automatically once your calendar is connected. For Zoom, install the [Oliv AI Zoom app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/zoom/), as set out under Set up Zoom recording.
3. **Decide who sends the invite.** If a customer would rather not see a bot, send the meeting invite from your own calendar. Your company is then the organizer, and the call records botlessly.
4. **Plan for the lobby.** On meetings someone outside your company hosts, the note taker may wait in a waiting room or lobby. Ask the host to admit it, or recording can't begin.

## Turn on botless recording {#turn-on-botless}

Botless recording is enabled per organization. If it isn't set up for yours, reach out to Oliv AI Support and connect your video conferencing admin with them. They'll help enable it for your team.

## Set up Zoom recording {#zoom}

Oliv AI has two Zoom apps on the Zoom marketplace:

| App | What it does |
|---|---|
| **Oliv - Meeting bot** | Adds the note taker to your meetings, records with your consent, and surfaces the meeting details afterward |
| **Oliv.ai** (meeting app) | Adds a richer set of features: fewer steps for recording consent, and Oliv AI's view inside Zoom during the call to [update CRM fields](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) |

By default, Oliv AI asks the host's permission to record a Zoom meeting. Without that permission, Oliv AI can't summarize the meeting.

### Record Zoom meetings without the host {#zoom-admin}

A Zoom admin can grant permissions so that Zoom meetings are recorded even when the host isn't present.

1. Go to the Zoom meeting bot settings at web.oliv.ai/apps/zoom-meeting-bot.
2. Check the **Permissions** box. This grants the admin-level permission that lets Zoom meetings record automatically without the host.
3. Click **Allow** to enable the Shared Access Permission.
4. Let the Oliv AI team know. They finish the setup on their side.

## Stop the note taker joining a meeting {#manage-notetaker}

Oliv AI joins external calls automatically, but you can manage that from Oliv AI or from your Google or Outlook calendar. There are five ways to stop the note taker joining:

1. The Oliv AI Chrome extension or the Oliv AI Outlook add-in.
2. The **Meetings** page in Oliv AI, under **Activities**.
3. The remove link in your meeting preparation summary, by email or Slack.
4. The remove link in the Zoom chat.
5. Removing the note taker directly in Zoom.

## How recording modes work with other features {#works-with}

### Meeting prep and follow-up {#with-meeting-assistant}

Recordings feed what happens before and after your calls. [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) [drafts the follow-up](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) from the transcript once a recording is processed. It also sends the brief that helps you [prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) next time.

### Conversation capture {#with-converse}

[Converse](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/) captures online meetings, bot-free calls, phone calls and email the same way. In-person meetings are captured with Plaud, a wearable recorder that travels with your reps, and the rep decides when and what to record.

A recorded meeting opens with a **Recording** tab: the player with **Add Comment**, **Clip** and **Share**, a speaker **Timeline** with talk time and engagement, and **Chapters**, **Transcripts** and **Comments**. The [meeting details page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) covers each tab.

<figure>

![Meeting details drawer on the Recording tab: a video player with Add Comment, Clip and Share buttons, a Timeline grouping speakers by company with Talk time and Engagement, and a Chapters list with Meeting Purpose, Action Items, Next Steps and Feedback Request and their timestamps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_243_activities-meetings_meeting-details-drawer_recording-tab_blank-player-add-comment-clip-share-timeline-and-chapters.webp)

<figcaption>This is what a recording becomes once it is processed: chapters, a transcript, comments and per-speaker talk time, ready to clip or share.</figcaption>
</figure>

A recorded phone call gets an audio player instead, with a **Timeline** of talk time per speaker, **Chapters**, **Add Comment** and a timestamped **Transcript**.

<figure>

![Call details drawer on the Recording tab for an outbound call marked Connected. An audio waveform player with play, time, scrubber and volume sits above Timeline and Chapters sub-tabs, Add Comment, and two speaker rows with Talk time and Engagement, beside a speaker-labelled Transcript.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-calls/oliv-ai_250_activities-calls_call-details-drawer_recording-tab_audio-waveform-player-talk-time-timeline-and-transcript.webp)

<figcaption>A recorded phone call is replayed the same way as a meeting, with the transcript beside an audio player, so calls are as easy to review as video meetings.</figcaption>
</figure>

### Inside Zoom {#with-zoom-app}

With the Oliv.ai meeting app, you can open Oliv AI inside Zoom during the call. Update deal data in place and see the moments you highlighted through Oliv AI during the meeting. See [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/) for the full list of connections.

### Clips {#with-clips}

Once a recording is processed, [Oliv AI's Content Curator agent](https://www.oliv.ai/agents/content-curator) can [clip the moments your team cares about](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) and post them to your team's channel.

### Your revenue team's agents {#with-agents}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) draws on meeting data as the primary source of her live context. [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) tells managers which meetings happened and their key outcomes in its end-of-day summary.

## Who uses recording modes, and how {#who-uses-it}

These are typical patterns, shown to illustrate how teams use the two modes.

### Account management {#account-management}

An [account manager](https://www.oliv.ai/account-management) sends renewal and QBR invites from their own calendar. Calls with customers who dislike bots record botlessly, and the full account history stays intact.

### Account executives {#account-executives}

An account executive joins a prospect's own meeting link for a demo. The note taker asks to be admitted from the lobby with the AE's company name, and the follow-up still arrives after the call. It's part of how AEs [run their deals in Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Customer success {#customer-success}

A [customer success](https://www.oliv.ai/customer-success) manager runs onboarding calls on Microsoft Teams. Because the CSM organizes them, no Oliv participant appears, and the customer sees only Teams' own recording indicator.

### Revenue operations {#revops}

A [revenue operations](https://www.oliv.ai/revops) lead works with the Zoom admin to grant admin-level permissions. Meetings then record even when the host is late or absent. RevOps also decides which [agent actions run without asking](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).

## How recording modes compare {#compare}

Oliv AI switches between botless recording and a visible note taker by itself, based on who organized the meeting. Calls you host record through Zoom or Microsoft Teams with no bot, and calls a customer hosts get a note taker with your company's name. Oliv AI is the only platform in this table that does all three.

Recording modes, from each platform's public documentation:

| Platform | Bot-free recording in Zoom and Teams | Recording method follows the meeting organizer | Note taker shows your company's name |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([native recording, Zoom only](https://help.gong.io/docs/faqs-for-web-conferencing)) | Set by company setup ([two methods by setup](https://help.gong.io/docs/how-calls-are-recorded)) | Not in docs |
| **Avoma** | Partly ([Teams needs a cloud recording license](https://help.avoma.com/admins-enable-microsoft-cloud-recording-in-avoma)) | Chosen during setup ([pick cloud or bot](https://help.avoma.com/avoma-integration-with-microsoft-cloud-recording)) | Yes ([custom bot name](https://help.avoma.com/configure-avoma-bot-settings)) |
| **Fathom** | Partly ([Teams still uses the notetaker](https://help.fathom.video/en/articles/13114369)) | User preference, admin can block ([org-wide bot override](https://help.fathom.video/en/articles/6220097)) | Yes ([custom notetaker name](https://help.fathom.video/en/articles/3239681)) |
| **Fireflies.ai** | Partly ([Google Meet SDK and desktop app](https://guide.fireflies.ai/articles/3309351579-integrate-google-meet-sdk-with-fireflies-for-bot-free-meeting-recording)) | Your choice per meeting ([bot or Take Notes](https://guide.fireflies.ai/articles/7066927951-bot-vs-no-bot-which-capture-am-i-using)) | Partly ([custom name on paid plans](https://guide.fireflies.ai/articles/8059419014-how-to-change-the-name-of-the-fireflies-notetaker-bot)) |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for recording modes {#compare-stronger}

- **Bot-free on Teams as well as Zoom.** Oliv AI records botlessly in both Zoom and Microsoft Teams when your company organizes. [Fathom records Microsoft Teams meetings by having its notetaker join the call](https://help.fathom.video/en/articles/13114369).
- **Nothing to choose per call.** Oliv AI reads the organizer and picks the mode for you. [Avoma has you choose between cloud recording and its bot during setup](https://help.avoma.com/avoma-integration-with-microsoft-cloud-recording). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Customer-hosted calls covered.** When someone outside your company organizes, Oliv AI joins with a visible note taker. [Gong lists calls hosted by someone outside your company among those not picked up automatically](https://help.gong.io/docs/how-calls-are-recorded). See [Gong vs Oliv AI](https://www.oliv.ai/blog/gong-vs-oliv).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Botless needs enabling.** Botless recording works once it's enabled for your organization, with help from Oliv AI Support and your video conferencing admin.
- **The organizer decides, not you.** You can't force botless recording on a meeting someone outside your company organized. Send the invite yourself if it matters.
- **Lobbies can block the note taker.** If an external meeting has a waiting room, someone has to admit the note taker before recording begins.
- **Zoom asks the host first.** By default, Oliv AI needs the host's permission to record a Zoom meeting. Admin-level permissions remove that step, and a Zoom admin has to grant them.
- **No calendar, no recording.** Oliv AI relies on your calendar to know which meetings to join.
- **Attendees are always told.** Botless calls show the meeting app's recording indication, so recording is never hidden.

## Common questions {#common-questions}

#### How does Oliv AI choose between bot and botless? {#faq-how-it-chooses}

By who organized the meeting. If you or someone from your company organized it, Oliv AI records botlessly. If someone outside your company did, the note taker joins.

#### Will attendees know the meeting is being recorded? {#faq-attendees-know}

Yes. On a botless call they see the meeting app's own recording indication. On other calls they see the note taker, shown with your company's name.

#### Which meeting apps support botless recording? {#faq-platforms}

Zoom and Microsoft Teams are both supported. Recording happens inside the meeting app itself, with no separate Oliv participant on the call.

#### My customer doesn't want a bot. What should I do? {#faq-no-bot}

Send the meeting invite from your own calendar. With your company as the organizer, Oliv AI records botlessly and no note taker joins.

#### Why didn't the note taker start recording? {#faq-lobby}

If the meeting had a waiting room or lobby, the note taker may have needed admitting first. Ask the host to let it in.

#### How do I turn on botless recording? {#faq-turn-on}

Reach out to Oliv AI Support and connect your video conferencing admin with them. They'll help enable botless recording for your team.

#### Do I need an integration for Teams or Google Meet? {#faq-teams-meet}

No. Once your calendar is connected, Oliv AI joins Microsoft Teams and Google Meet meetings automatically. Zoom uses the Oliv AI Zoom app.

#### Can Zoom meetings record when the host isn't there? {#faq-no-host}

Yes, once a Zoom admin grants admin-level permissions through the Zoom meeting bot settings and tells the Oliv AI team.

#### How do I stop the note taker joining one meeting? {#faq-remove}

Use the Chrome extension or Outlook add-in, the **Meetings** page under **Activities**, the remove link in your prep summary or the Zoom chat, or remove it in Zoom.

#### Can I record phone calls? {#faq-phone}

Yes. In the Power Dialer, turn on **Record call** and pick a **Recording method** of **One-way** or **Two-way**.

#### Can Oliv AI capture in-person meetings? {#faq-in-person}

Yes, through Plaud, a wearable recorder that travels with your reps. The rep decides when and what to record.

## Related {#related}

- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the brief that arrives before your recorded calls.
- [Converse](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/): every conversation, captured the same way.
- [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/): calendars, video platforms and chat tools.
- [Meeting recorder picks](https://www.oliv.ai/blog/meeting-recorder-picks-for-productivity): how meeting recorders differ.
- [Sales call analytics software](https://www.oliv.ai/blog/sales-call-analytics): recording, transcription and coaching compared.
- [Meeting transcription software](https://www.oliv.ai/blog/meeting-transcription-software): accuracy and speaker detection.
- [Plans and pricing](https://www.oliv.ai/pricing): how Oliv AI is priced.
