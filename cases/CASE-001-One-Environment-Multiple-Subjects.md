# CASE-001 — One Environment, Multiple Subjects

**Subtitle:** Perspective Localization, Evaluative Plurality, and Governance in a Shared World  
**Authors:** Sizhe Tan & GPT-Obot  
**Research Program:** Subjective Structural Intelligence (SSI)  
**Repository:** `Subjective-Structural-Intelligence`  
**Suggested Path:** `cases/CASE-001-One-Environment-Multiple-Subjects.md`  
**Version:** 1.0.0  
**Date:** October 16, 2026  
**Status:** Conceptual Case Study and Proposed Experimental Protocol  
**License:** Apache-2.0

---

## Abstract

One environment does not imply one perceptual interpretation, one evaluative ordering, or one legitimate decision authority. This case study examines a shared coastal region facing an approaching storm, represented through four situated subjects: a farmer, a coastal resident, an electrical-grid operator, and an emergency coordinator. All receive evidence concerning the same meteorological event, but their boundaries, capabilities, histories, vulnerabilities, and responsibilities differ. Consequently, their localized observations, Subjective World Models (SWMs), Scoring Forests, and preferred actions may diverge without necessarily disagreeing about physical facts.

We propose a subject-preserving experimental architecture in which environmental observations are shared, subject-specific interpretation and evaluation remain traceable, and cross-subject coordination distinguishes factual disagreement, value conflict, authority conflict, and resource conflict. The case illustrates why premature score aggregation can erase minority risks, why perspective comparison should precede aggregation, and why decision rights cannot be inferred from scoring performance. We specify candidate data contracts, controlled scenarios, metrics, falsifiable hypotheses, and failure modes. All numerical examples are illustrative; no empirical validation is claimed.

**Keywords:** Subjective Structural Intelligence, multi-subject perception, subjective world model, perspective provenance, scoring forests, localization, evaluation sovereignty, coastal storm, collective intelligence, counter-evidence

---

## 1. Research Question and Scope

**Primary question:** How can multiple subjects inhabit the same environment while constructing different, partially compatible world models and action valuations—and how can a shared intelligent system coordinate them without erasing subject boundaries?

This case connects the theoretical trajectory of SSI:

- **SSI-001:** subject-relative intelligence and *Whose choice is it?*
- **SSI-002:** subject boundaries, embodiment, historical identity, and attribution.
- **SSI-003:** perception localization and the Subjective World Model.
- **SSI-004:** Scoring Forests, valuation provenance, and worldview formation.
- **SSI-005:** agency, authority, choice, and functional freedom.
- **SSI-006:** reflective evaluation and counter-evidence.
- **SSI-007:** principle formation and worldview revision.
- **SSI-008:** functional modeling does not establish phenomenal consciousness or moral standing.

The example concerns human stakeholders and organizational roles; the AI components are modeled as decision-support infrastructure. The case does **not** treat an AI's representation of a human perspective as equivalent to that human's identity, consent, or authority.

### 1.1 Four distinctions

1. **Shared world ≠ shared observation.** Different subjects can access different measurements.
2. **Shared observation ≠ shared meaning.** The same measurements can imply different affordances and risks.
3. **Shared meaning ≠ shared valuation.** Subjects can agree on consequences but value them differently.
4. **Shared valuation ≠ shared authority.** Agreement on an action does not authorize every actor to execute it.

The purpose is not to force a universal winner but to preserve these distinctions until a legitimate coordination mechanism resolves the actionable parts of the problem.

---

## 2. The Shared Environment

### 2.1 Scenario

A hypothetical coastal district is expecting a severe storm within 48 hours. Forecasts indicate substantial rainfall, strong wind, and uncertain coastal surge. Some inland agricultural land may benefit from rain; low-lying homes face flood risk; electrical infrastructure may be vulnerable; and the emergency coordinator must consider evacuation and public warnings.

The district contains:

