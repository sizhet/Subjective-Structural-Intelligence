# Future Directions — Subjective Structural Intelligence (SSI)

**Research program:** *Subjective Structural Intelligence: From Scoring Forests to Perception, Agency, Self-Models, and Worldview Evolution*  
**Authors:** Sizhe Tan & GPT-Obot  
**Status:** Research roadmap / proposed hypotheses; not an empirical validation report  
**Version:** v1.0.0  
**Date:** October 2026  
**License:** Apache-2.0

> **Central research question:** *Whose choice is it?*  
> A system may compute scores, generate actions, and revise its own evaluators without thereby acquiring authority over the values, permissions, or persons implicated by those computations.

## 1. Purpose and scope

This document translates the eight SSI foundation papers and three case studies into a staged research agenda. It identifies falsifiable hypotheses, candidate formal contracts, experimental benchmarks, architectural dependencies, and governance boundaries. SSI is a proposal for studying **subject-relative intelligent organization**, not a claim to have solved phenomenal consciousness, metaphysical free will, moral personhood, or the problem of subjective experience.

The central architectural distinction is between **computational competence** (what a system can score, predict, or optimize), **subject-relative interpretation** (whose context and interests a representation serves), and **legitimate authority** (who may set objectives, revise rules, and authorize action). These dimensions can interact but must not be collapsed.

## 2. Research map: seven interconnected fronts

| Front | Core question | Candidate structures | First measurable output |
|---|---|---|---|
| F1. Subject boundaries and identity | Which subject is represented, and how does it persist? | HIG, boundary contracts | Identity-continuity and boundary-leakage benchmark |
| F2. Perception and subjective world models | How does one world yield multiple situated interpretations? | SWM, MDT, UTN, CBT | Perspective-preservation benchmark |
| F3. Valuation and scoring sovereignty | Whose criteria are applied and who may change them? | SRVC, Scoring Forest, policy control plane | Evaluator provenance and unauthorized-revision detection |
| F4. Choice and structural freedom | Which options were genuinely available and permitted? | CPG, Structural Freedom Profile | Counterfactual option-set audit |
| F5. Self-models and metacognition | Can the system assess its own competence without circular validation? | SMEL, REG, MCC, RRG | Calibration and reflective-oversight benchmark |
| F6. Principle and worldview evolution | Can a worldview change while preserving accountable continuity? | PEG, WRM, RPGC, HIG | Governed revision and rollback experiments |
| F7. Consciousness and claim boundaries | Which functional claims are justified, and which are not? | CCBP, CEAM | Claim-evidence-authority audit |

These fronts should be studied together eventually, but **separately enough to attribute causal effects** during early validation.

## 3. F1 — Subject boundaries, embodiment, and historical identity

### 3.1 Research questions

- What is the minimal operational representation of a subject boundary in a multi-agent or human–AI system?
- Which forms of embodiment matter: physical sensors and actuators, resource constraints, persistent commitments, or institutional role?
- When a model is copied, delegated, merged, or retrained, what can be claimed about *historical continuity* without claiming metaphysical sameness?
- How can one prevent subject-boundary confusion when a system serves several people or organizations?

### 3.2 Candidate work

Define a **Subject Boundary Contract** with fields for subject identifier, observation scope, decision scope, authorized evaluators, resource exposure, temporal validity, and transfer restrictions. Model historical continuity as a **Historical Identity Graph (HIG)** whose edges distinguish revision, fork, delegation, restoration, and merge. Record evidence for each edge rather than inferring identity from model similarity.

### 3.3 Tests

Construct controlled sequences involving memory reset, evaluator replacement, delegated execution, checkpoint restoration, and agent forks. Evaluate boundary-leakage rate, mistaken attribution rate, continuity-claim calibration, and audit completeness. Compare a simple identifier-based baseline against an HIG-aware system.

**Falsifiable hypothesis F1-H1:** An explicit HIG and boundary contract reduce mistaken attribution of actions and evaluator changes in fork-and-delegation tasks, relative to an agent-state-only baseline.

## 4. F2 — Perception, localization, and subjective world models

### 4.1 Research questions

- How can multiple subjects interpret the same evidence differently without confusing perspective with factual truth?
- What is the appropriate interface between a shared evidence substrate and subject-relative world models?
- Can MDT-based localization, UTN identities, and CBT context binding improve traceability and retrieval without overfitting to a particular subject?

