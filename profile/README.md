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

Two months of org-wide review (32 adversarial panel verdicts) plus a follow-up Tier 1–4 research campaign (27 verdicts) converge on a clear picture:

- **Kinematics** — b = γc *exactly*: the "collaborative speed" is celerity bookkeeping, not a new signal speed
- **Classical electromagnetism** — the proper-time Liénard–Wiechert field is *identically* the classical field (no third-term signature, no longitudinal radiation); the radiation-reaction force is exactly Lorentz–Abraham–Dirac, runaways included
- **QED** — the electron anomalous moment a_e is inherited from QED, not derived (probes P0–P6 all close); the celebrated closed form r_e/r₀ = (2−a_e)/(2(2+a_e)) is an algebraic identity, and the six-observable "triangulation" is one back-fit applied six times
- **Gravity** — the dual Newtonian force law gives exactly **−1/6 of GR's Mercury perihelion advance**; Corda's πm/M "precession" is refuted by Bertrand's theorem
- **Precision spectroscopy (the falsifier)** — the published g-factor chain contradicts the paper's own Eq. (III.8) by a factor of 2; the internally consistent corrected formula g_r(x) = 2(2x−1)/(2x+1) has range (−2, 2), so **no cutoff r_e > 0 can reproduce the measured electron g**; and the framework's own operators, evaluated self-consistently, predict a **+30.6% universal s-state hyperfine anomaly** excluded by existing data
- **The published record** — erratum-grade corrections proven against the sources: Gill–Zachary Eq. (24) (missing c and V²/2mc² terms), DRQM-I §III.D (published r_e gives g = −2.00057, not −2.00232), TCEP Eq. (4.16) (sign), DRQM-I's (III.8)→(a,b,c) factor-2, and a corrigendum case for J. Phys. Conf. Ser. 2482 (2023), which reprints the erroneous equations

## 📊 Experimental scoreboard

Every quantitative comparison the program has adjudicated. "Framework" values are the framework's **own operators and formulas evaluated self-consistently** at its published cutoff; every row below is adversarial-panel-confirmed.

**Where it deviates, it is excluded:**

| Observable | Measured | Framework | Margin |
|---|---|---|---|
| Mercury perihelion advance | +42.99″/century (obs. ≈ 43″) | **−7.17″/century** (exactly −Δφ_GR/6, eccentricity-independent) | wrong sign, ⅙ magnitude — structural rule-out |
| Venus / Earth perihelion residuals (Corda πm/M) | observed residuals | 30× / 51× over-prediction | excluded; not a precession (Bertrand) |
| Electron g — published back-fit (DRQM-I §III.D) | −2.002 319 304 362 56 | −2.000 571 48 from the published r_e/r₀ | off by 1.7×10⁻³ → erratum E-2 |
| Electron g — corrected algebra | −2.002 319 304 362 56 | g_r(x) = 2(2x−1)/(2x+1), range (−2, 2) | **no solution for any r_e > 0** |
| Free a_e — any static propagator modification at the r_e scale | a_e experimental tolerance | shift of 514–40 000× tolerance | excluded |
| H 21-cm hyperfine — corrected (III.20) | 1 420 405 751.768(2) Hz | **+435.2 MHz (+30.6%)** | **1088×** the campaign floor — the falsifying line |
| Muonium hyperfine — corrected (III.20) | 4 463 302 776(51) Hz | +1 367.5 MHz (the same universal +30.6%) | excluded |
| H 1S–2S — (III.19) μ² channel | 2 466 061 413 187 035(10) Hz | +182.4 kHz | ≥10³× the campaign floor |
| H–D isotope shift — (III.19) μ² scaling | measured at the ~15 Hz level | ~165 kHz anomaly | ~10⁴× |
| Parameter-free τ-reading of the exact spectral map K_D | 1S–2S · 21-cm · muonium HFS | −41.06 GHz · −37.8 kHz · −118.8 kHz | excluded at 10³–10⁹σ (muonium: 2330σ) |

**Where it agrees, it agrees by identity** — the framework reduces to standard physics exactly, so agreement carries no evidential weight:

| Observable | Result |
|---|---|
| GPS clock rates (+38.54 μs/day) | reproduced via b = γc — agreement-by-construction |
| Time dilation, velocity composition | identical to special relativity |
| Liénard–Wiechert radiation fields | identically the classical field (symbolic residual ≡ 0) |
| Radiation reaction | exactly Lorentz–Abraham–Dirac, runaway/pre-acceleration dichotomy intact |
| Free-electron a_e with D = 1/k² | QED's α/2π inherited, not derived |

**Program verdict:** no distinct surviving prediction; the org's real assets are its verification discipline, its errata, and its structural rule-outs — and those are exactly what we are writing up.

