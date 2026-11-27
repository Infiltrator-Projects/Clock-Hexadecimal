# Hexadecimal clock — model

**Stable ID:** `hexadecimal` · **Kind:** `clock`

## Defined behaviour

Exact hexadecimal partition of the civil day for any representable input instant.

**Historical interpretation:** Mathematical day/clock display.

**Fidelity boundary:** Modern representation, not a claimed historical practice.

This resource owns its clock rendering and next visible update boundary. The clock's display mode must not be confused with Common's elapsed-duration projection. Required location inputs must be validated, and unsupported solar events must not be fabricated. Model accuracy must not be overstated beyond this documented interpretation.

## Implementation status

This repository contains the independent provider, build configuration and tests; current package tools are supplied by the pinned Common submodule. Historical extraction records remain in SOURCE.md.

## Source documentation

[Calendar's clock model matrix](https://github.com/Infiltrator-Projects/Calendar/blob/main/docs/MODELS.md) · [Historical fidelity audit](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_HISTORICAL_FIDELITY.md) · [Runtime ABI](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_PROVIDERS.md)

## Source provenance

The original Common 1.19.78 extraction is historical evidence. Current builds use the authoritative pinned Common submodule. See [source record](../SOURCE.md) and [recorded results](../VALIDATION-RESULTS.json). The operational model, worked examples and limitations are maintained in [GUIDE.json](GUIDE.json).
