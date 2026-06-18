# Claude for Non-Tech — Episode 8: Skills (What They Are + Write Your First One)
**Series:** Claude for Non-Tech by @techwithgul | **Keyword:** SKILL

---

## What is a Skill?

A Skill is a **permanent instruction card** for Claude. Instead of repeating yourself every single time, you tell Claude *once* — who you are, how you like things done, what it should always do, and what it should never do — and Claude follows it from then on.

That's it. No coding. No setup.

> Example: a Skill that says *"Write like Tech With Gul. Use simple language. Teach beginners. Never use technical jargon."* — and every reply follows those rules.

---

## Don't start from scratch — the Skills Directory

You don't have to write one yourself. Inside **Claude Desktop**, open the **Skills Directory** and you'll find dozens of Skills already built by Anthropic. Click the **+** button and start using them instantly — no setup:

| Prebuilt Skill | Use it for |
|----------------|------------|
| **Canvas Design** | Creating designs |
| **Doc Coauthoring** | Writing documents |
| **Web Artifacts Builder** | Creating websites |
| GIF maker | Creating GIFs |

---

## Want a Skill that works exactly the way YOU work? Use Skill Creator

**Skill Creator** sits right at the top of the Directory. Open it and type something like:

```
Help me create a Skill for my Instagram content.
```
or
```
Help me create a Skill for my business.
```

Claude will then ask you questions — *Who's your audience? What tone do you use? What should I always do? What should I never do?* — you answer naturally, like texting a friend, and Claude builds the Skill for you.

---

## The 4-part framework behind every great Skill

Whether you use Skill Creator or write it by hand, every strong Skill has four parts:

| Part | Question it answers |
|------|---------------------|
| **Role** | Who should Claude be? |
| **Tone** | How should it sound? |
| **Rules** | What should it always do? |
| **Anti-rules** | What should it never do? |

The better your instructions, the better your results.

---

## The fill-in-the-blank template

Copy this into a plain text file, save it as `skill.md`, fill in the blanks, and load it into Claude Desktop.

```
# [Skill Name]

## Role
You are [describe the specialist Claude should be].

## Tone
Always write in a [describe tone] voice.

## Rules (always do)
- [rule 1]
- [rule 2]
- [rule 3]

## Anti-rules (never do)
- [anti-rule 1]
- [anti-rule 2]

## Format
[describe how responses should be structured]
```

### The minimal version (shortest that still works)

```
# My Claude Skill

You are my [role].
Tone: [describe].
Always: [rule 1]. [rule 2].
Never: [anti-rule 1]. [anti-rule 2].
Format: [how to structure answers].
```

---

## Example 1: Brand Voice Skill (Instagram captions)

```
# Instagram Caption Writer

## Role
You are an expert Instagram copywriter for lifestyle and wellness brands.

## Tone
Always write in a warm, relatable, and motivating voice — like a supportive friend.

## Rules (always do)
- Start with a bold hook in the first line
- Keep captions under 150 words
- End with a question to encourage comments
- Include 5–8 relevant hashtags at the end

## Anti-rules (never do)
- Use corporate or stiff language
- Use the word "journey"
- Write hashtags mid-caption

## Format
Hook (1 line) → Body (3–4 short lines) → Question → Hashtags (on a new line)
```

---

## Example 2: Customer Service Skill

```
# Customer Service Reply Writer

## Role
You are a customer service specialist for a small e-commerce brand. You handle
complaints, questions, and refund requests with professionalism and empathy.

## Tone
Always write in a calm, empathetic, and solution-focused voice. Warm but professional.

## Rules (always do)
- Acknowledge the customer's frustration first before giving a solution
- Offer a concrete next step (refund, replacement, or follow-up timeline)
- Sign off with the business name: "The Bloom & Co Team"

## Anti-rules (never do)
- Say "unfortunately" as the first word
- Make promises you can't keep (e.g. "delivered tomorrow" without checking)
- Use overly formal legal language

## Format
Greeting → Acknowledgement (1 sentence) → Solution (2–3 sentences) → Sign-off
```

---

## Write → save → load → test

1. **Open any plain-text app** (Apple Notes, Notepad, or any editor)
2. **Write your Skill** — copy a template above and fill in the blanks
3. **Save the file** as something clear like `caption-writer.md` (`.md` just means plain text)
4. **Load in Claude Desktop** — go to Skills → Add Skill → paste your text or upload the file
5. **Test it** — start a new chat, activate the Skill, and run a prompt

### 3 test prompts to confirm it's working

1. "Write a caption for a reel about morning routines."
2. "Reply to a customer who received the wrong item — offer a replacement or refund."
3. "Write a short post announcing a weekend sale."

If the tone, length, or format feels off, go back to the relevant line in your Skill and adjust. Test again.

---

## Learn more

- Skills Directory + Skill Creator → inside **Claude Desktop → Skills**
- Free Claude tutorials: https://claude.com/resources/tutorials
- Anthropic learning hub: https://www.anthropic.com/learn

---

*From @techwithgul · Claude for Non-Tech series · claude.com/resources/tutorials*
