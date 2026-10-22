# Set up CRM field mapping

How to map your team's standard, methodology and custom opportunity fields so Oliv AI's CRM Manager agent writes each update to the right place, then review and automate it.

- Applies to: Revenue operations admins connecting Salesforce, HubSpot or Zoho
- Status: Live
- Verified: 2026-10-22
- Canonical page: https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/field-mapping/

Field mapping decides which CRM field each update from [Oliv AI's CRM Manager agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) lands in. Standard fields are pre-mapped when you connect your CRM, and Oliv AI's team maps your custom fields during onboarding. This guide walks a RevOps admin through preparing the field list, connecting the CRM, checking the first updates and switching to automatic writes.

## At a glance {#at-a-glance}

| | |
|---|---|
| **Who does it** | A RevOps admin, with Oliv AI's onboarding team |
| **CRMs** | Salesforce, HubSpot and Zoho out of the box |
| **Pre-mapped** | Close date, deal amount, stage, next steps, last activity date |
| **Mapped for you** | Methodology fields and your custom fields |
| **First mode** | **Ask First**, with each suggestion beside the current value on the deal's **CRM Updates** tab |
| **Then** | **Auto-Pilot**, once RevOps confirms accuracy |

## Before you begin {#before-you-begin}

- **Have your CRM ready to connect.** You connect it during onboarding.
- **Know which methodology you run.** **Settings › Qualification Framework** lists MEDDPICC, MEDDIC, SPICED, BANT and DRIVE, with one marked **Active**.
- **List your custom opportunity fields.** Note what each one means and which reports read it.
- **Plan a short review period.** Reps take part while the team checks early updates.
- **For HubSpot, have access to HubSpot Settings.** You may need to create a custom property for Oliv data.

## Step 1: List the fields you want kept current {#step-1-list-fields}

CRM Manager fills three kinds of field. Sort your list into them before you connect anything.

1. **Standard fields.** Close date, deal amount, stage, next steps and last activity date. These are pre-mapped and fill from day one.
2. **Methodology fields.** The fields your qualification framework uses. Values come from Oliv AI's Deal Insights layer, and CRM Manager writes them and keeps them current.
3. **Custom fields.** Anything unique to your process, such as a deck status, use case, competition or integration type.

To see the standard fields as reps will, open a deal's **Details** tab. Its section index runs from **Overview** and **Next Steps** to **Opportunity and Risks**, **Adoption**, **Success Plan** and **Marketing Opportunity**.

<figure>

![A deal's Details tab, with a section index on the left and the Overview section open. Paired fields show Deal Name, Close Date, Amount, Stage, Pipeline, Deal Owner, Priority and Forecast Category, and a Next Step field starts the Next Steps section below.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/records-deals/oliv-ai_219_records-deals_deal-detail-drawer_details-tab_overview-fields-next-step-section-index-dunder-mifflin-scranton.webp)

<figcaption>Use the Details tab as your checklist for Step 1. The standard fields are already here; note which custom fields belong in the later sections.</figcaption>
</figure>

For methodology fields, open **Settings › Qualification Framework**. Each criterion of the previewed framework shows a **Supporting fields** count, the CRM fields that back it.

<figure>

![Settings, Qualification Framework, with MEDDPICC marked Active and MEDDIC selected for preview among SPICED, BANT and DRIVE tabs. The table lists criteria such as Metrics, Economic Buyer and Champion, each with a description, a 0-6 scoring chip and a supporting fields count.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/settings/oliv-ai_261_settings_qualification-framework_meddic-tab-selected-meddpicc-active_criteria-table-with-0-6-scoring-and-supporting-fields.webp)

<figcaption>The supporting fields count tells you how many CRM fields each criterion needs. Add those fields to your list so framework scores have somewhere to land.</figcaption>
</figure>

The [sales methodology overview](https://www.oliv.ai/sales-methodology) explains how framework fields fill from calls.

## Step 2: Connect your CRM {#step-2-connect}

1. Use the one-click integration for [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho. Your pipeline and fields sync straight away.
2. For HubSpot, visit the HubSpot integration in the Oliv AI web app. Share your HubSpot URL with the Oliv AI admin through Intercom in the Oliv AI interface.
3. To connect email and phone as well, add those integrations. They widen activity coverage beyond meetings.
4. Open **Settings › Revenue Process** and check your stages. Each sales motion has its own tab, and **Import Pipeline from CRM** pulls in the stages from the connected CRM. Every stage carries a **Type**, a **Probability** and a **Forecast Category**.

<figure>

![Settings, Revenue process page with tabs for Enterprise Sales, Mid-Market sales and Customer Success, a Search box and an Import Pipeline from CRM button. The stage table lists seven stages with Type, Probability, Forecast Category, Outcomes and Entry Criteria columns.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/settings/oliv-ai_260_settings_revenue-process_enterprise-sales-tab_stage-table-with-type-probability-forecast-category-outcomes-and-import-pipeline-from-crm.webp)

<figcaption>Stage values are the first mapping to confirm. Import them from the CRM here, then check that each stage rolls into the forecast category your reports expect.</figcaption>
</figure>

The [integrations directory](https://www.oliv.ai/integrations) lists the apps you can connect.

## Step 3: Create a HubSpot property for Oliv data {#step-3-hubspot-property}

Use this step when you want a piece of Oliv data, such as pain points, in its own HubSpot field.

1. In HubSpot, click **Settings** at the top of the page.
2. Under **Data Management**, select **Properties**, then click **Create Property**.
3. Name the property, for example **Oliv: Pain Points & Needs**, and set the object type to **Deal**.
4. Choose **Rich Text** as the field type, since most Oliv fields work best that way. Click **Preview**, then **Create**.
5. Back in **Settings**, go to **Objects**, then **Record Customization**, and open the default view.
6. Click **Add Cards**, then **Create Card**. Name the card, select your new property and click **Save and exit**.
7. Open any deal to check the field shows. Once Oliv captures relevant information, it fills the field automatically.

## Step 4: Hand your field list to Oliv AI's team {#step-4-mapping-service}

Oliv AI's team configures custom fields during onboarding, as a service. It isn't a task RevOps does alone. Share the list from Step 1, including any HubSpot properties you created in Step 3.

Once a custom field is mapped, CRM Manager updates it in the same way as standard and methodology fields. The [RevOps implementation guide](https://www.oliv.ai/blog/oliv-ai-revops-implementation-admin-guide) covers the rest of onboarding.

## Step 5: Check the first updates in Ask First {#step-5-review}

1. **Leave CRM Manager on Ask First.** You review each update before it's written.
2. **Watch for the notification.** After every activity, reps get a [Slack](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/slack/) or preferred-channel message: "I found updates for X fields, review here."
3. **Open the deal's CRM Updates tab.** Under **AI Suggestions**, each card names the field, holds the suggested value and shows "Current Value" below it.
4. **Accept or reject.** Reps press **Accept** or **Reject** on each field.
5. **Check the counts.** The index shows counts for **AI Suggestions**, **AI Updates** and **Updates History**, so you can see what's waiting and what already changed.

<figure>

![A deal's CRM Updates tab with an index of AI Suggestions, AI Updates and Updates History, each with a count. Cards for Use Case and Primary Contact show the suggested value, a Current Value line, and green Accept and outlined Reject buttons.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/records-deals/oliv-ai_225_records-deals_deal-detail-drawer_crm-updates-tab_ai-suggestions-4-accept-reject-use-case-primary-contact-competitor-notes.webp)

<figcaption>This is where you check your first mapped fields. A custom field like Use Case shows up as a suggestion beside its current value, so a wrong mapping is easy to spot.</figcaption>
</figure>

The meeting's own **CRM Updates** tab says what changed and why, for example a stage move held as **Pending Update** until someone presses **Update Deal**.

If a field keeps landing in the wrong place, raise it with Oliv AI's team before you move on. Reps see these reviews as part of [running their deals](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/use-cases/ae-run-deals/).

## Step 6: Switch to Auto-Pilot {#step-6-auto-pilot}

Once accuracy thresholds are met, RevOps confirms the switch to auto mode. On **Auto-Pilot**, unreviewed updates apply automatically and the pipeline stays current without anyone acting.

Teams on the weekly cadence get a middle path. Reps receive pending CRM suggestions on Friday morning, and unreviewed ones are accepted automatically on Sunday night. The same approval idea applies to other agents, as described in [agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/).

## Step 7: Backfill old records and watch the digest {#step-7-backfill}

1. **Backfill existing deals.** Ask CRM Manager in plain language, for example "Backfill MEDDPICC fields across the pipeline."
2. **Clean up as needed.** It can also find duplicate accounts, rebuild broken account hierarchies and clean unassigned contacts.
3. **Read the weekly governance summary.** It lists suggestions made, fields updated, reverts, time saved, acceptance rate by rep and flags that need review.

## What field mapping in Oliv AI is {#what-it-is}

Field mapping is the link between what Oliv AI learns from a conversation and the CRM field that stores it. Oliv AI's CRM Manager agent writes to [Salesforce](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/salesforce/), [HubSpot](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/integrations/hubspot/) or Zoho, and every update flows into your existing workflows, reports and dashboards. Oliv AI works on top of your CRM and doesn't replace it.

Mapping covers more than deal fields. CRM Manager also logs every meeting, call and email against the right account, contact and opportunity.

An agent's **Data** tab shows the other side of the link: the CRM objects and fields an agent can read. Under **Sources**, Salesforce lists **Deals**, **Contacts**, **Accounts** and **Leads**, and each field comes with a plain-language description.

<figure>

![An agent's Data tab with a Sources list showing Salesforce expanded to Deals, Contacts, Accounts and Leads, plus Oliv AI, Slack and ZoomInfo. The Deals panel lists field cards such as Deal ID, Name, Account, OwnerId / Owner and StageName, each with a short description.](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/images/screens/agent-detail/oliv-ai_046_agent-detail_multi-threader_data-tab_sources-list-salesforce-deals-selected-deal-id-name-account-owner-stagename-fields.webp)

<figcaption>Field definitions are what agents read back from your CRM. Clear descriptions here mean every agent understands a mapped field the same way.</figcaption>
</figure>

For a recorded call, CRM Manager attaches an AI-generated summary and the full call transcript to the Opportunity record. The [CRM Manager agent page](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/crm-manager/) shows that example in full.

## Why field mapping matters {#why-it-matters}

### What it's for {#what-its-for}

Field mapping is for RevOps teams whose reports depend on custom fields that reps rarely fill. It points each piece of call data at the one field where your reports expect it.

### How it helps {#how-it-helps}

- **Custom fields stay filled.** Once mapped, they update like stage and close date.
- **No rules to maintain.** CRM Manager reasons from context instead of rules someone has to write and update.
- **Every value can be checked.** Each suggestion sits beside the current value, and the meeting's update says why it changed.
- **Methodology stays complete.** Framework fields fill from every call, and old deals can be backfilled.

### What happens without it {#without-it}

Custom fields stay blank until someone chases them. Reports that rely on use case, competition or deal status show gaps, and leaders stop trusting them. Pipeline reviews fall back on whatever reps remember to type. Methodology fields sit half empty until someone chases them before a forecast call.

### Why buyers care {#why-buyers-care}

The RevOps lead owns this decision, because the reports they build depend on those fields. It matters most during onboarding, and again whenever the team adds a field for a new process or methodology. Sales leaders feel it later, when the reports they read every week finally show complete data.

## The Oliv AI approach to field mapping {#approach}

{/* 5P */}

Take a RevOps admin whose opportunity record carries a dozen custom fields beyond the standard set. There is a deck status, a use case, a competitor field and an integration type. Each one feeds a report the CRO opens every Monday, and two of them decide how deals are routed to solutions engineers.

Most teams fill fields like these in one of two ways. Either reps remember to type them, or an admin writes rules to fill them. Rules tend to break when the schema changes, and a field nobody fills quietly drops out of the reports.

The information behind those fields is usually spoken on calls already. A buyer names a competitor or describes the integration they need, often in the first ten minutes. What's left is pointing each piece of data at the right field once, so every later update lands there.

Oliv AI takes that job on during onboarding. Its team maps your custom fields as a service, and the CRM Manager agent then updates them from every meeting, call and email. It treats them exactly as it treats stage, close date and methodology fields.

While you're on **Ask First**, every suggestion sits next to the field's present value on the deal's **CRM Updates** tab. Nothing reaches the CRM until a rep presses **Accept**. The reason given for each update is covered in How Oliv AI compares for CRM field mapping, below.

## How field mapping works with other agents {#works-with}

### Oliver {#with-oliver}

[Oliv AI's Oliver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/oliver/) creates or modifies CRM field mappings when new tracking requirements emerge. When your process adds a field, Oliver works through CRM Manager to add it. An Oliver proposal can add a new Opportunity field that CRM Manager fills from meeting and email activity, with a 90-day backfill.

### Meeting Assistant {#with-meeting-assistant}

[Oliv AI's Meeting Assistant agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/meeting-assistant/) proposes field updates from every call. CRM Manager reviews the same call context and pushes approved changes into the mapped fields. The brief reps read before a call draws on those records, as shown in [preparing for a meeting](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/workflows/prepare-for-a-meeting/).

### Deal Driver {#with-deal-driver}

[Oliv AI's Deal Driver agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/) reads CRM field values and stage history for pipeline review and risk flags. Well-mapped fields make its alerts more accurate.

### Olivia {#with-olivia}

[Oliv AI's Olivia agent](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/) answers reps' questions about deals and accounts from the same records. Current fields mean current answers.

## Who uses field mapping, and how {#who-uses-it}

### Revenue operations admins {#revops-admins}

The RevOps admin prepares the field list, checks early updates and confirms the switch to auto mode. The weekly governance summary shows each rep's acceptance rate. More on Oliv AI for [revenue operations](https://www.oliv.ai/revops).

### Account executives {#account-executives}

AEs review proposed updates during the Ask First period, then mostly stop touching the fields. Their opportunity records stay current from their calls. See Oliv AI for [account executives](https://www.oliv.ai/account-executives).

### Sales managers {#sales-managers}

Managers watch the **AI Suggestions** count on each deal's **CRM Updates** tab. Custom fields they use in one-on-ones fill from real activity instead of reminders. Read about Oliv AI for [sales managers](https://www.oliv.ai/sales-managers).

### Customer success managers {#customer-success}

CS teams map renewal and account fields too, because CRM Manager covers onboarding, QBRs and renewals. Learn more about Oliv AI for [customer success](https://www.oliv.ai/customer-success).

## How Oliv AI compares for CRM field mapping {#compare}

Most tools here can fill custom CRM fields from calls once an admin sets up the mapping. Oliv AI's team does the mapping for you during onboarding, and every update says why it was made. Oliv AI is the only platform in this table that does all three.

Field mapping features, from each platform's public documentation:

| Platform | Custom fields filled from calls | Mapping set up for you at onboarding | Reason shown for each update |
|---|---|---|---|
| **Oliv AI** | Yes | Yes | Yes |
| **Outreach** | Yes ([Deal Agent field updates](https://support.outreach.io/support/solutions/articles/159000432550-deal-agent-faq)) | Admin task | Yes ([transcript excerpt and timestamp](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview)) |
| **Gong** | Yes ([AI data fields mapped to your CRM](https://help.gong.io/docs/monthly-updat)) | Admin task ([Business admin feature](https://help.gong.io/docs/ai-data-extractor)) | Partly ([evidence snippets on playbook notes](https://help.gong.io/docs/monthly-updat)) |
| **Avoma** | Yes ([CRM fields mapped to Smart Topics](https://help.avoma.com/crm-field-mapping-and-pipeline-faqs)) | Admin task ([needs an Avoma admin](https://help.avoma.com/mapping-crm-fields)) | Partly ([evidence in deal methodology](https://help.avoma.com/configure-deal-methodology)) |
| **Fireflies** | Yes ([custom fields in Autofill CRM](https://guide.fireflies.ai/articles/1729159683-autofill-crm-for-salesforce-automatically-extract-and-sync-meeting-data-to-contacts-accounts-and-opportunities)) | Partly ([suggested mappings to review](https://guide.fireflies.ai/articles/1729159683-autofill-crm-for-salesforce-automatically-extract-and-sync-meeting-data-to-contacts-accounts-and-opportunities)) | Not in docs |
| **Fathom** | Yes ([summary sections mapped to fields](https://help.fathom.video/en/articles/448640)) | Admin task ([set by a team admin](https://help.fathom.video/en/articles/448640)) | Not in docs |

*Yes: documented and built in. Partly: documented with a limit, shown in brackets. Not in docs: not found in the vendor's public documentation.*

### Why Oliv AI is the stronger choice for CRM field mapping {#compare-stronger}

- **Mapping done with you, not by you.** Oliv AI's team configures custom fields during onboarding. Avoma's mapping guide says [you must be an Avoma admin](https://help.avoma.com/mapping-crm-fields) and have Smart Topics configured first. Compare [Oliv AI vs Avoma](https://www.oliv.ai/blog/avoma-vs-oliv-ai).
- **Review before anything is overwritten.** On Ask First, CRM Manager shows the present value beside each proposal. Gong's extractor notes that [when new or better information is found, the previous value is overwritten](https://help.gong.io/docs/ai-data-extractor). See [Oliv AI as a Gong alternative](https://www.oliv.ai/gong-alternative).
- **No prompts to tune per field.** Oliv AI's team sets up each custom field. Outreach advises admins to [share exactly what evidence the AI should look for](https://support.outreach.io/support/solutions/articles/159000425187-deal-agent-overview) when writing Deal Agent prompts. Read [how Gong and Outreach compare](https://www.oliv.ai/blog/gong-vs-outreach).

*Competitor details checked against each vendor's public documentation on 21 October 2026. Features and plans change, so confirm with the vendor before you decide.*

## Limits and things to know {#limits}

- **Custom fields need onboarding.** Oliv AI's team maps them, so a new field goes through that team or through Oliver.
- **HubSpot properties come first.** To store Oliv data in its own HubSpot field, create the property before mapping.
- **Auto mode needs a decision.** RevOps confirms the switch once accuracy thresholds are met.
- **Values come from Deal Insights.** CRM Manager writes what that layer produces and doesn't decide values from scratch.
- **Other CRMs are by request.** Salesforce, HubSpot and Zoho work out of the box.

## Common questions {#common-questions}

#### Which fields are mapped automatically? {#faq-pre-mapped}

Standard fields are pre-mapped when you connect your CRM: close date, deal amount, stage, next steps and last activity date. They fill from day one.

#### Who maps our custom fields? {#faq-who-maps}

Oliv AI's team configures custom fields during onboarding as a service. You provide the field list and what each field means.

#### Do custom fields update differently from standard fields? {#faq-custom-vs-standard}

No. Once a custom field is mapped, CRM Manager updates it in the same way as standard and methodology fields.

#### Which methodologies can be mapped? {#faq-methodologies}

MEDDPICC, MEDDIC, SPICED, BANT and DRIVE, listed in **Settings › Qualification Framework**. The [guide to MEDDIC](https://www.oliv.ai/blog/meddic-sales-methodology) explains its fields.

#### What field type should a HubSpot property for Oliv data use? {#faq-hubspot-type}

Most Oliv fields work best as **Rich Text**. Set the object type to **Deal** so the property appears with deal information.

#### Can I check a value before it's written? {#faq-check-value}

Yes. On **Ask First**, every suggested update waits on the deal's **CRM Updates** tab, beside the field's current value.

#### What if a mapped field gets a wrong value? {#faq-wrong-value}

Reject the suggestion before it's written. **Updates History** on the deal's **CRM Updates** tab keeps the record of changes.

#### Can we fill fields on old deals? {#faq-backfill}

Yes. Ask CRM Manager to run a batch job, such as backfilling MEDDPICC fields across the pipeline.

#### Do meeting notes go to the CRM too? {#faq-meeting-notes}

Yes. In the live page example, an AI-generated summary and the full call transcript are attached to the Opportunity record.

#### How do I know the mapping is working? {#faq-is-it-working}

Read the weekly governance summary. It shows fields updated, reverts and acceptance rate by rep.

## Related {#related}

- [CRM Manager overview on oliv.ai](https://www.oliv.ai/crm-manager): how records stay current from real activity.
- [Autonomous CRM hygiene for RevOps](https://www.oliv.ai/blog/crm-data-quality-automation-revops): planning clean-up and backfill jobs.
- [Two-way CRM sync](https://www.oliv.ai/blog/bi-directional-crm-sync-ai): enriching the CRM without replacing it.
- [Integrating sales automation in your CRM](https://www.oliv.ai/blog/how-to-integrate-sales-automation-in-crm): connecting tools to the CRM.
- [Agent tools and run modes](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/builder/tools-and-run-modes/): approval choices for agent actions.
- [The Olivia agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/olivia/): asking about deals the mapped fields describe.
- [Deal Driver agent docs](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/agents/deal-driver/): manager alerts that read your fields.
- [Oliv AI product documentation](https://maximuslabs-ai.github.io/oliv-ai-product-docs-v3/product-docs/): every documented agent and feature.
