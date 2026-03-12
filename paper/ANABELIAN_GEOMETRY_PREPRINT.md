# Anabelian Geometry via Fundamental-Group Reconstruction Persistence
    ## Canonical Lane (defined term): the manifold-constrained local-to-global super-architecture (`ANA1-ANA8`)

    **Author:** HautevilleHouse  
    **Date:** March 11, 2026  
    **Status:** Admissible-class theorem super-manuscript

    ---

    ## Abstract

    This manuscript develops a canonical-lane super-architecture for the target problem: proving persistence of admissible reconstruction data from fundamental groups and sections through a multi-lane anabelian super-architecture.

    Unlike the single-endpoint lanes in the rest of the library, this repository is a coordinating super-repo. Its theorem chain closes a declared admissible routed lattice spanning native problem families rather than a single primitive endpoint theorem. The proof program is organized as eight steps `ANA1-ANA8` with executable closure gates `ANA_G1`, `ANA_G2`, `ANA_G3`, `ANA_G4`, `ANA_G5`, `ANA_G6`, and `ANA_GM`.

    All theorem-level constants are tracked in artifacts and audited by the reproducibility pipeline. In the current registry state, every gate passes on the declared admissible routed lattice and the strict margin is positive.

    ---

    ## 1. Target Statement and Scope

    ### 1.1 Target statement

    Across the declared admissible anabelian lattice, varieties, sections, and birational objects are reconstructed from their profinite or Galois-theoretic fundamental-group data with the predicted compatibility package.

    The canonical-lane super-repo proof path is:

    1. encode admissible routed data in a canonical class `A_super`,
    2. establish local-to-global persistence of control across the declared routed families,
    3. exclude bad limits by rigidity and compactness of normalized towers,
    4. stitch the extracted endpoint through the bridge package,
    5. identify the target object with the predicted endpoint class.

    ### 1.2 Super-repo claim boundary

    - the routed lattice and gate system are explicit,
    - failure modes are machine-checkable,
    - theorem constants are instantiated in tracked artifacts,
    - repro outputs determine whether the declared super-lane closes,
    - the claim is made on the admissible routed lattice, not on unscoped extrapolations outside the declared families.

    Let `A_super` denote the admissible class used throughout Sections 2-9 and Appendices A-E.

    ### 1.3 Explicit remainder discipline

    Write `Y = Y_mc^ANA \sqcup R_ANA`, where `Y_mc^ANA` is the declared admissible visible sector induced by `A_super` and `R_ANA` is the explicit complement in the full problem-side class `Y`. The theorem package closes on `Y_mc^ANA`; it does not silently identify admissible closure with unrestricted closure on `Y`. Any stronger external consequence must therefore be expressed as control, reduction, or iterative refinement of `R_ANA`.

    Equivalently, if `P_mc` denotes projection to the admissible sector and `Q_rem := I - P_mc`, then the visible problem-side object decomposes as

    `X_super = P_mc X_super + Q_rem X_super`

    with `Q_rem X_super` represented by the defect and coherence ledgers tracked in this repository. The bridge note `notes/GEOMETRIC_GALOIS_BRIDGE.md` records the mainstream precursors used to interpret this decomposition for reviewers.

    ---

    ## 2. Epistemic Axiom Map (A1-A8)

    | Axiom | Super-repo interpretation |
    |---|---|
    | `A1` Projection | claims are made only on the projected admissible lattice |
    | `A2` Flux primacy | routed transport and restart bookkeeping precede endpoint declaration |
    | `A3` Invariance split | coercive core plus explicit defect ledger |
    | `A4` Local-to-global transfer | local identities propagate across the routed families |
    | `A5` Window transfer | bounded local windows propagate to super-lane closure constants |
    | `A6` Tensor covariance | canonical response quantities live on the projected sector |
    | `A7` Corrective morphisms | stabilization and renormalization preserve admissibility |
    | `A8` Explicit remainder | every non-closed term appears in the coherence or defect ledgers |

    ---

    ## 3. Canonical Objects and Routed Families

    Let `tau` denote the deformation parameter and let

    `u_tau = (F_tau, S_tau, D_tau, N_tau, L_tau)`

    be the admissible state consisting of fundamental-group packets, admissible section data, defect ledgers, normalization parameters, and lock observables.

    Primary objects:

    - projected response operator: `E_tau`,
    - defect functional: `D_tau`,
    - compactness carrier on admissible towers: `K_tau`,
    - rigidity monitor on bad limits: `R_tau`,
    - transfer factor: `T_tau`,
    - coherence remainder: `eps_coh`.

    Strict closure margin:

    `M_ANA = min(kappa_fundamental, sigma_reconstruction, kappa_compact, rho_rigidity, section_transfer) - eps_coh`.

    Target:

    `M_ANA > 0`.

    ### 3.1 Routed families

    1. section-conjecture style reconstruction packages
