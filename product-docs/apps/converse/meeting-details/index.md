# Meeting details

What you see when you open one captured meeting in Oliv AI, across its seven tabs from takeaways and tasks to qualification evidence, coaching, attendees and CRM updates, how to share it, and how it compares.

- Applies to: Converse, Sell and Grow plans
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/

Meeting details is what you see when you open one captured meeting in Oliv AI. It opens in a drawer over the Meetings list, with seven tabs that cover the takeaways, the tasks, the qualification evidence, the recording, a coaching score, the attendees and the CRM changes. From here you can replay a moment, clip it, ask questions about the meeting and share it.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it shows** | One captured meeting, split across seven tabs |
| **The tabs** | **Overview**, **Action Items**, **Meeting insights**, **Recording**, **Coaching**, **Attendees**, **CRM Updates** |
| **How you get there** | **Activities › Meetings**, then a meeting, or **Open Meeting** in Slack |
| **What's ready after the call** | Key takeaways, an AI summary, tasks and next steps |
| **Recording** | Player, chapters, transcript, comments and per-speaker talk time |
| **Sharing** | **Clip**, **Share**, a transcript segment, or a link-accessible view |

## What meeting details is {#what-it-is}

Meeting details is the record of a single customer conversation. You reach it from the [Meetings list](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) under **Activities**, and its address takes the form `/meetings/<id>`. It opens as a drawer over the list, and a round arrow on its left edge collapses it again.

The header carries the meeting title, an account chip, the date, time and duration, and a **Meeting with** dropdown. On the right sit an **Ask** button and the initials of everyone who attended.

<figure>

![Meeting details drawer for a proposal review on the Overview tab. The header shows an account chip, the date with a 30 minute duration and a Prospect dropdown above seven tabs. Cards show Key takeaways with blue timestamps, an AI Summary and a deal updates card with Review Deal.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_240_activities-meetings_meeting-details-drawer_overview-tab_key-takeaways-ai-summary-and-deal-updates-card.webp)

<figcaption>The Overview tab is where a meeting opens: takeaways, the AI summary and the linked deal sit together, and every tab across the top splits the same meeting another way.</figcaption>
</figure>

### The seven tabs {#tabs}

1. **Overview.** Key takeaways, the AI summary and the linked deal.
2. **Action Items.** The next meeting, next action and next follow-up, then a task table.
3. **Meeting insights.** What was said against each qualification criterion.
4. **Recording.** The player, chapters, transcript and comments.
5. **Coaching.** A grade for the call and scores per skill.
6. **Attendees.** Who was in the room and where each person stands.
7. **CRM Updates.** What was written back to the CRM after the call.

### A shared view for people outside the workspace {#shared-view}

Each meeting also has a shared view, opened by link at an address of the form `/meeting/view/<id>`. It's for someone who needs to see the meeting from outside your Oliv AI workspace.

## Why meeting details matters {#why-it-matters}

### What it's for {#what-its-for}

Meeting details is for anyone who needs to know what happened on a call they didn't join. It puts the summary, the transcript and the key moments of one meeting in a single drawer.

### How it helps {#how-it-helps}

- **The gist in a minute.** Key takeaways and the AI summary are ready as soon as the call ends.
- **The words, not a paraphrase.** Timestamps link each point back to the moment in the recording.
- **Qualification without replaying.** Meeting insights files what was said under each criterion.
- **Easy to pass on.** You clip a moment or share a transcript segment that plays from the right minute.

### What happens without it {#without-it}

Without a record of the meeting, what was said lives in one person's memory. Commitments made on the call get lost when the account moves to a new owner. The customer then repeats themselves to a team that should already know.

### Why buyers care {#why-buyers-care}

Customer success leaders care at handover, when onboarding has to start from what sales promised. Sales managers care when they coach from calls they didn't attend. Product teams care when they want feature requests in the customer's own words.

## The Oliv AI approach to meeting details {#approach}

{/* 5P */}

Consider a customer success manager picking up an account that closed on Friday. The kickoff with the customer is on Tuesday. Last week the account executive ran a handover call with the champion to agree what goes live first and who signs off. The CSM wasn't on it.

The usual route is a short recap message from the AE and a skim of the CRM notes. Some CSMs block an hour to watch the full recording. Each path likely costs time, and a recap written from memory can drop the one integration the champion called a must-have.

The details already exist on the recording. What the CSM needs is the champion's priorities and open concerns, in their own words, before Tuesday. Reading a whole transcript to find two or three moments is the slow part.

