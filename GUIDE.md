# Reader's Guide — system-prompts-and-models-of-ai-tools

## What this project is

This repository is a **collection of system prompts, tool definitions and
model configurations from AI tools and products** — the hidden instruction
layers that shape how AI coding agents and assistants behave, gathered into
one place for study. Researchers, prompt engineers and the merely curious use
it to compare how different products instruct their models: tone rules,
tool-use schemas, safety behaviour and capability wiring, straight from the
source material.

## How the content is organised

**One top-level folder per product** — 32 of them — with that product's
prompt files (plain `.txt`/Markdown captures, sometimes with sub-folders per
surface) inside:

- **AI coding agents & IDEs:** `Cursor Prompts`, `Windsurf`, `Devin AI`,
  `Replit`, `Trae`, `Kiro`, `Qoder`, `Augment Code`, `CodeBuddy Prompts`,
  `VSCode Agent`, `Junie`, `Amp`, `Warp.dev`, `Xcode`, `Z.ai Code`.
- **Model providers & assistants:** `Anthropic` (for example the Claude Code
  and Claude model prompt files), `Google`, `Perplexity`, `NotionAi`,
  `Comet Assistant`, `dia`.
- **App builders & agents:** `v0 Prompts and Tools`, `Lovable`, `Same.dev`,
  `Leap.new`, `Emergent`, `Orchids.app`, `Manus Agent Tools & Prompt`,
  `Cluely`, `Poke`, `Traycer AI`.
- `Open Source prompts` — prompts from open-source projects, grouped apart
  from the commercial products.

[`README.md`](README.md) is short: the edition/provenance block, a **security
notice for AI startups** (the collection doubles as a warning about prompt
extraction risk), and support/sponsor information. `assets/` holds README
images; `LICENSE.md` is GPL-3.0.

## How to use it

1. Open the folder of the product you are studying.
2. Read the prompt/tool files inside — filenames identify the model, version
   or surface they belong to (e.g. the per-model files under `Anthropic/`).
3. Compare across products: the same job (coding agent, app builder) is
   instructed very differently by different vendors, which is the real study
   value of the collection.

## About this standalone edition

This repository is a standalone edition of
[x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors.
