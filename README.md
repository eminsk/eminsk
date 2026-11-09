### Hi there, I'm M_N_Nik 👋

**Systems Engineer & Compiler Developer** with an engineering background spanning back to the **early 2000s**.

Combining decades of foundational systems programming — from low-level architectures (x86/x64 Assembly, Win32 API, C) to modern high-performance Python engineering, AOT compilation, asynchronous services, desktop applications, and algorithmic data pipelines.

[![Website Badge](https://img.shields.io/badge/Developer_Portal-eminsk.github.io-00F0FF?style=for-the-badge&logo=google-chrome&logoColor=black)](https://eminsk.github.io/)
[![Telegram Badge](https://img.shields.io/badge/Telegram-@charter2029-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/charter2029)
[![Email Badge](https://img.shields.io/badge/Email-M__N__Nik@yahoo.com-6001D2?style=for-the-badge&logo=yahoo&logoColor=white)](mailto:M_N_Nik@yahoo.com)
[![Downloads Badge](https://img.shields.io/badge/Conda--Downloads-22k%2B-green?style=for-the-badge&logo=anaconda&logoColor=white)](https://anaconda.org/m_n_nik)

---

### 🧭 Engineering Philosophy & Background

- **Decades of Craft:** Writing code since the early 2000s, built on a deep understanding of memory management, operating system internals, CPU microarchitecture, and native Win32/POSIX runtime behavior.
- **Hardware-Aware Performance:** Bridging high-level Python productivity with bare-metal speed — developing native AOT compilers, custom SIMD (SSE2/AVX2/NEON) vector kernels, FASM x64 assembly engines, and zero-copy C extensions.
- **Architectural Discipline:** Strong emphasis on clean code separation, strict typing (`mypy`), modern tooling (`uv`, `ruff`), reproducible builds, hardware concurrency, and native assembly compilation (`FASM x64`).

---

### 🛠 Tech Stack & Core Competencies

- **Compilers & Low-Level Systems:** Python AST to pure x86_64 FASM AOT Compiler, Peephole Optimization, Calling Conventions (Microsoft x64 ABI / System V ABI, 16-byte stack alignment, shadow space), CPU register allocation, hardware atomic primitives (`lock add/sub`).
- **Languages:** Python (3.8–3.16, Free-Threaded No-GIL 3.13t–3.16t, PyPy), x86/x64 Assembly (Flat Assembler - FASM / FASMG), C99 / Win32 API
- **High-Performance Computing (HPC) & SIMD:** SIMD Vectorization (SSE2/AVX2/FMA/ARM NEON), BLAS / GEMM matrix multiplication micro-kernels, SIMD JSON parsing, Vector Search & Embeddings
- **Concurrency & Multithreading:** True No-GIL Native OS Threads (`CreateThread`), Free-Threaded Multi-Core (PEP 703), Lock-free & Atomic synchronization, Asyncio, Inter-Process Communication (IPC)
- **AI Agents & Protocols:** Model Context Protocol (MCP) JSON-RPC 2.0 Servers (Claude Code, Antigravity, Cursor, Windsurf), Agent Trajectory JIT Compilation, Semantic Vector Search
- **Desktop & UI Engineering:** Modern Fluent Dark UI styling (`ui_fluent.inc`), High-DPI scaling, CustomTkinter, Flet, Tkinter, native Win32/GDI assembly engineering
- **Data, Math & Trading:** TA-Lib (quantitative technical analysis & 61 candlestick pattern recognition), OpenPyXL, Pandas, NumPy, SQLite
- **Quality & DevTools:** uv, ruff, mypy, pytest, Conda-Forge / Rattler-Build, Debian/Ubuntu APT PPA, GitHub Actions CI/CD pipelines

---

### 🚀 Featured Projects

- **[pureapk](https://github.com/eminsk/pyapk)** (pyapk) — Zero-dependency pure Python Android APK engine with Android 15 16KB ELF page alignment (tag `0xd935`), APK v1/v2/v3 signatures, multi-store packaging (APK, Google Play AAB, iOS IPA stub, Windows 11 MSIX), in-place APK modification, and Android wheel extraction without Java or Android Studio. Published on [PyPI](https://pypi.org/project/pureapk/) (`pureapk v1.0.1`) and available on Debian/Ubuntu APT PPA (`python3-pureapk`).
- **[pyfasm](https://github.com/eminsk/pyfasm)** — Universal Native No-GIL (3.13t–3.16t) & PyPy to pure x86_64 Flat Assembler (FASM) Native Compiler. Translates Python AST directly into self-contained standalone PE+ (`.exe`, `.dll`), ELF64, and Mach-O binaries (~9 KB) with zero virtual machine and zero runtime overhead. Features true multi-threaded native concurrency (`CreateThread` with hardware atomics), SSE scalar/vector floating point, SIMD-accelerated JSON parser, and native Win32 GUI engine. Published on [PyPI](https://pypi.org/project/pyfasm64/) (`pyfasm64 v0.1.24`) and announced on the [Flat Assembler Board](https://board.flatassembler.net/topic.php?t=24431).
- **[fasm-modern-sdk](https://github.com/eminsk/fasm-modern-sdk)** — Modernized SDK and header toolchain for Flat Assembler (FASM v1.73 / FASMG) featuring 64-bit Windows equates, official calling conventions, and zero-configuration bindings.
- **[agentjit](https://github.com/eminsk/agentjit)** — Just-In-Time Compiler for AI Agent Trajectories. Compiles flaky, 30-second multi-step LLM workflows into 0.08ms deterministic Python code with zero token cost. Features speculative guards, automatic bailout runtime, free-threaded (No-GIL PEP 703) support, and Native MCP Server (`agentjit-mcp`). Featured as the #1 Top Story in [The Daily Diff](https://tdd.cat/2026-09-13/) (9/10 Depth & Utility Score). Published on [PyPI](https://pypi.org/project/agentjit/) and [conda-forge](https://anaconda.org/conda-forge/agentjit).
- **[nanovector](https://github.com/eminsk/nanovector)** — The SQLite of Vector Search & Episodic Memory for AI Agents in ~120KB. Zero dependencies, instant 0.2ms cold start, pure C99 with AVX2+FMA, ARM NEON, hand-crafted FASM x64 assembly kernels, and Native MCP Server (`nanovector-mcp`). Over 7,900+ downloads on Conda. Published on [PyPI](https://pypi.org/project/nanovector/) and [conda-forge](https://anaconda.org/conda-forge/nanovector).
- **[nanogemm](https://github.com/eminsk/nanogemm)** — Minimalist, bare-metal AVX2+FMA & ARM NEON matrix multiplication engine in ~100KB for Python, outperforming NumPy by up to 2.8x on CPU for edge neural network inference, and Native MCP Server (`nanogemm-mcp`). Over 9,800+ downloads on Conda. Featured in [The Daily Diff](https://tdd.cat/2026-09-07/) (9/10 Depth Score), trending on GitHub (Deep Learning), and published on [PyPI](https://pypi.org/project/nanogemm/) and [conda-forge](https://anaconda.org/conda-forge/nanogemm).
- **[nanorecall](https://github.com/eminsk/nanorecall)** — 100% Private, Zero-Cloud, Bare-Metal Desktop Memory & Screen Search Engine in <200KB. Runs on standard CPUs with zero telemetry, automatic privacy shielding for password managers, sub-millisecond semantic search via NanoVector, and Native MCP Server (`nanorecall-mcp`). Published on [PyPI](https://pypi.org/project/nanorecall/) and [conda-forge](https://anaconda.org/conda-forge/nanorecall).
- **[yfinance-ta-patterns](https://github.com/eminsk/yfinance-ta-patterns)** — Institutional candlestick pattern scanner (all 61 TA-Lib patterns with pure-Python fallback), unbiased next-open backtester, AI Confluence Scorer, Asset Economic Calendar, and Native MCP Server (`yfinance-ta-mcp`). Supports CPython 3.8–3.16 (including No-GIL 3.13t–3.16t) & PyPy 3.8–3.12. Over 1,900+ downloads on Conda. Published on [PyPI](https://pypi.org/project/yfinance-ta-patterns/) and [conda-forge](https://anaconda.org/conda-forge/yfinance-ta-patterns).
- **[xlsx_vievers](https://github.com/eminsk/xlsx_vievers)** — High-performance spreadsheet library and desktop processor with a headless 129-function formula engine, hardware-accelerated SIMD SSE2 math, Chart Wizard, AutoFilter, Goal Seek, and Native MCP Server (`xlsx-viewer-mcp`). Published on [PyPI](https://pypi.org/project/xlsx-viewer-pro/) as `xlsx-viewer-pro` and on [conda-forge](https://anaconda.org/conda-forge/xlsx-viewer-pro).
- **[avito-sdk](https://github.com/eminsk/avito-sdk)** — High-performance headless Avito scraping & data extraction SDK with real-time price drop tracking, full item parameter extraction, Playwright cookie refresh, Telegram/VK notification bots, and Native MCP Server (`avito-mcp`). Published on [PyPI](https://pypi.org/project/avito-sdk/) and [conda-forge](https://anaconda.org/conda-forge/avito-sdk).
- **[screenvideo](https://github.com/eminsk/screenvideo)** — High-performance desktop screen recorder and screenshot suite featuring WASAPI loopback audio, real-time H.264 streaming, Native MCP Server (`screenvideo-mcp`), and a standalone pure x64 Flat Assembler (FASM) native edition ([Release v2.0.0](https://github.com/eminsk/screenvideo/releases/tag/v2.0.0)).
- **[ppa](https://github.com/eminsk/ppa)** — Official APT Repository (PPA) for Debian/Ubuntu packaging `pureapk`, `agentjit`, `avito-sdk`, `nanogemm`, `nanorecall`, `nanovector`, `xlsx-viewer-pro`, and `yfinance-ta-patterns`. Available at [eminsk.github.io/ppa](https://eminsk.github.io/ppa/).
- **[awesome-baremetal-ai](https://github.com/eminsk/awesome-baremetal-ai)** — Curated benchmark leaderboard and directory of ultra-lightweight, zero-dependency C/C++/Rust/Assembly engines for local LLMs, edge inference, vector search, and AI agents.
- **[StackOverflowAPI](https://github.com/eminsk/StackOverflowAPI)** — Modern bilingual desktop client for Stack Overflow built with CustomTkinter, Catppuccin palettes, syntax highlighting, offline bookmarking, and native FASM x64 search client.

---

### 🌐 Open Source Contributions

- **[conda-forge](https://github.com/conda-forge)** / **[staged-recipes](https://github.com/conda-forge/staged-recipes)** (850+ ⭐) — Official Feedstock Maintainer across published Conda-Forge packages:
  - **Active & Merged Feedstocks:** [`nanogemm-feedstock`](https://github.com/conda-forge/nanogemm-feedstock) ([PR #34896](https://github.com/conda-forge/staged-recipes/pull/34896)), [`nanovector-feedstock`](https://github.com/conda-forge/nanovector-feedstock) ([PR #34898](https://github.com/conda-forge/staged-recipes/pull/34898)), [`yfinance-ta-patterns-feedstock`](https://github.com/conda-forge/yfinance-ta-patterns-feedstock) ([PR #34894](https://github.com/conda-forge/staged-recipes/pull/34894)), [`avito-sdk-feedstock`](https://github.com/conda-forge/avito-sdk-feedstock) ([PR #35071](https://github.com/conda-forge/staged-recipes/pull/35071)), [`agentjit-feedstock`](https://github.com/conda-forge/agentjit-feedstock) ([PR #34895](https://github.com/conda-forge/staged-recipes/pull/34895)), [`nanorecall-feedstock`](https://github.com/conda-forge/nanorecall-feedstock) ([PR #34897](https://github.com/conda-forge/staged-recipes/pull/34897)), [`xlsx-viewer-pro-feedstock`](https://github.com/conda-forge/xlsx-viewer-pro-feedstock) ([PR #34899](https://github.com/conda-forge/staged-recipes/pull/34899)), and [`pyfasm64`](https://github.com/conda-forge/staged-recipes/pull/35444) ([PR #35444](https://github.com/conda-forge/staged-recipes/pull/35444)).
- **[Duff89/parser_avito](https://github.com/Duff89/parser_avito)** (750+ ⭐) — Core contributor across parsing, reliability, and data export subsystems:
  - [PR #331 (Merged)](https://github.com/Duff89/parser_avito/pull/331): Incremental atomic page-by-page result persistence preventing data loss on crash or stop ([Fixes #300](https://github.com/Duff89/parser_avito/issues/300)).
  - [PR #329 (Merged)](https://github.com/Duff89/parser_avito/pull/329): Full item description extraction from ad pages with async fetching ([Fixes #305](https://github.com/Duff89/parser_avito/issues/305)).
  - [PR #328 (Merged)](https://github.com/Duff89/parser_avito/pull/328): Automatic log cleanup and gzip compression for rotated log files ([Fixes #274](https://github.com/Duff89/parser_avito/issues/274)).
  - [PR #327 (Merged)](https://github.com/Duff89/parser_avito/pull/327): Address filter crash fix (`AttributeError` on geo), Excel export with `None` fields, and GUI freeze prevention ([Fixes #324](https://github.com/Duff89/parser_avito/issues/324), [#325](https://github.com/Duff89/parser_avito/issues/325), [#326](https://github.com/Duff89/parser_avito/issues/326)).
  - [PR #337 (Active)](https://github.com/Duff89/parser_avito/pull/337): Extraction of additional item parameters and characteristics («О помещении» etc.) with Excel export column and unit tests ([Fixes #335](https://github.com/Duff89/parser_avito/issues/335)).
  - [PR #334 (Active)](https://github.com/Duff89/parser_avito/pull/334): Price change tracking & delta history ([Resolves #214](https://github.com/Duff89/parser_avito/issues/214)) and seller name extraction ([Fixes #333](https://github.com/Duff89/parser_avito/issues/333)).
- **[xtekky/gpt4free](https://github.com/xtekky/gpt4free)** (65k+ ⭐) — [PR #3514 (Merged)](https://github.com/xtekky/gpt4free/pull/3514) / [Issue #3511](https://github.com/xtekky/gpt4free/issues/3511): Fixed unhandled `AttributeError` on `access_token` in Copilot provider.
- **[flet-dev/flet](https://github.com/flet-dev/flet)** (11k+ ⭐) — [PR #6817 (Merged)](https://github.com/flet-dev/flet/pull/6817) / [Issue #6808](https://github.com/flet-dev/flet/issues/6808): Fixed Windows build crash `PermissionError` on read-only files during directory cleanup.
- **[sqlfluff/sqlfluff](https://github.com/sqlfluff/sqlfluff)** (8.5k+ ⭐) — [PR #8449 (Merged)](https://github.com/sqlfluff/sqlfluff/pull/8449) / [Issue #8171](https://github.com/sqlfluff/sqlfluff/issues/8171): Added support for MySQL-family `CONVERT(expr, type)` argument ordering across the SQL parser and rule engines.
- **[marshmallow-code/marshmallow](https://github.com/marshmallow-code/marshmallow)** (7k+ ⭐, 70M+/mo) — [PR #3046](https://github.com/marshmallow-code/marshmallow/pull/3046) / [Issue #2999](https://github.com/marshmallow-code/marshmallow/issues/2999): Fixed regex match in timestamp overflow tests to support Windows error messages.
- **[Textualize/rich](https://github.com/Textualize/rich)** (49k+ ⭐) — [Root-cause diagnosis & verified fix for Issue #4214](https://github.com/Textualize/rich/issues/4214): Resolved `ZeroDivisionError` in `Columns` when available terminal width is smaller than item width plus padding.
- **[Textualize/textual](https://github.com/Textualize/textual)** (26k+ ⭐) — [Fix & Tests for Issue #6708](https://github.com/Textualize/textual/issues/6708): Resolved unhandled `IndexError` in `Selection.extract` when mouse selecting on/across trailing empty lines of widgets.
- **Curated Ecosystem & Awesome Lists Submissions:**
  - **[e2b-dev/awesome-ai-sdks](https://github.com/e2b-dev/awesome-ai-sdks)** — [PR #399](https://github.com/e2b-dev/awesome-ai-sdks/pull/399): Added `agentjit` to Agent Infrastructure and Runtime JIT execution.
  - **[Danielskry/Awesome-RAG](https://github.com/Danielskry/Awesome-RAG)** — [PR #155](https://github.com/Danielskry/Awesome-RAG/pull/155): Added `nanovector` to Vector Search Libraries and Tools.
  - **[oz123/awesome-c](https://github.com/oz123/awesome-c)** — [PR #400](https://github.com/oz123/awesome-c/pull/400) & [PR #401](https://github.com/oz123/awesome-c/pull/401): Added `nanogemm` (Numerical) and `nanovector` (AI/Vector search).
  - **[currentslab/awesome-vector-search](https://github.com/currentslab/awesome-vector-search)** — [PR #72](https://github.com/currentslab/awesome-vector-search/pull/72): Added `nanovector` to Vector Search Library section.
  - **[awesome-simd/awesome-simd](https://github.com/awesome-simd/awesome-simd)** — [PR #9](https://github.com/awesome-simd/awesome-simd/pull/9): Added `nanogemm` to Neural Network SIMD section.

---

### 📬 Get in Touch

- **Telegram:** [@charter2029](https://t.me/charter2029)
- **Email:** [M_N_Nik@yahoo.com](mailto:M_N_Nik@yahoo.com)
- **GitHub:** [github.com/eminsk](https://github.com/eminsk)
