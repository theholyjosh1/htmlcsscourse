<div align="center">

# HTML & CSS: Zero to Master

**A complete, project-driven course that takes you from no experience to building and shipping real web pages.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Slides](https://img.shields.io/badge/slides-148-7C5CFF?style=flat-square)](#whats-included)
[![Modules](https://img.shields.io/badge/modules-7-22D3EE?style=flat-square)](#course-map)
[![Level](https://img.shields.io/badge/level-beginner%20to%20master-4ADE80?style=flat-square)](#suggested-pace)

**7 modules · 148 slides · 11 typed code boxes · 5 projects · 3 capstones**

[Quick start](#quick-start) · [Course map](#course-map) · [Use your own AI](#use-your-own-ai-as-your-reviewer) · [Exercises](#exercise-index) · [FAQ](#faq)

</div>

---

## What this is

A full HTML and CSS curriculum delivered as seven PowerPoint decks. It assumes **zero** prior experience: no tags, no selectors, no command line, no design background.

Each deck is one module. Each module mixes short concept slides, annotated code examples, a quiz with an answer key, and practice slides with a **dashed code box** you type into. At the end of every module there is a project brief.

The course is deliberately framework-free. You learn the platform — semantic HTML, the box model, the cascade, Flexbox, Grid, responsive design, accessibility, motion — before touching a tool that hides it.

> **If someone sent you this folder:** you do not need to know anything about the course, PowerPoint, or web development. Read [If someone sent you these files](#if-someone-sent-you-these-files), then start at deck `00`.

---

## What's included

| Deck | Slides | Focus | Module project |
|---|---:|---|---|
| [`00-Start-Here-and-Course-Map.pptx`](00-Start-Here-and-Course-Map.pptx) | 8 | Setup, roadmap, submission format | — |
| [`01-HTML-Foundations.pptx`](01-HTML-Foundations.pptx) | 22 | Tags, text, lists, links, images, paths | Recipe page |
| [`02-Semantic-HTML-and-Forms.pptx`](02-Semantic-HTML-and-Forms.pptx) | 22 | Landmarks, tables, forms, accessibility | Profile page |
| [`03-CSS-Fundamentals.pptx`](03-CSS-Fundamentals.pptx) | 26 | Selectors, box model, typography, cascade | Style the recipe page |
| [`04-Layout-Flexbox-and-Grid.pptx`](04-Layout-Flexbox-and-Grid.pptx) | 25 | Positioning, Flexbox, Grid, responsive | Responsive landing page |
| [`05-Advanced-CSS-and-Motion.pptx`](05-Advanced-CSS-and-Motion.pptx) | 25 | Tokens, transitions, modern selectors, performance | Component library |
| [`06-Mastery-Projects-and-Practice.pptx`](06-Mastery-Projects-and-Practice.pptx) | 20 | Architecture, audits, deployment, career | 3 capstone projects |

Also included:

- [`COURSE-OUTLINE.md`](COURSE-OUTLINE.md) — every slide, in order, for navigation.
- `course/` — the Python source that generated the decks, if you want to edit or restyle them.

---

## Quick start

1. **Download the folder** (or clone the repository) and keep all seven decks together.
2. Open **`00-Start-Here-and-Course-Map.pptx`** first. It covers setup and the submission format.
3. Do the 30-minute toolkit setup on slide 6: VS Code, Live Server, Chrome.
4. Open **`01-HTML-Foundations.pptx`** and complete practice **M1.1**.
5. Paste your code into your AI using [the review prompt](#step-1--give-your-ai-its-role-one-time-per-chat), or send it to whoever gave you the course.

Work in order. Each module assumes the one before it.

**Requirements:** PowerPoint 2016+, Keynote, or Google Slides. Fonts are Arial and Consolas; if they are missing, the layout still holds with any sans-serif and monospace substitute.

---

## How the code boxes work

Practice slides are laid out in two halves:

```
┌─────────────────────────────┬──────────────────────────────────────┐
│  YOUR BRIEF                 │  YOUR CODE — TYPE IN THE BOX         │
│  • what to build            │  ┌────────────────────────────────┐  │
│  • constraints              │  │  click here, select all, type  │  │
│                             │  │                                │  │
│  MUST INCLUDE               │  │                                │  │
│  ✓ checklist                │  └────────────────────────────────┘  │
└─────────────────────────────┴──────────────────────────────────────┘
```

1. Open the deck in **normal editing view** — not Slide Show.
2. Click inside the dashed box.
3. Select the placeholder or starter code with `Cmd + A` / `Ctrl + A`, then type or paste your code.
4. Check the **must include** list on the left before you submit.
5. Copy everything from the box into your AI chat.

The box is a real, editable PowerPoint text box. It is not an image, a form field, or a macro. If you prefer to build in VS Code, do that — the box is only a convenient place to assemble your submission.

---

## If someone sent you these files

You have been handed a self-contained course. Here is all you need to know:

1. **Seven `.pptx` files = seven modules.** Open them in number order, starting with `00`.
2. **Each deck is a lesson, not a reference manual.** Read the slides, then do the practice.
3. **Practice slides have a dashed code box** on the right. Click it in editing view and type your answer.
4. **You do not need to send the PowerPoint anywhere.** Your AI only needs the exercise brief and the code you wrote.
5. **Use the prompts below.** The first one teaches the AI how to review this specific course. After that, each submission is a short copy-paste.
6. **You can use any AI.** ChatGPT, Claude, Gemini, Copilot, a local model — the prompts are plain text and tool-agnostic.

The course does not require an account, a server, or any software beyond a browser and an editor.

---

## Use your own AI as your reviewer

You can get useful, structured feedback without a teacher. The trick is to give the AI three things every time:

1. **The lesson code** — e.g. `M4.2`.
2. **The brief** — what the exercise asked for, including the must-include list.
3. **Your code and the symptom** — what you expected versus what happened.

You do **not** need to upload the deck for code review. Pasting the brief and your code is faster, more reliable, and keeps the chat focused.

### Step 1 — Give your AI its role (one-time per chat)

Open a new chat and paste this **before** your first submission:

```text
You are my code reviewer for a beginner course called "HTML & CSS: Zero to Master".

Context you need:
- The course is 7 PowerPoint modules, starting from zero experience.
- Each exercise has a lesson code (for example M3.1) and a brief with a
  "must include" checklist.
- I will paste the lesson code, the brief, my code, and what I expected.
- The course uses plain HTML5 and CSS only: no frameworks, no build tools,
  and no JavaScript unless the brief asks for it.

Review my submission in this order:
1. Validity: unclosed tags, wrong nesting, missing quotes or braces.
2. Checklist: which "must include" items pass and which fail.
3. Semantics and accessibility: headings, labels, alt text, focus, contrast.
4. Layout: box model, spacing, overflow, units, responsive behaviour.
5. Maintainability: naming, repetition, dead CSS, selector weight.
6. Craft: typography, alignment, colour, finish. Comment on this last.

Reply in this format:
- One-line verdict: PASS / PASS WITH FIXES / REVISE.
- Up to 3 fixes, most important first. For each one: what is wrong,
  why it matters, and the smallest change that fixes it.
- A corrected snippet only for the broken part. Never rewrite the whole file.
- One question that makes me think.
- Beginner language. Define any term you introduce.

Do not rewrite the exercise for me. Do not add features or libraries the
brief did not ask for. If my code is correct, say so and give me one
stretch challenge.

My first submission follows.
```

That prompt works with any capable chat model. You only paste it once per conversation; the AI keeps the role for the rest of the chat.

### Step 2 — Submit an exercise

Replace the angle-bracket lines and paste:

```text
LESSON: M1.1
TASK:
<paste the brief and the "must include" list from the slide>

MY CODE:
<paste everything from the dashed box>

WHAT I EXPECTED:
<one sentence>

WHAT ACTUALLY HAPPENED:
<one sentence, or "not sure">

WHAT I TRIED:
<one or two things>
```

A complete first submission looks like this:

```text
LESSON: M1.1
TASK:
Build a page with a full HTML skeleton, an h1 with my name,
a paragraph on why I am learning, and one comment.
Must include: doctype, lang, charset, viewport, title, h1, p, comment.

MY CODE:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My first page</title>
</head>
<body>
  <!-- my first page -->
  <h1>Sam Taylor</h1>
  <p>I want to build my own portfolio.</p>
</body>
</html>

WHAT I EXPECTED:
A page with my name and one sentence.

WHAT ACTUALLY HAPPENED:
It works, but the tab says "My first page" and I am not sure if that is right.

WHAT I TRIED:
Renaming the file to index.html and refreshing Live Server.
```

The more specific your "what happened" is, the more specific the feedback will be.

### Step 3 — Work the feedback, one change at a time

Do not apply five fixes and then test. Apply one, save, refresh, look. If the fix works, keep it and move to the next. If it breaks something else, you have found the cause.

Then resubmit with:

```text
I applied fix 1 and 2. Here is the new code. Fix 3 did not work:
<what happened instead>. Can you explain why?
```

This loop — submit, fix one thing, resubmit — is the course method. It is also how professional code review works.

### Step 4 — Extra prompts that help

**When you are stuck (before asking for the answer):**

```text
I am stuck on <lesson code>. Here is the task, my code, and the exact symptom.
Ask me up to 3 questions before you answer. Then give me one next step,
not the whole solution.
```

**To be quizzed on a module (attach the deck if your AI can read files):**

```text
Using the attached deck, quiz me on Module <number>. Ask one question at a
time and wait for my answer. Do not open the answer-key slides until I ask.
At the end, list what I got wrong and which slides I should review.
```

**To have a slide explained:**

```text
Explain slide <number> of the attached deck in plain language. Use one
analogy and one tiny code example. Then ask me a question to check that
I understood.
```

**If your AI cannot read `.pptx` files**, that is fine. The deck is not required for code review. For explanations, copy the slide's text and paste it with: *"Explain this slide to a beginner."*

### Which AI tools can read the decks?

| Tool | Can usually read `.pptx`? | Best approach |
|---|---|---|
| ChatGPT | Yes, with file uploads | Attach the deck for quizzes and explanations; paste code for reviews |
| Claude | Yes, with file uploads | Attach the deck for quizzes and explanations; paste code for reviews |
| Gemini | Yes, with file uploads | Attach the deck for quizzes and explanations; paste code for reviews |
| Copilot | Depends on the product | Paste the slide text and your code |
| Local / other models | Often no | Paste the slide text and your code |

Capabilities change. If file upload is unavailable, copying the text always works.

> **Careful:** speaker notes contain teaching notes and quiz answers. If you want to be quizzed, tell the AI not to open the answer-key slides, or paste only the slide text you want to discuss.

### Rules for a review that actually helps

- **Paste code as text.** Screenshots cannot be copied, tested, or diffed.
- **One exercise per message.** Mixing two tasks produces vague feedback.
- **Always include the brief.** Without it, the AI invents requirements.
- **Say what you expected.** "It looks wrong" is hard to debug; "the cards should be in one row, but they stack" is not.
- **Ask for the smallest fix**, not a rewrite. You learn from the diff.
- **Do not let the AI add libraries** or features the exercise did not ask for.
- **Verify every fix in the browser.** The AI cannot see your rendered page.
- **Run the validator** at [validator.w3.org](https://validator.w3.org/) before you submit HTML.
- **Keep a mistakes file.** One line per bug you fixed. It becomes your personal reference.

AI reviewers are confident and sometimes wrong. If a suggestion contradicts the slides, the browser, or the validator, trust the browser and ask the AI to reconcile the difference.

### Privacy

The decks contain no personal data. Your code might contain your name or email; remove it if you care. Uploading files or code to a third-party AI is governed by that provider's terms, not by this course.

---

## Course map

| # | Module | You learn | You build |
|---|---|---|---|
| 00 | **Start here** | Tools, workflow, how to submit | — |
| 01 | **HTML Foundations** | Elements, attributes, text, lists, links, images, file paths | A recipe page |
| 02 | **Semantic HTML & Forms** | Landmarks, sections, tables, forms, validation, accessibility | A profile page |
| 03 | **CSS Fundamentals** | Selectors, colour, typography, box model, units, cascade | A styled recipe page |
| 04 | **Layout** | Positioning, Flexbox, Grid, media queries, container queries | A responsive landing page |
| 05 | **Advanced CSS** | Custom properties, transitions, transforms, animation, modern selectors, performance | A component library |
| 06 | **Mastery** | Architecture, audits, Git, deployment, portfolio strategy | Three capstone projects |

By the end you can build a responsive, accessible page from a blank file and explain every decision in it.

---

## Exercise index

| Code | Exercise | Deck |
|---|---|---|
| `M1.1` | Build your first page | 01 |
| `M1.2` | Three things I like — lists, links, images | 01 |
| `M1-PROJECT` | Recipe page in HTML only | 01 |
| `M2.1` | Signup form with labels and fieldsets | 02 |
| `M2.2` | Semantic blog article | 02 |
| `M2-PROJECT` | Personal profile page | 02 |
| `M3.1` | Style a profile card | 03 |
| `M3.2` | Build a readable article | 03 |
| `M3-PROJECT` | Style the recipe page | 03 |
| `M4.1` | Responsive navbar | 04 |
| `M4.2` | Responsive gallery | 04 |
| `M4.3` | Full landing page layout | 04 |
| `M4-PROJECT` | Responsive landing page | 04 |
| `M5.1` | Animate a card like a professional | 05 |
| `M5.2` | Two-theme token system | 05 |
| `M5-PROJECT` | Five-component library | 05 |
| `CAPSTONE-1` | Personal portfolio, deployed | 06 |
| `CAPSTONE-2` | Analytics dashboard | 06 |
| `CAPSTONE-3` | Product site + design system | 06 |

---

## Suggested pace

**Standard — 8 to 10 weeks, 1–2 hours a day.** One module every 1–2 weeks. Finish the project before moving on.

**Intensive — 30 days.** Follow the plan on slide 17 of deck 06: rebuild earlier projects from memory, then complete the three capstones.

Either way:

- Type examples by hand. Copy-paste feels like learning and is not.
- Rebuild each project from memory two days after finishing it.
- Keep every project in its own folder. Module 3 styles the Module 1 page; Module 4 makes it responsive; Module 5 adds polish.
- Do not start Module 6 until one page works at 320px without horizontal scrolling.

---

## What a good review covers

Use this rubric whether the reviewer is an AI, a friend, or an employer.

| Area | What good looks like |
|---|---|
| **Validity** | Tags closed and nested correctly, quoted attributes, no stray characters, validator clean |
| **Semantics** | Right element for the job, one `h1`, logical heading order, labels tied to inputs |
| **Layout** | Spacing from the box model, no magic numbers, no overflow at 320px |
| **Responsive** | Mobile-first `min-width` queries, fluid type and images, usable at 200% zoom |
| **Accessibility** | Keyboard reachable, visible focus, meaningful `alt`, 4.5:1 contrast, reduced-motion respected |
| **Maintainability** | Predictable class names, tokens instead of repeated values, flat specificity, no dead CSS |
| **Craft** | Consistent spacing, readable line length, deliberate hierarchy, finished hover and focus states |

If a review only talks about colour, it is not a review.

---

## Repository structure

```text
.
├── 00-Start-Here-and-Course-Map.pptx
├── 01-HTML-Foundations.pptx
├── 02-Semantic-HTML-and-Forms.pptx
├── 03-CSS-Fundamentals.pptx
├── 04-Layout-Flexbox-and-Grid.pptx
├── 05-Advanced-CSS-and-Motion.pptx
├── 06-Mastery-Projects-and-Practice.pptx
├── README.md
├── COURSE-OUTLINE.md
└── course/
    ├── build.py
    ├── deck_lib.py
    └── content_m00.py ... content_m06.py
```

The `course/` folder is optional. It exists so the decks can be regenerated, restyled, or translated without editing 148 slides by hand.

---

## Rebuilding the decks

Requires Python 3.9+ and `python-pptx`.

```bash
cd course
pip install python-pptx
python3 build.py
```

This writes the seven `.pptx` files to the repository root. Edit the content files, not the generated decks, if you want changes to survive a rebuild.

Speaker notes, syntax colouring, the code-box layout, and the theme are defined in `deck_lib.py`.

---

## FAQ

<details>
<summary><strong>Do I need PowerPoint?</strong></summary>

No. The decks open in PowerPoint, Keynote, and Google Slides. Editing the code boxes is smoothest in PowerPoint because the layout and fonts are designed there; Google Slides may substitute fonts.

</details>

<details>
<summary><strong>Can I type in the box during a slideshow?</strong></summary>

No. Use normal editing view. Presenter mode is read-only.

</details>

<details>
<summary><strong>Why does the AI need the brief as well as my code?</strong></summary>

Because "correct" depends on the task. A page can be valid HTML and still fail the brief — wrong element, missing label, no responsive behaviour. The brief is the specification; your code is the implementation.

</details>

<details>
<summary><strong>Do I have to upload the PowerPoint to my AI?</strong></summary>

Only if you want it to explain slides or quiz you. For code review, paste the exercise brief and your code. It is faster and avoids the AI reading the answer-key notes.

</details>

<details>
<summary><strong>Can I use VS Code instead of the box?</strong></summary>

Yes. Build in VS Code, test in the browser, then paste the final code into the box or straight into the chat. The box exists so your submission is easy to copy in one piece.

</details>

<details>
<summary><strong>Can I skip modules?</strong></summary>

No. Module 3 styles the page from Module 1; Module 4 lays out the components from Module 3; Module 5 adds motion to those components; Module 6 audits and ships the result. The dependency is deliberate.

</details>

<details>
<summary><strong>Where are the quiz answers?</strong></summary>

In the speaker notes and on the answer-key slide that follows each quiz. If you want to be tested, ask the AI not to reveal them.

</details>

<details>
<summary><strong>Can I share this with a friend?</strong></summary>

Yes. Give them the seven decks, this README, and `COURSE-OUTLINE.md`. Point them at [If someone sent you these files](#if-someone-sent-you-these-files).

</details>

<details>
<summary><strong>Can I publish my work from this course?</strong></summary>

Yes — that is the point. The capstones are designed to be deployed and shown. Use your own content and credit any third-party assets you use.

</details>

---

## Contributing

This is a personal course, but it is structured to be forked. If you adapt it:

- keep the lesson codes stable (`M1.1`, `M4.2`, …) so submissions stay traceable;
- keep the brief and the must-include list together on the same slide;
- run `python3 build.py` after editing content;
- update `COURSE-OUTLINE.md` if you add or remove slides.

---

## License

No license file is included. If you publish this repository, add one — MIT is a common choice for course materials. Until then, treat it as shared for personal learning.

<div align="center">

**Start with `00-Start-Here-and-Course-Map.pptx`.**

Then open deck 01 and send your first `M1.1`.

</div>
