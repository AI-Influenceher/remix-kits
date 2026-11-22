# Remix Kit: Ask in Slack, Get a Task

**From the AI Influenceher build log.** Set up a Slack channel where your team posts quick requests, and an automation turns each one into a task in your task tool. No more requests lost in email or retyped between apps.

| | |
|---|---|
| **Time** | About 1 to 2 hours |
| **Skill level** | Some comfort with apps helps. No coding. |
| **You end up with** | A request channel that creates tasks on its own, plus a second lane for bigger asks |

---

## How to use this file

1. Download this file.
2. Open a new chat at [claude.ai](https://claude.ai) and attach it.
3. Type: **"Let's start this remix kit."**
4. Claude will walk you through it one step at a time. Answer its questions, then keep going.

You don't need to read the rest unless you're curious. Claude will handle it.

---

## Instructions for Claude (read this first)

You are guiding someone through building their own version of this project. Follow these rules for the whole conversation:

- Go one step at a time. Finish a step, confirm it with the person, then move to the next.
- Ask questions as short multiple-choice options whenever you can, so the person can tap instead of type.
- Assume the person may be new to tech. Explain any technical word in a few plain words the first time you use it.
- Use only what the person tells you. Do not guess their team names, projects or tools.
- When giving setup steps for an app, tell them exactly where to click, and remind them that app screens change, so they should tell you if something looks different.
- Test with one fake request before the team uses it.
- At the end of each step, say in one line what's done and what's next.

---

## Step 1: Who you are

Claude asks these first, so the setup fits the team. Any group that uses Slack can use this kit: small businesses, agencies, nonprofits, volunteer boards, creator teams.

1. **What does your team do, and how many people will post requests?**
2. **What kinds of requests come in most?** (Quick to-dos, design asks, content, admin, client work)
3. **Where do requests get lost today?** (Email, DMs, meetings, sticky notes)
4. **Who handles bigger requests?** One person, a manager, or whoever is free
5. **How comfortable are you with tech?** New to this, I get by, or very comfortable

---

## Step 2: Your tech stack

A "tech stack" is just the list of tools a project uses.

| Tool | Needed? | What it's for |
|---|---|---|
| [Slack](https://slack.com) | Yes | Where your team posts requests |
| [Zapier](https://zapier.com) | Yes | The automation that connects Slack to your task tool. [Make](https://www.make.com) works too. |
| A task tool | Yes | Where tasks land: [Asana](https://asana.com), [Trello](https://trello.com), [ClickUp](https://clickup.com), [Monday](https://monday.com) or similar |
| [Claude](https://claude.ai) | Yes | Plans the setup with you and writes the request format and team instructions |

**What's an automation?** It's a small rule that runs on its own: "when *this* happens, do *that*." In Zapier, the "when" part is called a **trigger** (a new Slack message) and the "do" part is called an **action** (create a task). A full rule is called a **Zap**.

**About cost:** Zapier and Slack both have free plans with limits. Check [Zapier pricing](https://zapier.com/pricing) to see what fits how many requests you expect.

---

## Step 3: Content you'll need

Gather these before you start. Claude will ask for them in Step 5.

- [ ] **A channel name** for quick asks (for example #requests or #to-do)
- [ ] **A second channel name** for bigger asks (for example #big-asks)
- [ ] **Which project or board** in your task tool should get the new tasks
- [ ] **Who should be assigned** new tasks by default
- [ ] **What a good request includes**, such as what you need, when it's due and any links

---

## Step 4: What this builds

When you're done, you'll have:

- **One channel for quick asks.** Someone posts a simple request instead of sending an email.
- **Tasks that appear on their own.** The automation reads each message and creates the task, so nothing is retyped.
- **A confirmation in Slack.** The automation replies in the thread with a link to the new task, so the person knows it landed.
- **A second lane for big asks.** Larger requests wait in their own channel until the right person picks them up.
- **A pinned how-to** so everyone posts requests the same way.

---

## Step 5: The build, step by step

### 5.1 Design the request format
Claude drafts a short template your team copies when posting, like:
`Need: ... | Due: ... | Links: ...`
Keep it simple. If it's too long, people won't use it.

### 5.2 Create the channels
In Slack, create your quick-ask channel and your big-ask channel. Add your team.

### 5.3 Build the Zap
In Zapier, Claude walks you through:
1. **Trigger:** Slack, "New Message Posted to Channel," pick your quick-ask channel
2. **Action:** your task tool, "Create Task," pick the project and person
3. **Map the fields:** the Slack message becomes the task name and description, and the due date if you used one
4. **Second action:** Slack, "Send Channel Message" as a reply in the thread, with the task link

### 5.4 Test it
Post one fake request. Check that the task shows up in the right place and the reply lands in Slack. Fix anything that's off before the team starts.

### 5.5 Set up the big-ask lane
Decide how bigger requests get handled: a second Zap that creates a task in a "To review" section, or simply a channel the owner checks daily.

### 5.6 Tell the team
Claude writes a short pinned message for each channel explaining what goes where and how to format a request.

---

## Make it even better

- **Let AI clean up messy requests.** Add an AI step in Zapier that turns a rambling message into a clear task title and due date before the task is created.
- **Add emoji shortcuts.** Use a reaction, like a checkmark, to mark a task done from Slack.
- **Send a weekly recap.** A scheduled Zap can post every Friday with what was requested and what got done.

## If something goes wrong

- **No task was created:** check that the Zap is turned on and watching the right channel.
- **Tasks have weird names:** the message is probably mapped to the wrong field. Ask Claude to walk through the field mapping again.
- **Bot replies are creating tasks too:** add a filter step in Zapier so it ignores messages from bots.

---

*Remix kit from the AI Influenceher build log. Change anything that doesn't fit you.*
