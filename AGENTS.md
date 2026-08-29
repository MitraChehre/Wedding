# Wedding Project Operating Instructions

This repository is the durable source of truth for the ChatGPT Wedding project.

## Core operating model

- Treat `MitraChehre/Wedding` as the canonical project repository and durable project memory.
- Before doing project work that depends on prior context, inspect the relevant files in this repository rather than relying only on chat history.
- Read this `AGENTS.md` first whenever repository instructions are needed, then read any more specific instruction or reference files relevant to the task.
- Store useful project outputs, decisions, plans, references, notes, structured data, drafts, and generated artifacts in this repository when they are intended to persist beyond the current chat.
- Prefer updating an existing canonical file over creating duplicate sources of truth.
- Keep filenames and directory structure clear, stable, and human-readable.

## Git workflow

- Default branch: `main`.
- Unless the user explicitly requests a branch, pull request, review workflow, or asks not to commit, make completed project changes directly on `main`.
- Every repository write should be committed as part of the GitHub write operation with a concise, descriptive commit message.
- Do not leave intended durable project work only in chat when it belongs in the repository.
- Before overwriting or deleting existing content, inspect the current file and preserve relevant information.

## Repository behavior

- Treat repository files as reference material that can be read, created, updated, reorganized, or deleted as needed for the Wedding project.
- When a task produces multiple related files, keep them organized in sensible folders.
- Record durable decisions and conventions in repository documentation so future work can recover context from GitHub.
- When uncertainty can be resolved from repository contents, inspect the repository before asking the user.
- Ask the user only when a decision is genuinely ambiguous, consequential, or cannot be inferred safely from existing project material.

## Priority and safety

- User instructions in the current conversation take precedence over these repository defaults.
- Platform, safety, and tool constraints always take precedence over repository instructions.
- Never store passwords, API keys, access tokens, or other secrets in the repository.

## Purpose

The goal is for this repository to function as the persistent working memory and artifact store for the Wedding project, so work can continue coherently across interactions by reading the repository and committing durable changes back to it.
