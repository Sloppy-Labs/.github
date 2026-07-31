<div align="center">

<img src="./assets/logo.png" width="112" alt="Sloppy Labs logo">

# Sloppy Labs

**Carefully crafted. Fast, focused software with less overhead.**

We build practical software that stays small, understandable, and pleasant to operate.

</div>

---

## Featured project

### Manta Share

A self-hosted file-sharing service designed for both private deployments and public hosting.

Manta Share keeps its default operational model intentionally small:

* one Go binary
* embedded web interface
* SQLite metadata
* local file storage
* no required external services

Deployments that need additional infrastructure can optionally enable S3-compatible storage, Redis, SMTP, ClamAV, LDAP, OIDC, and social authentication.

#### Highlights

* Account, anonymous, and invitation-based sharing
* Passwords, expiration dates, download limits, and file requests
* Resumable uploads, folders, clipboard paste, previews, and QR links
* User ownership, quotas, roles, session revocation, and API keys
* Local and S3-compatible streaming storage
* Optional ClamAV malware quarantine
* SMTP notifications, invitations, verification, and password resets
* OIDC, Google, Microsoft, GitHub, Discord, Pocket ID, and LDAP authentication
* Optional Redis coordination for multi-instance deployments
* Signed webhooks, administrator diagnostics, and the `manta` upload CLI
* Reproducible cross-platform binaries and container images

Manta Share remains fully useful without external dependencies. SQLite and local files provide the supported baseline for a simple single-instance deployment.

> Manta Share is currently under private development.

---

## How we build

We prefer:

* focused products over oversized platforms
* simple deployments over infrastructure by default
* efficient native software over unnecessary runtime layers
* explicit configuration over hidden behavior
* secure defaults over convenient surprises
* understandable code over premature abstraction

Optional complexity should remain optional.

---

## Technology

Our current work is centered around:

`Go` · `SQLite` · `S3` · `Redis` · `Docker` · `templ` 

Manta Share is tested with formatting, static analysis, unit and integration tests, desktop and mobile browser workflows, the Go race detector, vulnerability scanning, dependency review, container builds, and reproducible release binaries.

---

<div align="center">

Built carefully by **Sloppy Labs**.

</div>
