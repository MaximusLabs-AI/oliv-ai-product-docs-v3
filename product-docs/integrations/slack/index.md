# Slack

Which meeting messages Oliv AI sends to Slack and when, which agents post alerts and clips there, how to connect Slack, and how it compares with other tools.

- Applies to: Customer success, account managers, account executives, sales managers and enablement
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/

Oliv AI's Slack integration brings your meetings and your agents' alerts into Slack. Once Slack is connected, you get a summary of tomorrow's meetings, a prep summary before each call and a meeting summary straight after it. Agents add their own messages on top, such as an expansion signal for the account executive or a new clip for the team.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Sends meeting messages and agent alerts to Slack |
| **Who it's for** | CSMs, account managers, account executives, sales managers and enablement |
| **Built-in messages** | Tomorrow's meetings, prep summary, meeting summary |
| **How to connect** | Install the Oliv Slack app, or accept a Slack Connect request |
| **Setup after connecting** | None: messages start automatically |
| **Also sent to** | Your email, by default |

## What the Slack integration is {#what-it-is}

The Slack integration connects Oliv AI to your Slack workspace. Oliv uses a collaboration tool to share meeting reminders and meeting summaries, so the team can see what's happening and move deals forward. Slack is one of three collaboration tools listed, next to Microsoft Teams and Google Chat.

### Two ways to connect {#connect-options}

- **The Oliv Slack app.** Install it at web.oliv.ai/slack/direct-install.
- **Slack Connect.** Oliv sends you a Slack Connect request. Once you accept it, you start receiving meeting preparation summaries and meeting summaries.

### What arrives in Slack {#what-arrives}

Two kinds of message reach you. The first is the three built-in meeting messages, which start as soon as Slack is connected. The second is alerts and reports from Oliv AI's agents, each sent when that agent has something to tell you.

Slack also works the other way round. Slack messages are captured as context, and each deal's **Momentum** tab plots **Internal Slack** and **External Slack** on the same timeline as meetings and email.

<figure>