## ❓ Open questions for the program's authors

The pipeline's fourth outcome — precisely-stated open questions routed back to the framework's authors. These are the places where the program's closure is *conditional* and an author's answer (or a one-page result) changes the conclusion:

| # | Question | What's established | What would resolve it |
|---|---|---|---|
| 1 | **"QED III" — does a genuine dual photon propagator D_dual(k) exist?** | a_e is not derivable by probes P0–P6; the problem is now a well-posed constraint set (C0–C3 + C3′, anchored by bound-state g-factor data to 8.5×10⁻¹⁰). Panel-confirmed: source-independent kernels deliver ≤ 9.7×10⁻⁴ of the bound (Zα)² term, and an acceleration-gated kernel is not a Fock two-point function | A construction satisfying C0–C3 + C3′ outside the closed branches — or acceptance that a_e is inherited from QED |
| 2 | **Gap G3 — the cross-coupling loophole** | D_dual ≡ 0 in *every* quantization of the Bateman system (theorem, panel-confirmed) — but the panel found a 2-parameter family of stationary cross moments with an exponentially growing commutator branch [y(τ), x(0)] | A one-page-scale result: either the growing branch makes every stationary cross kernel inadmissible (Route F closes, caveat G1 only), or some admixture furnishes a finite admissible kernel — which would be a major *positive* finding |
| 3 | **Gap G1 — multimode, τ-dependent gating** | The single-mode, constant-Γ reduction (assumption A1, inherited from the a_e probe series) is unjustified for bound orbits, where g(τ) = (u·a)/b⁴ varies along the orbit | A derivation of the mode reduction for bound orbits, or a multimode version of the no-go |
| 4 | **The factor-2 fork — which g-factor algebra is intended?** | The published g_r chain contradicts the paper's own Eq. (III.8) by a factor of 2 — unconditional, whichever side is blamed. If (III.8) stands, the corrected formula g_r(x) = 2(2x−1)/(2x+1) cannot reach the electron g for any r_e > 0 | The authors adjudicate the E-5 correction: affirm (III.8) (the back-fit dies) or repair the chain some third way |
| 5 | **t- vs τ-reading of the spectral operator K_D** | The exact map admits exactly two readings: the t-reading is identical to Dirac/QED (predicts nothing new); the τ-reading gives parameter-free shifts excluded at 10³–10⁹σ | The authors state which reading the framework intends — both horns are closed, so the choice selects *which* closure applies |
| 6 | **TCEP Eq. (4.15) — is there a surviving derivation?** | (4.15) was never independently derived; under the standard dk′/dτ transformation the group-velocity non-invariance claim dissolves (the (4.16) sign erratum stands separately) | A derivation of (4.15) that does not reduce to the standard transformation — or withdrawal of the claim |

**One clean experiment falls out of #1:** if the a_e route is rescued by an acceleration-gated kernel, it predicts a trap-field-linear shift δa_e ≈ 3.7–4.1×10⁻¹³ at 5.36 T (slope 7.7×10⁻¹⁴/T) — so measuring the a_e(B) slope against zero is a model-independent null test of the entire gated-kernel hypothesis, unconstrained by existing single-field data.

## 🗂 Repository map

| Repo | Role |
|---|---|
| **[quantum](../../quantum)** | Dirac/DRQM verification, precision spectroscopy, the a_e probe series, the T2b falsifier paper |
| **[electromagnetic](../../electromagnetic)** | Jackson canonical problems in proper time, Liénard–Wiechert & radiation reaction |
| **[relativistic-dynamics](../../relativistic-dynamics)** | Mercury perihelion (and the Comment paper), GPS relativity, classical-electron problem, TCEP |
| **[commons](../../commons)** | The hub: unified bibliography, cross-repo synthesis, errata packets, review reports, **coordination queue** |
| **[Proper-Time-Physics-Institute.github.io](../../Proper-Time-Physics-Institute.github.io)** | Public website (Astro), assembled from repo content at build time |
| [pyphysics-mcp](../../pyphysics-mcp) · [precision-data-mcp](../../precision-data-mcp) | MCP servers for computation and precision-data lookup |
| [animations](../../animations) · [podcasts](../../podcasts) · [branding](../../branding) · [tooling](../../tooling) | Shared media and infrastructure |

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
- 🔄 **In preparation, drafted and adversarially verified, awaiting author sign-off:** the Mercury −1/6 Comment (GRG Research Note), the T2b hyperfine falsification note, and the errata packet (E-1 / E-2 / E-3w / E-5 + JPCS corrigendum). DRQM-I is unpublished and its correction is co-author self-correction
- 🗓 Coordination: the human decision queue and the realignment overview live in **[commons](../../commons)** issues

*"The honest path forward is to publish exactly what survived."*
