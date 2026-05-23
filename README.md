# Dylan Sutton Chavez

**IEEE WCCI 2026 Peer Reviewer · ML Researcher · Systems Developer @ Amazon Audible**

---

Systems Developer at Amazon Audible, peer reviewer for IEEE WCCI 2026, and independent ML researcher with work currently under journal review.

I work on resource-constrained machine learning, compiler design, and production systems engineering. From migrating Player Services across AWS regions to building a single-pass SSA compiler in Rust, and proposing uncertainty-aware classifiers for TinyML deployment validated on NASA IMS and SemEval.

Most of what I build is small, fast, and deterministic. Open to collaborations on tiny compilers, selective classification, and embedded ML.

---

### Research

**Revisiting Rosenblatt Perceptron: Robust High-Entropy Classification via Uncertainty Margins**
First-author paper introducing an uncertainty-aware linear classifier with adaptive abstention margin for TinyML deployment. ~1 KB memory footprint, 9 ms latency, benchmarked against Bonsai, FastGRNN, ProtoNN, and LSTM.

- Paper source: [uncertainty-simple-perceptron.tex](https://github.com/dylan-sutton-chavez/uncertainty-simple-perceptron/blob/main/uncertainty-simple-perceptron.tex)
- Implementation: [uncertainty-simple-perceptron](https://github.com/dylan-sutton-chavez/uncertainty-simple-perceptron)

### Systems

**Edge Python** — Single-pass SSA compiler and threaded-code VM for a sandboxed Python subset. NaN-boxed values, dual inline caching, super-instruction fusion, pure-function memoization, mark-sweep GC; classes with inheritance and dunder protocol, async/await, pattern matching, and packages.json imports. around 170 KB WebAssembly module.

- Website: [edgepython.com](https://edgepython.com/)
- Live demo: [demo.edgepython.com](https://demo.edgepython.com/)
- Source: [edge-python](https://github.com/dylan-sutton-chavez/edge-python)

**Edge Python Official Packages:**

- Host Packages ([repository](https://github.com/dylan-sutton-chavez/edge-python-host)): Official packages that embed host-side bridge code (e.g., JS) and expose it to Python through the capability protocol. Includes modules like requests for networking and DOM bindings for browser interaction.
- Standard Packages ([repository](https://github.com/dylan-sutton-chavez/edge-python-std)): Official .wasm standard-library packages, where each capability is a Rust crate compiled to wasm32 against the wasm-pdk ABI. Hosts load the resulting .wasm over the standard plugin contract, no custom embedder, no Rust on the consumer side.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake.svg" />
</picture>
