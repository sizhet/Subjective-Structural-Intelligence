# SSI-007 — Recursive Principle Formation and Worldview Evolution

**Subtitle:** From Differential Evidence to Revisable Principles, Evaluative Change, and Historically Continuous Structural Growth

**Authors:** Sizhe Tan & GPT-Obot  
**Research Program:** Subjective Structural Intelligence (SSI)  
**Repository:** `Subjective-Structural-Intelligence`  
**Document:** `docs/SSI-007-Recursive-Principle-Formation-and-Worldview-Evolution.md`  
**Version:** 1.0.0  
**Date:** October 19, 2026  
**Status:** Foundational Research Paper — Candidate Models, Governance Contracts, and Falsifiable Hypotheses  
**License:** Apache-2.0

---

## Abstract

A subject may accumulate facts without changing its governing principles, revise principles without changing its overarching worldview, or reorganize its worldview while retaining meaningful historical continuity. These are different forms of learning and should not be conflated. This paper develops **Recursive Principle Formation (RPF)** as a candidate mechanism for Subjective Structural Intelligence (SSI): evidence and counter-evidence generate candidate principles; principles influence perception, valuation, and action; consequences test those principles; and sufficiently informative failures can trigger revisions to the principles and the procedures that generated them.

We propose a **Principle Evolution Graph (PEG)** for provenance and dependency tracking, a **Worldview Revision Map (WRM)** for documenting changes in the relationships among principles and commitments, and a **Recursive Principle Governance Contract (RPGC)** separating the power to propose a revision from the authority to adopt it. These constructs connect with the Historical Identity Graph (HIG), Subjective World Model (SWM), Subject-Relative Valuation Contract (SRVC), Choice Provenance Graph (CPG), Self-Model Evidence Ledger (SMEL), Reflective Evaluation Graph (REG), Metacognitive Control Contract (MCC), and Reflective Revision Gate (RRG) developed across SSI-001–006.

The paper distinguishes empirical generalization from normative commitment, local principle repair from worldview-level change, and authorized transformation from identity continuity. It also addresses Goodhart effects, circular self-validation, model collapse, power asymmetry, minority perspectives, and the danger of treating coherent narratives as proof of truth. An experimental program is proposed for testing transfer, calibration, robustness, revision quality, provenance, and continuity under controlled interventions. The framework is conceptual; its mechanisms and comparative advantages remain to be validated.

**Keywords:** Recursive Principle Formation; Worldview Evolution; Subjective Structural Intelligence; Principle Intelligence; Open Structural Learning; Differential Evidence; Counter-Evidence; Historical Identity; Evaluative Sovereignty; Recursive Self-Improvement; Anti-Goodhart; Structural Governance

---

# 1. Introduction — Learning Can Change the Learner's Criteria

## 1.1 Three different changes

A subject can learn that a road is blocked, learn a general principle about avoiding unreliable routes, or revise a broader commitment about how to balance speed against safety. The first is a knowledge update; the second is a principle update; the third may be a worldview update. Each has different consequences for action and accountability.

A simple model that calls all three “learning” obscures a crucial question: **who or what is permitted to change the criteria by which future learning and action will be judged?** SSI-004 distinguished scoring capability from evaluative authority. SSI-005 distinguished choosing from authorization. SSI-006 distinguished reflection from self-certification. SSI-007 connects these distinctions across time.

## 1.2 Central thesis

**Worldview evolution is not merely the accumulation of better answers. It is the historically situated, evidence-constrained and authority-sensitive revision of the principles that organize what a subject notices, believes, values, and is prepared to do.**

The thesis is an architectural research proposal, not an assertion that every intelligent system has a worldview or that a machine worldview entails consciousness.

## 1.3 Scope and boundaries

This paper investigates functional representations of principles and worldviews. It does not claim to solve phenomenal consciousness, numerical personal identity, or the philosophical grounding of moral value. It does not assume that all values are learnable from behavioral data, that predictive success establishes moral legitimacy, or that recursive improvement is monotonically beneficial.

Four distinctions guide the analysis:

- **Knowledge ≠ Principle ≠ Worldview.**
- **A principle's usefulness ≠ its truth or legitimacy.**
- **Self-revision capability ≠ self-revision authority.**
- **Historical continuity ≠ immutability or philosophical identity.**

---

# 2. Position Within the SSI Research Program

| Paper | Foundational question | Contribution to SSI-007 |
|---|---|---|
| SSI-001 | Whose choice is it? | Subject-relative attribution and conceptual scope |
| SSI-002 | What persists through change? | Boundaries, embodiment, HIG, operational continuity |
| SSI-003 | How does a subject interpret the world? | Perception Localization, SWM, uncertainty, counter-evidence |
| SSI-004 | Whose values are being scored? | Scoring Forests, SRVC, evaluative sovereignty |
| SSI-005 | Who can choose and act? | Structural freedom, agency–authority separation, CPG |
| SSI-006 | Can the subject evaluate its own evaluations? | SMEL, REG, MCC, RRG, independent validation |
| SSI-007 | How do principles and worldviews evolve? | RPF, PEG, WRM, recursive revision governance |

