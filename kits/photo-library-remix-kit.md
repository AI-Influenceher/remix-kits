# Remix Kit: A Searchable Photo Library

**From the AI Influenceher build log.** Build a photo library your team can search the way they search Google, with tags and filters like "outdoor, with people, warm colors."

| | |
|---|---|
| **Time** | About 1 to 2 hours for a first version |
| **Skill level** | Beginner friendly. No coding. |
| **You end up with** | One web page that shows your photos in a grid with stackable filters, favorites and saved views |

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
- Use only what the person tells you or shows you. Do not invent their brand details, products or results.
- Start with a small sample before doing everything, so they can check the look and the tags early.
- At the end of each step, say in one line what's done and what's next.

---

## Step 1: Who you are

Claude asks these first, so the library fits the person using it. Anyone can use this kit: a business owner, a marketer, a photographer, a nonprofit volunteer, a creator.

1. **What do you do?** (For example: run a shop, manage social for a brand, shoot photos for clients, run a community group)
2. **Who will search these photos?** Just you, a small team, or clients too?
3. **What kind of photos are they?** (Products, events, food, people, places, behind the scenes)
4. **How comfortable are you with tech?** New to this, I get by, or very comfortable
5. **What should it look like?** Brand colors and fonts if you have them, or a vibe like "clean and minimal" or "bold and fun"

---

## Step 2: Your tech stack

A "tech stack" is just the list of tools a project uses.

| Tool | Needed? | What it's for |
|---|---|---|
| [Claude](https://claude.ai) | Yes | Tags the photos and builds the page |
| Your photos in a folder | Yes | On your computer, or in [Google Drive](https://drive.google.com) or [Dropbox](https://www.dropbox.com) |
| A web browser | Yes | The finished library is a single web page file that opens in any browser |
| A place to share the page | Optional | Claude can publish it as a shareable link, or you can use a free host like [Netlify Drop](https://app.netlify.com/drop) |

**Good to know:** Photos are usually large files. Shrinking them first (to around 1,000 pixels wide) makes uploads faster and the page quicker to load. Free tools like [Squoosh](https://squoosh.app) can do this, or ask Claude to help.

---

## Step 3: Content you'll need

Gather these before you start. Claude will ask for them in Step 5.

- [ ] **A sample of 20 to 50 photos** to start (you'll add the rest later)
- [ ] **Your categories**, such as product names, event names or locations
- [ ] **Words your team already uses** to describe photos (for example "lifestyle," "flat lay," "hero shot")
- [ ] **Brand colors and fonts**, or a few words about the look you want
- [ ] **3 to 5 searches your team actually does**, like "a close-up of the product with hands in frame." These become your test.

---

## Step 4: What this builds

When you're done, you'll have a page where:

- Every photo has tags for things like **scene, product, who's in the frame and main color**
- You can **stack filters** to narrow down fast ("outdoor" + "with people" + "warm colors")
- You can **sort and group** photos, for example by product
- You can **star favorites** and **save views** you use often
- Anyone on your team can use it without training

**Why it helps:** Photos in folders only have one way to find them, which is scrolling. Tags let you find the same photo many different ways.

---

## Step 5: The build, step by step

### 5.1 Agree on your tags
Claude suggests a short list of tag groups based on your answers in Step 1 (for example Scene, Product, People, Color, Mood). You pick, cut or rename them. Keep it to 4 to 6 groups so filtering stays simple.

### 5.2 Tag the sample
Upload your sample photos. Claude tags each one and **lists any tags it was unsure about**, so you can fix them.

### 5.3 Review the tags
Look over the list. Correct anything wrong. This is the most important step, because good tags are what make search work.

### 5.4 Build the page
Claude builds the library page: a photo grid with filter buttons for each tag group, using your colors and look.

### 5.5 Add the extras
Ask for any of these: sort options, group by product, star favorites, saved views, a "copy file name" button, a dark mode.

### 5.6 Test it with real searches
Run the 3 to 5 searches you wrote down in Step 3. If a search doesn't find the right photo, tell Claude and it will adjust the tags or filters.

### 5.7 Add the rest of your photos
Once you like the sample, upload the rest in batches of about 50. Claude tags each batch the same way and adds it to the page.

### 5.8 Share it
Publish the page as a link, or save the file and send it to your team.

---

## Make it even better

- **Connect to your Drive.** If Claude has access to your Google Drive, it can read photos straight from a folder so you don't have to upload them.
- **Add videos.** The same tagging works for short clips, using a still frame as the cover.
- **Add usage notes.** Tag photos as "used on Instagram" or "approved for ads" so the team knows what's safe to post.
- **Keep it fresh.** After each new shoot, upload the new batch and ask Claude to tag and add it.

## If something goes wrong

- **The page is slow:** the photos are probably too large. Shrink them and rebuild.
- **Tags feel random:** go back to 5.1 and tighten your tag list with examples.
- **Favorites disappeared:** favorites and saved views are often stored in your browser, so they won't carry over to another computer. Ask Claude to add an "export my favorites" button.

---

*Remix kit from the AI Influenceher build log. Change anything that doesn't fit you.*
