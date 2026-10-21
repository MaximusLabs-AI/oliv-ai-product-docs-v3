# Meeting details

What you see when you open one captured meeting in Oliv AI, from the summary and next steps to objections, competitor mentions and product requests, how to ask about it and share it, and how it compares.

- Applies to: Converse, Sell and Grow plans
- Status: Live
- Verified: 2026-10-21
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/

Meeting details is the page you see when you open one captured meeting in Oliv AI. It shows the meeting's details panel alongside the recording and notes, with an AI summary and next steps ready as soon as the call ends. From here you can search what was said, ask questions about the meeting and share the part that matters.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it shows** | One captured meeting: details panel, recording, transcript and notes |
| **How you get there** | **Activities › Meetings**, then a meeting, or **Open Meeting** in Slack |
| **What's ready after the call** | AI summary, action items and next steps |
| **Transcript** | Every speaker labeled, with minute markers you can share from |
| **Signals Oliv AI picks out** | Objections, pricing concerns, competitor mentions and product requests |
| **Sharing** | A transcript segment, a clip, or a link-accessible view for outsiders |

## What meeting details is {#what-it-is}

Meeting details is the record of a single customer conversation. Its address takes the form `/meetings/<id>`, and you reach it from the [Meetings list](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) under **Activities**. The page puts a details panel next to the recording and the notes.

Oliv AI transcribes the conversation and labels every speaker. It reads context, sentiment and intent rather than matching keywords. The same record feeds your CRM, your forecast and every Oliv AI agent.

### A shared view for people outside the workspace {#shared-view}

Each meeting also has a shared view, opened by link at an address of the form `/meeting/view/<id>`. It's for someone who needs to see the meeting from outside your Oliv AI workspace.

## Why meeting details matters {#why-it-matters}

### What it's for {#what-its-for}

Meeting details is for anyone who needs to know what happened on a call they didn't join. It puts the summary, the transcript and the key moments of one meeting on a single page.

### How it helps {#how-it-helps}

- **The gist in a minute.** The AI summary and next steps are ready as soon as the call ends.
- **The words, not a paraphrase.** The transcript labels every speaker, so you see who said what.
- **Concerns surfaced.** Objections, pricing concerns and competitor mentions can be found and clipped.
- **Easy to pass on.** You share a transcript segment that plays from the right minute.

### What happens without it {#without-it}

Without a record of the meeting, what was said lives in one person's memory. Commitments made on the call get lost when the account moves to a new owner. The customer then repeats themselves to a team that should already know.

### Why buyers care {#why-buyers-care}

Customer success leaders care at handover, when onboarding has to start from what sales promised. Sales managers care when they coach from calls they didn't attend. Product teams care when they want feature requests in the customer's own words.

## The Oliv AI approach to meeting details {#approach}

{/* 5P */}

Consider a customer success manager picking up an account that closed on Friday. The kickoff with the customer is on Tuesday. Last week the account executive ran a handover call with the champion to agree what goes live first and who signs off. The CSM wasn't on it.

The usual route is a short recap message from the AE and a skim of the CRM notes. Some CSMs block an hour to watch the full recording. Each path likely costs time, and a recap written from memory can drop the one integration the champion called a must-have.

The details already exist on the recording. What the CSM needs is the champion's priorities and open concerns, in their own words, before Tuesday. Reading a whole transcript to find two or three moments is the slow part.

Oliv AI turns the handover call into a record the CSM can scan. The summary and next steps sit at the top, and the transcript labels every speaker. The CSM can search the concern the champion raised. Then they share that transcript segment with the onboarding lead, starting at the right minute.

The same summary and full call transcript also land on the opportunity record in the CRM. The CSM can find them there without opening Oliv AI. That CRM record is one of the points covered in How meeting details compares, below.

## Read a meeting {#read-a-meeting}

1. Open [**Activities › Meetings**](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meetings/) and choose the meeting, or press **Open Meeting** in the Slack message about it.
2. Read the AI summary, action items and next steps first. They're ready as soon as the call ends.
3. Use the transcript to check who said what. Every speaker is labeled.
4. Search for the exact objection, competitor mention or pricing concern you're looking for.
5. [Clip the moment into a playlist](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) for coaching, enablement or product.

If you'd rather get the summary without opening the page, the [Slack meeting summary](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) arrives as soon as the meeting ends. It carries the meeting details, key takeaways and next steps. For ways to structure what you capture, see [meeting summary templates](https://www.oliv.ai/blog/meeting-summary-templates).

## What Oliv AI picks out of a meeting {#what-it-picks-out}

### Summary, action items and next steps {#summary}