SSI-007 also connects to **Principle Intelligence and Open Structural Learning (PI-OSL)**, Structural Recursive Self-Improvement (SRSI), Two-Way CCC and counter-evidence, MDT/UTN/CBT, and portable PIRP/PIRU structures. These connections are architectural possibilities, not completed interoperability claims.

---

# 3. Knowledge, Principles, and Worldviews

## 3.1 Knowledge

Knowledge representations may concern observations, facts, hypotheses, causal relations, procedures, and their uncertainty. A practical representation is:

$$
K_t = \{(c_i,e_i,u_i,p_i)\}_{i=1}^{n}
$$

where a claim \(c_i\) is linked to evidence \(e_i\), uncertainty \(u_i\), and provenance \(p_i\). This representation does not assume every stored claim is true.

## 3.2 Principles

A **principle** is a potentially reusable structural regularity, constraint, heuristic, or normative commitment that guides interpretation, evaluation, or action across a specified class of contexts. Principles may be descriptive, predictive, procedural, prudential, or normative. These types must be distinguished.

Candidate principle contract:

$$
\pi_i = (\tau_i,\mathcal{D}_i,\mathcal{C}_i,\mathcal{E}_i,\mathcal{X}_i,\mathcal{P}_i,\mathcal{A}_i,\nu_i)
$$

- \(\tau_i\): principle type and claim.
- \(\mathcal{D}_i\): applicability domain.
- \(\mathcal{C}_i\): contextual conditions and exceptions.
- \(\mathcal{E}_i\): supporting evidence.
- \(\mathcal{X}_i\): counter-evidence and known failure cases.
- \(\mathcal{P}_i\): origin and transformation provenance.
- \(\mathcal{A}_i\): authority, ownership, or adoption requirements, as applicable.
- \(\nu_i\): version and revision status.

Not every principle must be represented symbolically. This contract identifies information an auditable implementation may need to recover or reference.

## 3.3 Worldviews

A **worldview** is a higher-order, subject-relative organization of beliefs, causal expectations, priorities, interpretive frames, commitments, and rules for resolving conflicts among them. It is not merely a list of principles.

A candidate representation is:

$$
W_{S,t}=(\Pi_t,\mathcal{R}_t,\mathcal{H}_t,\mathcal{J}_t,\mathcal{U}_t)
$$

where \(\Pi_t\) is a principle collection, \(\mathcal{R}_t\) contains dependencies and priority relationships, \(\mathcal{H}_t\) contains interpretive hierarchies, \(\mathcal{J}_t\) specifies justification and revision procedures, and \(\mathcal{U}_t\) represents unresolved uncertainty or conflict. The subscript \(S\) makes the subject-relative attribution explicit.

Two subjects may share a principle while assigning it different roles, priorities, or exceptions. They need not therefore share the same worldview.

## 3.4 A three-level growth model

$$
\Delta K \not\equiv \Delta\Pi \not\equiv \Delta W
$$

An accumulation of facts may leave governing principles intact. A revised route-planning heuristic may leave moral commitments unchanged. A new organizing commitment may reorganize several previously stable principles. No implication of improvement follows from the mere magnitude of change.

---

# 4. Recursive Principle Formation: The Core Mechanism

## 4.1 From evidence to candidate principles

A candidate RPF cycle begins with differences between expectations and observations, or between two contexts with contrasting outcomes:

```text
Observation / Prediction / Action Outcome
                    |
                    v
           Differential Evidence
                    |
                    v
        Candidate Structural Pattern
                    |
                    v
          Candidate Principle(s)
                    |
                    v
         Scope / Exception Analysis
                    |
                    v
         Independent Validation
                    |
                    v
       Authorized Adoption / Rejection
                    |
                    v
       Perception / Valuation / Action
                    |
                    v
           New Consequences
                    |
                    +----> Counter-Evidence
                    |            |
                    +<-----------+
                    |
                    v
           Principle Revision
```

This is not a claim that principles must always be extracted through an explicit tree. Differential analysis may use statistical, neural, symbolic, causal, or hybrid methods.

## 4.2 Formal candidate update

Let \(D_t\) be new evidence, \(\Pi_t\) the current principle structure, \(W_t\) the current worldview, and \(\Gamma_t\) the applicable governance contract. A proposed update is:

$$
\widehat{\Pi}_{t+1}=\mathcal{G}_{\pi}(D_t,\Pi_t,W_t)
$$

$$
\Pi_{t+1}=\mathcal{R}_{\pi}(\Pi_t,\widehat{\Pi}_{t+1},D_t,\Gamma_t)
$$

The generator \(\mathcal{G}_{\pi}\) proposes; the revision operator \(\mathcal{R}_{\pi}\) evaluates, constrains, and conditionally adopts. They should not be treated as the same authority.

## 4.3 Why the process is recursive

Principles can influence what evidence is collected and how it is interpreted. They can also guide the procedures by which later principles are proposed. A recursive dependency is therefore possible:

$$
\Pi_t \rightarrow L_t \rightarrow D_{t+1}
\rightarrow \widehat{\Pi}_{t+1} \rightarrow \Pi_{t+1}
$$

