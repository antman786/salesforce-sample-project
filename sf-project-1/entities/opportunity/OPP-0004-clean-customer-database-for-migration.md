---
aliases: []
data:
  scope: Data migration process
  timeline: Pre-migration
entity_type: opportunity
id: 'OPP-0004: Clean customer database for migration'
links:
  - target: PP-0002
    type: addresses_pain_point
  - target: P-0003
    type: target_persona
name: 'OPP-0004: Clean customer database for migration'
sources:
  - asset: >-
      assets/transcripts/2026-11-16_transcript-1-project-kick-off-call-raw-export-30-m.md
    date: '2026-11-16'
    stage: opportunities
version: 1
---

## Problem
The current customer database contains significant duplicates and inconsistent naming, complicating data integrity and migration efforts.

## Hypothesized value
If this is addressed, the client will successfully migrate clean customer data to the new system, measured by the completion of deduplication before the data load.

## Evidence
- "One thing I should warn you about now is our legacy customer database is pretty messy. We have got duplicate accounts everywhere"
- "source data cleansing and deduplication sits on Vanguard's plate prior to us loading the files"
