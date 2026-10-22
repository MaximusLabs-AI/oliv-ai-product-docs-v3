# Clip library

How Oliv AI builds a clip library from your recorded calls, where libraries live in the Enable app, what each clip page carries, how to define the moments it looks for, and how it compares with other call clipping tools.

- Applies to: Enablement, sales managers and anyone who learns from recorded calls
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/

Oliv AI turns your recorded calls into a clip library without anyone scrubbing through recordings. You describe the moments you want, such as a strong answer to a pricing objection. Oliv AI's Content Curator agent then reviews every completed meeting, clips the matching moments, files each clip in its library and posts it to your team's Slack channel.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it builds** | Libraries of short clips from your recorded calls |
| **Who builds it** | Oliv AI's Content Curator agent, or you, with **Clip** on a recording |
| **When it runs** | When a meeting is completed |
| **What you set** | The moments to look for, the library for each, and the channel to post to |
| **Each clip carries** | Why it was captured, who was on the call, the timestamp, the call date and a link to the full recording |
| **Where clips land** | The **Library** tab of the **Enable** app, plus a Slack message with a direct link |
| **Sharing** | **Public** or **Private** libraries, and **Share** on any single clip |

## What the clip library is {#what-it-is}

The clip library is where the best moments from your calls live once they've been cut out of the full recording. Libraries are reached through the **Library** tab of the Enable app, which carries the clip library alongside the people tabs. Any clip can also be opened on its own, through a shared view built for people outside your workspace.

<figure>

![Enable app on the Library tab with the All Libraries view selected and a count badge of 10. A Views tree, a search box, Group, Fields, Sort, Filter and a New Library button frame a table of Library Name, Description and an Access Type dropdown set to Public or Private.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/enable/oliv-ai_172_enable_library-tab_all-libraries-view_clip-library-list-name-description-access-type-public-private-with-views-tree-and-new-library.webp)

<figcaption>The Library tab is the home of every clip library: each one has a name, a description of the moments it collects and an access type you can change from the row.</figcaption>
</figure>