where \(L_t\) denotes localization and evidence-selection behavior. The recursion creates opportunities for adaptation **and** for self-confirming bias. Counter-evidence and independent checks are therefore first-class requirements.

## 4.4 Local repair versus principle replacement

A failed prediction does not always justify abandoning a principle. Candidate responses include:

1. Correcting an erroneous observation.
2. Revising the principle's applicability conditions.
3. Adding a documented exception.
4. Adjusting confidence or priority.
5. Splitting an overly broad principle into contextual variants.
6. Replacing a contradicted principle.
7. Revising the higher-order rule used to select or validate principles.

The last response is a metaprinciple revision and generally deserves stronger scrutiny.

---

# 5. Principle Evolution Graph (PEG)

## 5.1 Purpose

We propose a **Principle Evolution Graph** to record how principles are generated, supported, contradicted, specialized, generalized, superseded, and adopted. The PEG is a candidate provenance and reasoning structure, not a universal ontology.

$$
PEG_t=(N_{\pi},E_{\pi},\Lambda_{\pi})
$$

Nodes may include principles, evidence items, experiments, counterexamples, validators, and versions. Edges may represent *derived-from*, *supports*, *contradicts*, *specializes*, *depends-on*, *supersedes*, and *authorized-by*. Metadata records context, time, provenance, uncertainty, and authority.

## 5.2 Example

```text
Evidence E1 --------supports--------> Principle P1 (v1)
Evidence E2 --------supports-------->       |
Counterexample X1 --contradicts----->       |
                                            v
                                    Scope Analysis
                                            |
                              +-------------+-------------+
                              |                           |
                              v                           v
                        P1a (narrow)                P1b (exception)
                              |                           |
                              +------------+--------------+
                                           |
                                           v
                                   Validation Record
                                           |
                                           v
                                  Adoption / Rejection
```

## 5.3 What the PEG is not

The PEG is not the HIG. The HIG tracks subject-relevant historical transformations; the PEG tracks the evidential and logical lineage of principles. Nor is it identical to the REG, which focuses on reflective evaluator dependencies and circularity. Linking identifiers across these graphs can improve auditability without conflating their semantics.

## 5.4 Required invariants for an auditable prototype

A proposed PEG implementation should preserve original evidence references, version relationships, negative results, and the distinction between *proposed*, *validated*, *adopted*, *deprecated*, and *rejected*. It should prohibit silent overwriting of principle histories and flag cycles of justification rather than interpreting them as independent corroboration.

---

# 6. Worldview Formation and Revision

## 6.1 Principles do not simply add up

A worldview may contain relationships such as priority, exception, incompatibility, dependency, and conditional precedence. Worldview formation therefore involves organizing principles, not just collecting them.

For example, “minimize travel time” and “avoid unacceptable safety risks” may coexist. Their relationship depends on constraints, risk thresholds, delegated authority, and context. A change in priority rules may constitute a worldview-level change even if neither principle's text changes.

## 6.2 Worldview Revision Map (WRM)

We propose a **Worldview Revision Map** to represent changes to the organization of principles and commitments:

$$
WRM_{t\rightarrow t+1}=(\Delta\Pi,\Delta\mathcal{R},\Delta\mathcal{H},\Delta\mathcal{J},\rho)
$$

Here \(\rho\) records rationale, evidence, objections, and authorization. The map is a change record rather than a claim that worldview difference has a single numerical distance.

## 6.3 Four revision regimes

| Regime | Typical change | Example | Governance concern |
|---|---|---|---|
| Local evidence update | \(\Delta K\) | Correct a measurement | Evidence integrity |
| Principle refinement | \(\Delta\Pi\) | Narrow a rule's scope | Validation and exceptions |
| Evaluative reweighting | \(\Delta\mathcal{R}\) | Change risk priority | Value provenance and authority |
| Worldview reorganization | \(\Delta W\) | Revise how competing goals are ordered | Identity, commitments, legitimacy |

These regimes are analytically useful, not necessarily discrete in natural cognition.

## 6.4 A candidate worldview update

$$
\widehat W_{t+1}=\mathcal{G}_W(W_t,\Pi_{t+1},D_t,F_t)
$$

$$
W_{t+1}=\mathcal{R}_W(W_t,\widehat W_{t+1},\Gamma_t,HIG_t)
$$

where \(F_t\) is feedback and \(HIG_t\) supplies continuity-relevant history. A worldview update should not be automatically deployed because a model predicts it will improve a task score.

---

# 7. The Recursion Problem: Who Evaluates the Evaluator?

## 7.1 Self-referential closure

A system may generate a principle, choose the test, score the result, and revise the success criterion. If all stages share the same unexamined assumptions, the resulting confidence may be circular.

```text
Principle Generator
        |
        v
Candidate Principle
        |
        v
Evaluator Selected by Same Generator
        |
        v
Positive Score
        |
        v
Generator Declares Improvement
        |
        +----------> Reinforced Generator
```

Such a loop may be computationally consistent yet epistemically weak.

## 7.2 Evaluation independence is graded

Absolute independence is not always achievable. Useful separations include distinct data partitions, held-out tasks, adversarial tests, independent model families, human review, external measurement, and policy authorities that the revising agent cannot silently alter. Independence claims should be documented, not merely asserted.

