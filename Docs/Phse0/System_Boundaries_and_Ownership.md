System Boundaries and Ownership
System Boundary Definition

The GEMS Handheld Variant is strictly bounded as a dust capture and routing interface. Its functional responsibility ends at the point where captured regolith is delivered to an external GEMS intake.

The handheld unit:

Captures dust from external surfaces

Routes captured material through a sealed conduit

Does not perform any processing, storage, or transformation of regolith

All regolith processing, conversion, storage, or utilization functions are outside the boundary of this system and remain the responsibility of the external GEMS unit.

External Interfaces

The only external interface defined by this system is a mechanical routing connection to an existing GEMS intake port.

This interface:

Assumes no modification to GEMS internals

Does not impose performance or flow requirements on GEMS

Does not alter GEMS operating modes or control logic

The GEMS system is treated as a black box. No assumptions are made about its internal design, performance, or downstream use of collected material.

Ownership and Responsibility

Ownership and responsibility are explicitly separated as follows:

Handheld Unit Ownership
Responsibility for design, operation, failure, and abandonment of the handheld unit resides entirely with the handheld system.

GEMS System Ownership
Responsibility for processing behavior, outputs, safety, and downstream use of regolith resides entirely with the GEMS system.

No shared ownership, shared control, or shared failure responsibility exists between the handheld unit and GEMS.

Explicit Exclusions

The system boundary explicitly excludes:

Life-support systems

Habitat interior systems

EVA safety systems

Power, control, or data interfaces

Environmental sealing beyond dust containment

Operational dependency or mission-critical status

The handheld unit may be removed, disabled, or abandoned without consequence to other systems.

Boundary Enforcement

Any change that:

Requires modification of GEMS internals

Introduces operational dependence

Alters responsibility or certification ownership

Expands into life-support or habitat systems

is considered out of scope and invalidates this system definition.

Plain-English Summary

This page defines the handheld tool as responsible only for collecting dust and delivering it to an existing GEMS intake, with all processing left to GEMS. The two systems are separate, have no shared responsibilities, and can operate independently without affecting mission safety.
