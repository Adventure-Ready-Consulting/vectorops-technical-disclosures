# VectorOPS v1.0 Demonstration Evidence

This folder accompanies **VectorOPS Technical Disclosure v1.0** and contains sanitized demonstration evidence derived from an LCSAR training video that was publicly available on YouTube when this package was prepared:

<https://www.youtube.com/watch?v=UoWdR_O4nJg&t=7s>

## Contents

- `VectorOPS-Technical-Disclosure-v1.0.pdf` - the fixed technical disclosure.
- `LCSAR-Mountain-Color.mission.db` - a sanitized SQLite demonstration database containing detection events, staged AI results, Investigation AI records, and performance records.
- `aiScan/` - one detailed AI example image and a normalized result file.
- `aiScan/investigation_runs/` - normalized Investigation AI result examples for event 900.
- `quiltAI/` - one Quilt AI composite image, sanitized input metadata, and a normalized result file.
- `SHA256SUMS.txt` - SHA-256 checksums for every other file in this folder.

## Sanitization

The package intentionally removes or replaces:

- Local Windows usernames and absolute filesystem paths
- Provider response identifiers
- Billing, token-usage, cache, service-tier, and request-envelope metadata
- Machine-specific source and repository paths
- A UI screenshot that visibly contained a local playback path

The normalized JSON files retain the substantive model output, model identifier, result type, and creation time. The database retains the demonstration results while converting machine-specific file references to relative demonstration paths.

No production source code, credentials, API keys, client information, or private mission data are included.

## Source and Scope

The imagery originated from the public LCSAR training video linked above. The included database is demonstration evidence, not a complete copy of the source video or all generated image artifacts. Some relative paths in the database therefore identify artifacts that are not included in this package.

## Authors and Inventors

- David Boyce
- Laetitia Gerard

Adventure Ready Consulting

## Rights and Licensing

Copyright © 2026 David Boyce and Laetitia Gerard. All rights reserved.

These materials are published to document VectorOPS systems and methods. Public availability does not grant any patent, copyright, trademark, source-code, or other license except where a specific file expressly states otherwise.

