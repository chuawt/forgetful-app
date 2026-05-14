# forgetful.

a spaced repetition tool for things worth remembering.

---

## what it does

you set a date — the day you learned something, met someone, read something that mattered. forgetful then shows you when to revisit it: on day 1, day 7, and day 30.

these intervals follow the forgetting curve: the idea that memory decays predictably, and that reviewing at the right moments locks information in before it slips away.

the increments section lets you set custom review intervals on top of that — adjust them to fit how you actually learn.

## how to use it

1. tap the anchor card to set your start date
2. the forgetting curve section shows your fixed day 1 / 7 / 30 checkpoints
3. tap any number in the increments section to adjust the interval to your liking
4. use the dates as reminders to revisit whatever you're trying to hold onto

## stack

a single `index.html` — no build step, no dependencies, no backend. open it in a browser and it works.

- vanilla js for state and rendering
- inter for all type
- css custom properties for theming
- native date picker for input

## local use

```
open index.html
```

or serve it:

```
python3 -m http.server 8000
```

---

*quiet. lowercase. no notifications.*
