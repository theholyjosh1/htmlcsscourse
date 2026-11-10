# HTML & CSS: Zero to Master

A complete, practical course that takes you from no experience to building and shipping professional web pages. Seven PowerPoint decks, 148 slides, 11 typed code exercises, 5 module projects and 3 capstone briefs.

Every module is one `.pptx` file. Open them in order.

---

## What's in the folder

| Deck | Slides | Focus | Project |
|---|---|---|---|
| `00-Start-Here-and-Course-Map.pptx` | 8 | Setup, workflow, how to submit code | — |
| `01-HTML-Foundations.pptx` | 22 | Tags, text, lists, links, images, paths | Recipe page |
| `02-Semantic-HTML-and-Forms.pptx` | 22 | Landmarks, tables, forms, accessibility | Profile page |
| `03-CSS-Fundamentals.pptx` | 26 | Selectors, box model, typography, cascade | Style the recipe page |
| `04-Layout-Flexbox-and-Grid.pptx` | 25 | Positioning, Flexbox, Grid, responsive | Responsive landing page |
| `05-Advanced-CSS-and-Motion.pptx` | 25 | Tokens, transitions, modern selectors, performance | Component library |
| `06-Mastery-Projects-and-Practice.pptx` | 20 | Architecture, audits, deployment, career | 3 capstone projects |

`COURSE-OUTLINE.md` lists every slide, so you can navigate without opening each deck.

---

## How the code boxes work

Practice slides have a **dashed code box** on the right. It is a real, editable PowerPoint text box:

1. Open the deck in normal editing view (not Slide Show) and go to a slide marked **PRACTICE**.
2. Click inside the dashed box.
3. Select the placeholder (or starter code) with `Cmd + A` / `Ctrl + A`, then type your code.
4. When you are done, copy the contents of the box into chat.
5. Start your message with the lesson code, e.g. `M3.1 — your name`.

Each box has a **must include** checklist on the left. Check it yourself before sending.

### Submission format

```
M3.1 — Alex

--- HTML ---
<div class="card">...</div>

--- CSS ---
.card { padding: 32px; }

--- QUESTION ---
Why is my card wider than 380px?

--- WHAT I TRIED ---
I set width: 380px but it still grows.
```

Paste code as text, not as a screenshot. One lesson per message.

---

## The exercises

| Code | Task | Deck |
|---|---|---|
| M1.1 | Build your first page | 01 |
| M1.2 | Three things I like (lists, links, images) | 01 |
| M1-PROJECT | Recipe page in HTML only | 01 |
| M2.1 | Signup form with labels and fieldsets | 02 |
| M2.2 | Semantic blog article | 02 |
| M2-PROJECT | Personal profile page | 02 |
| M3.1 | Style a profile card | 03 |
| M3.2 | Build a readable article | 03 |
| M3-PROJECT | Style the recipe page | 03 |
| M4.1 | Responsive navbar | 04 |
| M4.2 | Responsive gallery | 04 |
| M4.3 | Full landing page layout | 04 |
| M4-PROJECT | Responsive landing page | 04 |
| M5.1 | Animate a card professionally | 05 |
| M5.2 | Two-theme token system | 05 |
| M5-PROJECT | Five-component library | 05 |
| CAPSTONE 1 | Personal portfolio, deployed | 06 |
| CAPSTONE 2 | Analytics dashboard | 06 |
| CAPSTONE 3 | Product site + design system | 06 |

---

## Suggested pace

**Standard (8–10 weeks, 1–2 hours/day):** one module per 1–2 weeks, with the project finished before moving on.

**Intensive (30 days):** follow the 30-day plan on slide 17 of deck 06. Rebuild earlier projects from memory, then complete the three capstones.

Do not skip the rebuild step. Reading code feels like learning; typing it from memory is learning.

---

## What my review will check

When you send code, I will review it in this order:

1. **Validity** — does it parse? are tags closed and nested correctly?
2. **Semantics** — right elements, heading order, labels, alt text.
3. **Layout** — box model, spacing, no overflow at 320px.
4. **Responsive** — mobile-first queries, fluid type, images.
5. **Accessibility** — keyboard, focus, contrast, reduced motion.
6. **Maintainability** — naming, tokens, dead CSS, selector weight.
7. **Craft** — typography, alignment, consistency, finish.

You will get specific fixes, not a score. Apply them one at a time and resubmit if unsure.

---

## Technical notes

- 16:9 widescreen (13.333 × 7.5 in), designed for PowerPoint 2016+ and Google Slides.
- Fonts: Arial for text, Consolas for code. Both ship with Microsoft Office.
- All code boxes, cards and text are native editable shapes — no images of text.
- Speaker notes on most slides contain teaching notes and answers.
- Decks are generated from the Python source in `course/`. To rebuild:

```bash
cd course
pip install python-pptx
python3 build.py
```

---

## Start here

1. Open `00-Start-Here-and-Course-Map.pptx`.
2. Do the 30-minute setup on slide 6.
3. Open deck 01 and complete **M1.1**.
4. Send me the contents of the code box with `M1.1 — your name`.

That is the whole method: read, type, submit, fix, rebuild.