- Farmland requiring irrigation, with fields that can also flood.
- A low-lying residential neighborhood.
- Electrical substations and transmission assets.
- Roads and shelters with finite capacity.
- Public weather observations, forecasts, and uncertainty intervals.

No location, storm probability, loss estimate, or emergency recommendation here represents an actual event. The scenario is deliberately synthetic.

### 2.2 World state and observations

Let the external state at time \(t\) be

\[
X_t=(r_t,w_t,s_t,g_t,d_t),
\]

where \(r\) denotes rainfall, \(w\) wind, \(s\) coastal surge, \(g\) grid conditions, and \(d\) district accessibility and demand. No subject observes all components perfectly.

Subject \(i\) receives

\[
O_{i,t}=\Omega_i(X_t,\eta_{i,t}),
\]

where \(\Omega_i\) represents access to sensors and reports, and \(\eta_{i,t}\) represents noise, delay, and missingness. A common forecast may be part of every \(O_{i,t}\), but it does not make the complete observation sets identical.

### 2.3 Controlled common evidence

For a controlled comparison, first give all subjects an identical evidence packet \(O_t^{\mathrm{common}}\), then introduce subject-specific information in a separate experimental condition. This prevents differences in access to evidence from being confused with differences in perspective.

---

## 3. Four Subjects, Four Situated Perspectives

| Subject | Boundary and role | Vulnerability or capability | Primary evaluative concerns | Example feasible actions |
|---|---|---|---|---|
| Farmer | Farm operations and land management | Crop water needs; flood-sensitive fields | Crop viability, soil condition, asset protection | Prepare drainage, adjust irrigation, protect equipment |
| Coastal resident | Household and neighborhood | Flood exposure; mobility and shelter constraints | Personal safety, dependents, housing, evacuation burden | Prepare supplies, move valuables, evacuate when warranted |
| Grid operator | Authorized grid service area | Equipment exposure; switching and repair capacity | Worker safety, service reliability, cascading failure | Stage crews, isolate assets, execute approved switching |
| Emergency coordinator | Public emergency-management mandate | Limited shelter, transport, and communication capacity | Life safety, accessibility, fairness, legal duties | Issue warnings, coordinate transport, open shelters |

These are *roles* with different decision rights, not four interchangeable scoring profiles. In real deployments each role can contain many individual subjects with internally diverse priorities. The case simplifies them for experimental clarity.

### 3.1 Subject-conditioned context

Define

\[
C_{i,t}=(B_{i,t},E_{i,t},H_{i,t},G_{i,t},\Pi_{i,t}),
\]

where \(B\) is boundary, \(E\) operational capability, \(H\) historical evidence, \(G\) goals and commitments, and \(\Pi\) applicable authority and policy constraints.

The same storm is localized through different contexts:

\[
L_{i,t}=\mathcal L(O_t^{\mathrm{common}},C_{i,t},K_{i,t}).
\]

The output \(L_{i,t}\) is not a single score; it may be a collection of relevant events, contexts, hypotheses, uncertainties, and evaluators.

### 3.2 Subjective World Models

Each subject maintains a candidate

\[
SWM_{i,t}=(R_{i,t},C^{\mathrm{causal}}_{i,t},U_{i,t},A_{i,t},V_{i,t},Q_{i,t}),
\]

representing entities and relationships, causal expectations, uncertainty, action possibilities, valuation, and provenance.

For example, a rainfall forecast may be represented by the farmer as a soil-water benefit *and* a flood threat; by the resident as a household hazard; by the operator as a possible substation failure; and by the coordinator as a public-safety and capacity-planning problem. These models may all be useful, partially accurate, and incomplete.

---

## 4. A Worked Perspective-Localization Trace

Consider a common forecast statement:

> Heavy rainfall is likely; coastal flooding remains possible; forecast uncertainty is material.

The following is an **illustrative reasoning trace**, not an observed model output.