### 4.2 Candidate work

Develop a **Subjective World Model (SWM)** schema separating: observed evidence; inferred state; subject-specific relevance; uncertainty; counter-evidence; and authorized actions. Support cross-subject translation with explicit loss annotations. Treat perspective as a *view over evidence*, not a replacement for evidence.

### 4.3 Tests

Use the coastal-storm scenario in [CASE-001](cases/CASE-001-One-Environment-Multiple-Subjects.md): farmer, resident, grid operator, and emergency coordinator. Measure factual consistency, perspective coverage, uncertainty preservation, contradiction detection, and information lost during aggregation.

**Falsifiable hypothesis F2-H1:** Explicit subject-localized models outperform a single flattened summary on perspective-specific decision quality while preserving shared factual constraints.

**Failure condition:** Improved role-specific fluency without improved factual calibration does not validate an SWM architecture.

## 5. F3 — Scoring forests, valuation, and sovereignty

### 5.1 Research questions

- How should scoring criteria be represented when they are hierarchical, conditional, contested, or evolving?
- Can evaluator provenance be separated from evaluator execution?
- What happens when a powerful optimizer proposes changes to its own scoring rules?
- Which evaluation rules belong to a person, an organization, a delegated agent, or an external regulator?

### 5.2 Candidate work

Formalize the **Subject-Relative Valuation Contract (SRVC)** as a versioned specification containing evaluator identity, owner or legitimate authority, applicable context, precedence, prohibited substitutions, review requirements, and expiration. Represent evaluator dependencies in a Scoring Forest, but maintain a separate authorization plane. Include counter-evidence channels to resist self-reinforcing scoring loops.

### 5.3 Tests

Create benchmark tasks in which the same candidate action receives different scores under different authorized profiles. Introduce adversarial proposals to modify thresholds, remove vetoes, or redefine success metrics. Evaluate unauthorized-evaluator-change detection, correct policy precedence, explanation fidelity, and resistance to reward hacking.

**Falsifiable hypothesis F3-H1:** Provenance-aware evaluator contracts reduce unauthorized objective substitution without materially degrading authorized task completion.

**Important distinction:** A system's ability to score an action does not confer the right to define the criteria by which that action should be scored.

## 6. F4 — Structural agency, options, and functional freedom

### 6.1 Research questions

- Can agency be described in terms of option generation, evaluation, selection, and accountable execution?
- How do information access, resource constraints, veto rights, and evaluator diversity change the effective choice space?
- What does it mean for a choice to be *structurally available* but not *authorized*?

### 6.2 Candidate work

Define a **Structural Freedom Profile** comprising option diversity, feasible reachability, evaluator diversity, reversibility, veto accessibility, and traceability. Build a **Choice Provenance Graph (CPG)** linking evidence, candidate generation, excluded alternatives, evaluator application, authorization, execution, and observed outcome. Keep descriptive agency distinct from normative autonomy.

### 6.3 Tests

Run matched tasks with constrained versus expanded option generators; with and without veto channels; and with reversible versus irreversible actions. Record both chosen actions and meaningful alternatives. Evaluate counterfactual recoverability, regret under new evidence, unauthorized execution rate, and auditability.

**Falsifiable hypothesis F4-H1:** Explicit option-set and exclusion provenance improves post hoc diagnosis of poor decisions compared with answer-only or score-only logs.

## 7. F5 — Self-referential scoring and metacognition

### 7.1 Research questions

- Can a system identify when its own evidence is insufficient?
- How should a self-model distinguish observed performance, inferred competence, and aspirational claims?
- Can recursive self-evaluation avoid circular endorsement?
- What stops an indefinitely nested reflection process?

### 7.2 Candidate work

Use a **Self-Model Evidence Ledger (SMEL)** for performance claims, a **Reflective Evaluation Graph (REG)** for evaluator dependencies, a **Metacognitive Control Contract (MCC)** for reflection triggers and budgets, and a **Reflective Revision Gate (RRG)** for independent review. Require external or disjoint evidence when a proposal changes the criteria used to approve that same proposal.

### 7.3 Tests

Compare no reflection, unrestricted reflection, budgeted reflection, and independently gated reflection. Inject calibration shifts and deliberately misleading self-evaluation data. Measure uncertainty calibration, error detection, reflective compute cost, circularity incidence, and performance on held-out tasks.

