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

- **Kinematics** — b = γc *exactly*: the "collaborative speed" is celerity bookkeeping, not a new signal speed; proper-time GPS/time-dilation agreement is agreement-by-construction
- **Classical electromagnetism** — the proper-time Liénard–Wiechert field is *identically* the classical field (no third-term signature, no longitudinal radiation); the proper-time radiation-reaction force is exactly Lorentz–Abraham–Dirac, runaways included
- **QED** — the electron anomalous moment a_e is inherited from QED, not derived (probes P0–P6 all close); the celebrated closed form r_e/r₀ = (2−a_e)/(2(2+a_e)) is an algebraic identity, and the six-observable "triangulation" is one back-fit applied six times
- **Gravity** — the dual Newtonian force law gives exactly **−1/6 of GR's Mercury perihelion advance** (wrong sign, one-sixth magnitude): a structural rule-out. Corda's πm/M "precession" is refuted by Bertrand's theorem
- **Precision spectroscopy (the falsifier)** — the published g-factor chain contradicts the paper's own Eq. (III.8) by a factor of 2, and the internally consistent corrected formula g_r(x) = 2(2x−1)/(2x+1) has range (−2, 2), so **no cutoff r_e > 0 can reproduce the measured electron g**. Evaluated self-consistently, the framework's own operators predict a **+30.6% universal s-state hyperfine anomaly** — +435.2 MHz on the 21-cm line, **1088×** our own conservative precision floor — and the joint (g, 21-cm) system has no solution
- **The published record** — erratum-grade corrections proven against the sources: Gill–Zachary Eq. (24) (missing c and V²/2mc² terms), DRQM-I §III.D (published r_e gives g = −2.00057, not −2.00232), TCEP Eq. (4.16) (sign), DRQM-I's (III.8)→(a,b,c) factor-2, and a corrigendum case for J. Phys. Conf. Ser. 2482 (2023), which reprints the erroneous equations

**Program verdict:** no distinct surviving prediction; the org's real assets are its verification discipline, its errata, and its structural rule-outs — and those are exactly what we are writing up.

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
