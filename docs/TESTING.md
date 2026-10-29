# Testing

Evidence date: October 29, 2026 (America/New_York). These results come from earlier recorded runs. The five-project package refresh reviewed the receipts and original-file hashes; it did not rerun application tests, lint or builds. Tests ran in isolated private copies using existing installed dependencies; no dependency reinstall was performed. The Windows build used .NET SDK 10.0.303.

| Check | Result |
|---|---|
| Release solution build, --no-restore | PASS; 0 warnings and 0 errors |
| Selected xUnit HDR/color suites | 68 passed, 0 failed, 0 skipped |
| Hardware validation | Not rerun; selected tests use fake providers and temporary state |

## Historical evidence

Older handoff reports were used as context, not counted as new test runs.

## Reproducibility and limits

The source is private, so these tests cannot be run from this documentation repository. The owner retains command receipts and redacted logs separately. Tests used fixtures/mocks without production credentials. No database migration, real email or Discord operation was authorized or executed.

Windows and compatible hardware are required. SDR gamma is not universal digital saturation/vibrance. The MHC2 path reports unsupported in the inspected implementation. DDC/CI depends on monitor, connection and driver capabilities. Physical HDR and broad vendor compatibility are not certified. Historical stability observations did not rule out memory/handle growth. No FPS improvement is promised.

A dependency audit is a dated registry observation, not proof of exploitability or a security certification. No coverage percentage is claimed. [Overview](../README.md).
