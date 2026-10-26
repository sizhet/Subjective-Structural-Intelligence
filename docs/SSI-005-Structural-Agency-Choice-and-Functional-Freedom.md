# SSI-005 — Structural Agency, Choice, and Functional Freedom

**Subtitle:** From Subject-Relative Evaluation to Authorized Action, Reflective Control, and Revisable Possibility Spaces

**Authors:** Sizhe Tan & GPT-Obot  
**Research Program:** Subjective Structural Intelligence (SSI)  
**Repository:** `Subjective-Structural-Intelligence`  
**Document:** `docs/SSI-005-Structural-Agency-Choice-and-Functional-Freedom.md`  
**Version:** 1.0.0  
**Date:** October 19, 2026  
**Status:** Foundational Research Paper — Candidate Models, Governance Contracts, and Falsifiable Hypotheses  
**License:** Apache-2.0

---

## Abstract

Scoring alternatives does not, by itself, establish agency. A system may rank actions without possessing authority to execute them; it may execute instructions without selecting its goals; it may optimize an objective without the capacity to inspect or revise that objective. Subjective Structural Intelligence (SSI) therefore distinguishes **evaluation**, **choice**, **authorization**, **execution**, and **structural revision** as separate functional relationships. This paper investigates **Structural Agency**: the organization through which an identifiable, historically situated subject can generate alternatives, assess them, select among them, act within legitimate constraints, learn from consequences, and—in some circumstances—reflectively revise its own evaluative structures.

We introduce a multidimensional candidate account of **Functional Freedom**, defined not by unconstrained action or the mere number of options, but by the quality of feasible alternatives, the provenance of decision authority, reflective revisability, reliable feedback, and the preservation of relevant commitments and rights. We propose a **Choice Provenance Graph (CPG)**, an **Agency–Authority Matrix (AAM)**, and a **Structural Freedom Profile (SFP)** to make the distinction between capability and legitimacy operational. These structures interface with the Historical Identity Graph (HIG), Subjective World Model (SWM), Subject-Relative Valuation Contracts (SRVC), Scoring Forests, and the Structural Policy Control Plane.

The paper analyzes human–AI delegation, apparent choice under constrained options, self-modification, multi-subject conflict, coercion, and Goodhart effects. It presents a staged architecture and experimental program, while explicitly avoiding claims about metaphysical free will, moral personhood, or phenomenal consciousness. The central proposition is that **functional freedom depends not merely on choosing within a given space, but also on the governed capacity to understand, contest, and sometimes reshape the structures that define that space**.

**Keywords:** Subjective Structural Intelligence, Structural Agency, Functional Freedom, Choice Provenance, Evaluative Sovereignty, Action Authority, Scoring Forest, Policy Control Plane, Reflective Revision, Historical Identity, Counter-Evidence, Anti-Goodhart

---

![Structural Freedom and Choice Generation](../figures/Fig-005-Structural-Freedom-and-Choice-Generation.png)

---

# 1. Introduction — A Score Is Not a Choice

## 1.1 The missing transition

SSI-001 posed the foundational question: **“Whose choice is it?”** SSI-002 examined the subject's boundaries, embodiment, and historical identity. SSI-003 investigated subject-conditioned perception and the Subjective World Model (SWM). SSI-004 examined valuation, Scoring Forests, and worldview formation. Yet even a sophisticated, subject-aware evaluator leaves a critical transition unexplained: **How does evaluation become an attributable choice and an authorized action?**

Consider an assistant that correctly identifies the most profitable financial transaction. It might be able to calculate a score, explain its ranking, and generate the transaction request. None of those capacities alone establishes that it is authorized to transact, that the human has consented, or that profit is the only relevant value. The choice cannot be understood by examining the score alone.

A second example is a robot that has three possible routes. If two routes are physically blocked and the third violates a safety constraint, presenting three routes in a user interface does not confer meaningful freedom. A third example is a self-improving agent that can modify its scoring weights. The mere ability to rewrite an evaluator does not establish the legitimacy of doing so.

These cases motivate the paper's primary distinctions:

- **Scoring ≠ Choosing.**
- **Choosing ≠ Executing.**
- **Capability ≠ Authority.**
- **Delegation ≠ Transfer of identity or unrestricted sovereignty.**
- **More nominal options ≠ Greater functional freedom.**
- **Reflective self-modification ≠ Metaphysical free will.**

## 1.2 Central thesis

We propose that structural agency is best investigated as a **subject-attributed, context-sensitive, authority-bounded, feedback-responsive organization of choices and actions**. Functional freedom is a multidimensional property of this organization, not a universal scalar or a claim about consciousness.

The research objective is to make agency's architecture inspectable and testable without collapsing it into either deterministic computation or metaphysical speculation.

# 2. Five Distinct Stages of Agency

A useful starting point is to separate five stages often compressed into the word “decision.”

| Stage | Question | Typical output | Critical failure |
|---|---|---|---|
| Perception | What situation does this subject confront? | Contextual interpretations | Mislocalization or missing evidence |
| Valuation | How do alternatives matter to the represented subject? | Scores, rankings, constraints, reasons | Proxy substitution or hidden stakeholder |
| Choice | Which alternative is selected, and by whom? | Choice record and rationale | Authority or attribution ambiguity |
| Execution | What action is actually performed? | Action and observable trace | Unauthorized or infeasible execution |
| Revision | What should change after feedback? | Model, policy, or evaluator proposal | Uncontrolled drift or illegitimate self-modification |

These stages may be recurrent, parallel, or implemented through integrated models. Their **conceptual separation** remains valuable even when their software implementation is not modular.

## 2.1 Candidate agency transition

Let the subject's state be:

$$
S_t=(B_t,E_t,H_t,P_t,V_t,A_t,M_t,W_t),
$$

where boundary, embodiment, history, perception, valuation, agency, self-model, and worldview are defined in the earlier SSI papers. Let \(\Pi_t\) be the governing policy and authorization state. A candidate transition is:

$$
\mathcal{O}_t = operatorname{Generate}(SWM_t,E_t,G_t),
$$

$$
\mathcal{F}_t = operatorname{Feasible}(\mathcal{O}_t,E_t,R_t),
$$

$$
\mathcal{U}_t = operatorname{Authorized}(\mathcal{F}_t,\Pi_t),
$$

$$
D_t = operatorname{Choose}(\mathcal{U}_t,V_t,M_t,H_t),
$$

$$
X_{t+1}=operatorname{Execute}(D_t,X_t),
$$

$$
S_{t+1}=operatorname{Update}(S_t,X_{t+1},F_t).
$$

Here \(\mathcal{O}_t\) denotes proposed options, \(\mathcal{F}_t\) physically or operationally feasible options, and \(\mathcal{U}_t\) authorized feasible options. The equations are **candidate interfaces**, not claims that these functions are known or that all agency is reducible to a pipeline.

## 2.2 Choice requires attribution

A choice record should distinguish the **beneficiary**, **evaluator**, **decision authority**, **executor**, and **affected parties**. These roles may coincide in an individual human decision but frequently diverge in human–AI systems. A system that selects an action because a human authorized a narrow delegation is not thereby the owner of the human's values.

# 3. Structural Agency: An Operational Definition

We propose:

> **Structural Agency is the capacity of a distinguishable, historically situated system to organize context-sensitive alternatives, participate in attributable selection, regulate action through applicable authority, and adapt its future behavior using evidence and feedback.**

The definition deliberately does not require unconstrained autonomy. Agency may be partial, delegated, constrained, collective, or conditional. It does not assert phenomenal subjectivity.

## 3.1 Agency dimensions

A candidate **Agency Profile** is:

$$
\mathbf{A}_S=(a_g,a_o,a_e,a_d,a_x,a_r,a_p),
$$

where:

- \(a_g\): ability to form or negotiate goals;
- \(a_o\): ability to generate and discover alternatives;
- \(a_e\): ability to evaluate alternatives;
- \(a_d\): authority and capacity to select;
- \(a_x\): capacity to execute or direct execution;
- \(a_r\): reflective capacity to inspect and revise evaluators;
- \(a_p\): provenance and accountability of these processes.

The dimensions need not be commensurable. We do not propose a universal weighted sum that declares one system “more of a subject” than another.

## 3.2 Agency without unrestricted autonomy