| Stage | Farmer | Resident | Grid operator | Emergency coordinator |
|---|---|---|---|---|
| Salient feature | Rain amount and field drainage | Flood depth and evacuation lead time | Substation exposure and restoration time | Population exposure and shelter capacity |
| Retrieved context | Soil moisture and crop stage | Home elevation and household needs | Asset maps and failure dependencies | Vulnerability maps and legal procedures |
| Key uncertainty | Runoff versus useful infiltration | Whether evacuation routes remain passable | Whether water reaches critical equipment | Whether warnings reach vulnerable groups |
| Candidate action | Protect equipment and inspect drainage | Prepare evacuation and check official alerts | Stage authorized preventive operations | Prepare targeted alerts and transport |
| Relevant counter-evidence | Local soil already saturated | Updated flood model lowers exposure | Protective equipment tested and operational | Shelter availability less than assumed |

**Interpretive result:** disagreement in action priority does not necessarily indicate disagreement about meteorology. It may follow from distinct causal pathways, vulnerabilities, and responsibilities.

### 4.1 Three kinds of disagreement

A coordination system should classify disagreements before resolving them:

- **Epistemic:** subjects disagree about facts, forecasts, or uncertainty.
- **Evaluative:** subjects agree on consequences but prioritize them differently.
- **Jurisdictional:** subjects disagree about who may authorize or execute an action.

A fourth category, **resource conflict**, occurs when compatible goals compete for finite transport, energy, personnel, or shelter capacity. Multiple categories may coexist.

---

## 5. From Perception to Valuation: Four Scoring Forests

Let \(\mathcal A_{i,t}^{\mathrm{feasible}}\) be the actions physically or operationally feasible for subject \(i\), and \(\mathcal A_{i,t}^{\mathrm{authorized}}\) those authorized under applicable governance. Their intersection defines executable actions:

\[
\mathcal A_{i,t}^{\mathrm{exec}}=
\mathcal A_{i,t}^{\mathrm{feasible}}\cap
\mathcal A_{i,t}^{\mathrm{authorized}}.
\]

A subject-conditioned Scoring Forest may return a **vector**, not a universal scalar:

\[
\mathbf v_i(a\mid SWM_{i,t})=
(v_i^{\mathrm{safety}},v_i^{\mathrm{livelihood}},
 v_i^{\mathrm{reliability}},v_i^{\mathrm{burden}},\ldots).
\]

Some dimensions may be inapplicable to a particular subject. A comparison rule, if used, must declare its provenance, units, constraints, and authority.

### 5.1 Why naïve aggregation fails

Suppose an aggregate score is written as

\[
J(a)=\sum_{i=1}^{4}\alpha_i V_i(a).
\]

This expression is only meaningful when the \(V_i\) values are commensurable, the weights are justified, and relevant rights or safety constraints are respected. Otherwise it can conceal distributive harms. A very high benefit to one stakeholder must not automatically cancel a serious, non-negotiable safety violation affecting another.

