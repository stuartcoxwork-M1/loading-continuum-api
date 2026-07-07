# Loading Continuum Staging API — Open Interface Specification

[![DOI](https://img.shields.io/badge/DOI-pending-lightgrey)](#) <!-- replace with Zenodo badge after Step 3 -->
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

An open, machine-readable interface specification for **The Loading Continuum** — a
seven-parameter, load-based staging framework for spinal pain rehabilitation (Unload →
Reload → Load), staged by clinical loading response rather than diagnosis, time, or
imaging.

**Framework publication:** Cox S. *The Loading Continuum: A Seven-Parameter Framework for
Staging Exercise Progression in Spinal Pain Rehabilitation.* JMIR Preprints. 2026.
doi:[10.2196/104890](https://doi.org/10.2196/104890)

**Author:** Stuart Cox, B.Phty, MPH — [ORCID 0009-0004-6096-9718](https://orcid.org/0009-0004-6096-9718)
**Organisation:** Movement First International — [loadingcontinuum.com](https://loadingcontinuum.com) · [spinalrisk.com](https://spinalrisk.com)

---

## What's in this repository

| File | Purpose |
|------|---------|
| `openapi.yaml` | The full interface specification (OpenAPI 3.1) — endpoints, request/response schemas. |
| `README.md` | This file. |
| `LICENSE` | Licence for this documentation (see below). |

**That's it.** This repository intentionally contains only the interface contract.

## What this is NOT

- **Not the clinical logic engine.** The provocation thresholds, staging rules, gate
  mechanics, and progression ordering that implement this contract are proprietary to
  Movement First International and are not published here or anywhere public.
- **Not a diagnosis.** This is clinical decision support for exercise progression only.
  It does not replace clinical judgement.
- **Not a live endpoint.** This repository documents an interface; it does not currently
  expose a publicly callable server. A hosted, callable version follows regulatory review
  appropriate to a clinical screening/staging tool.

## Composes with SpinalRisk

Staging under this specification requires a passed safety screen — either a
[SpinalRisk](https://spinalrisk.com) triage result of `conservative`/`monitor`, or an
explicit clinician attestation. Any higher-severity SpinalRisk outcome blocks staging and
returns a referral instruction. The two tools are separate products designed to compose,
not a single fused system.

## How to cite

**The framework:**
> Cox S. The Loading Continuum: A Seven-Parameter Framework for Staging Exercise
> Progression in Spinal Pain Rehabilitation. JMIR Preprints. 2026. doi:10.2196/104890

**This interface specification:**
> Cox S. Loading Continuum Staging API: Open Interface Specification v1.0. 2026.
> doi: [ZENODO DOI — insert after Step 3]

## License

This specification and documentation are licensed under
[**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — you may share and adapt
freely, including commercially, with attribution. See `LICENSE`.

This does **not** extend to the underlying clinical decision logic (proprietary, not
published here) or to The Loading Continuum™ / SpinalRisk™ trademarks.

## Contact

Stuart Cox, B.Phty, MPH — contact@movementfirst.org

---

<sub>Clinical decision support only. Not a diagnosis; does not replace clinical judgement.
The Loading Continuum™ is a trademark of Stuart Cox / Movement First International.
© 2026 Movement First International.</sub>