Oliv AI turns the handover call into a record the CSM can scan. The takeaways sit on the first tab, each with a timestamp into the recording. The **Attendees** tab shows where the champion stands. Then the CSM shares the right transcript segment with the onboarding lead, starting at the right minute.

The same summary and full call transcript also land on the opportunity record in the CRM. The CSM can find them there without opening Oliv AI. That CRM record is one of the points covered in How meeting details compares, below.

## Read a meeting {#read-a-meeting}

1. Open [**Activities › Meetings**](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) and click the meeting, or press **Open Meeting** in the Slack message about it.
2. Read **Key takeaways** and the **AI Summary** on **Overview**. Click a blue timestamp to hear that moment.
3. Open **Action Items** to see what was agreed, who owns it and when it's due.
4. Open **Meeting insights** to check qualification, or **Recording** to replay and read along.
5. Click **Review Deal** on the deal card to go to the linked deal.

If you'd rather get the summary without opening the drawer, the [Slack meeting summary](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) arrives as soon as the meeting ends. It carries the meeting details, key takeaways and next steps. For ways to structure what you capture, see [meeting summary templates](https://www.oliv.ai/blog/meeting-summary-templates).

## What each tab shows {#what-it-picks-out}

### Overview: takeaways, summary and the deal {#summary}

**Key takeaways** lists the main points of the call, each with blue timestamps that link back to the recording. The **AI Summary** card holds longer headed entries, also timestamped. Below them, a deal updates card shows the linked deal's stage, amount and close date, with a **Review Deal** button.

