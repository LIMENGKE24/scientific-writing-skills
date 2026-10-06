# Scientific Writing Skills

Reusable guidance for scientific manuscript drafting, literature reviews, and revision, developed through iterative research-writing collaboration.

## Available skill

**[Scientific manuscript writing](skills/scientific-manuscript-writing/SKILL.md)** helps an assistant preserve the author's logic, explain concrete literature contributions, and revise academic prose without changing its scientific meaning. It covers abstracts, introductions, results discussions, and figure captions, with additional guidance for authorized LaTeX and Overleaf edits.

The emphasis is on:

- Following the author's intended argument and requested editing scope.
- Describing what a study investigated and found, rather than listing topics or mechanisms.
- Connecting paragraphs naturally and avoiding repeated reasoning.
- Developing figure discussions from observations to physical interpretation, with examples drawn from research articles.
- Using direct academic prose and reserving qualifications for points that affect the scientific interpretation.
- Keeping terminology, quantitative claims, and source attribution accurate.
- Defining abbreviations at first use and maintaining them across text, figures, and captions.
- Distinguishing proposed wording from authorized manuscript changes.

## Use

The skill entrypoint is `skills/scientific-manuscript-writing/SKILL.md`, with a linked [Results writing reference](skills/scientific-manuscript-writing/references/results-style.md). Install the complete skill folder using your agent's skill-installation workflow, or provide the entrypoint and reference as writing guidance. It has no required scripts or external service dependencies. Editing a live document requires separately available access to that document.

After installation, example requests include:

> Use $scientific-manuscript-writing to revise this introduction while preserving my paragraph order and scientific claims.

> Use $scientific-manuscript-writing to turn these verified literature notes into a connected review. Explain the main findings, vary the sentence structure, and end with the specific unresolved question.

> Use $scientific-manuscript-writing to edit only this sentence. Preserve the terminology, numerical values, and LaTeX macros.

Provide the current passage, intended logic, relevant sources, and any journal or length requirements. Say whether you want draft wording or changes applied to a file.

## Scope

This public version contains reusable writing guidance, not manuscript text, unpublished research findings, private project identifiers, or personal file paths. Its style preferences are defaults, not universal journal rules. Explicit author instructions and applicable journal requirements take precedence. The skill does not independently validate scientific results or replace reading the cited sources.
