# Claude for Non-Tech — Episode 11: Main Agents and Subagents
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** SUBAGENT

---

## How main agents and subagents work

Think of the **main agent** as a manager — it knows the overall goal and delegates work to specialists.  
**Subagents** are the team — each one handles a specific part of the job (research, writing, formatting).

The manager doesn't do the work itself. It tells each team member what to do, collects their output, and assembles the final result. You only have to give instructions to the manager.

---

## The template

Copy this and fill in the blanks. Each `---` separates a different agent.

```
# Main Agent

Goal: [overall goal]

For research: use the Research Subagent
For writing: use the Writing Subagent
For formatting: use the Formatting Subagent

Deliver: [final output format]

---

# Research Subagent
Goal: [specific research task]
Tools: [web search]
Output: [bullet list of findings]

---

# Writing Subagent
Goal: [specific writing task]
Input: [what it receives from Research Subagent]
Output: [draft format]

---

# Formatting Subagent
Goal: [specific formatting task]
Input: [what it receives from Writing Subagent]
Output: [final formatted version]
```

---

## Filled-in example: weekly content workflow

```
# Main Agent

Goal: Produce 3 ready-to-post Instagram captions for a skincare brand every Monday morning.

For research: use the Research Subagent to find trending topics
For writing: use the Writing Subagent to draft captions
For formatting: use the Formatting Subagent to add hashtags and structure

Deliver: 3 numbered captions in plain text, each with hashtags, ready to copy-paste.

---

# Research Subagent
Goal: Find 3 trending skincare topics from the past 7 days (ingredients, routines, 
      or products people are talking about on social media).
Tools: web search
Output: a bullet list of 3 topics, each with one sentence explaining why it's trending

---

# Writing Subagent
Goal: Write one Instagram caption for each of the 3 trending topics.
Input: the bullet list from Research Subagent
Output: 3 captions, each 80–120 words, warm and educational tone, ends with a question

---

# Formatting Subagent
Goal: Polish each caption for posting.
Input: the 3 draft captions from Writing Subagent
Output: each caption formatted as: Caption text → blank line → 8 relevant hashtags
```

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
