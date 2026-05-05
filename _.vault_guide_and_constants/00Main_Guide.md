# AI/ML PhD Vault Guide

This vault is built around traceable research work. A useful note should make it easy to answer:

- What question was I trying to answer?
- What evidence did I collect?
- Can I reproduce the result?
- How does this connect to my thesis?

## Folder Roles

| Folder | Purpose |
| --- | --- |
| `00inbox` | Fast capture before sorting |
| `01concepts_methods_theory` | Concepts, algorithms, math, and implementation notes |
| `02literature` | Paper notes and citation-linked reading |
| `03meetings` | Advisor, group, collaboration, and committee meetings |
| `04research_experiments` | Datasets, models, plans, runs, evaluations, ablations, error analysis |
| `10ideas` | Early ideas before they become projects |
| `20research_log` | Daily research logs |
| `30manuscripts` | Thesis chapters, papers, outlines, reviews, rebuttals |
| `40projects` | Project hub notes that link everything together |
| `50reading_lists` | Reading plans by area or project |
| `60code_systems` | Repositories, infrastructure, pipelines, and tool notes |
| `88templates/vault_templates` | Active note templates |
| `99attachments` | PDFs, figures, images, and exported artifacts |

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

1. Capture rough notes in `00inbox`.
2. Write paper notes in `02literature` using `02_.paper`.
3. Convert promising thoughts into `10ideas` using `05_.research_idea`.
4. Create a project hub in `40projects` using `01_.research_project`.
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