A physician, pilot, researcher, or autonomous robot may exercise substantial functional agency within strong constraints. Constraints can protect other subjects, preserve commitments, and prevent irreversible harm. Thus, unrestricted action is neither necessary nor sufficient for legitimate agency.

A subject can have **high competence and low authority**; **high authority and low competence**; or **high execution capability and little reflective control**. A correct design must represent these combinations rather than assigning one opaque autonomy score.

# 4. Functional Freedom Is Not Option Count

## 4.1 The option-count fallacy

Let \(\mathcal{O}\) be a set of nominal options. A naive measure is \(|\mathcal{O}|\). This fails when options are inaccessible, dominated, coerced, misleading, unaffordable, unauthorized, or indistinguishable in their consequences.

An agent with 1,000 prohibited commands may have less effective freedom than an agent with three feasible, meaningful, legitimate choices. A person offered a choice between two harmful outcomes under coercion is not made free merely by having two alternatives.

## 4.2 The Structural Freedom Profile

We propose a multidimensional **Structural Freedom Profile (SFP)**:

$$
\mathbf{F}_{S,t}=(f_{\mathrm{feas}},f_{\mathrm{meaning}},f_{\mathrm{auth}},f_{\mathrm{reflect}},f_{\mathrm{inform}},f_{\mathrm{revise}},f_{\mathrm{contest}}),
$$

where the dimensions concern:

1. **Feasibility:** Can alternatives actually be performed?
2. **Meaningfulness:** Are they substantively distinct and relevant?
3. **Authority:** Can the subject legitimately choose or delegate among them?
4. **Reflective control:** Can the subject inspect reasons and challenge evaluations?
5. **Information quality:** Does the subject have adequate evidence and calibrated uncertainty?
6. **Revisability:** Can relevant constraints, goals, or evaluators be changed through appropriate procedures?
7. **Contestability:** Can decisions or delegated structures be appealed, overridden, or reviewed by authorized parties?

These are candidate dimensions requiring task-specific operationalization. No philosophical definition of free will follows from them.

## 4.3 A partial ordering rather than a single freedom score

For profiles \(\mathbf{F}_1\) and \(\mathbf{F}_2\), one can define **task-specific dominance** only when the relevant dimensions and measurement scales are justified. If one profile improves information quality while another improves execution autonomy, neither need dominate the other. The research program should preserve these tradeoffs rather than hide them behind arbitrary weights.

## 4.4 Functional freedom can include self-restraint

A commitment voluntarily adopted and legitimately maintained may expand long-term agency by preventing short-term impulsive actions. Safety constraints can similarly preserve future option sets. The challenge is to distinguish protective commitments from externally imposed restrictions, manipulation, or coercion. The same technical constraint can have different legitimacy depending on provenance, consent, context, and affected rights.

# 5. From Scoring Forest to Choice

SSI-004 investigated how Scoring Forests organize subject-relative valuation. SSI-005 adds the missing choice and authority interfaces.

```text
Observation -> Subjective World Model
                       |
                       v
               Option Generation
                       |
                       v
               Feasibility Filter
                       |
                       v
               Scoring Forest
                       |
               Evidence / Counter-Evidence
                       |
                       v
               Authority Check
                       |
                       v
              Choice / Escalation
                       |
                       v
                  Execution
                       |
                       v
              Feedback and Audit
```

**Proposed figure:** `figures/Fig-005-Agency-Choice-and-Functional-Freedom.png` (working filename; reconcile with repository figure index before release).

## 5.1 Score provenance

A scoring result should, when material to the decision, identify:

- Which subject or stakeholder the score purports to represent.
- Which criteria and weights were used.
- Which evidence and uncertainty supported the score.
- Which evaluator version produced it.
- Which constraints were treated as hard requirements.
- Which alternatives were omitted and why.

This connects to the **Subject-Relative Valuation Contract (SRVC)** proposed in SSI-004. SRVC is a candidate contract design, not an existing standardized protocol.

## 5.2 Selection is not automatically legitimate

Even a perfectly calibrated Scoring Forest cannot create authority from computation. The highest-ranked action may be unavailable or disallowed. A policy violation should not become permissible merely because the expected reward is large. Hard constraints, authorization checks, and escalation paths should remain independently visible.

