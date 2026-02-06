# Research Samples: Geometric Analysis & AI

This repository hosts supplementary research notes and case studies accompanying my application for the **Research Scientist (Mathematical Sciences)** role at OpenAI.

These documents illustrate my work at the intersection of rigorous Geometric Analysis and modern AI research, focusing on two key areas:
1.  **Auditing** frontier models for high-level geometric reasoning errors.
2.  **Deriving** first-principles geometric analysis of optimization algorithms used in Large Language Models.

## Files

### 1. [Remarks on Geometric Optimization (PDF)](./Remarks_on_Geometric_Optimization.pdf)
**Topic:** Foundations of Riemannian Adaptive Optimization
* **Context:** Standard adaptive optimizers (ADAM, AMSGRAD) rely on coordinate-wise scaling that implicitly assumes a Euclidean geometry. This assumption fails in curvature-constrained settings like **RMS-Normalization**, which projects activations onto an ellipsoid.
* **Contribution:** I unified the derivation of Riemannian adaptive optimizers on spheres and ellipsoids from first principles.
* **Key Finding:** My analysis further clarifies the ways in which applying standard coordinate-wise scaling to anisotropic manifolds (ellipsoids) introduce **nonlinear geometric distortions** into the descent direction. These artifacts (effectively "ghost" radial components) alter the effective learning rate in ways that standard Euclidean analysis fails to capture.

### 2. [Case Studies in AI-Assisted Analysis (PDF)](./Case_Studies_AI_Analysis.pdf)
**Topic:** Auditing Frontier Models for Mathematical Reasoning
* **Context:** A log of specific experiments (Oct 2025 – Jan 2026) testing the capability of frontier models to assist in high-level proofs in geometric analysis.
* **Key Insight:** Current models appear to function closer to a young research assistant, capable of symbolic manipulation but prone to fundamental conceptual errors. 
* **Specific Failure Modes:** I identified an inablility of models to understand subtle concepts in differential geometry, a failure to switch contexts between the "local" and "global" parts of proofs, and a tendency for circular reasoning in order to force an argument to work.

## License
The written content and research notes in this repository are licensed under the **Creative Commons Attribution 4.0 International License (CC-BY 4.0)**.

## Contact
**Daniel Weser, Ph.D.**
* [daniel.j.weser@gmail.com](mailto:daniel.j.weser@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/danielweser/)
