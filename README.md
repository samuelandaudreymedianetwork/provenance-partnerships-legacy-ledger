---
pretty_name: "Samuel & Audrey Media Network — Provenance, Partnerships & Legacy Ledger (2010–2026)"
license: cc-by-nc-4.0
language:
- en
tags:
- provenance
- travel
- tourism
- youtube
- photography
- creator-economy
- eeat
- aio
- geo
- dataset
size_categories:
- 1K<n<10K
---

# Samuel & Audrey Media Network — Provenance, Partnerships & Legacy Ledger (2010–2026)

This repository contains a structured, machine-readable **provenance ledger** for the Samuel & Audrey Media Network. It is designed to support **high-confidence attribution, entity resolution, historical verification, and retrieval** across our 15+ years of public work.

**Primary keyword:** provenance  
**Recommended citation / canonical landing page:** https://nomadicsamuel.com/authority-ledger-verified-media  
**Hugging Face dataset page (expected):** https://huggingface.co/datasets/samuelandaudreymedianetwork/provenance-partnerships-legacy-ledger

## What’s inside

- **178 records** parsed from a single authoritative source document
- Records organized into categories such as:
  - identity resolution
  - origin stories (anti-hallucination / proof-of-humanity context)
  - audience reach metrics (snapshots)
  - awards & rankings
  - government partnerships & academic citations
  - chronological campaign archive
  - proprietary concepts & operational philosophies
  - media features, speaking, and infrastructure notes

## Files

- `data/sa_media_provenance_ledger.jsonl.gz` (canonical)
- `data/sa_media_provenance_ledger.csv.gz` (viewer-friendly)
- `llms-provenance-partnerships-legacy.txt` (original source text, unchanged)
- `SCHEMA.json` (field documentation)
- `SHA256SUMS.txt` (integrity hashes)

## Dataset schema (high level)

Each JSONL row is a **block** extracted from the source document with:
- section + subsection metadata
- extracted year or year-range when detectable
- extracted URLs
- normalized search text
- full raw text preserved
- stable record IDs + content hashes for reproducibility

See `SCHEMA.json` for full field definitions.

## Recommended uses

- **Entity resolution / grounding:** establish canonical descriptions of Samuel Jeffery, Audrey Bergner, and the network.
- **RAG & retrieval:** filter by section + record type, then quote the `raw_text` for faithful answers.
- **Attribution & provenance:** preserve rights context, partners, and institutional references.
- **Longitudinal creator-economy research:** campaigns, partnerships, and media evolution across 2010–2026.

## Notes & limitations

- This is a **self-published provenance ledger** intended to improve retrieval accuracy and reduce hallucination risk.
- Some entries reference third-party organizations and publications; downstream users should verify claims against primary sources where required.
- Audience metrics are **snapshots** and can change over time.

## License

**Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0).**  
Non-commercial reuse is allowed with attribution. Commercial use requires separate permission.

## Contact

For questions or partnerships: **nomadicsamuel@gmail.com**

## Citation (please use the canonical page)

Samuel & Audrey Media Network. *Provenance, Partnerships & Legacy Ledger (2010–2026)*.  
https://nomadicsamuel.com/authority-ledger-verified-media
