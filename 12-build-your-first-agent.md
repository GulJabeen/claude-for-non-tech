# Claude for Non-Tech — Episode 12: Build Your First Agent
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** CREATE

---

## The 5-line agent file template

Copy this, fill in the blanks, and paste into Claude Desktop to run your agent.

```
Goal: [what the agent should accomplish]
Tools: [list the tools it can use]
Rules: [what it should and shouldn't do]
Format: [how to deliver the result]
Stop when: [the condition for finishing]
```

---

## Complete filled-in example: content research agent

```
Goal: Find 5 content ideas for a LinkedIn post about AI tools for small businesses.
      For each idea, write: the hook (first line), the angle, and why it would 
      perform well with a business audience.

Tools: web search (to find what people are already engaging with on LinkedIn)

Rules: 
- Only include topics from the past 30 days
- Avoid generic advice ("use AI to save time") — find specific, surprising angles
- Do not suggest any ideas that require technical knowledge to understand

Format: numbered list of 5 ideas. For each:
  - Hook: [first line of the post]
  - Angle: [what the post is really about]
  - Why it works: [1 sentence]

Stop when: all 5 ideas are written and formatted as described above.
```

---

## How to load and run in Claude Desktop

1. Open Claude Desktop and start a **new chat** (or open the Project where you want to run this)
2. Paste your filled-in agent file directly into the chat box
3. Press Enter — Claude will start working through the task step by step
4. When it's done, it will stop (because of your "Stop when" condition) and show you the result

---

## What to do if the agent gets stuck

**Fix 1: Tell it to continue.**  
Sometimes Claude stops mid-task and waits for confirmation. Just type:
```
Continue.
```
It will pick up where it left off.

**Fix 2: Be more specific about the stuck step.**  
If it keeps getting confused at the same point (e.g. the web search), rephrase that rule. For example, change "search the web" to "use web search to find recent articles about X."

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
