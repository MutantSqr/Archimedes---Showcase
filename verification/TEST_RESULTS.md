# Verification Record

## Test run

- Date: 2026-08-19
- Python test framework: pytest 8.4.2
- Result: **PASS**
- Tests: **303 passed**
- Failures: **0**

## Duncan adversarial run

- Creator: Bowser / `MutantSqr`
- Purpose: testing AI and software verification suite for testing other AI systems and programs
- Duncan version: 0.2.0
- Baseline suite: **PASS**
- Confirmed findings: **0**
- Suspected findings: **0**
- Informational false positives: **0**

Duncan first runs the tested project's own baseline suite, then applies adversarial probes that look for behavioral and security failures beyond ordinary unit-test success. Duncan is a separate project created by Bowser; it is not a renamed pytest component or a third-party commercial scanner.

## Scope statement

The test suite covers routing, planning, approvals, permissions, integrity, memory, audit behavior, coding-tool confinement, cancellation, runtime state, Windows voice adapters, macOS voice adapters, portable voice identity, checksum-verified voice setup, hands-free turn detection, cancellable speech playback, platform selection, text and desktop interfaces, guarded single-device handoff behavior, and automatic lease renewal.

Hardware-specific microphone permissions and audio-device behavior require a live check on each target computer and are not represented as CI-verified.
