# Archimedes — Public Engineering Showcase

Archimedes is a local, voice-first AI assistant designed and developed by Bowser (`MutantSqr`). It combines conversational assistance with guarded task execution, observable activity, persistent local memory, and explicit human approval before protected actions.

This repository is intentionally a **verification showcase**, not the Archimedes source distribution. The working implementation and protected core remain in a private repository.

## Verified capabilities

- Local Ollama model support
- Windows and macOS voice interfaces
- Visible terminal and desktop activity interfaces
- Conversation/task separation
- Plan review before execution
- Action-specific approval for protected operations
- Confined coding workspace
- Persistent local memory and append-only audit records
- Cooperative task cancellation
- Protected-core integrity verification
- Single-active-device handoff design for Home Base and Neo
- Advisory AI collaboration without delegated execution authority

## Independent test evidence

| Verification | Result |
|---|---:|
| Pytest suite | 288 passed |
| Duncan baseline | PASS |
| Duncan confirmed findings | 0 |
| Duncan suspected findings | 0 |

See [verification/TEST_RESULTS.md](verification/TEST_RESULTS.md) for the recorded test run and [ARCHITECTURE.md](ARCHITECTURE.md) for the public system overview.

## What is Duncan?

**Duncan is a testing AI and software verification suite created by Bowser (`MutantSqr`).** Duncan is designed to test other AI systems and conventional software projects. It runs the target project's normal test suite first, then applies adversarial probes intended to expose unsafe execution paths, state guard bypasses, and other failures that ordinary happy-path testing may miss.

For this verification run, Duncan independently executed Archimedes' full pytest suite and then ran its current adversarial probe set. The baseline passed with 288 tests, and Duncan reported no confirmed or suspected findings.

## Ownership and source access

Copyright © 2026 Bowser / MutantSqr. All rights reserved.

No license is granted to copy, redistribute, reverse engineer, or create derivative implementations from private Archimedes materials. This showcase contains descriptions and verification evidence only.
