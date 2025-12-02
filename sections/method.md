# Method

<div class="figure-grid">
<figure>
  <img src="assets/fig/method.webp" alt="Method Figure">
</figure>
</div>

## Multimodal Memory Construction
**WorldMM** builds a unified multimodal memory system that captures complementary aspects of long videos, enabling reasoning across diverse modalities and timescales:

- **Episodic Memory**: Multi-scale textual event graphs built from captions of fine-to-coarse video segments, allowing both detailed and long-range temporal understanding.
- **Semantic Memory**: A continuously updated knowledge graph that accumulates high-level relationships and habits across the full video.
- **Visual Memory**: A hybrid visual store combining feature embeddings for keyword-based semantic search and timestamped frames for precise visual grounding.

## Adaptive Memory Retrieval
The **retrieval agent** iteratively decides which memory to access and what query to issue, conditioned on the user question and retrieval history.
At each step, it evaluates the information gathered so far and identifies what additional evidence is needed. It then retrieves from the selected memory using a targeted search query.
Through successive iterations, the agent progressively refines its retrieval strategy and accumulates a more precise and comprehensive set of knowledge across diverse multimodal memories.

## Response Generation
Once sufficient information is collected, a **response agent** synthesizes the retrieved evidence and the reasoning history to produce a final, grounded answer.
