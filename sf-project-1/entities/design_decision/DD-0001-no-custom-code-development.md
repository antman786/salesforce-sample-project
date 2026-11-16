---
aliases: []
data:
  implementation_impact: >-
    All business requirements must be satisfied using standard objects, flows,
    and out-of-the-box Salesforce features.
  problem: >-
    The scope of the Salesforce implementation needs to be defined to ensure
    project delivery within the 10-week timeline and fixed-fee budget,
    preventing uncontrolled growth of complexity.
  rationale: >-
    By relying on standard platform capabilities, the project can maintain a
    predictable delivery schedule and stay within the agreed fixed-fee
    structure.
  recommendation: >-
    Use declarative Salesforce configuration only; custom Apex triggers,
    Lightning Web Components, and Visualforce pages are strictly out of scope.
entity_type: design_decision
id: 'DD-0001: No custom code development'
links:
  - target: COMP-0001
    type: affects_component
  - target: COMP-0002
    type: affects_component
name: 'DD-0001: No custom code development'
sources:
  - asset: >-
      assets/sow/2026-11-16_statement-of-work-sow-salesforce-sales-service-clo.md
    date: '2026-11-16'
    stage: design
version: 1
---

## Consequences
This rules out highly customized UI or complex backend logic that requires programmatic intervention, ensuring maintainability by a standard System Administrator.

## Status
Accepted

## Evidence
- "Custom Apex triggers, Lightning Web Components (LWCs), or Visualforce pages."
