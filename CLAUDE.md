# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A personal study-notes series, not a software project. Despite the repo name, there is no backend code here — each subfolder is one class's study pack. No build, test, lint, or CI tooling applies.

## Structure

Each class lives in its own `class-NN-study-pack/` folder, e.g. `class-02-study-pack/`. A folder contains:
- One Markdown study guide: `class-NN-<topic-slug>-study-guide.md`
- Supporting `.svg` diagrams and standalone `.html` interactive demos (no build step — open directly in a browser, no external JS dependencies)

## Study guide format

Follow `class-02-study-pack/class-02-networking-study-guide.md` as the template for new guides:
- Top-level `# Section NN — <Topic>` headings, with `## N.M <subtopic>` subheadings underneath
- Each subheading follows this exact pattern, in order:
  1. `**What it is.**` — concept explanation
  2. `**Try it.**` — a runnable shell/code snippet the reader executes themselves
  3. `**Exercises.**` — numbered list of practice questions
  4. `**Go deeper.**` — bullet list of external reference links
- Subsections separated by a `---` horizontal rule
- Guide ends with a `# Wrap-up` section (cheat sheet, self-test, "not covered" caveats)

Match this structure for any new study pack rather than inventing a new format.
