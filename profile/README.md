# PrudAI

**Agentic AI for legal, healthcare, and construction professionals.**
EU-pinned, Dutch-built, accountability-first.

[prudai.com](https://prudai.com) · [docs.prudai.com](https://docs.prudai.com) · [trust.prudai.com](https://trust.prudai.com) · [legal.prudai.com](https://legal.prudai.com) · [status.prudai.com](https://status.prudai.com)

---

## Products

| Product | Domain | Audience | Wikidata |
|---|---|---|---|
| **LEO** — Lex Explanata Oraculo | [leo.prudai.com](https://leo.prudai.com) | Legal professionals | [Q139906960](https://www.wikidata.org/wiki/Q139906960) |
| **VERA** | [vera.prudai.com](https://vera.prudai.com) | Construction (Bbl / Wkb compliance) | [Q139906961](https://www.wikidata.org/wiki/Q139906961) |
| **ZIA** | [zia.prudai.com](https://zia.prudai.com) | Healthcare professionals | [Q139906962](https://www.wikidata.org/wiki/Q139906962) |

LEO runs at [app.prudai.com](https://app.prudai.com).

## Why PrudAI

- **EU data residency by default** — Azure OpenAI (Sweden Central) and Vertex AI (EU regions). No US-bound prompt data unless you ask.
- **Citations or it didn't happen** — every legal/professional answer is backed by retrieved source documents; we surface them in the UI, never hidden.
- **Built for regulated work** — DPA, subprocessor list, and ISMS-derived controls published at [trust.prudai.com](https://trust.prudai.com).
- **B-Corp pending** — accountability isn't a marketing line, it's a governance commitment.

## What we open-source

Most of PrudAI's code is private (product code, infra, customer-touching surfaces). A small set of building blocks is public on npm under [`@prudai`](https://www.npmjs.com/org/prudai):

- **[echr-extractor](https://github.com/Prudai/echr-extractor)** — TypeScript port of the academic `echr-extractor`. Pulls ECHR case-law metadata, full text, and citation networks from HUDOC. Apache-2.0.
- **[marketing-analytics](https://github.com/Prudai/marketing-analytics)** — Shared GA4 + GlitchTip + consent (vanilla-cookieconsent v3) bundle used across our marketing sites. GDPR-first.

If you build legal-tech tooling on top of either, we'd love to hear about it.

## Identity

- **Legal entity:** PrudAI B.V., Enschede, Netherlands
- **Wikidata:** [Q139906958](https://www.wikidata.org/wiki/Q139906958)
- **Contact:** [info@prudai.com](mailto:info@prudai.com)
- **Status:** [status.prudai.com](https://status.prudai.com)
- **Trust & security:** [trust.prudai.com](https://trust.prudai.com)
- **Legal & DPA:** [legal.prudai.com](https://legal.prudai.com)

## Contributing

External PRs are welcome on our public repos. For each repo, see its `README.md` and `CONTRIBUTING.md` (where present) for scope, code style, and the DCO/CLA situation. Security issues: please email **security@prudai.com** rather than opening a public issue.
