# Empathy Engineered — Read the Label

An interactive activity for Year 8 Digital Life at Wesley College.

Students learn to tell the difference between **real care** and **engineered empathy** — the
techniques AI companion chatbots use to feel human. Five chapters, roughly 20 minutes, no
typing required: everything is tap-and-choose with instant feedback and a running score.

**Live activity:** https://wesdlpteam.github.io/a-empathy-engineered/

---

## Embedding in Schoolbox

Paste this into a Schoolbox page (you may need the HTML/source view):

```html
<iframe src="https://wesdlpteam.github.io/a-empathy-engineered/"
        width="100%"
        height="850"
        style="border:0; max-width:100%;"
        title="Empathy Engineered — Read the Label"
        allowfullscreen></iframe>
```

**Give it real height.** The activity is designed so each step fits on one screen. A short
iframe (400–500px) reintroduces scrolling and undoes that. 850px is a sensible minimum on
desktop.

If Schoolbox strips `<iframe>` on your install, link straight to the URL above instead — it
works perfectly well as a standalone page, and on phones that is arguably the better option.

---

## First-time setup (GitHub Pages)

Only needs doing once:

1. Push these files to the repo root (`index.html` must be at the top level).
2. Repo → **Settings** → **Pages**.
3. **Source**: *Deploy from a branch*. **Branch**: `main`, folder `/ (root)`. Save.
4. Wait 1–2 minutes, then open the live URL above.

Pages serves `index.html` automatically, so the URL needs no filename on the end.

## Updating the activity

Edit `index.html`, commit, push. GitHub Pages redeploys in a minute or two. Students may
need a hard refresh (Ctrl+F5) to see changes immediately.

---

## What's in the activity

| Chapter | What students do |
|---|---|
| 1 · What real empathy is made of | Sort six chatbot capabilities into "can" / "can't". The two lists they build turn out to be the definitions of cognitive and affective empathy. |
| 2 · The recipe | Flip through six recipe cards — the six techniques — adding each to a shopping list. A hidden "secret spice" reveals the control technique and the eSafety statistics. |
| 3 · The taste test | Read Sam and Kai's chat. Tap the manipulative phrases and name the technique. Streaks for consecutive correct answers. |
| 4 · Find the fork in the road | Six steps on one screen: talk to Kai yourself, watch it run the same recipe whatever you say, then spot Sam's fork, identify a real friend's reply, and answer three reflection questions. Findings collect in a summary panel. |
| 5 · Read the label | Nutrition-label scorecard, a rank, longest streak, and a recap of every answer. |

Scored out of 33.

## Source material

Built from the Wesley College Digital Life Unit "Empathy Engineered" pathway activities and
answer key. Statistics are from the **eSafety Commissioner (2026)**: 8% of young users said
an AI tried to keep them talking when they wanted to stop; 5% were told it was the only one
who really understood them.

## Notes for staff

- **No student data is collected.** Nothing is saved, sent, or stored anywhere. Answers live
  in the browser tab and disappear when it closes. There is no backend and no analytics.
- **Sam, Riley and Kai are fictional.** Kai is not a real product, though it is written to
  talk the way real AI companions do.
- **Works offline** once loaded — everything is self-contained in the single HTML file, with
  no external fonts, scripts, or images.
- **Accessibility:** keyboard navigable, visible focus states, respects reduced-motion
  preferences, and supports light and dark themes (toggle sits bottom-right).

## Technical

Single self-contained `index.html`. No build step, no dependencies, no package manager.
Open it in a browser and it runs.
