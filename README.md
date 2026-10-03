# Engineering Case Study — Codex Skill

Turn engineering artifacts into portfolio case studies with an evidence ledger. Supports Arabic and English and separates plans, modeled results, reproduced calculations, and missing evidence.

## Install

Clone this repository or use GitHub's Code → Download ZIP option and extract it. The repository contains the `skills/engineering-case-study` folder shown below.

Copy `skills/engineering-case-study` into `.agents/skills/engineering-case-study` in your project. For availability across projects, use your user-level `.agents/skills` directory. Inspect existing skills before overwriting.

Codex discovers local skills. Restart if an update does not appear. [Official documentation](https://learn.chatgpt.com/docs/build-skills).

## Use

Implicit: "حوّل هذا المشروع الهندسي إلى دراسة حالة موثقة للبورتفوليو مع جدول الأدلة."

Explicit: "Use $engineering-case-study to document this engineering project from the attached artifacts."

Supply the actual report, code, workbook, or simulation outputs. The skill cannot establish absent results.

```text
skills/engineering-case-study/
  SKILL.md
  agents/openai.yaml
  assets/case-study-template.md
  references/evidence-rules.md
  references/evaluation-prompts.md
```

The skill requires no external packages or services. Artifact extraction may use tools provided by the host. Private projects and local transcripts are excluded from this public package.

## Validation

Use the official skill-creator `quick_validate.py` for structure and evaluation prompts for behavioral testing. Structural validity and enabled implicit invocation do not prove automatic selection.
