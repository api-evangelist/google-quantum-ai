# Google Quantum AI (google-quantum-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Google Quantum AI is Google's quantum-computing research and engineering arm, building superconducting quantum processors (most recently the Willow chip with below-threshold quantum error correction) and the open software stack that runs on them. The team operates the Quantum Computing Service via the Quantum Engine API (quantum.googleapis.com, v1alpha1), accessed primarily through the cirq-google Python client. Google Quantum AI also stewards a portfolio of Apache 2.0 open-source quantum software — Cirq, qsim, OpenFermion, Stim, Qualtran, TensorFlow Quantum, ReCirq, Tesseract, and Unitary — published under the quantumlib GitHub organisation, plus the Willow Early Access Program for sponsored researcher access to current hardware.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-quantum-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-quantum-ai/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Quantum Computing
- Quantum
- Hardware
- NISQ
- Error Correction
- Willow
- Sycamore
- Cirq
- Quantum Engine
- Superconducting Qubits
- Google Cloud

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Google Quantum Engine API

The Quantum Engine API (quantum.googleapis.com, v1alpha1) lets approved Google Cloud projects upload quantum circuits as programs, run them as jobs on Google's superconducting quantum processors (Willow, Sycamore-class), inspect device specifications and calibrations, and reserve processor time. The canonical client is the cirq-google Python package (cirq_google.Engine), which wraps the gRPC service exposed by google.cloud.quantum.v1alpha1.QuantumEngineService. Authentication uses Google Cloud Application Default Credentials and standard IAM; access requires Google sponsorship plus inclusion on the approved-user list.

