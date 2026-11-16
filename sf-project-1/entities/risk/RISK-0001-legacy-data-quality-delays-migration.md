---
aliases: []
data:
  likelihood: high
  mitigation_strategy: >-
    Priya will send an Excel matching checklist and formulas to help identify
    duplicates before the load.
  severity: medium
entity_type: risk
id: 'RISK-0001: Legacy data quality delays migration'
links:
  - target: PERSON-0006
    type: owner
  - target: SOWD-0005
    type: threatens_deliverable
name: 'RISK-0001: Legacy data quality delays migration'
sources:
  - asset: >-
      assets/transcripts/2026-11-16_transcript-1-project-kick-off-call-raw-export-30-m.md
    date: '2026-11-16'
    stage: risks
version: 1
---

## Description
The client's legacy customer database contains many duplicate accounts and inconsistent data. If this data is not cleaned prior to the migration, it will cause issues or delays during the loading of records into Salesforce.

## Evidence
- "One thing I should warn you about now is our legacy customer database is pretty messy. We have got duplicate accounts everywhere"
- "Under the SOW, source data cleansing and deduplication sits on Vanguard's plate prior to us loading the files"
