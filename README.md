<h1 align="center">Hi, I'm Stuart Flannigan</h1>

<p align="center">
  <strong>Quantum Applications Lead · Computational Physicist · QEC &amp; Fault-Tolerant Quantum Computing</strong>
</p>

<p align="center">
  <a href="https://stuartflannigan.dev/"><img alt="Professional" src="https://img.shields.io/badge/Website-Professional-14B8A6?style=flat-square&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://github.com/SFlann/qec-canvas"><img alt="qec-canvas Python package" src="https://img.shields.io/badge/QEC-qec--canvas-65dbc8?style=flat-square"></a>
  <a href="https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor"><img alt="QEC portfolio" src="https://img.shields.io/badge/QEC-Portfolio-6f42c1?style=flat-square"></a>
  <a href="https://scholar.google.com/citations?user=nRFkgkIAAAAJ&amp;hl=en"><img alt="Google Scholar" src="https://img.shields.io/badge/Google_Scholar-Publications-4285F4?style=flat-square&amp;logo=googlescholar&amp;logoColor=white"></a>
  <a href="https://aws.amazon.com/blogs/quantum-computing/how-strangeworks-is-using-amazon-braket-to-explore-the-aircraft-cargo-loading-problem/"><img alt="AWS Quantum Technologies Blog" src="https://img.shields.io/badge/AWS-Quantum_article-232F3E?style=flat-square&amp;logo=amazonaws&amp;logoColor=white"></a>
  <a href="https://www.linkedin.com/in/stuart-flannigan-03ab7722a/"><img alt="LinkedIn profile" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white"></a>
</p>

I build quantum software that connects physical models, algorithms, and production compute platforms. My background combines a PhD in theoretical quantum physics, 15 peer-reviewed publications, tensor-network and HPC research, and end-to-end ownership of deployed quantum SDKs, services, and hybrid workflows.

I am now applying that experience to quantum error correction and fault-tolerant computing through a substantial independent implementation portfolio.

## What I work on

- **Quantum error correction:** surface codes, lattice surgery, decoding, noisy-circuit modelling, photonic fusion networks, and logical resource estimation.
- **Fault-tolerant workflows:** mapping application problems towards logical circuits, Clifford+T compilation, Pauli-based computation, and physical-resource questions.
- **Quantum software:** production Python services and SDKs, provider integrations, asynchronous job systems, testing, CI/CD, and cloud deployment.
- **Computational physics:** tensor networks, open quantum systems, strongly correlated models, error propagation, and hardware-aware simulation.

## Current role at Commutator Studios

I lead product direction at **Commutator Studios**, shaping the vision, roadmap, and priorities for our products. My role connects technical strategy with user needs, guiding ideas from early exploration through to delivery.

## Experience at Strangeworks

I joined Strangeworks as a **Quantum Algorithm Scientist** in 2022 and progressed to **Senior Quantum Software Engineer** in 2023. My work has combined algorithm development, platform architecture, hands-on implementation, and technical leadership.

- Created the original **QAOA, VQE, and Hybrid Optimize** products, taking them from algorithm design and prototyping through production SDKs, services, testing, documentation, CI/CD, and deployment.
- Became the principal technical owner of the **Optimization platform**, spanning its Python SDK, shared models, orchestration, provider services, asynchronous job lifecycle, billing, results, and deployments.
- Technically owned the **Amazon Braket, Qiskit, Qiskit Runtime, and neutral-atom provider paths**, and created platform integrations for MATLAB, Wolfram Language, and Julia.
- Drove the quantum and optimization direction of **AI-assisted workflows**, including natural-language-to-MIP/QUBO formulation, solver selection, execution, and problem-specific result analysis.
- Designed the best-measured-solution enhancement to **StrangeworksQAOA** and led its hardware benchmark on Rigetti Ankaa-3 through Amazon Braket Hybrid Jobs.

