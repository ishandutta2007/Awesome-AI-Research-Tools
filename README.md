# Awesome-AI-Research-Tools

# Top AI Research Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Literature Discovery, Autonomous Paper Generation & Peer Review*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Research Tools**. These tools enable researchers to search literature with semantic understanding, synthesize evidence across studies, visualize citation networks, and—at the frontier—autonomously generate research papers with simulated peer review.

**Examples** include SciSpace, Elicit Pro, Consensus, Semantic Scholar, Research Rabbit, Scite.ai, Paperpal, Iris.ai, Scholarcy, and Connected Papers (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, autonomous research generation, and open citation tooling—ideal for researchers, academics, and developers seeking transparent, vendor-independent research infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Elicit Pro](https://elicit.com/)**  
  **AI research assistant that automates literature reviews.** Searches 125M+ papers, extracts key information into structured tables, and synthesizes findings across studies. **The most focused tool for systematic review workflows.**

- **[Consensus](https://consensus.app/)**  
  **AI search engine that answers questions from peer-reviewed research.** Features **Consensus Meter** showing the degree of scientific agreement, **Study Snapshots** with key findings, and citation-backed answers. **The most transparent approach to evidence synthesis.**

- **[SciSpace](https://typeset.io/)**  
  AI research assistant with **Copilot** for paper Q&A, **Paraphraser** for rewriting, and **AI Detector**. Features literature review tables and citation generation.

- **[Semantic Scholar](https://www.semanticscholar.org/)**  
  **Free AI-powered research tool from Allen Institute for AI.** Features **Semantic Reader** with citation context, **TLDR summaries**, **Paper Recommendations**, and **API access**. **The most comprehensive open-access research graph** with 200M+ papers.

- **[Research Rabbit](https://www.researchrabbit.ai/)**  
  **Visual literature discovery and mapping.** Creates networks of related papers based on citations and co-authorship. **The most intuitive tool for exploring research landscapes.**

- **[Scite.ai](https://scite.ai/)**  
  **Smart Citations showing how papers have been cited**—supporting, contrasting, or mentioning. **The most rigorous approach to citation context analysis.** Features citation statements extracted from full text.

- **[Paperpal](https://paperpal.com/)**  
  AI academic writing assistant with grammar checking, language polishing, and submission readiness checks. **The most focused tool for manuscript preparation.**

- **[Iris.ai](https://iris.ai/)**  
  AI research assistant with **Research Assistant** for literature mapping and **Tools for Researchers** including paper summarization and dataset exploration.

- **[Scholarcy](https://www.scholarcy.com/)**  
  AI-powered article summarization with **flashcard generation**, **key term extraction**, and **reference linking**. **The most focused tool for rapid paper triage.**

- **[Connected Papers](https://www.connectedpapers.com/)**  
  **Visual exploration of academic papers**—generates a graph of related work based on citations and co-citations. **The most intuitive tool for literature mapping.**

## Open-Source GitHub Projects

- **[AI-Scientist-v2 (Sakana AI)](https://github.com/SakanaAI/AI-Scientist-v2)**  
  **The most advanced open-source autonomous research paper generation and peer-review system** (Apache-2.0). **The first AI system to produce a workshop-level paper that passed peer review** —one of three fully AI-generated papers accepted at ICLR 2025 workshop . **Uses progressive agentic tree search** to autonomously generate research ideas, run experiments, analyze results, and write papers . **The system runs the entire research loop autonomously** —hypothesis generation, experimental design, code execution, result interpretation, and manuscript writing . **Includes automated peer-review simulation** for self-critique and improvement . **The definitive open-source implementation for autonomous scientific discovery.** **Note**: Requires significant compute for experimentation.

- **[PaperQA2 (Future House)](https://github.com/Future-House/paper-qa)**  
  **The most accurate open-source RAG system for scientific literature** (Apache-2.0). **Answers questions with citations from scientific PDFs** —retrieves, reads, and synthesizes across thousands of papers . **Outperforms GPT-4 on scientific Q&A benchmarks** . Features **agentic search**, **citation-grounded answers**, and **contradiction detection** . **The standard open-source tool for literature Q&A.**

- **[AI-Scientist (Sakana AI v1)](https://github.com/SakanaAI/AI-Scientist)**  
  **The original autonomous research paper generation system** (Apache-2.0). **The predecessor to AI-Scientist-v2** —demonstrated end-to-end paper generation with idea generation, experimentation, and manuscript writing . **The foundational implementation** for the autonomous research field.

- **[PaperQA](https://github.com/Future-House/paper-qa)**  
  The original PaperQA implementation. See PaperQA2 above for the successor.

- **[OpenAlex](https://github.com/ourresearch/openalex-guts)**  
  **Open scholarly metadata covering 250M+ works** (CC0) . **The most comprehensive open-access research graph** —papers, authors, institutions, concepts, and citations . **Free API access** with no rate limits for reasonable use . **The open alternative to proprietary citation databases.**

- **[Zotero](https://github.com/zotero/zotero)**  
  **The standard open-source reference manager** (AGPL-3.0) . **Collect, organize, cite, and share research sources** —browser extension for one-click saving, Word/LibreOffice integration for citation insertion, and group libraries for collaboration . **The most widely adopted open-source citation tool.**

- **[Scholarly](https://github.com/scholarly-python-package/scholarly)**  
  **Python library for Google Scholar queries** (MIT) . Features **author profile extraction**, **publication parsing**, and **citation network exploration** . **The most accessible open-source Google Scholar interface.**

- **[Arxiv.py](https://github.com/lukasschwab/arxiv.py)**  
  **Python wrapper for the arXiv API** (MIT) . Features **paper search**, **metadata retrieval**, and **PDF download** . **The standard open-source tool for arXiv integration.**

- **[PyPaperBot](https://github.com/ferreiradev/PyPaperBot)**  
  **Download scientific papers using DOIs** (MIT) . Features **Sci-Hub integration**, **BibTeX generation**, and **batch downloads** . **The most practical open-source paper downloader.**

- **[Zotero Better BibTeX](https://github.com/retorquere/zotero-better-bibtex)**  
  **Citation management extension for Zotero** (MIT) . Features **BibTeX/BibLaTeX export**, **citation key generation**, and **LaTeX integration** . **The standard open-source citation workflow for LaTeX users.**

- **[LitLLM (PolyU)](https://github.com/LitLLM/LitLLM)**  
  **Open-source literature review assistant** (MIT) . Features **related work generation**, **citation retrieval**, and **RAG-based synthesis** . **The most focused open-source tool for related work sections.**

- **[Guttenberg (Sakana AI)](https://github.com/SakanaAI/Guttenberg)**  
  **Open-source autonomous research pipeline** (Apache-2.0) from Sakana AI. **Part of the AI-Scientist ecosystem** —automates literature review, hypothesis generation, and experimental design .

### Additional Strong Open-Source Options

- **[SciPy](https://github.com/scipy/scipy)** — Foundational scientific computing library (BSD-3-Clause) for research workflows .
- **[Pandas](https://github.com/pandas-dev/pandas)** — Data analysis library (BSD-3-Clause) for research data manipulation .
- **[Jupyter](https://github.com/jupyter/notebook)** — Interactive computing environment (BSD-3-Clause) for reproducible research .
- **[Snakemake](https://github.com/snakemake/snakemake)** — Workflow management for reproducible research (MIT) .
- **[DVC](https://github.com/iterative/dvc)** — Data version control for ML experiments (Apache-2.0) .
- **[MLflow](https://github.com/mlflow/mlflow)** — ML lifecycle management (Apache-2.0) for experiment tracking .
- **[Papers with Code](https://github.com/paperswithcode/paperswithcode-data)** — ML paper and code repository (CC BY-SA 4.0) .
- **[Connected Papers Alternatives](https://github.com/topics/literature-review)** — Community projects for literature visualization .
- Community **n8n** workflows for literature monitoring and research alert automation.

**Frameworks for building custom systems**: Combine **AI-Scientist-v2** for autonomous research generation with **PaperQA2** for literature Q&A, **OpenAlex** for scholarly metadata, **Zotero** for reference management, and **Snakemake** or **DVC** for reproducible experiments—creating a fully self-hosted, enterprise-grade AI research platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI research tools handling academic papers must comply with copyright law and publisher terms of service. **Autonomous paper generation raises authorship and attribution questions** —verify journal policies before submission.
- **AI-Scientist-v2 is a genuine breakthrough.** One of three fully AI-generated papers passed peer review at ICLR 2025 workshop . **This is the first time an AI-generated paper has been accepted at a peer-reviewed venue** —a milestone for autonomous research.
- **PaperQA2 outperforms GPT-4 on scientific Q&A.** It answers with citations from actual papers, not from training data . **Citation grounding is the difference between research and speculation.**
- **OpenAlex is the open-access research graph.** 250M+ works under CC0—no rate limits, no paywalls, no vendor lock-in . **The open alternative to proprietary citation databases.**
- **Citation context matters.** Scite.ai distinguishes supporting from contrasting citations . **A paper cited 100 times tells you nothing about whether those citations agree or disagree.**
- **Autonomous research requires human oversight.** AI-Scientist-v2 generates papers, but **human researchers must validate findings, verify reproducibility, and take responsibility for publication** . AI is a tool, not an author.
- Self-hosted open-source solutions require proper compute provisioning for AI-Scientist experiments, data management, and ongoing maintenance. **Research data may be subject to institutional review and data protection requirements.**

---

**Made for researchers, academics, and developers building transparent AI research solutions.**  
Let's make AI Research Tools more open, data-driven, and citation-grounded.
