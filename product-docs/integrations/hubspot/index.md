# HubSpot

How to connect Oliv AI to HubSpot, show Oliv AI fields on deal records, decide how updates are approved, and see what Oliv AI keeps current in your portal.

- Applies to: Sales leaders and teams that run on HubSpot
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/

Oliv AI connects to HubSpot so your deals, contacts and companies stay current without reps typing updates after every call. HubSpot remains your CRM, and Oliv AI works on top of it. Here you'll find the connection steps, how to show Oliv AI fields on a deal, and how approvals work.

## At a glance {#at-a-glance}

| | |
|---|---|
| **What it does** | Pulls HubSpot data into Oliv AI and fills it back with what customers said |
| **How you connect** | From the HubSpot integration in the Oliv AI web app, then share your HubSpot URL |
| **What it keeps current** | Deals, contacts, companies, activities, tasks and buying committee roles |
| **Approvals** | **Ask First** by default, or **Auto-Pilot** once you trust the updates |
| **Deal view** | Oliv AI fields appear in a card you add to the deal record |
| **What it needs** | A connected calendar, plus HubSpot itself |

## What the HubSpot integration is {#what-it-is}

The HubSpot integration links your portal to Oliv AI in both directions. Oliv AI pulls in information from HubSpot, and it fills auto-generated insights back in, so nobody on the team does manual updates. You don't need to replace HubSpot, because Oliv AI works with the CRM you already have.

The sync covers pipeline, fields, owners, close dates, stages and forecast categories. Writing back to HubSpot is the job of [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/).

### What changes in HubSpot {#what-changes}

- **Logged activity.** Meetings, calls and emails land on the right deal, contact and company.
- **New contacts and companies.** A person or company that shows up in a conversation, and isn't in HubSpot yet, gets a record.
- **New deals.** A deal is created when there are enough activity signals, with name, estimated close date, stage and amount where available.
- **Deal properties.** Close date, amount, stage and next steps are pre-mapped when you connect. Qualification fields such as MEDDPICC or BANT follow every call.
- **Tasks.** Next steps from meetings, calls and emails become tasks assigned to the right owner.
- **Buying committee.** Each contact's role on a deal, such as economic buyer, champion or blocker, is tracked as the deal moves.

## Why the HubSpot integration matters {#why-it-matters}

### What it's for {#what-its-for}

The HubSpot integration is for sales teams whose deal records fall behind their calls. It takes what buyers said and puts it on the deal, so the pipeline view matches the conversations.

### How it helps {#how-it-helps}

- **Deals you can trust on Monday.** Stage, amount and next steps update after each activity.
- **Stakeholders on the record.** Every new person from a call becomes a contact with a role on the deal.
- **Next steps that don't get lost.** Commitments from calls turn into HubSpot tasks with an owner.
- **Approval you control.** Reps see each proposed change beside the current CRM value, then accept or reject it.

### What happens without it {#without-it}

HubSpot only knows what a rep remembered to type. Deal properties go stale between calls, new stakeholders never become contacts, and next steps live in someone's notebook. The weekly pipeline meeting turns into an audit of missing fields instead of a talk about deals.

### Why buyers care {#why-buyers-care}

On a smaller team, the head of sales often owns HubSpot as well as the number. They care most at forecast time and in 1:1s, when deal records need to be right. Reps care because the follow-up admin after each call shrinks.

## The Oliv AI approach to the HubSpot integration {#approach}

{/* 5P */}

Imagine the head of sales at a twelve-person team: eight account executives and three SDRs. There is no RevOps hire yet, so she is also the HubSpot admin. Every Sunday night she opens the deals board and fixes amounts, stages and close dates before Monday's pipeline call.

A common fix is to make key deal properties required before a deal can change stage. Reps then paste a line or two from memory just to move the deal on. The board looks complete, but the values are often guesses, and she likely still rechecks the deals that matter most.

The information she needs already exists. It was said out loud on calls and written in emails during the week. What is missing is a step that turns those conversations into property values, with a person checking them before they count.

Oliv AI adds that step on top of HubSpot. Oliv AI's CRM Manager agent reads each meeting, call and email, then proposes updates to the deal, its contacts and its tasks. She starts every rep on **Ask First**, so reps **Accept** or **Reject** each proposal on the deal's **CRM Updates** tab.

Nothing reaches HubSpot until a rep approves it, and every proposal shows the current CRM value beside the suggested one. Approval before writing is one of the points covered in How the HubSpot integration compares, below.

## Connect HubSpot {#connect-hubspot}

1. Sign in to the Oliv AI web app and visit the HubSpot integration, at `web.oliv.ai/hubspot/connect`.
2. Share your HubSpot URL with the Oliv AI admin through Intercom in the Oliv AI app.
3. Connect your Gmail or Outlook calendar. Oliv AI needs a calendar integration to take notes in meetings.

