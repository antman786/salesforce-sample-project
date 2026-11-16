---
aliases: []
data:
  frequency: frequently
  severity: medium
entity_type: pain_point
id: 'PP-0002: Legacy customer database contains widespread duplicates'
links:
  - target: P-0003
    type: affects_persona
  - target: OPP-0004
    type: relates_to_opportunity
name: 'PP-0002: Legacy customer database contains widespread duplicates'
sources:
  - asset: >-
      assets/transcripts/2026-11-16_transcript-1-project-kick-off-call-raw-export-30-m.md
    date: '2026-11-16'
    stage: pain_points
version: 1
---

## Description
The legacy customer database is messy, containing duplicate accounts and inconsistent addresses for the same parent company. This complicates data migration and requires manual intervention to identify the correct billing entity.

## Current workaround
The team will be provided with an Excel matching checklist and formulas to flag duplicates to avoid manual review of ten thousand rows.

## Evidence
- "One thing I should warn you about now is our legacy customer database is pretty messy. We have got duplicate accounts everywhere"
