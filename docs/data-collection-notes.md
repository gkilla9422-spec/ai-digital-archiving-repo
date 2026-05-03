# Data Collection Notes

## Overview

This document describes the methodology used to collect and standardize metadata for the AI-Driven Digital Archiving project.

---

## Collection Process

### Step 1 — Archive Selection
Two major public digital archives were selected based on accessibility, metadata availability, and relevance to the project topic:
- **Internet Archive** (archive.org) — selected for its broad collection of labor history documents and open-access publications
- **Library of Congress Digital Collections** (loc.gov/collections) — selected for its structured, high-quality metadata and photographic collections related to labor and social movements

### Step 2 — Item Selection Criteria
Items were selected based on the following criteria:
- Relevance to labor movements, university activism, or social history
- Availability of complete metadata fields (title, creator, date, description, subject)
- Public domain or open-access licensing
- Variety of format types (PDF, JPEG, audio) to allow format analysis

### Step 3 — Metadata Standardization
All metadata was mapped to the **Dublin Core Metadata Element Set** (15 core fields). The following standardization decisions were made:
- Dates were formatted as YYYY-MM-DD where known, or YYYY-01-01 where only the year was available
- Subject fields use semicolon-separated controlled vocabulary terms
- Rights fields reflect the stated license from the source archive
- Identifiers are permanent URLs to the item or collection page

---

## Known Limitations

- Some items link to collection-level URLs rather than item-level permalinks due to archive structure
- Date precision varies — some items only have year-level accuracy
- Subject tags were manually assigned based on item descriptions where archive-provided tags were unavailable

---

## Metadata Field Mapping Reference

| Dublin Core Field | Source Archive Field (Internet Archive) | Source Archive Field (LOC) |
|---|---|---|
| Title | Title | Title |
| Creator | Creator / Author | Creator / Contributor |
| Date | Date | Date |
| Description | Description | Summary / Description |
| Subject | Subject / Tags | Subject Headings |
| Format | Format / Mediatype | Format |
| Identifier | Identifier / URL | URL / Call Number |
| Rights | License | Rights / Reproduction |
| Language | Language | Language |

---

## Tools Used

- Microsoft Excel — initial metadata entry and CSV formatting
- GitHub — version control and repository hosting
- Zenodo — permanent DOI assignment and open-access publication
