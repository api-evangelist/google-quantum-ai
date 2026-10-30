# Google Quantum AI

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Quantum Computing · Quantum · Hardware · NISQ · Error Correction · Willow · Sycamore · Cirq · Quantum Engine · Superconducting Qubits · Google Cloud

## Google Quantum AI on APIs.io

Everything profiled for Google Quantum AI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/google-quantum-ai/](https://apis.io/providers/google-quantum-ai/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Cirq](https://apis.io/apis/google-quantum-ai/cirq/) — Cirq is an Apache 2.0 Python framework for designing, manipulating, simulating, and executing Noisy Intermediate-Scale Quantum (NISQ) circuits. Cirq is the…
- [qsim](https://apis.io/apis/google-quantum-ai/qsim/) — qsim is a high-performance C++ state-vector simulator with a Python (qsimcirq) binding that plugs directly into Cirq. It is optimised for AVX/AVX-512, CUDA,…
- [OpenFermion](https://apis.io/apis/google-quantum-ai/openfermion/) — OpenFermion is an Apache 2.0 library for translating quantum chemistry and materials science problems (electronic structure, fermionic operators, second…
- [Stim](https://apis.io/apis/google-quantum-ai/stim/) — Stim is a fast stabilizer-circuit simulator and detector-error-model toolchain that underpins Google Quantum AI's quantum error-correction work, including…
- [Qualtran](https://apis.io/apis/google-quantum-ai/qualtran/) — Qualtran provides abstractions (Bloqs) for expressing, decomposing, and resource-estimating fault-tolerant quantum algorithms. It is Google Quantum AI's…
- [TensorFlow Quantum](https://apis.io/apis/google-quantum-ai/tensorflow-quantum/) — TensorFlow Quantum (TFQ) is a hybrid quantum-classical machine learning library that integrates Cirq circuits as differentiable layers inside…
- [ReCirq](https://apis.io/apis/google-quantum-ai/recirq/) — ReCirq is a research-grade collection of reproducible Cirq experiments and applications published by Google Quantum AI, covering Fermi-Hubbard simulations,…
- [Tesseract Decoder](https://apis.io/apis/google-quantum-ai/tesseract-decoder/) — Tesseract is a search-based maximum-likelihood decoder for quantum error correction that accompanies Stim. It targets surface-code and color-code decoding…
- [Unitary](https://apis.io/apis/google-quantum-ai/unitary/) — Unitary is an API library for adding quantum behaviours (superposition, entanglement, measurement) into classical games and interactive software, used in…
- [Google Quantum AI Calibrations API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-calibrations-api/) — Periodic device performance snapshots.
- [Google Quantum AI Jobs API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-jobs-api/) — Executions of a program against a processor or simulator backend.
- [Google Quantum AI Processors API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-processors-api/) — Quantum processing units (Willow, Sycamore-class) available to the project.
- [Google Quantum AI Programs API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-programs-api/) — Hardware-compatible circuits uploaded to a Google Cloud project.
- [Google Quantum AI Reservations API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-reservations-api/) — Processor time-slot reservations and budgets.
- [Google Quantum AI Results API](https://apis.io/apis/google-quantum-ai/google-quantum-ai-results-api/) — Measurement results returned by completed jobs.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Google Quantum Ai Agentic Access](https://apis.io/agentic-access/google-quantum-ai/google-quantum-ai-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [QuantumJob](https://apis.io/schemas/google-quantum-ai/google-quantum-ai-quantum-job/)
- [QuantumProgram](https://apis.io/schemas/google-quantum-ai/google-quantum-ai-quantum-program/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Google Quantum Ai Context](https://apis.io/jsonld/google-quantum-ai/google-quantum-ai-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Google Quantum Ai Vocabulary](https://apis.io/vocabularies/google-quantum-ai/google-quantum-ai-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Quantum Engine Create Job Example](https://apis.io/examples/google-quantum-ai/quantum-engine-create-job-example/)
- [Quantum Engine Create Program Example](https://apis.io/examples/google-quantum-ai/quantum-engine-create-program-example/)
- [Quantum Engine List Processors Example](https://apis.io/examples/google-quantum-ai/quantum-engine-list-processors-example/)

#### Collections (13)

Postman and Open Collection request collections.

- [Google Quantum Engine Calibrations API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-calibrations-api/)
- [Google Quantum Engine Calibrations Jobs API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-jobs-api/)
- [Google Quantum Engine Calibrations Processors API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-processors-api/)
- [Google Quantum Engine Calibrations Programs API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-programs-api/)
- [Google Quantum Engine Calibrations Reservations API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-reservations-api/)
- [Google Quantum Engine Calibrations Results API](https://apis.io/collections/google-quantum-ai/open-google-quantum-ai-results-api/)
- [Google Quantum Engine API](https://apis.io/collections/google-quantum-ai/open-quantum-engine-api/)
- [Google Quantum Engine Calibrations API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-calibrations-api/)
- [Google Quantum Engine Calibrations Jobs API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-jobs-api/)
- [Google Quantum Engine Calibrations Processors API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-processors-api/)
- [Google Quantum Engine Calibrations Programs API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-programs-api/)
- [Google Quantum Engine Calibrations Reservations API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-reservations-api/)
- [Google Quantum Engine Calibrations Results API](https://apis.io/collections/google-quantum-ai/postman-google-quantum-ai-results-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Google Quantum AI — jsonschema rules](https://apis.io/rules/google-quantum-ai/google-quantum-ai-jsonschema-spectral-rules/)
- [Google Quantum AI API Rules](https://apis.io/rules/google-quantum-ai/google-quantum-ai-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Google Quantum Ai Authentication](https://apis.io/security/google-quantum-ai/google-quantum-ai-authentication/)
- [Google Quantum Ai Domain Security](https://apis.io/security/google-quantum-ai/google-quantum-ai-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Google Quantum Ai Scopes](https://apis.io/scopes/google-quantum-ai/google-quantum-ai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Google Quantum Ai Plans Pricing](https://apis.io/plans/google-quantum-ai/google-quantum-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Google Quantum Ai Rate Limits](https://apis.io/rate-limits/google-quantum-ai/google-quantum-ai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Google Quantum Ai Finops](https://apis.io/finops/google-quantum-ai/google-quantum-ai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.quantumai.google/)
- [Documentation](https://quantumai.google/cirq)
- [Getting started](https://quantumai.google/cirq/start/install)
- [Changelog](https://github.com/quantumlib/Cirq/releases)
- [Blog](https://blog.google/technology/google-deepmind/google-quantum-ai/)
- [Terms of service](https://cloud.google.com/terms)
- [Privacy policy](https://policies.google.com/privacy)
- [GitHub](https://github.com/quantumlib)
- [Status](https://status.cloud.google.com/)

## API Evangelist rating

**Kin Score 53.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 63.3 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 67.9 |
| Access clarity | 50.0 |

**Agent readiness 27.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/google-quantum-ai/](https://apis.io/providers/google-quantum-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Google Quantum AI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/google-quantum-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
