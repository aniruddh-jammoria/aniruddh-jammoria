Product builder - 10+ years shipping products across consumer goods, e-commerce, and healthcare. Currently focused on AI/ML and agentic applications. Some of the things I've built so far:

- **AI agents** for knowledge base management and research
- **Clinical decision support** applications for digital pathology
- **Vision foundation models, RAG and vector search** applications
- **FDA, GDPR and EU AI Act frameworks** for AI/ML products
- **ML-powered recommendation systems** for detecting similar products using vision and text embeddings
- **Regional availability optimizations** for Amazon search
- **Payments, promotion, authentication and checkout** systems for cashierless Just-Walk-Out stores
- **A/B testing and experimentation frameworks** for online stores and physical retail
- **Water-saving formulations** for hand-wash detergents

Currently building:

- **eval-dual-GPU**: A benchmarking suite that measures whether a second GPU in a slower PCIe slot actually helps local LLM inference — tests 8 models (dense and MoE) across 5 GPU configurations on two RTX 5060 Ti cards, using Ollama and llama.cpp, with results published to a live dashboard.
  - Last updated: Jul 5, 2026 — added power-draw metrics and a long-document test tier, and built out a multi-metric dashboard.

- **obsidian-agentic-todolist (AgentBoard)**: An Obsidian plugin that turns a Markdown todo file into a two-way-synced, Google-Tasks-style kanban board, designed so an AI agent writes/prioritizes tasks into the file while you refine them on the board (edits sync straight back to Markdown).
  - Last updated: Jul 5, 2026 — shipped v2.0.0, adding prioritization, on-board editing, and the full agentic workflow, then hardened it with build-provenance attestations for the release pipeline.

- **gpt-from-scratch**: A from-scratch, notebook-based build of GPT-style language models following Karpathy's "Let's build GPT," implementing a bigram baseline then a full transformer (attention, multi-head, residuals, layer norm) trained on Tiny Shakespeare.
  - Last updated: Jun 25, 2026 — added the full NanoGPT transformer implementation plus save/load integration with the Hugging Face Hub.

- **research-newsletter-pipeline**: A configurable pipeline that generates a weekly research/news newsletter as a PDF and delivers it via Telegram, pulling web articles, academic papers, and top tweets per a YAML config, with LLM-based filtering and dedup.
  - Last updated: Jun 21, 2026 — added the research-papers and Twitter-highlights modules alongside the original news module, rounding out the three-part content pipeline.

- **search-api-eval**: A benchmarking framework for comparing web search API providers by running identical queries across them and scoring results with two independent LLM judges (Claude and GPT-4o-mini) on relevance/newsworthiness, outputting a self-contained HTML report.
  - Last updated: Jun 13, 2026 — added an AI-generated recommendation to the eval report and published a sample report via GitHub Pages.
