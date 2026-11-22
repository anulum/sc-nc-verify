<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-VERIFY — repository foundation
-->

# SC-NC Verify

SC-NC Verify is being built as the verification layer split out of SC-NeuroCore: the equivalence proofs between a network and its compiled form, the fault-injection campaigns that test its resilience, and the formal verification standard and evidence packets that carry the results to safety cases and acceptance. It imports SC-NC Core, SC-NC Catalogue, SC-NC Engine, SC-NC Analysis and SC-NC Compiler. Its current executable surface is repository validation tooling. It has no installed equivalence prover, fault-campaign runner, evidence-packet issuer or qualified record schema.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
