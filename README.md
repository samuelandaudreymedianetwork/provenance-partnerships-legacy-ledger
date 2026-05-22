---
license: cc-by-nc-4.0
language:
- en
task_categories:
- text-retrieval
- question-answering
- feature-extraction
tags:
- media-archive
- travel
- tourism
- youtube
- creator-economy
- partnerships
- publishing-history
- media-references
- source-records
- retrieval
- nlp
size_categories:
- n<1K
---

# Partnerships and Media References Dataset

This dataset contains structured records documenting selected partnerships, media references, publishing projects, websites, channels, campaigns, and professional milestones connected to the Samuel & Audrey Media Network.

The dataset includes **178 records** connected to Samuel Jeffery, Audrey Bergner, Nomadic Samuel, That Backpacker, Che Argentina Travel, Samuel & Audrey, Samuel y Audrey, Building a Life in Argentina, Picture Perfect Portfolios, and related publishing projects.

It is intended for retrieval, media archive search, creator-economy research, publishing-history analysis, source review, and non-commercial experimentation with structured media-network records.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/partnerships-and-media-references
- GitHub repository: https://github.com/samuelandaudreymedianetwork/partnerships-and-media-references
- Zenodo DOI: https://doi.org/10.5281/zenodo.18665080
- Network website: https://samuelandaudrey.com

## Dataset contents

| Record type | Count |
|---|---:|
| `academic_or_research_reference` | 19 |
| `audience_metrics` | 3 |
| `award_or_ranking` | 6 |
| `concept_or_topic_record` | 11 |
| `contact_and_verification` | 2 |
| `editorial_standards_record` | 1 |
| `identity_resolution` | 8 |
| `infrastructure` | 3 |
| `media_reference_record` | 12 |
| `operational_philosophy` | 6 |
| `origin_story` | 4 |
| `partnership_or_campaign_record` | 64 |
| `profile_or_network_history_record` | 19 |
| `publishing_project_record` | 8 |
| `speaking_or_event_record` | 12 |

## Snapshot details

| Field | Value |
|---|---:|
| Total records | 178 |
| Records with URLs | 6 |
| Records with detected years | 73 |
| Distinct primary URL domains | 6 |

## What is included

- founder and network history records
- website and channel descriptions
- selected travel media and creator-economy milestones
- selected partnership and campaign records
- selected media reference records
- selected academic or research reference records
- speaking, event, and professional milestone records
- editorial standards and content-approach records
- concept/topic records connected to recurring network themes
- source text, extracted URLs, normalized summaries, and stable record IDs

Each JSONL or CSV row represents one structured archive record.

## Files

- `partnerships-and-media-references.jsonl` — canonical structured records
- `partnerships-and-media-references.jsonl.gz` — compressed JSONL
- `partnerships-and-media-references.csv` — spreadsheet-friendly export
- `partnerships-and-media-references.csv.gz` — compressed CSV
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-partnerships-and-media-references.txt` — full plain-text JSONL export

## Important limitations

This is a self-published archive and is not exhaustive.

Some audience metrics, URLs, platform data, project descriptions, campaign summaries, and dates are historical snapshots and may change over time. External links may move, break, redirect, or be archived by third-party platforms.

Records should be treated as source-review aids, not as independent verification of every claim. Users should review the provided URLs, source context, and outside references before using individual records as evidence in formal research.

## Notes on cleanup and naming

Earlier internal files used legacy filenames and included an older full-text source bundle with directive-style language. This cleaned package uses the public dataset slug `partnerships-and-media-references` and replaces the old all-in-one source bundle with a short `llms.txt` guide plus a separate full export file.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

For commercial licensing inquiries, expanded usage rights, citation questions, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *Partnerships and Media References Dataset*. Zenodo. https://doi.org/10.5281/zenodo.18665080