![A deal's Momentum tab on the Activity Map sub-tab: dot rows for Meetings, Emails, Int. Slack, Ext. Slack and System along a date axis, a dashed Today line, and a legend that separates Internal Slack from External Slack.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/records-deals/oliv-ai_222_records-deals_deal-detail-drawer_momentum-tab_activity-map-meetings-emails-internal-external-slack-system-dots-today-line.webp)

<figcaption>Slack conversations about a deal show up as two rows on its Activity Map, internal and external, so a quiet deal is easy to spot even when the talk moved to Slack.</figcaption>
</figure>

## Why the Slack integration matters {#why-it-matters}

### What it's for {#what-its-for}

The Slack integration is for teams that already live in Slack. It puts the meeting prep, the call summary and the account alert where people read their messages. Nobody has to open another tool to find out what happened.

### How it helps {#how-it-helps}

- **Tomorrow is planned today.** At 4 PM local time, you see every meeting Oliv will summarize the next day.
- **Prep lands just in time.** The prep summary arrives 10 minutes before the meeting.
- **The call is summed up at once.** The meeting summary is sent as soon as the meeting ends.
- **Signals reach the right person.** Agents send alerts, such as an expansion signal from a customer call, to the person who acts on it.

### What happens without it {#without-it}

The news from each call stays where it was recorded. Someone has to go looking for it, and often nobody does. An expansion hint or a risk raised on a Tuesday call can sit unread until the next review.

### Why buyers care {#why-buyers-care}

Customer success leaders care when their team works across many accounts and few meetings overlap. Account executives care at handoff, when a signal from a CSM's call is theirs to act on. Enablement cares when good moments should reach the whole team quickly.

## The Oliv AI approach to the Slack integration {#approach}

{/* 5P */}

Think of a customer success team of six that runs its day from one shared Slack channel. Each CSM looks after around thirty accounts. When a customer hints at growth on a call, the team wants the account executive to hear about it the same day.

The usual way is a habit. After a call, the CSM types a short update into the channel, if there's time. Updates can get shorter as the week fills up, and some are skipped. The account executive may learn about an expansion hint weeks later, from a renewal note.

The call already holds the signal. It was said out loud, by a named person, at a known minute in the recording. What's missing is something that hears it and posts it, without waiting for the CSM to write it up.

Oliv AI handles this with its Gold Digger agent. Gold Digger listens to every call. When it detects an expansion signal, it sends the account executive a Slack notification right after the call ends. It also drafts the handoff email from the CSM. Meanwhile each CSM gets a meeting summary in Slack after every call.

The timing of each message is fixed and stated. The prep summary comes 10 minutes before a meeting. The list of tomorrow's meetings comes at 4 PM local time, as set out in Meeting messages in Slack. How those messages line up with other tools is covered in How Oliv AI compares for sales alerts in Slack, below.

## Set up the Slack integration {#set-up}

1. **Connect your calendar.** Calendar integration is required for Oliv to work, so connect it first.
2. **Connect Slack.** Install the Oliv Slack app at web.oliv.ai/slack/direct-install, or accept the Slack Connect request Oliv sends you.
3. **Let the messages start.** The three meeting messages begin automatically. There's no manual setup.
4. **Add the Sales Companion app, if you want it.** The Help Center suggests installing the **Oliv Slack Sales Companion** app to make the most of Slack.
5. **Turn messages off if you prefer.** You can disable the automated messages from your **Profile Settings** page, the last item in the **Settings** menu.

<figure>

![The Settings flyout opened from the bottom of the left sidebar, listing Revenue Process, Qualification Framework, Coaching Scorecard, Targets, Measurements, Organisational Settings and Profile Settings, over a dimmed Playbook page.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/settings/oliv-ai_259_settings_sidebar-settings-flyout-menu_open-with-revenue-process-qualification-framework-coaching-scorecard-targets-measurements-organisational-and-profile-settings.webp)

<figcaption>Profile Settings sits at the foot of the Settings menu. It's your own page, so turning the meeting messages off there changes only what you receive.</figcaption>
</figure>

## Meeting messages in Slack {#meeting-messages}

| Message | What it contains | When it's sent |
|---|---|---|
| **Summary of tomorrow's meetings** | Every meeting the next day that Oliv will summarize | 4 PM local time |
| **Prep summary** | Meeting details, plus research on the account and contact | 10 minutes before the meeting |
| **Meeting summary** | Meeting details, next steps, talk time and a scorecard | As soon as the meeting ends |

### Summary of tomorrow's meetings {#tomorrow-summary}

This message lists all the meetings for the following day that Oliv will summarize. It gives you an overview of the day ahead while there's still time to prepare.

### Prep summary {#prep-summary}

The prep summary gives you the meeting's title, date, time, participants and the account it belongs to. It adds research on the account and the contact you're meeting. For the full brief an agent builds before a deal meeting, see how to [prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Meeting summary {#meeting-summary}

Straight after the meeting, the summary repeats the meeting details and adds the key takeaways. That means the next steps, the talk time and a scorecard. If you want to change how summaries read, Oliv AI's guide to [AI meeting summaries](https://www.oliv.ai/blog/ai-meeting-summaries) covers what makes one useful.

## Work from a Slack message {#from-slack}

- **Open the call.** Click **Open Meeting** in a Slack message about a meeting. You [go straight to that meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/meeting-details/) in Oliv, with its recording.
- **Skip the note taker.** The meeting preparation summary includes a link to [stop the note taker from joining](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/recording-modes/) that call. The same link appears in the email version.
- **Reach it by email too.** The meeting messages also go to your email by default, so nothing is lost if you're away from Slack.

## How Slack works with Oliv AI's agents {#works-with}

### Gold Digger {#with-gold-digger}

[Oliv AI's Gold Digger agent](https://www.oliv.ai/agents/gold-digger) sends the account executive a Slack notification as soon as a call with an expansion signal ends. It names the account and who was on the call, and quotes what was said from the transcript.

### Portfolio Manager {#with-portfolio-manager}

[Oliv AI's Portfolio Manager agent](https://www.oliv.ai/agents/portfolio-manager) flags at-risk accounts with the evidence behind the flag and a next step with a date. It connects to your CRM, email, call recording and Slack.

### Content Curator {#with-content-curator}

Oliv AI's Content Curator agent posts to the Slack or Teams channel you configure. Each notification carries the intent name, a one-line summary, the source call and [a direct link to the clip](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/). You choose real-time posts, the default, or a daily digest. On its **Tools** tab, the last step is **Send to Slack**, which notifies the relevant channels or team members with moment highlights and links to the clip library.

<figure>

![Content Curator's Tools tab with five tools, Analyze Recordings, Detect Moments, Generate Summary, Add to Clip Library and Send to Slack, each card with a one-line description and an Auto Run run-mode dropdown.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_104_agent-detail_content-curator_tools-tab_five-tools-analyze-recordings-detect-moments-generate-summary-clip-library-slack-all-auto-run.webp)

<figcaption>Send to Slack is the final step of Oliv AI's Content Curator agent, after it analyses recordings, tags moments, summarises them and files the clip.</figcaption>
</figure>

Each run record keeps the Slack side in reach. The **Run History** drawer for a run shows the clip with its transcript, plus **View Clip Library** and **View Slack Alert** buttons.

<figure>

![A Run History drawer for an auto-triggered Content Curator run, showing a customer call clip with a video player, speaker timeline and transcript, and View Clip Library and View Slack Alert buttons at the top right.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_106_agent-detail_content-curator_runs-tab_run-record-drawer-open-hooli-corp-procurement-call-clip-view-clip-library-view-slack-alert.webp)

<figcaption>From any Content Curator run you can jump to the Slack alert it posted, or to the clip library where the moment was filed.</figcaption>
</figure>

### CRM Manager {#with-crm-manager}

[Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) sends a Slack notification after each activity when it finds [field updates for you to review](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/). RevOps also gets a weekly digest of time saved on manual CRM work.

### Deal Driver, Coach and Forecaster {#with-manager-agents}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) sends managers its alerts, briefs and summaries through Slack, email or the Oliv platform. [Oliv AI's Coach agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/coach/) sends reps weekly progress updates the same way. [Oliv AI's Forecaster agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/forecaster/) sends managers a weekly forecast summary with flagged deals.

### Olivia and custom agents {#with-olivia-custom}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) raises alerts and drives work through Slack, Teams or the Oliv product. A custom agent can use Slack as a tool too, with five actions: **Send Message to Slack**, **Get Slack Messages**, **Create Slack Channel**, **Invite Users to Channel** and **Upload File to Slack**. Each action's [run mode controls approval](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).

### Agents that start from Slack {#with-slack-triggers}

Some catalog agents start from a Slack message. Oliv AI's Product Release Messenger agent fires on a **Release announcement in #releases Slack channel**. It then uses **Monitor Slack channel**, **Read Slack message** and **Draft email** to turn release notes into customer updates for review.

<figure>

![Product Release Messenger's Overview tab: a goal of drafting customer product update emails when release notes are posted in Slack, one trigger chip for release announcements in the #releases Slack channel, and tools Monitor Slack channel, Read Slack message and Draft email.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_116_agent-detail_product-release-messenger_overview-tab_goal-releases-slack-trigger-tools-and-knowledge-cards.webp)

<figcaption>A post in a Slack channel can be the event that starts an agent. Here a release announcement becomes a customer update draft for the success team to review.</figcaption>
</figure>

Oliv AI's Comms Manager agent watches shared channels as well as email. One of its triggers is a **New message in a shared Teams or Slack Connect channel**, and its **Monitor Teams and Slack** tool reads those threads before it drafts a reply.

<figure>

![Comms Manager's Overview tab with a goal covering Gmail, Outlook, Microsoft Teams and Slack Connect, five trigger chips including New message in a shared Teams or Slack Connect channel, and six tool chips including Monitor Teams and Slack.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_091_agent-detail_comms-manager_overview-tab_goal-five-triggers-six-tools-watches-gmail-outlook-teams-slack-connect.webp)

<figcaption>Oliv AI's Comms Manager agent treats a customer's Slack Connect message like an email: it flags what needs a reply and drafts one for the seller to check.</figcaption>
</figure>

## Who uses the Slack integration, and how {#who-uses-it}

### Customer success and account management {#customer-success}

CSMs get a meeting summary after every customer call, so their notes are written for them. When a call holds an expansion signal, Gold Digger tells the account executive without the CSM posting a word. More on Oliv AI for [customer success](https://www.oliv.ai/customer-success) and [account management](https://www.oliv.ai/account-management).

### Account executives {#account-executives}

Account executives get the prep summary 10 minutes before each call and expansion signals from CSM calls. The whole selling day is set out in [running deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Sales managers {#sales-managers}

Managers get [Deal Driver's alerts and briefs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/) in Slack, plus Forecaster's weekly summary. The full set is on the [Deal Driver agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/).

### Enablement {#enablement}

Enablement leads point Content Curator at a team channel, so [new clips](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/apps/converse/clips/) reach reps as they're found. Read more on [Content Curator](https://www.oliv.ai/agents/content-curator).

## How Oliv AI compares for sales alerts in Slack {#compare}

Oliv AI posts three meeting messages in Slack on its own: tomorrow's meetings the afternoon before, a prep summary just ahead of each call and a summary right after it. Oliv AI is the only platform in this table that does all three.

Slack meeting messages, from each platform's public documentation:

| Platform | Meeting summary in Slack after each call | Prep summary in Slack before each meeting | Tomorrow's meetings sent the afternoon before |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Gong** | Partly ([call brief in stream notifications](https://help.gong.io/docs/catch-up-quickly-with-the-ai-briefer)) | Partly ([AI meeting prep, in app and mobile](https://help.gong.io/docs/monthly-updat)) | Partly ([daily digest email](https://help.gong.io/docs/about-the-emails-gong-sends-you)) |
| **Outreach** | Yes ([Kaia meeting summary notifications](https://support.outreach.io/support/solutions/articles/159000425264-configure-in-app-notifications-and-notifications-for-slack-in-outreach)) | Partly ([briefs from the Prep button](https://support.outreach.io/support/solutions/articles/159000425247-personalized-homepage-experience-overview)) | Partly ([daily digest email of tasks](https://support.outreach.io/support/solutions/articles/159000425431-how-to-set-up-outreach-activity-notifications-desktop-in-app-email-)) |
| **Fireflies** | Yes ([summaries posted to a channel](https://guide.fireflies.ai/articles/1671003178-how-to-set-up-the-fireflies-slack-integration)) | Partly ([prep email before recurring meetings](https://guide.fireflies.ai/articles/3878280311-meeting-prep-get-briefed-before-every-meeting)) | Partly ([daily digest of action items](https://guide.fireflies.ai/articles/7665784907-fireflies-settings-complete-overview-configuration-guide)) |
| **Avoma** | Partly ([meetings or snippets shared to Slack](https://help.avoma.com/enhance-collaboration-with-avomas-slack-integration)) | Not in docs | Not in docs |
| **Fathom** | Partly ([summaries to Slack via Zapier](https://help.fathom.video/en/articles/3239681)) | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for sales alerts in Slack {#compare-stronger}

- **Tomorrow's plan, in Slack.** Oliv posts the next day's meetings at 4 PM local time. Gong's daily digest is an email that [may include a personalized schedule of upcoming calls](https://help.gong.io/docs/about-the-emails-gong-sends-you). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **A summary nobody has to share.** Oliv sends the meeting summary as soon as the meeting ends, with next steps, talk time and a scorecard. Avoma's Slack integration lets you [share entire meetings or select snippets to any Slack channel](https://help.avoma.com/enhance-collaboration-with-avomas-slack-integration). Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Prep that arrives on its own.** Oliv's prep summary reaches Slack 10 minutes before each meeting. Gong describes its [AI meeting prep as being in one place, now on mobile](https://help.gong.io/docs/monthly-updat). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Meeting messages are personal.** The Help Center describes the three meeting messages as sent to you. It doesn't describe posting them to a shared channel.
- **Each agent picks its own path.** Content Curator posts to a configured channel. Gold Digger notifies the account executive. Check where each agent posts when you set it up.
- **Email copies are on by default.** The meeting messages go to your email as well as Slack.
- **Turning them off is one place.** Disable the automated messages from your **Profile Settings** page.
- **Slack Connect needs a yes.** If you connect through Slack Connect, nothing arrives until you accept Oliv's request.
- **Your calendar must be connected.** Calendar integration is required for Oliv to work.

## Common questions {#common-questions}

#### Do I need to set anything up after connecting Slack? {#faq-setup}

No. Once Oliv is connected to Slack, the three meeting messages start automatically, with no manual setup.

#### When does each message arrive? {#faq-timing}

Tomorrow's meetings arrive at 4 PM local time. The prep summary comes 10 minutes before each meeting. The meeting summary comes as soon as the meeting ends.

#### What's in the meeting summary? {#faq-summary-contents}

The meeting's title, date, time, participants and account, plus key takeaways: the next steps, talk time and a scorecard.

#### Can account alerts go to a channel my team shares? {#faq-shared-channel}

Content Curator posts to the channel you configure. A custom agent can send messages to Slack with its Slack tool. The three meeting messages are described as sent to each person.

#### How does an account executive hear about expansion on a CSM's call? {#faq-expansion}

Gold Digger sends the account executive a Slack notification right after the call ends. It includes the account, the quote and a recommended next step.

#### Can I turn the Slack messages off? {#faq-turn-off}

Yes. Go to your **Profile Settings** page and disable the automated messages.

#### Will I still get the messages by email? {#faq-email}

Yes, by default. The meeting messages are also sent to your email.

#### What's the difference between the Slack app and Slack Connect? {#faq-app-vs-connect}

With the app, you install Oliv in your workspace. With Slack Connect, Oliv sends you a request, and the messages start once you accept it.

#### Can I open the recording from Slack? {#faq-open-recording}

Yes. Click **Open Meeting** in the Slack message, and you go straight to that meeting in Oliv.

#### Can I stop the note taker joining from Slack? {#faq-stop-note-taker}

Yes. The meeting preparation summary in Slack includes a link that removes the note taker from that meeting.

#### Does it work with Microsoft Teams instead? {#faq-teams}

Microsoft Teams and Google Chat are listed as collaboration tools alongside Slack. For Teams, Oliv sends an invitation to a Teams shared channel.

## Related {#related}

- [Prepare for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/): the full brief behind a meeting.
- [Run deals as an account executive](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/): Slack messages across a selling day.
- [Olivia agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): the agent that works in Slack with you.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): the Slack tool in a custom agent.
- [Gold Digger on oliv.ai](https://www.oliv.ai/agents/gold-digger): expansion signals from customer calls.
- [Portfolio Manager on oliv.ai](https://www.oliv.ai/agents/portfolio-manager): account risk across the CS book.
- [Unify calls, email and Slack](https://www.oliv.ai/blog/revenue-intelligence-integration-revops-crm-slack-email): a RevOps integration blueprint.
- [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/): every tool Oliv AI connects to.
- [Oliv AI pricing](https://www.oliv.ai/pricing): plans and what each includes.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
