# Claude for Non-Tech — Episode 13: Full Workflow Setup
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** AUTOMATE

---

## The complete setup checklist

Work through these 5 steps in order. Each one builds on the previous.

```
Step 1: Write your Skill file (→ use file 08-skill-template.md)
Step 2: Install your Plugin (→ use file 06-plugin-install-guide.md)
Step 3: Write your Agent (→ use file 12-build-your-first-agent.md)
Step 4: Test each piece individually
Step 5: Run the full workflow with one trigger prompt
```

**Step 4 explained:** Before combining everything, test each piece on its own:
- Test your Skill: activate it and ask Claude to write one thing — check the tone and format
- Test your Plugin: ask Claude to pull one piece of data from the connected app
- Test your Agent: run it alone without the Skill active

If each piece works on its own, the combined workflow will run cleanly.

---

## The trigger prompt template

Once everything is set up, use this single prompt to kick off the entire workflow.

```
Using my [Skill name] and [Plugin name], [goal].
Steps: [1. X, 2. Y, 3. Z]
Save to: [destination]
```

**Filled-in example:**
```
Using my Caption Writer Skill and Google Drive plugin, create this week's 
Instagram content plan.
Steps:
1. Open this week's content brief from Google Drive (file: "May Week 3 Brief")
2. Write 5 captions based on the topics listed in the brief
3. Format them as a numbered list with hashtags
Save to: paste all 5 captions in this chat so I can copy them
```

---

## Complete example: weekly content creation workflow

**Setup you need first:**
- Skill: Instagram Caption Writer (see `08-skill-template.md`)
- Plugin: Google Drive (see `06-plugin-install-guide.md`)

**Your Google Drive:** has a folder called "Content Briefs" with a new doc each week listing 5 post topics.

**The trigger prompt you paste every Monday:**
```
Using my Instagram Caption Writer Skill and my Google Drive plugin:

1. Open the most recent file in my "Content Briefs" folder in Google Drive
2. Read the 5 post topics listed inside
3. Write one Instagram caption for each topic
4. For each caption: 80–120 words, warm and motivating tone, 
   ends with a question, followed by 8 relevant hashtags

Save to: paste all 5 captions here in numbered order, ready to copy-paste.
```

**What happens:** Claude opens your Drive, reads your brief, writes 5 captions using your Skill's tone rules, and delivers them formatted and ready to post. One paste. Done.

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