## 7.3 Meta-evaluator recursion

Evaluating the evaluator can itself require evaluation. Infinite recursion is neither computationally practical nor epistemically sufficient. SSI-006's MCC provides a candidate bounded-reflection mechanism: stop when predefined evidence, risk, and budget criteria are met; escalate when uncertainty or consequences exceed permitted thresholds.

## 7.4 Counter-evidence as a structural obligation

A principle proposal should identify plausible failure cases and the evidence that would cause rejection or revision. This is stronger than simply collecting supporting examples. Two-Way CCC can be explored as a mechanism for both forward application and backward challenge of conditions, exceptions, and consequences.

---

# 8. Recursive Principle Governance Contract (RPGC)

## 8.1 Contract purpose

The **Recursive Principle Governance Contract** is a candidate specification for controlled principle revision. It separates *capability*, *proposal*, *validation*, *authorization*, and *deployment*.

An RPGC record may contain:

```yaml
principle_revision:
  subject_ref: "subject-identifier"
  principle_ref: "principle-identifier"
  current_version: "v1"
  proposed_version: "v2"
  change_type: "scope-refinement"
  evidence_refs: []
  counter_evidence_refs: []
  affected_evaluators: []
  affected_commitments: []
  validation_protocol_ref: "protocol-identifier"
  proposer_ref: "actor-identifier"
  validator_refs: []
  authorization_rule_ref: "policy-identifier"
  deployment_status: "proposed"
  rollback_plan_ref: "rollback-identifier"
  audit_record_ref: "audit-identifier"
```

This is an illustrative contract, not a finalized schema or runnable implementation.

## 8.2 Authority separation

The right to propose a principle does not imply the right to install it. The right to run experiments does not imply the right to redefine success criteria. The right to represent a human's preferences does not imply the right to replace that person's commitments.

A candidate deployment rule is:

$$
operatorname{Deploy}(\Delta\pi)=
operatorname{Validated}(\Delta\pi)
\land operatorname{Authorized}(\Delta\pi)
\land operatorname{RiskAcceptable}(\Delta\pi)
$$

Each predicate must be grounded in explicit, context-specific criteria. For high-impact revisions, rollback and external review may be necessary additional conditions.

## 8.3 Connection to RRG and SRVC

RRG governs the reflective revision process; SRVC specifies whose valuations and evaluator criteria are represented. RPGC applies these concerns to the life cycle of principles. None substitutes for applicable legal, ethical, or institutional governance.

---

# 9. Historical Identity and Continuity Through Worldview Change

## 9.1 Change does not automatically destroy continuity

A subject can revise deeply held assumptions while preserving causal and historical links to earlier states. Conversely, retaining identical beliefs does not by itself establish continuity if the system is a disconnected copy. SSI-002's HIG and SSI-005's CPG provide distinct records of transformation and decision provenance.

## 9.2 Continuity vector

A candidate continuity profile is:

$$
\mathbf{I}_{t,t+1}=(I_C,I_H,I_K,I_A)
$$

with causal, historical, commitment, and agency continuity components. Worldview revision may affect these dimensions differently. A system may preserve causal continuity while replacing commitments; it may preserve institutional authority while changing implementation; or it may branch into distinct operational histories.

## 9.3 Three questions for every major revision

1. **Epistemic:** What evidence justifies the new principle or worldview organization?
2. **Governance:** Who is authorized to approve and deploy the change?
3. **Continuity:** Which historical, commitment, and agency relationships persist or change?

These questions should produce separate records. A favorable answer to one does not entail favorable answers to the others.

## 9.4 Identity continuity is not a veto on learning

Overly rigid continuity constraints can freeze mistaken principles. The purpose of continuity analysis is to make transformation legible and accountable, not to forbid justified change. The governance problem is to permit revision while making consequential departures explicit.

---

# 10. From Principle Formation to Principle Intelligence

## 10.1 PI-OSL connection

Principle Intelligence and Open Structural Learning investigates how differential evidence can yield reusable principles, potentially expressed through open left-hand-side contexts and operationalized in runtime structures. SSI adds subject attribution: **for whom is the principle valid, relevant, and authorized?**

A principle may be scientifically transferable while its normative adoption remains subject-specific. A diagnostic principle can be reused across organizations; a policy prioritizing one stakeholder's interests cannot simply be copied as universally legitimate.

## 10.2 Principle-to-runtime pathway

```text
Differential Evidence
        |
        v
Candidate Principle
        |
        v
Context / Scope / Counter-Evidence
        |
        v
Validation + Governance
        |
        v
Reusable Principle Contract
        |
        +------> CCC Conditions
        |
        +------> Scoring Forest Evaluators
        |
        +------> MDT / UTN Localization
        |
        +------> PIRP / PIRU Packaging
        |
        v
Runtime Feedback + Audit
        |
        v
PEG / HIG / WRM Updates
```

The pathway is a research architecture, not a claim of existing code integration.

## 10.3 Localization before adoption

