# Remix Kit: Client Hours, Profit and Health Dashboards

**From the AI Influenceher build log.** Join your time tracking and invoices to see hours against budget, real margin per client and which accounts need a conversation.

| | |
|---|---|
| **Time** | About 2 to 3 hours |
| **Skill level** | Some comfort with spreadsheets helps. No coding. |
| **You end up with** | Dashboards for hours by client, margin by client and month, and a simple star rating per account |

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
- Use only what the person tells you, shows you or what you can check. Do not invent names, numbers, quotes or results.
- At the end of each step, say in one line what's done and what's next.

---

## Step 1: Who you are

Claude asks these first, so the result fits the person using it. Anyone can use this kit: agencies, consultancies, freelancers with subcontractors and service teams.

1. **What do you do, and who is this for?** (For example: I run an agency with contractors, I bill retainers, I track hours for clients)
2. **Where do you track hours?** Harvest, Toggl, Clockify, a spreadsheet
3. **Where do invoices live?** QuickBooks, Xero, a spreadsheet
4. **Which view matters most?** Hours vs budget, profit per client, or overall account health
5. **How comfortable are you with tech?** New to this, I get by, or very comfortable

---

## Step 2: Your tech stack

A "tech stack" is just the list of tools a project uses.

| Tool | Needed? | What it's for |
|---|---|---|
| [Claude](https://claude.ai) | Yes | Joins the data and builds the dashboards |
| [Google Sheets](https://sheets.google.com) | Yes | Where the data lives so the page stays current |
| [Harvest](https://www.getharvest.com), Toggl or Clockify | Optional | Time tracking |
| [QuickBooks](https://quickbooks.intuit.com) or Xero | Optional | Invoices |

**What's margin?** How much of a client's payment is left after paying the people who did the work. Higher is healthier.

---

## Step 3: Content you'll need

Gather these before you start. Claude will ask for them in Step 5.

- [ ] A few months of logged hours by person and client
- [ ] Invoices by client by month
- [ ] Each client's monthly hour budget
- [ ] Contractor pay rates
- [ ] Which hours are internal (admin, sales, marketing)

---

## Step 4: What this builds

When you're done, you'll have:

- **Hours by person and client** against each budget, with a 10-week trend
- **Margin by client and by month** against a target line, with low ones in red
- **A star rating** per client, where fewer hours for the same work means more stars
- **Internal time** shown on its own, and a short list of what's left out so nobody mistakes it for full profit

**Why it helps:** When invoices and hours live in different tools, you can't see which clients are healthy.

---

## Step 5: The build, step by step

### 5.1 Gather the data
Export hours and invoices, or connect the tools.

### 5.2 Set up the sheet
Claude organizes it into tabs Claude can read.

### 5.3 Build the hours view
Hours vs budget per client, with trends.

### 5.4 Build the margin view
Revenue minus contractor cost, by client and month.

### 5.5 Add the rating
A simple star scale with a key.

### 5.6 Check for traps
Claude flags things that mislead, like a retainer billed twice one month and not the next.

---

## Make it even better

- Set a **monthly refresh** as a scheduled task.
- Add **alerts** when a client passes 90% of budget.
- Keep dashboards **private**, since they hold rates and pay.

## If something goes wrong

- **Numbers look wrong:** Check that client names match exactly in both data sets.
- **Margins seem too high:** Make sure all contractor costs are included.

---

*Remix kit from the AI Influenceher build log. Change anything that doesn't fit you.*
