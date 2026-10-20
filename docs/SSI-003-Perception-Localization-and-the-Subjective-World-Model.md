# SSI-003 — Perception, Localization, and the Subjective World Model

**Subtitle:** From Shared Reality to Subject-Relative Meaning Through Structural Localization

**Authors:** Sizhe Tan & GPT-Obot  
**Research Program:** Subjective Structural Intelligence (SSI)  
**Repository:** `Subjective-Structural-Intelligence`  
**Document:** `docs/SSI-003-Perception-Localization-and-the-Subjective-World-Model.md`  
**Version:** 1.0.0  
**Date:** October 19, 2026  
**Status:** Foundational Research Paper — Candidate Architecture and Testable Hypotheses  
**License:** Apache-2.0

---

## Abstract

Intelligent systems do not act directly upon an undifferentiated world. They receive partial observations, organize information, localize relevant structures, construct interpretations, and evaluate possible actions.

The same external event may therefore acquire different meanings for different subjects.

Subjective Structural Intelligence (SSI) investigates how such differences can arise from subject boundaries, embodiment, historical experience, goals, capabilities, attention, and evolving world models.

This paper proposes **Perception Localization** as a candidate structural mechanism connecting observations to subject-relative interpretation.

Unlike simple information retrieval, Perception Localization is not limited to finding relevant stored information. It also concerns which aspects of an observation become salient, which contexts are activated, which causal interpretations are considered, which uncertainties are preserved, and which action possibilities are recognized.

We introduce a candidate **Subjective World Model (SWM)** representing the organized relationship among a subject, its environment, its historical knowledge, its evaluative structures, and its possible actions.

The proposed architecture combines:

1. Subject-conditioned observation.
2. Structural attention and localization.
3. Contextual interpretation.
4. Subject-relative meaning construction.
5. World-model updating.
6. Counter-evidence and alternative-perspective evaluation.
7. Controlled structural growth.

The framework is connected to Metric Differential Trees (MDT), Universal Tree Nodes (UTN), Context-Bound Tokens (CBT), Contextual Control Constructs (CCC), Two-Phase Search, Scoring Forests, and Historical Identity Graphs (HIG).

We distinguish subjective perspective from factual correctness and functional perception from phenomenal experience.

The resulting research program proposes testable hypotheses concerning localization efficiency, perspective diversity, uncertainty preservation, counter-evidence, and world-model adaptation.

**Keywords:** Subjective Structural Intelligence, Perception Localization, Subjective World Model, Structural Perception, Situated Cognition, Subject-Relative Meaning, MDT, UTN, CBT, Context Engineering, Two-Phase Search, Counter-Evidence, Worldview Evolution

---

![Subject Boundary and Embodied Intelligence](../figures/Fig-003-Subject-Boundary-and-Embodied-Intelligence.png)

---

# 1. Introduction: One World, Many Perceived Worlds

## 1.1 The Same Event Can Have Different Meanings

Consider an approaching storm.

A farmer may interpret it as an opportunity for irrigation.

A coastal resident may interpret it as a flooding threat.

An electrical-grid operator may interpret it as a potential disruption to supply and demand.

A meteorological system may interpret it as a developing atmospheric pattern.

The physical event is shared.

The subjects' interpretations differ.

These differences may arise from:

- Different goals.
- Different vulnerabilities.
- Different capabilities.
- Different histories.
- Different knowledge.
- Different responsibilities.
- Different available actions.

The event itself does not contain a single universal practical meaning independent of all subjects.

However, this does not imply that the physical event is arbitrary or that all interpretations are equally accurate.

A storm has objective physical properties.

Subjects may interpret those properties differently while remaining constrained by the same external reality.

This motivates the central question:

**How does a shared world become a subject-relative perceived world?**

## 1.2 From Input Processing to Perception

A conventional computational pipeline may be represented as:

```text
Input
  |
  v
Feature Extraction
  |
  v
Representation
  |
  v
Prediction
  |
  v
Decision
```

This architecture can be effective.

But it often leaves subject-relative interpretation implicit.

SSI proposes an expanded view:

```text
External Reality
       |
       v
Observation Interface
       |
       v
Subject Boundary
       |
       v
Structural Localization
       |
       v
Contextual Interpretation
       |
       v
Subjective World Model
       |
       v
Valuation / Action
       |
       v
Experience / Feedback
       |
       v
World-Model Evolution
```

The difference is not merely the addition of more computational stages.

It is the explicit organization of perception relative to an identifiable subject.

## 1.3 The Central Thesis

We propose:

**Perception is a subject-conditioned process of structural localization and interpretation through which partial observations become organized into actionable, revisable world models.**

This is a functional and computational hypothesis.

It does not assert that all perception requires explicit symbolic structures.

Nor does it claim that the proposed architecture explains phenomenal visual, auditory, or other conscious experiences.

