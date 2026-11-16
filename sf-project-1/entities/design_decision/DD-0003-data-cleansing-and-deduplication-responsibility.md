---
aliases: []
data:
  alternatives:
    - Implementation partner handles deduplication during the data load
  implementation_impact: >-
    The client must clean their data and use provided Excel matching checklists
    and formulas to identify duplicates before the migration can proceed.
  problem: >-
    Legacy customer data is messy and contains duplicates, requiring a decision
    on whether the implementation partner or the client performs the cleaning
    before migration.
  rationale: >-
    Only the client team knows which versions of customer records are the actual
    billing entities.
  recommendation: >-
    Vanguard Logistics is responsible for performing source data cleansing and
    deduplication prior to loading the files into Salesforce.
entity_type: design_decision
id: 'DD-0003: Data cleansing and deduplication responsibility'
links:
  - target: COMP-0001
    type: affects_component
name: 'DD-0003: Data cleansing and deduplication responsibility'
sources:
  - asset: >-
      assets/transcripts/2026-11-16_transcript-1-project-kick-off-call-raw-export-30-m.md
    date: '2026-11-16'
    stage: design
version: 1
---

## Consequences
This ensures the integrity of the data in the new system but adds preparation work to the client's team.

## Status
Accepted

## Evidence
- "Under the SOW, source data cleansing and deduplication sits on Vanguard's plate prior to us loading the files, mostly because only your team knows which version of Acme Logistics is the real billing entity."
