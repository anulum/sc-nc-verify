<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-VERIFY — repository foundation
-->

# Repository architecture

## Current executable tooling

**What it contains:** the repository's metadata, source-provenance, workflow, dependency-alignment, documentation, inventory and preflight controls.

**What each control does:** it inspects its fixed, declared local scope.

**What received metadata cannot do:** select another acceptance policy or grant domain authority.

Foundation qualification is in progress.

## Intended domain boundaries

| Record | Responsibility | Required evidence |
| --- | --- | --- |
| IR equivalence proof | A proof that two network representations are equivalent, with its method, scope and solver | Proof scope and solver recorded; a bounded proof is never reported as complete |
| Fault campaign | A set of injected faults, their sites and models, and the outcomes | Campaign coverage declared before the run and outcomes counted against it |

## Planned record schemas

- `sc_nc_verify.ir_equivalence_proof.v1`
- `sc_nc_verify.fault_campaign.v1`

These are planned identifiers. None of them is registered or qualified here.

It also takes over, unchanged, sc-neurocore.formal-snn-verification-standard (v1) and sc-neurocore.evidence-packet (v1) from SC-NeuroCore when their code moves here.

Read [validation tooling](validation-tooling.md) for the executable repository interfaces.