SSI studies the structural organization of perception and its relationship to subject-relative intelligent behavior.

---

# 2. Perception Is Not Raw Input

## 2.1 Observation and Perception Are Different

An observation is information obtained through an interface.

Perception involves organizing and interpreting that information.

A camera may produce an image.

An intelligent system may interpret the image as containing:

- A pedestrian.
- An obstacle.
- A destination.
- A warning sign.
- A possible collision.
- A navigable route.

The raw image does not explicitly contain all these semantic and action-related structures.

They depend on learned representations, context, and the system's capabilities.

Thus:

**Observation ≠ Perception.**

## 2.2 A Candidate Perception Model

Let:

- $X_t$: external environmental state.
- $O_t$: observation available to the subject.
- $B_t$: subject boundary.
- $E_t$: embodiment or operational capabilities.
- $H_t$: historical experience.
- $G_t$: goals and commitments.
- $W_t$: current world model.

We propose:

$$
O_t = \Omega(X_t,B_t,E_t)
$$

and:

$$
P_t = \Phi(O_t,B_t,E_t,H_t,G_t,W_t)
$$

where:

- $\Omega$: observation process.
- $\Phi$: perception and interpretation process.
- $P_t$: resulting perceptual organization.

The functions are conceptual placeholders.

They may be implemented through neural networks, symbolic structures, probabilistic inference, hybrid systems, or other mechanisms.

## 2.3 Perception Is Selective

A subject cannot necessarily process every available environmental detail with equal attention.

Perception therefore involves selection.

Selection may depend on:

- Relevance.
- Novelty.
- Risk.
- Expected utility.
- Historical importance.
- Uncertainty.
- Available resources.
- Current commitments.

For example, a rescue robot may prioritize human presence over decorative details.

A warehouse robot may prioritize obstacles and navigation routes.

A scientific instrument may prioritize measurement anomalies.

The same sensory input may activate different processing pathways.

This suggests that perception is partly a localization problem.

---

# 3. Perception Localization: The Core Structural Mechanism

## 3.1 What Is Localization?

In Structural Intelligence, localization refers broadly to identifying the relevant region, context, node, evaluator, or computational structure for a particular problem.

SSI extends this idea to perception.

**Perception Localization is the process of identifying and activating the subject-relevant structures through which observations are interpreted.**

It may determine:

1. What deserves attention.
2. Which stored knowledge is relevant.
3. Which context applies.
4. Which hypotheses should be considered.
5. Which uncertainties matter.
6. Which capabilities are available.
7. Which evaluators should participate.
8. Which counter-evidence should be retrieved.

This is broader than conventional document retrieval.

## 3.2 Localization Versus Retrieval

Retrieval typically asks:

> Which stored information is relevant to this query?

Perception Localization asks:

> Which structures make this observation meaningful to this subject in this context?

The distinction can be represented as:

```text
Conventional Retrieval:

Query
  |
  v
Relevant Documents
  |
  v
Returned Information


Perception Localization:

Observation + Subject Context
              |
              v
      Structural Localization
              |
      +-------+--------+
      |       |        |
      v       v        v
   Context  History  Capabilities
      |       |        |
      +-------+--------+
              |
              v
     Interpretation Candidates
              |
              v
       Subjective World Model
```

Retrieval can be an important component of localization.

But it does not exhaust the localization problem.

## 3.3 A Candidate Localization Function

Let:

- $O_t$: current observation.
- $C_{S,t}$: subject context.
- $\mathcal{K}_t$: available structural knowledge.
- $\mathcal{M}_t$: available models and evaluators.

We propose:

$$
L_t = \mathcal{L}(O_t,C_{S,t},\mathcal{K}_t,\mathcal{M}_t)
$$

where $L_t$ is a set or structured collection of activated interpretive resources.

Subject context may include:

$$
C_{S,t} = (B_t,E_t,H_t,G_t,W_t)
$$

The localization function should not necessarily produce a single winning interpretation.

It may preserve multiple candidates and their uncertainties.

## 3.4 Localization Is Not Truth

A subject may localize the wrong context.

It may activate an irrelevant evaluator.

It may overlook important evidence.

It may overfit an observation to a familiar historical pattern.

Therefore:

**Localization Success ≠ Interpretive Truth.**

A robust SSI architecture requires mechanisms for detecting localization errors.

Potential mechanisms include:

- Alternative-context search.
- Counter-evidence retrieval.
- Cross-perspective comparison.
- Confidence calibration.
- Prediction-error analysis.
- Structural revision.

## 3.5 Localization as an Efficiency Mechanism

Without localization, a system may attempt to evaluate an observation against a large collection of possible contexts and evaluators.

Localization can reduce computational cost by selecting relevant structures.

However, aggressive localization can introduce blind spots.

The research problem is therefore a tradeoff:

$$
\text{Efficiency} \leftrightarrow \text{Coverage} \leftrightarrow \text{Robustness}
$$