- **Human URL:** [https://quantumai.google/cirq/google/engine](https://quantumai.google/cirq/google/engine)
- **Base URL:** `https://quantum.googleapis.com`

#### Tags

- Quantum Computing
- Quantum Engine
- Google Cloud
- Hardware
- NISQ

#### Properties

- [Documentation](https://quantumai.google/cirq/google/engine)
- [Documentation](https://quantumai.google/cirq/google/concepts)
- [Documentation](https://quantumai.google/cirq/google/access)
- [Documentation](https://quantumai.google/reference/python/cirq_google/engine/Engine)
- [OpenAPI](openapi/quantum-engine-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-quantum-ai-quantum-program-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/google-quantum-ai-quantum-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/google-quantum-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cirq

Cirq is an Apache 2.0 Python framework for designing, manipulating, simulating, and executing Noisy Intermediate-Scale Quantum (NISQ) circuits. Cirq is the canonical client library for Google's Quantum Engine, with cirq-google providing typed access to programs, jobs, processors, reservations, and calibrations. Cirq v1.6.x supports Python 3.11+ and ships dedicated subpackages for AQT, IonQ, Pasqal, and Google hardware backends.

- **Human URL:** [https://quantumai.google/cirq](https://quantumai.google/cirq)

#### Tags

- Quantum Computing
- SDK
- Python
- NISQ
- Open Source

#### Properties

- [Documentation](https://quantumai.google/cirq)
- [Source Code](https://github.com/quantumlib/Cirq)
- [Package U R L](https://pypi.org/project/cirq/)
- [Documentation](https://quantumai.google/reference/python/cirq/all_symbols)
- [Getting Started](https://quantumai.google/cirq/start/install)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### qsim

qsim is a high-performance C++ state-vector simulator with a Python (qsimcirq) binding that plugs directly into Cirq. It is optimised for AVX/AVX-512, CUDA, and cuQuantum backends and is the default classical engine for benchmarking Cirq circuits at scales of 30+ qubits before submitting to hardware.

- **Human URL:** [https://quantumai.google/qsim](https://quantumai.google/qsim)

#### Tags

- Quantum Computing
- Simulation
- Performance
- Open Source

#### Properties

- [Documentation](https://quantumai.google/qsim)
- [Source Code](https://github.com/quantumlib/qsim)
- [Package U R L](https://pypi.org/project/qsimcirq/)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenFermion

OpenFermion is an Apache 2.0 library for translating quantum chemistry and materials science problems (electronic structure, fermionic operators, second quantisation) into quantum circuits suitable for Cirq and other backends. Plugin packages (openfermion-pyscf, openfermion-psi4) bridge to classical chemistry stacks.

- **Human URL:** [https://quantumai.google/openfermion](https://quantumai.google/openfermion)

#### Tags

- Quantum Computing
- Chemistry
- Materials Science
- Open Source

#### Properties

- [Documentation](https://quantumai.google/openfermion)
- [Source Code](https://github.com/quantumlib/OpenFermion)
- [Package U R L](https://pypi.org/project/openfermion/)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stim

Stim is a fast stabilizer-circuit simulator and detector-error-model toolchain that underpins Google Quantum AI's quantum error-correction work, including the Willow surface-code experiments. It exposes Python and C++ APIs and pairs with PyMatching and Tesseract decoders.

- **Human URL:** [https://github.com/quantumlib/Stim](https://github.com/quantumlib/Stim)

#### Tags

- Quantum Computing
- Error Correction
- Stabilizer
- Open Source

#### Properties

- [Source Code](https://github.com/quantumlib/Stim)
- [Package U R L](https://pypi.org/project/stim/)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qualtran

Qualtran provides abstractions (Bloqs) for expressing, decomposing, and resource-estimating fault-tolerant quantum algorithms. It is Google Quantum AI's framework for reasoning about future error-corrected workloads on hardware beyond Willow.

- **Human URL:** [https://github.com/quantumlib/qualtran](https://github.com/quantumlib/qualtran)

#### Tags

- Quantum Computing
- Algorithms
- Resource Estimation
- Open Source

#### Properties

- [Source Code](https://github.com/quantumlib/qualtran)
- [Package U R L](https://pypi.org/project/qualtran/)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TensorFlow Quantum

TensorFlow Quantum (TFQ) is a hybrid quantum-classical machine learning library that integrates Cirq circuits as differentiable layers inside TensorFlow/Keras pipelines. Maintained jointly by Google Quantum AI and the TensorFlow team.

- **Human URL:** [https://www.tensorflow.org/quantum](https://www.tensorflow.org/quantum)

#### Tags

- Quantum Computing
- Machine Learning
- Hybrid
- Open Source

#### Properties

- [Documentation](https://www.tensorflow.org/quantum)
- [Source Code](https://github.com/tensorflow/quantum)
- [Package U R L](https://pypi.org/project/tensorflow-quantum/)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ReCirq

ReCirq is a research-grade collection of reproducible Cirq experiments and applications published by Google Quantum AI, covering Fermi-Hubbard simulations, quantum chemistry benchmarks, OTOC measurements, QAOA, and related workloads.

- **Human URL:** [https://github.com/quantumlib/ReCirq](https://github.com/quantumlib/ReCirq)

#### Tags

- Quantum Computing
- Research
- Experiments
- Open Source

#### Properties

- [Source Code](https://github.com/quantumlib/ReCirq)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tesseract Decoder

Tesseract is a search-based maximum-likelihood decoder for quantum error correction that accompanies Stim. It targets surface-code and color-code decoding workloads used in Willow-era QEC demonstrations.

- **Human URL:** [https://github.com/quantumlib/tesseract-decoder](https://github.com/quantumlib/tesseract-decoder)

#### Tags

- Quantum Computing
- Error Correction
- Decoder
- Open Source

#### Properties

- [Source Code](https://github.com/quantumlib/tesseract-decoder)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unitary

Unitary is an API library for adding quantum behaviours (superposition, entanglement, measurement) into classical games and interactive software, used in Google Quantum AI's educational outreach work.

- **Human URL:** [https://github.com/quantumlib/unitary](https://github.com/quantumlib/unitary)

#### Tags

- Quantum Computing
- Games
- Education
- Open Source

#### Properties

- [Source Code](https://github.com/quantumlib/unitary)
- [Postman Collection](collections/quantum-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quantum-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://quantumai.google/)
- [Documentation](https://quantumai.google/cirq)
- [Documentation](https://quantumai.google/software)
- [Documentation](https://quantumai.google/cirq/google/engine)
- [Documentation](https://quantumai.google/cirq/google/concepts)
- [Documentation](https://quantumai.google/cirq/google/access)
- [Getting Started](https://quantumai.google/cirq/start/install)
- [Getting Started](https://quantumai.google/cirq/start/start)
- [Getting Started](https://quantumai.google/cirq/start/basics)
- [Documentation](https://quantumai.google/reference/python/cirq/all_symbols)
- [Documentation](https://quantumai.google/reference/python/cirq_google)
- [Documentation](https://quantumai.google/qsim)
- [Documentation](https://quantumai.google/openfermion)
- [Documentation](https://quantumai.google/quantumcomputer)
- [Documentation](https://quantumai.google/roadmap)
- [Documentation](https://quantumai.google/research)
- [Sign Up](https://quantumai.google/willowearlyaccess)
- [Training](https://quantumai.google/learn/map)
- [Training](https://quantumai.google/learn)
- [Blog](https://blog.google/technology/google-deepmind/google-quantum-ai/)
- [Twitter](https://x.com/googlequantumai)
- [Video Channel](https://www.youtube.com/@GoogleQuantumAI)
- [GitHub Organization](https://github.com/quantumlib)
- [SDK](https://github.com/quantumlib/Cirq)
- [SDK](https://github.com/quantumlib/qsim)
- [SDK](https://github.com/quantumlib/OpenFermion)
- [SDK](https://github.com/quantumlib/Stim)
- [SDK](https://github.com/quantumlib/qualtran)
- [Code Examples](https://github.com/quantumlib/ReCirq)
- [Tool](https://github.com/quantumlib/tesseract-decoder)
- [SDK](https://github.com/quantumlib/unitary)
- [Tool](https://github.com/quantumlib/chromobius)
- [SDK](https://github.com/quantumlib/TypedUnits)
- [SDK](https://github.com/tensorflow/quantum)
- [Package U R L](https://pypi.org/project/cirq/)
- [Package U R L](https://pypi.org/project/cirq-google/)
- [Package U R L](https://pypi.org/project/qsimcirq/)
- [Package U R L](https://pypi.org/project/openfermion/)
- [Package U R L](https://pypi.org/project/stim/)
- [Forum](https://groups.google.com/g/cirq)
- [Forum](https://quantumcomputing.stackexchange.com/questions/tagged/cirq)
- [Terms of Service](https://cloud.google.com/terms)
- [Privacy Policy](https://policies.google.com/privacy)
- [Status Page](https://status.cloud.google.com/)
- [Changelog](https://github.com/quantumlib/Cirq/releases)
- [License](https://github.com/quantumlib/Cirq/blob/main/LICENSE)
- [Courses](https://www.coursera.org/learn/quantum-error-correction)
- [Plans](plans/google-quantum-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/google-quantum-ai-rate-limits.yml)
- [Fin Ops](finops/google-quantum-ai-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