Oliv AI writes an AI summary with action items and next steps for each captured meeting. After a call on an active opportunity, [Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) also [drafts the follow-up email](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/) from the transcript. It flags qualification gaps and proposes [CRM field updates](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/). More on [AI meeting summaries](https://www.oliv.ai/blog/ai-meeting-summaries).

### Objections and pricing concerns {#objections}

Oliv AI's Content Curator agent ships with an **Objection** moment type. It finds moments where prospects raise concerns about pricing, security or technical fit. You can also search a meeting for the exact objection or pricing concern yourself.

### Competitor mentions {#competitor-mentions}

The **Competition Intel** moment type looks for mentions of competitors, or feature by feature comparisons. It aims to capture market sentiment and signals that a competitor may be displaced.

### Product requests and feedback {#product-requests}

Content Curator's moment categories include **Product Requests**. Its public page lists product feedback among the moments a team can ask it to watch for. Clips can go into a playlist for the product team.

### Sentiment {#sentiment}

When Content Curator maps a conversation, it reads the meeting's context, who spoke and how they interacted, how it flowed, and its sentiment. Converse reads sentiment and intent instead of matching words.

### Voice of the customer {#voice-of-the-customer}

**Ask AI · Voice of the customer** is listed among the customer context features on every plan, as a credit-based feature. Details are on [Oliv AI pricing](https://www.oliv.ai/pricing).

## Ask questions about a meeting {#ask-questions}

You can ask [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) about a call in plain language. Ask her to draft the follow-up from your call this afternoon, and she pulls from the meeting transcript and drafts it.

[Every plan](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/plans/plans-and-seat-roles/) includes asking questions and reviewing conversations, opportunities and accounts. **Ask AI** is credit-based on every plan. AI agent actions are paid through credits, for tasks such as researching an account or updating CRM records.

## Share part of a meeting {#share}

1. In the transcript, find the minute marker where the moment starts.
2. Check the box beside the segment you want to share.
3. Copy the selected portion.
4. Open it in a new tab. Playback begins from that minute.

To share the whole meeting with someone outside your workspace, use its shared view, which opens by link. To share a moment with your own team, [clip it into a playlist](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) instead. The [guide to taking notes during sales calls](https://www.oliv.ai/blog/how-to-take-meeting-notes-during-sales-calls) covers what to capture by hand.

## How meeting details works with Oliv AI's agents {#works-with}

### Meeting Assistant {#with-meeting-assistant}

[Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) runs on Oliv Notetaker recordings and transcripts. After the meeting it drafts the follow-up and flags what needs updating in the CRM. The [prepare for a meeting guide](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/) covers its brief before the next call.

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) attaches the AI-generated summary and the full call transcript to the opportunity record. It writes the field updates Meeting Assistant proposes, as a layer on top of your CRM.

### Content Curator {#with-content-curator}

[Oliv AI's Content Curator agent](https://www.oliv.ai/agents/content-curator) runs when a meeting recording has been processed. Each clip carries a short explanation of why it was captured, plus the participants, timestamp, call date and a link to the recording.

### Gold Digger and Portfolio Manager {#with-cs-agents}

[Oliv AI's Gold Digger agent](https://www.oliv.ai/agents/gold-digger) quotes the transcript, with a timestamp link to the exact moment, when it spots an expansion signal. [Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager) flags account risk signals, including a sentiment shift.

## Who uses meeting details, and how {#who-uses-it}

### Customer success managers {#customer-success}

A CSM reads the handover call before kickoff, so onboarding starts from what the customer was promised. More on Oliv AI for [customer success teams](https://www.oliv.ai/customer-success).

### Account managers {#account-managers}

An account manager checks the last QBR before a renewal conversation, including any competitor the customer mentioned. See Oliv AI for [account management](https://www.oliv.ai/account-management).

### Account executives {#account-executives}

An AE confirms the next steps agreed on a call before sending the follow-up. See how AEs [run deals with Oliv AI](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Enablement and product {#enablement-and-product}

An enablement lead clips a strong objection handle for onboarding, and a product manager collects feature requests in the customer's words. Read about [sales enablement software](https://www.oliv.ai/blog/sales-enablement-software).

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
- **Clips are filed by moment type.** In Content Curator, each moment type routes to one library and one chat channel.
- **Clips live in Enable.** The clips route opens the **Library** tab of the Enable app.
- **Transcript sharing starts at a minute marker.** A shared segment plays from the minute marker you picked.
- **Meeting Assistant needs an active opportunity.** Its follow-up and field updates cover meetings linked to an active opportunity in your CRM.

## Common questions {#common-questions}

#### How do I open a meeting's details? {#faq-open}

Open **Activities › Meetings** and choose the meeting. Or press **Open Meeting** in the Slack message Oliv AI sent about it.

#### When is the summary ready? {#faq-summary-ready}

The AI summary and next steps are ready as soon as the call ends. The Slack meeting summary is sent immediately after the meeting ends.

#### Does the transcript show who said what? {#faq-speakers}

Yes. Oliv AI transcribes the conversation and labels every speaker.

#### Can I find a specific objection in a call? {#faq-objection}

Yes. Search for the exact objection, competitor mention or pricing concern, then clip it into a playlist.

#### Does Oliv AI detect competitor mentions? {#faq-competitors}

Oliv AI's Content Curator agent has a **Competition Intel** moment type for mentions of competitors or feature by feature comparisons.

#### Can product teams get feature requests from calls? {#faq-product}

Yes. Content Curator's categories include **Product Requests**, and clips can go into a playlist for product.

#### How do I share part of a call? {#faq-share-part}

Find the minute marker, check the box for the segment and copy it. Opened in a new tab, it plays from that minute.

#### Can someone outside my workspace see a meeting? {#faq-outside}

Yes. Each meeting has a shared, link-accessible view for someone opening it outside the workspace.

#### Does the meeting reach my CRM? {#faq-crm}

Yes. The AI-generated summary and the full call transcript are attached to the opportunity record.

#### Can I ask questions about a meeting? {#faq-ask}

Yes. Ask [Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/), for example to draft the follow-up from a call, and she works from the transcript.

## Related {#related}

- [Converse app](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/): the conversation capture app behind every meeting record.
- [Meeting transcription software compared](https://www.oliv.ai/blog/meeting-transcription-software): how transcripts differ across tools.
- [Meaning extraction vs dumping transcripts into LLMs](https://www.oliv.ai/blog/slms-vs-llms-enterprise): why Oliv AI reads context rather than keywords.
- [The Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): how meeting signals feed deal risk for managers.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): how agents act on what a meeting contains.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
