# 🤝 Contributing to `rags-lab`

Welcome to **rags-lab**. A collaborative workspace for exploring, discussing, and building next-generation Retrieval-Augmented Generation (RAG) systems. This document explains how to contribute, how to format proposals, and how discussions are managed via Pull Requests (PRs).

## 🧭 Overview

**rags-lab** operates through open collaboration driven by **Pull Requests**, not issues. Every idea, proposal, or addition... whether it’s a new paper, framework, or concept... starts with a PR.

Each PR acts as a **discussion thread** where contributors can,
- Propose new RAG architectures or experiments  
- Share research papers, datasets, or frameworks  
- Brainstorm approaches collaboratively  
- Decide collectively before merging or closing the idea  

Once a proposal is refined and accepted, it moves into
- `/ideas` for accepted research directions  
- `/implementations` for projects under development  

## ⚙️ Contribution Workflow

1. **Fork & Clone**
```bash
git clone https://github.com/<your-username>/rags-lab.git
cd rags-lab
```

2. **Create a Branch**
```bash
git checkout -b proposal/<short-title>
```

3. **Add Your Proposal or Resource**
- For ideas/discussions: place it in `/discussions/`
- For accepted ideas: move to `/ideas/`
- For new frameworks/papers/tools update relevant directories

4. **Commit & Push**
```bash
git add .
git commit -m "Proposal: <Your Proposal Title>"
git push origin proposal/<short-title>
```

5. **Open a Pull Request (PR)**
- Use the PR template below
- Tag it appropriately (e.g., `proposal`, `paper`, `framework`, `discussion`, `misc`, etc)
- Collaborators can comment and iterate within the PR

## 🧩 Pull Request Template
Each PR should follow this structure to ensure clarity and context. We shall soon be adding these as PR templates to the repository so that contributors can directly select a default template for their PR.
```md
# 🧠 Proposal: <Title of Your Idea or Contribution>

## 📘 Summary
Briefly describe the idea, framework, or resource you're introducing.  
What problem does it address? Why is it worth exploring?

---

## 🎯 Motivation / Rationale
- What gap or limitation in existing RAG systems does this target?
- What’s novel or different about this idea?
- What could be the potential impact?

---

## 🧩 Core Concept
Explain the core mechanism or hypothesis in simple, structured terms.

**Example format:**
- Input pipeline:
- Retrieval strategy:
- Generation mechanism:
- Evaluation or reliability metric (if any):

Include diagrams, pseudo-code, or links if relevant.

---

## 🔍 References & Related Work
List any relevant papers, frameworks, or resources:
- [Paper Title](link)
- [Framework / Library](link)
- Related PRs or discussions (if applicable)

---

## 🤔 Open Questions
- What needs further discussion or validation?
- What are the unknowns, challenges, or assumptions?

---

## ✅ Next Steps
Outline what should happen *if accepted*:
- [ ] Move to `/ideas/` or `/implementations/`
- [ ] Assign contributors or maintainers
- [ ] Define a minimal reproducible prototype

---

## 🧑‍💻 Contributors
Tag the people initiating or supporting the discussion.
```

## 🧱 Types of Contributions
| Type	| Description |	Location |
|-------|-------------|----------|
|💡 Proposal | New architecture, retrieval method, or experimental idea |	`/discussions/` |
|📄 Paper/Survey | Academic papers or summaries	| `/papers/` |
|🧰 Framework/Tool	| RAG frameworks, APIs, or infrastructure components | `/frameworks/` |
|📊 Benchmark | Dataset, metric, or evaluation report |	`/benchmarks/` |
|🧪 Implementation | Accepted ideas under development	| `/implementations/` |

## 💬 Discussion Guidelines
- Be clear and constructive in feedback
- Critique the idea, not the individual
- Keep PRs focused. One topic per proposal
- Use data, experiments, or references wherever possible
- Mark comments as Resolved once addressed

## 🧾 Decision Process
- **Open PR:** Active discussion
- **Merged PR:** Accepted and added to `/ideas` or `/implementations`
- **Closed PR:** Rejected, parked, or merged elsewhere

Decisions are made based on clarity, feasibility, and value to the RAG ecosystem.

## 🧠 Tips for High-Quality Contributions
- Read recent PRs to avoid duplicates
- Provide clear motivations backed by existing research
- Include minimal reproducible examples when possible
- Use plain Markdown. Clarity > Complexity
- Link related frameworks or datasets directly

🧩 Example PR Titles
- `Proposal: Graph-based Retrieval-Augmented Generation`
- `Framework Addition: Haystack v2.0`
- `Paper Summary: Enhancing Context Compression in RAG`
- `Idea: Multi-hop Vector Retrieval Optimization`
- `Benchmark: RAG Evaluation Metrics Suite`

⭐ If you find value in this repository, give it a star and join the discussion.

</div>