[Oliv AI's Content Curator agent](https://www.oliv.ai/agents/content-curator) does the clipping. It runs once a meeting is completed and its recording is ready for analysis. It reads the meeting context, who spoke and how the conversation flowed, then isolates the segments that match the moments your team has defined. Each clip is cut to be concise and complete rather than to a fixed length.

### Library views and access {#library-views}

Four views sit above the table: **Favorites**, **My Library**, **AI Library** and **All Libraries**, each with a count. **My Library** shows the libraries you own, and **AI Library** shows the libraries the AI builds. A **Views** tree on the left holds the same views, with a search box and a new-folder button.

<figure>

![Enable Library tab with the AI Library view selected and a count badge of 3. The Views tree shows Favorites expanded with AI Library highlighted, and the table lists three libraries with truncated descriptions and Public or Private access type dropdowns.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/enable/oliv-ai_181_enable_library-tab_ai-library-view-selected-count-3-master-objection-competitive-landscape-best-of-product-pitches-public-private.webp)

<figcaption>Switch to AI Library to see the libraries the agent fills for you, separate from the ones you curate by hand under My Library.</figcaption>
</figure>

Each row's **Access Type** dropdown sets a library to **Public**, with a globe icon, or **Private**, with a lock. Use **+ New Library** to start one, and **Search**, **Group**, **Fields**, **Sort** and **Filter** to find one.

### What's attached to every clip {#clip-details}

- **Why it was kept.** A short explanation of why the agent captured that moment.
- **Who was there.** The names of the people on the call.
- **Where it sits.** The timestamp and the call date.
- **The full context.** A link back to the source recording.

### Watch a clip {#clip-page}

Opening a library takes you to **Clip Libraries**. The library's clips are listed on the left, each named by account and topic, with a **Search library** box and a pencil to edit the library. The selected clip fills the centre: its account, date and length, a **Customers** dropdown, the attendees and **Ask AI**.

<figure>

![Clip Libraries page with a library's clip list and Search library box on the left. The centre shows a procurement call clip with its account chip, date, length, Customers dropdown, attendees, Ask AI, a video area, Add Comment and Share, and speaker cards with Talk time and Engagement.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/clip-libraries/oliv-ai_182_clip-libraries_master-objection-library_clip-details_hooli-procurement-call-video-player-attendees-talk-time-engagement-transcript-ask-ai.webp)

<figcaption>A clip opens with everything a rep needs to learn from it: the video, who spoke and how much, and a transcript you can search, filter by speaker or download.</figcaption>
</figure>

Under the video sit **Add Comment** and **Share**, then speaker cards with each person's **Talk time** and **Engagement**. The transcript on the right has a search box, a download button and a tab per speaker, so you can read only the buyer's turns.

### Moments and libraries {#moments-and-libraries}

A moment is a description of what to capture. Each moment routes to one library and one Slack channel. Three moment types come ready: **Product Requests**, **Competitor Mentions** and **Objections**. You can add your own, for example discovery wins, customer pain or strong closes.

<figure>

![Content Curator agent page on the Overview tab, with tabs for Overview, Instructions, Moments, Tools and Runs and a Run Agent button. Cards show its goal, the trigger When a meeting is completed, five tool chips and three moments: Product Requests, Competitor Mentions and Objections.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_100_agent-detail_content-curator_overview-tab_goal-meeting-completed-trigger-five-tools-three-moment-types.webp)

<figcaption>The agent's Overview shows what fills your clip library: it runs when a meeting is completed and looks for the three moment types listed at the bottom.</figcaption>
</figure>

## Why the clip library matters {#why-it-matters}

### What it's for {#what-its-for}

The clip library gives your team real examples of what good sounds like, taken from your own calls. New reps hear how a pricing objection was handled. Managers coach from a moment instead of a memory.

### How it helps {#how-it-helps}

- **No manual clipping.** Matching moments are found and cut from every completed meeting.
- **Always current.** The library grows as calls come in, not once a quarter.
- **Context on every clip.** Each one says why it was kept and links to the full call.
- **Clips reach people.** A Slack message with a direct link goes to the channel you chose.

### What happens without it {#without-it}

Without a clip library, your best answers stay buried in hours of recordings that nobody revisits. New reps learn to handle objections from scratch, each in their own way. The strongest responses leave with the reps who gave them.

### Why buyers care {#why-buyers-care}

This matters most to enablement leads, who own the library and decide what goes in it. It matters to sales managers who coach from real calls. It counts most when new hires are ramping, because examples are what they ask for first.

## The Oliv AI approach to the clip library {#approach}

{/* 5P */}

Picture an enablement manager with six new reps starting in two weeks. She wants each of them to hear how experienced reps handle the objections that come up most. Pricing pushback and security questions top her list.

The usual route is to ask managers for good calls, then scrub the recordings and trim clips by hand. That can take days, and the folder tends to stop growing once the cohort ramps. Next quarter, the examples are already a few months old.

Strong objection handling keeps happening on calls every week. The hard part isn't finding one great clip. It's catching the new ones as they happen and getting them in front of the reps who need them.

Oliv AI does that catching with its Content Curator agent. The manager describes the moment once, in plain words: a rep answers a pricing or security concern and keeps the deal moving. From then on, every completed meeting is reviewed, matching moments are clipped, and each clip goes into the objection library and the onboarding channel.

Every clip arrives with a short note on why it was captured. It also carries the people on the call, the timestamp, the call date and a link to the full recording. How that compares with other call clipping tools is covered in How the clip library compares, below.

## Set up a moment {#set-up}

A moment tells Oliv AI's Content Curator agent what to clip and where to send it. An enablement or sales manager usually sets up the first ones.

1. **Make sure recordings are flowing.** The agent works on recordings from the Oliv AI notetaker, so [meetings need to be recorded](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) first. [Connect Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) too, so clips have somewhere to go.
2. **Open the agent and its Moments tab.** The **Moments** tab is unique to Content Curator. It lists each moment type, its **Clip Library** and its channel.
3. **Name the moment.** Use **Moment name**, for example "Pricing objection handled".
4. **Describe what to capture.** Use **Define the moment**. Be specific: the agent uses your description to understand intent, not keywords.
5. **Choose the library.** Pick one in **Select Library**, or type a **New Library Name** to start one.
6. **Choose the channel.** Set the **Channel Name** that each new clip is posted to.

The public walkthrough shows the same flow in four steps: **Configure**, **Output**, **Preview results** and **Finish**. Once saved, the moment runs every time a meeting is completed, with [no manual trigger](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/triggers/). **Run Agent** starts a run by hand if you want one.

### Refine what it captures {#refine}

If a clip doesn't belong, remove it and the agent learns from that feedback. You can also sharpen a moment's description at any time to tighten what it looks for.

### Search before you clip {#search-and-clip}

You don't have to wait for the agent. In [Converse](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/), search for the exact objection, competitor mention or pricing concern. Then open the meeting's **Recording** tab and press **Clip** to cut that moment yourself.

<figure>

![Meeting details drawer on the Recording tab, with a video player and three buttons under it: Add Comment, Clip with a scissors icon, and Share. A speaker Timeline with Talk time and Engagement sits below, and a Chapters list with timestamps sits on the right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_243_activities-meetings_meeting-details-drawer_recording-tab_blank-player-add-comment-clip-share-timeline-and-chapters.webp)

<figcaption>The Clip button on a meeting's Recording tab is the manual way into the library, for a moment you found yourself before the agent's next run.</figcaption>
</figure>

Find the moment from **Chapters** or **Transcripts** first. The [meeting details page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) covers the rest of the Recording tab.

## How the clip library works with other features {#works-with}

### Coaching {#with-coach}

[Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) surfaces clips from the library for coaching sessions. When a rep keeps struggling with the same objection, the manager can open the 1:1 with real examples of it handled well. Managers already get a per-rep 1:1 report from [Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/), so clips and pipeline context meet in the same conversation.

### Meeting prep {#with-meeting-prep}

When a competitor comes up in a live opportunity, [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) pulls three recent clips from your competitive intel library before the next meeting. Reps see how colleagues handled that exact comparison. That's part of how Oliv AI helps you [prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Slack notifications {#with-chat}

Each new clip is posted to the Slack channel set for its moment, with a direct link to the clip. Each run's record carries **View Clip Library** and **View Slack Alert**, so you can jump to the clip or the message it sent. See [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/) for the chat tools you can connect.

### Agent tools {#with-tools}

The agent has five tools: **Analyze Recordings**, **Detect Moments**, **Generate Summary**, **Add to Clip Library** and **Send to Slack**. All five are set to **Auto Run** by default, so they act without asking.

<figure>

![Content Curator agent on the Tools tab. An Add Tool button heads a list of five tools, and five cards describe Analyze Recordings, Detect Moments, Generate Summary, Add to Clip Library and Send to Slack, each with an Auto Run run-mode dropdown.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_104_agent-detail_content-curator_tools-tab_five-tools-analyze-recordings-detect-moments-generate-summary-clip-library-slack-all-auto-run.webp)

<figcaption>These five tools are the steps behind every clip, from reading the recording to filing it and posting to Slack, and each run mode can be changed from its card.</figcaption>
</figure>

[Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/) explains how to change which actions wait for your approval.

## Who uses the clip library, and how {#who-uses-it}

These are typical patterns, shown to illustrate how teams use clips.

### Enablement {#enablement}

An enablement lead defines moments for objection handling, discovery wins and strong closes. The library fills itself, and [new-hire ramp](https://www.oliv.ai/blog/sales-new-hire-ramp-time-coaching-onboarding) runs on examples from this month's calls rather than last year's.

### Sales managers {#sales-managers}

A [sales manager](https://www.oliv.ai/sales-managers) sets a moment for pricing objections across the team. Before each 1:1, the manager picks two clips that show the gap and one that shows the fix.

### Account executives and SDRs {#account-executives}

An account executive with a competitive deal gets recent clips of colleagues handling that competitor before the next meeting. It fits the way AEs [run their deals in Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/), with prep arriving instead of being assembled.

### Customer success {#customer-success}

Every recording is in scope, including onboarding sessions, QBRs and check-ins. A [customer success](https://www.oliv.ai/customer-success) lead uses the **Product Requests** moment and routes it to a channel the product team reads.

## How the clip library compares {#compare}

Oliv AI's clip library fills itself from moments you describe in plain words. Oliv AI's Content Curator agent clips each match, files it in that moment's library and posts it to your channel, every time a meeting is completed. Oliv AI is the only platform in this table that does all four.

Call clipping features, from each platform's public documentation:

| Platform | Clips cut from moments you describe | Clips filed into libraries automatically | New clips posted to a chat channel | Share link for a single clip |
|---|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes | Yes |
| **Gong** | Partly ([AI trackers flag moments](https://help.gong.io/docs/about-trackers)) | Partly ([streams collect whole calls](https://help.gong.io/docs/about-the-call-library)) | Partly ([stream alerts for new calls](https://help.gong.io/docs/about-the-call-library)) | Yes ([snip a moment to share](https://help.gong.io/docs/share-or-embed-a-call)) |
| **Avoma** | Partly ([AI picks the moments](https://help.avoma.com/how-to-create-a-snippet)) | Partly ([Smart Playlists by filter rules](https://help.avoma.com/creating-a-playlist)) | Partly ([keyword and topic alerts](https://help.avoma.com/slack-integration-setup-guide)) | Yes ([public snippet links](https://help.avoma.com/how-to-create-a-snippet)) |
| **Fireflies.ai** | Partly ([Magic Soundbites on request](https://guide.fireflies.ai/articles/1026795385-soundbites-how-to-extract-meeting-clips-and-highlights-from-fireflies-meetings-automatic-and-manual-methods)) | Partly ([playlist picked per soundbite](https://guide.fireflies.ai/articles/2540580393-getting-started-with-playlists-how-to-create-and-view-them)) | Not in docs | Yes ([anyone-with-link access](https://guide.fireflies.ai/articles/1026795385-soundbites-how-to-extract-meeting-clips-and-highlights-from-fireflies-meetings-automatic-and-manual-methods)) |
| **Fathom** | Partly ([Trackers find moments by meaning](https://help.fathom.video/en/articles/11380417)) | Partly ([playlists assembled by hand](https://help.fathom.video/en/articles/11380417)) | Partly ([search and tracker alerts](https://help.fathom.video/en/articles/7374465)) | Yes ([copy a highlight clip link](https://help.fathom.video/en/articles/295680)) |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for the clip library {#compare-stronger}

- **Moments you describe, clipped for you.** Oliv AI's Content Curator agent cuts the segments that match a moment you wrote in plain words. [Gong documents snippets made by dragging bars across the call timeline](https://help.gong.io/docs/add-calls-and-snippets-to-a-folder). See [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **Libraries of clips, not whole calls.** Oliv AI files each clip in the library its moment points to. [Avoma's Smart Playlists pull in whole recordings that match your filter rules](https://help.avoma.com/creating-a-playlist). See [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Filed without a second step.** Oliv AI routes every clip to its library and channel as soon as it's cut. [Fireflies.ai has you choose a playlist for each soundbite](https://guide.fireflies.ai/articles/2540580393-getting-started-with-playlists-how-to-create-and-view-them).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Recordings come first.** The agent needs recordings flowing from the Oliv AI notetaker before it can clip anything.
- **New recordings only.** It acts on newly completed recordings.
- **One library and one channel per moment.** To send the same kind of moment to two places, set up two moments.
- **Two access types.** A library is either **Public** or **Private**.
- **No fixed clip length.** Clips are cut to be concise and complete, so lengths vary.
- **Moment descriptions are the only guidance.** The agent has no [knowledge files](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/knowledge/), so put everything it needs into the description.
- **No match, no clip.** If a recording has nothing that matches a moment, no clip is made.

## Common questions {#common-questions}

#### Does the agent clip automatically, or do I trigger it? {#faq-automatic}

Automatically. Once a moment is defined, Oliv AI's Content Curator agent runs when a meeting is completed and adds clips as it finds them. **Run Agent** is there if you want to start a run by hand.

#### Can I clip a moment myself? {#faq-manual}

Yes. Open the meeting's **Recording** tab, find the moment and press **Clip**.

#### How does it know what to clip? {#faq-what-to-clip}

You describe the moment in plain language. The agent matches segments against that description, using context and intent rather than keyword lists.

#### What if it clips something irrelevant? {#faq-irrelevant}

Remove the clip and the agent learns from it. You can also refine the moment's description at any time to sharpen what it looks for.

#### What does each clip include? {#faq-clip-contents}

A short note on why it was captured, the participants, the timestamp, the call date and a link to the source recording.

#### How long is a clip? {#faq-length}

There's no set length. Each clip is cut to be concise and complete, so it holds the whole moment and little else.

#### Does it work on customer success and onboarding calls? {#faq-cs-calls}

Yes. Every recording in Oliv AI is in scope, including sales calls, demos, onboarding sessions, QBRs and customer success check-ins.

#### Can we share a library across teams? {#faq-share-library}

Yes. Set the library's **Access Type** to **Public**. Keep it **Private** while you curate. Individual clips can also be shared with **Share**.

#### Can someone outside our workspace watch a clip? {#faq-outside-viewer}

Yes. A clip has a shared view that opens from a link, built for someone outside your workspace.

#### Where do new clips show up? {#faq-where}

In the library set for the moment, on the **Library** tab of the Enable app. Libraries the agent fills show under **AI Library**. A Slack message with a direct link also goes to that moment's channel.

#### Which moments come ready to use? {#faq-default-moments}

Three come ready: **Product Requests**, **Competitor Mentions** and **Objections**. Add your own for anything else your team wants to learn from.

## Related {#related}

- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every guide, by agent and feature.
- [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): where clips fit in an AE's week.
- [Content Curator agent page](https://www.oliv.ai/agents/content-curator): what the agent watches for and where clips go.
- [Converse](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/): conversation capture, search and clipping.
- [Handling objections in sales](https://www.oliv.ai/blog/handling-objections-in-sales): what good objection handling sounds like.
- [Sales enablement software](https://www.oliv.ai/blog/sales-enablement-software): how enablement tools differ.
- [Coaching at scale with AI](https://www.oliv.ai/blog/vp-of-sales-coaching-at-scale-using-ai): building coaching that doesn't rely on hero managers.
- [Plans and pricing](https://www.oliv.ai/pricing): how Oliv AI is priced.
