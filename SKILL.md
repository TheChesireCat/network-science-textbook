---
name: network-science-textbook
description: Use the bundled network science course texts as a reusable local knowledge base for network science concepts, textbook-grounded summaries, and chapter-based explanations. Trigger when the user asks for Barabasi's Network Science textbook, Dima Krioukov's Network Science II lecture notes, or wants answers grounded in those course materials on topics like graphs, random networks, scale-free networks, preferential attachment, robustness, community structure, sparsity, small-worldness, clustering, assortativity, configuration models, graphons, latent space models, or stochastic block models.
---

# Network Science Textbook

Use the bundled course texts as the primary reference when the user wants textbook framing rather than a generic explanation.

## Quick Start

1. Open [references/index.md](references/index.md) to choose the relevant chapter.
2. Read only the chapter files needed for the request.
3. Answer in textbook terms and mention the chapter number or title when helpful.
4. Treat the textbook as background knowledge, not as the final authority on current research.

## Course Split

- Use Barabasi for the standard first-course coverage: graphs, random networks, scale-free networks, preferential attachment, robustness, communities, and epidemic spreading.
- Use Dima for the second-course / modeling-theory coverage: sparsity, small-worldness, clustering, assortativity, data binning, power laws, typicality, unbiased models, configuration models, dK-series, graphons, latent space models, and stochastic block models.
- If the user asks for "the textbook" without specifying which one, choose the course whose topics best match the request and say which source you are using.

## Workflow

### For concept lookup or explanation

- Start from [references/index.md](references/index.md).
- Open the most relevant course index first, then the relevant chapter file.
- Prefer paraphrase and synthesis over long quotation.
- If the user asks for intuition, preserve the textbook's examples and framing where useful.

### For summaries or notes

- Read the requested chapter or small set of chapters.
- Keep the output organized by concept, theorem, mechanism, or example rather than by raw paragraph order.
- Call out when a claim is textbook background versus newer literature or project-specific interpretation.

### For project grounding

- Use the textbook to establish definitions and baseline intuition.
- If the project involves modern sparse training, pruning, or lottery-ticket research, use the textbook for network-science foundations and keep that separate from later ML literature.

## Reference Files

- [references/index.md](references/index.md): top-level catalog for both course texts.
- [references/barabasi-textbook-network-science-1/index.md](references/barabasi-textbook-network-science-1/index.md): Barabasi chapter index.
- [references/dima-textbook-network-science-2/index.md](references/dima-textbook-network-science-2/index.md): Dima lecture-note index.

Read only the chapters relevant to the request. Do not load both course texts unless the task genuinely requires a comparison.