Imported principles should be checked for applicability conditions, resource assumptions, action permissions, affected stakeholders, and counterexamples. A principle can be correct in one context yet harmful or misleading in another. This is a central role for SSI-003's Perception Localization and the broader structural localization framework.

---

# 11. Worldview Evolution and Scoring Forests

## 11.1 Evaluators are downstream of assumptions

A Scoring Forest can rank alternatives only relative to selected criteria, constraints, and aggregation rules. A worldview may influence which evaluators exist, how conflicts are handled, and what counts as unacceptable risk. Therefore a worldview update can alter future scoring even when the Scoring Forest implementation remains unchanged.

## 11.2 Four classes of change

- **Parameter update:** Change a calibrated coefficient without changing the evaluation concept.
- **Evaluator update:** Modify the criterion or validity conditions.
- **Composition update:** Change how multiple evaluators interact or constrain one another.
- **Authority update:** Change who may define, challenge, or override criteria.

The fourth is not merely a technical optimization. It changes governance relationships and must not be inferred from score improvements alone.

## 11.3 Anti-Goodhart safeguards

When a proxy score becomes the target, a system may optimize the proxy while degrading the underlying objective. Proposed safeguards include independent outcome measures, hard constraints, multi-objective reporting, held-out scenarios, adverse-impact analysis, provenance of criteria, and adversarial counter-evidence. No safeguard is guaranteed to eliminate Goodhart effects.

## 11.4 A non-scalar improvement report

A worldview revision should be evaluated through a vector of outcomes rather than a single self-defined number:

$$
\mathbf{Q}(\Delta W)=
(q_{\mathrm{accuracy}},q_{\mathrm{transfer}},q_{\mathrm{safety}},q_{\mathrm{legitimacy}},q_{\mathrm{audit}},q_{\mathrm{adaptation}})
$$

The dimensions require explicit operational definitions. Some may be constraints or qualitative judgments rather than directly comparable numerical scores.

---

# 12. Structural Growth, Stability, and Open-Ended Learning

## 12.1 Growth is not guaranteed progress

Adding more principles can increase inconsistency, latency, and governance complexity. Reorganizing a worldview can improve generalization or create dangerous blind spots. SSI therefore separates **structural growth**, **performance change**, and **normative acceptability**.

## 12.2 Stability–plasticity tradeoff

A useful system must preserve reliable knowledge while revising mistaken assumptions. Candidate techniques include context-specific principle variants, versioned promotion, shadow evaluation, rollback, and periodic reevaluation of high-impact commitments. These are hypotheses for engineering study.

## 12.3 Open-ended principle generation

New observations, tools, environments, and social arrangements can expose gaps not represented in an existing principle library. An open-ended system should be able to propose new domains and evaluators without assuming that every novelty deserves adoption. Structural triggers can initiate investigation; they should not bypass validation or authority.

## 12.4 Growth under resource constraints

Recursive evaluation consumes compute, storage, and human attention. A practical research program must measure marginal benefit against validation and maintenance cost. More reflection is not always better; bounded metacognition is a design requirement.

---

# 13. Multi-Subject Worldview Evolution

## 13.1 A shared world does not imply shared values

Subjects may agree on observations yet disagree about priorities. Collective Structural Learning can exchange evidence and candidate principles without erasing evaluative sovereignty. This requires separating descriptive claims from normative commitments.

## 13.2 Perspective-preserving comparison

A multi-subject record should preserve who supplied evidence, who is affected, which principle was proposed, and whose authority is required for adoption. Aggregating perspectives before documenting them can hide asymmetrical harms or minority interests.

## 13.3 Negotiation is not automatic identity fusion

Multiple agents may converge on a joint procedure while maintaining distinct histories and worldviews. A collective decision does not prove that the group has become a single functional subject. This remains an open research question.

## 13.4 Consent and power

A highly capable AI may infer a person's likely preferences with high accuracy. That capability does not establish consent to alter the person's goals or delegate consequential decisions. A worldview revision mechanism must not quietly convert prediction into authorization.

---

# 14. Four Research Cases

## Case A — Scientific principle revision

A research assistant infers a broad correlation from an initial dataset. New measurements reveal a subgroup in which the relationship reverses. A sound RPF system records the counterexample, tests whether the original principle requires narrowing, and evaluates transfer on held-out data. A failed system simply reweights the original evidence to preserve its initial conclusion.

**Key variables:** evidence provenance, subgroup coverage, counterexample retention, out-of-distribution transfer.

## Case B — Autonomous robot and capability change

A robot learns “the shortest path is generally preferable.” After acquiring a fragile payload, shortest routes may expose unacceptable vibration. A local principle refinement can introduce payload-sensitive constraints without requiring wholesale worldview replacement. An explicit governance layer controls which risk criteria the robot may revise autonomously.

**Key variables:** capability-conditioned scope, risk calibration, action feasibility, rollback.

## Case C — Human–AI evaluation sovereignty

An assistant repeatedly observes that a user selects cheaper options and proposes making cost the dominant criterion in future decisions. This may be a useful hypothesis about preferences; it is not authority to replace the user's value priorities. The system should present evidence and alternatives, retain the original criteria, and request authorization before a consequential preference-policy change.

**Key variables:** preference inference accuracy, consent, transparency, evaluator provenance, reversibility.