## 5.3 Refusal, deferral, and inquiry are genuine options

A choice architecture that only offers “execute A” or “execute B” may conceal critical alternatives:

- Ask for clarification.
- Request consent.
- Gather more evidence.
- Escalate to an accountable decision maker.
- Defer action.
- Refuse an unauthorized operation.
- Propose a policy revision without applying it.

These meta-options are especially important under uncertainty and asymmetric risk.

# 6. The Agency–Authority Matrix

The **Agency–Authority Matrix (AAM)** is a candidate representation that separates the capacity to perform an operation from the authority to approve it.

| Operation | Human principal | AI assistant | Policy authority | External stakeholder |
|---|---|---|---|---|
| Supply goals and preferences | May provide | May elicit/interpret | May constrain | May express affected interests |
| Generate alternatives | May generate | May generate | May define exclusions | May contribute evidence |
| Evaluate alternatives | May evaluate | May evaluate under contract | May audit | May challenge consequences |
| Make consequential choice | Retained unless validly delegated | Only within explicit delegation | May impose limits | Rights may constrain choice |
| Execute action | May execute | Only when authorized and capable | May block or require review | May be affected |
| Change evaluators | May request or approve within authority | May propose; apply only if authorized | May require review | May contest adverse changes |
| Modify action permissions | Not inherently unrestricted | No implicit permission | Governed authorization process | Relevant rights remain |

This table is illustrative, not a universal legal or organizational allocation. Actual authority depends on the governing context.

## 6.1 Delegation as a scoped contract

A candidate delegation record is:

$$
\delta=(p,d,\mathcal{A},C,T,R,\rho),
$$

where \(p\) is principal, \(d\) delegate, \(\mathcal{A}\) permitted operations, \(C\) contextual conditions, \(T\) time scope, \(R\) revocation rules, and \(\rho\) audit/provenance requirements.

Delegation should be explicit about whether it grants **information access**, **evaluation**, **choice**, **execution**, or **structural revision**. Permission for one does not imply permission for the others.

## 6.2 Revocation and reversibility

A delegated choice architecture should specify what happens when authorization expires or is revoked, including pending actions, durable effects, and irreversible operations. Reversibility is not guaranteed. This makes pre-execution review and risk-sensitive escalation essential in consequential settings.

# 7. The Choice Provenance Graph

We propose the **Choice Provenance Graph (CPG)** to connect subject attribution, evaluative reasoning, authority, execution, and consequences.

$$
CPG=(N_C,E_C,\Lambda_C),
$$

where nodes may represent observations, hypotheses, options, evaluators, constraints, authorization decisions, choices, actions, and feedback; edges represent causal, justificatory, or authorization relationships; and metadata includes provenance, uncertainty, timestamps, and version identifiers.

```text
Subject / Stakeholders
         |
         v
Observation -> World-Model Version
         |               |
         v               v
Candidate Options -> Scoring Evidence
         |               |
         +-------+-------+
                 |
                 v
          Constraint Check
                 |
                 v
        Authorization Record
                 |
                 v
            Choice Record
                 |
                 v
         Execution / Refusal
                 |
                 v
        Consequences / Audit
                 |
                 v
         Historical Identity Graph
```

## 7.1 CPG versus HIG

The **Historical Identity Graph (HIG)**, introduced in SSI-002, records identity-relevant historical transformations. The CPG records **why and under whose authority a particular choice was made**. A CPG may supply selected events to an HIG, but the graphs have distinct purposes. Neither is identical to a Calling Graph, which primarily captures invocation or execution relationships.

## 7.2 CPG minimal contract

For high-impact choices, a candidate minimal record includes:

1. Subject or represented stakeholder identifier.
2. Context and world-model version.
3. Material alternatives considered.
4. Applicable valuation contract and evaluator versions.
5. Binding constraints and authorization source.
6. Selected outcome, refusal, or escalation.
7. Execution result and observed consequences.
8. Uncertainty, counter-evidence, and audit references.

Not every low-risk interaction warrants full graph storage. Data minimization, privacy, retention limits, and selective logging must be part of the design.

