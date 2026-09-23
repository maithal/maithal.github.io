# Featured Research & Systems

### 1. PLACID: Privacy-Preserving Clinical Acronym Disambiguation
*The Mitchell Lab, CU Anschutz | Dec 2025 – Present*
- **Problem:** Cloud-hosted LLMs cannot process sensitive patient health information under HIPAA/privacy regulations.
- **Solution:** Architected a two-stage cascaded pipeline routing instruction-following models (acronym detection) to specialized biomedical models (contextual expansion).
- **Impact:** Benchmarked small on-device models (2B–10B); achieved ~0.988 detection accuracy and lifted expansion accuracy from ~0.655 to ~0.81 with zero external data egress.
- **Status:** Preprint on arXiv ([arXiv:2603.23678](https://arxiv.org/abs/2603.23678)) | [Lab Project Page](https://www.jamphd.com/placid.html) | Presented at AMIA 2026.

---

### 2. LadderTeam: Dual-Agent Requirement Elicitation Framework
*The Mitchell Lab, CU Anschutz | Dec 2025 – Present*
- **Problem:** Eliciting detailed clinical software requirements using laddering interviews is highly manual, variable, and skill-dependent.
- **Solution:** Designed an autonomous dual-agent architecture (Interviewer & Judge) supporting ACV, 5-Whys, and JTBD probing techniques.
- **Architecture:** 5-step state-gated conversational loop with drift detection and a background evaluation judge scoring dialogue without interrupting user flow.
- **Impact:** 99.1% chain convergence (214 of 216 runs), 81.0% ground-truth actionable match, and zero conversational drift across 216 controlled simulation runs.
- **Status:** Preprint on arXiv ([arXiv:2608.17029](https://arxiv.org/abs/2608.17029)) | [Lab Project Page](https://www.jamphd.com/clarifai.html) | Poster at ACM AI Leadership Summit 2026.

---

### 3. PersonaDrift: Black-Box Persona Stability Measurement
*The Mitchell Lab, CU Anschutz | Dec 2025 – Present*
- **Problem:** Personality-calibrated language model agents drift from their assigned persona during long multi-turn interactions in clinical patient simulations.
- **Solution:** Engineered a 3-channel black-box drift measurement framework (NEO-FFI trait score, behavioural deflection signature, and external judge model).
- **Architecture:** Behavioral deflection computed as sentence-transformer cosine distance to fixed persona signatures without requiring access to internal model activations.
- **Status:** Target submission for AAMAS 2027 Main Technical Track.

---

### 4. MiniGali: Local Knowledge Agent for Healthcare
*CU Innovations Fellowship | FY 2026 – 2027*
- **Overview:** Fully local, privacy-preserving retrieval-augmented generation (RAG) agent that captures institutional program knowledge for internal clinical decision support.
- **Focus:** Complete on-premise execution guaranteeing data sovereignty for sensitive institutional workflows.

---

### 5. Enterprise Gen-AI Camera & Edge Vision Systems
*Lenovo Research | Nov 2022 – Oct 2025*
- **Overview:** High-throughput computer vision and generative models deployed to enterprise laptops and mobile devices.
- **Key Innovations:**
  - Designed blink & gaze correction solution for enterprise Gen-AI platform.
  - Built ultra-lightweight Super Resolution module (8ms latency, +71MB GPU overhead).
  - Engineered novel GAN training infrastructure with CI/CD, cutting training time by 40% and manual QA by 85%.
  - Standardized device-wide benchmarking dashboards, cutting test cycles from 6 hours to 2 hours.
- **Recognition:** 2 patent filings, Lenovo SVP Individual Excellence Award.
