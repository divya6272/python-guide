# Python Complete Foundation

A single-file, interactive Python revision guide, built for anyone preparing for Python interviews or just trying to get a solid grip on the language.

I made this because when I was learning Python myself, I kept bouncing between ten different tabs to find the same handful of concepts explained clearly. This is my attempt to put all of that in one place so it's easier for the next person.

## What's inside

- **All Topics** — Basics, Functions, OOP, Advanced concepts, and DS/ML fundamentals, organized into clickable cards. Each topic has multiple tabs covering the concept, the "why," and working code examples.
- **Interview Q&A** — A running list of Python interview questions with short, direct answers: the GIL, `*args` vs `**kwargs`, `__str__` vs `__repr__`, closures, LEGB, decorators, and more.
- **Gotchas** — Classic Python traps that catch people off guard, both in interviews and in real code: mutable default arguments, shallow vs deep copy, late binding in closures, and a few others.

No build step, no dependencies. The whole thing lives in a single `index.html` file. Open it in a browser and it just works.

## Live demo

If GitHub Pages is enabled on this repo, it's live here:

```
https://divya6272.github.io/python-guide/
```

To enable it: go to Settings, then Pages, then set Source to the `main` branch and `/ (root)`. It usually goes live within a minute.

## Running it locally

```bash
git clone https://github.com/<your-username>/python-guide.git
cd python-guide
open index.html   # Mac
start index.html  # Windows
```
Or just double-click the file and it'll open in your browser.

## Contributing

This is meant to grow. If you've got a topic that's missing, an interview question worth adding, or a gotcha you've personally been burned by, open a PR. Everything lives in three JavaScript objects inside `index.html`: `topics`, `qs`, and `gotchas`. Add an entry, follow the existing pattern, and it'll show up automatically.

If something's explained badly or incorrectly, please say so. The goal is for this to actually be useful, not just complete.

## License

Free to use, share, and build on. If it helps someone get through an interview or finally understand closures, that's the whole point.
