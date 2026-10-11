# ai-evidence-format-landing

Static landing site for the **[AI Evidence Format spec](https://github.com/mizcausevic-dev/ai-evidence-format-spec)** — part of the [Kinetic Gain Protocol Suite](https://suite.kineticgain.com).

Live at **[evidence.kineticgain.com](https://evidence.kineticgain.com)**.

Hand-written HTML + CSS, no build step. Merging to `main` does not deploy: the GitHub Actions SFTP upload requires `workflow_dispatch` and is unverified. For a release, use a reviewed local Hostinger SSH/SFTP route with pinned host key, exact backups and hashes, hosted checks, and restore proof.

## License
Apache-2.0. Underlying spec is MIT-licensed.
