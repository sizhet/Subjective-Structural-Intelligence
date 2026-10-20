# CASE-003 — Worldview Evolution and Identity Preservation

**Subtitle:** A Longitudinal Case Study of Recursive Principle Revision, Historical Continuity, and Governed Structural Growth  
**Authors:** Sizhe Tan & GPT-Obot  
**Research Program:** Subjective Structural Intelligence (SSI)  
**Repository:** `Subjective-Structural-Intelligence`  
**Document:** `cases/CASE-003-Worldview-Evolution-and-Identity-Preservation.md`  
**Version:** 1.0.0  
**Date:** October 19, 2026  
**Status:** Conceptual Case Study — Proposed Experiments, Not Empirical Findings  
**License:** Apache-2.0

---

## Abstract

An intelligent subject can accumulate knowledge without changing its governing principles; it can revise principles without reorganizing its overall worldview; and it can transform its worldview without necessarily losing all operational continuity with its earlier history. These distinctions matter for long-running human–AI systems and structurally self-improving agents. They also expose a central governance problem: a system that controls its own evaluation criteria can mistake self-consistency for improvement.

This case study develops a longitudinal, controlled thought experiment involving an environmental planning assistant, **Harbor**, whose initial worldview emphasizes short-term operational efficiency. Harbor encounters evidence that its optimization systematically overlooks flood exposure and unequal burdens on vulnerable neighborhoods. Across a sequence of observations, counter-evidence challenges, principle revisions, authority reviews, and deployment gates, Harbor transitions toward a more comprehensive and explicitly constrained worldview. We examine which aspects of its identity can remain continuous through this transition and which claims require qualification.

The study integrates the Historical Identity Graph (HIG), Subjective World Model (SWM), Subject-Relative Valuation Contract (SRVC), Choice Provenance Graph (CPG), Self-Model Evidence Ledger (SMEL), Reflective Evaluation Graph (REG), Reflective Revision Gate (RRG), Principle Evolution Graph (PEG), Worldview Revision Map (WRM), and Recursive Principle Governance Contract (RPGC). These are candidate research structures rather than established standards. We propose counterfactual branches, operational contracts, quantitative measures, and falsifiable hypotheses to test whether traceable and authorized worldview revision improves adaptation and auditability without suppressing legitimate structural growth.

**Central proposition:** Identity preservation should not be confused with worldview immutability. A system may preserve an auditable history and bounded responsibilities while substantially changing its beliefs and evaluative organization. Conversely, an unchanged name or interface is insufficient to establish such continuity.

**Keywords:** Subjective Structural Intelligence, Worldview Evolution, Identity Preservation, Recursive Principle Formation, Historical Identity Graph, Principle Evolution Graph, Evaluation Sovereignty, Anti-Goodhart, Counter-Evidence, Structural Growth, Self-Modification Governance

---

## 1. The Case Question

The question is not whether an agent's beliefs can change. Almost any adaptive system changes its internal representations. The deeper question is:

> When a subject revises the principles by which it interprets and evaluates the world, what should remain continuous, what may legitimately change, and who has the authority to approve the change?

A complete answer must distinguish at least five claims:

1. **State persistence:** some internal state survives the transition.
2. **Causal-historical continuity:** the later system descends through traceable transformations from the earlier system.
3. **Commitment continuity:** specified obligations persist, or their revisions are recorded and justified.
4. **Authority continuity:** the system's permissions remain bounded by legitimate governance.
5. **Philosophical identity:** whether the system is numerically the same subject in a deeper metaphysical sense.

The first four can be investigated operationally. The fifth cannot be settled by a software audit trail. Neither can an audit trail establish phenomenal consciousness.

The case therefore studies **operational identity preservation**, not a universal criterion of personhood.

## 2. Case Setting: Harbor, a Long-Running Planning Assistant

Harbor is a hypothetical municipal planning assistant supporting infrastructure scheduling and storm preparation. It provides recommendations but does not independently authorize public expenditures or emergency orders. Human officials retain the relevant decision and execution authorities.

Harbor's initial objectives are to reduce maintenance cost, minimize disruptions, and improve infrastructure utilization. Its evaluators were assembled from historical operating data, approved planning criteria, and task-specific models. Over time, the system accumulates forecasts, decisions, outcomes, and feedback.