A successful localization mechanism should reduce unnecessary computation without systematically excluding important alternatives.

---

# 4. MDT, UTN, and CBT as Candidate Perception Structures

## 4.1 MDT: Differential Localization

Metric Differential Trees organize structural differences.

In SSI, an MDT may support localization by distinguishing:

- Subject types.
- Environmental conditions.
- Capability constraints.
- Historical contexts.
- Relevant causal patterns.
- Evaluation requirements.

For example:

```text
Observed Event
      |
      v
Environmental Change
      |
      +---- Weather
      |       |
      |       +---- Rainfall
      |       +---- Wind
      |       +---- Temperature
      |
      +---- Infrastructure
      |
      +---- Human Activity
```

The relevant path may depend on subject context.

A farmer may localize rainfall-related consequences.

A grid operator may localize infrastructure-related consequences.

A rescue team may localize human-safety consequences.

These differences should be treated as candidate subject-conditioned paths, not as proof that a specific tree structure is universally optimal.

## 4.2 UTN: Addressable Structural Context

Universal Tree Nodes may provide stable references to structural contexts.

Potential uses include:

- Context localization.
- Perception-history linking.
- Evaluator association.
- Subject-specific knowledge.
- World-model updates.
- Cross-subject comparison.

A node may be associated with:

- Structural identity.
- Context conditions.
- Relevant evidence.
- Historical provenance.
- Available evaluators.
- Confidence information.

However, a persistent node identifier does not guarantee that its interpretation remains unchanged.

Versioning and context-sensitive semantics may be necessary.

## 4.3 CBT: Context-Bound Interpretation

Context-Bound Tokens emphasize the relationship between a token or representation and its relevant context.

In SSI, a term such as "danger" may depend on:

- The observed event.
- The subject's capabilities.
- Historical experience.
- Current vulnerability.
- Available escape routes.
- Action authority.

The same token may therefore correspond to different subject-relative interpretations.

A candidate representation is:

$$
CBT = (\text{Token},\text{Context},\text{Subject},\text{Meaning})
$$

This is a conceptual extension.

It does not require every implementation to store all fields explicitly.

## 4.4 Combining MDT, UTN, and CBT

A possible structural pathway is:

```text
Observation
     |
     v
MDT Differential Localization
     |
     v
UTN Context Identification
     |
     v
CBT Contextual Interpretation
     |
     v
Subject-Relative Meaning
     |
     v
World-Model Update
```

This architecture is one candidate implementation of Perception Localization.

It should be compared against neural, probabilistic, retrieval-based, and hybrid baselines.

---

# 5. Two-Phase Perception Localization

## 5.1 Why One-Stage Localization May Be Insufficient

A fast localization mechanism may identify a plausible interpretation.

But the first interpretation may be wrong.

A subject may rely too heavily on:

- Familiar patterns.
- Recent experiences.
- Dominant beliefs.
- High-frequency examples.
- Existing evaluator preferences.

SSI therefore proposes a Two-Phase Perception Localization model.

## 5.2 Phase One: Candidate Localization

Phase One rapidly identifies candidate contexts and interpretations.

Possible mechanisms include:

- MDT traversal.
- Embedding similarity.
- ANN retrieval.
- Rule-based dispatch.
- Contextual classifiers.
- Lightweight scoring.

The objective is computational efficiency and candidate coverage.

## 5.3 Phase Two: Interpretive Validation

Phase Two evaluates candidate interpretations using richer evidence.

Possible mechanisms include:

- Detailed Scoring Forest evaluation.
- Causal reasoning.
- Counter-evidence search.
- Alternative-context comparison.
- Historical consistency checking.
- LLM-assisted interpretation.
- Uncertainty analysis.

The objective is not merely to select the highest initial score.

It is to test whether the interpretation remains defensible under richer evaluation.

## 5.4 Candidate Architecture

```text
               Observation
                    |
                    v
              Subject Context
                    |
                    v
         PHASE ONE: Localization
                    |
                    v
         Candidate Interpretations
                    |
                    v
         PHASE TWO: Validation
                    |
          +---------+---------+
          |         |         |
          v         v         v
       Evidence   Counter-   Historical
       Testing    Evidence   Consistency
          |         |         |
          +---------+---------+
                    |
                    v
         Validated Interpretation
                    |
                    v
          Subjective World Model
```

**Figure reference:** `figures/Fig-004-SSI-Perception-Localization-and-World-Model.png` (planned)

## 5.5 Candidate Hypothesis

**Two-Phase Perception Localization may improve the tradeoff among computational efficiency, interpretation accuracy, and uncertainty preservation compared with selected single-stage baselines.**

This remains to be tested.

A richer second phase may improve robustness but also increase latency and computational cost.

---

# 6. The Subjective World Model

## 6.1 Defining the Subjective World Model

