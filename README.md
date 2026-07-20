# 👋 Hi, I'm Malik | Experimental Physicist

I am a physicist interested in Quantum Technology and high-energy physics data analysis pipelines, applying advanced machine learning frameworks to track reconstruction and classification challenges.

## Research & Technical Publications

*   **[Technical Note: TrkQual ANN-BDT Analysis](https://github.com)**
    *   *Published via HEPYorkCUNY Collaboration*
    *   Coauthored research analyzing tracking quality configurations, bridging pre-existing Artificial Neural Network (ANN) modules with multi-threaded Boosted Decision Tree (BDT) verification frameworks.

## Collaboration Presentations & Technical Talks

*   **[Mu2e Collaboration Software Committee Presentations](https://github.com/Malik-Farouh/Mu2e_XGboost_Project/tree/main/presentations)** (3 Talks | 2026)
    *   *Delivered directly to the official Mu2e Experiment Working Group. Click the link above to access the full slide decks.*
  
**Talk 1: Application of Boosted Decision Trees for High-Quality Track Selection in the Mu2e Experiment** — Updating Mu2e committees on the recent developments and classification benchmarks of the Boosted Decision Tree (BDT) model. Reference: Mu2e-doc-55327 (https://github.com)

**Talk 2: Integrating an XGBoost Model into the Mu2e Offline Framework: From Python to C++** — The BDT model is developed using Python as our main language, but the core Mu2e software is written in C++. We engineered a pipeline to translate the BDT model parameters directly into native C++ structures at readout time.

  *  **Workflow:** Train XGBoost Model in Python $\rightarrow$ Convert to C++ with `m2cgen` $\rightarrow$ Run Conversion Script $\rightarrow$ Integrate into Mu2e Offline Pipeline.
  
**Talk 3: Testing the BDT Model’s Ability to Classify Tracks Across Perturbed Datasets** — This study focuses on momentum error (`momerr`) variables to test the BDT's operational boundaries and ensure classifier stability remains robust across distinct simulated dataset variations.


## Featured Machine Learning Workspaces

*   **[Mu2e_XGboost_Project](https://github.com)**
    *   A complete machine learning pipeline engineered to run parallel to ANN model that has been deployed in the offline version of the Mu2e experiment.
    *   Built utilizing `XGBoost`, `TensorFlow`, `PyTorch`, and `ONNX` configurations optimized for multi-threaded processing.


## Technical Toolkit

*   **Languages:** Python, LaTeX (for academic reporting)
*   **Machine Learning:** XGBoost (BDT), TensorFlow, PyTorch, Scikit-Learn, ONNX Runtime
*   **Physics Frameworks:** CERN ROOT 
