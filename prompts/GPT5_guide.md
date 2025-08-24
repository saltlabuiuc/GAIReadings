**Title:** GPT-5 Prompting Guide
**Authors:** OpenAI Cookbook Team
**Venue & Year:** Aug 7, 2025
**Link to PDF or DOI:** [OpenAI Cookbook – GPT-5 Prompting Guide](https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide)
**Keywords:** Prompt Engineering, Context Design, GPT-5, Instruction Following, Best Practices

**Summary (3–5 sentences):**. 
The GPT-5 Prompting Guide presents a collection of tested strategies for eliciting reliable, controllable, and high-quality responses from GPT-5. It highlights techniques such as role prompting (e.g., “You are a debate coach…”), structured outputs (forcing JSON or Markdown tables), and few-shot demonstration to anchor responses in concrete examples. The guide introduces advanced methods like self-consistency prompting (sampling multiple reasoning paths and selecting the majority answer), step-by-step scaffolding (breaking tasks into subtasks across multiple turns), and prompt compression (shortening instructions into reusable “macros” to reduce token usage). It also emphasizes style and verbosity control by explicitly instructing the model to be “concise” or “elaborative,” as well as iterative refinement loops, where the model critiques and improves its own outputs.

**What’s novel or useful about this guide?**
Unlike earlier prompting tutorials, this guide organizes prompting into a toolbox of reusable strategies tied directly to GPT-5’s capabilities. For example:

It shows how to control randomness with temperature + self-consistency, improving reasoning quality.

It formalizes scaffolding prompts, where one prompt generates outlines and another fills details, effectively chaining the model with itself.

It introduces prompt compression tricks (abbreviated shorthand instructions) that retain instruction fidelity while saving tokens in long workflows.

It gives actionable patterns like “delimiters for clarity” (e.g., triple quotes or XML tags around data) to avoid hallucination.

These strategies are presented with copy-and-paste examples, making them directly usable for developers.

**One question you’d ask the authors:**
How can developers best balance prompt specificity with flexibility, ensuring robustness across varied tasks without overfitting to a single style?

**Personal Reflection (Optional):**
Reading this guide highlighted how much prompting is both an art and a science. I realized that small adjustments—like structuring outputs in JSON or giving one worked example—can dramatically improve model reliability in my own projects.
