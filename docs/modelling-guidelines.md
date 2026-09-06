# Modelling Guidelines

## 1. Start from questions, not classes
Every modelling change should be motivated by one or more competency questions.

## 2. Separate identity from role
Ask whether a class expresses what an entity essentially is or a contingent role it may gain or lose.

## 3. Prefer explicit semantics
Record why a relation, restriction, equivalence, disjointness axiom, or mapping exists.

## 4. Avoid premature complexity
Use the least expressive model that still answers the competency questions and supports required inference.

## 5. Test assumptions
For each important modelling choice, create at least one example, non-example, and edge case.

## 6. Record decisions
Non-trivial modelling choices belong in an ADR under `docs/decisions/`.

## 7. Validate continuously
Use reasoners for logical consistency, SHACL for data constraints, and SPARQL/tests for competency-question coverage.

## 8. Keep provenance
When a modelling choice comes from a paper, standard, domain expert, or dataset, record the source.
