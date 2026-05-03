# AI-Driven Digital Archiving: Metadata Trends Repository

## Project Overview

This repository contains metadata collected from public digital archives as part of a study on AI-driven digital archiving systems and metadata trends. The project examines how major digital archives structure, classify, and describe their collections, and explores the role of artificial intelligence in automating metadata generation and organization.

**Project Topic:** AI-Driven Digital Archiving Systems: A Study of Information Organization and Metadata Trends  
**Course:** Information Science — Digital Archiving  
**Repository Type:** Open-Access Research Dataset  

---

## Repository Structure

```
ai-digital-archiving-repo/
│
├── README.md                  ← Project overview and documentation
│
├── data/                      ← All collected metadata (organized by source archive)
│   ├── internet-archive/      ← Items collected from the Internet Archive
│   │   └── metadata.csv
│   └── library-of-congress/   ← Items collected from the Library of Congress
│       └── metadata.csv
│
└── docs/                      ← Project documentation and analysis notes
    └── data-collection-notes.md
```

### Two-Level Organization

The repository is organized into **two levels**:

1. **Top Level — `data/`**: Contains all metadata collected across archives, representing the full project collection.
2. **Sub-Level — Archive-Specific Folders**: Items are divided by source archive (`internet-archive/` and `library-of-congress/`) to allow direct comparison of how different institutions structure their metadata.

---

## Metadata Fields (Dublin Core Standard)

All metadata files use the following fields based on the Dublin Core Metadata Element Set:

| Field | Description |
|---|---|
| Title | Name of the digital item |
| Creator | Author, creator, or originating organization |
| Date | Date of creation or publication |
| Description | Brief summary of the item's content |
| Subject | Keywords or subject tags |
| Format | File format of the digital object |
| Identifier | Unique URL or ID for the item |
| Source | Name of the digital archive |
| Rights | License or access rights |
| Language | Language of the content |

---

## Sources

- **Internet Archive** — https://archive.org
- **Library of Congress Digital Collections** — https://www.loc.gov/collections

---

## Research Questions

1. How do different digital archives structure and apply metadata to their collections?
2. What role does AI play in automating metadata generation and classification?
3. What metadata trends emerge when comparing collections across institutions?

---

## License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material for any purpose, provided appropriate credit is given.
