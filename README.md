## Ray Huang

Division of Computational and Data Sciences, Department of Mathematics, National Central University, Taiwan, with a second major in Communication Engineering. Research is what I actively push on. The projects below are what happens when something catches my interest; they, and the contests further down, are closer to how I relax than to work.

### What I am working on

**Molecular communication.**
Instead of modulating a wave you release particles into a fluid and read where they land. With no drift in the medium that landing position is Cauchy — a noise model with no mean and no variance, where most of the usual toolbox quietly stops applying. There are a lot of interesting questions in there.

**Some water sort problems.**
Take n colours with h balls of each, pour them into n full bottles, and hand yourself k spare empty ones. A ball moves only off the top of a bottle, and only onto an empty bottle or onto its own colour. Plenty of questions live in here too: whether solvability can be decided in polynomial time, how many spare bottles you actually need, and so on.

<img src="./watersort.svg" width="440" alt="A water sort puzzle: three bottles of mixed colours and one spare empty bottle, moved step by step until each bottle holds a single colour." />

Both are ongoing and unpublished.

### Things I have built

The fun is usually in the layer underneath, so it tends to get written rather than imported — a language of my own, a renderer, a wire protocol.

- **[asymptote](https://github.com/rayhuang2006/asymptote)** — VS Code extension for competitive programmers, on the Marketplace. Parses C++ into a tree-sitter AST and derives time complexity from loop nesting and recursion depth rather than pattern-matching, and fetches Codeforces samples to run in the editor. TypeScript.
- **[Loophole](https://github.com/rayhuang2006/Loophole)** — a language for wishing against a genie, and the compiler that decides whether your wish was legal. Wishes are written in one file and the genie's own rules in another; the compiler charges the toll, runs the arithmetic on a narrow unsigned counter, and reports which invariant you broke on the way. Single-file C++17, no dependencies, with a [browser playground](https://rayhuang2006.github.io/Loophole/) and [editor support](https://github.com/rayhuang2006/loophole-vscode) whose diagnostics come from the compiler itself compiled to WebAssembly.
- **[Aceey](https://github.com/rayhuang2006/Aceey)** — desktop IDE for contests. Tauri v2 and a Rust backend that compiles, runs and judges C++ locally; its debug agent asks Socratic questions instead of handing over the fix, rendered under the offending line through Monaco's zone widgets.
- **[arachne](https://github.com/rayhuang2006/arachne)** — a Chrome extension that lets idle tabs fall into disrepair. The cobwebs are a mass-spring system with real gravity and sag, drawn procedurally with no images and no libraries; you can sweep the dust and tear the webs, and the whole thing sleeps to near-zero CPU once it settles.
- **[CPyGfx](https://github.com/rayhuang2006/CPyGfx)** + **[SteadyHand](https://github.com/rayhuang2006/SteadyHand)** — a C/SDL rendering library driven from Python through ctypes, and the networked game on top of it, speaking its own binary protocol over TCP against a flat file store written from scratch.

### Competitive Programming

- **ICPC Asia Taiwan Online Programming Contest, 2026** — 11th overall, and the highest-placed team from NCU, as woowoowoo.
- **NCPC, 2025** — reached the final of Taiwan's national collegiate contest with the same team.
- **[Codeforces](https://codeforces.com/profile/Weeeeeeeeeeeee00)** — Expert. My main platform, and where most of the C++ above got its habits.

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