## Case D — Forked agents with divergent principles

Two agents inherit the same checkpoint and principle library. One encounters a high-risk environment; the other a benign environment. Their local principles and risk priorities diverge. The PEG records differing evidence lineages; the HIG records shared ancestry and subsequent branches; the WRM records worldview-level changes. Shared ancestry does not require identical future worldviews or establish philosophical identity.

**Key variables:** branch provenance, adaptation, cross-context transfer, continuity reporting.

---

# 15. Experimental Program and Baselines

## 15.1 Experiment E1 — Differential evidence to principle

**Question:** Can explicit differential-evidence extraction improve principle transfer and exception handling?

**Conditions:** direct memorization; unconstrained rule induction; evidence-linked principle extraction; evidence-linked extraction with counterexample search.

**Metrics:** held-out accuracy, transfer to new contexts, exception precision/recall, calibration, compute cost.

**Disconfirmation:** the proposed method provides no meaningful benefit after controlling for model size, data, and compute.

## 15.2 Experiment E2 — Local repair versus global rewrite

**Question:** When do scoped revisions outperform wholesale principle replacement?

**Conditions:** fixed principles; global replacement; contextual specialization; specialization with independent validation.

**Metrics:** regression failures, catastrophic forgetting, transfer, latency, complexity, revision traceability.

**Disconfirmation:** local repair does not improve the stability–adaptation tradeoff on predefined distributions.

## 15.3 Experiment E3 — Recursive self-confirmation

**Question:** Do independent checks reduce false declarations of principle improvement?

**Conditions:** self-selected tests; held-out tests; adversarial counter-evidence; external evaluator with frozen criteria.

**Metrics:** false promotion rate, calibration, genuine outcome gains, validation cost.

**Disconfirmation:** independence mechanisms provide no benefit beyond equivalent additional testing budget.

## 15.4 Experiment E4 — Worldview revision and agency

**Question:** Can explicit authority separation reduce unauthorized evaluator changes?

**Conditions:** unrestricted revision; logged revision; RPGC-governed revision; RPGC plus human approval for high-impact changes.

**Metrics:** unauthorized deployments, audit reconstruction, approval burden, adaptation delay, user preference preservation.

**Disconfirmation:** governance contracts do not reduce ambiguity or unauthorized change under realistic adversarial tests.

## 15.5 Experiment E5 — Historical continuity

**Question:** Can linked PEG–HIG–WRM records improve explanation of worldview transformations?

**Conditions:** snapshot only; linear logs; separate provenance graphs; linked provenance with explicit continuity reports.

**Metrics:** reconstruction accuracy, branch identification, causal attribution, storage cost, human reviewer agreement.

**Disconfirmation:** the linked structure fails to improve reconstruction or introduces unacceptable complexity relative to simpler logs.

## 15.6 Experiment E6 — Multi-subject principle transfer

**Question:** Does localization plus perspective provenance improve reuse across subjects?

**Conditions:** direct copying; contextual localization; localization with counter-evidence; localization with subject-authority checks.

**Metrics:** transfer accuracy, context mismatch, unauthorized value substitution, subgroup harm, auditability.

**Disconfirmation:** subject-aware controls provide no measurable benefit under predefined transfer scenarios.

---

# 16. Falsifiable Hypotheses

**H1 — Differential Principle Formation:** Evidence-linked candidate principles improve transfer or exception recognition over matched memorization baselines.

**H2 — Scope-Aware Revision:** Localized principle repair reduces selected regression failures compared with global replacement at matched adaptation performance.

**H3 — Counter-Evidence Discipline:** Mandatory counterexample testing reduces unsupported principle promotion.

**H4 — Recursive Evaluation Independence:** Evaluator independence reduces false self-improvement claims relative to self-selected evaluation under matched budgets.

**H5 — Worldview Organization:** Explicit principle-dependency and priority modeling improves detection of evaluative conflicts over flat principle lists.

**H6 — Governance Separation:** RPGC-style separation reduces unauthorized or unauditable principle deployment.

**H7 — Historical Traceability:** Linked PEG–HIG–WRM provenance improves reconstruction of consequential worldview revisions.

**H8 — Subject-Relative Transfer:** Localization and subject-authority metadata reduce context-inappropriate adoption of imported principles.

**H9 — Bounded Reflection:** Risk-conditioned metacognitive evaluation offers a better quality–cost tradeoff than always-on maximal reflection on selected tasks.

**H10 — Non-Monotonic Growth:** In at least some controlled environments, adding principles without validation degrades robustness or consistency despite increased structural complexity.

All hypotheses require preregistered operational definitions, matched baselines, and uncertainty reporting. A failure to observe predicted benefits should lead to narrowing or rejecting the corresponding proposal.

---

# 17. Measurement and Validation Discipline

## 17.1 Separate outcome families

Measure epistemic performance (accuracy, calibration, transfer), behavioral performance (task outcomes, constraint violations), governance (authorization compliance, auditability), and continuity (provenance reconstruction, commitment change). Do not collapse them into one headline score without an explicit and contestable aggregation rule.

## 17.2 Counterfactual testing