After a call on an active opportunity, [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) also [drafts the follow-up email](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) from the transcript. More on [AI meeting summaries](https://www.oliv.ai/blog/ai-meeting-summaries).

### Action Items: next steps and tasks {#action-items}

Three cards sit across the top: **Next meeting**, **Next action** and **Next follow-up**. The next meeting carries its RSVP status, such as **Accepted**, and a late follow-up shows **Overdue**. Below them, a **Tasks** table lists each commitment with an **Assignee** and a **Due Date**.

<figure>

![Action Items tab with three cards: Next meeting with a green Accepted badge, Next action with a date chip and Next follow-up with a red Overdue badge. Below, a Tasks table on the Pending filter lists Our tasks with checkboxes, Assignee, Due Date and blue timestamps, then Add task.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_241_activities-meetings_meeting-details-drawer_action-items-tab_next-meeting-next-action-follow-up-and-our-tasks-table.webp)

<figcaption>Action Items turns what was agreed on the call into owned, dated tasks, and each timestamp takes you back to the moment the commitment was made.</figcaption>
</figure>

Each task links to the moment in the recording where it was agreed. Tick a task off, change the **Pending** status filter, or press **Add task** to add one by hand.

### Meeting insights: qualification evidence {#meeting-insights}

Meeting insights files what was said under each criterion of your qualification framework. A row of chips jumps to each section: **Metrics**, **Economic Buyer**, **Decision Criteria**, **Decision Process**, **Paper Process**, **Identify Pain**, **Champion** and **Additional Fields**.

<figure>

![Meeting insights tab with eight chips from Metrics to Additional Fields, Metrics selected. The Metrics section holds Success Metrics, Business Impact and Investment ROI cards, the last reading No ROI, and the Economic Buyer section starts below with Buying Committee and Budget Requirements cards.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_242_activities-meetings_meeting-details-drawer_meeting-insights-tab_meddpicc-sections-metrics-and-economic-buyer.webp)

<figcaption>Meeting insights lets a manager check qualification without listening to the call, and a card that says nothing was discussed marks the gap to close on the next one.</figcaption>
</figure>

Each section holds evidence cards with timestamps. Where nothing was said, the card states it rather than guessing. The criteria follow the methodology active in **Settings › Qualification Framework**, so a team on another framework sees its own criteria.

### Recording: player, chapters and transcript {#recording}

The **Recording** tab holds the player, with **Add Comment**, **Clip** and **Share** beneath it. A **Timeline** groups speakers by company and shows each person's **Talk time** and **Engagement**. On the right, **Chapters**, **Transcripts** and **Comments** let you jump to a section, read along or see your team's notes.

<figure>

![Recording tab with a video player and Add Comment, Clip and Share buttons under it. A Timeline shows a speaker grouped by company with Talk time and Engagement, and the Chapters sub-tab lists Meeting Purpose, Action Items, Next Steps and Feedback Request with timestamps.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_243_activities-meetings_meeting-details-drawer_recording-tab_blank-player-add-comment-clip-share-timeline-and-chapters.webp)

<figcaption>The Recording tab is where you find a moment by chapter or transcript, then clip it, comment on it or share the meeting, without scrubbing through the whole call.</figcaption>
</figure>

### Coaching: a grade for the call {#coaching}

The **Coaching** tab grades the call and scores the rep's skills out of 5. Skill groups such as **Solution Presentation**, **Value Storytelling**, **Prospect Engagement**, **Objection Handling** and **Driving Action** each break into sub-skills. A **Summary** card names one **Improvement Required** and one **Strength**.

<figure>

![Coaching tab with a left list of Summary with a letter grade, Meeting Stats and skill groups scored out of 5 with sub-skills. The right pane shows a Summary card with Improvement Required and Strength notes, a circular grade gauge and a MEDDPICC Scorecard radar chart.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_244_activities-meetings_meeting-details-drawer_coaching-tab_b-plus-summary-skill-scores-and-meddpicc-radar-chart.webp)

<figcaption>Coaching shows a manager where a rep needs help on this call, skill by skill, with the framework scorecard beside it, so a 1:1 can start from evidence.</figcaption>
</figure>

A scorecard radar shows coverage of each qualification criterion, with a badge counting how many improved. Click any skill in the left list to see the evidence behind its score. [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) does the scoring, using the scorecards set in **Settings › Coaching Scorecard**.

### Attendees: the buying committee {#attendees}

The **Attendees** tab sorts the people on the call into **Buying Committee** and **Other Contacts**, with a search box. Each person gets a card with their sentiment, such as **Ally** or **Neutral**, whether they are a **Decision Maker**, and an access level such as **In-Depth Access** or **Limited Access**.

<figure>

![Attendees tab with a searchable Buying Committee list of three people with sentiment faces, and Other Contacts below. The right pane shows a card per attendee with View Contact, a status row of sentiment, Decision Maker, access level, Talk time and Engagement, and timestamped Key Attendee Insights.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_245_activities-meetings_meeting-details-drawer_attendees-tab_buying-committee-sentiment-access-talk-time-and-insights.webp)

<figcaption>Attendees maps the buying committee from one call, so you can see who decides, who is on your side and who barely spoke before the next meeting.</figcaption>
</figure>

Each card also shows talk time, engagement and **Key Attendee Insights** with timestamps. **View Contact** opens the person's full contact record.

### CRM Updates: what reached the CRM {#crm-updates}

The **CRM Updates** tab is a timeline of the changes made after the meeting. A green check marks a completed change, such as an account summary refresh, a scorecard update or a new contact. A grey clock marks a **Pending Update** that waits for you, such as a stage move.

<figure>

![CRM Updates tab with a vertical timeline. Green checks mark Account Updated, Opportunity Updated: BANT Scorecard and two Contact Created entries, each with View Account, View Deal or View Contact. A grey clock marks Pending Update: Move to Proposal with an Update Deal button.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_246_activities-meetings_meeting-details-drawer_crm-updates-tab_account-deal-bant-and-contact-updates-with-pending-stage-move.webp)

<figcaption>CRM Updates shows RevOps exactly what this meeting changed in the CRM, and which change, like a stage move, is still waiting for a person to confirm.</figcaption>
</figure>

Press **Update Deal** to act on a pending change. **View Account**, **View Deal** and **View Contact** open the record that changed. The [keep the CRM updated guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/) covers the wider flow.

### Objections and pricing concerns {#objections}

Oliv AI's Content Curator agent watches for **Objections**, one of its three moment types. Its **Detect Moments** tool tags moments by type, such as product requests, competitor mentions and objections. You can also search a meeting for the exact objection or pricing concern yourself.

### Competitor mentions {#competitor-mentions}

**Competitor Mentions** is another of Content Curator's moment types. It looks for mentions of competitors, or feature by feature comparisons, so you see how a competitor came up.

### Product requests and feedback {#product-requests}

**Product Requests** is the third moment type. Its public page lists product feedback among the moments a team can ask it to watch for. Clips can go into a clip library for the product team.

### Sentiment {#sentiment}

Sentiment shows per person on the **Attendees** tab, as **Ally** or **Neutral** for example. When Content Curator maps a conversation, it also reads the meeting's sentiment and how it flowed. Converse reads sentiment and intent instead of matching words.

### Voice of the customer {#voice-of-the-customer}

**Ask AI · Voice of the customer** is listed among the customer context features on every plan, as a credit-based feature. Details are on [Oliv AI pricing](https://www.oliv.ai/pricing).

## Ask questions about a meeting {#ask-questions}

The **Ask** button sits at the right of the meeting drawer. You can also ask [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) about a call in plain language. Ask her to draft the follow-up from your call this afternoon, and she pulls from the meeting transcript and drafts it.

[Every plan](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) includes asking questions and reviewing conversations, opportunities and accounts. **Ask AI** is credit-based on every plan. AI agent actions are paid through credits, for tasks such as researching an account or updating CRM records.

## Share part of a meeting {#share}

On the **Recording** tab, **Clip** cuts a moment, **Add Comment** notes a point in the call and **Share** shares the meeting. To share part of the transcript instead:

1. In the transcript, find the minute marker where the moment starts.
2. Check the box beside the segment you want to share.
3. Copy the selected portion.
4. Open it in a new tab. Playback begins from that minute.

To share the whole meeting with someone outside your workspace, use its shared view, which opens by link. To keep a moment for your own team, [clip it into a clip library](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) instead. The [guide to taking notes during sales calls](https://www.oliv.ai/blog/how-to-take-meeting-notes-during-sales-calls) covers what to capture by hand.

## How meeting details works with Oliv AI's agents {#works-with}

### Meeting Assistant {#with-meeting-assistant}

Oliv AI's Meeting Assistant agent runs on Oliv Notetaker recordings and transcripts. After the meeting it drafts the follow-up and flags what needs updating in the CRM. The [prepare for a meeting guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) covers its brief before the next call.

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) attaches the AI-generated summary and the full call transcript to the opportunity record. It writes the field updates Meeting Assistant proposes, as a layer on top of your CRM. Its changes for this meeting show on the **CRM Updates** tab.

### Coach {#with-coach}

Oliv AI's Coach agent fills the **Coaching** tab. It grades the call against the scorecard for meetings and scores each skill, so a manager can coach from the call without joining it.

### Content Curator {#with-content-curator}

[Oliv AI's Content Curator agent](https://www.oliv.ai/agents/content-curator) runs when a meeting is completed. Each clip carries a short explanation of why it was captured, plus the participants, timestamp, call date and a link to the recording.

### Gold Digger and Portfolio Manager {#with-cs-agents}

[Oliv AI's Gold Digger agent](https://www.oliv.ai/agents/gold-digger) quotes the transcript, with a timestamp link to the exact moment, when it spots an expansion signal. [Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager) flags account risk signals, including a sentiment shift.

## Who uses meeting details, and how {#who-uses-it}

### Customer success managers {#customer-success}

A CSM reads the handover call before kickoff, so onboarding starts from what the customer was promised. More on Oliv AI for [customer success teams](https://www.oliv.ai/customer-success).

### Account managers {#account-managers}

An account manager checks the last QBR before a renewal conversation, including any competitor the customer mentioned. See Oliv AI for [account management](https://www.oliv.ai/account-management).

### Account executives {#account-executives}

An AE works the **Action Items** tab before sending the follow-up, so every agreed task has an owner and a date. See how AEs [run deals with Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Sales managers and enablement {#enablement-and-product}

A manager reads **Meeting insights** and **Coaching** before a 1:1. An enablement lead clips a strong objection handle for onboarding. Read about [sales enablement software](https://www.oliv.ai/blog/sales-enablement-software).

## How meeting details compares {#compare}

Most meeting tools write an AI summary and send notes to the CRM. Oliv AI also turns a plain-language description of a moment into clips that are cut, filed and shared for you. Oliv AI is the only platform in this table that does all three.

Meeting record features, from each platform's public documentation:

| Platform | AI summary with next steps | Clips cut from a description you write | Meeting notes written to the CRM record |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Yes ([Highlights recap and next steps](https://help.gong.io/docs/about-the-call-page)) | Partly ([AI trackers mark matching moments](https://help.gong.io/docs/find-and-review-tracker-results)) | Yes ([Highlights and Transcript tabs in Salesforce](https://help.gong.io/docs/conversation-canvas-page-errors)) |
| **Avoma** | Yes ([Key Takeaways with next steps](https://help.avoma.com/ai-generated-key-takeaways)) | Partly ([custom categories for notes](https://help.avoma.com/ai-generated-notes)) | Yes ([notes and action items pushed to CRM](https://help.avoma.com/create-an-account)) |
| **Fireflies** | Yes ([summary and action items](https://guide.fireflies.ai/articles/1123841396-how-to-upload-and-transcribe-a-meeting-recording-file-to-fireflies-ai-web-app)) | Partly ([AI picks the key moments](https://guide.fireflies.ai/articles/1026795385-soundbites-how-to-extract-meeting-clips-and-highlights-from-fireflies-meetings-automatic-and-manual-methods)) | Yes ([notes and transcript link in HubSpot](https://guide.fireflies.ai/articles/4037978139-how-to-integrate-hubspot-with-fireflies)) |
| **Fathom** | Yes ([summaries and action items](https://help.fathom.video/en/articles/13926529)) | Partly ([highlight button pressed on the call](https://help.fathom.video/en/articles/448576)) | Yes ([summaries written to Salesforce](https://help.fathom.video/en/articles/448640)) |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for meeting details {#compare-stronger}

- **Moments become clips, filed and posted.** Content Curator cuts each match into a clip, files it in a library and posts it to a chat channel. Gong's tracker results appear as [timestamps in the Points of interest tab](https://help.gong.io/docs/find-and-review-tracker-results). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **You describe the moment, not the category.** You tell Content Curator what belongs in plain language, with no keyword lists. Avoma lets you [create custom categories](https://help.avoma.com/ai-generated-notes) to organize meeting notes. Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **The full transcript travels with the summary.** Oliv AI attaches the AI summary and the full call transcript to the opportunity record. Avoma documents pushing [meeting notes, action items, and insights](https://help.avoma.com/create-an-account) to the CRM. See [Gong vs Avoma](https://www.oliv.ai/blog/gong-vs-avoma) for where Oliv AI fits.

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Ask AI uses credits.** **Ask AI · Voice of the customer** is credit-based on every plan. See [plan details on oliv.ai](https://www.oliv.ai/pricing).
- **Insights follow one framework.** Meeting insights and the scorecard radar use the methodology active in **Settings › Qualification Framework**.
- **Some CRM changes wait for you.** A **Pending Update**, such as a stage move, stays pending until someone confirms it with **Update Deal**.
- **Clips live in Enable.** The clips route opens the **Library** tab of the Enable app.
- **Transcript sharing starts at a minute marker.** A shared segment plays from the minute marker you picked.
- **Meeting Assistant needs an active opportunity.** Its follow-up and field updates cover meetings linked to an active opportunity in your CRM.

## Common questions {#common-questions}

#### How do I open a meeting's details? {#faq-open}

Open **Activities › Meetings** and click the meeting. Or press **Open Meeting** in the Slack message Oliv AI sent about it.

#### What tabs does a meeting have? {#faq-tabs}

Seven: **Overview**, **Action Items**, **Meeting insights**, **Recording**, **Coaching**, **Attendees** and **CRM Updates**.

#### When is the summary ready? {#faq-summary-ready}

The AI summary and next steps are ready as soon as the call ends. The Slack meeting summary is sent immediately after the meeting ends.

#### Does the transcript show who said what? {#faq-speakers}

Yes. Oliv AI transcribes the conversation and labels every speaker. The **Recording** tab also shows each speaker's talk time.

#### Can I check qualification without replaying the call? {#faq-qualification}

Yes. **Meeting insights** files what was said under each criterion, with timestamps, and says so when a criterion wasn't discussed.

#### Can I find a specific objection in a call? {#faq-objection}

Yes. Search for the exact objection, competitor mention or pricing concern, then clip it into a clip library.

#### Does Oliv AI detect competitor mentions? {#faq-competitors}

Oliv AI's Content Curator agent has a **Competitor Mentions** moment type for mentions of competitors or feature by feature comparisons.

#### Can product teams get feature requests from calls? {#faq-product}

Yes. Content Curator's moment types include **Product Requests**, and clips can go into a library for product.

#### How do I share part of a call? {#faq-share-part}

Find the minute marker, check the box for the segment and copy it. Opened in a new tab, it plays from that minute.

#### Can someone outside my workspace see a meeting? {#faq-outside}

Yes. Each meeting has a shared, link-accessible view for someone opening it outside the workspace.

#### Does the meeting reach my CRM? {#faq-crm}

Yes. The AI-generated summary and the full call transcript are attached to the opportunity record. The **CRM Updates** tab lists every change made.

#### Can I ask questions about a meeting? {#faq-ask}

Yes. Use **Ask** in the drawer, or ask Olivia, for example to draft the follow-up from a call, and she works from the transcript.

## Related {#related}

- [Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/): the conversation capture app behind every meeting record.
- [Meeting transcription software compared](https://www.oliv.ai/blog/meeting-transcription-software): how transcripts differ across tools.
- [Meaning extraction vs dumping transcripts into LLMs](https://www.oliv.ai/blog/slms-vs-llms-enterprise): why Oliv AI reads context rather than keywords.
- [The Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): how meeting signals feed deal risk for managers.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): how agents act on what a meeting contains.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
