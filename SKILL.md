---
name: documentation-templates
description: Choose, tailor, and produce maintainable templates for README files, API references, architecture notes, code comments, changelogs, runbooks, and AI-readable project documentation.
---

# Documentation Templates

## Purpose
Create documentation that is accurate, discoverable, maintainable, and appropriate for its audience. Templates are starting points, not mandatory boilerplate.

## Workflow
1. Identify the reader and the action the document should enable.
2. Inspect existing documentation and project conventions.
3. Select the smallest template that covers the need.
4. Replace every placeholder with verified project information.
5. Remove sections that do not apply.
6. Add examples that can be checked against actual behavior.
7. Review links, commands, versions, owners, and maintenance expectations.

## Template selection
- Project overview: templates/README-template.md
- HTTP API: templates/api-reference-template.md
- Architecture decision: templates/adr-template.md
- Release history: templates/changelog-template.md
- Operations: templates/runbook-template.md

## Quality rules
- Put the most useful information near the top.
- Prefer concrete steps and runnable examples.
- Document prerequisites and expected outcomes.
- Explain why non-obvious decisions exist.
- Keep code comments focused on intent and constraints.
- Do not document an imagined interface.
- Use consistent terms and heading levels.
- Add owners and review triggers to operational documents.
- Avoid duplicating information that has a canonical home.

## AI-readable documentation
Use clear headings, explicit file paths, structured examples, and concise definitions. Keep instructions self-contained. Never expose credentials or private data in examples.

See resources/style-guide.md for writing conventions.