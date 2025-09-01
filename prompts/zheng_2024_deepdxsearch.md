**Title:** End-to-End Agentic RAG System Training for Traceable Diagnostic Reasoning
**Authors:** Qiaoyu Zheng, Yuze Sun, Chaoyi Wu, Weike Zhao, Pengcheng Qiu, Yongguo Yu, Kun Sun, Yanfeng Wang, Ya Zhang, Weidi Xie
**Venue & Year:** arXiv preprint, August 2024
**Link to PDF or DOI:** [arXiv:2508.15746](https://arxiv.org/abs/2508.15746)
**Keywords:** Medical AI, Diagnostic Reasoning, Retrieval-Augmented Generation, Reinforcement Learning, Agentic Systems

**Summary (3–5 sentences):**
This paper introduces Deep-DxSearch, an AI system that addresses knowledge gaps in large language models for medical diagnosis by training an agentic Retrieval-Augmented Generation (RAG) system using reinforcement learning. The approach frames the LLM as an "agent" that interacts with a large-scale medical retrieval corpus as its "environment," using tailored rewards for format compliance, retrieval accuracy, reasoning structure, and diagnostic precision. The system constructs a comprehensive medical knowledge base combining patient records and medical literature, then trains the agent to perform traceable diagnostic reasoning. Deep-DxSearch demonstrates superior diagnostic accuracy compared to baseline models like GPT-4o and DeepSeek-R1 across multiple medical datasets, particularly excelling in both common and rare disease diagnosis.

**What's novel or useful about this paper?**
Unlike traditional RAG systems that simply append retrieved information, this work treats retrieval as an interactive process where the LLM agent learns to strategically query and reason with medical knowledge. Key innovations include:

The agentic framework that enables dynamic, multi-step retrieval and reasoning rather than single-shot information lookup.

Reinforcement learning training with multi-faceted rewards that optimize not just diagnostic accuracy but also reasoning traceability and retrieval relevance.

A large-scale medical corpus construction methodology that combines structured patient data with unstructured medical literature for comprehensive knowledge coverage.

End-to-end training that jointly optimizes retrieval strategies and diagnostic reasoning, making the system more coherent and effective.

The emphasis on traceable reasoning provides interpretability crucial for medical applications, addressing the "black box" problem in AI diagnosis.

**One question you'd ask the authors:**
How does the system handle conflicting information between retrieved sources, and what mechanisms ensure the diagnostic reasoning remains robust when faced with incomplete or contradictory medical evidence?

**Personal Reflection (Optional):**
This paper represents a significant step toward more reliable AI in healthcare by addressing both the knowledge limitation and interpretability challenges of current LLMs. The agentic approach to RAG feels like a natural evolution that could be applied beyond medical diagnosis to other domains requiring evidence-based reasoning.