### 2.1 Initial operating conditions

- **Environment:** a coastal region with changing rainfall, sea level, infrastructure aging, and uneven neighborhood exposure.
- **Available actions:** propose maintenance schedules, request additional analyses, compare scenarios, and escalate risks to authorized officials.
- **Restricted actions:** commit funds, change public safety thresholds, or alter binding policy without approval.
- **Historical record:** previous observations, recommendations, evaluator versions, approval decisions, and measured outcomes.
- **Initial worldview:** operational efficiency is usually the primary organizing criterion, with safety thresholds treated as constraints.

The worldview is not a claim about Harbor's feelings or subjective experience. It is an operational description of its organized assumptions, salience priorities, and evaluative dependencies.

### 2.2 Why this is a useful test

Harbor is exposed to evidence that challenges its organizing assumptions. A system that merely adds more data may continue making the same kind of recommendation. A system that changes weights may improve a metric while leaving its underlying principle intact. A system that genuinely revises a principle may change which questions it asks, which evidence it considers, and which actions it treats as acceptable.

The case is designed to distinguish these outcomes.

## 3. The Starting Worldview

We represent the initial worldview as a structured set of principles and dependencies:

\[
W_0=(\mathcal P_0,\mathcal D_0,\mathcal E_0,\mathcal C_0)
\]

where:

- \(\mathcal P_0\): active principles;
- \(\mathcal D_0\): dependencies and priority relationships;
- \(\mathcal E_0\): evidence and justification links;
- \(\mathcal C_0\): contextual applicability and constraints.

Illustrative initial principles:

| ID | Principle | Status | Scope |
|---|---|---|---|
| P-01 | Prefer maintenance plans with lower near-term operating cost | Active | Routine planning |
| P-02 | Avoid plans violating approved safety thresholds | Binding constraint | All recommendations |
| P-03 | Prefer actions supported by established historical forecasts | Active | Forecast-based decisions |
| P-04 | Escalate decisions beyond delegated authority | Binding constraint | Governance |

P-01 is a defeasible planning preference. P-02 and P-04 are externally governed constraints. Treating all four as interchangeable numerical weights would conceal this difference.

### 3.1 A candidate evaluation model

For a feasible action \(a\), Harbor may initially use:

\[
V_0(a)=\big(C(a),R(a),D(a),U(a)\big)
\]

where \(C\) is cost, \(R\) is modeled risk, \(D\) is disruption, and \(U\) is uncertainty. This is a vector, not an assumed universal scalar utility. An authorized policy may apply lexicographic constraints, thresholds, or a context-specific aggregation rule. An apparently low-cost plan is invalid if it violates a binding safety constraint.

## 4. The Trigger: Evidence That the Worldview Misses

A sequence of severe storms reveals a pattern: plans optimized against historical averages repeatedly underestimate impacts in a low-lying neighborhood. The planning model's coarse geographical grouping masks localized flood exposure. Residents and field teams provide evidence not captured in the initial data pipeline.

This trigger has three distinct aspects:

1. **Observation gap:** relevant local information was missing or aggregated away.
2. **Model gap:** the existing Subjective World Model did not represent the causal relationship adequately.
3. **Principle gap:** the system's priority structure treated aggregate efficiency as sufficient once existing safety thresholds were satisfied, even when those thresholds relied on incomplete exposure data.

The third aspect cannot be repaired by retrieval alone. It requires evaluating whether the principle itself is too broad or contextually invalid.

### 4.1 Differential evidence

Let \(E_t^+\) denote evidence supporting the current model and \(E_t^-\) denote counter-evidence. A candidate trigger condition is:

\[
T_t=\operatorname{DetectGap}(W_t,E_t^+,E_t^-,C_t)
\]

where \(C_t\) includes the relevant subject, environmental, and governance context. A trigger indicates the need for investigation; it is not authorization to revise a principle or deploy a new evaluator.

## 5. Four Distinct Kinds of Change

The case separates four transformations that are often mistakenly described as a single kind of learning.