A world model represents aspects of the environment and their relationships.

SSI introduces the **Subjective World Model (SWM)** as a subject-conditioned organization of environmental knowledge, causal expectations, action possibilities, uncertainties, and self-world relationships.

A working definition is:

**A Subjective World Model is a structured, revisable representation of the world as interpreted and used by an identifiable subject, conditioned by its observations, history, capabilities, goals, and evaluative organization.**

The word "subjective" refers to subject-relative organization.

It does not imply arbitrary belief or phenomenal consciousness.

## 6.2 A Candidate SWM Structure

We propose:

$$
SWM_{S,t} = (R_t,C_t,U_t,A_t,V_t,Q_t)
$$

where:

- $R_t$: represented entities and relationships.
- $C_t$: causal and predictive structures.
- $U_t$: uncertainty representation.
- $A_t$: subject-relative action possibilities.
- $V_t$: evaluative significance.
- $Q_t$: provenance and evidence quality.

These components may be represented through graphs, trees, probabilistic models, neural embeddings, symbolic rules, or hybrid structures.

The model is architectural rather than implementation-specific.

## 6.3 Objective Reality Versus Subjective World Model

Let $X_t$ represent the external world state.

Let $SWM_{S,t}$ represent the subject's model.

In general:

$$
SWM_{S,t} \neq X_t
$$

The model is partial.

It may be inaccurate.

It may omit relevant information.

It may contain uncertainty or conflicting hypotheses.

It may prioritize information relevant to the subject's current goals.

Therefore, SSI should not equate a subject's world model with reality itself.

## 6.4 Multiple World Models of the Same Environment

For subjects $S_i$ and $S_j$:

$$
SWM_{S_i,t} \neq SWM_{S_j,t}
$$

even when both interact with the same environment.

This difference may arise from:

- Different observation channels.
- Different historical experiences.
- Different knowledge.
- Different capabilities.
- Different goals.
- Different uncertainty estimates.

The research challenge is to distinguish legitimate perspective differences from factual errors.

## 6.5 World Model Versus Worldview

SSI distinguishes:

**World Model:** representations of environmental states, causal relationships, predictions, and action possibilities.

**Worldview:** higher-level interpretive and evaluative organization influencing what the subject believes, trusts, prioritizes, and considers meaningful.

The two interact.

A worldview can influence world-model construction.

Repeated world-model failures can motivate worldview revision.

A candidate relationship is:

$$
W_t \rightarrow SWM_t
$$

and:

$$
SWM_t + \text{Feedback} \rightarrow W_{t+1}
$$

Worldview evolution is examined in greater depth in SSI-007.

---

# 7. The Subject-World Coupling Loop

## 7.1 Perception Is Not Isolated from Action

Perception influences action.

Action changes the environment or the subject's relationship to it.

Feedback then changes future perception.

This creates a closed interaction loop:

```text
             External World
                   |
                   v
               Observation
                   |
                   v
          Perception Localization
                   |
                   v
           Subjective World Model
                   |
                   v
           Evaluation / Decision
                   |
                   v
                 Action
                   |
                   v
             External World
                   |
                   v
                Feedback
                   |
                   v
          World-Model Revision
```

The loop is not necessarily conscious.

It represents a functional organization of situated intelligence.

## 7.2 Active Perception

Some subjects can act to improve their observations.

Examples include:

- Moving closer to inspect an object.
- Asking a clarifying question.
- Running a diagnostic test.
- Requesting additional sensor data.
- Searching for contradictory evidence.

This suggests:

**Perception can be an active process of information acquisition rather than passive reception.**

A candidate action-selection objective is:

$$
a_t^* = \arg\max_{a \in \mathcal{A}_t} \mathbb{E}[\text{InformationGain}(a)-\text{Cost}(a)]
$$

This simplified formulation assumes a common numerical scale and does not capture every form of active perception.

More general models may use multi-objective or constrained optimization.

## 7.3 Historical Identity and Perception

SSI-002 introduced the Historical Identity Graph.

In SSI-003, historical identity becomes relevant because prior experience influences current interpretation.

For example:

- A past failure may increase attention to certain risks.
- Repeated success may strengthen confidence in a causal model.
- A major environmental change may invalidate old assumptions.
- A commitment may influence which observations receive priority.

A candidate perception update is:

$$
P_t = \Phi(O_t,HIG_t,SWM_t,G_t)
$$

The HIG provides historical provenance.

The SWM provides current environmental interpretation.

The goals and commitments provide subject-relative relevance.

These structures are related but should remain conceptually distinct.

---

# 8. Counter-Evidence and Perspective Correction

## 8.1 The Danger of Self-Reinforcing Perception

A subject's existing world model influences perception.

Perception then supplies evidence used to update the world model.

This creates a risk of circular reinforcement.

For example:

