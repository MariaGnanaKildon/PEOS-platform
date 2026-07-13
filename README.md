# PEOS Platform

PEOS Platform is a reusable management framework for a Personal Engineering Operating System (PEOS).

This repository defines *how* personal operations are engineered, improved, and versioned. It does not store personal runtime data such as daily tasks, journal entries, schedules, or calendar events.

## Purpose

- Provide reusable management capabilities (kernel modules).
- Standardize templates, playbooks, and operating patterns.
- Support Agile and Scrum-inspired continuous improvement.
- Keep platform design independent from execution tools.

## Platform vs Runtime

- Platform (this repo): architecture, modules, templates, playbooks, standards.
- Runtime (external tools): task execution, scheduling, tracking, and personal data.

Execution examples: Jira, Google Calendar, Obsidian/Notion, Confluence.

## High-Level Architecture

Vision -> Goals -> Programs -> Operating Models -> Management Kernel -> Execution -> Review

See [docs/architecture.md](docs/architecture.md) for details.

## Repository Structure

- `docs/` Philosophy, architecture, principles, glossary.
- `kernel/` Reusable management capabilities.
- `playbooks/` Scenario-driven operating guides.
- `templates/` Reusable markdown templates.
- `automation/` Future automation assets (tool-agnostic).
- `.github/` Community and contribution metadata.

## Semantic Versioning

This platform follows SemVer:

- MAJOR: incompatible architectural change.
- MINOR: backward-compatible capability additions.
- PATCH: backward-compatible clarifications or fixes.

Current version: `v1.0.0`.

## Getting Started

1. Read [docs/philosophy.md](docs/philosophy.md).
2. Review [docs/architecture.md](docs/architecture.md).
3. Pick a kernel module and adapt its templates.
4. Use playbooks to operationalize your weekly cycle.
5. Track platform improvements through changelog and roadmap.

## Non-Goals for v1

- Personal data storage.
- AI planning engine.
- Calendar scheduler.
- Optimization/recommendation engines.
- Personal analytics dashboard.
