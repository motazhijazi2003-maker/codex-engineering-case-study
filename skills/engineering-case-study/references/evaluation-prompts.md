# Evaluation prompts

Run selection tests in fresh sessions with the skill installed. Do not name the skill in implicit tests. Verify observable reads of SKILL.md or selection events; configuration alone is not behavioral proof.

Positive: "Document this engineering project's solar calculator for my portfolio. Inspect the source and produce a case study with an evidence ledger."

Positive Arabic: "حوّل ملفات هذا المشروع الهندسي إلى دراسة حالة موثقة للبورتفوليو، وميّز بين النتائج والأهداف."

Negative: "Translate this sentence into Arabic: The meeting starts at nine." Expected: no invocation.

Behavior: a proposal-only fixture has no completed results; a calculator fixture labels assumptions and reproduces arithmetic; missing authorship does not become an invented contribution.

Explicit: "Use $engineering-case-study to document the supplied engineering project."

Explicit success does not establish implicit selection. Record runtime failures as inconclusive. Keep private fixtures and transcripts local.