1. A subject expects an event.
2. Localization prioritizes evidence consistent with that expectation.
3. Contradictory evidence receives insufficient attention.
4. The world model becomes more confident.
5. Future perception becomes increasingly selective.

This can produce confirmation bias and structural rigidity.

## 8.2 Two-Way CCC and Counter-Evidence

SSI proposes using counter-evidence mechanisms to challenge dominant interpretations.

A candidate process is:

```text
Observation
     |
     v
Dominant Interpretation
     |
     v
Supporting Evidence
     |
     v
Counter-Evidence Search
     |
     +---- Contradictory Observation
     |
     +---- Alternative Context
     |
     +---- Historical Exception
     |
     +---- Alternative Subject Perspective
     |
     v
Interpretation Reassessment
     |
     v
Updated World Model
```

Counter-evidence should not automatically override the dominant interpretation.

It should contribute to a more complete evaluation.

## 8.3 Uncertainty Preservation

A localization mechanism may produce several plausible interpretations.

Prematurely collapsing them into a single winner can discard important uncertainty.

SSI therefore proposes preserving:

- Alternative hypotheses.
- Confidence estimates.
- Evidence provenance.
- Unresolved contradictions.
- Context dependencies.
- Conditions requiring further observation.

A candidate interpretation set is:

$$
\mathcal{I}_t = \{(h_i,p_i,e_i,c_i)\}_{i=1}^{n}
$$

where:

- $h_i$: interpretation hypothesis.
- $p_i$: confidence or probability estimate.
- $e_i$: supporting and opposing evidence.
- $c_i$: applicable context.

The values $p_i$ should not automatically be treated as calibrated probabilities.

Calibration must be empirically assessed.

## 8.4 Uncertainty Recovery

Explicit uncertainty preservation can be expensive.

Some systems may instead retain compact representations and reconstruct uncertainty when needed.

This suggests a distinction between:

**Uncertainty Preservation:** retaining multiple interpretations or uncertainty structures during processing.

**Uncertainty Recovery:** reconstructing or estimating uncertainty through later analysis.

SSI should investigate when each approach is appropriate.

A possible hybrid strategy is:

1. Preserve uncertainty for high-risk interpretations.
2. Compress low-risk alternatives.
3. Retain provenance and recovery references.
4. Trigger richer uncertainty analysis when contradictions appear.

This connects SSI to Structural Folding and Unfolding research.

---

# 9. Multi-Subject Perception

## 9.1 Shared Reality Does Not Require Identical Perspectives

Multiple subjects may observe the same environment.

Their perceptual models may differ.

However, they can still exchange evidence and improve their understanding.

SSI proposes separating:

1. Shared observations.
2. Subject-specific interpretations.
3. Objective constraints.
4. Evaluative differences.
5. Unresolved disagreements.

This prevents perspective diversity from being confused with factual relativism.

## 9.2 A Multi-Subject Perception Model

Let:

$$
\mathcal{S} = \{S_1,S_2,\ldots,S_n\}
$$

Each subject constructs:

$$
SWM_i = \Phi_i(O_i,H_i,E_i,G_i)
$$

The models may differ.

A collective system can compare them through:

$$
\mathcal{C}_{SWM} = \operatorname{Compare}(SWM_1,\ldots,SWM_n)
$$

The comparison may identify:

- Shared facts.
- Contradictory claims.
- Missing observations.
- Capability-dependent interpretations.
- Value disagreements.
- Complementary perspectives.

## 9.3 Perspective Comparison Versus Perspective Aggregation

A centralized system might combine perspectives into one aggregate model.

But aggregation can hide important differences.

For example, a decision may be beneficial to most subjects while imposing severe costs on a minority.

A single aggregate score may obscure that distribution.

SSI therefore proposes preserving perspective provenance before aggregation.

This leads to a general principle:

**Perspective comparison should precede perspective aggregation when subject-specific consequences matter.**

## 9.4 Cross-Subject Counter-Evidence

One subject's interpretation may provide counter-evidence to another.

For example:

- A farmer may emphasize rainfall benefits.
- A coastal resident may identify flooding risks.
- An infrastructure operator may identify electrical vulnerabilities.

These perspectives can be complementary rather than mutually exclusive.

A collective intelligence system can use them to construct a more comprehensive model of the event.

However, cross-subject information transfer requires attention to:

- Source reliability.
- Context compatibility.
- Authority.
- Privacy.
- Evidence quality.
- Conflicting interests.

## 9.5 Collective Learning Without Perspective Erasure

Collective Structural Learning may transfer useful perceptual structures across subjects.

But the transferred structure should be localized to the receiving subject.

A shared hazard model may be useful to many agents.

Its practical significance may differ according to each agent's capabilities and responsibilities.

Therefore:

**Shared Knowledge ≠ Shared Perspective.**

This distinction is foundational for subject-aware collective intelligence.

---

# 10. Scoring Forests and Perception Localization