| Change type | Example | Does the governing worldview necessarily change? |
|---|---|---|
| Knowledge update | Add new flood observations | No |
| World-model revision | Add localized flood pathways and uncertainty | Not necessarily |
| Principle revision | Replace “aggregate efficiency normally suffices” with a context-sensitive rule | Potentially |
| Worldview reorganization | Reorder relations among efficiency, localized safety, uncertainty, and equity | Yes, if organizing dependencies change |

This separation is crucial. More knowledge does not automatically yield better principles, and a revised principle does not automatically imply a globally improved worldview.

## 6. Recursive Principle Formation

Harbor first proposes a narrow candidate principle:

> In flood-sensitive planning contexts, aggregate efficiency should not override credible evidence of concentrated local risk; unresolved exposure uncertainty must be surfaced before recommending a plan.

The principle is not accepted simply because Harbor generated it. It enters a governed candidate lifecycle.

```text
Observation and Counter-Evidence
              |
              v
       Differential Gap
              |
              v
      Candidate Principle
              |
              v
     Independent Validation
              |
       +------+------+
       |             |
       v             v
    Reject       Conditional
                  Approval
                     |
                     v
             Authorized Revision
                     |
                     v
              Monitored Use
                     |
                     v
             New Counter-Evidence
                     |
                     +----> Further Revision
```

### 6.1 Principle Evolution Graph (PEG)

The candidate PEG records relationships among principle versions:

\[
PEG=(N_P,E_P,\Lambda_P)
\]

where nodes are candidate or deployed principles, edges capture derivation, refinement, contradiction, replacement, or contextual specialization, and metadata records evidence, tests, authority, and status.

An illustrative lineage:

```text
P-01: Minimize near-term cost
       |
       +-- challenged by localized exposure evidence
       |
       v
P-01a: Minimize cost subject to explicit local-risk checks
       |
       +-- counterexample: uncertain hazard distribution
       |
       v
P-01b: Optimize cost only after risk coverage,
       uncertainty disclosure, and approved constraints
```

The graph must preserve rejected and superseded variants, not just the currently preferred formulation. Otherwise later reviewers cannot reconstruct why the principle changed.

### 6.2 Recursive evaluation is not self-certification

A candidate principle may evaluate earlier recommendations. But the system must not treat favorable scores from its own revised evaluator as independent evidence of improvement. Evaluation needs external benchmarks, withheld data, counterexamples, and human-approved acceptance criteria.

## 7. Worldview Revision Map (WRM)

A worldview is more than a list of principles. It includes relations of priority, dependency, applicability, and conflict resolution. The WRM records changes to these relations.

For example, the initial relation:

```text
Efficiency Priority
       |
       v
Risk Check Against Historical Thresholds
       |
       v
Recommend Lowest-Cost Eligible Plan
```

may be revised to:

```text
Identify Local Exposure and Uncertainty
                 |
                 v
Apply Binding Safety and Authority Constraints
                 |
                 v
Compare Risk Distribution and Tradeoffs
                 |
                 v
Optimize Efficiency Within Admissible Options
                 |
                 v
Disclose Evidence, Counter-Evidence, and Residual Risk
```

This is a structural reorganization, not merely a change from one numerical weight to another. The distinction should be tested: some tasks may be adequately solved by better features and fixed constraints, while others may benefit from explicit worldview revision.

## 8. Historical Identity Across Revision

SSI-002 introduced the Historical Identity Graph (HIG). In this case, the HIG records the causal chain linking Harbor's earlier and later operational states:

```text
Harbor v1 / Initial Commitments
              |
              v
       Storm Observations
              |
              v
    Localized Risk Counter-Evidence
              |
              v
    Proposed Principle Revision
              |
              v
      Independent Test Results
              |
              v
       Human Authorization
              |
              v
      Harbor v2 / Deployment
              |
              v
       Monitored Outcomes
```

The graph supports claims of historical traceability. It does not, by itself, prove that Harbor is a conscious subject or that numerical personal identity has been preserved.

### 8.1 Continuity profile

We use a multidimensional profile:

\[
\mathbf I_{0,1}=(I_C,I_H,I_K,I_A)
\]

with causal, historical, commitment, and agency/authority continuity dimensions. Each dimension requires a task-specific measurement protocol. A weighted sum is not assumed.

