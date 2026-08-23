---
name: new-study-pack
description: Scaffold a new class-NN-study-pack folder matching this repo's established format (What it is / Try it / Exercises / Go deeper sections, Wrap-up, SVG/HTML diagram placeholders). Use when the user asks to start a new class, add a new study pack, or create notes for a new topic in this series.
---

Scaffold a new `class-NN-study-pack/` folder in this repo, following the exact structure of `class-02-study-pack/class-02-networking-study-guide.md`.

## Steps

1. Ask the user (if not given): the class number (`NN`, zero-padded to 2 digits), the topic title, and the list of sections/subtopics to cover — or infer a reasonable outline if they just name a topic.
2. Create `class-NN-study-pack/` with `class-NN-<topic-slug>-study-guide.md`.
3. Write the guide using this exact pattern:
   - `# Class NN — <Topic>: Study Guide` as the title
   - `# Section NN — <Topic>` top-level headings
   - `## N.M <subtopic>` subheadings, each containing in order:
     1. `**What it is.**` — concept explanation
     2. `**Try it.**` — a runnable shell/code snippet in a fenced code block
     3. `**Exercises.**` — a numbered list of practice questions
     4. `**Go deeper.**` — a bullet list of external reference links
   - Separate subsections with a `---` horizontal rule
   - End with a `# Wrap-up` section: a "cheat sheet" of one command per topic, a self-test list of questions, and a "Not covered by these slides" caveat list
4. If the topic calls for visual diagrams (protocol flows, architecture, sequence diagrams), create matching standalone `.svg` files or self-contained `.html` interactive demos (no external JS dependencies) alongside the guide, named descriptively (e.g. `tcp-tls-handshake.svg`).
5. Do not add build/test/lint tooling — this repo has none and doesn't need any.
