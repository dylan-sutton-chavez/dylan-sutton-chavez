# Dylan Sutton Chavez

**Systems Developer @ Amazon Audible**

---

I work on compiler design and production systems. At Audible I move services across AWS regions and build their throttling, alarms and load tests. On my own I build interpreter, a Rust SDK for language runtimes (>270 stars, externally sponsored).

Most of what I build is small, fast and deterministic. Open to collaborations on tiny compilers, interpreters and WebAssembly runtimes.

---

### Systems

**interpreter** is a Rust SDK for building language runtimes. You bring a token table, a few rules and the natives your programs call. It brings the lexer, a single-pass parser that writes SSA bytecode with no AST, and a tiered register VM with NaN-boxed values, inline caches, a mark-sweep GC and snapshots. A runtime built on it is one WebAssembly module that runs in browsers, JavaScript runtimes, the CLI and your own Rust program, sandboxed by default: no file, network or environment unless its host grants it. Its example language is Lox, which passes the book's 241 tests.

- Source: [interpreter](https://github.com/dylan-sutton-chavez/interpreter)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/dylan-sutton-chavez/dylan-sutton-chavez/output/github-snake.svg" />
</picture>
