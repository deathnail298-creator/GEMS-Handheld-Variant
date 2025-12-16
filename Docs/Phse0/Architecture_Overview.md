Architecture Overview
System Composition

The GEMS Handheld Variant is a mechanically simple, human-operated dust capture and routing tool. The system is composed entirely of passive or manually operated elements and contains no processing logic, electronics, or autonomous behavior.

The architecture is intentionally limited to ensure failure-benign behavior and to prevent coupling with life-support or mission-critical systems.

Subsystem Overview
Intake Head

Hand-applied to dusty external surfaces such as suits, tools, or exterior hardware

Provides mechanical disturbance to mobilize surface regolith

Geometry favors localized capture and containment rather than precision or throughput

Capture / Containment Volume

Located immediately downstream of the intake head

Serves as a transient holding volume to reduce immediate re-aerosolization

Performs no sorting, processing, or chemical interaction

Sealed Routing Conduit

Provides a continuous sealed path from the handheld unit to an external GEMS intake

May be flexible or semi-rigid

Designed to tolerate particulate flow without fine alignment or cleanliness requirements

Mechanical Interfaces and Seals

Passive joints and seals between intake head, containment volume, conduit, and GEMS interface

Designed for containment adequacy rather than pressure performance

No active locking, control, or sensing mechanisms are required

Human Interface

Grip and form factor suitable for gloved operation

No controls beyond simple manual handling

No indicators, displays, or feedback systems

Interface with GEMS

The GEMS Handheld Variant interfaces only with an existing external GEMS intake port.

No modification of GEMS internals is assumed or required

No assumptions are made regarding GEMS performance, flow rate, or processing behavior

The handheld system imposes no operational requirements on GEMS

GEMS is treated as a black-box downstream consumer of collected material.

Architectural Constraints

The architecture explicitly enforces the following constraints:

No life-support integration

No power, data, or control interfaces

No operational dependency

No autonomous behavior

No performance or throughput guarantees

Any architectural change that violates these constraints is considered out of scope.

Plain-English Summary

This page describes a simple handheld tool made of mechanical parts that collect dust and route it through a sealed path into an existing GEMS intake. The design avoids electronics, processing, or system coupling and keeps all responsibility for regolith processing inside GEMS.