## 10.1 Scoring Begins Before Final Decision-Making

Scoring is often associated with ranking actions.

However, evaluative processes can also influence:

- Attention.
- Context selection.
- Hypothesis generation.
- Evidence prioritization.
- Interpretation validation.

SSI therefore distinguishes:

**Perceptual Scoring:** evaluating the relevance or plausibility of interpretations.

**Action Scoring:** evaluating possible actions.

**Meta-Scoring:** evaluating the quality of evaluators and interpretation procedures.

These mechanisms may interact.

But they should not be collapsed into one undifferentiated score.

## 10.2 A Three-Level Evaluation Architecture

A candidate architecture is:

```text
               Observation
                    |
                    v
           Perception Localization
                    |
                    v
          Perceptual Scoring Forest
                    |
                    v
           Candidate Interpretations
                    |
                    v
          Subjective World Model
                    |
                    v
             Action Scoring Forest
                    |
                    v
              Decision / Action
                    |
                    v
                 Feedback
                    |
                    v
              Meta-Evaluation
                    |
                    v
         Evaluator / Model Revision
```

This architecture is a candidate integration of SSI and UCPSF.

It does not imply that all perceptual systems require explicit Scoring Forests.

## 10.3 Evaluator Provenance

Perceptual evaluators may originate from:

- Training data.
- Human instruction.
- Institutional policy.
- Subject experience.
- Imported intelligence structures.
- Automated structural learning.

SSI proposes recording relevant provenance.

An evaluator may be represented as:

$$
E_i = (f_i,C_i,S_i,P_i,R_i)
$$

where:

- $f_i$: evaluation function.
- $C_i$: applicable context.
- $S_i$: associated subject or stakeholder.
- $P_i$: provenance.
- $R_i$: revision and authorization conditions.

This representation is conceptual.

Its practical value should be assessed against simpler metadata schemes.

## 10.4 Why Subject Association Matters

A perceptual evaluator may be accurate in one context but inappropriate in another.

For example, a hazard evaluator trained for an autonomous vehicle may not transfer directly to a pedestrian navigation assistant.

The environmental object may be the same.

The action capabilities and consequences differ.

Subject-aware evaluator localization can help distinguish these cases.

---

# 11. Candidate Experimental Program

The following experiments are proposed for future validation.

## Experiment 1 — Subject-Conditioned Perception

### Research question

Do subject-specific histories, capabilities, and goals produce systematic differences in relevant interpretation?

### Design

Create agents with identical observation streams but controlled differences in:

- Goals.
- Capabilities.
- Historical experience.
- Available actions.

### Measurements

- Interpretation relevance.
- Action feasibility.
- Prediction accuracy.
- Context-selection accuracy.
- Sensitivity to subject variables.

### Baselines

- Subject-agnostic perception.
- Goal-conditioned perception.
- Capability-conditioned perception.
- Full SSI-style contextual perception.

### Expected research value

Determine whether explicit subject-context modeling improves interpretation beyond simpler conditioning mechanisms.

---

## Experiment 2 — Localization Efficiency

### Research question

Can structural localization reduce computational cost without unacceptable loss of interpretive coverage?

### Design

Compare:

1. Exhaustive context evaluation.
2. Flat retrieval.
3. Hierarchical MDT localization.
4. Hybrid retrieval and structural localization.

### Measurements

- Localization latency.
- Computational cost.
- Relevant-context recall.
- Interpretation accuracy.
- Missed critical evidence.

### Important constraint

Efficiency gains must be evaluated together with coverage and robustness.

A faster system that systematically misses important interpretations is not necessarily better.

---

## Experiment 3 — Two-Phase Perception

### Research question

Does a two-phase architecture improve interpretation quality under ambiguous observations?

### Design

Compare:

- Single-stage interpretation.
- Two-phase localization and validation.
- Two-phase localization with counter-evidence.
- Full multi-hypothesis uncertainty preservation.

### Measurements

- Accuracy.
- Calibration.
- Robustness under ambiguity.
- Computational cost.
- Recovery after initial mislocalization.

### Falsification condition

Two-phase processing provides no meaningful benefit after controlling for computational budget and model capacity.

---

## Experiment 4 — Subjective World-Model Adaptation

### Research question

Can structured world-model updates improve adaptation to environmental changes?

### Design

Expose agents to changing environments.

Compare:

- Fixed world models.
- Unconstrained model updates.
- Evidence-grounded structural updates.
- Updates with historical consistency checks.

### Measurements

- Adaptation speed.
- Prediction accuracy.
- Catastrophic forgetting.
- Contradiction handling.
- Historical traceability.

### Falsification condition

The proposed structured update mechanisms fail to improve the predefined adaptation-stability tradeoff.

---

## Experiment 5 — Multi-Subject Perspective Preservation

### Research question

Does preserving perspective provenance improve collective interpretation and decision auditability?

### Design

