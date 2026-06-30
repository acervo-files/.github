# Acervo

**Local-first infrastructure for archival document research.**

Acervo is a hybrid project for ingesting, OCRing, summarizing, and
locally searching large archives of public-record documents — from
government disclosures to court filings to scientific records.

## Two layers

**Acervo Engine** — the open framework
- Source adapter pattern, OCR cascade, hybrid full-text + semantic search
- Source available under BSL
- Built so anyone can verify how documents are obtained and processed

**Acervo Files** — the commercial application
- Polished desktop app that ships maintained Collections of curated
  archives, OCR + AI summaries, hybrid search
- First Collections at launch: U.S. government disclosures
  (PURSUE, FBI Vault, etc)
- Future Collections: FOIA disclosures, court records, others

## Source adapters

Each source has its own openly published adapter so legal compliance
(ToS, robots.txt) is verifiable independently of the application.

## Status

In active development. First public release planned for later in 2026/2027.
Watch this organization to be notified.

## Principles

- **Local-first**: no cloud dependency, no telemetry, your archive stays on your machine
- **Legal compliance**: ToS + robots.txt audited per source
- **Bit-perfect preservation**: original documents stored unmodified
- **Secrets stay local**: API keys never in repo — only in OS keyring
- **Verifiability**: source adapters are open so anyone can audit our compliance posture