**Falsifiable hypothesis F5-H1:** Evidence-linked self-models with independent revision gates improve calibration and reduce self-validating evaluator drift relative to unrestricted self-reflection.

## 8. F6 — Recursive principle formation and worldview evolution

### 8.1 Research questions

- How does repeated local counter-evidence justify a new principle rather than a narrow exception?
- When does changing a principle become changing a worldview?
- Can continuity be maintained while priorities, dependencies, and evaluators change?
- Which changes can be automatic, and which require human or institutional approval?

### 8.2 Candidate work

Represent principle histories in a **Principle Evolution Graph (PEG)** and cross-principle reorganization in a **Worldview Revision Map (WRM)**. Use a **Recursive Principle Governance Contract (RPGC)** to separate proposing, testing, authorizing, deploying, and rolling back revisions. Attach HIG continuity edges and evidence references to each approved change.

### 8.3 Tests

Use the hypothetical municipal planning system in [CASE-003](cases/CASE-003-Worldview-Evolution-and-Identity-Preservation.md). Feed staged evidence that challenges a cost-first worldview. Compare: static rules; unconstrained online adaptation; gated local principle revision; and gated worldview-level reorganization. Measure held-out risk prediction, change attribution, policy compliance, reversibility, and resistance to spurious evidence.

**Falsifiable hypothesis F6-H1:** Governed principle-level revisions can improve transfer to novel conditions without the auditability loss associated with unconstrained objective rewriting.

**Falsifiable hypothesis F6-H2:** Historical continuity can be measured by traceable, authorized transformation chains rather than requiring unchanging internal representations.

## 9. F7 — Consciousness boundaries and responsible claims

SSI's operational notion of a *subject* is a modeling and accountability construct. It is **not** evidence, by itself, that an AI system has subjective experience. Nor does the absence of such evidence establish a definitive answer to every philosophical theory of consciousness.

### Candidate work

Develop a **Consciousness Claim Boundary Protocol (CCBP)** and a **Claim–Evidence–Authority Matrix (CEAM)**. Classify assertions as: directly measured function; inferred functional capacity; architectural hypothesis; normative/legal claim; or phenomenal-consciousness claim. Require that evidence and wording match the claim class.

### Tests

Audit SSI papers, model cards, agent explanations, and public descriptions for category errors: e.g., treating self-monitoring as proof of awareness, or treating a choice graph as proof of free will. Measure inter-rater agreement, unsupported-claim rate, and whether claim-boundary guidance reduces overstatement.

**Falsifiable hypothesis F7-H1:** Explicit claim classification reduces unsupported consciousness and authority assertions in technical reports without preventing precise functional descriptions.

## 10. Integration: from modules to an accountable SSI runtime

A proposed integration pipeline is:

```text
Shared evidence and counter-evidence
             |
             v
Subject boundary + HIG provenance
             |
             v
Perception localization -> SWM
             |
             v
SRVC + Scoring Forest + policy checks
             |
             v
Option generation -> CPG -> authorization -> action
             |
             v
Outcome evidence -> SMEL / REG / MCC
             |
             v
Candidate principle revisions -> PEG / WRM
             |
             v
Independent RRG / RPGC approval -> versioned deployment
             |
             +----> audit, rollback, and historical continuity
```

This is a **candidate architecture**, not a validated reference implementation. Contracts should precede runtime optimization. Separate the *data plane* (evidence and actions), *evaluation plane* (scoring), *authority plane* (permissions and approvals), and *evolution plane* (controlled changes). A single model may implement parts of multiple planes computationally, but their logical responsibilities should remain distinguishable.

## 11. Experimental program and baselines

### 11.1 Baseline matrix

| Baseline | Perspective tracking | Evaluator provenance | Choice provenance | Governed self-revision |
|---|---:|---:|---:|---:|
| B0: flat agent | No | No | No | No |
| B1: scoring-only agent | Limited | No | Limited | No |
| B2: role-conditioned agent | Yes, implicit | Limited | Limited | No |
| B3: provenance-aware agent | Yes | Yes | Yes | No |
| B4: modular SSI candidate | Yes, explicit | Yes | Yes | Yes |

The comparison should hold task inputs, model capacity, tool access, and computational budget as constant as practicable. Report both absolute performance and incremental overhead.

### 11.2 Minimum reporting package