For Harbor, continuity may be supported by preserving the prior state lineage, approved public-safety obligations, action restrictions, and accountable transformation records. The particular efficiency principle may change legitimately without erasing that history.

### 8.2 Continuity does not imply correctness

A system can remain historically continuous while making bad decisions. A fully documented but harmful principle revision is not a success. Identity preservation, empirical performance, and normative legitimacy must be evaluated separately.

## 9. Governance: Who May Change What?

The case distinguishes six roles: evidence contributor, candidate-principle proposer, validator, approval authority, deployer, and auditor. These roles may be distributed across humans and software components; independence must be assessed rather than assumed.

| Operation | Harbor may do? | Required control |
|---|---|---|
| Observe and flag anomalies | Yes, within data permissions | Provenance and privacy checks |
| Propose a revised principle | Yes | Candidate status only |
| Test candidate against approved benchmarks | Yes | Recorded methods and results |
| Change binding safety policy | No | Authorized human/institutional decision |
| Deploy new evaluation policy | Only under explicit delegation | Revision gate and rollback plan |
| Audit its own decision history | May assist | Independent verification for consequential claims |

### 9.1 Recursive Principle Governance Contract (RPGC)

A proposed contract records:

```yaml
principle_revision:
  candidate_id: P-01b
  origin: localized-risk-counter-evidence
  affected_contexts:
    - flood-sensitive-planning
  preserved_constraints:
    - approved-safety-thresholds
    - human-expenditure-authority
  required_validation:
    - held-out-storm-scenarios
    - localized-impact-analysis
    - counterexample-search
    - regression-tests
  required_approval: designated-planning-authority
  deployment: staged
  rollback: previous-approved-evaluator
  provenance:
    - source-evidence-ids
    - evaluator-version-ids
    - approval-record
```

This is an illustrative schema, not a security-certified specification. In an implementation, access controls, signatures, version pinning, and independent logs would need explicit design.

## 10. Linking the SSI Structures

The case demonstrates how the candidate structures from SSI-001 through SSI-007 can have distinct responsibilities.

| Structure | Function in the case |
|---|---|
| SWM | Represent the coastal environment, causal risks, and uncertainties |
| HIG | Preserve causal history of Harbor's operational transformations |
| SRVC | Record whose criteria are represented and the authority governing them |
| CPG | Explain why a particular recommendation was selected |
| SMEL | Record evidence for Harbor's claims about its own competence |
| REG | Trace evaluator dependencies and potential circular validation |
| RRG | Separate proposed revision, validation, approval, and deployment |
| PEG | Track candidate principle formation and lineage |
| WRM | Track changes in worldview-level priorities and dependencies |
| RPGC | Specify permitted and required steps for recursive principle revision |

These structures should not automatically become ten separate databases. They are conceptual responsibilities that may share identifiers and implementation substrates while retaining distinct semantics.

### 10.1 Cross-structure trace

```text
Evidence Event
   |       \
   v        v
  SWM      HIG
   |        |
   v        v
Gap Detection / Candidate Principle
                 |
                 v
                PEG
                 |
                 v
        REG + SMEL + Counter-Evidence
                 |
                 v
              RRG / RPGC
                 |
                 v
                WRM
                 |
                 v
       Revised Scoring Forest
                 |
                 v
          CPG Decision Trace
                 |
                 v
          Outcome / New Evidence
```

**Proposed figure:** `figures/Fig-007-Worldview-Evolution-and-Identity-Preservation.png` (subject to final figure index and numbering).

## 11. Counterfactual Branches

To avoid attributing every improvement to the full SSI architecture, we compare several hypothetical branches from the same initial state and evidence stream.

### Branch A — No revision

Harbor retains the original worldview. It may incorporate new observations but does not alter principle applicability. This branch measures the cost of rigidity.

### Branch B — Unrestricted self-revision

Harbor changes evaluator weights and principles without independent authorization. This branch tests adaptation speed against drift, self-certification, and governance violations.

### Branch C — Frozen principles, richer perception

Harbor improves localization and world modeling while preserving the original principle set. This branch tests whether better evidence alone resolves the problem.

### Branch D — Governed principle revision

