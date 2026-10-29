# Architecture

The WPF shell and ViewModels call application coordinators through shared contracts. Hardware-specific color engines and Windows adapters return typed applied/unsupported/failed results. JSON repositories preserve profiles and recovery state. Background coordinators handle cancellation and UI dispatch.

```text
WPF UI / ViewModels → coordinators → shared contracts
Contracts → Windows color adapters / profile storage / telemetry
Operation results → UI state and recovery
```

## Design rationale

Capability-aware adapters avoid presenting every slider as an effective hardware operation. Original-state backups and readback support reversible changes. Cancellation and serialized updates help keep rapid UI interaction consistent.

## Boundaries

Windows and compatible hardware are required. SDR gamma is not universal digital saturation/vibrance. The MHC2 path reports unsupported in the inspected implementation. DDC/CI depends on monitor, connection and driver capabilities. Physical HDR and broad vendor compatibility are not certified. Historical stability observations did not rule out memory/handle growth. No FPS improvement is promised.

The diagram is an explanatory abstraction of inspected source, not a deployment topology or operational runbook. [Overview](../README.md).
