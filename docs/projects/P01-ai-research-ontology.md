# P01 — AI Research Ontology

## Status
Planning

## Goal
Build a small but rigorous ontology for representing AI research entities and relationships.

## Initial Scope
- Researcher
- Student
- Institution
- Paper
- Dataset
- Model
- Task
- Benchmark
- Method
- Topic

## Candidate Relations
- writes
- affiliatedWith
- studies
- cites
- usesDataset
- evaluatesOn
- addressesTask
- proposesMethod
- hasTopic

## Deliverables
- Competency-question set
- Conceptual model
- OWL ontology
- Example individuals/data
- Reasoning checks
- SHACL shapes
- SPARQL queries
- ADRs for non-trivial modelling decisions
- README/documentation

## Definition of Done — v0.1
- At least 10 competency questions
- At least 20 meaningful classes/properties combined
- At least 3 documented modelling decisions
- Reasoner reports no unintended inconsistency
- At least 5 SHACL validation rules
- At least 10 SPARQL queries answering competency questions