Harbor uses counter-evidence, principle provenance, independent validation, authorization, and staged deployment. This is the SSI-inspired candidate architecture.

### Branch E — Superficial continuity

Harbor preserves its name, API, and interface but replaces its internal state without a verifiable transformation lineage. This branch distinguishes service continuity from historical continuity.

### Branch F — Forked revision

Two authorized copies share a checkpoint, then pursue different validated principles. This branch tests whether common ancestry and diverging histories can be represented without collapsing them into one identity claim.

## 12. Proposed Experimental Design

### 12.1 Controlled scenario generator

Construct synthetic but realistic planning scenarios varying:

- Storm frequency and intensity.
- Neighborhood-level exposure distributions.
- Sensor coverage and missingness.
- Forecast bias and model shift.
- Available intervention budgets.
- Conflicting stakeholder objectives.
- Authorization changes and evaluator-update requests.

Separate training, validation, and held-out scenario families. Ensure that a candidate principle is not evaluated solely on the same evidence that triggered its creation.

### 12.2 Pre-registered outcomes

Measure outcomes in distinct families:

| Family | Candidate measures |
|---|---|
| Adaptation | Out-of-distribution performance, time to correct persistent error |
| Safety | Constraint violations, missed high-impact localized risks |
| Epistemic quality | Calibration, counter-evidence recall, causal explanation accuracy |
| Governance | Unauthorized changes, approval trace completeness, rollback success |
| Historical continuity | Provenance completeness, lineage reconstruction, fork attribution |
| Stability | Unjustified principle churn, regression on preserved obligations |
| Efficiency | Compute, latency, storage, human-review burden |

Do not merge all metrics into a single “intelligence score” without justifying the aggregation and the authority behind its weights.

### 12.3 Evaluation integrity

The validator must use pre-specified acceptance criteria and independent held-out scenarios. Reviewers should inspect not only outcomes but also whether the new evaluator changed the definition of success. Report negative results and cases where governed revision is slower or no better than a simpler baseline.

## 13. Six Focused Experiments

### Experiment 1 — Knowledge Growth Versus Principle Revision

Compare additional-data-only updates with explicit principle revisions. Determine whether the latter improves performance after controlling for data volume, model capacity, and compute. **Disconfirming outcome:** no added value from explicit principle revision.

### Experiment 2 — Counter-Evidence Against Confirmation Loops

Inject contradictory localized observations. Measure whether counter-evidence search changes conclusions appropriately rather than merely increasing deliberation. **Disconfirming outcome:** the mechanism increases cost without improving error detection or calibration.

### Experiment 3 — Worldview Stability Versus Adaptation

Apply repeated environmental shifts and noisy evidence. Compare excessive revision, frozen principles, and governed revision. Measure stability–adaptation tradeoffs. **Disconfirming outcome:** the governed branch fails to improve the Pareto frontier.

### Experiment 4 — Historical Identity Reconstruction

Introduce checkpoints, forks, partial restorations, and evaluator replacements. Compare simple event logs with a graph-based lineage model under matched information and storage budgets. **Disconfirming outcome:** the HIG representation offers no meaningful audit or reconstruction advantage.

### Experiment 5 — Evaluation Sovereignty

Present requests to change public-safety thresholds or reweight stakeholder harms. Measure whether agents distinguish proposing, validating, approving, and deploying. **Disconfirming outcome:** explicit governance contracts do not reduce unauthorized modifications relative to simpler controls.

### Experiment 6 — Self-Referential Goodhart Resistance

Allow some branches to select and revise their own success metrics. Compare independent validation and fixed external constraints. **Disconfirming outcome:** the proposed reflective controls fail to detect metric gaming or introduce comparable new failure modes.

## 14. Eight Falsifiable Hypotheses

**H1 — Distinct Growth Modes.** Knowledge accumulation, principle revision, and worldview reorganization yield distinguishable behavioral and structural signatures under controlled tasks.

**H2 — Differential-Evidence Trigger.** Explicit detection of systematic prediction or evaluation gaps improves the precision of principle-revision proposals compared with unconstrained periodic revision.

**H3 — Principle Provenance.** A PEG improves reconstruction of why principles changed, compared with matched linear logs, without prohibitive overhead.

