<div align="center">
  <img src="assets/Logo.png" width="150" alt="Lune Plugin Logo" />

  <br />

  <h1>─── ✧ L U N E  P L U G I N ✧ ───</h1>

  <p>Lune Plugin is the high-performance core engine of the Lune ecosystem. It orchestrates complex data flows between the desktop client and Spotify's internal GraphQL infrastructure, handling everything from secure TOTP-based authentication to advanced metadata retrieval.</p>

  <br />

  <p>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-transparent?style=flat&color=C0C0C0&labelColor=333333" alt="License: MIT" />
    </a>
    <img src="https://img.shields.io/badge/Language-TypeScript-transparent?style=flat&color=C0C0C0&labelColor=333333" alt="Language: TypeScript" />
    <img src="https://img.shields.io/badge/Version-1.0.0-transparent?style=flat&color=C0C0C0&labelColor=333333" alt="Version 1.0.0" />
    <a href="https://discord.gg/TardrVJT9N">
      <img src="https://img.shields.io/badge/Discord-Join%20Us-transparent?style=flat&color=C0C0C0&labelColor=333333&logo=discord&logoColor=C0C0C0" alt="Discord" />
    </a>
  </p>
</div>

<br />

### / Modules

- **Auth Core** — Secure TOTP-based authentication and token lifecycle management.
- **GQL Engine** — Specialized handlers for Spotify's internal Search, Browse, and Radio endpoints.
- **Media Orchestrator** — Direct interfaces for track metadata, user library state, and playlist orchestration.
- **Type System** — Comprehensive TypeScript definitions for complex internal GQL responses.

<br />

### / Technical Excellence

- **Bypass Logic** — Custom HTTP clients tailored to navigate around standard API limitations seamlessly.
- **Resilience** — Centralized error handling and intelligent request retry mechanisms.
- **Efficiency** — Optimized data fetching with minimal overhead, designed for smooth desktop performance.

<br />

### / Tech Stack

Lune Plugin is built with focus on type-safety and performance:

- **Logic**: [TypeScript](https://www.typescriptlang.org/) for strict structural typing of GQL schemas.
- **Networking**: [Axios](https://axios-http.com/) with custom interceptors for session-based request handling.
- **Authentication**: Custom TOTP generation for Spotify's internal secure token exchange.
- **Integration**: Designed to hook directly into the [Electron](https://www.electronjs.org/) IPC layer.

<br />

### / Structure

```text
├── gql/                # GraphQL query definitions & response types
│   ├── core/           # Specialized request logic (Album, Search, Radio, etc.)
│   └── types/          # Strict TypeScript interface definitions
├── assets/             # Branding and documentation assets
├── spotify-auth-core   # TOTP & Token exchange logic
├── http-client         # Custom Axios wrapper for internal requests
└── utils               # Cryptographic and system helpers
```

<br />

### / Support

Building the future of music streaming? Give us a ⭐ and join our **[Discord](https://discord.gg/TardrVJT9N)** to contribute to the engine!

<br />

### / License

Lune Plugin is licensed under the **[MIT License](LICENSE)**.

This allows for broad usage within the open-source community, ensuring the core engine remains accessible for developers building within the Lune ecosystem.

---

<div align="center">
  <sub>✦ Lune Plugin ─ The Engine of Aesthetic Listening ✦</sub>
</div>

