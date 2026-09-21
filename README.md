# Curriculum Knowledge Graph

This repository contains the curriculum knowledge graph data used in the paper:

**Mining Curriculum Knowledge Graphs to Reveal Hidden Structure in Flexible Degrees**  
Gizem Intepe, Oliver Middleton, and Laurence A. F. Park  
AusDM 2026

The case study represents the Bachelor of Data Science at Western Sydney University, including its core subjects and selected majors and minors.

## Data

The `data` folder contains the extracted graph in JSON format. Files are organised as node and edge files for the degree core and its specialisations.

- `nodes_*.json` — graph nodes, including subjects, specialisations, and related curriculum entities.
- `edges_*.json` — relationships between nodes, including prerequisite and specialisation relationships.

These files contain the curriculum knowledge graph used for the analysis reported in the paper.

