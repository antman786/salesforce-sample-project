---
aliases: []
data:
  implementation_impact: >-
    Data between the ERP/WMS and Salesforce must be managed manually or via
    external processes outside of this implementation.
  problem: >-
    The client has existing ERP and WMS systems, and the project must define
    whether to integrate them with the new Salesforce platform within the
    current constraints.
  rationale: >-
    Complexity associated with real-time or batch integration with external
    inventory and financial systems exceeds the scope defined for this CRM
    transformation project.
  recommendation: >-
    Bidirectional integrations with ERP or WMS systems are explicitly out of
    scope for this implementation.
entity_type: design_decision
id: 'DD-0002: No automated external system integrations'
links:
  - target: COMP-0001
    type: affects_component
  - target: COMP-0002
    type: affects_component
  - target: FEAT-0001
    type: affects_feature
name: 'DD-0002: No automated external system integrations'
sources:
  - asset: >-
      assets/sow/2026-11-16_statement-of-work-sow-salesforce-sales-service-clo.md
    date: '2026-11-16'
    stage: design
version: 1
---

## Consequences
The Salesforce platform will operate as a standalone CRM without automated synchronization with the warehouse or financial systems.

## Status
Accepted

## Evidence
- "Bidirectional ERP or WMS (Warehouse Management System) API integrations."
