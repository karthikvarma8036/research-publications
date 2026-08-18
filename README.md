# research-publications


## Research Portfolio

A collection of research implementations and experimental studies spanning efficient LLMs, dynamic graph learning, robust representation learning, graph neural networks, and theoretical machine learning.

---

## Research Projects

### 1. Megalodon: Efficient LLM Pretraining and Inference with Unlimited Context Length

This work explores efficient Transformer architectures for large language models, focusing on scalable pretraining and inference over very long contexts. It investigates architectural improvements that reduce computational overhead while maintaining strong language modeling performance, with emphasis on efficient sequence processing, long-context modeling, and practical LLM scalability.

**Paper:** [Megalodon — Official NeurIPS 2024 Publication](https://proceedings.neurips.cc/paper_files/paper/2024/hash/840abfadd04c967feaa2a49aba94a32d-Abstract-Conference.html)

### 2. Improving Generalization of Dynamic Graph Learning via Environment Prompt

This work investigates dynamic graph representation learning in evolving environments where graph structures and data distributions can change over time. It explores environment-aware prompting and robust representation learning techniques to improve generalization across different temporal environments and distribution shifts in dynamic networks.

**Paper:** [Improving Generalization of Dynamic Graph Learning via Environment Prompt](https://proceedings.neurips.cc/paper_files/paper/2024/hash/81c565e605161fcf25d08aa230431eba-Abstract-Conference.html)


### 3. Class Distribution Shifts in Zero-Shot Learning: Learning Robust Representations

This work studies robust representation learning for zero-shot classification under changing class distributions. It focuses on learning representations that remain effective when the relationship between training and testing class distributions differs, improving generalization to unseen classes and challenging distribution-shift scenarios.

**Paper:** [Class Distribution Shifts in Zero-Shot Learning: Learning Robust Representations](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a2753c86334b9b4a21dd9d8e191a8bbf-Abstract-Conference.html)

### 4. Non-convolutional Graph Neural Networks

This work explores graph representation learning using random walks and recurrent memory instead of conventional graph convolutions. It investigates how structural and semantic information can be captured through learned random-walk trajectories while addressing limitations of traditional GNNs such as over-smoothing, over-squashing, and scalability constraints.
**Paper:** [Non-convolutional Graph Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2024/hash/397271e11322fae8ba7f827c50ca8d9b-Abstract-Conference.html)


### 5. Learning a Single Neuron Robustly to Distributional Shifts and Adversarial Label Noise

This work investigates theoretically grounded learning under distributional shifts and adversarial label noise. It develops robust learning approaches designed to maintain reliable predictions under challenging data conditions and studies formal guarantees for learning performance in the presence of distribution changes and corrupted labels.
**Paper:** [Learning a Single Neuron Robustly to Distributional Shifts and Adversarial Label Noise](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7c8c0db90a14c7a2db9475e52dc343a9-Abstract-Conference.html)


### 6. Towards Fully FP8 GEMM LLM Training at Scale
This work investigates fully FP8-based training for large-scale Transformer language models, focusing on improving computational and memory efficiency during LLM optimization. It explores numerical stability challenges associated with low-precision matrix multiplication and develops techniques for maintaining model accuracy while enabling more efficient large-scale training.
**Paper:** [Towards Fully FP8 GEMM LLM Training at Scale — NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/file/51ffd0668534ac8db7b4d89fe21d5486-Paper-Conference.pdf)


### 7. MiNT: Multi-Network Transfer Benchmark for Temporal Graph Learning

This work studies transferable representation learning for temporal graphs across multiple evolving networks. It introduces a multi-network transfer setting for evaluating how temporal graph neural networks can learn reusable representations across different graph structures and temporal dynamics, with emphasis on scalability, cross-network generalization, and zero-shot transfer.
**Paper:** [MiNT: Multi-Network Transfer Benchmark for Temporal Graph Learning — NeurIPS 2025](https://papers.nips.cc/paper_files/paper/2025/hash/c5548168cb7324f714365a971dfe76d1-Abstract-Datasets_and_Benchmarks_Track.html)

### 8. Stable Fair Graph Representation Learning with Lipschitz Constraint
This work investigates stable and fair graph representation learning using Lipschitz-constrained models. It focuses on controlling the sensitivity of learned graph representations while maintaining predictive performance and fairness, combining theoretical stability analysis with empirical evaluation across graph learning tasks.
**Paper:** [Stable Fair Graph Representation Learning with Lipschitz Constraint — ICML 2025](https://proceedings.mlr.press/v267/chen25bs.html)

### 9. D³: Dynamic Directional Graph-Constrained Data Scheduling for LLM Training
This work explores graph-aware data scheduling for large language model training by modeling relationships between training examples as a dynamic directional graph. It investigates how graph-constrained scheduling can improve the ordering and selection of training data, with the goal of making LLM optimization more efficient and effective.
**Paper:** [D³: Dynamic Directional Graph-Constrained Data Scheduling for LLM Training — ICML 2026](https://www.microsoft.com/en-us/research/publication/d3-dynamic-directional-graph-constrained-data-scheduling-for-llm-training-2/)

### 10. Learning Long Range Spatio-Temporal Representations over Continuous Time Dynamic Graphs with State Space Models

This work investigates long-range spatio-temporal representation learning on continuous-time dynamic graphs using state-space models. It focuses on efficiently capturing long-term temporal dependencies and evolving graph structures while maintaining expressive representations for dynamic network prediction and analysis.
**Paper:** [Learning Long Range Spatio-Temporal Representations over Continuous Time Dynamic Graphs with State Space Models — ICML 2026](https://arxiv.org/abs/2606.04672)

---

## Research Focus

- Efficient LLM architectures and Transformer optimization
- Dynamic graph representation learning
- Robust learning under distribution shifts
- Random-walk-based graph representation learning
- Zero-shot and low-resource learning
- Theoretical and mathematically grounded machine learning

This research portfolio spans efficient large language model training, Transformer optimization, dynamic and temporal graph representation learning, robust and fair machine learning, random-walk-based graph neural networks, distribution-shift adaptation, and theoretically grounded learning. The projects explore scalable and generalizable approaches for learning from evolving, structured, and imperfect data, combining algorithmic development, mathematical analysis, model implementation, and empirical evaluation across language and graph-based learning systems. 

---

## Repository Contents

- Research implementations
- Experimental evaluations
- Model architectures and training pipelines
- Mathematical formulations and theoretical analysis
- Dataset preparation and preprocessing
- Evaluation and benchmarking
- Reproducibility resources

---

## Technologies

Python · PyTorch · Transformers · Graph Neural Networks · NumPy · SciPy · NetworkX · Jupyter

---

## References

Links to the original publications and official conference proceedings for each research project.

---




## Disclaimer

This repository is intended for research and educational purposes and contains implementations, experiments, and analyses related to the referenced research works.
