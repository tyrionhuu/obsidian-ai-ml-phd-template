---
aliases:
  - mermaid
---
# Mermaid

Mermaid is useful for lightweight diagrams in research notes, especially model pipelines, experiment workflows, and project timelines.

## Example

```mermaid
graph TD
    A[Research question] --> B[Hypothesis]
    B --> C[Experiment plan]
    C --> D[Training run]
    D --> E[Evaluation]
    E --> F{Result supports hypothesis?}
    F -->|Yes| G[Write result]
    F -->|No| H[Error analysis]
    H --> B
```

Documentation: <https://mermaid.js.org/>

---
#concept
