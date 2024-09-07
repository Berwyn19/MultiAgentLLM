# Flash Fiction Generation with Multi-Agent Pipelines

This project explores the use of multi-agent communication to enhance the creative capabilities of Large Language Models (LLMs) in generating flash fiction stories. Inspired by collaborative processes such as writers' rooms, we designed and implemented three distinct pipelines to improve the quality of AI-generated creative writing:

1. **Reiterative Feedback Mechanism (RFM)**
2. **Modular Feedback-Enhanced Revision (MFER)**
3. **Mixture of Experts-Inspired Modular Feedback-Enhanced Revision (MOE-MFER)**

Each pipeline applies different strategies to balance creativity and coherence in story generation through iterative feedback and multi-agent collaboration.

### Key Findings:
- **RFM** utilizes a large guiding model, like Gemini, alongside external story resources, and consistently produces stable story outputs.
- **MFER** operates reliably based on well-established research methods and maintains a consistent mechanism for generating coherent stories.
- **MOE-MFER** demonstrates high variability but shows promise in producing highly creative and interesting narratives.

### Conclusion:
Our study demonstrates that structured multi-agent collaboration can significantly improve story generation, even for smaller, open-source models like Zephyr-1.6B. Flash fiction serves as a proxy for broader creative tasks, showcasing the potential to generate more innovative ideas when operating under constrained prompts. Future work could focus on refining these pipelines to further reduce variability, enhance the balance between creativity and coherence, and explore more diverse datasets for LLM-based story generation in broader applications.
