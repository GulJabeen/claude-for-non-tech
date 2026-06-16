# Claude for Non-Tech — Episode 5: MCP Plugins (What They Are)
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** MCP

---

## What is MCP? (in plain English)

**MCP stands for Model Context Protocol.** Think of it as the set of *plugs and sockets* that lets Claude connect to the apps you already use every day.

Out of the box, Claude can only *talk* to you — it writes, explains, and answers. With MCP turned on, Claude can actually *do things* in your real accounts: read your inbox, add an event to your calendar, update a Notion page, or pull numbers out of a spreadsheet.

A simple way to picture it:

> **Without MCP:** Claude is a brilliant assistant locked in a room. It can give you advice, but it can't touch anything.
>
> **With MCP:** You hand that assistant the keys to specific rooms — your email, your calendar, your docs — and now it can fetch, change, and organise things for you.

You stay in control of *which* keys you hand over. Every plugin asks your permission before it connects, and you can switch any of them off at any time.

---

## Why this matters for non-technical people

You don't need to code, run a server, or understand the protocol. You just **click to connect an app**, and from then on you can ask Claude things like:

- *"Summarise the 5 newest emails in my inbox and draft replies to the two that need answers."*
- *"Look at my calendar this week and tell me where I have a free 2-hour block."*
- *"Pull the latest figures from my Sales sheet and write a short summary for my team."*

Claude does the busywork; you just review and approve.

---

## Top 10 most useful plugins

| Plugin | What it does | Best for | Try saying… |
|--------|-------------|----------|-------------|
| **Gmail** | Reads, drafts, and sends emails from your Gmail account | Drafting replies, summarising your inbox, writing cold outreach | *"Draft a polite reply to the email from Sarah about the invoice."* |
| **Google Drive** | Reads and creates files in your Drive | Summarising documents, drafting reports, finding files by asking | *"Find my Q3 report in Drive and give me the 3 key takeaways."* |
| **Notion** | Creates, edits, and organises pages in Notion | Building wikis, writing notes, managing your knowledge base | *"Create a new Notion page for this week's meeting notes."* |
| **Google Calendar** | Reads your calendar and schedules events | Scheduling meetings, planning your week, spotting conflicts | *"Find a free 30-min slot tomorrow and book a call with the team."* |
| **Slack** | Reads messages and posts to channels | Summarising threads, drafting announcements, replying to DMs | *"Summarise what I missed in #general today."* |
| **GitHub** | Reads code, creates issues, and manages repos | Reviewing code, writing documentation, tracking bugs | *"Open an issue titled 'Login button broken on mobile'."* |
| **Zapier** | Connects Claude to 6,000+ other apps | Automating workflows between any tools you use | *"When I get a new lead, add them to my CRM and email me."* |
| **Canva** | Creates designs directly from a prompt | Social posts, presentations, flyers — without opening Canva | *"Make me an Instagram post announcing our Friday sale."* |
| **HubSpot** | Reads and updates your CRM contacts and deals | Writing follow-ups, updating deal stages, pulling contact info | *"Move the Acme deal to 'Negotiation' and draft a follow-up."* |
| **Google Sheets** | Reads and writes spreadsheet data | Analysing data, filling in columns, generating reports | *"Read my expenses sheet and total each category for me."* |

> **Tip:** You don't need all ten. Most people start with just **Gmail + Calendar + Drive** — the three that save the most time on day one — and add others as they go.

---

## Plugins vs Connectors — what's the difference?

People mix these up, so here's the simple version:

| | **Plugins** | **Connectors** |
|---|---|---|
| **What they link to** | Popular apps (Gmail, Notion, Slack…) | Private or company data sources |
| **Who it's for** | Everyone — personal use | Teams and businesses |
| **Setup** | One click to connect | May need an admin to enable |

If you're an individual getting started, **plugins are all you need.** Connectors come into play when you want Claude reaching into internal company tools.

---

## A quick safety note (read this)

Because plugins give Claude real access to your accounts, two habits keep you safe:

1. **Only connect what you need.** Turn off any plugin you're not actively using.
2. **Review before you approve.** When Claude is about to send an email or change a file, it shows you what it'll do *first*. Read it, then approve. Nothing happens without your okay.

This is exactly like giving a new assistant access — start small, build trust, expand from there.

---

## How to find more plugins

Browse the full plugin directory: **https://claude.com/plugins**

New plugins are added regularly, so it's worth checking back — the app you wish was connected might already be there.

## How to find connectors

Connectors work differently from plugins — they let Claude access private data sources like your company tools.
Browse connectors: **https://claude.com/connectors**

---

## Your 2-minute first step

1. Open Claude and go to **Settings → Connectors / Plugins**.
2. Connect **one** app you use every day (Gmail is a great start).
3. Ask it something simple: *"Summarise my 3 most recent emails."*
4. Watch it work — then approve. That's MCP. 🎉

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
