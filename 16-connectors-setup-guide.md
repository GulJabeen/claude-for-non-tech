# Claude for Non-Tech — Episode 16: Claude Connectors
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** CONNECT

---

## Plugins vs. connectors — what's the difference?

**Plugins** connect Claude to public apps (Gmail, Notion, Canva) — you install them in one click.  
**Connectors** connect Claude to private data sources (your company's CRM, internal databases, custom tools) — they require a short setup but unlock access to data that's specific to your organisation.

---

## Top 3 connectors to start with

### 1. HubSpot Connector
Unlocks: your contacts, deals, notes, and pipeline data from HubSpot

**Example prompts after connecting:**
```
"List all leads who came in this week and have not been contacted yet."
"Write personalised follow-up emails for the 3 leads in my pipeline marked 'Interested'."
"Summarise the deal history for [Company Name] in 5 bullet points."
"Which of my open deals has been idle the longest? Draft a check-in email for it."
```

---

### 2. Jira / Project Tools Connector
Unlocks: your tasks, sprints, project boards, and issue history

**Example prompts after connecting:**
```
"List all open tasks assigned to me across all projects."
"Summarise what our team shipped in the last 2-week sprint."
"Find all bugs reported in the last 30 days and sort them by priority."
"Draft release notes for everything we completed in the current sprint."
```

---

### 3. Zapier Connector
Unlocks: the ability to chain Claude to literally any app through Zapier's 6,000+ integrations

**How Zapier works with Claude:** you set up a Zap (an automated connection between two apps) and Claude becomes one of the steps — for example, Claude can write a summary that then automatically gets sent as a Slack message or saved to a Google Sheet.

**Example prompts + setups:**
```
"When a new lead fills out my Typeform, summarise their answers and add them to HubSpot."
"When I get a new Gmail from a client, draft a reply and save it as a Notion note for review."
"Every Friday at 5pm, pull my completed tasks from Todoist and send me a weekly summary in Slack."
```

---

## Step-by-step connector setup

1. Go to **https://claude.com/connectors** and browse the directory
2. Find the connector you want (e.g. HubSpot) and click **Set Up**
3. You'll be asked to authenticate — sign in to the relevant app (e.g. log into HubSpot) and grant access
4. Once connected, go back to Claude Desktop and start a new chat
5. Ask Claude to do something specific with the connected data to confirm it's working (e.g. "List my last 5 HubSpot contacts")

---

## Quick link

Connector directory: **https://claude.com/connectors**

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
