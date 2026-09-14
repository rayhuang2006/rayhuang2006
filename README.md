## Ray Huang

Mathematics (Computation and Data Science) at National Central University, Taiwan, with a second major in Communication Engineering. I work on probability models and signal detection, and I write a lot of C++.

### What I am working on

**Heavy tails, and the densities you cannot write down.**
My research is in molecular communication — signalling by releasing particles into a medium and reading when and where they arrive. The distributions that fall out of it are heavy-tailed, which in practice means a clean characteristic function, no elementary density, and a detection theory that inherits that silence everywhere it matters. I am interested in how much of it can be recovered analytically instead of numerically.

**A combinatorial constant whose value nobody knows.**
Take n colours with h balls of each, pour them into n full bottles, and hand yourself k spare empty ones. A ball moves only off the top of a bottle, and only onto an empty bottle or onto its own colour. How small can k be and still guarantee that *every* starting position can be sorted? The quantity was posed as an open problem in 2022 and its value is still unknown: the published upper and lower bounds are far apart, and for short bottles the lower one degenerates into saying nothing at all. Two directions interest me. One is the bounds themselves — moving either side of k, which comes down to understanding which configurations deadlock and what forces it. The other is complexity: whether solvability can be decided in polynomial time is settled only in parts of the parameter space, and the fixed-height case is not one of them. That it is a family of questions rather than a single one is most of the appeal.

<img src="./watersort.svg" width="440" alt="A water sort puzzle: three bottles of mixed colours and one spare empty bottle, moved step by step until each bottle holds a single colour." />

Both are ongoing and unpublished.

### Things I have built

Mostly tools I wanted to exist, plus a long-running habit of writing the layer underneath instead of importing it — a language of my own, a renderer, a wire protocol — because reading how they work never stuck the way building one did.

- **[asymptote](https://github.com/rayhuang2006/asymptote)** — VS Code extension for competitive programmers, on the Marketplace. Parses C++ into a tree-sitter AST and derives time complexity from loop nesting and recursion depth rather than pattern-matching, and fetches Codeforces samples to run in the editor. TypeScript.
- **[Loophole](https://github.com/rayhuang2006/Loophole)** — a language for wishing against a genie, and the compiler that decides whether your wish was legal. Wishes are written in one file and the genie's own rules in another; the compiler charges the toll, runs the arithmetic on a narrow unsigned counter, and reports which invariant you broke on the way. Single-file C++17, no dependencies, with a [browser playground](https://rayhuang2006.github.io/Loophole/) and [editor support](https://github.com/rayhuang2006/loophole-vscode) whose diagnostics come from the compiler itself compiled to WebAssembly.
- **[Aceey](https://github.com/rayhuang2006/Aceey)** — desktop IDE for contests. Tauri v2 and a Rust backend that compiles, runs and judges C++ locally; its debug agent asks Socratic questions instead of handing over the fix, rendered under the offending line through Monaco's zone widgets.
- **[arachne](https://github.com/rayhuang2006/arachne)** — a Chrome extension that lets idle tabs fall into disrepair. The cobwebs are a mass-spring system with real gravity and sag, drawn procedurally with no images and no libraries; you can sweep the dust and tear the webs, and the whole thing sleeps to near-zero CPU once it settles.
- **[CPyGfx](https://github.com/rayhuang2006/CPyGfx)** + **[SteadyHand](https://github.com/rayhuang2006/SteadyHand)** — a C/SDL rendering library driven from Python through ctypes, and the networked game on top of it, speaking its own binary protocol over TCP against a flat file store written from scratch.

### Competitive Programming

Codeforces Expert — [Weeeeeeeeeeeee00](https://codeforces.com/profile/Weeeeeeeeeeeee00). C++.

### Tools

C++ · Python · TypeScript · Rust · Swift · NumPy/SciPy · Lean 4 · LLVM · Tauri · macOS

### Statistics

<a href="https://github.com/rayhuang2006">
  <img align="center" width="49%" src="./acti_comm.svg" />
</a>
<a href="https://github.com/rayhuang2006">
  <img align="center" width="49%" src="./repositories.svg" />
</a>
<a href="https://github.com/rayhuang2006">
  <img align="center" width="49%" src="./iso_calender.svg" />
</a>
<a href="https://github.com/rayhuang2006">
  <img align="center" width="49%" src="./issue_pr_lang.svg" />
</a>
