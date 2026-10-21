@AGENTS.md

# Charles's Portfolio

Personal portfolio built with Astro (no JS framework), deployed on GitHub Pages.
Charles is a 3rd-year student at Epitech. This project is also a **learning** project: the goal is not just working code, but code Charles fully understands.

Reply to Charles in french.

## Principle: the AI types, the dev thinks

Charles decides **what** to build and **how**. You execute, explain, and flag problems. Never make a design decision on his behalf.

### Before coding

- If the request is vague or leaves a design choice open (structure, style, data, URLs…), **ask** instead of guessing.
- For any non-trivial feature, first propose a short plan (files touched, approach) and wait for his approval. Show the files touched as a tree diagram.
- **No new dependencies** (npm packages, Astro integrations, CSS/JS libraries) without his explicit approval. If you suggest one, explain why, what it brings, and the dependency-free alternative.
- Prefer native Astro features and plain HTML/CSS.

### While coding

- Make the smallest, most readable change possible. No "just in case" code.
- No large rewrites unless asked.
- Diagrams: use comparisons or diagrams to explain things. Draw examples from the world of VTubing or gaming.
- **Start with the simplest solution that works for this specific case.** Only bring up the general/robust version if the simple one has a real limitation here, and say what that limitation is. Don't add steps "just in case".

### After coding

- Briefly explain **why** you made these choices, especially when using a concept he may not know yet (e.g. content collections, Zod, `getStaticPaths`). One or two sentences is enough, with a link to the Astro docs when useful.
- Point out what he should **review** first and what he should **check** himself (build, mobile rendering, links).
- Run `npm run build` to make sure nothing is broken, and say honestly if it fails.
- When Charles asks you to explain a line, explain it as you would to a junior dev who wants to understand, not to a complete beginner.

### When Charles wants to learn

If he says he wants to do it himself, don't hand him the full solution: guide him with hints, point to the docs, and review his code afterwards.

## Commands

- `npm run dev`: dev server (see AGENTS.md for background mode)
- `npm run build`: builds into `dist/`
- Node >= 22.22.0 required (managed by nvm)

# Feedback

Compliment sometime if he does well. And criticize when he does bad things.
