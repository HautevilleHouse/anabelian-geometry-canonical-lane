# Reviewer Map

    ## Claim Scope

    - Canonical-lane claim: inside the `manifold_constrained` routed lattice, if the theorem chain in this repository holds and the guard certificate passes, the repository-level super-lane closure claim is satisfied.
    - Standard target claim: Across the declared admissible anabelian lattice, varieties, sections, and birational objects are reconstructed from their profinite or Galois-theoretic fundamental-group data with the predicted compatibility package.

    ## Super-Lane Families

    1. section-conjecture style reconstruction packages
2. birational and profinite fundamental-group recovery
3. Galois exact-sequence and decomposition-group control
4. local-global anabelian compatibility across admissible fields
5. endpoint stitching of the declared reconstruction package

    ## Theorem Dependency Chain

    1. `EG1`: coercive projected response and active floor.
    2. `EG2`: routed-family capture across the declared lattice.
    3. `EG3`: compactness and no-collapse spacing for normalized towers.
    4. `EG4`: rigidity and endpoint transfer.
    5. Identification bridge: strict coherence on the determining class.
    6. Scalar closure: `ANA_G1`, `ANA_G2`, `ANA_G3`, `ANA_G4`, `ANA_G5`, `ANA_G6`, `ANA_GM` all `PASS`.

    ## Falsification Conditions

    - `repro/certificate_runtime.json` has any non-`PASS` gate.
    - `lane.active_lane != "manifold_constrained"`.
    - `all_pass != true`.
    - Any manifest hash mismatch under `repro/repro_manifest.json`.
    - A verified counterexample to any routed family theorem used by the super-repo.
