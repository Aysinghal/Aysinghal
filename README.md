# Hi, I'm Ayush

**I build research systems for efficient machine learning and quantum computing.**

I'm a Computer Science and Applied Mathematics student at the University of Maryland, with a minor in Quantum Science and Engineering. I like early-stage problems where the answer is still unclear, the experimental infrastructure still needs to be built, and a careful baseline can change what we think the real bottleneck is.

Across those areas, I keep returning to the same question: when a system is slow or unreliable, what work never needed to happen? That question has led me to focus on better data, strong baselines, and reliable experimental infrastructure before adding more complexity.

## What I'm working on

- **Long-context LLM inference at Rice University:** I am the primary developer of [Prism-Test](https://github.com/RUSH-Intelligence/Prism-test), an evaluation framework spanning four inference backends, 8+ long-context benchmark suites, and roughly 36 KV-cache compression methods.
- **Quantum algorithms at BosonQ Psi:** I develop and benchmark variational quantum linear solvers for scientific computing, with a focus on reliable optimization, faster experiments, and reproducible evaluation.
- **Code retrieval at UMD:** I study how training-data quality shapes retrieval performance, including cases where better data matters more than changing the model architecture.
- **Geospatial ML with UMD Team AGWA:** I lead the code and data work for a funded, eight-person project building a multi-source pipeline to forecast groundwater salinity across Maryland's Eastern Shore.

## Selected work

### [Variational Quantum Linear Solver via Block Encoding for the Poisson Equation](https://arxiv.org/abs/2608.19655)

An exact block-encoding approach that uses one circuit per cost-function evaluation, where the standard linear-combination-of-unitaries method needs on the order of L squared distinct circuits. We benchmark the solver on Poisson, heat-conduction, and lid-driven cavity problems and examine how classical optimizer choice affects convergence.

I am the second author of five and contributed most of the implementation and experimentation. The manuscript is currently a public preprint under peer review.

### [Prism-Test](https://github.com/RUSH-Intelligence/Prism-test)

A research framework for evaluating long-context language models and KV-cache compression methods across consistent quality, latency, throughput, memory, and cache-size measurements.

I rebuilt the original prototype and own the benchmark runner, backend adapters, cluster execution, metrics, tests, and documentation.

## A few results that shaped how I work

- Reduced a diffusion model's training dataset by up to 40% while keeping downstream evaluation within 1% of the full-data baseline.
- Found across eight variational quantum tasks that simple projected updates frequently matched or beat more elaborate geometry-aware optimizers.
- Built a multi-agent Critic-Refiner system whose generated educational content scored up to 21% higher than an existing production pipeline during evaluation.

## Technical toolkit

`Python` `PyTorch` `Hugging Face Transformers` `vLLM` `PennyLane` `JAX` `NumPy` `SciPy` `FAISS` `ScaNN` `C++` `Git`

## Let's connect

I'm most interested in efficient ML systems, quantum algorithms, and optimization. If you are working on a problem in that neighborhood, feel free to reach out.

[LinkedIn](https://www.linkedin.com/in/aysinghal) | [Email](mailto:aysinghal06@gmail.com)
