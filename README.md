# FA Local Operator

FA Local is the governed local execution boundary for Forge applications.

This repository is the implementation home for the FA Local service. It is intentionally separate from `forge-local-runtime`, which remains the governance-and-contracts authority repository for the shared local runtime layer.

Current status: Ticket 1 scaffold complete. The crate builds, exposes typed baseline vocabulary, and defaults toward fail-closed admission. Contract schemas, artifact loaders, and execution coordination are intentionally not implemented yet.
