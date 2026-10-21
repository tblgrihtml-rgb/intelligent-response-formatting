# Intelligent Response Formatting

A Codex skill that structures answers for quick reading while adapting the format to the request.

## What it does

- Leads with the answer, then adds only the explanation and detail the user needs.
- Uses paragraphs, headings, lists, steps, and compact tables when each format improves scanning.
- Applies restrained partial-word bolding in ordinary prose as a visual preference, and removes it when it adds noise.
- Keeps code, links, formulas, and special notation free of partial-word emphasis.

The skill does not claim that Bionic Reading improves speed or comprehension. One controlled study found no reading-time benefit; see [Snell (2024)](https://doi.org/10.1016/j.actpsy.2024.104304).

## Install

Copy `SKILL.md` and the `agents` folder to `~/.codex/skills/intelligent-response-formatting/`. Start a new Codex task to refresh skill discovery.
