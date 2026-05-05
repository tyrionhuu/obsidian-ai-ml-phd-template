# AI/ML PhD Vault Guide

This vault is built around traceable research work. A useful note should make it easy to answer:

- What question was I trying to answer?
- What evidence did I collect?
- Can I reproduce the result?
- How does this connect to my thesis?

## Folder Roles

| Folder                         | Purpose                                                               |
| ------------------------------ | --------------------------------------------------------------------- |
| [[00 Inbox/00 Inbox|00 Inbox]] | Fast capture before sorting |
| [[01 Concepts/01 Concepts|01 Concepts]] | Concepts, algorithms, math, and implementation notes |
| [[02 Literature/02 Literature|02 Literature]] | Paper notes and citation-linked reading |
| [[03 Ideas/03 Ideas|03 Ideas]] | Early ideas before they become projects |
| [[04 Projects/04 Projects|04 Projects]] | Project hub notes that link everything together |
| [[05 Experiments/05 Experiments|05 Experiments]] | Datasets, models, plans, runs, evaluations, ablations, error analysis |
| [[06 Results/06 Results|06 Results]] | Distilled findings, result summaries, and figure-ready outputs |
| [[07 Meetings/07 Meetings|07 Meetings]] | Advisor, group, collaboration, and committee meetings |
| [[08 Manuscripts/08 Manuscripts|08 Manuscripts]] | Thesis chapters, papers, outlines, reviews, rebuttals |
| [[09 Presentations/09 Presentations|09 Presentations]] | Talks, posters, conference notes, and event material |
| [[10 Teaching/10 Teaching|10 Teaching]] | Lectures, training, and student supervision |
| [[20 Research Log/20 Research Log|20 Research Log]] | Daily research logs |
| [[70 People/70 People|70 People]] | Advisor, collaborator, and contact notes |
| [[80 Admin and Funding/80 Admin and Funding|80 Admin and Funding]] | Funding, admin, forms, and bureaucracy |
| [[88 Templates/Vault Templates/Vault Templates|88 Templates/Vault Templates]] | Active note templates |
| [[99 Attachments/99 Attachments|99 Attachments]] | PDFs, figures, images, and exported artifacts |

## Naming Suggestions

Use names that sort well and make backlinks readable:

| Object | Example |
| --- | --- |
| Daily log | `20260505` |
| Paper | `@Vaswani2017_AttentionIsAllYouNeed` |
| Project | `project$efficient_reasoning` |
| Idea | `idea$contrastive_search_for_agents` |
| Hypothesis | `hypothesis$retrieval_reduces_hallucination` |
| Training run | `run$20260505_model_dataset_seed` |
| Evaluation | `eval$20260505_benchmark_model` |

## Research Loop

1. Capture rough notes in [[00 Inbox/00 Inbox|00 Inbox]].
2. Write paper notes in [[02 Literature/02 Literature|02 Literature]] using [[88 Templates/Vault Templates/02_.paper|02_.paper]].
3. Convert promising thoughts into [[03 Ideas/03 Ideas|03 Ideas]] using [[88 Templates/Vault Templates/05_.research_idea|05_.research_idea]].
4. Create a project hub in [[04 Projects/04 Projects|04 Projects]] using [[88 Templates/Vault Templates/01_.research_project|01_.research_project]].
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