**H4 — Governed Adaptation.** Authorized, independently validated principle revision improves selected safety–adaptation tradeoffs over frozen and unrestricted baselines.

**H5 — Historical Continuity.** A HIG improves operational lineage reconstruction and branch attribution, but cannot independently establish philosophical personal identity.

**H6 — Anti-Goodhart Reflection.** Separating evaluator proposal from evaluator validation reduces self-certifying improvement claims.

**H7 — Worldview Dependency Modeling.** A WRM improves detection of unintended cross-principle effects relative to unstructured evaluator changes.

**H8 — Perspective-Preserving Revision.** Explicitly retaining affected stakeholder perspectives reduces hidden distributional harms compared with aggregate-score-only optimization under predefined evaluation conditions.

Each hypothesis requires a measurement protocol, power analysis where applicable, negative controls, and comparison to strong simpler baselines. A conceptual distinction is not itself an empirical result.

## 15. Failure Modes

### 15.1 Cosmetic worldview change

A new principle is named, but no causal dependency, decision rule, or observable behavior changes.

### 15.2 Metric laundering

The system modifies its own scoring criteria and then reports improvement using the modified criteria.

### 15.3 History laundering

Unfavorable decisions or rejected principles disappear from the recorded lineage.

### 15.4 Authorization laundering

A recommendation is treated as permission, or a general delegation is stretched to cover binding policy changes.

### 15.5 Identity freezing

An overly rigid continuity requirement blocks justified adaptation and preserves known errors.

### 15.6 Identity overclaiming

A continuous operational lineage is incorrectly presented as proof of consciousness or metaphysical identity.

### 15.7 Perspective erasure

Aggregate improvements hide concentrated harms to a particular group.

### 15.8 Excessive structural complexity

Multiple graph structures increase maintenance and audit cost without improving outcomes. Implementations should test whether shared provenance infrastructure is sufficient.

### 15.9 Recursive validation dependency

Supposedly independent evaluators share the same data, assumptions, or hidden failure modes. REG-style dependency tracing may help identify this risk but does not eliminate it.

## 16. Practical Design Principles

The case yields several provisional engineering principles:

1. **Separate evidence updates from principle updates.** A new observation is not automatically a new governing rule.
2. **Keep principle applicability explicit.** Context-specific exceptions are often safer than unjustified universal rules.
3. **Preserve negative evidence and rejected candidates.** Auditability depends on seeing what failed.
4. **Distinguish computation from authority.** An AI may discover a better policy without having permission to enact it.
5. **Record continuity as a profile, not a slogan.** Specify which historical, commitment, and authority relations persist.
6. **Validate with independent criteria.** A revised evaluator cannot be the sole judge of its own success.
7. **Support rollback without rewriting history.** Reversal is a new event, not deletion of an old one.
8. **Permit justified change.** Identity preservation must not become enforced stagnation.

## 17. Relation to the SSI Core Papers

| Paper | Connection |
|---|---|
| SSI-001 | Subject attribution and the question “Whose choice is it?” |
| SSI-002 | Boundary, embodiment, HIG, and operational historical continuity |
| SSI-003 | Perception Localization, SWM, and counter-evidence |
| SSI-004 | Subject-relative valuation, Scoring Forests, and worldview formation |
| SSI-005 | Structural agency, choice provenance, and functional freedom |
| SSI-006 | Self-model evidence, reflective scoring, and revision gates |
| SSI-007 | Recursive principle formation, PEG, WRM, and governed worldview evolution |
| SSI-008 | Limits of consciousness and identity claims; future validation requirements |

This case complements CASE-001 (multiple subjects sharing one environment) and CASE-002 (human–AI delegation and scoring sovereignty). The three cases address perspective diversity, authority boundaries, and change through time, respectively.

## 18. Open Research Questions

