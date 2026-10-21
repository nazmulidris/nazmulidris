### Hi there 👋

| <img src="https://github.com/nazmulidris/developerlife.com/blob/main/assets/nazmul.png?raw=true"/> | Hi, I'm <a href="https://nazmulidris.com">Naz</a> 😃, a **Rustacean 🦀, Systems Engineering Leader & Founder** building next-generation terminal platforms and developer tooling for the AI & cloud era. Also an ex-Googler (Android Studio IDE Platform), <a href="https://github.com/r3bl-org/r3bl-open-core/" target="_blank">maintainer</a>, designer, leader, HsingI-er, racer, storyteller. I 💓 leadership, authenticity, play, and hope. I build high-performance systems infrastructure and lead teams that ship production systems. I am equally comfortable architecting low-latency systems and writing production code, defining product vision and go-to-market execution, and building cultures of engineering excellence. |
| -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

✨ You can read all my articles on [developerlife.com](https://developerlife.com) and
watch my videos on [YouTube](https://www.youtube.com/@developerlifecom).

## 🦀 What I'm Building at R3BL

```text
██████╗  ██████╗  ██████╗
██╔══██╗██╔═══██╗██╔════╝
██████╔╝██║   ██║██║
██╔══██╗██║   ██║██║
██║  ██║╚██████╔╝╚██████╗
╚═╝  ╚═╝ ╚═════╝  ╚═════╝
```

Despite the massive rise of autonomous coding agents and remote cloud VM administration,
terminal UI and foundational primitives have largely stagnated since the 1990s.

I am reimagining the terminal for this era, to address the needs of LLM harnesses and
ergonomic remote cloud VM admin.

The first thing I am doing is creating better primitives
([`r3bl-open-core` aka `ROC`](https://github.com/r3bl-org/r3bl-open-core)) from the ground
up in Rust (**2.7M+ downloads** on [crates.io](https://crates.io/users/nazmulidris)) to bridge
the gap in terminal capabilities since the 90's.

Available today, `ROC` provides a strictly type-safe, correctness-focused async TUI engine,
headless virtual terminal emulation (VTE), low-latency PTY/TTY runtime, CLI/TUI apps
(`edi`, `giti`), MCP servers, and IDE/browser extensions.

Built on top of this open-source foundation, I'm building an upcoming closed-source suite
of terminal apps at [r3bl.com](https://r3bl.com) (which all work seamlessly over SSH).
This includes a local-first collaborative _"Google Docs meets Jupyter notebooks"_ for
Markdown and virtual terminal multiplexers.

My focus is on preserving data sovereignty, privacy, and enabling local-first computing,
while enhancing developer productivity, knowledge capture & sharing, and workflow
management.

### Architecture, Platform & Ecosystem

- **Async TUI Engine & VTE Primitives (Open Source):** [`r3bl_tui`](https://crates.io/crates/r3bl_tui)
  provides a strictly type-safe, correctness-focused async TUI engine (custom CSS/Flexbox layout engine,
  custom rendering engine, Elm-style unidirectional state management, React/JSX-style declarative
  macros, and a full-featured Markdown editor component with custom Markdown parser and syntax
  highlighting), async readline, headless virtual terminal emulation (VTE), and low-latency
  PTY/TTY runtime in Rust.
- **Interactive CLI & TUI Apps (Open Source):** [`r3bl-cmdr`](https://crates.io/crates/r3bl-cmdr)
  provides a terminal Markdown editor (`edi`) powered by `r3bl_tui`'s Markdown editor component,
  alongside interactive Git workflows (`giti`) for branch management and staging.
- **AI & MCP Servers (Open Source):** [`r3bl-rust-analyzer-mcp-server`](https://crates.io/crates/r3bl-rust-analyzer-mcp-server)
  delivers high-performance Model Context Protocol (MCP) servers and tools for LLMs to orchestrate in
  their agentic harnesses, bridging AI coding agents directly with local language servers and toolchains.
- **IDE & Browser Extensions (Open Source):** Suite of [VS Code](https://marketplace.visualstudio.com/publishers/R3BL)
  and [Open VSX](https://open-vsx.org/namespace/R3BL) extensions for Rust development, semantic
  highlighting, and task spaces, alongside the R3BL Shortlink browser extension
  ([Chrome](https://chrome.google.com/webstore/detail/r3bl-shortlink/ffhfkgcfbjoadmhdmdcmigopbfkddial)
  and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/r3bl-shortlink/)).
- **Upcoming Local-First Product Suite (Closed Source):** Built on top of the `ROC` open-source
  foundation, I am building an upcoming suite of terminal apps at [r3bl.com](https://r3bl.com)
  (which all work seamlessly over SSH). Products like **local-first collaborative _"Google Docs meets
  Jupyter notebooks"_ for Markdown** (real-time collaborative editing and Markdown code execution)
  and **headless virtual terminal multiplexers** with virtual tabs for interactive cloud infrastructure
  setup and multiplexed AI coding agent workflows, all focused on **data sovereignty, privacy, and
  local-first computing**.

## 💡 Background

- **30-year tech career:** Hands-on software engineering throughout all 30 years, alongside **10+ years concurrently** in founder, CEO, and executive leadership roles
- **5+ years Rust systems programming:** Founder, Principal Systems Engineer & Maintainer at [R3BL](https://r3bl.com) ([`ROC`](https://github.com/r3bl-org/r3bl-open-core), **2.7M+ downloads** on [crates.io](https://crates.io/users/nazmulidris))
- **Ex-Google (7.5 years):** Android Studio IDE Platform team (performance, memory latency & stability on a 10M+ LOC codebase), Google Maps APIs, Android Media Framework (ExoPlayer), and Android UX Design
- **Founder & CEO:** **TRNQL** ($1.5M VC seed raised, shipped production Android/iOS contextual SDKs) and **ScreamingToaster** (100k+ users globally, 2× Global BlackBerry DevCon Best App in the World finalist)
- **Patents & Books:** Invented [US Patent `US6891860B1`](https://patents.google.com/patent/US6891860) (mobile push/socket multiplexing) and authored **[Java and XML](https://www.amazon.com/dp/188477783X)** (Manning Publications, 400 pages)
- **Full-Stack Systems Breadth:** Rust, TypeScript, Kotlin, Java, Node.js, React | Desktop, web, mobile, IDEs, cloud infrastructure

## 📚 Teaching & Content

- **YouTube:** [Advanced Rust systems programming & live coding](https://www.youtube.com/@developerlifecom)
- **developerlife.com (est. 1998):** [28 years of authoring in-depth engineering tutorials & architecture case studies](https://developerlife.com) across Rust, AI & LLMs, async systems, Tokio, TUI/CLI platforms, Kotlin, Android, TypeScript, Node.js, and React
- **Google UX Design Show & Udacity Course:** 400k+ combined reach (200k+ YouTube views, 200k+ Udacity students) & Google I/O experiential workshops (2,000+ attendees)

<p align="center">
<a href="https://github.com/nazmulidris">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=nazmulidris&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=nazmulidris&layout=compact&langs_count=8&theme=dark"/>
</a>
</p>

💬 More info about me: https://nazmulidris.com  
📬 Reach me: [LinkedIn](https://linkedin.com/in/nazmulidris)

<!--
**nazmulidris/nazmulidris** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