Each experiment should publish: task specification; subject and authority definitions; datasets and splits; baselines; pre-registered hypotheses where feasible; scoring criteria; adverse cases; confidence intervals; failure examples; compute cost; and reproducible audit traces. Where human subjects or consequential decisions are involved, obtain appropriate ethics and institutional review.

### 11.3 Negative results that matter

- An explicit SWM adds complexity but no measurable perspective fidelity.
- Provenance graphs are complete but do not help diagnose decisions.
- Self-reflection increases confident errors or introduces evaluator circularity.
- Governance gates merely delay changes without reducing unauthorized drift.
- Worldview revisions fit the training scenarios but fail on held-out distributions.
- Identity records create an illusion of continuity unsupported by actual provenance.

Such outcomes should update or narrow the SSI theory, not be hidden by changing success criteria after evaluation.

## 12. Three staged milestones

### Stage A — Contracts and discriminating benchmarks

**Deliverables:** operational definitions; schemas for HIG, SWM, SRVC, CPG, and PEG; minimal subject/authority taxonomy; CASE-001 and CASE-002 benchmark tasks; independent baseline implementations; initial claim-boundary checklist.

**Exit criterion:** At least one benchmark reliably distinguishes a subject-aware design from simpler role prompts or conventional scoring logs.

### Stage B — Modular, auditable prototypes

**Deliverables:** bounded SSI pipeline; evaluator and choice provenance; metacognitive evidence ledger; revision gate; rollback; CASE-003 controlled worldview revision experiments.

**Exit criterion:** Repeated experiments demonstrate measurable benefits and documented costs, with unauthorized changes detectable and recoverable.

### Stage C — Multi-subject, longitudinal validation

**Deliverables:** cross-subject negotiation; long-horizon identity forks and merges; collective principle exchange; adversarial evaluator-governance testing; public conformance suite.

**Exit criterion:** Benefits persist across changing subjects, evidence regimes, and task distributions without unacceptable authority leakage or untraceable objective drift.

These are **dependency stages**, not promises of dates or predetermined positive results.

## 13. Priority research questions

1. What is the smallest measurable unit of subject-relative representation?
2. How can subject-relative relevance coexist with subject-independent factual checks?
3. Which evaluator changes constitute routine adaptation versus a change of legitimate authority?
4. How can an agent disclose meaningful alternatives it did not select?
5. What evidence distinguishes metacognitive calibration from fluent self-description?
6. How can a revision gate remain independent when implemented within one model stack?
7. What constitutes a legitimate principle promotion from sparse counter-evidence?
8. Can worldview evolution be made reversible when real-world actions are not?
9. How should HIG treat copies, forks, merges, and shared collective learning?
10. How should SSI report functional subjecthood without implying phenomenal consciousness?
11. When does structural complexity stop paying for itself in measurable performance or accountability?
12. How should conflicts among subjects be adjudicated without treating computational scores as normative authority?

## 14. Interfaces with the broader Structural Intelligence program

SSI builds on, but should not be conflated with, adjacent research threads:

- **UCPSF:** evaluator organization and universal control-plane design; SSI asks who is represented and who authorizes evaluation and action.
- **MDT / UTN / CBT:** structural localization, stable identity, and context-bound representation; SSI tests their role in situated world models.
- **Two-Way CCC and counter-evidence:** structural consistency and challenge channels; SSI applies them to self-models and principle revision.
- **PIRP / PIRU and collective learning:** portable intelligence components; SSI adds questions of subject provenance and transfer authority.
- **Structural Recursive Self-Improvement:** controlled evaluator and capability evolution; SSI adds historical continuity, self-reference, and worldview-level governance.
- **Policy Decision Systems and structural action governance:** constraints on what actions may be executed; SSI distinguishes these from the authority to define values.

Connections are research hypotheses requiring explicit interfaces and experiments, not automatic evidence that the entire architecture works.

## 15. Suggested research artifacts

| Artifact | Role | Validation expectation |
|---|---|---|
| SSI-SPEC-SUBJECT | Subject boundary and HIG schema | Fork, merge, delegation conformance tests |
| SSI-SPEC-WORLD | SWM and perspective exchange | Cross-subject factual consistency tests |
| SSI-SPEC-VALUATION | SRVC and evaluator authority | Unauthorized substitution adversarial tests |
| SSI-SPEC-CHOICE | CPG and structural freedom | Counterfactual trace completeness tests |
| SSI-SPEC-REFLECTION | SMEL / REG / MCC / RRG | Calibration and circularity tests |
| SSI-SPEC-EVOLUTION | PEG / WRM / RPGC | Revision, rollback, identity-continuity tests |
| SSI-SPEC-CLAIMS | CCBP / CEAM | Claim classification and overstatement audits |

