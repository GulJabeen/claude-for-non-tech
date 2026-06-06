# Claude for Non-Tech — Episode 10: Agents (What They Are)
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** AGENT

---

## What is an agent?

An agent is Claude running a multi-step task on its own — you give it a goal, tools, and a finish condition, and it works through the steps without you having to prompt each one.

---

## The 3-line agent formula

```
Goal: [what you want the agent to accomplish]
Tools: [what it can use — web search, Notion, Gmail, etc.]
Stop when: [how it knows it's done]
```

---

## 3 filled-in examples

**Research agent**
```
Goal: Find the top 5 AI tools for small business owners launched in the last 3 months.
        For each one, write: tool name, what it does, price, and who it's best for.
Tools: web search
Stop when: you have a formatted table with all 5 tools and their details.
```

**Content agent**
```
Goal: Write 7 Instagram captions for a coffee shop — one for each day of the week.
        Each caption should have a different angle: product, behind-the-scenes, 
        customer story, seasonal, fun fact, tip, and weekend vibe.
Tools: none (writing only)
Stop when: all 7 captions are written, each under 120 words, each with 5 hashtags.
```

**Inbox agent**
```
Goal: Go through my Gmail inbox and give me a summary of every unread email 
        from the last 48 hours. Flag any that need a reply today.
Tools: Gmail
Stop when: you've listed every unread email with a 1-line summary and a "Reply needed: Yes/No" flag.
```

---

## Prompt vs. agent instruction

| | Prompt | Agent instruction |
|---|--------|------------------|
| **What it is** | A single request you type | A set of rules for an ongoing task |
| **Who drives it** | You — you ask, Claude replies, you ask again | Claude — it works through steps on its own |
| **Best for** | Quick tasks (write this, explain that) | Multi-step tasks (research + write + save) |
| **Example** | "Write me a product description" | "Find 5 competitors, summarise their pricing, then draft a comparison table — stop when the table is complete" |
| **How long it runs** | One response | Until the Stop when condition is met |

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
