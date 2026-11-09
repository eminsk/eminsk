### Hi there, I'm M_N_Nik 👋

**Systems Engineer & Compiler Developer** with an engineering background spanning low-level architectures (x86/x64 Assembly, Win32 API, C) to modern high-performance Python runtime engineering, AOT compilation, and native SIMD acceleration.

[![Developer Portal](https://img.shields.io/badge/Developer_Portal-eminsk.github.io-00F0FF?style=for-the-badge&logo=google-chrome&logoColor=black)](https://eminsk.github.io/)
[![Conda Downloads](https://img.shields.io/badge/Conda--Downloads-22k%2B-green?style=for-the-badge&logo=anaconda&logoColor=white)](https://anaconda.org/m_n_nik)
[![Telegram](https://img.shields.io/badge/Telegram-@charter2029-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/charter2029)
[![Email](https://img.shields.io/badge/Email-M__N__Nik@yahoo.com-6001D2?style=for-the-badge&logo=yahoo&logoColor=white)](mailto:M_N_Nik@yahoo.com)

---

### 🧭 Engineering Philosophy & Background

- **Decades of Systems Craft:** Writing software since the early 2000s, grounded in memory management, CPU microarchitecture, hardware registers, and native Win32/POSIX runtime behavior.
- **Hardware-Aware Performance:** Bridging high-level productivity with bare-metal speed — developing native AOT compilers, custom SIMD (SSE2/AVX2/NEON) vector kernels, FASM x64 assembly engines, and zero-copy C extensions.
- **Architectural Discipline:** Strict typing (`mypy`), modern tooling (`uv`, `ruff`), reproducible packaging, hardware concurrency, free-threaded Python (No-GIL PEP 703), and native ABI calling conventions.

---

### 🛠 Tech Stack & Core Competencies

- **Compilers & Low-Level Systems:** Python AST to pure x86_64 FASM AOT Compiler, Peephole Optimization, Calling Conventions (Microsoft x64 ABI / System V ABI, 16-byte stack alignment, shadow space), CPU register allocation, hardware atomic primitives (`lock add/sub`).
- **Languages:** Python (3.8–3.16, Free-Threaded No-GIL 3.13t–3.16t, PyPy), x86/x64 Assembly (Flat Assembler - FASM / FASMG), C99 / Win32 API
- **High-Performance Computing (HPC) & SIMD:** SIMD Vectorization (SSE2/AVX2/FMA/ARM NEON), BLAS / GEMM matrix multiplication micro-kernels, SIMD JSON parsing, Vector Search & Embeddings
- **Concurrency & Multithreading:** True No-GIL Native OS Threads (`CreateThread`), Free-Threaded Multi-Core (PEP 703), Lock-free & Atomic synchronization, Asyncio, Inter-Process Communication (IPC)
- **AI Systems & Runtime Protocols:** Model Context Protocol (MCP) JSON-RPC 2.0 Servers, Agent Trajectory JIT Compilation, Semantic Vector Search
- **Packaging & Infrastructure:** uv, ruff, mypy, pytest, Conda-Forge / Rattler-Build, Debian/Ubuntu APT PPA, GitHub Actions CI/CD pipelines

---

### 🚀 Featured Projects

- **[pureapk](https://github.com/eminsk/pyapk)** (pyapk) — Zero-dependency pure Python Android APK engine with Android 15 16KB ELF page alignment (tag `0xd935`), APK v1/v2/v3 signatures, multi-store packaging (APK, Google Play AAB, iOS IPA stub, Windows 11 MSIX), in-place APK modification, and Android wheel extraction without Java or Android Studio. Published on [PyPI](https://pypi.org/project/pureapk/) (`pureapk v1.0.2`) and available on Debian/Ubuntu APT PPA (`python3-pureapk`).
- **[pyfasm](https://github.com/eminsk/pyfasm)** — Universal Native No-GIL (3.13t–3.16t) & PyPy to pure x86_64 Flat Assembler (FASM) Native Compiler. Translates Python AST directly into self-contained standalone PE+ (`.exe`, `.dll`), ELF64, and Mach-O binaries (~9 KB) with zero virtual machine and zero runtime overhead. Features true multi-threaded native concurrency (`CreateThread` with hardware atomics), SSE scalar/vector floating point, SIMD-accelerated JSON parser, and native Win32 GUI engine. Published on [PyPI](https://pypi.org/project/pyfasm64/) (`pyfasm64`) and announced on the [Flat Assembler Board](https://board.flatassembler.net/topic.php?t=24431).
- **[fasm-modern-sdk](https://github.com/eminsk/fasm-modern-sdk)** — Modernized SDK and header toolchain for Flat Assembler (FASM v1.73 / FASMG) featuring 64-bit Windows equates, official calling conventions, and zero-configuration bindings.
- **[agentjit](https://github.com/eminsk/agentjit)** — Just-In-Time Compiler for AI Agent Trajectories. Compiles multi-step LLM workflows into 0.08ms deterministic Python code with zero token cost. Features speculative guards, automatic bailout runtime, free-threaded (No-GIL PEP 703) support, and Native MCP Server (`agentjit-mcp`). Featured as the #1 Top Story in [The Daily Diff](https://tdd.cat/2026-09-13/) (9/10 Depth & Utility Score). Published on [PyPI](https://pypi.org/project/agentjit/) and [conda-forge](https://anaconda.org/conda-forge/agentjit).
- **[nanovector](https://github.com/eminsk/nanovector)** — The SQLite of Vector Search & Episodic Memory for AI Agents in ~120KB. Zero dependencies, instant 0.2ms cold start, pure C99 with AVX2+FMA, ARM NEON, hand-crafted FASM x64 assembly kernels, and Native MCP Server (`nanovector-mcp`). Over 7,900+ downloads on Conda. Published on [PyPI](https://pypi.org/project/nanovector/) and [conda-forge](https://anaconda.org/conda-forge/nanovector).
- **[nanogemm](https://github.com/eminsk/nanogemm)** — Minimalist, bare-metal AVX2+FMA & ARM NEON matrix multiplication engine in ~100KB for Python, outperforming NumPy by up to 2.8x on CPU for edge neural network inference, and Native MCP Server (`nanogemm-mcp`). Over 9,800+ downloads on Conda. Featured in [The Daily Diff](https://tdd.cat/2026-09-07/) (9/10 Depth Score), trending on GitHub (Deep Learning), and published on [PyPI](https://pypi.org/project/nanogemm/) and [conda-forge](https://anaconda.org/conda-forge/nanogemm).
- **[nanorecall](https://github.com/eminsk/nanorecall)** — 100% Private, Zero-Cloud, Bare-Metal Desktop Memory & Screen Search Engine in <200KB. Runs on standard CPUs with zero telemetry, automatic privacy shielding for password managers, sub-millisecond semantic search via NanoVector, and Native MCP Server (`nanorecall-mcp`). Published on [PyPI](https://pypi.org/project/nanorecall/) and [conda-forge](https://anaconda.org/conda-forge/nanorecall).
- **[yfinance-ta-patterns](https://github.com/eminsk/yfinance-ta-patterns)** — Institutional candlestick pattern scanner (all 61 TA-Lib patterns with pure-Python fallback), unbiased next-open backtester, AI Confluence Scorer, Asset Economic Calendar, and Native MCP Server (`yfinance-ta-mcp`). Supports CPython 3.8–3.16 (including No-GIL 3.13t–3.16t) & PyPy 3.8–3.12. Over 1,900+ downloads on Conda. Published on [PyPI](https://pypi.org/project/yfinance-ta-patterns/) and [conda-forge](https://anaconda.org/conda-forge/yfinance-ta-patterns).
- **[xlsx_vievers](https://github.com/eminsk/xlsx_vievers)** — High-performance spreadsheet library and desktop processor with a headless 129-function formula engine, hardware-accelerated SIMD SSE2 math, Chart Wizard, AutoFilter, Goal Seek, and Native MCP Server (`xlsx-viewer-mcp`). Published on [PyPI](https://pypi.org/project/xlsx-viewer-pro/) as `xlsx-viewer-pro` and on [conda-forge](https://anaconda.org/conda-forge/xlsx-viewer-pro).
- **[screenvideo](https://github.com/eminsk/screenvideo)** — High-performance desktop screen recorder and screenshot suite featuring WASAPI loopback audio, real-time H.264 streaming, Native MCP Server (`screenvideo-mcp`), and a standalone pure x64 Flat Assembler (FASM) native edition.
- **[ppa](https://github.com/eminsk/ppa)** — Official APT Repository (PPA) for Debian/Ubuntu packaging `pureapk`, `agentjit`, `nanogemm`, `nanorecall`, `nanovector`, `xlsx-viewer-pro`, and `yfinance-ta-patterns`. Available at [eminsk.github.io/ppa](https://eminsk.github.io/ppa/).

---

### 🌐 Open Source & Upstream Engineering

- **[conda-forge](https://github.com/conda-forge)** — Official Feedstock Maintainer across 8 published Conda packages:
  - [`nanogemm-feedstock`](https://github.com/conda-forge/nanogemm-feedstock), [`nanovector-feedstock`](https://github.com/conda-forge/nanovector-feedstock), [`agentjit-feedstock`](https://github.com/conda-forge/agentjit-feedstock), [`yfinance-ta-patterns-feedstock`](https://github.com/conda-forge/yfinance-ta-patterns-feedstock), [`nanorecall-feedstock`](https://github.com/conda-forge/nanorecall-feedstock), [`xlsx-viewer-pro-feedstock`](https://github.com/conda-forge/xlsx-viewer-pro-feedstock), [`avito-sdk-feedstock`](https://github.com/conda-forge/avito-sdk-feedstock), and [`pyfasm64`](https://github.com/conda-forge/staged-recipes/pull/35444).
- **Upstream Engineering & Contributions:**
  - **[Textualize/rich](https://github.com/Textualize/rich)** (49,000+ ⭐) — Layout engine edge case handling and terminal column boundary computation ([Issue #4214](https://github.com/Textualize/rich/issues/4214)).
  - **[Textualize/textual](https://github.com/Textualize/textual)** (26,000+ ⭐) — Text selection and boundary extraction in terminal widget hierarchies ([Issue #6708](https://github.com/Textualize/textual/issues/6708)).
  - **[marshmallow](https://github.com/marshmallow-code/marshmallow)** (7,000+ ⭐, 70M+/month downloads) — Cross-platform timestamp serialization test compatibility across POSIX and Windows runtimes ([PR #3046](https://github.com/marshmallow-code/marshmallow/pull/3046)).
  - **[sqlfluff](https://github.com/sqlfluff/sqlfluff)** (8,500+ ⭐) — SQL AST parser enhancement for MySQL-family type conversion expressions ([PR #8449](https://github.com/sqlfluff/sqlfluff/pull/8449)).
  - **[flet](https://github.com/flet-dev/flet)** (11,000+ ⭐) — Windows runtime file lock management during application asset cleanup ([PR #6817](https://github.com/flet-dev/flet/pull/6817)).

---

### 📬 Get in Touch

- **Developer Portal:** [eminsk.github.io](https://eminsk.github.io/)
- **Telegram:** [@charter2029](https://t.me/charter2029)
- **Email:** [M_N_Nik@yahoo.com](mailto:M_N_Nik@yahoo.com)
- **GitHub:** [github.com/eminsk](https://github.com/eminsk)
