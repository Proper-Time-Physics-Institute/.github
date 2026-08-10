# Proper-Time Physics Institute

**An adversarial verification program for the proper-time ("dual") formulation of relativity and quantum mechanics** (T. L. Gill and collaborators) — the reformulation built on proper time τ as evolution parameter, the positive-definite Hamiltonian K = H²/2mc² + mc²/2, and the collaborative speed b = √(c² + u²).

We take the framework seriously enough to *test it* — derivation by derivation, against the published record and against precision data — and we publish what we find, whichever way it goes. So far, what we have found is that **the framework is empirically refuted**: every sector tested either reduces to standard physics exactly or deviates and is excluded by existing data.

---

## 🎯 What we do

Every claim in the framework's corpus is pushed through the same pipeline:

1. **Derive** — independent re-derivation from the primary sources, in writing, with a PROVEN / ASSUMED / OUT-OF-SCOPE ledger
2. **Compute** — reproducible Wolfram Language scripts as the generator of record for every number and figure
3. **Adversarially verify** — independent skeptic panels (re-derivation lens, assumption-completeness lens, numeric lens) actively try to refute each load-bearing claim
4. **Publish honestly** — verdicts are *confirmed / disputed / unresolved* and are never upgraded; refuted claims are quarantined in the record, not deleted

The output is one of four honest outcomes: an **exact equivalence** with standard physics, a **correction** to the published record, a **rule-out** against data, or a precisely-stated **open question** routed back to the framework's authors.

## 📌 What we've established

An org-wide review of two months of work (32 adversarial panel verdicts, 2026-07-05) plus a follow-up Tier 1–4 research campaign (27 verdicts) converge on a clear picture:

- **Kinematics** — b = γc *exactly*: the "collaborative speed" is celerity bookkeeping, not a new signal speed
- **Classical electromagnetism** — the proper-time Liénard–Wiechert field is *identically* the classical field (no third-term signature, no longitudinal radiation); the radiation-reaction force is exactly Lorentz–Abraham–Dirac, runaways included (Wolfram-verified path derivation)
- **QED** — the electron anomalous moment a_e is inherited from QED, not derived (probes P0–P6 all close); the celebrated closed form r_e/r₀ = (2−a_e)/(2(2+a_e)) is an algebraic identity, and the six-observable "triangulation" is one back-fit applied six times
- **Gravity** — the dual Newtonian force law (the paper's own V + V²/2mc² gravitational substitution) gives exactly **−1/6 of GR's Mercury perihelion advance**; Corda's πm/M "precession" is refuted by Bertrand's theorem
- **Precision spectroscopy (the falsifier)** — the published g-factor chain contradicts the paper's own Eq. (III.8) by a factor of 2; the internally consistent corrected formula g_r(x) = 2(2x−1)/(2x+1) has range (−2, 2), so **no cutoff r_e > 0 can reproduce the measured electron g**; and the framework's own operators, evaluated self-consistently, predict a **+30.6% universal s-state hyperfine anomaly** excluded by existing data
- **The published record** — erratum-grade corrections proven against the sources: Gill–Zachary Eq. (24) (missing c and V²/2mc² terms), DRQM-I §III.D (published r_e gives g = −2.00057, not −2.00232), the TCEP group-velocity chain (4.12)/(4.15)/(4.16) — transcription, underivability, and sign (E-3w, widened per the T1b dissolution), DRQM-I's (III.8)→(a,b,c) factor-2, and a corrigendum case for J. Phys. Conf. Ser. 2482 (2023), which reprints the erroneous equations

## 📊 Experimental scoreboard

The quantitative comparisons the program has adjudicated. "Framework" values are the framework's **own operators and formulas evaluated self-consistently** at its triangulated (g-fitting) cutoff. Every row is adversarial-panel-confirmed except the two marked † — Wolfram-verified path results of the 2026-07-05 review, not separately panelled.

**Where it deviates, it is excluded:**

| Observable | Measured / reference | Framework | Margin |
|---|---|---|---|
| Mercury perihelion advance — the paper's own V + V²/2mc² gravitational substitution | GR: +42.99″/century; observed ≈ 43″ | **−7.17″/century** (exactly −Δφ_GR/6, eccentricity-independent) | wrong sign, ⅙ magnitude — structural rule-out of that substitution |
| Venus / Earth perihelion residuals (Corda πm/M) | observed residuals | 30× / 51× over-prediction | excluded; not a precession (Bertrand) |
| Solar light bending — gravity-kernel class, every coupling f | Cassini γ measurement | factor 2 low, or zero (f-independent) | excluded at 4.35×10⁴σ |
| Shapiro time delay | +131.2 μs (GR round-trip) | zero, or **−65.6 μs** (wrong sign) | excluded for the entire kernel class |
| Electron g — published back-fit (DRQM-I §III.D) | −2.002 319 304 362 56 | −2.000 571 48 from the published r_e/r₀ | off by 1.75×10⁻³ → erratum E-2 |
| Electron g — corrected algebra | −2.002 319 304 362 56 | g_r(x) = 2(2x−1)/(2x+1), range (−2, 2) | **no solution for any r_e > 0** |
| Free a_e — any static propagator modification at the r_e scale † | a_e experimental tolerance | shift of 514–40 000× tolerance | excluded |
| H 21-cm hyperfine — corrected (III.20) | 1 420 405 751.768(2) Hz | **+435.2 MHz (+30.6%)** | **1088×** the campaign floor — the falsifying line |
| Muonium hyperfine — corrected (III.20) | 4 463 302 776(51) Hz | +1 367.5 MHz (the same universal +30.6%) | excluded |
| H 1S–2S — (III.19) μ² channel | 2 466 061 413 187 035(10) Hz | +182.4 kHz | ≥10³× the campaign floor |
| H–D isotope shift — (III.19) μ² scaling | measured at the ~15 Hz level | ~165 kHz anomaly | ~10⁴× |
| Parameter-free τ-reading of the exact spectral map K_D | the three transitions above (1S–2S · 21-cm · muonium HFS) | −41.06 GHz · −37.8 kHz · −118.8 kHz | excluded at 10³–10⁹σ (muonium: 2330σ) |

**Where it agrees, it agrees by identity** — the framework reduces to standard physics exactly, so agreement carries no evidential weight:

| Observable | Result |
|---|---|
| GPS clock rates (+38.54 μs/day) | reproduced via b = γc — agreement-by-construction |
| Time dilation, velocity composition | identical to special relativity |
| Liénard–Wiechert radiation fields | identically the classical field (symbolic residual ≡ 0) |
| Radiation reaction † | exactly Lorentz–Abraham–Dirac, runaway/pre-acceleration dichotomy intact |
| Free-electron a_e with D = 1/k² | QED's α/2π inherited, not derived |

**Program verdict:** no unconditional surviving prediction — the one falsifiable residue is the conditional a_e(B) trap-slope test below; the org's real assets are its verification discipline, its errata, and its structural rule-outs, and those are exactly what we are writing up.

## ❓ Open questions for the program's authors

The pipeline's fourth outcome — precisely-stated open questions routed back to the framework's authors. These are the places where the program's closure is *conditional* and an author's answer (or a one-page result) changes the conclusion:

| # | Question | What's established | What would resolve it |
|---|---|---|---|
| 1 | **"QED III" — does a genuine dual photon propagator D_dual(k) exist?** | a_e is not derivable by probes P0–P6; the problem is now a well-posed constraint set (C0–C3 + C3′, anchored by bound-state g-factor data to 8.5×10⁻¹⁰). Panel-confirmed: source-independent kernels deliver ≤ 9.7×10⁻⁴ of the bound (Zα)² term, and an acceleration-gated kernel is not a Fock two-point function | A construction satisfying C0–C3 + C3′ outside the closed branches — or acceptance that a_e is inherited from QED |
| 2 | **Gap G3 — the cross-coupling loophole** | D_dual ≡ 0 in *every* quantization of the Bateman system (theorem, panel-confirmed) — but the panel found a 2-parameter family of stationary cross moments with an exponentially growing commutator branch [y(τ), x(0)] | A one-page-scale result: either the growing branch makes every stationary cross kernel inadmissible (Route F closes, caveat G1 only), or some admixture furnishes a finite admissible kernel — which would be a major *positive* finding |
| 3 | **Gap G1 — multimode, τ-dependent gating** | The single-mode, constant-Γ reduction (assumption A1, inherited from the a_e probe series) is unjustified for bound orbits, where g(τ) = (u·a)/b⁴ varies along the orbit | A derivation of the mode reduction for bound orbits, or a multimode version of the no-go |
| 4 | **The factor-2 fork — which g-factor algebra is intended?** | The published g_r chain contradicts the paper's own Eq. (III.8) by a factor of 2 — unconditional, whichever side is blamed. If (III.8) stands, the corrected formula g_r(x) = 2(2x−1)/(2x+1) cannot reach the electron g for any r_e > 0 | The authors adjudicate the E-5 correction: affirm (III.8) (the back-fit dies) or repair the chain some third way |
| 5 | **t- vs τ-reading of the spectral operator K_D** | The exact map admits exactly two readings: the t-reading is identical to Dirac/QED (predicts nothing new); the τ-reading gives parameter-free shifts excluded at 10³–10⁹σ | The authors state which reading the framework intends — both horns are closed, so the choice selects *which* closure applies |
| 6 | **TCEP (4.15) — can the group-velocity claim be rescued?** | Panel-confirmed dissolution: (4.15) is underivable from (4.12) under *both* the printed γ² and corrected γ readings, fails at O(1) on the paper's own worldline class (the transformation gives 0.875 where the paper claims 1.25), and (4.16) carries no physical content in either sign | A derivation outside both readings — or withdrawal of the claim |

**One clean experiment falls out of #1:** if the a_e route is rescued by an acceleration-gated kernel, it predicts a trap-field-linear shift δa_e ≈ 3.7–4.1×10⁻¹³ at 5.36 T (slope 7.7×10⁻¹⁴/T) — so measuring the a_e(B) slope against zero is a model-independent null test of the entire gated-kernel hypothesis, unconstrained by existing single-field data.

## 🗂 Repository map

| Repo | Role |
|---|---|
| **[quantum](https://github.com/Proper-Time-Physics-Institute/quantum)** | Dirac/DRQM verification, precision spectroscopy, the a_e probe series, the T2b falsifier paper |
| **[electromagnetic](https://github.com/Proper-Time-Physics-Institute/electromagnetic)** | Jackson canonical problems in proper time, Liénard–Wiechert & radiation reaction |
| **[relativistic-dynamics](https://github.com/Proper-Time-Physics-Institute/relativistic-dynamics)** | Mercury perihelion (and the −1/6 paper), GPS relativity, classical-electron problem, TCEP |
| **[commons](https://github.com/Proper-Time-Physics-Institute/commons)** | The hub: unified bibliography, cross-repo synthesis, errata packets, review reports, **coordination queue** |
| **[Proper-Time-Physics-Institute.github.io](https://github.com/Proper-Time-Physics-Institute/Proper-Time-Physics-Institute.github.io)** | Public website (Astro), assembled from repo content at build time |
| [pyphysics-mcp](https://github.com/Proper-Time-Physics-Institute/pyphysics-mcp) · [precision-data-mcp](https://github.com/Proper-Time-Physics-Institute/precision-data-mcp) | MCP servers for computation and precision-data lookup |
| [animations](https://github.com/Proper-Time-Physics-Institute/animations) · [podcasts](https://github.com/Proper-Time-Physics-Institute/podcasts) · [branding](https://github.com/Proper-Time-Physics-Institute/branding) · [tooling](https://github.com/Proper-Time-Physics-Institute/tooling) | Shared media and infrastructure |

Split from the former `PyPhysics` monorepo (archived, read-only) with per-file history preserved.

## 🧭 How the org runs

- **Nothing merges to a topic-repo `main` without human review.** Research lands as PRs on dated review/research branches; merge order is managed through an explicit queue
- **Nothing leaves the org without a human.** Erratum letters, comment papers, and submission packets are drafted and verified by agents, but every external send is a human decision with author sign-off
- **Citations are never fabricated.** Bibliography notes carry `human_reviewed` flags that only a human may set; unverified metadata is marked TODO-verify rather than guessed
- **Multi-agent, adversarial by default.** Large reviews run as orchestrated workflows: parallel per-repo reviewers → independent verification panels → synthesis, with every load-bearing claim panelled before it is relied on

## 📍 Where things stand *(August 2026)*

- ✅ **2026-07-05 org-wide review** complete — 143-page report, 32 adversarial verdicts, org knowledge graph
- ✅ **Tier 1–4 research campaign** complete — 7 tracks, 27 panelled claims (24 confirmed, 3 disputed), headlined by the T2b falsifier
- ✅ **All review, research, and errata work merged to `main`** across the four research repos (2026-08-07) — every `main` now tells the corrected story
- 🔄 **In preparation, drafted and adversarially verified, awaiting author sign-off:** the Mercury −1/6 paper (a standalone Research Note for *General Relativity and Gravitation*), the T2b hyperfine falsification note, and the errata packet (E-1 / E-2 / E-3w / E-5 + JPCS corrigendum). DRQM-I is unpublished and its correction is co-author self-correction
- 🗓 Coordination: the human decision queue and the realignment overview live in **[commons](https://github.com/Proper-Time-Physics-Institute/commons)** issues

## 📖 Glossary

**Physics terms and symbols**

| Term | Meaning |
|---|---|
| **τ** (proper time) | Time as measured by a clock riding along with the particle — as opposed to coordinate time t measured by a stationary observer. The framework's central move is to use τ as the evolution parameter |
| **γ** (Lorentz factor) | 1/√(1 − u²/c²) — how much special relativity dilates time and contracts length at speed u |
| **b = √(c² + u²)** | The framework's "collaborative speed." Our result: b = γc exactly — it is the temporal component of the standard proper velocity (celerity), i.e. relabeled bookkeeping, not a new speed |
| **celerity** | Proper velocity dx/dτ = γu: distance per unit *proper* time. Can exceed c without violating relativity |
| **g-factor** | A particle's dimensionless magnetic strength. Dirac's equation predicts exactly g = −2 for the electron; the measured value is −2.002 319 304 362 56 |
| **a_e** (electron anomalous magnetic moment) | The tiny amount by which the electron's magnetism exceeds Dirac's prediction: a_e = (\|g\| − 2)/2 ≈ 0.001 159 652. QED derives it from first principles (leading term α/2π) and it matches measurement to ~12 digits — the most stringent test in physics. The framework claims to *derive* a_e from an electron-radius cutoff; we found the claim reduces to fitting one parameter to the measured answer |
| **α** (fine-structure constant) | ≈ 1/137, the dimensionless strength of electromagnetism; α/2π ≈ 0.00116 is QED's famous leading contribution to a_e |
| **r_e, r₀, x** | The framework's electron-radius cutoff parameter, the classical electron radius, and their dimensionless ratio x = r_e/r₀ — the framework's one free knob, and the argument of g_r(x) |
| **back-fit** | Tuning a free parameter to reproduce a measured number, then citing agreement with that number as a prediction. One back-fit reused six times is still one fit |
| **K = H²/2mc² + mc²/2** | The framework's positive-definite Hamiltonian, generating evolution in τ; **K_D** is its exact version built from the Dirac Hamiltonian |
| **hyperfine structure (HFS)** | Tiny energy splittings from the magnetic interaction between an electron and the nucleus. The **21-cm line** (1 420 405 751.768 Hz) is hydrogen's hyperfine transition — one of the most precisely known frequencies in science |
| **muonium** | An "atom" made of an electron orbiting an antimuon — hydrogen-like but with no nuclear structure, so an exceptionally clean QED test bench |
| **1S–2S** | Hydrogen's sharpest optical transition, measured to 15 digits (2 466 061 413 187 035(10) Hz) |
| **perihelion advance** | The slow rotation of an orbit's point of closest approach. Mercury's anomalous +43″/century (arcseconds per century) was general relativity's first great confirmation |
| **Liénard–Wiechert (LW) field** | The exact electromagnetic field of a moving point charge in classical electrodynamics |
| **LAD** (Lorentz–Abraham–Dirac) | The classical equation for radiation reaction — the recoil a charge feels from its own radiation — infamous for runaway solutions. The framework's version turns out to be *exactly* LAD, runaways included |
| **propagator, D_dual(k)** | The mathematical object encoding how a quantum field transmits influence; QED's photon propagator is 1/k². "QED III" is the framework's not-yet-written dual photon propagator |
| **Fock space** | The standard Hilbert space of photon states. "Not a Fock two-point function" = cannot come from any standard quantized field |
| **Bateman doubling** | A trick for quantizing a damped (energy-losing) system by pairing it with a mirror-image amplifying partner |
| **Γ** | The damping (friction) rate of the framework's dual radiation mode — the quantity the Bateman construction doubles |
| **μ² channel** | The deferred DRQM-I interaction term (III.19), whose contribution scales with the square of the nuclear magnetic moment μ — one of the two "type-b" operators the falsifier evaluates (the other is the hyperfine term (III.20)) |
| **Bertrand's theorem** | Only two force laws (1/r² and Hooke's law) give closed orbits for all bound motion — the tool that refutes Corda's πm/M "precession" |
| **σ** | Standard deviations of experimental uncertainty; "excluded at 2330σ" means the prediction misses by 2330 error bars |

**Program shorthand**

| Term | Meaning |
|---|---|
| **DRQM-I** | *Dual Relativistic Quantum Mechanics I* — the framework's central quantum-mechanics manuscript (unpublished; Morris is a co-author, so its corrections are self-correction) |
| **TCEP** | *The Classical Electron Problem* — the framework paper containing the Eq. (4.15)/(4.16) group-velocity claims |
| **JPCS 2482** | J. Phys. Conf. Ser. **2482** (2023) — a published conference paper that reprints the erroneous g-factor equations, hence the corrigendum case |
| **E-1 … E-5** | The five erratum instruments: E-1 Gill–Zachary Eq. (24); E-2 DRQM-I §III.D r_e digits; E-3w the *widened* TCEP group-velocity erratum — (4.12) transcription, (4.15) underivability, (4.16) sign; E-5 DRQM-I factor-2; plus the JPCS 2482 corrigendum |
| **P0–P6, Routes F/W/E** | The candidate routes by which a_e might be derived in the framework — each probed and closed (Route F = field-theoretic propagator route; W = Wheeler–Feynman; E = worldline) |
| **Spec A, C0–C3 + C3′** | The formalized constraint set any dual photon propagator must satisfy: inertial exactness, positive bound response, and the measured bound-state g-factor structure |
| **G1, G2, G3** | The numbered gaps in the a_e closure argument (see Open questions): G2 is now a proven theorem; G1 (multimode gating) and G3 (cross-coupling loophole) remain open |
| **t-reading vs τ-reading** | The two possible physical interpretations of the framework's spectral operator: evolve in coordinate time (→ identical to Dirac/QED) or in proper time (→ excluded shifts) |
| **campaign floor** | Our own conservative precision floor for each observable — the loosest error bar we allow ourselves when claiming an exclusion |
| **adversarial panel** | Independent skeptic agents who try to *refute* each claim before we rely on it; verdicts are **confirmed / disputed / unresolved** and are never upgraded. Claims no panel has adjudicated are marked UNVERIFIED and quarantined from headline use |
| **structural rule-out** | An exclusion that no parameter tuning can rescue — the failure is in the theory's form (wrong sign, wrong range), not its calibration |

*"The honest path forward is to publish exactly what survived."*
