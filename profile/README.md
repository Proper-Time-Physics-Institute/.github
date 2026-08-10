# Proper-Time Physics Institute

**An adversarial verification program for the proper-time ("dual") formulation of relativity and quantum mechanics** (T. L. Gill and collaborators) — the reformulation built on proper time τ as evolution parameter, the positive-definite Hamiltonian K = H²/2mc² + mc²/2, and the collaborative speed b = √(c² + u²).

We take the framework seriously enough to *test it* — derivation by derivation, against the published record and against precision data — and we publish what we find, whichever way it goes.

---

## 🎯 What we do

Every claim in the framework's corpus is pushed through the same pipeline:

1. **Derive** — independent re-derivation from the primary sources, in writing, with a PROVEN / ASSUMED / OUT-OF-SCOPE ledger
2. **Compute** — reproducible Wolfram Language scripts as the generator of record for every number and figure
3. **Adversarially verify** — independent skeptic panels (re-derivation lens, assumption-completeness lens, numeric lens) actively try to refute each load-bearing claim
4. **Publish honestly** — verdicts are *confirmed / disputed / unresolved* and are never upgraded; refuted claims are quarantined in the record, not deleted

The output is one of four honest outcomes: an **exact equivalence** with standard physics, a **correction** to the published record, a **rule-out** against data, or a precisely-stated **open question** routed back to the framework's authors.

## 📌 What we've established (high level)

Two months of org-wide review (32 panel verdicts) plus a follow-up research campaign (27 panel verdicts) converge on a clear picture:

- **Kinematics** — b = γc *exactly*: the "collaborative speed" is celerity bookkeeping, not a new signal speed; proper-time GPS/time-dilation agreement is agreement-by-construction
- **Classical electromagnetism** — the proper-time Liénard–Wiechert field is *identically* the classical field; the proper-time radiation-reaction force is exactly Lorentz–Abraham–Dirac, runaways included
- **QED** — the electron anomalous moment is inherited from QED, not derived; the celebrated closed-form r_e relation is an algebraic identity fit once and reused
- **Gravity** — the dual Newtonian force law gives exactly **−1/6 of GR's Mercury perihelion advance** (wrong sign, wrong magnitude): a structural rule-out
- **Precision spectroscopy** — evaluated self-consistently, the framework's own operators predict hyperfine shifts excluded by existing data by ≥3 orders of magnitude; a falsification analysis is in preparation
- **The published record** — a small set of erratum-grade corrections to published equations has been proven and is being coordinated with the authors

**Program verdict:** no distinct surviving prediction; the org's real assets are its verification discipline, its corrections, and its structural rule-outs — and those are exactly what we are writing up.

## 🗂 Repository map

| Repo | Role |
|---|---|
| **[quantum](../../quantum)** | Dirac/DRQM verification, precision spectroscopy, the a_e probe series |
| **[electromagnetic](../../electromagnetic)** | Jackson canonical problems in proper time, Liénard–Wiechert & radiation reaction |
| **[relativistic-dynamics](../../relativistic-dynamics)** | Mercury perihelion, GPS relativity, classical-electron problem, TCEP |
| **[commons](../../commons)** | The hub: unified bibliography, cross-repo synthesis, paper pipeline, review reports, **coordination queue** |
| **[Proper-Time-Physics-Institute.github.io](../../Proper-Time-Physics-Institute.github.io)** | Public website (Astro), assembled from repo content at build time |
| [pyphysics-mcp](../../pyphysics-mcp) · [precision-data-mcp](../../precision-data-mcp) | MCP servers for computation and precision-data lookup |
| [animations](../../animations) · [podcasts](../../podcasts) · [branding](../../branding) · [tooling](../../tooling) | Shared media and infrastructure |

Split from the former `PyPhysics` monorepo (archived, read-only) with per-file history preserved.

## 🧭 How the org runs

- **Nothing merges to a topic-repo `main` without human review.** Research lands as PRs on dated review/research branches; merge order is managed through an explicit queue.
- **Nothing leaves the org without a human.** Erratum letters, comment papers, and submission packets are drafted and verified by agents, but every external send is a human decision with author sign-off.
- **Citations are never fabricated.** Bibliography notes carry `human_reviewed` flags that only a human may set, and unverified metadata is marked TODO-verify rather than guessed.
- **Multi-agent, adversarial by default.** Large reviews run as orchestrated workflows: parallel per-repo reviewers → independent verification panels → synthesis, with every load-bearing claim panelled before it is relied on.

## 📍 Where things stand *(August 2026)*

- ✅ **2026-07-05 org-wide review** complete — 143-page report, 32 adversarial verdicts, org knowledge graph
- ✅ **Tier 1–4 research campaign** complete — 7 tracks, 27 panelled claims, headline falsification result
- ✅ **All review, research, and errata work merged to `main`** across the four research repos (2026-08-07) — every `main` now tells the corrected story
- 🔄 **In preparation:** a Mercury perihelion Comment, a hyperfine falsification note, and published-record errata — all drafted, verified, and awaiting author sign-off
- 🗓 Coordination: see the open decision queue in **[commons](../../commons)** issues

*"The honest path forward is to publish exactly what survived."*