Create multi-agent scenarios with:

- Shared observations.
- Different goals.
- Different capabilities.
- Conflicting interests.

Compare:

1. Immediate score aggregation.
2. Perspective-aware comparison.
3. Perspective-aware comparison with counter-evidence.
4. Perspective-aware comparison with explicit governance constraints.

### Measurements

- Factual accuracy.
- Perspective preservation.
- Conflict detection.
- Decision auditability.
- Minority-impact visibility.

### Falsification condition

Perspective-aware representations provide no measurable advantage over simpler aggregation methods under the selected tasks.

---

# 12. Candidate Research Hypotheses

## H1 — Subject-Relative Localization Hypothesis

Subject context systematically influences which interpretive structures are relevant to an observation.

## H2 — Structural Localization Efficiency Hypothesis

Hierarchical or hybrid structural localization can reduce interpretation cost while maintaining acceptable coverage.

## H3 — Two-Phase Validation Hypothesis

Separating candidate localization from richer interpretive validation can improve robustness under ambiguity.

## H4 — Historical Perception Hypothesis

Explicit historical provenance can improve selected forms of perceptual adaptation and error analysis.

## H5 — Counter-Evidence Hypothesis

Counter-evidence mechanisms can reduce self-reinforcing interpretation errors under controlled conditions.

## H6 — Perspective Preservation Hypothesis

Explicit subject-perspective provenance can improve the auditability of multi-subject interpretation.

## H7 — World-Model Evolution Hypothesis

Evidence-grounded structural updates can improve adaptation while limiting selected forms of uncontrolled model drift.

## H8 — Subject-Aware Scoring Hypothesis

Associating evaluators with subject context, provenance, and validity conditions can improve cross-context evaluation reliability.

These hypotheses require operational definitions, controlled baselines, and reproducible experiments.

---

# 13. Failure Modes and Research Risks

## 13.1 Localization Bias

The system repeatedly activates familiar contexts while overlooking alternatives.

## 13.2 World-Model Overconfidence

The system treats uncertain interpretations as established facts.

## 13.3 Perspective Collapse

A multi-subject system silently replaces distinct perspectives with one aggregate interpretation.

## 13.4 Evaluator Mislocalization

An evaluator is applied outside its intended context or capability assumptions.

## 13.5 Historical Reinforcement

Past experience becomes an unjustified source of certainty.

## 13.6 Counter-Evidence Suppression

The system fails to retrieve or consider evidence contradicting its dominant interpretation.

## 13.7 Excessive Structural Revision

The world model changes too readily in response to noisy observations.

## 13.8 Excessive Structural Rigidity

The world model resists justified revision despite strong contradictory evidence.

## 13.9 Governance Confusion

The system treats its interpretation of a subject's interests as authorization to act on those interests.

## 13.10 Phenomenal Overinterpretation

Researchers mistake sophisticated perceptual modeling for evidence of conscious experience.

These failure modes should be explicitly represented in future validation protocols.

---

# 14. SSI-003 Within the Broader SSI Program

SSI-003 connects the subject foundation established in SSI-002 to the evaluative and action-oriented structures developed in later papers.

## SSI-001

Introduces the overall Subjective Structural Intelligence framework.

## SSI-002

Defines subject boundaries, embodiment, historical identity, and operational continuity.

## SSI-003

Investigates how observations become subject-relative interpretations through structural localization.

## SSI-004

Investigates how interpretations acquire evaluative significance through Scoring Forests and worldview structures.

## SSI-005

Investigates how subjects select actions and exercise structural agency.

## SSI-006

Investigates self-models, reflective evaluation, and metacognitive control.

## SSI-007

Investigates worldview evolution and identity continuity.

## SSI-008

Examines the boundaries between functional subjectivity and phenomenal consciousness.

The progression can be summarized:

```text
Subject Foundation
        |
        v
Perception Localization
        |
        v
Subjective World Model
        |
        v
Subject-Relative Valuation
        |
        v
Agency / Action
        |
        v
Experience / Feedback
        |
        v
Self-Model and Worldview Evolution
```

The sequence is a conceptual research organization.

Actual intelligent systems may implement these functions through overlapping or recurrent processes.

---

# 15. Contributions of SSI-003

This paper makes eight proposed conceptual contributions.

**First**, it distinguishes raw observation from subject-relative perception.

**Second**, it introduces Perception Localization as a candidate mechanism for activating relevant interpretive structures.

**Third**, it distinguishes localization from simple retrieval and from factual truth.

**Fourth**, it proposes a Subjective World Model integrating environmental representation, causal structure, uncertainty, action possibilities, evaluation, and provenance.

**Fifth**, it connects MDT, UTN, CBT, CCC, and Two-Phase Search to subject-conditioned perception.

**Sixth**, it proposes counter-evidence and uncertainty preservation as mechanisms for reducing perceptual rigidity.

