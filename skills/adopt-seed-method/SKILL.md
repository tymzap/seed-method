---
name: adopt-seed-method
description: Adopt Seed Method in a project by establishing a temporary place for capturing, developing, and graduating knowledge into permanent project structures.
disable-model-invocation: true
---

# Adopt Seed Method

Introduce Seed Method into this project. Seed is a temporary place for capturing and developing ideas, information, and knowledge before they are integrated into permanent project structures.

## Process

### 1. Inspect

Read the project layout, documentation, and existing agent instructions (`AGENTS.md`, `CLAUDE.md`, `README.md`, and other relevant files).

Identify:

- Existing agent instruction files and conventions
- Any existing `seed/` directory or equivalent
- Existing practices for capturing and organizing project knowledge
- Whether Seed Method is already documented for agents or humans

If Seed Method is already adopted, preserve any sufficient existing instructions or explanations. Add or update only what is missing or inconsistent.

### 2. Choose

Select a location for Seed and destinations for its conventions.

**Seed location:** Default to `seed/` at the project root. If the project already uses an equivalent location, preserve it and adjust the conventions accordingly.

**Agent instructions:** Prefer `AGENTS.md`. Use `CLAUDE.md` or another established agent instruction file when the project already relies on it. If no agent instructions exist, create `AGENTS.md`.

**Human documentation:** Use the existing `README.md` if present.

Keep the agent instructions and human explanation separate. Do not duplicate either across multiple files.

### 3. Confirm when needed

If multiple reasonable locations or instruction files exist, explain the options and ask the user to choose.

Otherwise, proceed with the established project conventions.

### 4. Establish

Create the Seed directory if necessary. Add `.gitkeep` if it is empty.

Add or update the agent instructions below in the selected instruction file.

Add or update the human-facing explanation in the existing README, if present.

Adapt the instructions to existing project conventions while preserving the principles of Seed Method. Preserve existing instructions, documentation, and Seed material.

### 5. Report

Report the Seed location and the files created or updated.

Identify existing material that might belong in Seed, but do not move it without a specific reason or request.

## Agent instructions

Add the following instructions to the project's agent instruction file. Adapt them to existing conventions while preserving the principles of Seed Method.

### Seed

Use `seed/` as a temporary place for capturing and developing ideas, information, and knowledge before integrating them into permanent project structures.

When knowledge is still developing, capture it in Seed without requiring its final structure to be decided upfront. Refine it as understanding evolves, then graduate it into the appropriate permanent structures.

Seed may contain exploratory ideas, verified findings, and approved decisions. Its location does not determine its authority. Approved plans may guide implementation even when they describe a future state different from the current system.

Consult relevant Seed material when working on related tasks. When Seed conflicts with established project knowledge, identify the conflict and resolve it rather than silently choosing one source.

Graduate knowledge when it is ready to be integrated, not necessarily when it becomes verified. Integrate it into the project's appropriate permanent structures, such as documentation, established processes, code, tests, agent instructions, or the backlog. Remove or reduce Seed material once its useful content has been integrated.

## Human explanation

Add the following explanation to the existing `README.md`, adapting it to the project.

### Seed

The `seed/` directory is a shared place for capturing and developing ideas, research, decisions, and other knowledge before integrating them into permanent project structures.

Seed allows knowledge to be captured without requiring its final structure to be decided upfront. As understanding develops, the material is refined and gradually integrated into documentation, code, tests, or other established parts of the project. Once integrated, the corresponding Seed material is reduced or removed.