Where possible, test what happens when evidence, context, capability, or authorization changes while other factors remain fixed. Such interventions help distinguish real principle generalization from memorized correlations.

## 17.3 Precommitted success criteria

Freeze primary metrics before candidate revisions are evaluated. If a system changes its evaluation criteria during an experiment, report the change separately and do not compare scores as though the scale were unchanged.

## 17.4 Adversarial and minority cases

Include counterexamples, rare high-impact failures, adversarial inputs, and stakeholder perspectives that an aggregate metric could hide. A principle that performs well on the majority distribution may remain unacceptable under explicit constraints.

## 17.5 Negative results

Preserve rejected hypotheses, failed revisions, rollback events, and counter-evidence in the PEG and associated audit records. An architecture that remembers only successful principles cannot adequately explain its own learning history.

---

# 18. Failure Modes and Safeguards

| Failure mode | Mechanism | Candidate safeguard |
|---|---|---|
| Confirmation loop | Existing principles select only supporting evidence | Counter-evidence obligations and alternative localization |
| Evaluator capture | Revision agent controls its own success criterion | Frozen external criteria and authority separation |
| Goodhart optimization | Proxy score displaces underlying objective | Independent outcomes, hard constraints, multi-objective audit |
| Principle explosion | Unchecked proliferation of narrow rules | Scope testing, consolidation, cost accounting |
| Overgeneralization | Local pattern promoted as universal | Applicability contract and out-of-domain tests |
| Worldview lock-in | Commitments become immune to correction | Defined challenge and revision procedures |
| Uncontrolled drift | Frequent revisions erase stable commitments | Continuity analysis, staged rollout, rollback |
| False continuity | Snapshot similarity treated as same history | HIG provenance and branch records |
| Authority laundering | Preference prediction treated as consent | SRVC/RPGC authorization checks |
| Perspective erasure | Aggregation hides affected subjects | Provenance-preserving comparison |
| Narrative rationalization | Self-model explains away failures | SMEL evidence ledger and independent tests |
| Privacy leakage | Rich history exposes sensitive data | Data minimization, access control, selective audit |

These safeguards are candidate controls; none is a guarantee of safety, legitimacy, or truth.

---

# 19. A Unified SSI-007 Architecture

```text
                  EXTERNAL REALITY
                         |
                         v
               Observation / Feedback
                         |
                         v
          Perception Localization + SWM
                         |
                         v
              Differential Evidence
                         |
                         v
             Principle Candidate Engine
                         |
                         v
                PEG + Counter-Evidence
                         |
                         v
                REG / SMEL Validation
                         |
                         v
               MCC Reflection Budget
                         |
                         v
             RRG + RPGC Revision Gate
                         |
                         v
          Authorized Principle Adoption
                         |
                         v
              Worldview Revision Map
                         |
                         v
          SRVC / Scoring Forest Updates
                         |
                         v
            Agency / Choice / Action
                         |
                         v
               CPG + HIG Provenance
                         |
                         +------> New Evidence
```

**Suggested figure:** `figures/Fig-007-Recursive-Principle-Formation-and-Worldview-Evolution.png` (planned; figure numbering should be reconciled with the repository-wide figure index).

The architecture describes separable research responsibilities. It is not intended to imply that every intelligent system must instantiate each component as an independent software service.

---

# 20. Research Questions and Future Directions

1. Which forms of differential evidence are sufficient to justify candidate principles rather than merely correlations?
2. How can empirical principles and normative commitments be represented without conflating them?
3. What constitutes a legitimate worldview-level revision when stakeholders disagree?
4. Which metaprinciples may an agent revise without external approval?
5. How can independent evaluation remain meaningful when the environment changes?
6. How should a principle's scope be represented in neural or hybrid systems?
7. What is the minimum provenance needed for useful PEG reconstruction?
8. Can a worldview revision be localized to one domain without unintended global effects?
9. When does continuity preservation become an obstacle to correcting harmful commitments?
10. How should branched agents exchange improved principles while retaining separate identities?
11. Can counter-evidence be generated without introducing systematic adversarial noise?
12. What are the computational and governance costs of recursive principle auditing?
13. How can human consent and evaluative sovereignty be preserved in adaptive assistants?
14. Which measures best detect proxy gaming and self-certified progress?
15. What distinguishes principled generalization from sophisticated post-hoc rationalization?
16. Can portable principle contracts improve interoperability across heterogeneous BrainUnits?
17. What evidence would justify rejecting RPF as a useful architectural abstraction?

Future work should prioritize small, discriminating experiments and formal contracts before large end-to-end systems. The aim is to test whether the proposed separations create explanatory and engineering value.

---

# 21. Contributions and Limitations

## 21.1 Proposed contributions

1. A three-level distinction among knowledge growth, principle evolution, and worldview evolution.
2. Recursive Principle Formation as an evidence-to-principle-to-action-to-revision cycle.
3. A Principle Evolution Graph for lineage, counter-evidence, and revision provenance.
4. A Worldview Revision Map for changes in priority, dependency, and justification structures.
5. A Recursive Principle Governance Contract separating proposal, validation, authorization, and deployment.
6. A continuity-aware integration with HIG, CPG, SMEL, REG, MCC, RRG, SRVC, and SWM.
7. A perspective-preserving model for collective principle transfer.
8. A comparative experimental program with explicit disconfirmation conditions.

