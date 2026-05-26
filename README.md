# Post-Quantum Cryptography for IoT — Research Notes

Personal research notes and literature review for my MCA dissertation.  
Actively updated as I read papers and explore the domain.

## What this is about

Current encryption (RSA, ECC) will be broken by quantum computers.  
Post-Quantum Cryptography (PQC) offers quantum-resistant alternatives —  
but running them on tiny, battery-powered IoT devices is a serious challenge.

This repo documents my journey through the research landscape:
understanding the algorithms, the constraints, and where the open problems are.

## Structure
pqc-iot-research/
├── notes/
│   ├── domain-overview.md       ← core concepts, jargon, algorithms
│   └── paper-summaries/         ← one file per paper read
├── gaps.md                      ← research gaps I'm tracking
└── resources.md                 ← useful papers, links, tools

## Papers Read So Far

| # | Title | Authors | Year | Key Takeaway |
|---|-------|---------|------|--------------|
| 1 | Fortifying Future IoT Security: A Comprehensive Review on Lightweight PQC | Mahdi, Abdullah | 2025 | Survey of lightweight PQC; key gaps: energy efficiency, key size, scalability |

## Key Research Gaps (so far)

- Resource constraints on IoT devices
- Energy efficiency of PQC algorithms
- Key size and bandwidth limitations
- Scalability across large IoT networks
- Hardware acceleration for PQC

## Status

Literature review in progress 