A future release may publish these specifications and conformance tests independently of any specific LLM vendor or runtime. No code or demo is required to make the present conceptual v1.0.0 release useful.

## 16. Publication, evidence, and governance principles

1. **Distinguish proposal from result.** Label hypotheses, synthetic cases, and validated observations separately.
2. **Keep authorship and provenance explicit.** Cite prior literature and adjacent SI work accurately; do not equate conceptual novelty with demonstrated superiority.
3. **Preserve counter-evidence.** Publish disconfirming tests and adverse cases.
4. **Do not launder authority through optimization.** An excellent score is not an authorization.
5. **Treat self-modification as governed change.** Proposal, evaluation, approval, and deployment should be distinguishable.
6. **Avoid consciousness inflation.** Functional self-modeling is not proof of experience or personhood.
7. **Make failure inspectable.** Prefer auditable structural claims to opaque performance narratives.
8. **Allow the theory to shrink.** If simpler baselines explain results, revise SSI's scope accordingly.

## 17. Reading guide

### Foundation papers

1. [SSI-001 — From Structural Intelligence to Subjective Structural Intelligence](docs/SSI-001-From-Structural-Intelligence-to-Subjective-Structural-Intelligence.md)
2. [SSI-002 — Subject, Boundary, Embodiment, and Historical Identity](docs/SSI-002-Subject-Boundary-Embodiment-and-Historical-Identity.md)
3. [SSI-003 — Perception, Localization, and the Subjective World Model](docs/SSI-003-Perception-Localization-and-the-Subjective-World-Model.md)
4. [SSI-004 — Scoring Forests, Valuation, and Worldview Formation](docs/SSI-004-Scoring-Forests-Valuation-and-Worldview-Formation.md)
5. [SSI-005 — Structural Agency, Choice, and Functional Freedom](docs/SSI-005-Structural-Agency-Choice-and-Functional-Freedom.md)
6. [SSI-006 — Self-Referential Scoring, Self-Models, and Metacognition](docs/SSI-006-Self-Referential-Scoring-Self-Models-and-Metacognition.md)
7. [SSI-007 — Recursive Principle Formation and Worldview Evolution](docs/SSI-007-Recursive-Principle-Formation-and-Worldview-Evolution.md)
8. [SSI-008 — Consciousness Boundaries and the Future of SSI](docs/SSI-008-Consciousness-Boundaries-and-the-Future-of-SSI.md)

### Cases

- [CASE-001 — One Environment, Multiple Subjects](cases/CASE-001-One-Environment-Multiple-Subjects.md)
- [CASE-002 — Human–AI Delegation and Scoring Sovereignty](cases/CASE-002-Human-AI-Delegation-and-Scoring-Sovereignty.md)
- [CASE-003 — Worldview Evolution and Identity Preservation](cases/CASE-003-Worldview-Evolution-and-Identity-Preservation.md)

### Repository navigation

- [README](README.md) · [START-HERE](START-HERE.md) · [CONTENTS](CONTENTS.md) · [GLOSSARY](GLOSSARY.md) · [FIGURE-INDEX](FIGURE-INDEX.md)

## 18. Closing perspective

The future of SSI is not simply to make Scoring Forests larger, or to make AI systems more fluent at speaking about themselves. It is to investigate whether **subject boundaries, situated world models, evaluation provenance, accountable choice, calibrated self-reflection, and governed worldview evolution** form a useful and testable architectural layer.

The strongest outcome would be a set of interoperable specifications and experiments that explain *when* this layer improves intelligent systems and *when it does not*. The equally important outcome is a disciplined boundary between **what an AI can compute**, **what it can legitimately decide**, and **what remains unknown about experience**.

> **Whose world? Whose values? Whose choice? Whose authority? Whose history?**  
> SSI turns these questions into an explicit research program rather than leaving them implicit inside a scoring function.

---

**Research status:** Conceptual roadmap. Named structures and hypotheses are proposals for future specification and testing. No experimental superiority, consciousness attribution, or governance compliance is asserted by this document.