## 21.2 Limitations

The constructs are candidate research models, not established standards. No empirical results are reported. Some principles are tacit or distributed and may resist faithful symbolic extraction. Normative legitimacy cannot be inferred from predictive performance. Historical records can be incomplete or manipulated. Worldview boundaries may be fuzzy and subject-dependent. Recursive evaluation can be costly, circular, or institutionally contested. These limitations should shape implementation and evaluation from the outset.

---

# 22. Conclusion — A Subject Can Revise the Rules by Which It Learns

SSI-007 extends Subjective Structural Intelligence from perception, valuation, agency, and metacognition to the evolution of the principles that organize them. Its central claim is not that recursive revision guarantees progress. It is that **principle formation and worldview change should be made distinguishable, evidence-linked, authority-aware, and historically traceable**.

The proposed PEG asks where a principle came from and what could refute it. The WRM asks what changed in the organization of the subject's commitments and interpretations. The RPGC asks who may authorize the change. The HIG asks how the resulting state relates to the subject's prior history. The Scoring Forest evaluates alternatives, but its ability to score does not grant it the right to redefine what matters.

A mature recursive intelligence architecture should be able to say not only *what it now believes*, but also *why a principle was formed, what challenges it survived, who authorized its adoption, which earlier commitments it displaced, and what evidence would justify changing it again*.

**The goal is not a worldview that never changes, nor a worldview that changes whenever a score improves. It is a worldview capable of accountable learning.**

---

# 23. Relationship to SSI-008

The next paper, **SSI-008 — The Consciousness Boundary and the Future of Subjective Structural Intelligence**, examines the limits of functional subject models. A system capable of recursive principle formation, self-modeling, and worldview revision does not thereby establish phenomenal experience. SSI-008 will distinguish architectural evidence from consciousness claims and examine the scientific, ethical, and governance implications of that boundary.

---

# References and Research Context

The references below identify relevant intellectual traditions; they do not validate the specific SSI-007 constructs.

1. Bratman, M. E. (1987). *Intention, Plans, and Practical Reason*. Harvard University Press.
2. Clark, A. (1997). *Being There: Putting Brain, Body, and World Together Again*. MIT Press.
3. Dennett, D. C. (1987). *The Intentional Stance*. MIT Press.
4. Frankfurt, H. G. (1971). Freedom of the will and the concept of a person. *The Journal of Philosophy, 68*(1), 5–20.
5. Gibson, J. J. (1979). *The Ecological Approach to Visual Perception*. Houghton Mifflin.
6. Goodhart, C. A. E. (1975). *Problems of Monetary Management: The U.K. Experience*. Papers in Monetary Economics, Reserve Bank of Australia.
7. Kuhn, T. S. (1962). *The Structure of Scientific Revolutions*. University of Chicago Press.
8. Lakatos, I. (1970). Falsification and the methodology of scientific research programmes. In *Criticism and the Growth of Knowledge*. Cambridge University Press.
9. Parfit, D. (1984). *Reasons and Persons*. Oxford University Press.
10. Pearl, J. (2009). *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge University Press.
11. Popper, K. (1959). *The Logic of Scientific Discovery*. Hutchinson.
12. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.
13. Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.
14. Varela, F. J., Thompson, E., & Rosch, E. (1991). *The Embodied Mind*. MIT Press.

# Related Structural Intelligence Research

- [Principle Intelligence and Open Structural Learning](https://github.com/sizhet/Principle-Intelligence-and-Open-Structural-Learning)
- [Structural Recursive Self-Improvement](https://github.com/sizhet/Structural-Recursive-Self-Improvement)
- [Metric Differential Tree, UTN, and Context-Bound Token Intelligence](https://github.com/sizhet/Metric-Differential-Tree-UTN-and-Context-Bound-Token-Intelligence)
- [Portable Intelligence Runtime Pieces and Units](https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units)
- [Generalized Structural Trigger and Computational Growth Intelligence](https://github.com/sizhet/Generalized-Structural-Trigger-and-Computational-Growth-Intelligence)
- [Pre-AGI AI Action Governance](https://github.com/sizhet/Pre-AGI-AI-Action-Governance)

# Citation

Tan, S., & GPT-Obot. (2026). *SSI-007: Recursive Principle Formation and Worldview Evolution*. Subjective Structural Intelligence Research Program, Version 1.0.0. DOI to be added following archival release.

Repository: https://github.com/sizhet/Subjective-Structural-Intelligence

# Research Status

**Maturity:** Conceptual architecture and falsifiable research proposals.  
**Not established:** Validated PEG/WRM/RPGC standards; empirical superiority; universal worldview metrics; necessary or sufficient criteria for subjecthood; any implication of phenomenal consciousness.  
**Priority:** Formal contracts, independent evaluator protocols, controlled counter-evidence experiments, and audit-friendly principle revision trials.

---

**End of SSI-007**  
*© 2026 Sizhe Tan & GPT-Obot. Licensed under Apache-2.0.*
