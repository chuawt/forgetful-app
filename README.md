# forgetful.

A spaced repetition tool for things worth remembering.

---

## What it does

You set a date — the day you learned something, met someone, read something that mattered. forgetful then shows you when to revisit it: on day 1, day 7, and day 30.

These intervals follow the forgetting curve: the idea that memory decays predictably, and that reviewing at the right moments locks information in before it slips away.

The increments section lets you set custom review intervals on top of that — adjust them to fit how you actually learn.

## How to use it

1. Tap the anchor card to set your start date
2. The forgetting curve section shows your fixed day 1 / 7 / 30 checkpoints
3. Tap any number in the increments section to adjust the interval to your liking
4. Use the dates as reminders to revisit whatever you're trying to hold onto

## Stack

A single `index.html` — no build step, no dependencies, no backend. Open it in a browser and it works.

- Vanilla JS for state and rendering
- Inter for all type
- CSS custom properties for theming
- Native date picker for input

## Use it online

Visit [forgetful.pages.dev](https://forgetful.pages.dev/) to use the app.

## Local use

```
open index.html
```

Or serve it:

```
python3 -m http.server 8000
```

---

*Quiet. Lowercase. No notifications.*
