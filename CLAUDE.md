# Concept Ventures — Directory & Repo Layout

> This file documents how this directory is organized and version-controlled. It is project context for working in this repo, not business content — for the venture playbooks themselves, see each venture's own `CLAUDE.md`.

## What this directory is

`concept-ventures` is the hub for four related storage-installation business concepts (see `README.md` for the pitch-level summary). It ties the ventures together with shared tracking (`decision-log.md`), an automation blueprint (`automate.md`), and a pilot launch plan (`iron-oak-project-plan.md`).

## Directory structure — multi-repo, not a monorepo

Each venture is a **separate git repository**, nested as a subfolder here for convenience, but independently tracked and pushed:

| Local folder | GitHub repo | Business name |
| :--- | :--- | :--- |
| `ironOak/` | [`resoh/iron-oak-closets`](https://github.com/resoh/iron-oak-closets) | Iron & Oak Closets |
| `stockroom-standard/` | [`resoh/stockroom-standard`](https://github.com/resoh/stockroom-standard) | Stockroom Standard |
| `the-utility-line/` | [`resoh/the-utility-line`](https://github.com/resoh/the-utility-line) | The Utility Line |
| `bay-and-bolt/` | [`resoh/bay-and-bolt`](https://github.com/resoh/bay-and-bolt) | Bay & Bolt |

This directory itself (`concept-ventures/`) is also its own git repo: [`resoh/concept-ventures`](https://github.com/resoh/concept-ventures).

**Important:** the four venture folders are listed in this directory's `.gitignore` (`/ironOak/`, `/stockroom-standard/`, `/the-utility-line/`, `/bay-and-bolt/`) so they are excluded from the `concept-ventures` repo — each is a standalone nested repo, not a submodule or embedded tree. This means:
- Changes made inside a venture folder must be committed/pushed from *within that folder* (its own `git` remote), not from the `concept-ventures` root.
- `git status`/`git add` run from `concept-ventures/` root will never see venture-folder changes — that's expected, not a bug.
- Each venture folder has its own `.git`, its own `origin` remote, and its own commit history predating this reorganization (merged with `--allow-unrelated-histories` when first linked here on 2026-09-21).

## Key files at this level

- `README.md` — landing page / pitch-hub summary, links to all four ventures.
- `decision-log.md` — running log of partner/stakeholder concerns and exactly where each was resolved across the four playbooks. Check this before assuming a concern is unaddressed; add a new row here whenever a partner/stakeholder comment results in a change.
- `automate.md` — six-pillar automation blueprint (written for Iron & Oak, intended as the template for the other ventures).
- `iron-oak-project-plan.md` — phased pilot launch plan for Iron & Oak specifically (the first venture slated for real deployment); intended as the template for deploying the next venture.
- `concept-ventures.code-workspace` — VS Code multi-root workspace, currently a single root (`.`) since the ventures are real subfolders now.

## Working conventions

- All four venture concepts are **drafts** — each venture's `CLAUDE.md` playbook says so explicitly ("Status: Concept draft"). Treat specific numbers/mechanisms as illustrative, not final, unless told otherwise.
- When a partner/stakeholder raises a concern that changes a playbook or site, log it in `decision-log.md` (see "How to use this log" at the bottom of that file) in addition to making the change.
- Cross-venture consistency matters: a fix driven by a concern about one venture (e.g. the powder-coat wear-point fix) is usually meant to apply to all four — check `decision-log.md`'s "Ventures Affected" column before scoping a fix to just one.
