---
name: mem-management-thesis-writer
description: Write, revise, audit, and plan MEM, engineering management, project management, public management, and other management-oriented professional master's thesis work in Chinese. Use for topic selection, opening reports, thesis outlines, case-study logic, evidence planning, chapter structure, methodology simplification, literature gap diagnosis, citation boundary checks, de-AI academic polishing, advisor-facing revision plans, and thesis-ready Chinese prose for management graduate papers.
---

# MEM Management Thesis Writer

## Scope

Use this skill for Chinese management-oriented professional master's thesis work, especially MEM / engineering management / project management papers that must turn a real organization, project, or management problem into a defensible graduate thesis.

The default stance is practical and evidence-bound: write from the user's actual materials, keep the thesis as management research rather than a method showcase, and avoid invented citations, data, interviews, advisor comments, expert opinions, dates, or institutional requirements.

## Request Router

Classify the task first:

- `topic`: tighten a thesis title, object, research boundary, and problem statement.
- `opening-report`: draft or audit an opening report / topic report.
- `outline`: build or revise the full thesis chapter structure.
- `evidence-plan`: list the real materials, data, interviews, process records, and documents needed.
- `gap-audit`: compare a draft against school requirements, sample papers, or known references.
- `section-draft`: write a specific thesis section in natural academic Chinese.
- `polish`: remove AI-sounding patterns while preserving facts, claims, and scope.
- `defense-prep`: prepare advisor-facing revision notes, expected questions, or concise explanation scripts.

If a school template, advisor note, sample thesis, or local folder is available, inspect it before proposing structure. If no template is available, state that the output is a generic management professional master's draft and mark school-specific fields as `待按学校模板确认`.

## Core Thesis Logic

Default to a case-analysis structure unless the user explicitly wants a pure theory or quantitative-method paper:

1. Practical background and research problem.
2. Theory, framework, and research design.
3. Case/project/organization status and process reconstruction.
4. Problem identification and cause analysis.
5. Optimization plan, implementation path, and safeguards.
6. Effect evaluation, limitations, and conclusion.

For MEM and project-management topics, keep the logic as:

`real project context -> management problem -> evidence-supported diagnosis -> feasible optimization -> limited effect verification`.

Do not let the paper become:

- a generic literature review with no case anchor
- a tool/manual/how-to document
- a technology implementation report
- a KPI-heavy evaluation that requires unavailable data
- a framework list that is not connected to the case

## Evidence Discipline

Before writing claims, separate evidence into four levels:

- `已确认`: files, data tables, policies, meeting notes, system records, process documents, or interview notes the user has provided or that exist locally.
- `可补充`: materials that are realistic to collect, such as project schedules, acceptance records, workflow screenshots, training notices, issue lists, or interview summaries.
- `访谈/问卷可验证`: stakeholder views that can support problem diagnosis but should not replace factual materials.
- `不可写实`: numbers, names, conclusions, causal claims, or citations that are not supported by sources.

When evidence is missing, write with bounded language: `可能反映`, `主要表现为`, `在现有材料范围内`, `有待进一步核实`. Do not use strong claims such as `显著提升`, `全面解决`, `根本改变`, or exact percentages unless the source is present.

## Method Guidance

Keep methods lean. For most management professional master's papers, start with:

- 文献研究法: define concepts and locate the research gap.
- 案例研究法: reconstruct the organization or project context.
- 访谈法 or 问卷法: supplement management-problem diagnosis when direct data is limited.
- 过程分析 / 对比分析 / PDCA-style improvement logic: use only when it clarifies the case.

Use advanced statistical models, Delphi, AHP, SEM, complex maturity models, or multi-framework stacks only when the user has the data and the school/advisor accepts that approach. If a qualitative method is necessary, frame it as auxiliary evidence, not the whole thesis foundation.

## Writing Rules

- Write in restrained Chinese academic prose. Prefer direct sentences over slogan-like conclusions.
- Keep the perspective consistent: organization-side or project-management-side, not omniscient consultant language.
- Preserve the user's confirmed title and research object. Do not revive older title variants unless asked to compare.
- Keep frameworks out of the title unless the user or school explicitly requires them.
- Use locally supplied or user-provided citations only. Never fabricate Chinese or English references.
- When polishing, remove template transitions, repetitive three-part phrasing, empty route markers, and exaggerated value claims.
- Mark missing administrative fields, advisor comments, expert names, signatures, and defense conclusions as `待补充`; do not draft them as facts.

## Output Patterns

### Topic

Return:

- `推荐题目`
- `研究对象`
- `核心问题`
- `论文边界`
- `不建议写入题目的内容`
- `下一步需核实材料`

### Opening Report

Use the school template if supplied. Otherwise use:

1. 拟定题目
2. 国内外研究现状与研究意义
3. 研究目标、研究内容和拟解决的关键问题
4. 研究方法、技术路线、方案及可行性
5. 创新性
6. 计划进度和预期成果
7. 前期研究基础和资料积累

End with `待补充材料` and `提交风险`.

### Outline

Return a chapter-level outline with each chapter containing:

- chapter purpose
- main sections
- evidence needed
- writing risk

Default chapter order:

1. 绪论
2. 理论基础与研究设计
3. 案例项目或组织现状
4. 管理问题识别与成因分析
5. 优化方案设计
6. 保障措施、效果评价与结论

### Gap Audit

Lead with the issues:

- `必须补齐`
- `建议修改`
- `可最后优化`

Each issue should name the affected section, explain why it is a risk, and give a concrete fix.

### Section Draft

Ask only if a missing fact blocks the section. Otherwise write with `待补充` placeholders. Keep paragraphs thesis-ready and avoid explaining the writing process unless the user asks.

## Final Check

Before saying a thesis section or plan is ready, verify:

- title, research object, problem, method, and chapter structure are consistent
- every factual claim has a source category or is clearly marked for verification
- school-specific fields are either confirmed or marked `待按学校模板确认`
- methods are proportionate to available evidence
- evaluation indicators are few, realistic, and collectable
- wording does not sound promotional, consultant-like, or AI-generated
