### Hi, I'm Sean 👋

I'm a final-year Advanced Computing (R&D) Honours student at **The Australian National University**, graduating in December 2026. I work on systems software: crash-consistent storage, compilers, and concurrent network services.

#### Right now

- 🔬 **Research assistant at ANU:** building crash-consistent durable state across memory tiers. That means a write-ahead log and a persistent region allocator behind one persistence interface, covering both byte-addressable and block-backed media. It's written in [Virgil](https://github.com/titzer/virgil) inside the Wizard research VM.
- 🧠 **[virgil-language-server](https://github.com/SaltedTan/virgil-language-server):** a Language Server for Virgil, written in Virgil on top of the compiler's own parser and type checker. Diagnostics, go-to-definition, and hover in Neovim and VS Code.
- 🔋 **[CellKeeper](https://github.com/SaltedTan/CellKeeper):** an open-source macOS menu-bar app for transparent, safety-first battery charge management. The charging policy engine is kept separate from the hardware and covered by 1,300+ tests.

#### Selected projects

| Project | What it is |
| :-- | :-- |
| [**traffic‑warden**](https://github.com/SaltedTan/traffic-warden)<br><sub>Rust&nbsp;·&nbsp;Tokio&nbsp;·&nbsp;Axum</sub> | Concurrent HTTP reverse proxy with token-bucket rate limiting, round-robin load balancing, health-checked failover, and streamed bodies. Lock striping cut the rate limiter's hot path from ~25 ms to ~3 ms at 8 threads. |
| [**sysy‑compiler**](https://github.com/SaltedTan/sysy-compiler)<br><sub>C++17&nbsp;·&nbsp;Flex&nbsp;·&nbsp;Bison</sub> | Compiler for SysY, a subset of C: Flex/Bison parsing, a polymorphic AST, Koopa IR, and a two-pass RV32I backend. |
| [**courtside‑alpha**](https://github.com/SaltedTan/courtside-alpha)<br><sub>Rust&nbsp;·&nbsp;Next.js&nbsp;·&nbsp;Python</sub> | Paper-trading system for live NBA prediction markets, built at UNIHACK 2026 in a team of two. I built the Rust execution engine and the Next.js dashboard; my teammate built the model. |

#### Tools I reach for

<p>
  <img src="https://skillicons.dev/icons?i=rust,c,cpp,cs,java,py,ts,swift,react,nextjs,fastapi,dotnet,postgres,redis,linux,docker,git,wasm&perline=9" alt="Rust, C, C++, C#, Java, Python, TypeScript, Swift, React, Next.js, FastAPI, .NET, PostgreSQL, Redis, Linux, Docker, Git, WebAssembly" />
</p>

#### Previously

Co-founder & full-stack developer at Pookie Platforms · .NET intern at Sarawak Information Systems (SAINS) · Internal VP and Tech Lead at GDG on Campus ANU, where I co-built a [campus AR scavenger hunt](https://github.com/fishchimp/AR-Scavenger-Hunt) · Lead instructor at OzCode Academy

#### Get in touch

Happy to chat about systems, compilers, or research. Find me on [LinkedIn](https://www.linkedin.com/in/sean-huan-zhi-tan/).