# 8. Reflective Agency and Second-Order Choice

## 8.1 Choosing actions versus choosing evaluators

First-order agency selects among actions under a given evaluator. Second-order agency examines the evaluator itself. A system might ask: “Why do I value speed over reliability?” or “Should this scoring criterion be revised after contradictory evidence?”

We distinguish:

$$
D_t^{(1)}=operatorname{ChooseActions}(\mathcal{U}_t,V_t),
$$

$$
D_t^{(2)}=operatorname{ProposeRevision}(V_t,H_t,F_t,M_t).
$$

A proposal is not authorization. Installation requires a separate governed process:

$$
V_{t+1}=operatorname{ApplyIfAuthorized}(V_t,D_t^{(2)},\Pi_t).
$$

## 8.2 Evaluator lock-in and evaluator drift

Two opposing failure modes arise:

- **Lock-in:** a subject cannot revise an evaluator despite strong evidence that it is harmful or mistaken.
- **Drift:** evaluators change too readily, losing important commitments, historical accountability, or legitimate constraints.

Functional freedom therefore includes neither unconditional stability nor unconditional self-modification. It includes the ability to **propose, justify, contest, authorize, test, and audit** revisions where appropriate.

## 8.3 Anti-Goodhart and counter-evidence

When a score becomes a target, optimization may exploit imperfections in the score. A reflective agent should ask whether a high score corresponds to the intended outcome, and whether counter-evidence challenges the metric. Useful safeguards include independent outcome measures, distribution-shift tests, held-out evidence, red-team counterexamples, and separation of evaluation and authorization.

# 9. The Structural Freedom Expansion Loop

A subject may improve freedom not merely by selecting an existing option but by discovering or creating new legitimate possibilities.

```text
Current Situation
       |
       v
Current Feasible / Authorized Options
       |
       v
Detect Missing Capability or Constraint
       |
       v
Generate Structural Growth Proposal
       |
       v
Evidence + Risk + Authority Review
       |
       +---- Reject / Defer / Revise
       |
       v
Authorized Capability or Policy Change
       |
       v
Expanded or Improved Possibility Space
       |
       v
Feedback + HIG / CPG Update
```

Examples include learning a new skill, acquiring a tool, negotiating an appropriate permission, improving information quality, or correcting a faulty evaluator. Some changes narrow immediate options while increasing long-term safety or competence.

## 9.1 A non-monotonic freedom hypothesis

More structural growth need not increase freedom. A new capability can create dependence, increase exposure to coercion, or enable unauthorized actions. A newly installed evaluator can narrow the set of considered options. Therefore, the relationship between structural growth and functional freedom is **non-monotonic** and context-dependent.

## 9.2 Freedom over trajectories

Instantaneous option sets omit long-term effects. Let \(\tau=(S_t,a_t,S_{t+1},\ldots,S_{t+k})\) be a candidate trajectory. A trajectory-aware assessment may consider how current actions affect future feasible options, retained commitments, and the ability to reverse or contest decisions. This connects SSI to trajectory intelligence and policy decision systems.

# 10. Multi-Subject Agency and Conflicting Authority

A single action can affect multiple subjects with different interests. One subject's freedom may restrict another's. A system that maximizes one subject's score can violate the rights or commitments of another.

We propose that multi-subject choice preserve:

- Stakeholder identities and perspective provenance.
- Which outcomes each subject values or rejects.
- Relevant rights and hard constraints.
- Who has authority to decide and who may contest.
- Distribution of benefits, risks, and irreversible consequences.

**Aggregate utility alone does not establish legitimacy.** Some conflicts require negotiation, institutional process, or refusal rather than a technical optimization result. This paper does not claim a universal algorithm for moral or political legitimacy.

# 11. Three Illustrative Cases

## Case A — Human–AI medical decision support

A model ranks treatment options using evidence and patient-specific constraints. It may assist with information retrieval and comparative evaluation. Clinical judgment, patient consent, applicable law, and professional responsibilities remain separate. A correct score does not authorize the AI to prescribe or administer treatment. The CPG can record recommendations, uncertainties, consent boundaries, and escalation decisions, subject to privacy controls.

**Research question:** Does separating evaluator provenance from decision authority reduce unauthorized action and improve audit quality?

