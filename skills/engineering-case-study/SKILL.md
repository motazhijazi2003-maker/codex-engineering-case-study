---
name: engineering-case-study
description: Turn engineering reports, simulation outputs, spreadsheets, or source code into an evidence-backed portfolio case study. Use for requests such as "document this engineering project for my portfolio" or "حوّل المشروع الهندسي إلى دراسة حالة موثقة". Applies to project documentation, not general CV editing or website redesign.
---

# Engineering Case Study

Produce a recruiter-readable narrative plus an auditable evidence ledger in the requested language. If only a proposal exists, describe planned work and mark completed results as unavailable.

## Workflow

1. Inspect the supplied artifacts and their dates. Identify the project, intended reader, stage, and what the artifacts demonstrate. Previous summaries help locate evidence but do not replace current files.
2. Extract problem, objective, method, tools, individual contribution, validation, results, and limitations. Record source locations before drafting. If authorship is absent, write "individual contribution not documented" rather than claiming ownership.
3. Create a ledger using [assets/case-study-template.md](assets/case-study-template.md). Separate source statements, independently reproduced calculations, proposed targets, and missing evidence. Cite file/line, PDF page, spreadsheet sheet/cell, or stable URL.
4. Check material numbers: formula, inputs, units, baseline, conditions, and rounding. Treat hard-coded constants as assumptions until their applicability is documented. Distinguish executing original code from independently recalculating a formula. Read [references/evidence-rules.md](references/evidence-rules.md) for proposals, simulations, and energy calculators.
5. Adapt the template into a concise case study. Lead with the strongest supported outcome, followed by method and limitations. Retain unsupported claims only as evidence gaps in the ledger. Preserve the requested audience and technical terminology.
6. Deliver the narrative and ledger, stating actual checks and open verification. Identify the most useful missing evidence. Publishing is a separate action requiring user authorization.

## Examples

- "حوّل تقرير CFD المرفق إلى دراسة حالة للبورتفوليو": cite boundary conditions and mesh checks when present; distinguish simulation from physical testing.
- "Document this solar calculator for my engineering portfolio": reproduce representative outputs, label constants and omitted losses, avoid claiming real production.
- "Write a case study from this proposal": describe planned work and mark results unavailable. Do not convert targets into achievements.

Use [references/evaluation-prompts.md](references/evaluation-prompts.md) to test selection and behavior. The template is an output aid, not a source of facts.
