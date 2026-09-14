# Qoopia V1

Your own memory for agents, on your Mac or server.

**[Download Qoopia V1](https://github.com/qoopia/qoopia-downloads/releases/latest)** · [Website](https://qoopia.ai) · [Installation guide and agent prompts](https://qoopia.ai/docs.html#agent-install) · [Open-source code](https://github.com/qoopia/qoopia-source)

- **Mac:** Apple Silicon, macOS 15 or newer. Developer ID signed and notarized by Apple.
- **Linux:** x64, glibc 2.34 or newer. Publisher-signed bundle. Managed agent process control requires procps (ps).
- Intel Macs and Windows are not supported in this release.

On Mac, open the DMG and drag Qoopia to Applications. On Linux, extract the archive and run `./qoopia open`. Each new user gets their own independent memory; a Qoopia website account does not give access to someone else's memory.

In **My Qoopia agent**, choose ChatGPT/Codex or Claude/Claude Code and complete your provider sign-in. Use the dashboard chat or configure your own Telegram bot. Existing stewards can be retained. A supported provider subscription and its limits apply. Connections to ChatGPT Web/Desktop remain experimental.

Already using Codex or Claude Code? Copy the installation task from the [website](https://qoopia.ai/docs.html#agent-install) to your agent. It includes the exact package, checksum and approval boundaries.

Verify the package against `SHA256SUMS.txt`. Each release includes signed manifests and `publisher-public-key.pem` (SHA-256 `542bd3715cfbc89fbb2df47b8c40f4964e340993f316f0c32866a2972965e33b`).

This repository distributes installers and public release metadata. Product source is open under MIT in [qoopia-source](https://github.com/qoopia/qoopia-source). No private workspace data is distributed here.
