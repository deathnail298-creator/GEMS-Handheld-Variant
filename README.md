# GEMS-Handheld-VariantGEMS Handheld Variant
Overview

The GEMS Handheld Variant defines a handheld, astronaut-operated dust collection interface that routes lunar regolith into an external GEMS unit. The system adds a controlled intake path for surface dust removal without modifying GEMS processing behavior or integrating with life-support systems.

This variant is intended for external or dirty-side use only and operates entirely as a mechanical collection and routing tool. All regolith processing remains the responsibility of the external GEMS unit.

Scope and Intent

This repository is strictly limited to Phase 0 (Permission to Exist) and Phase 1 (Permission to Test).

Included:

Concept definition and architectural boundaries

Failure-tolerant design philosophy

Phase-bounded assumptions and success criteria

Prototype-level testing objectives and validation methods

Explicitly excluded:

Life-support integration

Oxygen production or utilization claims

Performance, throughput, or efficiency guarantees

Mission-critical dependence

Phase 2 or flight-ready development

System Boundary

The GEMS Handheld Variant performs dust capture and sealed routing only. It does not process regolith, store oxygen, or interact with habitat systems.

The external GEMS unit is treated as a black box. No assumptions are made about its internal design, performance, or operational requirements.

Failure Philosophy

All failures are designed to be:

Local to the handheld unit

Non-propagating

Human-recoverable

Safe to abandon without downstream impact

The system may degrade, clog, or become unusable without affecting GEMS or mission operations.

Repository Structure
/docs
  /phase0
    Mission_Definition_and_NonClaims.md
    System_Boundaries_and_Ownership.md
    Architecture_Overview.md
    Failure_Tolerance_Philosophy.md
    Phase0_Assumptions.md
    Phase0_Success_Criteria.md

  /phase1
    Phase1_Objectives.md
    Prototype_Hardware_Definition.md
    Test_Modules.md
    Instrumentation_and_Data.md
    Termination_Kill_Criteria.md
    Phase1_Exit_Conditions.md

  /appendix
    Executive_Contractor_Appendix.md

Status

Phase 0: Complete

Phase 1: Defined and bounded

No Phase 2 work is included or implied

License

This repository is released under a non-commercial open reference license. Commercial use requires a separate license agreement.

See LICENSE for details.

Plain-English Summary

This repository describes a handheld tool that collects lunar dust and routes it into an external GEMS unit without changing how GEMS works. The design is limited to early concept definition and basic testing, avoids life-support or mission-critical claims, and is intended only as an optional, failure-benign add-on.
