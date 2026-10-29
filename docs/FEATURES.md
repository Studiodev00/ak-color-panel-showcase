# Verified features

- Per-monitor SDR gamma/RGB adjustment, intensity control, original-state capture and restoration.
- Global/game profiles, executable associations and session-driven application/restoration.
- HDR state detection and safeguards for unsupported display paths.
- Conditional DDC/CI brightness/contrast and ICC association; hardware support is required.
- Windows appearance settings and external performance HUD infrastructure.

## Evidence level

These capabilities were found in the private source and related local records. Execution receipts exist for the checks listed in [Testing](TESTING.md); this package refresh reviewed those records without rerunning the applications. Presence in code, enabled configuration and live operation are different claims.

## Limits

Windows and compatible hardware are required. SDR gamma is not universal digital saturation/vibrance. The MHC2 path reports unsupported in the inspected implementation. DDC/CI depends on monitor, connection and driver capabilities. Physical HDR and broad vendor compatibility are not certified. Historical stability observations did not rule out memory/handle growth. No FPS improvement is promised.

## Visual evidence

Owner-approved historical development screenshots in Portuguese. They predate the current internal beta; visible controls do not establish hardware support. Preset values are part of the specifically approved images.

[Overview and screenshots](../README.md).
