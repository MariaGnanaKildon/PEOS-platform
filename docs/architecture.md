# Architecture

## System Flow

Vision -> Goals -> Programs -> Operating Models -> Management Kernel -> Execution -> Review

## Layer Definitions

- Vision: long-term direction and intent.
- Goals: measurable outcomes aligned with vision.
- Programs: strategic pathways to achieve goals.
- Operating Models: repeatable ways programs are run.
- Management Kernel: reusable management capabilities.
- Execution: external systems where work happens.
- Review: closed-loop adaptation and improvement.

## Architectural Constraints

- Platform must remain generic and reusable.
- Runtime data must stay outside this repository.
- Modules should expose clear interfaces: purpose, inputs, outputs, metrics.
- Modules should be independently versionable in practice.

## Integration Boundary

The platform defines *what* and *how* to manage.
External tools execute *where* and *when* work happens.

Examples:

- Jira for tasks, projects, and sprint operations.
- Confluence for deep documentation/research.
- Calendar systems for scheduling and time blocks.
- Notes systems for knowledge capture/retrieval.