Once you're connected, **Settings** › **Revenue Process** has an **Import Pipeline from CRM** button that pulls your existing stages into Oliv AI, one tab per sales motion.

<figure>

![The Revenue process settings page on the Enterprise Sales tab, with Mid-Market sales and Customer Success tabs, a blue Import Pipeline from CRM button, and a stage table showing type, probability, forecast category, outcomes and entry criteria.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/settings/oliv-ai_260_settings_revenue-process_enterprise-sales-tab_stage-table-with-type-probability-forecast-category-outcomes-and-import-pipeline-from-crm.webp)

<figcaption>After HubSpot is connected, Import Pipeline from CRM brings your deal stages into Oliv AI, so agents and the forecast use the same pipeline as your portal.</figcaption>
</figure>

Your core deal properties are mapped on connection and start filling from day one. If you track properties unique to your process, Oliv AI's team [maps them for you during onboarding](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/).

## Show Oliv AI fields on HubSpot deals {#show-fields-on-deals}

Oliv AI's help center walks through adding a custom property and a card, so Oliv AI's data sits on the deal record.

1. In HubSpot, click **Settings** at the top of the page.
2. Under **Data Management**, select **Properties**, then click **Create Property**.
3. Name the property, for example "Oliv: Pain Points & Needs", and set the object type to **Deal**.
4. Choose **Rich Text** as the field type, which suits most Oliv AI fields. Click **Preview**, then **Create**.
5. Back in **Settings**, under **Data Management**, open **Objects** and go to **Record Customization**.
6. Click the default view, click **Add Cards**, then **Create Card**.
7. Name the card, select the property you created, and click **Save and exit**.
8. Open any deal to check the field. Once Oliv AI captures relevant information, it fills the field automatically.

## Decide how updates are approved {#approve-updates}

Out of the box, Oliv AI's CRM Manager agent holds every suggestion for review before it touches HubSpot. There are two control modes:

- **Ask First.** Each update waits for a rep before anything is written to HubSpot.
- **Auto-Pilot.** Updates nobody reviewed are applied on their own, so deals stay current with no one acting.

After a call, the rep gets a [Slack message](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/), or a note in their preferred channel, saying updates were found. On the deal, the **CRM Updates** tab lists each proposed change under **AI Suggestions**. The suggested value sits in its own field above the **Current Value**, and the choices are **Accept** or **Reject**. **AI Updates** holds changes already applied, and **Updates History** keeps the record.

<figure>

![A deal drawer on the CRM Updates tab, with an index of AI Suggestions, AI Updates and Updates History, and suggestion cards for Use Case and Primary Contact, each showing the suggested value, the Current Value, and Accept and Reject buttons.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/records-deals/oliv-ai_225_records-deals_deal-detail-drawer_crm-updates-tab_ai-suggestions-4-accept-reject-use-case-primary-contact-competitor-notes.webp)

<figcaption>This is where a rep approves HubSpot updates on Ask First: each suggestion sits beside the value HubSpot holds now, and nothing is written until the rep accepts it.</figcaption>
</figure>

Each meeting has a **CRM Updates** tab of its own. It lists what was written after the call, such as **Account Updated** or **Contact Created**, and holds a stage move as a **Pending Update** until you press **Update Deal**.

<figure>

![A meeting details drawer on the CRM Updates tab: a timeline with Account Updated, Pending Update: Move to Proposal with an Update Deal button, Opportunity Updated: BANT Scorecard and two Contact Created entries, each with a View link.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/activities-meetings/oliv-ai_246_activities-meetings_meeting-details-drawer_crm-updates-tab_account-deal-bant-and-contact-updates-with-pending-stage-move.webp)

<figcaption>After a call, the meeting's CRM Updates timeline shows what reached HubSpot and what is still pending, with a link to each record that changed.</figcaption>
</figure>

Reps with open tasks or unverified deal updates get an end-of-day reminder. If updates stay undone past a set window, deals can be deferred or flagged as closed-lost, and your org chooses whether that happens. When accuracy is good enough, the person who owns HubSpot confirms the move to auto mode.

## How the HubSpot integration works with agents {#works-with}

### CRM Manager {#with-crm-manager}

Oliv AI's CRM Manager agent does every write, so updates show up in the HubSpot workflows, reports and dashboards you already use. The [CRM Manager overview](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) covers its full job.

### Meeting Assistant {#with-meeting-assistant}

[Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) [suggests field updates after each call](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/record-and-follow-up/). CRM Manager then reviews that call context and pushes approved changes into HubSpot. Briefs before a call draw on the contacts and companies kept current here, as in [preparing for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Deal Driver {#with-deal-driver}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) reads deal stage history and field values for [pipeline reviews](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/run-a-pipeline-review/). Task reminders and end-of-day nudges belong to Deal Driver, while creating and logging tasks stays with CRM Manager.

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) reads what is already in HubSpot, messy data included. Ask her about a deal and she works from the same records.

### Agents you build {#with-custom-agents}

HubSpot appears in the **Add Tool** catalogue with 32 tools in six groups: **Lookup / Search**, **Create / Update**, **Associations**, **Activities**, **Marketing** and **Utility**. They run from **Find Deal** and **Update Deal Stage & Dates** to **Enroll Contact in Sequence** and **Submit Form**.

<figure>

![The full HubSpot tool list in the Add Tool catalogue, six category bars with 32 tool cards: Lookup / Search, Create / Update, Associations, Activities, Marketing and Utility, from Find Company down to Get Recently Modified Records.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_055_agent-detail_multi-threader_add-tool-catalog_hubspot-complete-list-of-32-tools-in-6-categories-lookup-create-associations-activities-marketing-utility_full-length.webp)

<figcaption>Every action an agent you build can take in HubSpot, including the Marketing group for lists and forms. Each tool you add gets its own run mode.</figcaption>
</figure>

HubSpot is also listed under **Most popular** when you add a trigger, so a change in your portal can start an agent.

<figure>

![The Triggers picker opened from Add Trigger, with a Search triggers box and a Most popular group of 11 systems, where Hubspot appears beside Salesforce, Google Calendar, Google Mail and Microsoft Outlook.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_065_agent-detail_multi-threader_triggers-tab_add-trigger-picker-modal_search-triggers-most-popular-outlook-google-mail-calendar-salesforce-hubspot-zoominfo-linkedin.webp)

<figcaption>HubSpot is one of the most popular trigger sources, which lets an event in your portal start an agent without anyone pressing Run Agent.</figcaption>
</figure>

How each tool asks for approval is explained in [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).

## Who uses the HubSpot integration, and how {#who-uses-it}

### Sales leaders {#sales-leaders}

A head of sales opens the deals board on Monday and finds stages, amounts and next steps already updated from last week's calls. The **AI Suggestions** count on each deal's **CRM Updates** tab shows what still needs review. More on Oliv AI for [sales managers](https://www.oliv.ai/sales-managers).

### Account executives {#account-executives}

An AE finishes a demo where a new economic buyer joined late. By the next call, that person is a contact with a role on the deal and the next step is logged. See how an AE [runs deals day to day](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

### Sales development {#sales-development}

An SDR books a first meeting with three people from a target company. Each attendee who isn't in HubSpot becomes a contact, and the meeting is logged against the company. More on Oliv AI for [sales development teams](https://www.oliv.ai/sales-development).

### Account management {#account-management}

An account manager's renewal and check-in calls update the company record the same way sales calls do. Changes to the stakeholder map show up on the record before the next renewal talk. More on Oliv AI for [account management](https://www.oliv.ai/account-management).

## How the HubSpot integration compares {#compare}

Several meeting tools can push notes or properties into HubSpot. Oliv AI also holds each update for approval, tracks each contact's role on the deal, and reminds reps about updates they haven't reviewed. Oliv AI is the only platform in this table that does all four.

HubSpot sync features, from each platform's public documentation:

| Platform | Deal properties filled from calls | Approval before anything reaches HubSpot | Buying committee roles on each deal | Reminders for pending updates |
|---|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes | Yes |
| **Gong** | Yes ([AI data fields mapped to your CRM](https://help.gong.io/docs/monthly-updat)) | Automatic ([fields update without rep action](https://help.gong.io/docs/ai-data-extractor)) | Not in docs | Not in docs |
| **Avoma** | Partly ([field mapping needs Business license](https://help.avoma.com/crm-sync-hubspot)) | Not in docs | Not in docs | Not in docs |
| **Fireflies** | Yes ([Autofill CRM for HubSpot](https://guide.fireflies.ai/articles/3882093831-autofill-crm-hubspot-sync-meeting-data-to-contacts-company-and-deals)) | Yes ([nothing sent until you approve](https://guide.fireflies.ai/articles/3882093831-autofill-crm-hubspot-sync-meeting-data-to-contacts-company-and-deals)) | Not in docs | Not in docs |
| **Fathom** | Partly ([Business and Enterprise plans only](https://help.fathom.video/en/articles/448832)) | Not in docs | Not in docs | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for the HubSpot integration {#compare-stronger}

- **Updates follow each activity.** Oliv AI's CRM Manager agent proposes changes after every meeting, call and email and notifies the rep. Gong's help center notes that [exporting Gong data to HubSpot can take up to six hours](https://help.gong.io/docs/export-data-to-hubspot). Compare [Oliv AI vs Gong](https://www.oliv.ai/blog/gong-vs-oliv).
- **Your own fields, mapped for you.** Oliv AI's team maps the properties unique to your process during onboarding. Gong documents that its [AI Data Extractor can only export to an existing CRM field](https://help.gong.io/docs/ai-data-extractor). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **Standard fields from day one.** Core deal properties are pre-mapped on connection and fill from day one. Avoma lists a [HubSpot Business license for users of field mapping](https://help.avoma.com/crm-sync-hubspot). Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Setup goes through Oliv AI's team.** After visiting the integration, you share your HubSpot URL with the Oliv AI admin through Intercom.
- **A calendar is required.** Without a calendar integration, Oliv AI can't take notes during meetings.
- **The deal card is yours to add.** Oliv AI fields show on the deal view once you create the property and card in HubSpot.
- **[Custom properties are mapped at onboarding](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/).** There's no self-serve mapping screen for them.
- **Auto mode waits for you.** Updates stay on review until the HubSpot owner confirms the switch.
- **Removing the integration is a message.** Send Oliv AI a message through Intercom in the Oliv AI app.

## Common questions {#common-questions}

#### Do we have to move off HubSpot to use Oliv AI? {#faq-replace}

No. Oliv AI works with your existing CRM, brings the context together and [keeps HubSpot updated](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/keep-the-crm-updated/). HubSpot stays your system of record.

#### How do we connect HubSpot? {#faq-connect}

Visit the HubSpot integration in the Oliv AI web app, then share your HubSpot URL with the Oliv AI admin through Intercom in the Oliv AI app.

#### Where do Oliv AI's insights show up on a deal? {#faq-where-insights}

In a custom property you create, shown in a card on the deal view. The help center suggests a name like "Oliv: Pain Points & Needs".

#### Which field type should an Oliv AI property use? {#faq-field-type}

Rich Text. Oliv AI's guide says most Oliv fields work best as Rich Text, with **Deal** as the object type.

#### Do reps have to approve every change? {#faq-approval}

At first, yes. Every suggestion surfaces for review by default. Once the team trusts the updates, you can switch to **Auto-Pilot** for hands-free changes.

#### What if a rep ignores pending updates? {#faq-ignored-updates}

They get end-of-day reminders. If updates aren't completed within a set window, deals can be deferred or flagged as closed-lost, depending on how your org configures it.

#### Will Oliv AI create contacts we don't have yet? {#faq-new-contacts}

Yes. When a person or company in a meeting, call or email isn't in HubSpot, Oliv AI's CRM Manager agent creates the record and enriches it.

#### Our HubSpot data is messy. Is that a problem? {#faq-messy-data}

No. CRM Manager works with unclean data and normalizes it as it goes, resolving duplicates and filling gaps in real time and in batch.

#### Can a wrong update be undone? {#faq-wrong-update}

Every suggestion shows the current value next to the proposed one, and you can reject it before it's written. Changes already applied are listed under **AI Updates**, and **Updates History** keeps the record.

#### Does it work for customer calls after the sale? {#faq-after-sale}

Yes. Activity tracking covers renewals, QBRs and customer success check-ins as well as sales calls.

#### Which other CRMs does Oliv AI support? {#faq-other-crms}

[Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/) and Zoho, alongside HubSpot, out of the box. Other CRMs are available on request.

#### How is Oliv AI priced for a team on HubSpot? {#faq-pricing}

Plans are assigned by role, so each person gets the apps they need. For current plans, see [Oliv AI pricing](https://www.oliv.ai/pricing).

## Related {#related}

- [How the Context Graph enriches your CRM](https://www.oliv.ai/blog/bi-directional-crm-sync-ai): why Oliv AI adds to HubSpot records instead of replacing them.
- [Oliv AI for sales managers, day to day](https://www.oliv.ai/blog/oliv-ai-sales-manager-daily-use-guide-features): how a manager uses agents to keep the CRM current.
- [The RevOps integration blueprint](https://www.oliv.ai/blog/revenue-intelligence-integration-revops-crm-slack-email): connecting calls, email and Slack to the CRM.
- [Sales call notes software](https://www.oliv.ai/blog/sales-call-notes): what good call notes in a CRM look like.
- [Oliv AI for sales teams](https://www.oliv.ai/sales): how agents support account executives and their managers.
- [Oliv AI integrations](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/): every tool Oliv AI connects to besides HubSpot.
- [The Context Graph](https://www.oliv.ai/context-graph): how Oliv AI maps activity to the right deal and company.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