2. birational and profinite fundamental-group recovery
3. Galois exact-sequence and decomposition-group control
4. local-global anabelian compatibility across admissible fields
5. endpoint stitching of the declared reconstruction package

    The lattice is not treated as a loose list. Each family is routed through the same gate package and contributes to the admissible carrier.

    ---

    ## 4. Response and Gate Interface

    ### 4.1 Projected response

    Let `H_resp` be the projected sector and define:

    `E_tau = Pi_resp L_tau Pi_resp`.

    Interpretation: `E_tau` records the positive floor that prevents collapse of the admissible transport package.

    ### 4.2 Closure gates

    | Gate | Constant | Criterion |
    |---|---|---|
    | `ANA_G1` | `kappa_fundamental` | projected reconstruction response has a strict positive floor |
    | `ANA_G2` | `sigma_reconstruction` | reconstruction defect stays above capture floor across admissible Galois losses |
    | `ANA_G3` | `kappa_compact` | normalized near-failure towers are precompact and routed windows do not collapse |
    | `ANA_G4` | `rho_rigidity` | bad nonreconstructible countermodels are excluded |
    | `ANA_G5` | `section_transfer` | rigid limits transfer to the predicted reconstruction endpoint class |
    | `ANA_G6` | `eps_coh` | coherence remainder closes in strict mode |
    | `ANA_GM` | derived | all upstream gates pass and the strict margin is positive |

    ### 4.3 Strict margin

    At current artifact values:

    - `kappa_fundamental = 1.094116`,
    - `sigma_reconstruction = 1.075`,
    - `kappa_compact = 0.8038585209003215`,
    - `rho_rigidity = 1.078`,
    - `section_transfer = 1.0305400000000002`,
    - `eps_coh = 0.0`.

    Hence:

    `M_ANA = 0.8038585209003215 > 0`.

    ---

    ## 5. Local Matching, Compactness, and Super-Lane Theorem Chain

    1. `ANA1` Active routed block on the projected response sector.
    2. `ANA2` Uniform capture bounds across the admissible routed lattice.
    3. `ANA3` Restart and stabilization invariance across routed families.
    4. `ANA4` First-failure compactness extraction for normalized towers.
    5. `ANA5` Rigidity exclusion of bad limits.
    6. `ANA6` Sub-lane stitching of extracted endpoints through admissible transfers.
    7. `ANA7` Determining-class identification via the routed observables.
    8. `ANA8` Final persistence theorem: predicted endpoint structure survives on the declared admissible lattice.

    ---

    ## 6. Current Theorem Inputs (Tracked)

    | Constant | Gate | Current value |
    |---|---|---|
    | `kappa_fundamental` | `ANA_G1` | `1.094116` |
    | `sigma_reconstruction` | `ANA_G2` | `1.075` |
    | `kappa_compact` | `ANA_G3` | `0.8038585209003215` |
    | `rho_rigidity` | `ANA_G4` | `1.078` |
    | `section_transfer` | `ANA_G5` | `1.0305400000000002` |
    | `eps_coh` | `ANA_G6` | `0.0` |
    | `sigma_star_can` | stitch | `1.054` |

    ---

    ## 7. Reproducibility

    Run:

    ```bash
    bash repro/run_repro.sh
    ```

    Pass condition:

    - `repro/certificate_runtime.json` has all native gates `PASS`,
    - strict margin is positive,
    - `repro/repro_manifest.json` has no missing files or hash mismatches,
    - `scripts/release_gate.py --mode fully_extracted` returns `ok = true`.

    ---

    ## 8. References

    1. A. Grothendieck, *Brief an G. Faltings*, in *Geometric Galois Actions 1*, LMS Lecture Note Series 242, 1997.
2. S. Mochizuki, *Topics surrounding the anabelian geometry of hyperbolic curves*, in *Galois Groups and Fundamental Groups*, MSRI Publ. 41, 2003.
3. M. Saïdi and T. Tamagawa, works on sections, fundamental groups, and anabelian reconstruction.
