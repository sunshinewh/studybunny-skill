# 🐰 StudyBunny Skill

**The open-source playbook that turns your AI agent into a study-bundle builder.**

StudyBunny is a **free, agent-first** study tool. You connect your own AI agent —
Claude, ChatGPT, Gemini, or Grok — and it turns your course material into
**master notes, flashcards, and memory palaces**, then pushes them to any flashcard
app: **Quizlet, Anki, or [FlashOne](https://flashone.ai)** (the full experience, with
phone sync). Audio review — coming soon.

It's free because **your own agent does the work** (your tokens). This repo is that
agent's method, out in the open so you can read exactly what it does before you run it.

## What's here

- **[`SKILL.md`](./SKILL.md)** — the entire skill: how it captures material losslessly,
  synthesizes on demand, builds language decks + memory palaces, and pushes into your
  flashcard app. This *is* the product's logic — nothing hidden.

## Install

Full step-by-step for each agent: **[studybunny.ai/install](https://studybunny.ai/install)**

In short:
1. **Add the connector** to your agent: `https://mcp.studybunny.ai/mcp` (sign in with Google).
2. **Install this skill** — download the packaged version from
   [studybunny.ai/skill.zip](https://studybunny.ai/skill.zip), or clone this repo.
3. **Ask your agent** to build flashcards, a memory palace, or a study bundle from your material.

## How it works

Your agent runs the pipeline client-side: **sources → lossless notes → outlines →
flashcards / memory palaces → pushed to your flashcard app**. The
[StudyBunny connector](https://mcp.studybunny.ai/mcp) gives it the tools (link your Flash
account, push decks, generate mnemonic images, and more); this skill gives it the method.

## Free vs. paid

- **Free:** everything your agent generates itself — notes, outlines, flashcards, and
  images it draws — pushed to your flashcard app.
- **Credits (FlashOne):** when you ask *FlashOne's* backend to generate premium images or
  (soon) audio, that draws down your FlashOne balance.

## License

MIT — see [`LICENSE`](./LICENSE). Part of the [Flash](https://flashone.ai) ecosystem.
