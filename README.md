# Hi, I'm Malik | Experimental Physicist

I am a physicist interested in Quantum Technology and high-energy physics data analysis pipelines, applying advanced machine learning frameworks to track reconstruction and classification challenges.

## Research & Technical Publications

*   **[Technical Note: TrkQual ANN-BDT Analysis](https://github.com)**
    *   *Published via HEPYorkCUNY Collaboration*
    *   Coauthored research analyzing track quality discrimination power, bridging pre-existing Artificial Neural Network (ANN) modules with a Boosted Decision Tree (BDT) framework. The developed BDT architecture retains greater classification power, demonstrates faster training efficiency on unseen datasets, and exhibits enhanced robustness under hardware and parameter stress testing.

## Collaboration Presentations and Technical Talks

*   **[Mu2e Collaboration Software Committee Presentations](https://github.com)** (3 Talks | 2026)
    *   Presented directly to the Mu2e Experiment Working Group. The full slide decks are available via the repository link above.

    *   **Talk 1: Application of Boosted Decision Trees for High-Quality Track Selection in the Mu2e Experiment** – Provided updates to the Mu2e committees on recent developments and classification benchmarks regarding the Boosted Decision Tree (BDT) model.
        *   Official Reference: Mu2e-doc-55327
  
    *   **Talk 2: Integrating an XGBoost Model into the Mu2e Offline Framework: From Python to C++** — Dealt with software translation requirements. While the BDT model is developed in Python, the core Mu2e offline software framework is compiled in C++. This talk detailed the engineering pipeline used to translate Python model parameters directly into native C++ structures at readout time.
        *   *Workflow:* Python Model Training -> C++ Conversion via m2cgen -> Execution of Conversion Script -> Integration into the Mu2e Offline Pipeline.
  
    *   **Talk 3: Testing the BDT Model’s Ability to Classify Tracks Across Perturbed Datasets** — Evaluated model stability under data stress testing. This study focused specifically on momentum error (momerr) variables to determine operational boundaries and ensure classifier performance remains stable across simulated dataset variations.

## Featured Machine Learning Workspaces

*   **[Mu2e_XGboost_Project](https://github.com)**
    *   A complete machine learning pipeline engineered to run parallel to ANN model that has been deployed in the offline version of the Mu2e experiment.
    *   Built utilizing `XGBoost`, `TensorFlow`, `PyTorch`, and `ONNX` configurations optimized for multi-threaded processing.


## Technical Toolkit

*   **Languages:** Python, LaTeX (for academic reporting)
*   **Machine Learning:** XGBoost (BDT), TensorFlow, PyTorch, Scikit-Learn, ONNX Runtime
*   **Physics Frameworks:** CERN ROOT 