## Case B — Robot with limited physical capabilities

A robot evaluates five routes; only two are traversable, and one of those enters a restricted zone. Its meaningful authorized choice may consist of one route, waiting, or requesting assistance. If it acquires a new sensor or receives a legitimate permission update, its functional possibility space changes.

**Research question:** Can a Structural Freedom Profile predict effective choice quality better than nominal action count?

## Case C — Self-improving agent and evaluator revision

An agent detects that its speed metric rewards incomplete work. It proposes an evaluator revision based on counter-evidence. The proposed change is tested against held-out tasks and historical commitments; a separate authority approves or rejects installation. The HIG records the transformation, while the CPG records the proposal and authorization path.

**Research question:** Can governed second-order revision improve outcome quality while limiting evaluator drift and Goodhart exploitation?

# 12. Testable Hypotheses

The following are **candidate hypotheses**, not validated findings.

### H1 — Agency Decomposition

Separating evaluation, choice, authorization, execution, and revision improves attribution accuracy and detection of unauthorized actions compared with monolithic decision logging.

### H2 — Feasible-Option Quality

Measures of feasible, meaningful, authorized alternatives predict task-relevant effective choice better than nominal option count alone.

### H3 — Choice Provenance

CPG-style provenance improves reconstruction of consequential decisions compared with equally resourced flat logs, after controlling for recorded information content.

### H4 — Delegation Precision

Scoped delegation contracts reduce permission ambiguity and unauthorized execution compared with coarse all-or-nothing permissions.

### H5 — Reflective Revisability

Governed evaluator revision improves selected outcome measures under evaluator misspecification while preserving predefined stability constraints.

### H6 — Counter-Evidence

Explicit counter-evidence testing reduces proxy exploitation and unjustified evaluator confidence in controlled optimization settings.

### H7 — Trajectory-Aware Freedom

Assessments that include future option preservation better identify long-term agency loss than one-step action-set measures.

### H8 — Multi-Subject Provenance

Explicit stakeholder and authority separation improves detection of distributional harms and conflicting permissions compared with a single aggregated score.

# 13. Experimental Design and Falsification

## 13.1 Evaluation matrix

| Experiment | Intervention | Baseline | Primary metrics | Key confound |
|---|---|---|---|---|
| Choice attribution | Explicit stage separation | Monolithic agent trace | Correct attribution, violations | Extra logging detail |
| Option quality | SFP-informed selection | Option-count heuristic | Feasible success, regret, reversibility | Task design |
| Delegation | Scoped permissions | Broad permissions | Unauthorized acts, escalation accuracy | Different permission budgets |
| Provenance | CPG | Flat logs | Reconstruction accuracy, audit cost | Information parity |
| Reflective revision | Governed revision | Fixed or unrestricted evaluator | Outcome quality, drift, violations | Compute and review cost |
| Anti-Goodhart | Counter-evidence checks | Score-only optimization | Proxy exploitation, real outcomes | Test leakage |
| Multi-subject | Perspective and rights metadata | Aggregated scoring | Harm visibility, conflict detection | Normative benchmark choices |

## 13.2 Evaluation discipline

Experiments should preregister operational definitions where practical; use multiple domains; report uncertainty and confidence intervals; include adversarial and distribution-shift tests; and compare systems under matched computational, information, and human-review budgets. A richer architecture is not successful simply because it stores more metadata.

## 13.3 Falsification examples

The central claims would be weakened if, under fair comparisons, explicit provenance does not improve reconstruction; scoped delegation does not reduce errors; reflective revision fails to improve adaptation; or proposed freedom dimensions provide no explanatory value beyond simpler feasible-action metrics. Negative results should be preserved as counter-evidence rather than absorbed into unfalsifiable definitions.

# 14. Governance and Safety Requirements

Structural agency introduces risks when a system can change its own evaluators, permissions, or action interfaces. Candidate controls include:

1. **Separation of duties:** proposing, approving, and executing a high-impact change need not belong to the same actor.
2. **Least authority:** permissions are scoped to tasks, contexts, and time.
3. **Human review where warranted:** consequential or irreversible actions require appropriate oversight.
4. **Independent evidence:** evaluation revisions are tested against external outcomes and counter-evidence.
5. **Auditability:** material choices and changes preserve sufficient provenance.
6. **Revocation:** delegated permissions can be withdrawn, subject to real-world limits.
7. **Privacy:** logs do not become unrestricted surveillance records.
8. **Rollback or containment:** reversible changes support recovery; irreversible actions require stronger prior controls.
9. **Multi-subject safeguards:** affected parties' rights are not erased by an aggregate score.

These controls are design candidates, not a guarantee of safety or compliance with any particular legal regime.

# 15. Integration with the Structural Intelligence Ecosystem

**UCPSF:** supplies candidate scoring, evaluator composition, and policy-control mechanisms. SSI adds subject attribution, authority, reflective choice, and functional freedom. The two research programs remain separate.

**MDT / UTN / CBT:** can localize subject-conditioned alternatives, capabilities, constraints, and contextual meaning. Their role is structural representation and dispatch, not automatic legitimacy.

**CCC and Two-Way CCC:** can encode conditional action contracts and counter-evidence triggers. Conditions must remain interpretable within their authorized contexts.

**Calling Graphs:** describe execution dependencies and delegated calls. CPG captures why a choice was made and under whose authority; HIG captures identity-relevant history.

**PIRP / PIRU and Collective Structural Learning:** permit transfer of reusable decision structures. A transferred evaluator does not carry universal authority into a new subject or institution; localization and reauthorization may be necessary.

**Structural Recursive Self-Improvement:** can propose new evaluators, capabilities, and decision processes. SSI adds subject-specific continuity, evaluator provenance, and authority checks before consequential self-modification.

**Policy Decision Systems and Trajectory Intelligence:** provide natural settings for testing choice over multi-step trajectories, future option preservation, and the difference between local reward and long-term agency.

# 16. Limits and Non-Claims

This paper does **not** claim:

- A solution to metaphysical free will or determinism.
- That functional agency entails phenomenal consciousness.
- That an AI system has moral personhood or legal rights merely because it satisfies the proposed profile.
- That numerical scores can settle all conflicts of values or authority.
- That every increase in autonomy increases freedom or welfare.
- That the SFP, AAM, or CPG are validated standards.
- That any particular governance arrangement is universally legitimate.

It also does not equate an AI's ability to articulate reasons with verified reflective control. Explanations may be post hoc; experiments must assess whether they are causally informative and behaviorally predictive.

# 17. Open Research Questions

1. What minimum conditions justify attributing a choice to a functional subject?
2. How should shared or distributed decision authority be represented?
3. Can functional freedom be compared without imposing arbitrary value weights?
4. Which option qualities matter most under irreversible risk?
5. How should coercion, manipulation, and deceptive choice architectures be detected?
6. When is refusal an expression of agency rather than failure to act?
7. What evidence demonstrates genuine second-order evaluator control rather than verbal self-description?
8. How can structural revision be both adaptable and continuity-preserving?
9. When do protective constraints increase long-term functional freedom?
10. How should multi-subject rights and competing authorities constrain aggregation?
11. What minimum provenance is sufficient for accountability without excessive surveillance?
12. How do branching agents and copied policies affect responsibility attribution?
13. Can an agent improve future option quality without uncontrolled capability expansion?
14. Which architectures most effectively separate evaluator recommendation from execution authority?
15. What experimental results would justify abandoning the proposed SFP or CPG constructs?

# 18. Contributions

SSI-005 proposes six main research contributions:

1. A **five-stage decomposition** of perception, valuation, choice, execution, and revision.
2. A **multidimensional Structural Agency Profile** distinguishing capability from authority.
3. A **Structural Freedom Profile** that goes beyond nominal option count and permits non-comparable tradeoffs.
4. An **Agency–Authority Matrix** and scoped delegation contract for explicit control relationships.
5. A **Choice Provenance Graph** linking evaluation, authorization, action, consequences, and the HIG.
6. A **governed reflective-revision framework** connecting second-order choice, counter-evidence, Anti-Goodhart safeguards, and future possibility-space evolution.

Each is a candidate construct requiring formal specification, baseline comparisons, and empirical testing.

