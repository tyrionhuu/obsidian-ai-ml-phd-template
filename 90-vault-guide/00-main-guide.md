# AI/ML PhD Vault Guide

This vault is built around traceable research work. A useful note should make it easy to answer:

- What question was I trying to answer?
- What evidence did I collect?
- Can I reproduce the result?
- How does this connect to my thesis?

## Folder Roles

| Folder                         | Purpose                                                               |
| ------------------------------ | --------------------------------------------------------------------- |
| [[00-inbox/00-inbox|00-inbox]] | Fast capture before sorting |
| [[01-concepts/01-concepts|01-concepts]] | Concepts, algorithms, math, and implementation notes |
| [[02-literature/02-literature|02-literature]] | Paper notes and citation-linked reading |
| [[03-ideas/03-ideas|03-ideas]] | Early ideas before they become projects |
| [[04-projects/04-projects|04-projects]] | Project hub notes that link everything together |
| [[05-experiments/05-experiments|05-experiments]] | Datasets, models, plans, runs, evaluations, ablations, error analysis |
| [[06-results/06-results|06-results]] | Distilled findings, result summaries, and figure-ready outputs |
| [[07-meetings/07-meetings|07-meetings]] | Advisor, group, collaboration, and committee meetings |
| [[08-manuscripts/08-manuscripts|08-manuscripts]] | Thesis chapters, papers, outlines, reviews, rebuttals |
| [[09-presentations/09-presentations|09-presentations]] | Talks, posters, conference notes, and event material |
| [[10-teaching/10-teaching|10-teaching]] | Lectures, training, and student supervision |
| [[20-research-log/20-research-log|20-research-log]] | Daily research logs |
| [[70-people/70-people|70-people]] | Advisor, collaborator, and contact notes |
| [[80-admin-and-funding/80-admin-and-funding|80-admin-and-funding]] | Funding, admin, forms, and bureaucracy |
| [[88-templates/vault-templates/vault-templates|88-templates/vault-templates]] | Active note templates |
| [[99-attachments/99-attachments|99-attachments]] | PDFs, figures, images, and exported artifacts |

## Naming Suggestions

Use names that sort well and make backlinks readable:

| Object | Example |
| --- | --- |
| Daily log | `20260505` |
| Paper | `paper-vaswani-2017-attention-is-all-you-need` |
| Project | `project-efficient-reasoning` |
| Idea | `idea-contrastive-search-for-agents` |
| Hypothesis | `hypothesis-retrieval-reduces-hallucination` |
| Training run | `run-2026-05-05-model-dataset-seed` |
| Evaluation | `evaluation-2026-05-05-benchmark-model` |

## Research Loop

1. Capture rough notes in [[00-inbox/00-inbox|00-inbox]].
2. Write paper notes in [[02-literature/02-literature|02-literature]] using [[88-templates/vault-templates/02-paper|02-paper]].
3. Convert promising thoughts into [[03-ideas/03-ideas|03-ideas]] using [[88-templates/vault-templates/05-research-idea|05-research-idea]].
4. Create a project hub in [[04-projects/04-projects|04-projects]] using [[88-templates/vault-templates/01-research-project|01-research-project]].
5. Turn ideas into hypotheses and experiment plans.
6. Record every run with commit, command, config, dataset version, and seeds.
7. Summarize results in project notes and manuscript outlines.

## Minimum Reproducibility Standard

Every experiment note should include:

- repository and git commit
- exact command
- config path or pasted config
- dataset version
- random seeds
- hardware
- metrics and result artifacts
- interpretation and next action

---
#vault_guide