## Featured QEC & fault-tolerant work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SFlann/qec-canvas">
        <img alt="qec-canvas — explainable quantum error correction" src="https://raw.githubusercontent.com/SFlann/qec-canvas/main/docs/images/social-preview.png">
      </a>
      <br>
      <strong><a href="https://github.com/SFlann/qec-canvas">qec-canvas</a></strong> — a typed, tested Python package for defining small stabilizer codes, running reproducible memory experiments, and inspecting batch or sliding-window decoder decisions.
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SFlann/Quantum-Playground">
        <img alt="Quantum Playground — quantum error correction, simulation and compilation" src="https://raw.githubusercontent.com/SFlann/Quantum-Playground/main/assets/social-preview.png">
      </a>
      <br>
      <strong><a href="https://github.com/SFlann/Quantum-Playground">Quantum Playground</a></strong> — a checked notebook laboratory spanning surface-code QEC, tensor-network simulation, decoding, quantum algorithms, and fault-tolerant resource estimation.
    </td>
  </tr>
</table>

These projects serve different purposes. `qec-canvas` packages a focused QEC
vertical slice behind backend-neutral domain models, documented public APIs,
strict typing, continuous integration, and 100% statement and branch coverage.
The [Quantum Playground](https://github.com/SFlann/Quantum-Playground) is the
broader research and learning record from which ideas can be tested before they
become stable software.

The Playground's QEC collection progresses from individual logical qubits to
decoding, lattice surgery, noise modelling, compilation, and
application-level resource studies.

| Area | Selected work |
| --- | --- |
| Surface codes & decoding | [Logical qubit](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/01.Single-logical-qubit) · [Simple decoders](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/02.Simple-Decoder) · [Sliding-window decoding](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/06.Real-Time-Decoder) |
| Logical operations | [Lattice-surgery CNOT](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/05.Lattice-Surgery) · [Non-Clifford circuits & magic states](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/04.Magic-states) |
| Noise & scaling | [Noisy-circuit modelling](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/07.Modelling-Noisy-Circuits) · [Bond-dimension and multi-qubit scaling](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/08.Scaling) |
| FTQC compilation | [Clifford+T and Hamiltonian-simulation studies](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/13.Compilation) |
| Application resources | [Hubbard dynamics, ground-state QPE, and PDE studies](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/14.Algorithms) |
| Photonic architectures | [Six-ring fusion-network simulation](https://github.com/SFlann/Quantum-Playground/tree/main/Playground/Surface-Codes/Itensor/12.Photonic) |

## Selected public work

- **[Aircraft cargo loading with Amazon Braket](https://aws.amazon.com/blogs/quantum-computing/how-strangeworks-is-using-amazon-braket-to-explore-the-aircraft-cargo-loading-problem/)** — I co-authored this AWS Quantum Technologies Blog case study after designing a QAOA enhancement and leading the 26–78-qubit benchmark on Rigetti Ankaa-3 through Braket Hybrid Jobs.
- **[Strangeworks Wolfram Language paclet](https://resources.wolframcloud.com/PacletRepository/resources/Strangeworks/Strangeworks/)** — I created this published Wolfram package for submitting quantum circuits from Mathematica to quantum hardware through the Strangeworks platform. The accompanying [Wolfram Community article](https://community.wolfram.com/groups/-/m/t/3074999) was selected as a Staff Pick.
- **[Research publications](https://scholar.google.com/citations?user=nRFkgkIAAAAJ&hl=en)** — 15 peer-reviewed papers spanning quantum simulation, many-body physics, tensor networks, open quantum systems, topology, error propagation, and practical quantum advantage.

## Selected publications

- [Dynamical structure factor from weak measurements](https://arxiv.org/abs/2409.07030), *Quantum Science and Technology* **10**, 035045 (2025).
- [Practical quantum advantage in quantum simulation](https://doi.org/10.1038/s41586-022-04940-6), *Nature* **607**, 667–676 (2022).
- [Propagation of errors and quantitative quantum simulation with quantum advantage](https://arxiv.org/abs/2204.13644), *Quantum Science and Technology* **7**, 045025 (2022).
- [Many-body quantum state diffusion for non-Markovian dynamics in strongly interacting systems](https://arxiv.org/abs/2108.06224), *Physical Review Letters* **128**, 063601 (2022).

## Toolbox

`Python` · `Julia` · `Wolfram Language` · `Qiskit` · `Amazon Braket` · `Stim` · `ITensors` · `tensor networks` · `HPC` · `Docker` · `AWS` · `CI/CD`

## Let's connect

I am especially interested in QEC/FTQC software, resource estimation, logical-architecture simulation, compilers, decoders, and scientific developer tooling. Explore my [personal website](https://stuartflannigan.dev/) or connect with me on [LinkedIn](https://www.linkedin.com/in/stuart-flannigan-03ab7722a/).
