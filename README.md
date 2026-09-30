*Intuz — Your automation partner, one workflow at a time.*

<p align="center">
  <picture>
    <img alt="Banner Image" src="https://github.com/user-attachments/assets/210f97fc-0fce-404a-b647-7dfe1302cd37" />
  </picture>
</p>

[Intuz](https://www.intuz.com) helps organizations orchestrate AI, automation, and enterprise systems through scalable workflows. Our repository showcases proven implementations across healthcare, operations, customer support, document processing, sales, and back-office functions, enabling teams to accelerate automation initiatives without starting from scratch.

[N8N Creator](https://n8n.io/creators/intuz/) · [Workflow Automation](https://www.intuz.com/workflow-automation-services/) · [AI Consulting Company](https://www.intuz.com/company/) · [For Custom Workflow Automation](https://www.intuz.com/get-started/)

# Automate scraping Y Combinator startups with Apify & Google Sheets

> Community nodes are used, and this template can only be used on **self-hosted n8n instances**.

This n8n template from Intuz provides a complete solution to automate the process of scraping company and founder data from Y Combinator.

It systematically extracts valuable information from your target search and organizes it directly into a Google Sheet, building a powerful prospecting list with minimal effort.

## Who’s this workflow for?

- Sales Teams & SDRs
- Venture Capitalists
- Angel Investors
- Market Researchers
- Startup Founders

## How it works

1. **Trigger the Scrape:** You start the workflow manually whenever you want to gather new company data.

2. **Scrape Y Combinator:** An Apify actor automatically visits your specified Y Combinator search URL (e.g., filtered by batch, industry, or region) and scrapes the details of each company listed.

3. **Retrieve Structured Data:** The workflow fetches the neatly structured data from Apify, including company names, descriptions, websites, founder details, and more.

4. **Log to Google Sheets:** All the scraped information is added or updated as new rows in your designated Google Sheet, creating an organized and actionable database.

## Setup Instructions

### 1. Apify Configuration

- In the **Run an Actor** node, connect your Apify account.
- Select the **Y Combinator Directory Scraper** actor.
- In the **Custom Body** field, replace `{YOUR_Y_COMBINATOR_SEARCH_URL}` with the actual URL from the Y Combinator website after you’ve applied your desired filters.
- You can adjust the `maxCompanies` value to control how many companies are scraped per run.

### 2. Google Sheets Configuration

- In the **Add data to Google Sheet** node, connect your Google Sheets account.
- Select the Document (spreadsheet) and Sheet where you want to save the data. Make sure the sheet has the required columns listed in the **Key Requirements** section.

### 3. Execute the Workflow

- Click the **Execute workflow** button to run the scraper and populate your Google Sheet.

## Key Requirements to Use This Template

- **n8n Instance:** An active **self-hosted** n8n instance (community nodes are required).
- **Apify Account:** An active Apify account with an API key. You will also need sufficient credits or a subscription plan to run the Y Combinator Directory Scraper actor.
- **Google Account & Sheet:** A Google account and a pre-made Google Sheet. The sheet must have the following columns created in advance: `Company`, `Location`, `Website`, `LinkedIn`, `Founded`, `Description`, `Industry Tags`, `Founder 1 Name`, `Founder 1 LinkedIn`, `Founder 2 Name`, and `Founder 2 LinkedIn`.

## FAQ

**Is this template free to use?**
Yes. It's an open-source n8n workflow published by Intuz — copy the workflow JSON from this repo and import it into your own n8n instance at no cost.

**Do I need a paid n8n plan to run this?**
This template uses community nodes, so it only runs on **self-hosted n8n**. You'll need your own Apify and Google Sheets credentials — not a specific n8n Cloud pricing tier.

**Does this use AI?**
No. It scrapes Y Combinator company and founder data with an Apify actor and writes the results to Google Sheets. There is no LLM step.

## Related n8n templates from Intuz

- [Automate LinkedIn profile research & email outreach with Apify, Gemini & Sheets](https://github.com/Intuz-production/LinkedIn-Lead-Generation-Automation)
- [Automate lead gen & email outreach with Apify, Apollo.io, GPT-4 & Google Sheets](https://github.com/Intuz-production/AI-Lead-Generation-Automation)
- [Automate AI Upwork proposal generation with Apify, Google Gemini & Sheets](https://github.com/Intuz-production/Upwork-proposal-generation-automation)

[See all of Intuz's free n8n templates](https://www.intuz.com/n8n-workflow-automation-templates/)

## Connect with us

Intuz is a USA-based AI & workflow automation company with 16+ years of experience building custom AI-enabled workflow automations for SMBs and Enterprises, specializing in agentic AI, LLM integrations, and CRM/ERP sync across Healthcare, FinTech, eCommerce, Manufacturing, and Real Estate.

* **Website:** [https://www.intuz.com](https://www.intuz.com)
* **Email:** [getstarted@intuz.com](mailto:getstarted@intuz.com)
* **LinkedIn:** https://www.linkedin.com/company/intuz/
* **Get Started:** https://n8n.partnerlinks.io/intuz

## For Custom Workflow Automation

[Click here - Get Started](https://www.intuz.com/get-started/)
