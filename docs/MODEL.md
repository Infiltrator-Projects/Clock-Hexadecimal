# Hexadecimal clock — model

**Stable ID:** `hexadecimal` · **Kind:** `clock`

## Defined behaviour

Exact hexadecimal partition of the civil day for any representable input instant.

**Historical interpretation:** Mathematical day/clock display.

**Fidelity boundary:** Modern representation, not a claimed historical practice.

This resource owns its clock rendering and next visible update boundary. The clock's display mode must not be confused with Common's elapsed-duration projection. Required location inputs must be validated, and unsupported solar events must not be fabricated. Model accuracy must not be overstated beyond this documented interpretation.

## Implementation status

The source, tests and combined package still belong to [Libraries/Common](https://github.com/Infiltrator-Projects/Libraries/tree/main/resources/temporal). This repository documents the independent `.so` resource that is intended to be migrated; it does **not** claim a working standalone installer or release.

## Source documentation

[Calendar's clock model matrix](https://github.com/Infiltrator-Projects/Calendar/blob/main/docs/MODELS.md) · [Historical fidelity audit](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_HISTORICAL_FIDELITY.md) · [Runtime ABI](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_PROVIDERS.md)
