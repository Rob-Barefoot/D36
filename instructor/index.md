---
title: Instructor Guide
---

# Using GitHub & AI to Create & Host Websites

## Instructor Lesson Plan — 3-Hour Training Session

| Detail | Value |
|---|---|
| **Audience** | Teenagers, ages 12–18 |
| **Group size** | ~20 learners |
| **Duration** | ~3 hours 30 minutes (210 minutes) |
| **Platform** | GitHub (github.com) + AI assistants (GitHub Copilot, Microsoft Copilot, and others) |
| **Device** | iPad with Safari browser (internet required). A physical keyboard (Smart Keyboard, Magic Keyboard, or Bluetooth) is strongly recommended. |
| **Prerequisites** | None — no prior coding or GitHub experience needed |

### Session description

In this session you'll start designing a website on paper, then take a quick dive into source control (the process of tracking and managing source code changes) using GitHub software automation tools. Then you'll create an account and use an AI (artificial intelligence) assistant to help build your website.

## Jump to a section

**Prep & overview:**

| Section | |
|---|---|
| [Before the Session](#before-the-session) | Prep |
| [Session at a Glance](#session-at-a-glance) | Schedule |

**Session flow** — 🎤 = instructor-led, ✍️ = student activity (matches student guide)

| | Section | Time |
|---|---|---|
| 🎤 | [Welcome & Icebreaker](#block-1-welcome--design-000055) | 0:00–0:15 |
| 🎤 | [What Is a Website?](#what-is-a-website-design-on-paper-20-min) | 0:15–0:35 |
| ✍️ | [Activity 1: Wireframe Your Website](#activity-1-wireframe-your-website-20-min) | 0:35–0:55 |
| 🎤 | [Source Control & Intro to GitHub](#what-is-source-control-intro-to-github-055115--20-min) | 0:55–1:15 |
| ☕ | [Break](#break-115125--10-min) | 1:15–1:25 |
| ✍️ | [Activity 2: GitHub Account & First Repo](#activity-2-create-a-github-account--first-repo-125150--25-min) | 1:25–1:50 |
| ✍️ | [Activity 3: Go Live with GitHub Pages](#activity-3-go-live-with-github-pages-150200--10-min) | 1:50–2:00 |
| 🎤 | [What Is AI? How Can It Help You Code?](#what-is-ai-how-can-it-help-you-code-200220--20-min) | 2:00–2:20 |
| ✍️ | [Activity 4: Use AI to Build Your Website](#activity-4-use-ai-to-build-your-website-220300--40-min) | 2:20–3:00 |
| ✍️ | [Customize & Polish](#customize--polish-300315--15-min) | 3:00–3:15 |
| 🎤 | [Showcase & Wrap-Up](#showcase--wrap-up-315330--15-min) | 3:15–3:30 |

**Reference:**

| Section | |
|---|---|
| [Concepts Covered](#concepts-covered-summary) | Summary table |
| [Troubleshooting](#troubleshooting) | Common issues |
| [Materials Checklist](#materials-checklist) | What to bring |

---

## Before the Session

### Instructor prep (do these at least 1 day before)

1. **Create your own GitHub account** at https://github.com — walk through the full signup flow so you can troubleshoot learner issues.
2. **Create a sample website repo** on your GitHub account. Build a working example with GitHub Pages enabled so you can show learners a finished product. Make it something personal and fun — an "about me" page, a hobby showcase, a fan page for a band — anything that shows teens what's possible. Include a simple `index.html` with basic CSS styling.
3. **Test GitHub Pages** — confirm your sample site is live at `https://<your-username>.github.io/<repo-name>`. It can take 1–2 minutes after enabling Pages for the site to go live.
4. **Test AI assistant access** — learners will use AI assistants throughout the session. Any AI chat tool works; the demos in this lesson plan use **GitHub Copilot** because it's included free with the GitHub account every learner will create, but learners can use whichever tool they prefer. Test your options ahead of time:
   - **GitHub Copilot** — free tier included with GitHub Free accounts. Learners can access it at [github.com/copilot](https://github.com/copilot) in the browser immediately after creating their GitHub account. No extra signup needed.
   - **Microsoft Copilot** — copilot.microsoft.com — free, no account required. Great for brainstorming and works just as well for code generation.
   - **Other options** — ChatGPT (chatgpt.com), Google Gemini (gemini.google.com), Meta AI (meta.ai), Perplexity (perplexity.ai), Mistral Le Chat (chat.mistral.ai), HuggingChat (huggingface.co/chat), or any other AI chat tool. The prompts in this session work the same way in all of them.
   - Test at least two options on the learners' network before session day.
5. **Print the Student Activity Guides** (1 per learner) and the **Paper Wireframe Templates** (1 per learner).
6. **Ensure Wi-Fi can handle 20+ simultaneous connections** to github.com and your chosen AI tools.
7. **Prepare colored pencils or markers** for the wireframing activity — 1 set per table of 4.
8. **Test the full workflow on an iPad** — create an account, make a repo, edit a file, enable Pages — all in Safari. Some school networks block GitHub or AI tools — find out before session day.
9. **Confirm iPad readiness:**
   - **Physical keyboards:** If the iPads have Smart Keyboards, Magic Keyboards, or Bluetooth keyboards, the experience will be nearly identical to a laptop. Without a keyboard, copy-paste is doable but slower — budget an extra 5–10 minutes for Activities 2 and 4.
   - **iPad Split View:** Test opening two Safari windows side by side (drag a tab to the edge of the screen). This lets learners keep the AI assistant on one side and GitHub on the other — much easier than switching tabs. Plan to demo this for the group.
   - **Safari settings:** Make sure pop-up blockers won't interfere with GitHub's signup flow. Test this on one iPad before session day.

### Room setup

- Arrange tables in clusters of 4 so pairs can collaborate and share screens.
- Project your own screen (laptop or iPad with AirPlay/adapter) for live demos.
- Have a whiteboard or flip chart for brainstorming.
- Put colored pencils/markers and printed wireframe templates on each table before learners arrive.
- **Ensure every iPad is charged** (or have charging cables at each table). A 3.5-hour session will drain a battery.
- **If iPads have detachable keyboards,** make sure they're attached before learners arrive.

---

## Session at a Glance

| Time | Block | Duration | Type |
|---|---|---|---|
| 0:00–0:15 | Welcome & Icebreaker | 15 min | Discussion |
| 0:15–0:35 | What Is a Website? Design on Paper | 20 min | Interactive lecture + hands-on |
| 0:35–0:55 | Activity 1: Wireframe Your Website | 20 min | Paper-based hands-on |
| 0:55–1:15 | What Is Source Control? Intro to GitHub | 20 min | Interactive lecture |
| 1:15–1:25 | **Break** | 10 min | — |
| 1:25–1:50 | Activity 2: Create a GitHub Account & First Repo | 25 min | Guided hands-on |
| 1:50–2:00 | Activity 3: Go Live with GitHub Pages | 10 min | Guided hands-on |
| 2:00–2:20 | What Is AI? How Can It Help You Code? | 20 min | Interactive lecture + demo |
| 2:20–3:00 | Activity 4: Use AI to Build Your Website | 40 min | Guided + independent hands-on |
| 3:00–3:15 | Customize & Polish | 15 min | Independent hands-on |
| 3:15–3:30 | Showcase & Wrap-Up | 15 min | Presentations / discussion |

---

## Detailed Session Plan

---

### Block 1: Welcome & Design (0:00–0:55)

#### Welcome & Icebreaker (15 min)

**Goal:** Build energy, learn names, and get learners thinking about websites they use every day.

1. **Introduce yourself** (2 min) — Keep it short. Share one fun fact about a website or app you built, or a funny mistake you made while learning.
   - **Instructor note:** Teens warm up faster if you're relatable. "I once published a website where the background was the same color as the text — it looked completely blank to everyone else" lands better than listing credentials.

2. **Icebreaker: "Website Critic"** (13 min)

   > 👥 **GROUP ACTIVITY:** Split into groups. Each group picks a website, answers 3 questions on sticky notes, then shares with the class.

   - Split into groups of 3–4 at their tables.
   - Each group picks a website they all know (a school site, a social media platform, a game wiki, a fan page — anything).
   - Give them 5 minutes to answer three questions on a sticky note or whiteboard:
     1. **What's one thing this website does well?**
     2. **What's one thing that annoys you about it?**
     3. **If you could change one thing, what would it be?**
   - Each group shares their answers (1 min per group).

   **Debrief** (3 min): Ask the group:
   - *Did anyone pick the same website? Did you agree on what's good and bad?*
   - *Who decides what goes on a website?* (Answer: someone like you! Designers and developers.)
   - *What if I told you that by the end of today, you'll have your OWN website live on the internet?*

   **Key takeaway**: Every website was built by people who started by thinking about what the site should do and what problems it should solve. That's what you're going to do today.

#### What Is a Website? Design on Paper (20 min)

**Goal:** Demystify how websites work and introduce the design-first mindset.

1. **How websites work — the 30-second version** (5 min)

   > 🗒️ **WHITEBOARD:** Draw the browser → internet → server → files → screen flow diagram.

   - Draw a simple diagram on the whiteboard:
     ```
     You (browser) → Internet → Server (a computer) → sends back files → Your screen shows the page
     ```
   - "A website is just files — mostly three types":
     - **HTML** = the content (text, images, structure) — think of it as the skeleton
     - **CSS** = the style (colors, fonts, layout) — think of it as the clothes
     - **JavaScript** = the behavior (buttons, animations) — think of it as the muscles (we won't use this today)
   - Show view-source on a simple webpage: on your demo device, long-press the URL bar in Safari and choose "Show Page Source" (or use a site like [neatnik.net/view-source](https://neatnik.net/view-source/) to show the source of any URL). "See? It's just text with angle brackets. Not as scary as it looks."

   > 🖥️ **PROJECTOR:** Show the raw HTML source of your demo page.

   **Instructor note:** iPads don't have a right-click "View Page Source" like desktops. Don't dwell on this — just show it from your demo screen. The goal is a quick peek at what's behind a web page, not a deep dive.

2. **What makes a website good for EVERYONE?** (5 min)
   - "We talked about what makes a website annoying or great. But here's a question: what if someone visiting your site can't see the colors? Or can't use a mouse? Or is reading on a tiny phone screen in bright sunlight?"
   - **Introduce accessibility:** "Making a website accessible means designing it so everyone can use it — people with visual impairments, hearing differences, motor disabilities, or just someone in a noisy room or with a slow internet connection."
   - **Mention WCAG:** "There's actually a set of international guidelines for this called **WCAG** — the Web Content Accessibility Guidelines. Professional web developers follow these to make sure their sites work for everyone. Today we'll learn a few of the most important ones:"
     - **Color contrast** — text needs to stand out clearly from the background so it's readable in any lighting
     - **Alt text** — images should have a text description so screen readers can describe them to someone who can't see the image
     - **Semantic headings** — using proper heading levels (H1, H2, H3) so the page structure makes sense even without the visual layout
   - **Key message — accessibility benefits EVERYONE:**
     - "Here's the thing — accessibility isn't just about helping people with disabilities. Almost every accessibility feature ends up helping everybody."
     - Ask the group: *"Has anyone ever used closed captions on a video — not because you're deaf, but because you're in a noisy place or don't want to wake someone up?"* That's an accessibility feature that benefits everyone.
     - More examples:
       - **Curb cuts** on sidewalks were designed for wheelchair users — but strollers, bikes, skateboarders, and delivery carts all use them
       - **Dark mode** started as an accessibility option for people with light sensitivity — now it's the most popular display setting
       - **Voice assistants** (Siri, Alexa) came from accessibility research for people who can't type — now everyone uses them
       - **Automatic doors** were created for people with mobility challenges — but everyone appreciates them when carrying groceries
       - **Subtitles on foreign-language shows** — that's the same technology as closed captions
     - "When you make something accessible, you make it better for *everyone*. That's why we'll ask our AI assistant to include these features when it builds your page."

   **Instructor note:** This is a quick but important section. Don't turn it into a lecture — the real-world examples land better than rules. The goal is for teens to think "oh, that's just good design" rather than "ugh, more requirements." They'll apply these ideas when they write their AI prompts in Activity 3.

3. **What kind of website would YOU make?** (5 min)

   > 🖥️ **PROJECTOR:** Show 3–4 example teen websites, then open Microsoft Copilot for a live AI brainstorm.

   - Show 3–4 examples of simple personal websites (your demo site, a hobby page, a portfolio, a fan site). Pick ones that feel like something a teen would actually want to build — not corporate or boring.
   - **Try an AI brainstorm** (optional but fun): Open **Microsoft Copilot** (copilot.microsoft.com) on the projector — no account needed — and type:

     > I'm a teenager and I want to make a website about something I'm interested in. Give me 10 creative and fun website ideas that a teen would actually want to build.

   - Read the suggestions out loud. This gets the group thinking AND shows them that AI is useful for more than just code — it's a brainstorming partner. Add the AI's ideas to the whiteboard alongside the group's ideas.
   - Brainstorm website ideas with the group. Get suggestions on the whiteboard:

   > 🗒️ **WHITEBOARD:** Collect the group's website ideas alongside the AI suggestions.

     - **Fan page** for a game, artist, show, or sport team
     - **About me** — your interests, hobbies, playlists, favorite things
     - **Club or group page** — your 4-H club, sports team, friend group, study group
     - **Hobby showcase** — art, photography, cooking recipes, skateboard tricks
     - **"Top 10" or ranking page** — best albums, games, movies, snacks
     - **Guide or tips page** — how to get better at something you're good at
     - **Creative writing / poetry** — your own work with cool styling
     - **Fictional page** — a website for a made-up band, restaurant, or superhero
   - **Instructor note:** The more personal and weird the idea, the more engaged teens will be. "A website ranking every school lunch from best to worst" will get way more energy than "a professional portfolio." Let them be creative.

3. **Intro to wireframing** (10 min)

   > 🗒️ **WHITEBOARD:** Draw a site map (3 page boxes), then wireframe the homepage with nav bar, sections, and footer.

   - "Before you write any code, real designers sketch their ideas on paper. This is called a wireframe — it's a rough blueprint of what the page will look like."
   - "Real websites aren't just one page — think about your favorite sites. They have a homepage, an about page, maybe a gallery or contact page. You're going to plan a real multi-page website today, starting with the homepage."
   - Demo on the whiteboard or flip chart: draw a **site map** first, then a wireframe for the homepage of a 4-H SPIN club site:
     ```
     Site Map:
     ┌─────────────┐   ┌─────────────┐   ┌─────────────┐
     │  Home       │   │  Projects   │   │  Meetings   │
     │ index.html  │   │projects.html│   │meetings.html│
     └─────────────┘   └─────────────┘   └─────────────┘
     ```
     Then the homepage wireframe:
     ```
     ┌──────────────────────────────────┐
     │  Home | Projects | Meetings    │  ← Navigation bar
     │──────────────────────────────────│
     │  🍀 Tech Explorers SPIN Club     │  ← Title / header
     │──────────────────────────────────│
     │  About Our Club                  │  ← Section heading
     │  We meet every Thursday to       │
     │  learn coding, robotics, and     │
     │  how tech shapes our world.      │
     │                                  │
     │  What We're Working On           │  ← Section heading
     │  • Building websites (that's     │
     │    what we're doing today!)      │
     │  • Raspberry Pi projects         │
     │  • 3D printing                   │
     │                                  │
     │  Join Us / Contact               │
     │  • Email: techclub@4h.org        │
     │  • Meeting location & time       │
     │──────────────────────────────────│
     │  Made by [name] — 2026  🍀      │  ← Footer
     └──────────────────────────────────┘
     ```
   - Point out the decisions: "How many pages? What goes on each page? What does the nav bar link to? What goes on the homepage vs. other pages?"
   - Show a second wireframe with a totally different layout — maybe a grid of project cards or a full-screen hero image with text overlay — to show there's no single right answer.

   ![Example wireframe sketch showing a web page layout with a title, banner area, three content sections, and a footer](../media/wireframe-example.svg)

#### Activity 1: Wireframe Your Website (20 min)

**Goal:** Every learner designs their website on paper before touching a computer.

**Tell learners:** "Open your Student Activity Guide to Activity 1. Grab the wireframe template and some colored pencils. You have 20 minutes to design YOUR page."

> **Your challenge:** Plan your website on paper. First, decide what pages your site will have — every website needs a homepage (`index.html`), plus at least one or two more pages (like "About," "Favorites," or "Gallery"). Then wireframe your homepage — this is the first page visitors see.
>
> Your wireframe should include:
> - A page title or site name
> - A **navigation bar** showing links to your other pages
> - At least 2–3 sections of content on the homepage (intro, highlights, links — whatever fits your idea)
> - A color scheme (pick 2–3 colors)
> - Some idea of layout — where does each element go?
> - Your name somewhere on the page (it's YOUR website!)
> - On the back of your paper: a quick list of what goes on each of your other pages

**Instructor notes:**
- Walk the room and ask questions: "What's your site about?" "Why did you pick that layout?" This validates their choices and keeps them engaged.
- If a learner is stuck on an idea, ask: "What could you talk about for 10 minutes without getting bored?" That's their website topic.
- If a learner finishes early, challenge them: "Sketch your second page too — what will it look like? Will it have the same layout as the homepage or a different one?"
- **Don't skip this activity.** Teens who design on paper first build better websites and make faster decisions when coding. The wireframe becomes their reference for the rest of the session.
- With 5 minutes left, ask 2–3 volunteers to hold up their wireframe and explain their design in 30 seconds. Celebrate creativity and variety.

> 👥 **GROUP ACTIVITY:** 2–3 volunteers share their wireframes with the class (30 seconds each).

---

### What Is Source Control? Intro to GitHub (0:55–1:15) — 20 min

**Goal:** Explain why source control matters and what GitHub is — in terms teens understand.

1. **The problem source control solves** (5 min)
   - "Raise your hand if you've ever had a file called `essay_final.docx`, then `essay_final_v2.docx`, then `essay_FINAL_REAL_final.docx`." (Expect laughs and raised hands.)
   - "Source control solves this. Instead of saving copies with weird names, it tracks every change you make — who changed what, when, and why. You can go back to any previous version at any time."
   - "It's like unlimited undo — but for your whole project, and it works across a team."

   **Instructor note:** The "final_v2_REAL_final" analogy works because every teen has done this. It's the single best hook for explaining version control.

2. **What is GitHub?** (5 min)
   - "GitHub is a website where people store and share code. It's like Google Drive, but specifically designed for code projects."
   - Key terms (keep it simple — refer learners to the glossary in their Student Activity Guide):
     - **Repository (repo)**: A folder for your project that lives on GitHub. It holds all your files and tracks their history.
     - **Commit**: A saved snapshot of your changes. Like pressing "save" but with a note about what you changed.
     - **Branch**: A copy of your project where you can try things without messing up the original (we won't use this today, but it's good to know).
     - **GitHub Pages**: A free feature that turns your repo into a live website.
   - "Over 100 million developers use GitHub. The code for Android, Python, VS Code, and thousands of other tools you use lives there. Today, YOUR code will live there too."

3. **Quick demo** (10 min) — Show your sample website repo on the projector:

   > 🖥️ **PROJECTOR:** Navigate your sample repo → show files → show code → show live site → show commit history.

   - Navigate to github.com and show your profile and the sample repo.
   - Open the repo: "See? It's just files — an `index.html` file and maybe a `style.css` file."
   - Click on `index.html` to show the code. "This is what a website looks like as source code."
   - Open the live GitHub Pages site in another tab. "And THIS is what it looks like when someone visits it. Same files — GitHub Pages just serves them as a website."
   - Show the commit history: "See these entries? Every time I saved a change, GitHub recorded it. I can go back to any version."
   - **Instructor note:** Don't dwell on advanced Git concepts (branching, merging, pull requests). The goal is "GitHub = a place to store your code and publish a website for free." Everything else is bonus context.

---

### Break (1:15–1:25) — 10 min

Encourage learners to step away from screens. Stretch, get water.

**Instructor note:** Use the break to:
- Check that github.com and your chosen AI tool(s) are accessible on the learners' devices/network.
- If you noticed confusion during the GitHub intro, plan a quick clarification after the break.
- Prepare your screen for the account-creation walkthrough.

**Transition note:** When the break ends: "Now we're going to get hands-on. You're going to create your own GitHub account, create your first repository, and by the end of the session, your website will be live on the internet."

---

### Block 2: Build It (1:25–2:50)

#### Activity 2: Create a GitHub Account & First Repo (1:25–1:50) — 25 min

**Goal:** Every learner has a GitHub account and a repository with an `index.html` file.

**Tell learners:** "Open your Student Activity Guide to Activity 2. Follow along as I demo each step on the projector."

##### Part A: Create a GitHub Account (10 min)

> 🖥️ **PROJECTOR:** Walk through the full GitHub signup live. Learners follow along on their own devices.

Walk through the signup live on the projector while learners follow along.

1. Go to **github.com** → **Sign up**.
2. Enter an email address, create a password, choose a username.
   - **Tip for the group:** "Your username becomes part of your website URL — like `yourname.github.io` — so pick something you'd be happy sharing. Keep it appropriate and memorable."
   - **If learners don't have email:** Some may not have their own email. Options:
     - Use a school-provided email if available.
     - Use a parent/guardian email with permission.
     - If neither works, pair them with a neighbor who has an account — they can work together on one repo.
3. Complete the verification puzzle (CAPTCHA).
   - **iPad tip:** If the CAPTCHA is hard to tap, try rotating the iPad to landscape mode — the puzzle pieces are bigger.
4. Skip the personalization survey (or fill it out — doesn't matter).
5. Confirm: everyone should see their GitHub dashboard.

**Instructor notes:**
- **Account creation is the biggest bottleneck.** Budget extra time here. CAPTCHA puzzles, email verification delays, and forgotten passwords will eat minutes. Stay calm and help individuals while the rest of the group waits.
- **Age requirement:** GitHub requires users to be 13+. If you have younger learners, pair them with an older partner or use a shared demo account. Don't ask learners to lie about their age.
- **Network issues:** Some school networks block GitHub or flag the signup page. If this happens, try a mobile hotspot as a backup. Test this before session day.

##### Part B: Create Your First Repository (15 min)

1. From the GitHub dashboard, click the **+** icon (top right) → **New repository**.
2. Repository name: `my-website` (or whatever fits their topic — tell them this becomes part of their URL).
3. Description: "My personal website" (optional but good practice).
4. Select **Public** (required for free GitHub Pages).
5. Check **Add a README file**.
6. Click **Create repository**.

Now they have a repo! Next, create the first file:

![Screenshot of a GitHub repository page showing the file list, Code tab, and Add file button](../media/github-repo-page.png)

7. In the repo, click **Add file** → **Create new file**.
8. Name it `index.html`.
9. Type a minimal starter (show this on the projector):

   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>My Website</title>
   </head>
   <body>
       <h1>Welcome to my site!</h1>
       <p>Coming soon...</p>
   </body>
   </html>
   ```

10. Scroll down. In the "Commit changes" section:
    - Commit message: "Add my first HTML file" (explain: "This is a note to your future self about what you just did").
    - Click **Commit changes**.

11. Click on `index.html` in the file list to verify it saved.

![Screenshot of the GitHub file view showing an HTML file with the edit pencil icon in the toolbar](../media/github-file-view.png)

**Instructor notes:**
- Walk the room constantly during this activity. Teens will mis-click, forget steps, or freeze at the commit message.
- The `index.html` filename matters — GitHub Pages looks for this specific file. If someone names it `Index.html` or `index.htm`, Pages won't find it. Call this out: "All lowercase, exactly `index.html`."
- If someone gets stuck, the Student Activity Guide has screenshots for every step. Point them to the guide.
- **Don't worry about the code being perfect.** The HTML they type here is a placeholder — the AI assistant will help them replace it with their real content later. But first, let's get this placeholder live on the internet!

#### Activity 3: Go Live with GitHub Pages (1:50–2:00) — 10 min

**Goal:** Every learner's placeholder website is live on the internet — before AI changes anything.

**Tell learners:** "Open your Student Activity Guide to Activity 3. Before we bring in AI, let's get your page live so you can see it for real."

##### Enable GitHub Pages

> 🖥️ **PROJECTOR:** Walk through Settings → Pages setup live. Learners follow along.

Walk through this live on the projector:

1. In your repo, click **Settings** (the gear icon near the top).
2. In the left sidebar, scroll down and click **Pages**.
3. Under "Source," select **Deploy from a branch**.
4. Under "Branch," select **main** and **/ (root)**.
5. Click **Save**.
6. Wait 1–2 minutes. Refresh the Settings → Pages page.
7. A green banner appears with your live URL: `https://<username>.github.io/<repo-name>/`
8. Click the link — YOUR WEBSITE IS LIVE!

![Screenshot of the GitHub Pages settings page showing the live site URL and deployment configuration](../media/github-pages-settings.png)

**Instructor notes:**
- **This is the first "wow" moment.** It's just "Welcome to my site! Coming soon..." but it's REAL. It's on the internet. Anyone in the world could visit that URL right now. Let them feel that.
- Say: "This is YOUR website. It's simple right now — but in a few minutes, we're going to use AI to completely transform it. Keep this tab open so you can see the before and after."
- **Expect delays.** GitHub Pages can take 1–3 minutes to deploy. If some learners' sites show a 404 error, tell them to wait and refresh. Don't troubleshoot immediately — it's almost always just a delay.
- **Common issues:**
  - 404 error after enabling Pages → Wait 2–3 minutes and refresh. If it persists, check that the file is named `index.html` (not `Index.html` or `index.htm`) and is in the root of the repo (not in a subfolder).
  - "Settings" not visible → Learner might not be in their own repo. Make sure they're at `github.com/<their-username>/<their-repo>`.
- Have everyone bookmark or remember their URL — they'll refresh it later to see the AI transformation.

![Flow diagram showing four steps: code on your device, push to GitHub, GitHub Pages builds it, live on the internet](../media/deployment-flow.svg)

---

#### What Is AI? How Can It Help You Code? (2:00–2:20) — 20 min

**Goal:** Explain AI in simple terms and show how it can help build websites.

1. **What is AI?** (5 min)
   - "AI — artificial intelligence — is software that can learn patterns and generate new content. You've probably used it without realizing it":
     - Autocomplete on your phone? AI.
     - Spotify's Discover Weekly playlist? AI.
     - Snapchat filters that track your face? AI.
     - Spell-check that suggests whole sentences in Gmail? AI.
   - "Today we'll use AI as a coding assistant. You'll describe what you want in plain English, and the AI will write the HTML and CSS code for you."
   - "There are lots of AI tools you can use — GitHub Copilot, Microsoft Copilot, ChatGPT, Google Gemini, and more. The prompts you write work the same way in all of them. We already used one to brainstorm website ideas earlier! For the coding demos, I'll be using **GitHub Copilot** because you already have it — it comes free with the GitHub account you just created — but feel free to use whichever AI tool you like."

   **Instructor note:** Don't over-explain how AI works (neural networks, training data, etc.). Teens need to know what it does, not how it works under the hood. Think of it like driving a car — you don't need to understand the engine to drive.

2. **AI is an assistant, not a replacement** (5 min)
   - "AI is really good at writing code from a description — but it doesn't know what YOU want. That's why you designed your page on paper first. Your wireframe is the plan. The AI is the helper that builds it."
   - "AI sometimes makes mistakes. It might write code that looks right but doesn't do exactly what you asked. That's normal — you'll learn to review and fix it."
   - **Key message:** "YOU are the designer and the decision-maker. The AI is a tool, like a calculator. It does the tedious work so you can focus on the creative work."

3. **Live demo: Ask AI to write HTML** (10 min)

   > 🖥️ **PROJECTOR:** Three-act demo — (1) generate a page with Microsoft Copilot, (2) generate another with a different AI tool to show inconsistency, (3) unify with GitHub Copilot.

   - **Introduce the base prompt.** Show this on the projector: "Every page you build today will start from the same base prompt. This ensures your HTML uses standard structure — proper headings, semantic elements, a nav bar — so we can apply one consistent stylesheet at the end."
   - Show the **base prompt** on the projector:

     > Write an HTML page called `[FILENAME]`. Use semantic HTML5 elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`. Use a heading hierarchy: `<h1>` for the page title, `<h2>` for section headings, `<h3>` for sub-headings. Include a `<nav>` bar at the top with links to: [LIST ALL YOUR PAGES]. Put all CSS in a `<style>` tag in the `<head>` — do NOT use inline `style=""` attributes on individual elements. Include `alt` text on all images. Make it responsive for mobile screens.
     >
     > This page is about: [DESCRIBE THIS PAGE'S CONTENT]
     > Style/colors: [YOUR PREFERENCES]

   - **Demo with Microsoft Copilot** (copilot.microsoft.com — no account needed). Fill in the base prompt:

     > Write an HTML page called `index.html`. Use semantic HTML5 elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`. Use a heading hierarchy: `<h1>` for the page title, `<h2>` for section headings, `<h3>` for sub-headings. Include a `<nav>` bar at the top with links to: Home (index.html), Projects (projects.html), and Meetings (meetings.html). Put all CSS in a `<style>` tag in the `<head>` — do NOT use inline style attributes on individual elements. Include alt text on all images. Make it responsive for mobile screens.
     >
     > This page is about: The homepage for a 4-H technology SPIN club called "Tech Explorers". Include a hero section with the club name and the 4-H clover emoji, an "About Our Club" section, and a section showing 3 current projects as styled cards. Include a footer with my name.
     > Style/colors: Green and white with dark text. Clean, modern, friendly.

   - Show the AI's response. Copy the code, paste it into `index.html` in your demo repo, commit, refresh.
   - "That took about 60 seconds. Now let me show you something cool — I'm going to use a **different** AI tool for the next page."
   - **Switch to ChatGPT** (or Google Gemini). Use the same base prompt but for `projects.html`:

     > Write an HTML page called `projects.html`. Use semantic HTML5 elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`. [same base rules]...
     >
     > This page is about: The "Projects" page for Tech Explorers. Show 3 project cards with titles, descriptions, and "What we learned" bullet lists.
     > Style/colors: Same green and white theme.

   - Paste into a new file in the repo, commit, refresh. Click "Projects" in the nav bar — it works! But point out: "Notice anything? The pages don't look exactly the same. Different colors, different spacing. That's because two different AI tools wrote the CSS independently. Each one made different choices."
   - **Now introduce GitHub Copilot for the integration step.** Open [github.com/copilot](https://github.com/copilot) and type:

     > I have a multi-page website with these HTML files: index.html and projects.html. Each page has its own `<style>` tag with CSS. I want you to: (1) Extract all the CSS into a single shared file called `style.css`. (2) Remove the `<style>` tags from both HTML files and replace them with `<link rel="stylesheet" href="style.css">`. (3) Make the styling consistent across both pages — same colors, fonts, spacing, nav bar, and footer style. Use the green-and-white theme. (4) Keep the HTML content and structure of each page the same — only change the styling.

   - Show the result — Copilot produces three files: the updated `index.html`, updated `projects.html`, and the new `style.css`. Paste each one into the repo, commit, refresh.
   - **The big reveal:** "Now look — both pages have exactly the same look and feel. And here's the magic: if I change ONE thing in `style.css` — say I change the background color — it changes on EVERY page at once." Make a quick edit to `style.css`, commit, refresh. "That's the power of a shared stylesheet. That's how real websites work."

   **Instructor notes:**
   - **This demo has three acts: generate, compare, unify.** Act 1 (generate) shows AI writing code. Act 2 (compare) shows the problem — inconsistency. Act 3 (unify with Copilot) shows the professional solution. Don't rush Act 2 — the inconsistency is the teaching moment.
   - **Why different AI tools?** Two reasons: (1) It conserves each tool's free-tier limits — spreading across tools means no one runs out. (2) It proves the prompts are tool-agnostic — any AI can write HTML from the same instructions. (3) It sets up the integration moment where Copilot adds the most value.
   - **The base prompt matters.** Because every page uses semantic HTML5 elements and standard headings, Copilot can target `h1`, `h2`, `nav`, `section`, etc. with simple CSS selectors. If each page used random `<div>` structures, unification would be much harder. Point this out: "See why we used a standard base prompt? It's like building with LEGO — standard pieces snap together."
   - **The prompt matters.** Show learners that a detailed prompt ("dark purple background, gold accents, top 5 albums as cards") gets better results than a vague one ("make a website"). This is a real skill — it's called prompt engineering.
   - **If the AI generates bad code:** That's actually a teaching moment. Say: "See? The AI isn't perfect. We need to check its work." Fix it together.
   - **Save GitHub Copilot for integration.** Since Copilot's free tier has a monthly message limit, using it for the high-value integration step (rather than individual page generation) makes the most of the allowance.

#### Activity 4: Use AI to Build Your Website (2:20–3:00) — 40 min

**Goal:** Every learner builds a multi-page website using multiple AI tools for page generation, then uses GitHub Copilot to unify everything with a shared stylesheet — learning separation of concerns along the way.

**Tell learners:** "Open your Student Activity Guide to Activity 4. Grab your wireframe — you're going to build ALL the pages of your website. Each page will be generated by a different AI tool, and then GitHub Copilot will wire them together with a professional shared stylesheet. Your site is already live, so you'll see it transform in real time."

##### Part A: Build Your Pages with AI (2:20–2:45) — 25 min

**Tell learners:** "You're going to use a different AI tool for each page. This is intentional — it shows you that the same prompt works everywhere, it spreads the load across free tools so nobody runs out, and it sets up a cool moment at the end."

1. **Show the AI tool list** on the projector. Tell learners to pick a different tool for each page:

   **No account needed — just open and go:**

   | AI Tool | URL |
   |---|---|
   | Microsoft Copilot | [copilot.microsoft.com](https://copilot.microsoft.com) |
   | Meta AI | [meta.ai](https://meta.ai) |

   **Free account required:**

   | AI Tool | URL | Account |
   |---|---|---|
   | ChatGPT | [chatgpt.com](https://chatgpt.com) | Free tier |
   | Google Gemini | [gemini.google.com](https://gemini.google.com) | Google account (most of you have one) |
   | Perplexity | [perplexity.ai](https://www.perplexity.ai) | Free tier |
   | Mistral Le Chat | [chat.mistral.ai](https://chat.mistral.ai) | Free account |
   | HuggingChat | [huggingface.co/chat](https://huggingface.co/chat) | Free account |

   **Save for Part B (CSS unification):**

   | AI Tool | URL | Why save it? |
   |---|---|---|
   | GitHub Copilot | [github.com/copilot](https://github.com/copilot) | Uses their GitHub account. Free tier has limited messages — save them for the unification step! |

   > **Important:** Save GitHub Copilot for Part B — that's where it adds the most value. Use the other tools for building individual pages.

2. **Show the base prompt** on the projector. Every page starts from this same template — it ensures consistent HTML structure so the final unification step works:

   > Write an HTML page called `[FILENAME]`. Use semantic HTML5 elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`. Use a heading hierarchy: `<h1>` for the page title, `<h2>` for section headings, `<h3>` for sub-headings. Include a `<nav>` bar at the top with links to: [LIST ALL YOUR PAGES]. Put all CSS in a `<style>` tag in the `<head>` — do NOT use inline `style=""` attributes on individual elements. Include `alt` text on all images. Make it responsive for mobile screens.
   >
   > This page is about: [DESCRIBE THIS PAGE'S CONTENT]
   > Style/colors: [YOUR PREFERENCES]

3. **Learners build page by page.** For each page:
   - Open a different AI tool from the list
   - Paste the base prompt, fill in the blanks for that page
   - Copy the generated code
   - In their GitHub repo: **Add file** → **Create new file** (or edit `index.html` for the homepage)
   - Name the file to match their nav link
   - Paste the code, write a commit message, click **Commit changes**
   - Refresh their live site to see the new page

4. **Encourage 3–5 pages.** The more pages they build with different tools, the more dramatic the unification step will be.

![Site map diagram showing three HTML pages — index.html, page2.html, and page3.html — connected by double-headed arrows labeled nav](../media/nav-site-map.svg)

**Instructor notes:**
- Walk the room during this phase. Help learners fill in the base prompt for each page. The base prompt stays the same — only the filename, content description, and style preferences change.
- **The base prompt is the key to this whole approach.** Because it forces semantic HTML (`header`, `nav`, `main`, `section`, `footer`) and standard headings (`h1`, `h2`, `h3`) with no inline styles, GitHub Copilot can target everything with simple CSS selectors later. Explain it like LEGO: "Standard pieces snap together. Random pieces don't."
- **Source control in action — call out the diff!** After they paste their homepage and before they click "Commit changes," pause and point to the diff view on the projector. GitHub highlights deleted lines in **red** and new lines in **green**. Say: "See this? GitHub is showing you exactly what changed — the red lines are the old placeholder code being removed, and the green lines are your new AI-generated code being added. This is source control at work." Don't skip this.
- **iPad paste shortcut:** `Cmd+A` / `Cmd+V` works if they have a physical keyboard. Without a keyboard, the tap-and-hold → Select All → Paste flow works but is slower — budget an extra couple of minutes.
- **iPad copy tip:** Most AI tools show a **clipboard icon** or **"Copy" button** on code blocks — tap that instead of trying to select all the code by hand. It's faster and avoids accidentally missing lines.
- **Common prompt mistakes:**
  - Too vague: "Make me a website" → AI doesn't know the topic, style, or content
  - Too specific about code: "Use flexbox with gap: 20px" → Teens don't know CSS yet
  - Just right: "A fan page for Taylor Swift with a pink and purple gradient, a big hero image area, a section listing my favorite songs, and a section with links to her social media"
- **Select-all shortcut** (for replacing `index.html`): Remind the group: `Ctrl+A` (Windows/Chromebook) or `Cmd+A` (Mac) selects all text. Then paste with `Ctrl+V` / `Cmd+V`.
- After a few learners have 2+ pages live, point out the inconsistency: "Look at your pages. Do they look like they belong together? Probably not — different AI tools made different styling choices. That's the problem we're going to fix next."
- **If an AI tool is blocked on the network:** The tool list has 5 options — if one is blocked, they have 4 others. If ALL are blocked, provide pre-generated HTML templates from the appendix.

##### Part B: Unify with GitHub Copilot (2:45–2:55) — 10 min

**Goal:** GitHub Copilot extracts all CSS into a shared `style.css` file and makes every page look consistent — teaching separation of concerns.

**Tell learners:** "Look at your pages — they each have their own styles embedded in them, and they probably look different from each other. That's because different AI tools wrote the CSS independently. Now we're going to use GitHub Copilot to fix this — it's going to pull all the CSS out into one shared file and make everything look consistent."

1. **Open GitHub Copilot** at [github.com/copilot](https://github.com/copilot).
2. **Paste this unification prompt** (show it on the projector — learners should fill in their specifics):

   > I have a multi-page website in my GitHub repo with these HTML files: [LIST YOUR FILES, e.g., index.html, about.html, favorites.html, gallery.html]. Each page has its own `<style>` tag with CSS. I want you to:
   > 1. Create a single shared CSS file called `style.css` with all the styling.
   > 2. Give me updated versions of each HTML file with the `<style>` tag removed and replaced with `<link rel="stylesheet" href="style.css">` in the `<head>`.
   > 3. Make the styling consistent across ALL pages — same colors, fonts, spacing, nav bar style, and footer.
   > 4. Keep all the HTML content and structure of each page the same — only change the styling.
   > Style/colors: [YOUR COLOR SCHEME AND VIBE]

3. **Apply the changes to their repo:**
   - First, create the new `style.css` file: **Add file** → **Create new file** → name it `style.css` → paste the CSS → commit.
   - Then update each HTML file: click the file → pencil icon → replace the content → commit.
   - Refresh the live site.

4. **The big reveal.** "Now click through your pages. They all match! Same colors, same fonts, same nav bar, same footer. And here's the real power — if you change ONE thing in `style.css`, it changes on EVERY page at once."

**Instructor notes:**
- **This is the "professional developer" moment.** When all their pages suddenly look consistent, teens realize their site went from "school project" to "real website." Celebrate it.
- **Call out what happened:** "Before, each page had its own styling buried inside it. Now all the styling lives in one file — `style.css`. In the real world, this is called **separation of concerns** — HTML handles the content, CSS handles the look. Professional websites always work this way."

![Before and after diagram showing three HTML files with separate inline styles on the left, versus three HTML files sharing one style.css file on the right](../media/separation-of-concerns.svg)

- **Show the power of a shared stylesheet.** Open `style.css`, change one color (e.g., the background), commit, refresh. "See? I changed ONE line in ONE file, and every page updated. That's why you separate CSS from HTML."
- **Source control moment:** The diff view for this step is dramatic. All the `<style>` blocks are red (removed), and the single `<link>` tag is green (added). "Look at how much cleaner each HTML file is now. Source control shows you the cleanup."
- If a learner has only one page, the unification step still works — it moves the CSS to a separate file, which is still the right practice. But encourage them to build at least 2 pages so they see the consistency benefit.
- **Copilot may need 2–3 messages.** It might give you `style.css` and updated `index.html` in one response, then you ask for the updated `about.html`, etc. That's fine — it's still way fewer messages than generating every page from scratch.

##### Part C: Polish & Iterate (2:55–3:00) — 5 min

1. Learners refresh their live site and click through all their pages. Everything should look consistent now.
2. If they want changes, they can:
   - Edit `style.css` to change colors, fonts, or spacing across ALL pages at once
   - Edit any individual HTML file to change content on that page
   - Commit each change and refresh to see it live
3. **Challenge:** "Change one thing in `style.css` — a color, a font size, anything — and watch it change on every page at once."

**Instructor notes:**
- This iteration loop — edit, commit, refresh — is the core workflow of professional web development. Call it out: "What you're doing right now is exactly what professional developers do every day."

![Circular workflow diagram showing three steps — Edit, Commit, Refresh — connected by arrows in a continuous cycle](../media/edit-commit-refresh.svg)

---

### Customize & Polish (3:00–3:15) — 15 min

**Goal:** Open-ended time to improve their sites using the edit → commit → refresh cycle.

> **Ideas from your Student Activity Guide:**
> - **Add more pages** — each one is just a new HTML file with the standard base prompt, generated by any AI tool. Add `<link rel="stylesheet" href="style.css">` in the `<head>` so it picks up your shared styles automatically.
> - **Edit `style.css`** to change the look of ALL pages at once — colors, fonts, spacing, borders
> - Ask an AI tool to suggest improvements to your `style.css`: "Make the nav bar sticky so it stays at the top when I scroll"
> - Add a new section to any page (playlist, gallery, shout-outs, links)
> - Ask the AI for a completely different visual style: "Redesign my `style.css` to look like a retro video game menu" — all pages change at once!
> - Add a link to your favorite YouTube video or playlist
> - **Accessibility check:** Ask the AI: "Check my `style.css` for accessibility — does it have good color contrast and proper font sizing?"
> - Try viewing your site with your browser zoomed to 200% — does it still look good? That's an accessibility win!

**Instructor notes:**
- Walk around and encourage experimentation. Editing `style.css` and seeing all pages change at once is the most powerful reinforcement of separation of concerns.
- This is great time for learners to add more pages or polish existing ones. The edit → commit → refresh loop is the core workflow of professional development — call it out.
- If someone's site breaks after an edit, this is a **teaching moment about source control**: show them how to click on "commits" in the repo, find the previous working version, and view the old code. They can copy-paste the working version back. "This is exactly why source control exists — you can always go back."
- Don't pressure anyone to keep coding if they're happy with their site. Some learners will want to browse others' sites instead — that's fine.

---

### Showcase & Wrap-Up (3:15–3:30) — 15 min

1. **Share URLs & gallery walk** (5 min)

   > 👥 **GROUP ACTIVITY:** Learners paste URLs into shared doc, visit each other's sites, and give one compliment to a neighbor.

   - Have each learner paste their URL into a shared doc, chat, or call it out. The format is always `https://<username>.github.io/<repo-name>/`.
   - Quick gallery walk: learners visit each other's sites by typing in the URLs.
   - Pair feedback: each learner visits a neighbor's site and tells them one thing they like about it.
   - **Instructor note:** This sharing moment builds community and validates the work. Teens who see their name on a real URL with a real website feel genuine accomplishment. Encourage them: "This URL works from any device, anywhere in the world. Text it to someone right now."

2. **Showcase** (5 min)

   > 🖥️ **PROJECTOR:** Navigate to 4–5 volunteer sites on the projector. Quick applause after each.

   - Ask 4–5 volunteers to share their screen or call out their URL while you navigate to it on the projector.
   - Quick applause after each demo.
   - **Instructor note:** Keep feedback specific: "I love your color scheme — the dark background really makes the text pop" or "The way you organized your content into cards looks super professional." Connecting their choices to design concepts reinforces the learning.

3. **Wrap-up discussion** (3 min)
   - *What was your favorite part of today?*
   - *What surprised you about building a website?*
   - *What would you add to your site if you had more time?*

4. **What's next?** (2 min) — Give learners a path to keep going:
   - **Keep editing your site**: Go to github.com, open your repo, edit `index.html`, commit, and your site updates automatically.
   - **Learn HTML & CSS**: freeCodeCamp.org (free, beginner-friendly) or Khan Academy's "Intro to HTML/CSS" course.
   - **Keep using AI to learn**: Ask any AI assistant to explain any code it wrote — "What does this CSS do?" is a great way to learn.
   - **Explore GitHub**: Browse github.com/explore to see open-source projects. Look at other people's code, remix ideas, and build more sites.
   - **Upgrade your GitHub account — for free**: Middle-school and high-school students can verify at github.com/education/students to get **GitHub Copilot Student** and the **Student Developer Pack** at no cost. It includes upgraded Copilot, free cloud dev environments, and dozens of pro tools. No credit card required — just a school email or enrollment document.
   - **Share your URL**: Your site is live — text the link to friends and family!

---

## Concepts Covered (Summary)

| Concept | Where it was taught | How learners applied it |
|---|---|---|
| Website structure (HTML/CSS) | "What Is a Website?" lecture | Reviewing and editing AI-generated code |
| Multi-page site structure | Wireframing + AI demo | Planning pages, creating nav bars, building pages with different AI tools |
| Separation of concerns (CSS) | AI demo (unification step) + Part B | Extracting inline CSS into shared `style.css`; editing one file to change all pages |
| Design / wireframing | Activity 1 | Paper wireframe of their homepage + site map |
| Source control | "Intro to GitHub" lecture | Creating repos, committing changes, viewing diffs and history |
| Repositories & commits | Activity 2 | Creating a repo and committing `index.html` |
| Publishing / deployment | Activity 3 | Enabling GitHub Pages, seeing placeholder live |
| AI-assisted coding | "What Is AI?" lecture + Activity 4 | Using multiple AI tools to generate HTML pages |
| AI tool comparison | Activity 4 Part A | Using different AI tools for different pages, seeing varied output |
| Prompt engineering | Activity 4 | Writing detailed prompts, using a standard base prompt, iterating on AI output |
| Iteration & debugging | Parts B–C + Customize | Edit → commit → refresh cycle; editing `style.css` to change all pages |
| Accessibility (WCAG) | "What Is a Website?" lecture + base prompt | Including contrast, alt text, and headings in every AI prompt |

---

## Troubleshooting

| Issue | Solution |
|---|---|
| GitHub signup blocked by network | Try a mobile hotspot. If that fails, pair learners on a shared account. Test network access before session day. |
| Email verification delayed | Check spam/junk folder. Some email providers delay GitHub verification by a few minutes. Learner can continue with repo creation while waiting. |
| AI tool blocked by network | Switch to Microsoft Copilot (copilot.microsoft.com — no account needed) or Meta AI (meta.ai — no account needed). With 7 tools on the list, at least one should work. As a last resort, provide pre-generated HTML templates from the appendix. |
| GitHub Pages shows 404 | Wait 2–3 minutes and refresh. Check that the file is named exactly `index.html` in the root of the repo. Check Settings → Pages to confirm the branch is set to `main` and `/ (root)`. |
| AI generated broken HTML | Paste the broken code and the error into the AI: "This code isn't working correctly. Can you fix it?" Or use the backup template. |
| "My page looks different from the AI preview" | AI tools often show a preview that doesn't match exactly. The GitHub Pages version is the real one. Iterate from there. |
| Learner has no email for GitHub | Pair with a neighbor, use a school/parent email, or use a shared demo account. |
| Learner is ahead of the group | Challenge them: add a third or fourth page, experiment with different page layouts, try linking to an external CSS file, or help a neighbor. |
| Learner is stuck or frustrated | Pair them with a neighbor. Reduce scope: "Just get a title and one section on the page." Celebrate small wins. |
| Commit failed or file not saving | Check that the learner is signed in to their own account and in their own repo. Re-do the commit steps. |
| iPad keyboard isn't responding | Disconnect and reconnect the keyboard (for Bluetooth: toggle Bluetooth off/on in Settings). If using Smart Keyboard or Magic Keyboard, detach and re-attach. |
| Copy-paste not working on iPad | Use the clipboard/copy button in the AI tool (not manual text selection). For paste, tap and hold in the GitHub editor → "Paste". If nothing pastes, go back to the AI tool and re-copy. |
| iPad Split View not working | Requires iPadOS 15+. Open Safari, then drag a tab from the tab bar to the left or right edge of the screen. Some older iPad models don't support Split View. |
| iPad screen too small for code editing | Rotate to landscape mode. If available, use a keyboard with the iPad for a better editing experience. |

---

## Materials Checklist

- [ ] iPads (1 per learner, **fully charged** — a 3.5-hour session will drain a battery)
- [ ] iPad charging cables and power sources at each table (backup)
- [ ] Physical keyboards for iPads — Smart Keyboard, Magic Keyboard, or Bluetooth (strongly recommended)
- [ ] Reliable Wi-Fi (test github.com and AI tool access **on an iPad** beforehand)
- [ ] Projector or shared display for demos (AirPlay, adapter, or demo from a laptop)
- [ ] **Student Activity Guides — iPad Edition** (1 per learner, printed or shared digitally)
- [ ] **Paper wireframe templates** (1 per learner, printed)
- [ ] Colored pencils or markers (1 set per table)
- [ ] Whiteboard or flip chart + markers
- [ ] Sticky notes (for icebreaker)
- [ ] Timer (phone or projected)
- [ ] Pre-built sample website repo with GitHub Pages enabled (for demos)
- [ ] Backup HTML templates (in case AI tools are blocked — include in Student Activity Guide appendix)
- [ ] A shared doc or chat channel for learners to share their live URLs
