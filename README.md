# SITROZYI

**Systems & Developer Tooling Engineer**  
Specializing in AST-level context compression for LLMs, Model Context Protocol (MCP) tooling, and zero-dependency real-time engines.

[Portfolio](https://sitrozyi.com/) · [X (Twitter)](https://x.com/Sitrozyi) · [Kaggle](https://www.kaggle.com/Sitrozyi)

---

## 🛠️ Featured Artifacts

### 1. `repomix-semantic-compressor` *(Private Beta · npm release coming soon)*
> **AST-powered semantic context optimizer & MCP Server for Repomix.**  
> Prunes TypeScript/JavaScript implementation bodies via AST traversal while strictly preserving exported type contracts, function signatures, and class hierarchies for LLM context windows.

```text
Source Code ──► [@babel/parser] ──► AST Traversal ──► Minimized Schema ──► MCP Context
                (~80% token reduction while preserving semantic logic)
```

```bash
$ repomix-compress
ℹ repomix-output not found. Running "npx repomix" automatically... (done in 1.8s)

✔ Optimized 16 files in 224ms

  LLM Tokens ~:  104,023 → 20,830  (-80.0%)
  File Size:     386.0 kB →  77.3 kB (-80.0%)
  Est. Savings:  ~$0.2496 / prompt (Claude 3.5 Sonnet / GPT-4o input rate)
  Output File:   repomix-optimized.md
```
<sub>* Benchmark measured using cl100k_base tokenizer across production TypeScript codebases</sub>

* **Stack:** `Node.js` · `@babel/parser` · `@babel/traverse` · `Model Context Protocol (MCP SDK)` · `Vitest`

---

### 2. [Bug Clash](https://bug-clash-online.sitrozyi.workers.dev/) *(Live / Playable)*
> **Zero-dependency real-time tactical card battle engine.**  
> Built from scratch with a custom 60 FPS HTML5 Canvas 2D render pipeline, deterministic client-side state machine, and P2P mesh synchronization via WebRTC DataChannels.

* **Stack:** `Vanilla JavaScript` · `HTML5 Canvas 2D` · `PeerJS (WebRTC DataChannel)` · `Web Audio API`

---

## 🔬 Technical Focus & Philosophy

* **AST & Compiler Tooling:** Abstract Syntax Tree parsing, type signature extraction, and MCP server implementations for LLM context optimization.
* **Real-Time Systems & Networking:** Frameworkless Canvas 2D render loops, WebRTC P2P state synchronization, and procedural Web Audio synthesis.
* **Zero-Dependency Mindset:** Deep understanding of runtime internals and standard web APIs over unnecessary third-party abstractions.

---

<details>
<summary>🌿 <b>Offline Craftsmanship: 65cm Custom Moss Terrarium</b></summary>
<br>
<blockquote><i>"High attention to detail, both in software architectures and closed biological ecosystems."</i></blockquote>

<table>
  <tr>
    <td width="33%"><img src="images/moss1.jpg" alt="Terrarium View 1"></td>
    <td width="33%"><img src="images/moss2.jpg" alt="Terrarium View 2"></td>
    <td width="33%"><img src="images/moss3.jpg" alt="Terrarium View 3"></td>
  </tr>
</table>

</details>
