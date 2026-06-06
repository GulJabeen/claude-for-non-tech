# Claude for Non-Tech — Episode 9: Write Your First Skill
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** BUILD

---

## The minimal 8-line Skill file

This is the shortest version that works. Copy it, fill it in, and you have a working Skill.

```
# My Claude Skill

You are my [role].
Tone: [describe].
Always: [rule 1]. [rule 2].
Never: [anti-rule 1]. [anti-rule 2].
Format: [how to structure answers].
```

**Filled-in example — Email Reply Skill:**
```
# My Email Reply Skill

You are my professional email writer.
Tone: confident, warm, and concise — never stiff or overly formal.
Always: keep replies under 100 words. End with a clear next step or question.
Never: start an email with "I hope this email finds you well." Use passive aggressive tone.
Format: Greeting → Main point (2–3 sentences) → Next step → Sign-off as "Nadia".
```

---

## Step-by-step: write → save → load → test

1. **Open Notes** (iPhone Notes, Apple Notes, Windows Notepad, or any plain text app)
2. **Write your Skill** — copy the 8-line template above and fill in the blanks for your use case
3. **Save the file** — name it something clear like `email-skill.md` or `caption-writer.md` (the `.md` stands for markdown — it just means plain text with formatting)
4. **Load in Claude Desktop** — go to Skills in the sidebar, click Add Skill, and paste your text or upload the file
5. **Test it** — start a new chat, activate your Skill, and try one of the test prompts below

---

## 5 test prompts to verify your Skill is working

Use these right after loading your Skill. If Claude responds in the right tone and format, it's working.

1. "Write a reply to a customer asking about delivery times. We usually deliver in 3–5 business days."
2. "Draft a quick email to cancel a meeting tomorrow and suggest rescheduling next week."
3. "Write a follow-up message to a potential client I met at a networking event last Thursday."
4. "Reply to an angry customer who received the wrong item. Offer a replacement or refund."
5. "Write a short email introducing myself to a new collaborator I'll be working with next month."

If any response feels off (wrong tone, wrong length, wrong format), go back to your Skill file and adjust the relevant line. Test again.

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
