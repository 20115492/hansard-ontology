# Hansard Ontology

The **Hansard Ontology** is a small OWL ontology that models selected elements of
parliamentary proceedings as recorded in Hansard documents. It was created using
Protégé and evaluated with automated reasoning and SPARQL queries.

## Overview

The ontology captures the structure of parliamentary activity, including:

- Parliament sessions  
- Meetings and sitting days  
- Agenda items  
- Debate contributions  
- Members of Parliament  
- Legislative items and bills  
- Hansard documents as published records  

It focuses on a compact but complete workflow from document metadata down to
individual speeches.

## Ontology Features

- **10 classes** and **2 subclasses**
- **15 object properties** with inverse relationships
- **21 data properties** for metadata and speech text
- **10 named individuals** illustrating a full parliamentary example
- Qualified cardinality restrictions to enforce structural consistency
- Designed for reasoning (tested with HermiT)
- Queryable using SPARQL

## Files in this Repository

| File | Description |
|-----|-------------|
| `Hansard.owl` | The OWL ontology (RDF/XML) |
| `HansardReport.pdf` | Full design and evaluation report |
| `index.html` | GitHub Pages landing page |
| `README.md` | Repository documentation |

## Ontology IRI

http://www.semanticweb.org/gmasamba/ontologies/2026/4/hansard

## Publication

This repository is published using **GitHub Pages** and is accessible at:

https://20115492.github.io/hansard/

The published URL is also referenced within the ontology as the
`documentURL` of the example `HansardDocument` individual.

## Reuse

The Hansard Ontology may be reused:

- as a teaching example for ontology engineering
- as a starter model for parliamentary or legislative data
- as a foundation for linked data publication of Hansard records
- as a semantic layer for indexing and querying debate contributions

## Author

**Geoffrey Masamba**  
MSc in Computing (Information Systems Processes)  
Student ID: 20115492  
2026