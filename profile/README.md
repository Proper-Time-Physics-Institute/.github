# Proper-Time Physics Institute

**An adversarial verification program for the proper-time ("dual") formulation of relativity and quantum mechanics** (T. L. Gill and collaborators) — the reformulation built on proper time τ as evolution parameter, the positive-definite Hamiltonian K = H²/2mc² + mc²/2, and the collaborative speed b = √(c² + u²).

We take the framework seriously enough to *test it* — derivation by derivation, against the published record and against precision data — and we publish what we find, whichever way it goes. So far, what we have found is that **the framework is empirically refuted**: every sector tested either reduces to standard physics exactly or deviates and is excluded by existing data — a pattern that has hardened, across gravity, quantum coherence, electrodynamics, precision metrology, relativistic quantum information, strong-field QED, and now from the laboratory out to cosmological baselines, into a **structural no-go**: *wherever the theory is well-defined it is inert (standard physics), and wherever it is distinctive it is excluded, with the two regimes provably disjoint.* The consolidated statement is the [**Well-defined ⟺ Inert capstone**](https://github.com/Proper-Time-Physics-Institute/commons/blob/main/graph/DISJOINTNESS_NOGO_CAPSTONE.md), rendered as a living, honesty-gated [anthology](https://github.com/Proper-Time-Physics-Institute/commons/tree/main/graph/anthology) built from the cross-repo knowledge graph.

| Contents | |
|---|---|
| [🎯 What we do](#-what-we-do) | the derive → compute → adversarially-verify → publish pipeline |
| [📌 What we've established](#-what-weve-established) | the verdict, sector by sector |
| [📊 Experimental scoreboard](#-experimental-scoreboard) | every adjudicated comparison: exclusions and identities |
| [❓ Open questions](#-open-questions-for-the-programs-authors) | where closure is conditional on an author's answer |
| [🌳 What happens next](#-what-happens-next--the-response-decision-tree) | the pre-registered decision tree for those answers |
| [🗂 Repository map](#-repository-map) | where everything lives |
| [🧭 How the org runs](#-how-the-org-runs) | the operating rules |
| [📍 Where things stand](#-where-things-stand-august-2026) | status as of August 2026 |
| [📖 Glossary](#-glossary) | every symbol and shorthand, in plain language |

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
- **Classical electromagnetism** — the proper-time Liénard–Wiechert field is *identically* the classical field (no third-term signature, no longitudinal radiation); the radiation-reaction force is exactly Lorentz–Abraham–Dirac, runaways included (Wolfram-verified path derivation); and in a **dispersive medium** (Cherenkov, dispersion, the Eq. (4) dissipative term) it is again *identically* macroscopic Maxwell — the last open EM context, now closed, with the medium "bare-equation" escape hatch not merely inert but **empirically falsified** by channeling radiation-reaction data
- **QED** — the electron anomalous moment a_e is inherited from QED, not derived (probes P0–P6 all close); the celebrated closed form r_e/r₀ = (2−a_e)/(2(2+a_e)) is an algebraic identity, and the six-observable "triangulation" is one back-fit applied six times
- **Gravity** — the dual Newtonian force law (the paper's own V + V²/2mc² gravitational substitution) gives exactly **−1/6 of GR's Mercury perihelion advance**; Corda's πm/M "precession" is refuted by Bertrand's theorem
- **Precision spectroscopy (the falsifier)** — the published g-factor chain contradicts the paper's own Eq. (III.8) by a factor of 2; the internally consistent corrected formula g_r(x) = 2(2x−1)/(2x+1) has range (−2, 2), so **no cutoff r_e > 0 can reproduce the measured electron g**; and the framework's own operators, evaluated self-consistently, predict a **+30.6% universal s-state hyperfine anomaly** excluded by existing data
- **The published record** — erratum-grade corrections proven against the sources: Gill–Zachary Eq. (24) (missing c and V²/2mc² terms), DRQM-I §III.D (published r_e gives g = −2.00057, not −2.00232), the TCEP group-velocity chain (4.12)/(4.15)/(4.16) — transcription, underivability, and sign (E-3w, widened per the T1b dissolution), DRQM-I's (III.8)→(a,b,c) factor-2, and a corrigendum case for J. Phys. Conf. Ser. 2482 (2023), which reprints the erroneous equations
- **Foundations — is proper time physically *fundamental*?** *(2026-08)* The deepest question — whether taking τ as a genuine primitive (not a reparametrization) yields *any* distinctive, viable physics — was pushed to its floor and has kept failing the same way in every new sector opened. The core arc (gravity's c→b dynamics and metric readings, off-shell SHP, 2T-physics, varying-constants, entropic gravity, Tomita–Takesaki *thermal time*, objective-collapse, the colored-noise corner) established a **structural no-go**: *well-defined ⟺ inert* — a consistent construction reduces to standard physics; a distinctive one is excluded; the regimes are disjoint. Later sectors only widened it: four quantum campaigns *(2026-08-24: precision metrology, relativistic quantum information, strong-field QED, condensate physics)* all landed inert-or-excluded; the missing **dual photon propagator D_dual** forks inert / massive-wrong-sign / ghost-tachyon; the relativistic single-particle equations are unitarily equivalent to standard Dirac; and a **cosmological-scale sweep** *(cosmic birefringence, the GZK threshold, GRB spectral lags, the Weyl-curvature initial condition)* returned four fresh NO-GOs — each by a different route, extending the law from the lab out to 10²⁶ m. Its hard number is a **world-class null bound on any physical off-shell rest-mass fraction**, from optical-clock coherence — Δm/m < 9.7×10⁻²⁹ (Sr-87), sharpened ~2 orders by the metrology campaign (Yb⁺ → 1.06×10⁻³⁰), where *tightening the bound widens* the observable-vs-excluded gap. The one genuine, non-illusory positive is a **computational-methods** advance: the positive-energy, bounded-below square-root operator variationally *enables* relativistic neural-VMC where naive Dirac collapses (Brown–Ravenhall) — standard physics computed more stably, not distinctive proper-time content, and it does not reach a_e. Not a universal theorem, but no natural construction has evaded it *(capstone + living anthology; consolidation manuscript in submission prep)*

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
| Local-gate propagator candidate λ(−a·a/m²)^{1/3} — and the whole monomial gate sector | Si¹³⁺ bound-electron g-factor (8.5×10⁻¹⁰ relative) | shift ≈872× the allowed margin (sector-wide ~870×) | excluded |
| H 21-cm hyperfine — corrected (III.20) | 1 420 405 751.768(2) Hz | **+435.2 MHz (+30.6%)** | **1088×** the campaign floor — the falsifying line |
| Muonium hyperfine — corrected (III.20) | 4 463 302 776(51) Hz | +1 367.5 MHz (the same universal +30.6%) | excluded |
| H 1S–2S — (III.19) μ² channel | 2 466 061 413 187 035(10) Hz | +182.4 kHz | ≥10³× the campaign floor |
| H–D isotope shift — (III.19) μ² scaling | measured at the ~15 Hz level | ~165 kHz anomaly | ~10⁴× |
| Parameter-free τ-reading of the exact spectral map K_D | the three transitions above (1S–2S · 21-cm · muonium HFS) | −41.06 GHz · −37.8 kHz · −118.8 kHz | excluded at 10³–10⁹σ (muonium: 2330σ) |
| Off-shell rest-mass content — proper-time-as-*fundamental* (SHP) | Sr-87 optical-clock coherence (118 s); sharpened on Yb⁺ / ²²⁹Th | any physical Δm/m ≥ 9.7×10⁻²⁹, sharpened to ≥ 1.06×10⁻³⁰ (Yb⁺) | excluded — Δ(mc²) < 7.9×10⁻¹⁸ eV; *tightening the bound widens* the observable-vs-excluded scissors (16.5 → 18.65 orders) — the program's sharpest null bound |
| Binary-pulsar periastron ω̇ — proper-time dynamics (any coupling) | J0737−3039 (theory-independent mass ratio) | factor-2 miss (M²+m² vs the Mm cross term) | excluded ≈2× / requires an unphysical 2.8× mass inflation |

**Where it agrees, it agrees by identity** — the framework reduces to standard physics exactly, so agreement carries no evidential weight:

| Observable | Result |
|---|---|
| GPS clock rates (+38.54 μs/day) | reproduced via b = γc — agreement-by-construction |
| Time dilation, velocity composition | identical to special relativity |
| Liénard–Wiechert radiation fields | identically the classical field (symbolic residual ≡ 0) |
| Radiation reaction † | exactly Lorentz–Abraham–Dirac, runaway/pre-acceleration dichotomy intact |
| Free-electron a_e with D = 1/k² | QED's α/2π inherited, not derived |
| Cherenkov / dispersion in a medium | identically macroscopic Maxwell (b and c/n never compete) |
| Einstein-delay γ in a binary pulsar (1PN) | reproduces GR exactly via the c/b clock identity (a reinterpretation, not a new signal) |

**Program verdict:** no unconditional surviving prediction — the one falsifiable residue is the conditional a_e(B) trap-slope test below; the org's real assets are its verification discipline, its errata, and its structural rule-outs — now consolidated into the multi-sector *well-defined ⟺ inert* no-go against proper-time-*as-fundamental* (see *Foundations* above), spanning the laboratory out to cosmological scales, plus a world-class Δm/m null bound and one honest computational-methods positive (bounded-below relativistic neural-VMC) — and those are exactly what we are writing up.

## ❓ Open questions for the program's authors

The pipeline's fourth outcome — precisely-stated open questions routed back to the framework's authors. These are the places where the program's closure is *conditional* and an author's answer (or a one-page result) changes the conclusion:

| # | Question | What's established | What would resolve it |
|---|---|---|---|
| 1 | **"QED III" — does a genuine dual photon propagator D_dual(k) exist?** | a_e is not derivable by probes P0–P6; the problem is now a well-posed constraint set (C0–C3 + C3′, anchored by bound-state g-factor data to 8.5×10⁻¹⁰). Panel-confirmed: source-independent kernels deliver ≤ 9.7×10⁻⁴ of the bound (Zα)² term; an acceleration-gated kernel is not a Fock two-point function; the entire monomial local-gate sector is excluded ≈870× by Si¹³⁺ data; and the exclusion holds **circularity-free** (a proton-electron-mass-chain bound of ≈417× that avoids the m_e-dependence of the C⁵⁺ data). The surviving class is worldline-memory gates — now shown spectrum-dependent, with the classification exhaustive for a_e-class observables | A construction satisfying C0–C3 + C3′ outside the closed branches (the un-killed memory-gate class is where it would have to live) — or acceptance that a_e is inherited from QED |
| 2 | **Gap G3 — the cross-coupling loophole** *(CLOSED 2026-08-09/11)* | **Resolved in the closure direction, panel-adjudicated:** for every hermitian stationary functional the growing commutator branch survives in a quadrature no real moments can cancel, so every cross kernel on every admixture is non-tempered; dropping hermiticity leaves exactly one tempered point, realizable by no state in any metric. **Route F closes; the caveat ledger is G1 only**, conditional on one explicitly flagged definitional axiom (A2, hermiticity — itself 3/3-confirmed) | Closed. A principled challenge to axiom A2, or a non-stationary (in-in) formulation — explicitly out of the current scope — would be required to reopen it |
| 3 | **Gap G1 — multimode, τ-dependent gating** | The single-mode, constant-Γ reduction (assumption A1, inherited from the a_e probe series) is unjustified for bound orbits, where g(τ) = (u·a)/b⁴ varies along the orbit | A derivation of the mode reduction for bound orbits, or a multimode version of the no-go |
| 4 | **The factor-2 fork — which g-factor algebra is intended?** | The published g_r chain contradicts the paper's own Eq. (III.8) by a factor of 2 — unconditional, whichever side is blamed. If (III.8) stands, the corrected formula g_r(x) = 2(2x−1)/(2x+1) cannot reach the electron g for any r_e > 0 | The authors adjudicate the E-5 correction: affirm (III.8) (the back-fit dies) or repair the chain some third way |
| 5 | **t- vs τ-reading of the spectral operator K_D** | The exact map admits exactly two readings: the t-reading is identical to Dirac/QED (predicts nothing new); the τ-reading gives parameter-free shifts excluded at 10³–10⁹σ | The authors state which reading the framework intends — both horns are closed, so the choice selects *which* closure applies |
| 6 | **TCEP (4.15) — can the group-velocity claim be rescued?** | Panel-confirmed dissolution: (4.15) is underivable from (4.12) under *both* the printed γ² and corrected γ readings, fails at O(1) on the paper's own worldline class (the transformation gives 0.875 where the paper claims 1.25), and (4.16) carries no physical content in either sign | A derivation outside both readings — or withdrawal of the claim |

**One clean experiment falls out of #1:** if the a_e route is rescued by an acceleration-gated kernel, it predicts a trap-field-linear shift δa_e ≈ 1.9–2.1×10⁻¹³ at 5.36 T (slope 3.9×10⁻¹⁴/T; 1.4–1.6σ of current precision) — so measuring the a_e(B) slope against zero is a model-independent null test of the entire gated-kernel hypothesis, unconstrained by existing single-field data. *(Prediction halved 2026-08-11 when the repair dispatch resolved a factor-2 normalization in the constraint set — the same fix that strengthened the candidate exclusion to ≈872×.)* **Status — DORMANT (2026-08-26 frontier scan):** valid *in kind* (standard QED predicts an exactly-zero slope, and no a_e(B) slope is constrained by existing single-field data), but not currently promotable to an experimental proposal — the specific 3.9×10⁻¹⁴/T magnitude belongs to a gate *already* excluded ≈872× by Si¹³⁺ data, the only un-killed branch (worldline-memory gate, gap G1) fixes no magnitude, and even that number sits ~10× below the reach of an unbuilt trap-field-scan. Recorded as the sole surviving falsifiable residue; awaits either a definite magnitude from the memory-gate class or a several-fold B-scan precision gain.

## 🌳 What happens next — the response decision tree

Each open question above is pre-registered as a fork. The analysis already closed *both* horns of each question, so an author's answer doesn't reopen research — it selects which verified result becomes operative. Every branch obeys the same invariants: new claims are panelled before we rely on them, nothing ships externally without sign-off, no verdict is upgraded because a conversation went well — and **silence is a handled case on every branch**, so the program never blocks on a response.

**A — The factor-2 fork** *(question 4; the most consequential answer)*
- ✅ *Affirm Eq. (III.8)* → the published chain is the wrong side; the corrected formula governs; the back-fit is dead; the falsification note becomes unconditional on its central pillar
- 🔁 *Defend the chain / propose a third repair* → the repair is a new mathematical claim: its own track, a 3-lens adversarial panel, and a re-run of the back-fit solvability scan against it
- 🕐 *No answer* → publish with the fork documented — the contradiction itself is unconditional whichever side is blamed

**B — t- vs τ-reading of K_D** *(question 5; cheap to answer, clarifies every downstream paper)*
- *t-reading* → the framework is identical to Dirac/QED and predicts nothing new; we cite the equivalence
- *τ-reading* → the parameter-free exclusions (10³–10⁹σ) apply; we cite the falsification
- *A third reading* → new physics content: formalize it, panel it, re-derive the observables

**C — QED III / a dual photon propagator** *(questions 1–3; the only branch that can produce a positive result)*
- 📥 *A construction is supplied* → run the Spec A constraint harness (C0–C3 + C3′), apply the two panel-confirmed kill tests (source-independent kernels deliver ≤ 9.7×10⁻⁴ of the bound term; gated kernels aren't Fock two-point functions), and check it threads gap G3 — with acceptance criteria fixed *before* we see the candidate, so no goalposts move in either direction
- 🚫 *None* → the a_e story publishes as the honest capstone: inherited from QED, all articulated escape routes closed modulo G1 + G3

**D — Proper-Time gravity** *(cost-gated, cheapest check first)*
- Any candidate must first be shown to sit *outside* the potential-in-mass kernel class — which already fails light bending and Shapiro delay for every coupling — then pass, in order: light bending at the Cassini bound → Shapiro sign → Mercury +42.99″/century. No panel investment until the free paper-checks pass
- *Not pursued* → the Mercury −1/6 Research Note proceeds unchanged

**E — TCEP group velocity** *(question 6; smallest branch)*
- *Withdraw* → folded into the E-3w erratum as author-accepted
- *A new derivation* → must live outside both panel-dissolved readings; panel before anything else

The design intent: author input is *valuable* — it can flip which paper gets written, or open the program's first positive finding — but never *load-bearing*. If the submission gate arrives with no response, the record publishes as it stands.

## 🗂 Repository map

| Repo | Role |
|---|---|
| **[quantum](https://github.com/Proper-Time-Physics-Institute/quantum)** | Dirac/DRQM verification, precision spectroscopy, the a_e probe series, the T2b falsifier paper |
| **[electromagnetic](https://github.com/Proper-Time-Physics-Institute/electromagnetic)** | Jackson canonical problems in proper time, Liénard–Wiechert & radiation reaction |
| **[relativistic-dynamics](https://github.com/Proper-Time-Physics-Institute/relativistic-dynamics)** | Mercury perihelion (and the −1/6 paper), GPS relativity, classical-electron problem, TCEP |
| **[commons](https://github.com/Proper-Time-Physics-Institute/commons)** | The hub: unified bibliography, cross-repo synthesis, errata packets, review reports, the **cross-repo knowledge graph**, the **Well-defined ⟺ Inert capstone + living anthology**, and the **coordination queue** |
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
- ✅ **Foundational proper-time-*as-fundamental* arc** complete *(2026-08-13 → 15)* — 8 adversarial reports across gravity, quantum coherence, and electromagnetics; the six-mechanism *well-defined ⟺ inert* no-go and the **Δm/m < 9.7×10⁻²⁹** bound; and the **electromagnetic research path closed out** (all issues resolved, the medium / route-(iii) and Cherenkov-cone consistency fixes on `main`)
- ✅ **Frontier campaigns + capstone** *(2026-08-24 → 26)* — four more quantum campaigns (precision metrology, relativistic quantum information, strong-field QED, condensate) and a **cosmological-scale sweep** (cosmic birefringence, GZK threshold, GRB spectral lags, Weyl curvature) all closed **inert-or-excluded**; the metrology bound sharpened ~2 orders (Yb⁺ → 1.06×10⁻³⁰); the whole program consolidated as the **Well-defined ⟺ Inert capstone** plus a living, honesty-gated **anthology** (v0.5.0) rendered from the cross-repo knowledge graph
- 🔬 **Relativistic neural-VMC methods thread** *(quantum #61–#65)* — the positive-energy square-root-operator route computes relativistic atomic-shift observables stably where naive Dirac VMC collapses (a genuine **computational-methods** positive: standard physics computed more stably, **not** distinctive proper-time content, does **not** reach a_e); cusp mixing solved and scaling to N=10, the current frontier a precisely-diagnosed fixed-node / operator-variance floor on many-electron nets
- 🔄 **In preparation, drafted and adversarially verified, awaiting author sign-off:** the Mercury −1/6 paper (a standalone Research Note for *General Relativity and Gravitation*), the T2b hyperfine falsification note, the errata packet (E-1 / E-2 / E-3w / E-5 + JPCS corrigendum), and the **proper-time-gravity viability paper** — *No distinctive proper-time gravity: a viability arc across three constructions, with a world-class off-shell rest-mass bound* (arXiv gr-qc → *Phys. Rev. D*; bibliography staged in commons #29). DRQM-I is unpublished and its correction is co-author self-correction
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
| **G1, G2, G3** | The numbered gaps in the a_e closure argument (see Open questions): G2 and G3 are now proven/closed (G3 conditional on the hermiticity axiom A2); G1 (multimode gating) is the one that remains open |
| **t-reading vs τ-reading** | The two possible physical interpretations of the framework's spectral operator: evolve in coordinate time (→ identical to Dirac/QED) or in proper time (→ excluded shifts) |
| **campaign floor** | Our own conservative precision floor for each observable — the loosest error bar we allow ourselves when claiming an exclusion |
| **adversarial panel** | Independent skeptic agents who try to *refute* each claim before we rely on it; verdicts are **confirmed / disputed / unresolved** and are never upgraded. Claims no panel has adjudicated are marked UNVERIFIED and quarantined from headline use |
| **structural rule-out** | An exclusion that no parameter tuning can rescue — the failure is in the theory's form (wrong sign, wrong range), not its calibration |

*"The honest path forward is to publish exactly what survived."*
