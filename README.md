# Google Quantum AI (google-quantum-ai)
Google Quantum AI is Google's quantum-computing research and engineering arm, building superconducting quantum processors (most recently the Willow chip with below-threshold quantum error correction) and the open software stack that runs on them. The team operates the Quantum Computing Service via the Quantum Engine API (`quantum.googleapis.com`, `v1alpha1`), accessed primarily through the `cirq-google` Python client. Google Quantum AI also stewards a portfolio of Apache 2.0 open-source quantum software — Cirq, qsim, OpenFermion, Stim, Qualtran, TensorFlow Quantum, ReCirq, Tesseract, and Unitary — published under the `quantumlib` GitHub organisation, plus the Willow Early Access Program for sponsored researcher access to current hardware.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/google-quantum-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Quantum Computing, Quantum, Hardware, NISQ, Error Correction, Willow, Sycamore, Cirq, Quantum Engine, Superconducting Qubits, Google Cloud

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Hardware & Software

| Component | Type | Notes |
|---|---|---|
| Willow | Quantum Processor | Current-generation superconducting chip; first below-threshold surface-code QEC. |
| Sycamore-class | Quantum Processor | Earlier production hardware (e.g., `rainbow`). |
| Quantum Virtual Machine | Simulator | Includes the `willow_pink` noise-aware target shipped in Cirq v1.6. |
| Cirq | SDK | Apache 2.0 Python framework for NISQ circuits. v1.6.x (Aug 2025). |
| qsim | Simulator | High-performance C++ / CUDA state-vector simulator. |
| OpenFermion | Library | Quantum chemistry and materials simulation. |
| Stim | Simulator | Fast stabilizer-circuit simulator for QEC research. |
| Qualtran | Library | Fault-tolerant algorithm authoring and resource estimation. |
| TensorFlow Quantum | Library | Hybrid quantum-classical ML. |
| ReCirq | Examples | Reproducible Cirq research experiments. |
| Tesseract Decoder | Tool | Search-based decoder for QEC. |
| Unitary | SDK | Quantum behaviours for games and education. |

## APIs

### Google Quantum Engine API
REST/gRPC surface (`quantum.googleapis.com`, `google.cloud.quantum.v1alpha1.QuantumEngineService`) for uploading quantum programs, running them as jobs on Google's quantum processors, inspecting device specs and calibrations, and reserving processor time. Cirq's `cirq_google.Engine` is the canonical client.

**Human URL:** [https://quantumai.google/cirq/google/engine](https://quantumai.google/cirq/google/engine)

- [Documentation — Engine](https://quantumai.google/cirq/google/engine)
- [Documentation — Concepts](https://quantumai.google/cirq/google/concepts)
- [Documentation — Access](https://quantumai.google/cirq/google/access)
- [OpenAPI](openapi/quantum-engine-api-openapi.yml)
- [JSON Schema — Program](json-schema/google-quantum-ai-quantum-program-schema.json)
- [JSON Schema — Job](json-schema/google-quantum-ai-quantum-job-schema.json)
- [JSON-LD Context](json-ld/google-quantum-ai-context.jsonld)
- [Naftiko Capability — Programs](capabilities/quantum-engine-programs.yaml)
- [Naftiko Capability — Jobs](capabilities/quantum-engine-jobs.yaml)
- [Naftiko Capability — Processors](capabilities/quantum-engine-processors.yaml)
- [Naftiko Capability — Calibrations](capabilities/quantum-engine-calibrations.yaml)
- [Naftiko Capability — Reservations](capabilities/quantum-engine-reservations.yaml)

### Cirq
Apache 2.0 Python framework for NISQ circuit design, simulation, and execution. Subpackage `cirq-google` provides the typed Quantum Engine client.

- [Documentation](https://quantumai.google/cirq)
- [Source Code](https://github.com/quantumlib/Cirq)
- [PyPI](https://pypi.org/project/cirq/)
- [API Reference](https://quantumai.google/reference/python/cirq/all_symbols)

### qsim
High-performance state-vector simulator integrated with Cirq via `qsimcirq`.

- [Documentation](https://quantumai.google/qsim)
- [Source Code](https://github.com/quantumlib/qsim)

### OpenFermion
Quantum chemistry and materials science library.

- [Documentation](https://quantumai.google/openfermion)
- [Source Code](https://github.com/quantumlib/OpenFermion)

### Stim
Fast stabilizer-circuit simulator used in QEC research and Willow experiments.

- [Source Code](https://github.com/quantumlib/Stim)

### Qualtran
Library of fault-tolerant quantum algorithm Bloqs with resource estimation.

- [Source Code](https://github.com/quantumlib/qualtran)

### TensorFlow Quantum
Hybrid quantum-classical machine learning library.

- [Documentation](https://www.tensorflow.org/quantum)
- [Source Code](https://github.com/tensorflow/quantum)

### ReCirq
Collection of reproducible Cirq research experiments.

- [Source Code](https://github.com/quantumlib/ReCirq)

### Tesseract Decoder
Search-based maximum-likelihood decoder paired with Stim.

- [Source Code](https://github.com/quantumlib/tesseract-decoder)

### Unitary
API library for adding quantum behaviours to games and educational software.

- [Source Code](https://github.com/quantumlib/unitary)

## Examples

- [Create Program](examples/quantum-engine-create-program-example.json)
- [Create Job](examples/quantum-engine-create-job-example.json)
- [List Processors](examples/quantum-engine-list-processors-example.json)

## Operational artifacts

- [Plans / Pricing (sponsored access)](plans/google-quantum-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/google-quantum-ai-rate-limits.yml)
- [FinOps](finops/google-quantum-ai-finops.yml)
- [Vocabulary](vocabulary/google-quantum-ai-vocabulary.yml)
- [Spectral Rules](rules/google-quantum-ai-rules.yml)

## Programs

- [Willow Early Access Program](https://quantumai.google/willowearlyaccess) — proposal-based access to the Willow chip. 2026 intake deadline 2026-05-15; selection by 2026-07-01.
- [Quantum Error Correction on Coursera](https://www.coursera.org/learn/quantum-error-correction) — Google Quantum AI's hands-on QEC course.

## Authentication

- OAuth 2.0 via Google Cloud Application Default Credentials (`gcloud auth application-default login`).
- Scope: `https://www.googleapis.com/auth/cloud-platform`.
- Project must have the Quantum Engine API enabled and billing attached.
- Each user must be on Google Quantum AI's approved-user list (sponsorship required).

## Source URLs

- [Google Quantum AI Portal](https://quantumai.google/)
- [Open Source Software](https://quantumai.google/software)
- [Roadmap](https://quantumai.google/roadmap)
- [Research](https://quantumai.google/research)
- [Our Quantum Computer](https://quantumai.google/quantumcomputer)
- [quantumlib GitHub Organization](https://github.com/quantumlib)
- [Cirq Release Notes](https://github.com/quantumlib/Cirq/releases)
- [Google Cloud Status](https://status.cloud.google.com/)