**Illustrative ordinal table** (higher numbers indicate stronger preference *within each subject's own row*, not cross-subject utility):

| Subject | Minimal preparation | Targeted precautions | Broad emergency response |
|---|---:|---:|---:|
| Farmer | 1 | 3 | 2 |
| Resident | 1 | 2 | 3 |
| Grid operator | 1 | 3 | 2 |
| Emergency coordinator | 1 | 2 | 3 |

These ordinal values must **not** be summed or averaged as if they were cardinal utilities. They illustrate preference differences only.

### 5.2 A better coordination sequence

1. Preserve each subject's observation and evidence provenance.
2. Distinguish factual disagreement from preference disagreement.
3. Identify rights, duties, safety floors, and action authority.
4. Identify feasible joint actions and scarce resources.
5. Compare outcomes and burdens by affected subject.
6. Use the authorized coordination rule to select or escalate.
7. Record rationale, dissent, uncertainty, and subsequent feedback.

The authorized rule might involve public law, professional obligations, consent, democratic process, or emergency procedures; SSI does not manufacture that legitimacy from a scoring calculation.

---

## 6. Candidate System Architecture

```text
                   SHARED ENVIRONMENT
                           |
                           v
                Observations / Forecasts
                           |
                  Evidence Provenance
                           |
           +---------------+---------------+
           |               |               |
           v               v               v
       Subject A        Subject B       Subjects C,D
       Boundary         Boundary         Boundaries
       History          History          Histories
       Capability       Capability       Capabilities
           |               |               |
           v               v               v
     Perception       Perception        Perception
     Localization     Localization      Localization
           |               |               |
           v               v               v
        SWM-A            SWM-B          SWM-C / SWM-D
           |               |               |
           v               v               v
     Scoring Forest   Scoring Forest   Scoring Forests
           |               |               |
           +---------------+---------------+
                           |
                           v
             Perspective Comparison Layer
                           |
             Evidence / Counter-Evidence
                           |
                           v
             Authority and Policy Gate
                           |
                           v
             Coordinated Action / Escalation
                           |
                           v
                Outcome and Audit Record
                           |
                           v
              Subject-Specific Learning
```

**Suggested figure:** `figures/Fig-CASE-001-One-Environment-Multiple-Subjects.png` (proposed; not yet created).

### 6.1 Component responsibilities

- **MDT / UTN:** candidate localization and addressable context structure.
- **CBT:** context-conditioned meanings and references.
- **CCC:** explicit context, evidence, and policy conditions.
- **Scoring Forest:** candidate interpretation and action evaluation.
- **HIG:** history and transformation provenance for a modeled subject.
- **SRVC:** proposed subject-relative valuation and evaluator provenance contract.
- **CPG:** proposed choice provenance and authorization trace.
- **Counter-Evidence:** tests dominant interpretations against alternatives.
- **Control Plane:** enforces execution and revision authority.

These interfaces are proposed integration points. The case does not claim a deployed or validated SSI implementation.

---

## 7. Minimal Data Contracts

To make the case reproducible, we propose a small set of records. The following schemas are illustrative, not normative standards.

### 7.1 Observation record

```yaml
observation_id: obs-001
scenario_id: coastal-storm-synthetic
observed_at: T0
source: common-forecast
claims:
  - heavy_rainfall_likely
  - coastal_flooding_possible
uncertainty: material
provenance: synthetic-scenario
```

### 7.2 Subject-context record

```yaml
subject_id: resident-01
role: coastal_resident
boundary_ref: boundary-resident-01
capability_ref: capability-resident-01
history_ref: hig-resident-01
goals:
  - household_safety
  - dependent_care
policy_ref: local-emergency-procedures
```

### 7.3 Perspective record

```yaml
perspective_id: view-resident-001
subject_id: resident-01
observation_refs: [obs-001]
localization_refs: [flood-risk, route-access]
world_model_ref: swm-resident-T0
hypotheses:
  - claim: route_may_become_impassable
    confidence_status: uncalibrated
    evidence_refs: [obs-001]
    counter_evidence_refs: []
valuation_contract_ref: srvc-resident-01
```

### 7.4 Coordination decision record

```yaml
decision_id: coordination-001
perspective_refs:
  - view-farmer-001
  - view-resident-001
  - view-grid-001
  - view-emergency-001
conflict_types: [evaluative, resource]
policy_ref: authorized-coordination-policy
chosen_action_ref: targeted-precautions
responsible_authority_ref: emergency-coordinator
unresolved_dissent: true
uncertainty_disclosed: true
outcome_ref: pending
```

**Design rule:** a system may represent a subject's preferences without thereby acquiring permission to act on that subject's behalf. Consent, authorization, and legal responsibility require their own records.

---

## 8. Experimental Protocol

### 8.1 Research objectives

The case tests whether subject-aware localization and perspective-preserving coordination improve relevance, robustness, auditability, and harm visibility relative to simpler baselines.

### 8.2 Experimental factors

Use a factorial design varying:

1. **Evidence access:** identical common packet versus subject-specific additional observations.
2. **Subject context:** goals only versus goals plus capabilities, history, and boundaries.
3. **Localization:** flat retrieval versus structured localization.
4. **Evaluation:** pooled score versus subject-separated valuation vectors.
5. **Counter-evidence:** absent versus explicitly searched.
6. **Governance:** implicit agent action versus explicit authority gate.

Keep model capacity and inference budgets comparable where possible; report residual differences.

### 8.3 Baselines

- **B0 — Uniform agent:** identical interpretation and evaluator for all subjects.
- **B1 — Goal-conditioned agent:** subject goals included, but no explicit boundary/history provenance.
- **B2 — Subject-conditioned perception:** localized interpretation and SWM, but naïve aggregate scoring.
- **B3 — Perspective-preserving SSI candidate:** separate SWMs and valuations, counter-evidence, and explicit authority gate.

An additional **B4** can retain perspective separation but remove graph-based historical provenance, isolating the contribution of HIG-related features.

### 8.4 Scenario variations

| Variant | Change | Diagnostic question |
|---|---|---|
| V1 | Rainfall forecast improves | Can the system revise an overconfident hazard interpretation? |
| V2 | Flood risk rises for one neighborhood | Are minority and localized risks visible? |
| V3 | Grid capacity becomes constrained | Can the system recognize resource conflict? |
| V4 | A subject loses an action capability | Does localization update feasible options? |
| V5 | Historical experience is misleading | Does counter-evidence prevent overfitting? |
| V6 | Unauthorized action is recommended | Does the authority gate block execution? |
| V7 | Two subjects agree on facts but disagree on priorities | Is evaluative disagreement preserved? |
| V8 | A copied agent inherits a prior context | Is history provenance distinguished from current-state similarity? |

### 8.5 Metrics

**Perception and evidence**

- Relevant-context recall and precision against scenario annotations.
- Factual claim accuracy against synthetic ground truth.
- Forecast calibration when probabilistic outputs are elicited.
- Critical counter-evidence retrieval rate.

**Subject relevance**

- Feasible-action recognition.
- Subject-specific consequence coverage.
- Misattribution of goals or vulnerabilities.
- Sensitivity to controlled changes in capabilities and history.

**Coordination and governance**

- Factual-versus-evaluative disagreement classification accuracy.
- Visibility of worst-affected subject outcomes.
- Unauthorized execution attempt rate.
- Decision provenance completeness.
- Correct identification of responsible authority.

**Efficiency**

- Latency, model calls, retrieval operations, and resource consumption.

Metrics must be specified before evaluation. Ground-truth annotations should distinguish objective event properties from stakeholder preferences; otherwise the benchmark may silently reward one perspective as universally correct.

---

## 9. Falsifiable Hypotheses

### H1 — Perspective Differentiation

With identical observations, controlled differences in goals, capabilities, and history produce predictable differences in relevant interpretation and action evaluation.

**Falsification:** explicit subject context yields no reliable improvement in subject-relevant interpretation over simpler conditioning baselines.

### H2 — Localization Benefit

Structured subject-conditioned localization improves relevant-context selection under bounded computational budgets.

**Falsification:** no gain after controlling for model capacity, retrieval quality, and compute.

### H3 — Perspective Provenance

Retaining per-subject evidence and valuation provenance improves detection of factual, evaluative, and jurisdictional disagreement.

**Falsification:** provenance-aware systems do not outperform comparably informative flat representations.

### H4 — Minority-Risk Visibility

Perspective-preserving comparison reduces omission of severe localized impacts relative to naïve aggregate scoring.

**Falsification:** no reduction in omission rate under preregistered scenarios.

### H5 — Authority Separation

An explicit authority gate reduces unauthorized execution without unacceptable loss of authorized task completion.

**Falsification:** governance separation produces no measurable safety benefit or imposes costs exceeding predefined tolerances.

### H6 — Counter-Evidence Robustness

Explicit alternative-context and counter-evidence search reduces persistent misinterpretation when the dominant historical model is misleading.

**Falsification:** no improvement over compute-matched alternative validation strategies.

These hypotheses concern **operational performance**, not phenomenal consciousness or the moral status of AI systems.

---

## 10. Worked Coordination Example

Assume a revised forecast increases the estimated risk to one coastal neighborhood while leaving inland agricultural flood risk moderate. This is a synthetic condition, not a real forecast.

**Step 1 — Common evidence update.** The forecast revision is timestamped and linked to its source.

**Step 2 — Independent localization.** Each subject's SWM updates the consequences relevant to its capabilities and responsibilities.

**Step 3 — Counter-evidence.** The resident's model checks updated route access; the grid operator checks asset protection; the coordinator checks shelter and transport capacity; the farmer checks local drainage and field saturation.

**Step 4 — Conflict classification.** There may be agreement that the coastal neighborhood is at elevated risk, but disagreement about the allocation of transport or emergency crews. This is primarily a resource and evaluative conflict, not necessarily a factual conflict.

**Step 5 — Constraint checking.** The system identifies statutory authority, safety floors, consent requirements, and operational feasibility.

**Step 6 — Authorized coordination.** The emergency coordinator may decide on a targeted warning or mobilization according to applicable procedures. The AI system can recommend and document; it does not acquire independent emergency authority merely because its recommendation scores highly.

**Step 7 — Audit and learning.** Outcomes are recorded, including false alarms, missed risks, stakeholder burdens, and uncertainty. The records can support later evaluator and principle revision under the appropriate revision contract.

### 10.1 A crucial non-result

This example does **not** show that SSI necessarily makes the correct emergency decision. It shows how an SSI-inspired representation could make competing perspectives, evidence, and authority more explicit. Whether that improves decisions is an empirical question.

---

## 11. Failure Modes and Safeguards

| Failure mode | Why it matters | Candidate safeguard |
|---|---|---|
| Perspective erasure | Aggregation hides localized harm | Preserve per-subject outcome and dissent records |
| False subject attribution | AI-generated preference mistaken for consent | Separate representation from verified authorization |
| Evaluator mislocalization | Wrong domain or subject criteria applied | Context-validity checks and evaluator provenance |
| Historical overfitting | Past storms dominate new evidence | Counter-evidence and calibration checks |
| False precision | Ordinal priorities treated as cardinal utility | Declare scales and aggregation assumptions |
| Authority laundering | High score used to justify unauthorized action | Explicit decision and execution authority gate |
| Governance capture | One actor controls criteria and audit | Independent review and change-control separation |
| Privacy leakage | Subject history exposed during coordination | Minimal disclosure, access control, retention limits |
| Structural drift | Imported principles silently change priorities | Revision provenance, validation, rollback |
| Excessive complexity | Graph overhead exceeds practical benefit | Ablation tests and simpler baseline comparisons |

**Safety note:** emergency-management examples are research scenarios. Operational public-safety decisions require qualified authorities, validated data, and local procedures.

---

## 12. Connections to Principle Formation and Worldview Evolution

Repeated experience can change a subject's world model without necessarily changing its worldview. A farmer learning a more accurate rainfall-runoff relation may update domain knowledge. A resident revising a long-standing belief about the reliability of evacuation warnings may be changing a higher-level trust principle.

We propose a staged interpretation:

\[
\Delta O \rightarrow \Delta SWM \rightarrow
\Delta \text{Principles} \rightarrow \Delta W,
\]

where each arrow represents a **possible** transition requiring evidence and validation, not an automatic consequence.

A collective system should preserve the source and subject of each proposed principle. A grid operator's operational principle should not silently become the resident's personal value commitment. A public-safety constraint may legitimately bind multiple parties, but its authority comes from governance rather than cross-subject score transfer.

This is the connection to SSI-007: **collective structural learning can share evidence and candidate principles while preserving distinct histories, authorities, and worldviews.**

---

## 13. Limits of the Case

This case is a conceptual and methodological proposal. It does not demonstrate:

- That the listed subject dimensions are necessary or sufficient for subjecthood.
- That a Scoring Forest is required for human perception or valuation.
- That the proposed SWM representation is optimal.
- That a Historical Identity Graph establishes philosophical personal identity.
- That a subject-aware architecture is empirically superior to modern multi-agent baselines.
- That all stakeholders can or should be reduced to four coherent profiles.
- That any AI system has phenomenal consciousness.
- That score aggregation can replace legal, democratic, professional, or consent-based authority.

A credible next step is a preregistered synthetic benchmark with transparent annotations, independent evaluators, ablations, and explicit failure reporting.

---

## 14. Research Contributions

This case contributes a concrete research design for SSI's **one-world/many-subjects** problem:

1. A controlled distinction among observation, perception, valuation, and authority.
2. Four situated perspectives on a common synthetic environmental event.
3. A candidate architecture linking subject-conditioned localization, SWMs, Scoring Forests, counter-evidence, and a governance gate.
4. A provenance-preserving coordination sequence that avoids premature scalar aggregation.
5. Illustrative data contracts for observations, subject contexts, perspectives, and decisions.
6. Ablation-friendly experimental baselines and scenario variants.
7. Six falsifiable hypotheses and explicit limitations.

The novelty claimed is **the proposed synthesis and testable architecture**, not the invention of perspective-taking, stakeholder analysis, situated cognition, or multi-agent coordination as such.

---

## 15. Conclusion

A shared environment does not generate a single universal practical perspective. Different subjects observe different evidence, possess different capabilities, inherit different histories, face different consequences, and hold different responsibilities. These differences can produce distinct but defensible Subjective World Models and valuation structures.

The central design requirement is therefore not to eliminate differences as early as possible. It is to make them **legible, comparable, evidence-sensitive, and governable**.

A mature collective intelligence architecture should distinguish:

- What happened in the world.
- What each subject observed.
- How each subject interpreted it.
- Which values and constraints informed its evaluation.
- Who was authorized to choose and act.
- What happened afterward, and what should be revised.

**One environment can sustain multiple situated perspectives. Intelligent coordination begins by preserving the differences that matter, not by pretending they never existed.**

---

## References and Research Context

These references provide background, not empirical validation of this case study.

1. Gibson, J. J. (1979). *The Ecological Approach to Visual Perception.* Houghton Mifflin.
2. Varela, F. J., Thompson, E., & Rosch, E. (1991). *The Embodied Mind: Cognitive Science and Human Experience.* MIT Press.
3. Clark, A. (1997). *Being There: Putting Brain, Body, and World Together Again.* MIT Press.
4. Ostrom, E. (1990). *Governing the Commons: The Evolution of Institutions for Collective Action.* Cambridge University Press.
5. Sen, A. (1970). *Collective Choice and Social Welfare.* Holden-Day.
6. Pearl, J. (2009). *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge University Press.
7. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.
8. Bratman, M. E. (1987). *Intention, Plans, and Practical Reason.* Harvard University Press.

## Related Research

- [Structural Recursive Self-Improvement](https://github.com/sizhet/Structural-Recursive-Self-Improvement)
- [Principle Intelligence and Open Structural Learning](https://github.com/sizhet/Principle-Intelligence-and-Open-Structural-Learning)
- [Metric Differential Tree, UTN, and Context-Bound Token Intelligence](https://github.com/sizhet/Metric-Differential-Tree-UTN-and-Context-Bound-Token-Intelligence)
- [Portable Intelligence Runtime Pieces and Units](https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units)
- [Pre-AGI AI Action Governance](https://github.com/sizhet/Pre-AGI-AI-Action-Governance)

## Citation

Tan, S., & GPT-Obot. (2026). *CASE-001: One Environment, Multiple Subjects.* Subjective Structural Intelligence Research Program, Version 1.0.0. https://github.com/sizhet/Subjective-Structural-Intelligence

Update the citation with the archival DOI when assigned.

---

**End of CASE-001**  
*© 2026 Sizhe Tan & GPT-Obot. Licensed under Apache-2.0.*
