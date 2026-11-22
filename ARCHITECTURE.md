<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-VERIFY — repository foundation
-->

# Architecture

## Current executable surface

The checkout contains:
- repository validation tooling;
- dedicated tests;
- workflow definitions;
- native documentation.

No domain component of SC-NC Verify is implemented yet, and no code has moved here from SC-NeuroCore. The metadata keeps domain capabilities, claims and qualified record formats empty.

## Intended records

1. **IR equivalence proof:** A proof that two network representations are equivalent, with its method, scope and solver.
2. **Fault campaign:** A set of injected faults, their sites and models, and the outcomes.

## Ownership

**This project owns** the planned SC-NC Verify records and boundary rules.

**Owned elsewhere:**

| Responsibility | Owner |
|---|---|
| statistics and audit reports | SC-NC Analysis |
| compiled designs | SC-NC Compiler |
| acceptance and sign-off | Circuit Acceptance |
| the public package, documentation and releases of the monolith | SC-NeuroCore |

## Interpretation

- **Proofs.** A proof holds for its stated scope and bound.
- **Moves.** Code arrives only through SC-NeuroCore's split import gate, unit by unit; a planned move is not a moved capability.

Read [the documentation architecture](docs/ARCHITECTURE.md) for the planned records, rules and schema identifiers.