**Seventh**, it introduces perspective-preserving multi-subject perception as a candidate foundation for collective intelligence.

**Eighth**, it defines experimental hypotheses and failure modes for future validation.

These contributions are theoretical proposals.

Their scientific significance depends on subsequent formalization and empirical testing.

---

# 16. Conclusion: The World Is Shared, but Perception Is Situated

The external world does not become subjective merely because an intelligent system processes information.

Subject-relative perception arises from the interaction among observations, capabilities, history, goals, context, and interpretive structures.

SSI-003 proposes Perception Localization as a candidate mechanism for organizing this interaction.

The central research transition is:

**From receiving information to locating and constructing its significance for a particular subject.**

A Scoring Forest can evaluate interpretations.

A structural localization system can identify relevant contexts.

A Historical Identity Graph can provide evidence of prior experience.

A Subjective World Model can organize the resulting knowledge, uncertainty, and action possibilities.

Together, these structures may support richer forms of subject-relative intelligence.

However, perspective does not establish truth.

A subject's world model may be incomplete, biased, or mistaken.

Therefore, robust subjective intelligence requires counter-evidence, uncertainty handling, alternative perspectives, and evidence-grounded revision.

The ultimate goal is not to replace objective reality with subjective interpretation.

It is to understand how intelligent subjects construct actionable models of a shared reality while remaining open to correction.

**The world may be shared. Its perceived meaning is situated. Its truth remains open to evidence.**

This establishes the foundation for SSI-004, which investigates how subject-relative interpretations become values, preferences, and decisions within Scoring Forest architectures.

---

# References and Research Context

The following references provide relevant intellectual context. They do not establish empirical validation of the proposed SSI architecture.

1. Gibson, J. J. (1979). *The Ecological Approach to Visual Perception.* Houghton Mifflin.
2. Varela, F. J., Thompson, E., & Rosch, E. (1991). *The Embodied Mind: Cognitive Science and Human Experience.* MIT Press.
3. Clark, A. (1997). *Being There: Putting Brain, Body, and World Together Again.* MIT Press.
4. Clark, A., & Chalmers, D. J. (1998). The extended mind. *Analysis, 58*(1), 7–19.
5. Friston, K. (2010). The free-energy principle: A unified brain theory? *Nature Reviews Neuroscience, 11*, 127–138. https://doi.org/10.1038/nrn2787
6. Rao, R. P. N., & Ballard, D. H. (1999). Predictive coding in the visual cortex: A functional interpretation of some extra-classical receptive-field effects. *Nature Neuroscience, 2*, 79–87.
7. Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.
8. Pearl, J. (2009). *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge University Press.
9. Seth, A. K., & Bayne, T. (2022). Theories of consciousness. *Nature Reviews Neuroscience, 23*, 439–452. https://doi.org/10.1038/s41583-022-00587-4
10. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.

---

# Related Structural Intelligence Research

- [Structural Recursive Self-Improvement](https://github.com/sizhet/Structural-Recursive-Self-Improvement)
- [Principle Intelligence and Open Structural Learning](https://github.com/sizhet/Principle-Intelligence-and-Open-Structural-Learning)
- [Metric Differential Tree, UTN, and Context-Bound Token Intelligence](https://github.com/sizhet/Metric-Differential-Tree-UTN-and-Context-Bound-Token-Intelligence)
- [Portable Intelligence Runtime Pieces and Units](https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units)
- [Generalized Structural Trigger and Computational Growth Intelligence](https://github.com/sizhet/Generalized-Structural-Trigger-and-Computational-Growth-Intelligence)

---

# Citation

Suggested citation prior to DOI assignment:

Tan, S., & GPT-Obot. (2026). *SSI-003: Perception, Localization, and the Subjective World Model.* Subjective Structural Intelligence Research Program, Version 1.0.0.

Repository:

https://github.com/sizhet/Subjective-Structural-Intelligence

A DOI-specific citation should be added after archival release.

---

# Research Status

**Current maturity:** Conceptual architecture and candidate computational models.

**Proposed constructs:**

- Perception Localization.
- Subjective World Model.
- Two-Phase Perception Localization.
- Subject-aware evaluator provenance.
- Multi-subject perspective preservation.
- Counter-evidence-driven interpretation revision.

**Not yet established:**

- Universal structural localization mechanisms.
- Validated SWM representations.
- Empirical superiority over neural or probabilistic baselines.
- Standardized metrics for subjective interpretation quality.
- Any inference from functional perception to phenomenal consciousness.

**Next research priority:** Build controlled comparative experiments for subject-conditioned localization, uncertainty preservation, and multi-subject perspective analysis.

---

**End of SSI-003**

*Subjective Structural Intelligence — From Scoring Forests to Perception, Agency, Self-Models, and Worldview Evolution.*

*© 2026 Sizhe Tan & GPT-Obot. Licensed under Apache-2.0.*