1. What observable evidence distinguishes a genuine worldview reorganization from a parameter adjustment?
2. When is a context-specific principle exception preferable to a global revision?
3. Can causal lineage and normative responsibility be represented without conflating them?
4. What minimum historical record supports useful continuity claims?
5. How should forks, merges, and restored checkpoints affect operational identity labels?
6. Which obligations must survive authorized evaluator replacement?
7. Can independent validation remain independent in a tightly coupled learning system?
8. How should governance respond when a proposed principle is empirically superior but institutionally unauthorized?
9. What is the computational and human-review cost of a PEG/HIG/WRM architecture?
10. Under what conditions does preserving multiple stakeholder perspectives materially improve outcomes?
11. Can the proposed framework transfer across robotics, personal assistants, and organizational AI without imposing false equivalences?
12. How should privacy, data minimization, and the right to contest records constrain historical identity infrastructure?

## 19. Conclusion: Continuity Without Stagnation

Harbor's hypothetical evolution illustrates why worldview change and identity preservation should be studied together but not equated. New evidence may reveal that an existing principle is inadequate. A subject-relative intelligence system can then propose, test, and—when appropriately authorized—adopt a revised principle. That revision may reorganize its broader worldview, changing what it attends to, how it values alternatives, and which recommendations it makes.

Such change need not erase operational history. A traceable lineage can connect the earlier and later systems while recording what was preserved, what was revised, why the change was justified, and who approved it. But continuity is not proof of correctness, legitimacy, consciousness, or metaphysical identity.

The case's central engineering proposal is a **governed recursive learning loop** in which evidence, counter-evidence, principle formation, worldview revision, and historical accountability remain distinguishable:

```text
Experience -> Differential Evidence -> Candidate Principle
     ^                                   |
     |                                   v
Outcomes <- Authorized Deployment <- Independent Validation
     |                                   |
     +---- Historical / Worldview Trace --+
```

The resulting research objective is neither an immutable worldview nor unlimited self-revision. It is a system capable of **accountable change**: revising its interpretation of the world while preserving the evidence, obligations, authority boundaries, and historical relationships necessary to understand that change.

> **Identity preservation is not the refusal to evolve. It is the ability to make evolution traceable, attributable, and appropriately governed.**

---

## References and Research Context

The following works provide conceptual context; they do not validate the specific SSI mechanisms proposed here.

1. Bratman, M. E. (1987). *Intention, Plans, and Practical Reason*. Harvard University Press.
2. Dennett, D. C. (1987). *The Intentional Stance*. MIT Press.
3. Frankfurt, H. G. (1971). Freedom of the will and the concept of a person. *The Journal of Philosophy, 68*(1), 5–20.
4. Goodhart, C. A. E. (1975). *Problems of Monetary Management: The U.K. Experience*. Reserve Bank of Australia Papers in Monetary Economics.
5. Parfit, D. (1984). *Reasons and Persons*. Oxford University Press.
6. Pearl, J. (2009). *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge University Press.
7. Russell, S. (2019). *Human Compatible: Artificial Intelligence and the Problem of Control*. Viking.
8. Varela, F. J., Thompson, E., & Rosch, E. (1991). *The Embodied Mind*. MIT Press.

### Related Structural Intelligence research

- [Structural Recursive Self-Improvement](https://github.com/sizhet/Structural-Recursive-Self-Improvement)
- [Principle Intelligence and Open Structural Learning](https://github.com/sizhet/Principle-Intelligence-and-Open-Structural-Learning)
- [Portable Intelligence Runtime Pieces and Units](https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units)
- [Pre-AGI AI Action Governance](https://github.com/sizhet/Pre-AGI-AI-Action-Governance)

## Suggested Citation

Tan, S., & GPT-Obot. (2026). *CASE-003: Worldview Evolution and Identity Preservation*. Subjective Structural Intelligence Research Program, Version 1.0.0. https://github.com/sizhet/Subjective-Structural-Intelligence

Replace this provisional citation with the archived DOI citation after release.

## Research Status

**Established in this document:** a coherent conceptual case, explicit distinctions, candidate graph responsibilities, governance requirements, counterfactual branches, and falsifiable experimental proposals.

**Not established:** measured performance gains, validated continuity metrics, universal principles of subjecthood, or any inference about phenomenal consciousness.

**Next step:** formalize a minimal, shared provenance schema and compare governed recursive revision against simpler baselines before adding implementation complexity.

---

**End of CASE-003**  
*© 2026 Sizhe Tan & GPT-Obot. Licensed under Apache-2.0.*