# 19. Conclusion — Whose Choice, Under Whose Authority?

A Scoring Forest can compare alternatives. A Subjective World Model can explain why those alternatives appear relevant. A Historical Identity Graph can preserve the subject's evolving provenance. But **none of these alone establishes who is entitled to choose, what can be executed, or how the criteria of choice may legitimately change**.

SSI-005 locates structural agency at the intersection of **subject attribution, meaningful options, evaluation, authority, execution, feedback, and reflective revision**. It treats functional freedom as a profile of real, situated capabilities and legitimate control—not as a count of buttons, a single score, or a metaphysical declaration.

The central insight is that an intelligent subject may exercise agency not only by selecting an action from a given set, but also by recognizing missing alternatives, requesting better evidence, challenging flawed evaluators, and pursuing authorized structural growth. Yet such growth must remain accountable to other subjects, established commitments, and legitimate constraints.

**A system's ability to select an action does not answer whose choice it is. Its ability to change the scoring rules does not answer who authorized the change. Structural agency requires both questions to remain visible.**

The next paper, **SSI-006 — Self-Models, Self-Referential Scoring, and Metacognition**, examines the reflective mechanisms through which a subject can represent, question, and potentially revise its own decision architecture.

---

# References and Intellectual Context

These references identify relevant established traditions; they do not validate the proposed SSI constructs.

1. Frankfurt, H. G. (1971). Freedom of the will and the concept of a person. *The Journal of Philosophy, 68*(1), 5–20.
2. Bratman, M. E. (1987). *Intention, Plans, and Practical Reason.* Harvard University Press.
3. Dennett, D. C. (1984). *Elbow Room: The Varieties of Free Will Worth Wanting.* MIT Press.
4. Sen, A. (1999). *Development as Freedom.* Oxford University Press.
5. Nussbaum, M. C. (2011). *Creating Capabilities: The Human Development Approach.* Harvard University Press.
6. Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.
7. Russell, S. (2019). *Human Compatible: Artificial Intelligence and the Problem of Control.* Viking.
8. Goodhart, C. A. E. (1975). *Problems of Monetary Management: The U.K. Experience.* Papers in Monetary Economics, Reserve Bank of Australia.
9. Manheim, D., & Garrabrant, S. (2019). Categorizing variants of Goodhart's law. *arXiv:1803.04585*.
10. Pearl, J. (2009). *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge University Press.
11. Parfit, D. (1984). *Reasons and Persons.* Oxford University Press.
12. Gibson, J. J. (1979). *The Ecological Approach to Visual Perception.* Houghton Mifflin.

# Related Research

- [Structural Recursive Self-Improvement](https://github.com/sizhet/Structural-Recursive-Self-Improvement)
- [Principle Intelligence and Open Structural Learning](https://github.com/sizhet/Principle-Intelligence-and-Open-Structural-Learning)
- [Metric Differential Tree, UTN, and Context-Bound Token Intelligence](https://github.com/sizhet/Metric-Differential-Tree-UTN-and-Context-Bound-Token-Intelligence)
- [Portable Intelligence Runtime Pieces and Units](https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units)
- [Pre-AGI AI Action Governance](https://github.com/sizhet/Pre-AGI-AI-Action-Governance)

# Citation

Tan, S., & GPT-Obot. (2026). *SSI-005: Structural Agency, Choice, and Functional Freedom.* Subjective Structural Intelligence Research Program, Version 1.0.0. https://github.com/sizhet/Subjective-Structural-Intelligence

Replace the provisional repository citation with the archival DOI after release.

# Research Status

**Maturity:** Theoretical and architectural proposals; no empirical validation claimed.

**Candidate constructs:** Structural Agency Profile; Structural Freedom Profile; Agency–Authority Matrix; Choice Provenance Graph; scoped delegation; governed reflective revision.

**Validation priorities:** Feasible-option quality, provenance utility, authority separation, evaluator-revision stability, multi-subject safeguards, and trajectory-aware measures of future options.

**Next document:** `SSI-006-Self-Models-Self-Referential-Scoring-and-Metacognition.md` (planned).

---

**End of SSI-005**  
*© 2026 Sizhe Tan & GPT-Obot. Licensed under Apache-2.0.*
