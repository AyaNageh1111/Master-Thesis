# Concept Grounding in Concept Bottleneck Models Papers

Paper 1 — Addressing Leakage in Concept Bottleneck Models (2022)

* **Authors:** Marton Havasi, Sonali Parbhoo, Finale Doshi-Velez.
* **Venue:** NeurIPS 2022.
* **Problem:** When the final classifier is trained on predicted concept *probabilities*, these values can encode unintended label information. Predictions can look good even when concepts are inaccurate or difficult to correct through interventions.
* **Method:**
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 3 (concept leakage)**; **Problem 6 (evaluating the value of interventions)**.
* **Paper:** https://papers.neurips.cc/paper\_files/paper/2022/hash/944ecf65a46feb578a43abfd5cddd960-Abstract-Conference.html

## Paper 2 — GlanceNets: Interpretable, Leak-proof Concept-based Models (2022)

* **Authors:** Emanuele Marconato, Andrea Passerini, Stefano Teso.
* **Venue:** NeurIPS 2022.
* **Problem:** Learned concept representations may not align with their intended meanings and may contain spurious, unintended information.
* **Method:** Defines interpretability through alignment with the factors underlying data generation. GlanceNets combines disentangled representation learning, concept-level supervision, and open-set recognition to identify representations that do not fit the intended concept structure.
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 3 (concept leakage)**; **Problem 1 (incorrect grounding / semantic alignment)** and **Problem 6 (diagnostic evaluation)**.
* **Paper:** https://proceedings.neurips.cc/paper\_files/paper/2022/hash/85b2ff7574ef265f3a4800db9112ce14-Abstract-Conference.html
* **Code:** https://github.com/ema-marconato/glancenet

## Paper 3 — Coarse-to-Fine Concept Bottleneck Models (2024)

* **Authors:** Konstantinos P. Panousis, Dino Ienco, Diego Marcos.
* **Venue:** NeurIPS 2024.
* **Problem:** Global image-level concept representations can miss meaningful, localized evidence and cannot explain fine-grained parts of scenes.
* **Method:** 
* **Finding / contribution:**
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 4 (poor spatial localization)**; **Problem 1 (incorrect grounding)**.
* **Paper:** https://papers.nips.cc/paper\_files/paper/2024/hash/bdeab378efe6eb289714e2a5abc6ed42-Abstract-Conference.html
* **Code:** https://github.com/konpanousis/Coarse-To-Fine-CBMs

## Paper 4 — VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance (2024)

* **Authors:** Divyansh Srivastava, Ge Yan, Tsui-Wei Weng.
* **Venue:** NeurIPS 2024.
* **Problem:** Automatically selected concepts can mismatch image content, and concept activations can carry unintended predictive information.
* **Method:** 
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 1 (incorrect grounding)** and **Problem 4 (spatial grounding)**; **Problem 3 (leakage)** and **Problem 6 (evaluation)** through NEC/ANEC.
* **Paper:** https://papers.nips.cc/paper\_files/paper/2024/hash/90043ebd68500f9efe84fedf860a64f3-Abstract-Conference.html
* **Project:** https://lilywenglab.github.io/VLG-CBM/
* **Code:** https://github.com/Trustworthy-ML-Lab/VLG-CBM

## Paper 5 — Measuring Leakage in Concept-Based Methods: An Information Theoretic Approach (2025)

* **Authors:** Mikael Makonnen, Moritz Vandenhirtz, Sonia Laguna, Julia E. Vogt.
* **Publication:** ICLR 2025 XAI4Science workshop / arXiv.
* **Problem:** Leakage is hard to quantify because a concept representation can contain information beyond its stated semantics while preserving high downstream accuracy.
* **Method:** 
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 6 (lack of grounding-related evaluation)** and **Problem 3 (measuring concept leakage)**.
* **Paper:** https://arxiv.org/abs/2504.09459
* **Code:** https://github.com/MMakonnen/leakage-cbm

## Paper 6 — Object-Centric Concept Bottlenecks (2025)

* **Authors:** David Steinmann, Wolfgang Stammer, Antonia Wüst, Kristian Kersting.
* **Venue:** NeurIPS 2025.
* **Problem:** A single global image representation can obscure which object possesses a particular property and can restrict a CBM's ability to reason about multiple objects.
* **Method:** 
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 5 (binding errors; partial architectural response)** and **Problem 4 (object-level localization)**.
* **Paper:** https://proceedings.neurips.cc/paper\_files/paper/2025/file/639d992f819c2b40387d4d5170b8ffd7-Paper-Conference.pdf

## Paper 7 — Spatially Grounded Concept-Based Image Classification (2025)

* **Authors:** Ran Eisenberg, Amit Rozner, Ethan Fetaya, Ofir Lindenbaum.
* **Publication:** arXiv 2025, updated 2026.
* **Problem:** Many CBMs treat concepts as global scores, obscuring how evidence from individual image regions contributes to the final decision.
* **Method:** 
* **Finding / contribution:** 
* **Remaining limitation:** 
* **Primarily addresses:** **Problem 4 (spatial localization)** and **Problem 1 (evidence alignment)**; **Problem 2 (spurious correlations)** and **Problem 6 (faithfulness evaluation)**.
* **Paper:** https://arxiv.org/abs/2510.04180

