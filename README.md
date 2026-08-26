# Hi, I'm Ayush

**I build research systems for efficient machine learning and quantum computing.**

I'm a Computer Science and Applied Mathematics student at the University of Maryland, with a minor in Quantum Science and Engineering. I like early-stage problems where the answer is still unclear, the experimental infrastructure still needs to be built, and a careful baseline can change what we think the real bottleneck is.

Across those areas, I keep returning to the same question: when a system is slow or unreliable, what work never needed to happen? That question has led me to focus on better data, strong baselines, and reliable experimental infrastructure before adding more complexity.

## What I'm working on

- **Long-context LLM inference at Rice University:** I am the primary developer of [Prism-Test](https://github.com/RUSH-Intelligence/Prism-Test), an evaluation framework spanning four inference backends, 8+ long-context benchmark suites, and roughly 36 KV-cache compression methods.
- **Quantum algorithms at BosonQ Psi:** I develop and benchmark variational quantum linear solvers for scientific computing, with a focus on reliable optimization, faster experiments, and reproducible evaluation.
- **Code retrieval at UMD:** I study how training-data quality shapes retrieval performance, including cases where better data matters more than changing the model architecture.
- **Geospatial ML with UMD Team AGWA:** I lead the code and data work for a funded, eight-person project building a multi-source pipeline to forecast groundwater salinity across Maryland's Eastern Shore.

Much of my current research code lives in private or organization-owned repositories. Here are the pieces I can share publicly.

## Selected work

### [Variational Quantum Linear Solver via Block Encoding for the Poisson Equation](https://arxiv.org/abs/2608.19655)

An exact block-encoding approach that uses one circuit per cost-function evaluation, where the standard linear-combination-of-unitaries method needs on the order of L squared distinct circuits. We benchmark the solver on Poisson, heat-conduction, and lid-driven cavity problems and examine how classical optimizer choice affects convergence.

I am the second author of five and contributed most of the implementation and experimentation. The manuscript is currently a public preprint under peer review.

### [Prism-Test](https://github.com/RUSH-Intelligence/Prism-Test)

A research framework for evaluating long-context language models and KV-cache compression methods across consistent quality, latency, throughput, memory, and cache-size measurements.

I rebuilt the original prototype and own the benchmark runner, backend adapters, cluster execution, metrics, tests, and documentation.

### [Geometry-Aware Optimization for Quantum Machine Learning](https://github.com/Aysinghal/quantum-manifold-optimization)

A three-person UMD QLearn research project comparing flat-space, projection-based, and Riemannian optimizers across eight variational quantum tasks. We found that simple projected updates frequently matched or outperformed more complex geometry-aware methods, offering the strongest reliability-to-complexity tradeoff while no single optimizer dominated every task.

I led the technical work, built the experimental code, and conducted the primary analysis. Our project was selected for one of the symposium's few oral presentations.

## Technical toolkit

`Python` `PyTorch` `Hugging Face Transformers` `vLLM` `PennyLane` `JAX` `NumPy` `SciPy` `FAISS` `ScaNN` `C++` `Git`

## Let's connect

I'm most interested in efficient ML systems, quantum algorithms, and optimization. If you are working on a problem in that neighborhood, feel free to reach out.

[LinkedIn](https://www.linkedin.com/in/aysinghal) | [Email](mailto:aysinghal06@gmail.com)
