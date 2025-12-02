# Case Study

<div class="figure-grid">
<figure>
  <img src="assets/fig/casestudy.webp" alt="Case Study Figure">
</figure>
</div>

<ol class="alpha-list">
  <li>Episodic memory alone is often insufficient for capturing the detailed visual context required for accurate reasoning. When the model relies solely on episodic memory, it overlooks fine-grained object attributes, such as the specific type of baked item, which leads to incorrect predictions. By contrast, the retrieval agent can dynamically retrieve from visual memory, retrieving the corresponding video frames. By incorporating the visual context, the model can precisely interpret objects, activities, and their fine-grained characteristics.</li>
  <li>Episodic memory struggles to represent patterns or behaviors that extend beyond an individual event, failing to capture habitual behaviors, such as what is regularly used to wipe kitchenware. The retrieval agent addresses this limitation by dynamically retrieving from semantic memory, which encodes long-term, repeated behaviors accumulated across episodes. This access to cumulative, habitual knowledge allows the model to perform more robust long-term reasoning, even when individual episodes lack explicit evidence.</li>
</ol>

Together, they highlight the complementary roles of multimodal memories: visual memory provides perceptual detail, while semantic memory encodes the high-level knowledge about relationships and habits. The retrieval agent’s ability to dynamically retrieve from these memories enables more accurate and contextually grounded reasoning than episodic memory alone.