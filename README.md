# Lead-Opportunity-Management-Sales-# Dynamics 365 Sales — Lead to Opportunity Automation

A 90-second demo of an end-to-end Dynamics 365 + Power Automate workflow built 
for a fictional bicycle retailer ("MAXi") that needed to efficiently track 
and convert leads from multiple channels into paying customers.

## 📺 Demo

▶️ **[Watch on YouTube](<TODO: your YouTube URL>)**

[![Demo video](https://img.youtube.com/vi/VxpqTS1i0OQ/maxresdefault.jpg)](https://youtu.be/VxpqTS1i0OQ)
## 🎯 Scenario

MAXi, a bicycle retailer, needed to:
- Capture leads from Outlook and web forms
- Qualify leads consistently into Accounts, Contacts, and Opportunities
- Track each opportunity through Qualify → Develop → Propose → Close
- Prioritise high-value leads with AI
- Automate follow-up reminders and notify sellers in real time

## 🧩 Solution

Built using native Dynamics 365 Sales entities (Leads, Accounts, Contacts, 
Opportunities) extended with custom fields and Power Platform automation.

### Custom configuration
- Added **Bicycle Preference** and **Budget** custom fields to the Lead form
- Configured the **Lead-to-Opportunity** business process flow
- Set **Euro** as the default transaction currency

### AI and Automation
- **Predictive Lead Scoring** via Sales Insights — scores leads 0–100 with A–D grades
- **Sales Accelerator sequences** for automated follow-up cadences with conditional branching
- **Up Next widget** for suggested next actions on each record
- **Power Automate flow** sends an email notification to the lead owner the moment a lead is created

## 🛠️ Built with

- Microsoft Dynamics 365 Sales
- Power Automate (Dataverse + Office 365 Outlook connectors)
- Microsoft Dataverse
- Sales Insights
- Sales Hub model-driven app

## ✅ What was delivered

- Customised Lead form with Bicycle Preference and Budget fields
- 5 sample leads created; 2 qualified into Opportunities
- 3 opportunities advanced through the pipeline
- End-to-end automation demoed in 90 seconds (see video above)

## 📂 Power Automate Flow

Exported solution: [`notify-on-new-lead.zip`](./notify-on-new-lead.zip)

To reproduce:
1. Go to make.powerautomate.com → Solutions → Import solution
2. Upload the .zip
3. Map the Dataverse and Office 365 Outlook connections
4. Activate the flow


