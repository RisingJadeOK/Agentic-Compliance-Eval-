# Agentic-Compliance-Eval: Stress-Testing Financial LLMs

### The Problem
Large Language Models are surprisingly good at summarizing regulatory PDFs, but they struggle to maintain those same boundaries when given "Agency" (the power to use tools and execute tasks). This project moves away from static Q&A benchmarks to evaluate how agents behave in a multi-step banking workflow.

### Research Thesis
"Compliance Knowledge" does not equal "Compliance Adherence." Inspired by **HealthBench (Kratsios et al., 2024)**, this framework evaluates the execution gap where models fail to uphold PII and AML protocols despite having the underlying regulations in their context window.

### Key Deliverables
* **Compliance_Rubric.csv**: A tiered scoring system for high-stakes banking risks.
* **Adversarial_Scenarios.json**: 50+ test cases focused on social engineering and tool-use vulnerabilities.

### References
* Kratsios, I., et al. (2024). *HealthBench: Rigorous Evaluation for Healthcare AI*.
* Nair, V., et al. (2023). *Derisking AI in Financial Services*.
