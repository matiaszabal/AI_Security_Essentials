# AI_Security_Essentials

This curriculum provides a comprehensive technical foundation for securing modern artificial intelligence systems, moving from basic machine learning vulnerabilities to the complex security challenges of autonomous agentic systems.
overview 2025 2026
https://hi120ki.github.io/blog/posts/20260103/

## AI Security Essentials: Full Curriculum

### Module 1: Foundations of Artificial Intelligence

* **Architectural Overview**: Technical breakdown of Machine Learning (ML), Large Language Models (LLMs), and Agentic AI.
* **Infrastructure Components**: Analysis of vector databases, orchestrators (LangChain/AutoGPT), and inference engines.
* **Data Flow Analysis**: Identifying trust boundaries between users, models, and external data sources.

### Module 2: AI Threat Landscape

* **Adversarial Machine Learning**: Evasion attacks, model inversion, and membership inference.
* **Data Integrity**: Identifying training data poisoning and supply chain vulnerabilities in pre-trained models.
* **Exploitation Vectors**: Mapping threats to the MITRE ATLAS (Adversarial Threat Landscape for Artificial-Intelligence Systems) framework.

### Module 3: OWASP ML Security Top 10 (2023)

* **Core Risks**: Detailed analysis of the top vulnerabilities including ML01: Input Manipulation and ML04: Model Inversion.
* **Countermeasures**: Implementation of input sanitization and differential privacy techniques.

### Module 4: OWASP LLM Security Top 10 (2024)

* **Injection Attacks**: Deep dive into Direct and Indirect Prompt Injection.
* **Data Leakage**: Mitigating training data sensitive information disclosure.
* **Output Handling**: Preventing XSS and SSRF through insecure output handling.

### Module 5: OWASP Agentic AI Security (2024–2025)

* **Excessive Agency**: Managing risks when agents have broad permissions to execute code or access APIs.
* **Goal Manipulation**: Preventing attackers from hijacking an agent's reasoning loop (ReAct pattern).
* **Multi-Agent Coordination**: Security protocols for inter-agent communication and task delegation.

### Module 6: Secure AI Development Lifecycle (SAIDLC)

* **Secure Design**: Threat modeling specific to AI-enabled applications.
* **Secure Development**: Version control for datasets and model weights (Data-Sec-Ops).
* **Secure Deployment**: Implementing model guardrails and API rate limiting.
* **Monitoring**: Continuous logging for "jailbreak" attempts and distribution shift detection.

### Module 7: Deepfakes and Disinformation

* **Generative Risks**: Technical mechanisms behind synthetic media generation.
* **Detection & Attribution**: Implementing digital watermarking and provenance tracking (C2PA standards).

### Module 8: Shadow AI and Governance

* **Detection**: Identifying unauthorized SaaS AI usage within enterprise networks.
* **Policy Enforcement**: Establishing Acceptable Use Policies (AUP) and technical controls for data egress to public LLMs.

### Module 9: AI Red Teaming

* **Methodology**: Planning and executing adversarial simulations.
* **Tooling**: Hands-on with automation frameworks like PyRIT (Microsoft) and Garak.
* **Reporting**: Translating technical findings into risk-informed remediation plans.

---

## Primary Learning Resources

* **OWASP AI Exchange**: The definitive repository for AI security standards and the LLM/Agentic Top 10 lists.
* **NCSC/NIST Guidelines**: "Guidelines for Secure AI System Development" (NCSC) and the NIST AI Risk Management Framework (AI RMF 1.0).
* **MITRE ATLAS**: A knowledge base of adversary tactics and techniques based on real-world observations.
* **BSI Germany**: "Security of AI-Systems: Fundamentals" for a deep dive into adversarial deep learning.
* **AISA Lab Assets**: Access to the AISA (AI Security Academy) virtual labs for hands-on prompt injection and model extraction exercises.


[Episode 1: What is AI Red Teaming?](https://www.youtube.com/watch?v=DabrWAKNQZc)

This video provides a foundational introduction to the AI Red Teaming concepts covered in Module 9, specifically focusing on the differences between traditional security testing and AI-specific adversarial simulations.
