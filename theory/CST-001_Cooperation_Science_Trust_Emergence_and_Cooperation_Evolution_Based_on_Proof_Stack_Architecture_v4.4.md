# CST-001 — Cooperation Science: Trust Emergence and Cooperation Evolution Based on Proof Stack Architecture v4.4

**GnomonSystem Protocol Baseline v4.4**

**V4.4 · 2026-09-11 · GNOMON BASELINE V4.4**

---

## Abstract

The development of human civilization is, in essence, a process in which the scale of cooperation continually expands. Existing research, however, often explains cooperation separately from the perspectives of economics, sociology, law, organizational management, and computer science, and lacks a unified theoretical framework.

This paper proposes a new theory of Cooperation Science. It first establishes a Cooperation Loss Model: along the information flow “analog → digital → digital → analog,” there are four layers of flow loss—reality loss, sampling loss, transmission loss, and execution loss—plus interpretation loss, which cuts across every stage. The properties of these losses are fundamentally different: physical-layer losses (reality loss and sampling loss) cannot be eliminated, while transmission loss can be greatly reduced through engineering. The paper then proposes a Trust Emergence Model, redefining trust as a probabilistic judgment in which a subject predicts future behavior based on evidence and incentive structures, rather than as a social relationship or psychological state. On this basis, it proposes a Proof Stack. Through five axioms and seven theorems, it establishes a strict dependency hierarchy among time, events, subjects, content, authorization, relationships, and value, in which higher-level proof cannot replace lower-level proof. Finally, it proposes the Cooperation Scale Law, which states that sustainable cooperation scale is inversely proportional to cooperation entropy and that the essence of civilizational expansion is the continued growth of proof capability.

The source identifies “Sundial System” (GnomonSystem) as the formal name of this project.

This paper argues that a crucial intermediate layer in the chain of civilizational evolution has long been overlooked: proof infrastructure. Historically, this layer was successively served by religious authority, legal systems, and accounting and auditing. In the digital-civilization era, it must be served by cryptographic proof systems. GnomonSystem's seven-protocol architecture is the engineering implementation of the theoretical framework in this paper and forms a complete correspondence, from theory to engineering, with the Proof Stack.

This paper ultimately proposes a complete emergence chain of structural semantics: time → event → subject → proof → confidence → trust → cooperation → organization → institution → civilization. Each layer is the semantics of the preceding layer; civilization is the result of emergence across layers. GnomonSystem precisely covers the four layers from time through proof and provides an engineering foundation for the objective formation of confidence.

**Keywords:** Cooperation Science, Trust Emergence, Proof Stack, Cooperation Entropy, Digital Civilization, GnomonSystem

---

## Contents

1. Introduction
  1.1 A simple question
  1.2 From personal cooperation to civilizational cooperation
  1.3 Core proposition: the emergence chain of structural semantics
  1.4 Scope and method
2. Cooperation loss theory
  2.1 The information path of cooperation
  2.2 Cooperation loss model: four layers of flow loss and one cross-cutting dimension
  2.3 Comparing the properties of loss and engineering implications
  2.4 Preliminary definition of cooperation entropy
3. Trust emergence theory
  3.1 Limitations of traditional views
  3.2 Redefinition of trust
  3.3 The nature of trust
  3.4 Trust-formation chain and its critical intermediate layer
4. Axiomatic system of Cooperation Science
5. Proof Stack theory
  5.1 Why proof is more important than data
  5.2 Temporal Foundation Theorem
  5.3 Event Existence Theorem
  5.4 Subject Existence Theorem
  5.5 Content Integrity Theorem
  5.6 Authorization Theorem
  5.7 Relationship Theorem
  5.8 Value Attribution Theorem
6. Proof Irreversibility Theorem
7. Proof Completeness Theorem
8. Case studies
  8.1 Real-estate transaction
  8.2 Bank transfer
  8.3 Blockchain coverage boundary
  8.4 AI Agent governance
9. Cooperation entropy model
  9.1 Why entropy is needed
  9.2 Precise definition of cooperation entropy
  9.3 Essential role of the proof system
  9.4 Cooperation Scale Law
  9.5 Corollaries of the Cooperation Scale Law
10. Mathematical model of trust emergence
  10.1 Trust is not a variable
  10.2 Evidence set
  10.3 Trust function
  10.4 Trust entropy
  10.5 Trust Emergence Theorem
11. Civilizational expansion model
  11.1 Historical observation: three major reductions in cooperation entropy
  11.2 Civilizational expansion equation
  11.3 Civilizational evolution chain
12. Comparison with existing systems
  12.1 Blockchain
  12.2 Public Key Infrastructure (PKI)
  12.3 Decentralized Identity (DID)
  12.4 Zero Trust Architecture
  12.5 Comparison of system coverage
13. Engineering mapping of GnomonSystem
  13.1 Use cases
14. Theoretical limitations and falsifiability
  14.1 Limitations
  14.2 Falsifiability
  14.3 Future research directions
References

---

## 1. Introduction

### 1.1 A simple question

Suppose Zhang lends Li 100 yuan. Three months later, Li says, “I have already repaid it.” Zhang says, “You never repaid me.” Which one is right? We cannot know from the claims alone.

The parties then look for evidence: transfer records, a written IOU, chat messages, witness testimony, or surveillance footage. If none exists, the dispute may be impossible to resolve.

The problem need not arise from bad faith. It may arise because the facts cannot be proved. This reveals a basic principle of cooperation:

**Cooperation often fails not because of the behavior itself, but because proof capability is insufficient.**

This principle applies to personal lending as well as international trade, judicial decisions, corporate governance, and AI decision-making. A lack of proof capability is one fundamental cause of cooperation failure.

### 1.2 From personal cooperation to civilizational cooperation

The same problem appears in larger systems:

- Why do companies need audits? Shareholders cannot directly observe management's actions.
- Why do banks keep ledgers? Creditors need proof that assets exist and who owns them.
- Why do courts require evidence? Judges cannot directly revisit past events.
- Why do states maintain registries? The validity of property rights depends on trustworthy temporal records.
- Why does the Internet need protocols? Communication between heterogeneous systems requires trusted shared conventions.

These institutions appear very different, but they perform a common task: **reducing uncertainty in cooperation**. Each is a form of proof infrastructure.

This leads to a broader question: **How does large-scale cooperation become possible?** This paper seeks to answer it within a unified theoretical framework.

### 1.3 Core proposition: the emergence chain of structural semantics

**Terminology.** This paper uses structural semantics to mean objective, ontological emergence relations between layers. This differs from content semantics—the human-interpretable meaning of symbols in a linguistic system. L3 interpretation loss concerns ambiguity in content semantics; the emergence chain concerns ontological relations between layers. They operate at different levels.

> **Formal convention.** The notation $x \xrightarrow{\sigma} y$ means “$y$ is the structural semantics of $x$.” Within a given ontological hierarchy, the emergence of $y$ presupposes the existence of $x$, and $y$ cannot be reduced to a simple aggregation of $x$. For example, $Event \xrightarrow{\sigma} Subject$ means that no subject can be defined without events, while a subject is not merely an accumulation of events. This is a **one-way dependency**: $x$ can exist independently of $y$, but $y$ cannot exist independently of $x$. The relation is distinct from logical implication and causal necessity. Every arrow in the ten-layer chain follows this convention.

The central theory can be expressed as a complete emergence chain of structural semantics:

**Time → Event → Subject → Proof → Confidence → Trust → Cooperation → Organization → Institution → Civilization**

Each layer is the structural semantics of the preceding layer:

**Event is the structural semantics of temporal order.** Time alone does not prove that anything happened; an event gives time meaning.

**Subject is the structural semantics of an event.** An event needs attribution; a subject identifies the actor.

**Proof is the structural semantics of a subject.** A subject's claim alone does not establish credibility; proof gives the subject verifiable attributes.

**Confidence results when subjects observe a subject's proofs.** Proof is objective in the sense that cryptographic proof is non-forgeable. Confidence is subjective because it depends on each observer's observation window. The same proof may produce different confidence levels for different observers.

**Trust is a semantic compression of a set of proofs.** A cognitive system compresses many discrete proofs into a single judgment. Trust cannot simply be created; it emerges from sufficient proof.

**Cooperation emerges naturally from proof and agreements on interests.** Trust provides the cognitive basis—the expectation that another party can perform. Agreements on interests provide behavioral motivation—each party expects to benefit. Together, they enable cooperation to occur naturally.

**Organization is the structural semantics of relations among subjects.** Stable patterns of cooperation become organizations.

**Institution is the structural semantics of relations among organizations.** Relations between organizations become structured by rules.

**Civilization is an emergence of structural semantics across layers.** It is the whole property that emerges when all layers accumulate. Disruption of any foundational layer can cause disturbances at the civilizational level.

**GnomonSystem's precise position in this chain:**

- Covers: time → event → subject → proof.
- Provides: an objective basis for confidence.
- Does not cover: layers above confidence, which emerge through subjects themselves.

GnomonSystem is infrastructure for the proof layer. It does not create trust or design cooperation. It makes proof reliable and allows the rest to emerge.

### 1.4 Scope and method

This paper combines deductive and inductive methods. Deductively, it derives seven theorems from five axioms to establish a formal system for Cooperation Science. Inductively, it uses historical cases to examine the theory's predictions and trace the evolution of proof capability through civilizational history.

The paper does not presuppose a particular cooperation scenario. Instead, it seeks the smallest complete set of problems shared by all cooperation scenarios. This follows a methodology similar to Shannon's information theory: rather than designing for a particular communication scenario, it seeks the common mathematical structure of all communication scenarios.

---

## 2. Cooperation Loss Theory

### 2.1 The information path of cooperation

All cooperation requires information transfer. Consider an agricultural transaction, from a farmer's sale of grain to the recipient's acceptance:

Physical grain  
↓ Weighing record (physical → digital)  
↓ Order system (digital propagation)  
↓ Logistics system (digital propagation)  
↓ Delivery acceptance (digital → physical)  
Physical receipt of goods

Throughout this process, information repeatedly moves between the physical and digital worlds, and each transition introduces loss. More generally, the information path of cooperation can be represented as:

$$\text{Physical reality} \xrightarrow{L0,L1} \text{Digitization} \xrightarrow{L2} \text{Digital transmission} \xrightarrow{L4} \text{Physical execution}$$

L3 interpretation loss cuts across the semantic understanding of all these stages; it is not represented as a separate process arrow.

### 2.2 Cooperation Loss Model: four layers of flow loss and one cross-cutting dimension

As cooperation information flows along analog → digital → digital → analog, it incurs **flow loss** at four stages: L0, L1, L2, and L4. In addition, there is a semantic loss that does not occupy a separate position in the flow but **cuts across all stages**: L3 interpretation loss. Flow loss asks where information is lost; interpretation loss asks whether the same information is understood consistently. Because they have different properties, they are modeled separately.

> **Relation to the three-stage model.** The three-stage model in the companion *Theoretical Framework*, §2.2, is a coarse-grained form of this model: Stage 1, “analog → digital (physical),” corresponds to L0 + L1; Stage 2, “digital → digital (human interference),” corresponds to L2; and Stage 3, “digital → analog (execution),” corresponds to L4. L3 interpretation loss is a cross-cutting dimension, implicit in the semantic-consistency requirements of each stage. The two are different granularities of the same model, not separate models.

#### Four layers of flow loss

**L0 Reality Loss**

Facts are permanently missing because observation conditions are insufficient. For example, if no camera is present when an accident occurs, some facts can never be recorded. If an oral commitment in a negotiation has no third-party witness, its content may be impossible to prove later.

The essence of reality loss is **observational blind spots and information asymmetry**. It is distinct from quantum uncertainty and from cognitive limitations; it is an objective gap in facts under any finite observation conditions. This loss forms a physical boundary for facts in cooperation and cannot be eliminated through technology.

**L1 Sampling Loss**

Loss occurs as physical reality is converted into digital form. A camera records at only 30 frames per second, audio is sampled at 16 kHz, and sensors have finite precision. Every sample is an approximation. Sampling loss is constrained by the Nyquist sampling theorem. It can theoretically be reduced by increasing the sampling rate, but never eliminated.

L0 and L1 together constitute **physical-layer loss**. They are constrained by physical law, cannot be completely eliminated, and can only be minimized under given technical conditions.

**L2 Transmission Loss**

Loss in the propagation of digital information includes active tampering, replay attacks, forged injections, transmission loss, storage corruption, clock drift, and semantic shifts during protocol conversion.

Unlike physical-layer loss, transmission loss is **controllable loss**. It mainly arises from human interference and system noise and can be greatly reduced, or even eliminated, through engineering. The core value of cryptographic proof systems is to remove the human-interference component of transmission loss and suppress system noise to an acceptable level.

**L4 Execution Loss**

Deviation occurs when digital outcomes are translated into physical actions. A system approves a payment, but an operator enters the wrong account. A contract specifies a delivery date, but logistics are delayed. An algorithm makes an optimal decision, but the execution environment has changed.

Execution loss is **structural loss**, arising from the inherent tension between digital intent and physical action. It can be reduced through more accurate execution and traceability, but not eliminated. Traceability is a core means of reducing execution loss: when execution outcomes can be reviewed and responsibility assigned, incentives for deviation are substantially reduced.

#### Cross-cutting dimension: interpretation loss

**L3 Interpretation Loss**

The same data may be understood differently. In a contract, “Party A may terminate” might be understood by Party A as an unconditional right and by Party B as subject to prerequisites. One party may interpret a timestamp in a system log as send time, while another interprets it as receive time.

Interpretation loss is **not an independent stage in the flow**. It is a semantic-consistency problem that **cuts across each layer from P2 through P5**. It can arise at any point after L2, so it is listed as a cross-cutting dimension rather than as a flow-loss layer parallel to L0, L1, L2, and L4. The L3 label is retained for convenience; it does not mean that interpretation loss occurs between L2 and L4 in the process. This dimension highlights that a proof system must protect not only the physical integrity of data but also establish shared semantic conventions.

### 2.3 Comparing loss types and engineering implications

| Loss | Type | Eliminability | Main source | Engineering response |
|---|---|---|---|---|
| L0 Reality Loss | Physical (flow) | Irreducible | Observational blind spots | Accept the boundary |
| L1 Sampling Loss | Physical (flow) | Irreducible | Physical law | Minimize |
| L2 Transmission Loss | Controllable (flow) | Can be greatly reduced | Human interference · system noise | Cryptographic proof |
| L4 Execution Loss | Structural (flow) | Can be reduced | Tension between digital and physical | Traceability |
| L3 Interpretation Loss | Semantic (cross-cutting) | Can be reduced | Semantic ambiguity | Standardized conventions |

L0/L1/L2/L4 are the four flow-loss layers along the analog → digital → digital → analog information flow. L3 interpretation loss cuts across all stages and is listed separately from the flow sequence.

This classification reveals the precise position of a proof system: **its primary field is L2 transmission loss; traceability can indirectly reduce L4 execution loss; and L0 and L1 form the epistemic boundary of every proof system.**

### 2.4 A preliminary definition of cooperation entropy

**Definition: Cooperation Entropy**, denoted $H_c$, is the overall level of uncertainty in a cooperation system.

$$H_c = \sum_{i=0}^{4} w_i \cdot L_i$$

Here $L_i$ is the loss level at layer $i$, and $w_i$ is the weight of that loss in the system's cooperation uncertainty. As loss increases, $H_c$ increases; as loss decreases, $H_c$ decreases. Cooperation capability is negatively correlated with cooperation entropy.

---

## 3. Trust Emergence Theory

### 3.1 Limitations of traditional views

Traditional theories often treat trust as a social relationship (Putnam, 1993) or a psychological state (Zucker, 1986). These definitions have two fundamental limitations. First, they are difficult to quantify and do not readily yield an operational engineering model. Second, they do not explain how trust can be established from zero between strangers: trust between two institutions that have never interacted cannot arise from an existing social relationship or psychological state.

### 3.2 Redefining trust

This paper proposes: **Trust is not a state; trust is a prediction.**

**Formal definition:**

$$Trust(A,B) = P(\text{Compliance} \mid E, I)$$

Where:

- $E = \{e_1, e_2, \ldots, e_n\}$ is the set of currently available evidence.
- $I$ is the incentive structure.
- Compliance is the future behavior of subject B in adhering to the cooperation agreement.

That is, subject A estimates the probability that subject B will comply with the cooperation agreement in the future. The estimate depends on both evidence quality and the alignment of the incentive structure.

Including the incentive structure is essential. Consider a subject with 100 records of perfect compliance. In the current case, however, breaching the agreement could yield 10 billion yuan, while the probability of detection is only 1%. Historical evidence alone is insufficient to predict future behavior because the expected net return from breach greatly exceeds the return from compliance. A trust function must therefore include incentives.

### 3.3 The nature of trust

From this definition, trust can be described as **an order of behavioral prediction that self-interested individuals establish naturally, given aligned interests and sufficient evidence**.

Three elements are indispensable:

- **Self-interest:** Trust rests on the expectation that the other party has an incentive to comply.
- **Aligned interests:** Incentives $I$ favor compliance rather than breach.
- **Sufficient evidence:** Evidence set $E$ provides enough historical information.

Trust is not designed into existence; it emerges naturally when these three conditions are jointly met. **A proof system does not create trust; it lowers the barriers to trust emergence.** By making evidence non-forgeable, it can make the cost of obtaining credible evidence approach zero and, in turn, make the cost of establishing trust approach zero.

### 3.4 The trust-formation chain and its critical intermediate layer

**Time → Event → Subject → [Proof] → Confidence → Trust → Cooperation**

GnomonSystem provides the [Proof] layer. Confidence results when subjects observe a subject's proofs. The same proof may produce different confidence levels for different observers because each has a different observation window. This is the theoretical basis for the Tianji Protocol's Window of Proof Observation (WPO) mechanism.

A critical intermediate layer in this chain has long been overlooked: **proof infrastructure**.

Evidence can be forged. A transfer screenshot can be edited with Photoshop, a contract can be altered after the fact, and a video can be AI-generated. Without proof infrastructure, the existence of evidence does not make it credible—the logical arrow from evidence to confidence is broken.

Only when proof infrastructure ensures evidence is **non-forgeable, tamper-evident, and temporally trustworthy** can evidence reliably give rise to confidence and then trust. The historical evolution of this intermediate layer is discussed in §11.

---

## 4. Axiomatic System for Cooperation Science

Every mature science requires an axiomatic system. Euclidean geometry has geometric axioms; Newtonian mechanics has laws of motion; information theory has a definition of entropy. Cooperation Science likewise requires a minimal, complete set of axioms to provide a rigorous logical basis for deriving theorems.

**Axiom 1: Cooperation Existence**

Every instance of cooperation involves at least two independent subjects: $A \neq B$. If there are not multiple independent subjects, there is no cooperation problem: a person talking to themself needs no trust, proof, or protocol. Cooperation is a multi-subject phenomenon.

**Axiom 2: Limited Cognition**

No subject can fully observe reality: $\text{Reality} \neq \text{Observation}$. This is the axiomatic basis of L0 and L1 loss. Different witnesses see different things in the same accident; the intentions behind a contract cannot be fully recorded when it is signed. An inherent gap exists between reality and cognition, and this gap is a source of cooperation loss.

**Axiom 3: Future Uncertainty**

Future behavior cannot be directly observed. Every instance of cooperation must rely on predictions about the future. Signing a contract is, in essence, predicting future performance rather than observing it. This axiom establishes why trust is necessarily a prediction problem and why evidence set $E$ and incentive structure $I$ jointly determine trust: predictions about the future depend on both historical evidence and current incentives.

**Axiom 4: Evidence Dependence**

Predictions must rely on evidence. Without evidence, no credible prediction can be formed. Banks do not lend merely because they like someone; they examine income, assets, and credit history. Governments do not issue business licenses solely on an applicant's promise; they verify supporting qualifications. **Evidence precedes trust.** This is a fundamental reason cooperation can extend beyond circles of personal acquaintance.

**Axiom 5: Proof Dependence**

Every proof depends on more foundational proofs; proof has a layered structure. To prove value attribution, one must first prove that a relationship exists. To prove a relationship, one must prove that authorization is valid. To prove authorization, one must prove subject identity. To prove subject identity, one must prove that an event occurred. To prove an event, one must have trustworthy temporal order. This axiom underlies the seven-layer proof theory that follows.

---

## 5. Proof Stack Theory

### 5.1 Why proof matters more than data

Modern systems process large volumes of data, but cooperation requires not merely data; it requires proof.

“I have paid” is data; it answers “what happened?” A bank statement is proof; it answers “why should what happened be believed?”

This distinction matters because data can be forged in high-entropy cooperation environments, while sound proof cannot. When cooperation extends beyond circles of personal acquaintance, crosses time zones and national borders, or uses AI to perform actions, forgeable data cannot support large-scale cooperation. Only verifiable proof can fill the trust gap.

### 5.2 Temporal Foundation Theorem

**Proposition:** All proofs ultimately depend on temporal proof.

**Proof:**

Consider any cooperation event. There are two states: S1 (valid) and S2 (invalid). Either state may exist at any given time. The only way to distinguish them is to establish the temporal order of state transitions.

Consider authorization. Let E1 be the granting of authorization and E2 its revocation. If the temporal order of E1 and E2 cannot be established, authorization status at any given time cannot be determined. The same applies to:

- Contract signing: determine whether signing occurred before or after a specified deadline.
- Asset transfer: establish the sequence of ownership changes and prevent double transfer.
- Identity changes: establish when a change took effect and determine whether a credential was valid.
- Relationship formation: establish the start of a relationship to determine the scope of rights and obligations.

**Counterexample:** Assume that temporal proof is unnecessary and that only content proof is needed. Then two contracts with identical contents but different signing times cannot be distinguished, double transfers cannot be detected, and the validity of an authorization revocation cannot be assessed. Content proof is incomplete without temporal order.

Therefore, all proof ultimately depends on time. **Q.E.D.**

**Corollary:** Temporal proof must occupy the base layer of the Proof Stack: $P_1 = \text{Temporal Proof}$.

**Historical illustration:** The earliest known written records of humanity (cuneiform tablets, circa 3000 BCE) were largely transaction ledgers and carried date marks. This suggests that even in early civilizations, people intuitively recognized temporal proof as the foundation of transaction proof.

### 5.3 Event Existence Theorem

**Proposition:** Temporal proof alone cannot prove that an event occurred; an independent event proof is required.

**Proof:**

Temporal proof can establish that “a valid temporal reference existed at time T.” It cannot establish that “a particular action occurred at time T.”

For example, anyone may obtain a time proof for midnight on January 1, 2025. It cannot prove that a particular party signed a particular contract at that time. If temporal proof could replace event proof, anyone could claim that any event occurred at any time.

An independent event proof must therefore include: time (anchored to a trusted temporal order), source (the subject that initiated the event), a content digest (a tamper-evident hash of the event content), and a signature (for non-repudiation).

$$P_2 = \text{Event Proof}$$

**Historical illustration:** The Code of Hammurabi, dating to around 1750 BCE, required transactions to be witnessed and inscribed on clay tablets. This was an early system of event proof: multiple witnesses and a physical record upgraded an event from an oral claim to a verifiable fact.

### 5.4 Subject Existence Theorem

**Proposition:** Event proof does not establish the identity of the subject; an independent subject proof is required.

**Proof:**

An event proof may establish that “an event occurred at a given time,” but not “who performed it.” If event proof includes a subject identifier, that identifier's validity must itself be verified through an independent subject-identity system. Otherwise, anyone could claim any identity in an event.

If subjects can make arbitrary identity claims, event proof becomes an anonymous assertion. It cannot support legal responsibility or prevent a Sybil attack, in which one subject impersonates multiple subjects.

$$P_3 = \text{Subject Proof}$$

**Historical illustration:** The Roman Empire developed detailed systems of citizenship registration and census-taking, beginning centuries BCE, because taxation, military service, and inheritance required a reliable foundation for subject identity. Without trustworthy subject identity, state-level cooperation cannot function.

### 5.5 Content Integrity Theorem

**Proposition:** Knowing who did something and when does not establish what they did; proof of content integrity is required.

**Proof:**

Suppose it is known that “Zhang signed a contract on January 1, 2025.” If either party can modify the contract afterward, the statement has no legal value: the act of signing alone does not establish a commitment to specific content.

Content must therefore be locked at the time of signing, and any later modification must be detectable. The core mechanism for content proof is a content hash:

$$\text{ContentHash} = H(\text{Content})$$

Any modification to the content can then be detected.

$$P_4 = \text{Content Proof}$$

**Historical illustration:** The notarial system that emerged in twelfth-century Europe is, in essence, a content-integrity mechanism. A notary witnesses the original state of content so that it cannot later be changed unilaterally. In the digital era, hash functions provide the same function mathematically, without requiring a trusted third party.

### 5.6 Authorization Theorem

**Proposition:** Subject identity and action content are insufficient to determine whether an action is valid; proof of authorization is required.

**Proof:**

Suppose Zhang signed a contract on behalf of a company. If Zhang's authority to sign cannot be established, the contract does not bind the company.

Missing authorization proof can make an action legally invalid and confuse responsibility: it becomes difficult to distinguish an authorized action from an overreach or to trace responsibility through multiple levels of delegation. Authorization proof is especially important as AI Agents perform more actions: every Agent action must be traceable to an authorized natural person who bears responsibility.

$$P_5 = \text{Authorization Proof}$$

**Historical illustration:** Feudalism (roughly the fifth through fifteenth centuries CE) was based on grants of authority: a king granted land to a lord, who in turn granted authority to a knight. Each layer of authorization had defined conditions and scope. This was an early large-scale system of hierarchical authorization proof.

### 5.7 Relationship Theorem

**Proposition:** The validity of authorization depends on the existence of a relationship between subjects; relationship proof is required.

**Proof:**

A board authorizes a CEO to sign a contract. If the CEO's employment relationship with the company cannot be established, the authorization is invalid. A relationship is a prerequisite for authorization: without a relationship there is no authorization, and without authorization there is no valid cooperative action.

Relationship proof must answer: Does a particular type of relationship exist between two subjects (employment, equity ownership, agency, partnership)? Was it valid at a particular time (when was it established and terminated)? What rights and obligations did it cover?

$$P_6 = \text{Relationship Proof}$$

**Historical illustration:** The invention of the corporation, including the first joint-stock companies in the early seventeenth century, was an innovation in relationship proof. Shares recorded ownership relationships, making large-scale cooperation among anonymous investors possible. Without trustworthy relationship proof, large commercial collaborations such as the Dutch East India Company could not have existed.

### 5.8 Value Attribution Theorem

**Proposition:** The ultimate purpose of cooperation is value distribution. Proof of value attribution depends on all six preceding layers.

**Proof:**

Suppose a company earns 10 million yuan and distributes it to its shareholders. The credibility of this cooperation requires:

- **P1:** Trustworthy temporal order (the earnings event occurred before the distribution).
- **P2:** Proof that the earnings and distribution events occurred.
- **P3:** Clear subject identities (who the shareholders are).
- **P4:** Content integrity (the allocation ratios and amounts were not altered).
- **P5:** Valid authorization (the board was authorized to approve the distribution plan).
- **P6:** An established relationship (the shareholders' ownership relationships with the company are genuine).

If any layer is missing, value-attribution proof is incomplete and the distribution can be challenged.

$$P_7 = \text{Yield Proof}$$

Yield proof occupies the top layer. It is the final expression of realized cooperative value and a fundamental incentive for subjects to continue cooperating. The division of labor described by Adam Smith and the distribution of value described by Marx find a common foundation in proof theory at this layer.

---

## 6. Proof Irreversibility Theorem

**Proposition:** Higher-level proof cannot substitute for lower-level proof.

**Proof:**

Assume that higher-level proof could substitute for lower-level proof, such that $P_k$ implies $P_j$ for $k > j$. Then establishing value proof would allow one to infer that a relationship exists ($P_7 \Rightarrow P_6$).

But claiming value does not establish a relationship: anyone may claim that value belongs to them without proving a relationship to its source. This contradicts Axiom 5 (Proof Dependence).

More generally, the set of facts proved by $P_k$ is a proper subset of the set of facts proved by $P_j$: higher-level proof has meaning only if lower-level proof is already established, while lower-level proof does not depend on higher-level proof. **Q.E.D.**

**Corollary:** The Proof Stack forms a strict partial order:

$$P_7 \succ P_6 \succ P_5 \succ P_4 \succ P_3 \succ P_2 \succ P_1$$

Here, $\succ$ means “depends on.” This partial order means the proof system must be built from the bottom up: no layer can be skipped or reversed. Temporal proof must precede event proof; event proof must precede subject-identity proof; and so on.

**Engineering implication:** This is the theoretical basis for the dependency structure of GnomonSystem's seven-protocol architecture. The Tianji Protocol depends on the Tianxuan Protocol, and the Tianxuan Protocol depends on the Tianshu Protocol. This is not an engineering convention; it is a logical necessity.

---

## 7. Proof Completeness Theorem

**Proposition:** If $P_1$ through $P_7$ all hold, cooperative facts reach the theoretical maximum level of provability in the digital world.

**Proof:**

According to Proof Stack Theory, $P_1$ through $P_7$ cover the complete dimensions of cooperative facts: time (when), event (what happened), subject (who), content (what content), authorization (whether it was authorized), relationship (the relationship between subjects), and value (who is entitled to the value).

At a given level of digitization, there is no eighth independent dimension that could further improve the provability of cooperative facts. Therefore, $P_1$ through $P_7$ form a complete set for proving cooperative facts in the digital world. **Q.E.D.**

**Independence argument (a non-circular supplement):**

This completeness does not follow only from the internal enumeration in Axiom 5; it also has independent support in the ontological structure of cooperation. Consider any cooperative action. The dimensions that can be objectively verified must involve the following ontological categories:

1. **Temporality:** A cooperative action necessarily occupies a position in time; an “action” without time cannot be verified.
2. **Eventhood:** Cooperation must appear as an identifiable event; without an event, a third party cannot confirm the cooperation.
3. **Agency:** Cooperation requires an actor; without a subject, responsibility cannot be attributed.
4. **Content:** Cooperation must have confirmable content; an “agreement” with no content cannot be verified.
5. **Authorization:** The normative validity of cooperative action depends on authorization; unauthorized action has no normative effect.
6. **Relationality:** Multi-subject cooperation presupposes relationships between subjects; without a relationship, there is no cooperative counterpart.
7. **Distribution:** The continuity of cooperation depends on value distribution; cooperation without distribution is not sustainable.

These seven categories form a **minimal complete ontological partition** of cooperative facts (mutually exclusive and collectively exhaustive).

Any conceivable “eighth independent dimension” can be reduced to one of the seven:

- **Intention** reduces to authorization (P5, which includes statements of intent) or interpretation loss (L3, ambiguity in the meaning of intent).
- **Outcome** reduces to event (P2, since an outcome is an event) or execution loss (L4).
- **Reputation** reduces to confidence, which is not a protocol layer but emerges through observers.

Therefore, the completeness of P1–P7 is ontologically necessary, not an accidental result of enumeration. **Q.E.D.**

**Epistemic boundary:** Proof completeness does not equal absolute truth. The Cooperation Loss Theory establishes that L0 reality loss and L1 sampling loss always exist. Therefore:

$$\text{Proof completeness} = \text{theoretical maximum credibility at a given level of digitization}$$

This is the epistemic boundary of Cooperation Science: **a proof system can establish that facts already digitized have not been altered in the digital layer; it cannot establish whether the physical world was completely sampled before digitization.**

This is not a defect but a clear recognition of boundaries. Knowing where the boundary lies is more credible than claiming to do everything.

---

## 8. Case Studies

### 8.1 Real-estate transaction

$$P_1(\text{when the contract was signed}) \rightarrow P_2(\text{the signing event}) \rightarrow P_3(\text{buyer and seller}) \rightarrow P_4(\text{contract content}) \rightarrow P_5(\text{authority to sell}) \rightarrow P_6(\text{property relationship}) \rightarrow P_7(\text{allocation of payment})$$

The real-estate transaction system is, in effect, an engineering implementation of a Proof Stack. Property registration provides P1–P2; notarization provides P4; lawyer attestation provides P3; mortgage registration provides P6; and the transfer process provides P7. Each step fills a layer of the Proof Stack.

When any layer is missing, transaction disputes can follow. Many disputes in China's real-estate market—such as a developer selling the same unit more than once, unclear property rights, or contract disputes—are, in essence, caused by missing or invalid proof at one or more layers.

### 8.2 Bank transfer

$$P_1(\text{transfer time}) \rightarrow P_2(\text{transfer event}) \rightarrow P_3(\text{payer and recipient}) \rightarrow P_4(\text{amount and accounts}) \rightarrow P_5(\text{account control}) \rightarrow P_6(\text{account ownership relationship}) \rightarrow P_7(\text{change in value attribution})$$

A bank is, in essence, infrastructure for value proof. The SWIFT system provides proof mechanisms for P2–P4; KYC/AML provides mechanisms for P3; account systems provide mechanisms for P6; and clearing and settlement systems provide mechanisms for P7.

### 8.3 The coverage boundary of blockchain

Blockchain is effective at proving temporal order (block height), event occurrence (tamper-evident transaction records), and content integrity (Merkle-tree hash chains), covering P1–P4. It has fundamental limitations at P5–P7:

- **P5 Authorization:** A digital signature on a blockchain proves possession of a private key; it does not prove that the key holder is authorized to represent an organization.
- **P6 Relationship:** An on-chain address does not natively express relationships between subjects in the physical world.
- **P7 Value:** An on-chain asset transfer does not prove that the transfer conforms to real-world rights and obligations.

This helps explain why blockchain can be complete in purely digital-asset domains such as Bitcoin, yet continues to face P5–P7 gaps in scenarios involving deep interaction with the physical world, such as DeFi tied to real-world assets or on-chain contracts with legal effect.

### 8.4 AI Agent governance

As AI Agents begin to perform high-value actions on behalf of people—financial transactions, medical decisions, and signing legal documents—a fundamental question arises: **When an AI makes a bad decision, where does responsibility lie?**

This is a cooperation problem involving P3–P5: Who is the subject—the AI or the authorizing human (P3)? What was the content of the action (P4)? Was the AI authorized to act within that scope (P5)?

The Proof Stack provides a clear framework for AI Agent governance: every Agent action must be traceable to an authorizing natural person (P5); the scope of authorization must be clearly recorded (P5); the action content must be tamper-evident (P4); and the action time must be trustworthy (P1–P2). This is a central governance problem of the digital-civilization era and one of the most urgent application areas for the Proof Stack.

---
## 9. Cooperation Entropy Model

### 9.1 Why entropy is needed

Compare two scenarios.

**Scenario A:** Zhang lends Li 100 yuan in person. They have known each other for 20 years. There are few key uncertainties: both identities are known, the amount is clear, the time is clear, and willingness to repay can be predicted from their history.

**Scenario B:** A multinational company pays another company 100 million US dollars. The transaction involves four countries, three currencies, two banks, more than ten contracts, and dozens of participants. Each participant's identity, authorization, content, and timing can be a source of uncertainty.

Scenario B is more complex. Complexity arises from accumulated uncertainty. A measurable indicator is therefore needed to describe this uncertainty: cooperation entropy.

### 9.2 A precise definition of cooperation entropy

For a cooperation system $S$ containing $n$ key provable facts, define:

$$H_c(S) = \sum_{i=1}^{n} U_i$$

where $U_i$ denotes the uncertainty of the $i$th fact.

Let $P_i^*$ denote the proof strength for the $i$th fact. Then:

$$U_i \approx \frac{1}{P_i^*}$$

Stronger proof means lower uncertainty. Therefore:

$$H_c \approx \sum_{i=1}^{n} \frac{1}{P_i^*}$$

**Boundary condition:** When the proof strength of any fact approaches zero ($P_i^* \rightarrow 0$), $H_c \rightarrow \infty$. The corresponding dimension of cooperation cannot be established, and the system falls back to a lower-dimensional form of cooperation, such as relying only on familiarity or authority. Some forms of cooperation cannot exist at all when the required proof capability is absent; this is not merely a reduction in efficiency.

> **Draft measurement protocol for cooperation entropy:** To make $H_c = \sum w_i L_i$ operational, the following proxy variables are proposed. They may be adapted to a particular setting:
>
> - **L0 Reality Loss:** The time/space proportion of observational blind spots, such as camera coverage or sensor density.
> - **L1 Sampling Loss:** The logarithm of the ratio between sampling rate and Nyquist frequency.
> - **L2 Transmission Loss:** Frequency of data-tampering events, success rate of replay attacks, and storage-integrity check failures.
> - **L3 Interpretation Loss:** Number of disputes caused by semantic ambiguity, such as contract-dispute rates.
> - **L4 Execution Loss:** Deviation rate between digital instructions and physical execution.
>
> Weights $w_i$ may be determined using the Delphi method or regression analysis based on historical cooperation failures. Until a general protocol is established, researchers may define scenario-specific weights but should disclose their measurement methods. The proposed Cooperation Scale Law, $S_c \propto 1/H_c$, can be tested for correlation using cross-industry data, such as international trade, software development, and supply chains.

### 9.3 The essential role of a proof system

The definition of cooperation entropy leads to the following conclusion: **the essential role of a proof system is not to record information, but to reduce entropy.**

More precisely, a proof system converts uncertainty that would otherwise depend on subjective judgment into verifiable, objective proof. It can reduce $U_i$ from near infinity (when there is no evidence) toward zero (when cryptographic proof is available).

This view explains why proof infrastructures from different eras—law, auditing, and cryptography—serve the same functional goal despite their very different forms.

### 9.4 Cooperation Scale Law

Let $S_c$ denote sustainable cooperation scale. This paper proposes:

$$S_c \propto \frac{1}{H_c}$$

In other words, the lower the cooperation entropy, the larger the sustainable scale of cooperation.

The proposed relationship can be examined against turning points in the history of cooperation:

| Form of cooperation | Proof mechanism | Change in cooperation entropy | Increase in cooperation scale |
|---|---|---|---|
| Early tribes | None (direct observation only) | Very high | Dozens of people |
| Agrarian civilization | Oral agreements · customs | High | Thousands of people |
| City-states | Written records · law | Medium-high | Tens of thousands |
| Empires | Currency · bureaucracy · codes | Medium | Millions |
| Modern nation-states | Accounting · auditing · corporate institutions | Medium-low | Tens of millions |
| Internet platforms | Protocols · digital signatures | Low | Billions |
| Digital civilization (proposed need) | Complete Proof Stack | Theoretical minimum | No fixed upper bound |

Each major reduction in cooperation entropy is associated with an order-of-magnitude increase in cooperation scale. The driving force of civilizational expansion is, in essence, the continued growth of proof capability.

### 9.5 Implications of the Cooperation Scale Law

**Implication 1:** If $H_c$ remains unchanged, cooperation scale has an upper limit. The historical “ceilings” of civilizations—the limit of hundreds of people in a tribe or millions in a feudal state—correspond to the maximum cooperation entropy their proof systems could support.

**Implication 2:** Digitization by itself does not reduce cooperation entropy. Only digitization combined with trustworthy proof infrastructure can do so. The Internet expanded information transmission but also expanded the spread of misinformation. Without proof infrastructure, digitization may increase cooperation entropy.

**Implication 3:** The Cooperation Scale Law predicts that a complete Proof Stack could allow cooperation in digital civilization to exceed current limits and support global cooperation with substantially fewer sources of friction.

---

## 10. Mathematical Model of Trust Emergence

### 10.1 Trust is not a variable

Traditional models may write $\\text{Trust} = x$. This is a category error: trust is not an object but a prediction outcome.

$$Trust(A,B) = P(B \\text{ will comply with the agreement in the future} \\mid E, I)$$

This is a conditional probability, not a state variable. Trust is not fixed; it changes with evidence set $E$ and incentive structure $I$.

### 10.2 Evidence set

$$E = {e_1, e_2, e_3, \\ldots, e_n}$$

Examples include identity proofs, bank statements, records of past performance, and contract-signing records. The quality of an evidence set depends on two dimensions: **quantity** ($|E|$) and **credibility** (the degree to which each item is non-forgeable).

**Key insight:** Both the quantity and credibility of evidence matter, but credibility is more fundamental. One hundred forgeable pieces of evidence are weaker than one cryptographic proof: the former only raise the cost of forgery, while the latter removes the possibility of forgery mathematically.

### 10.3 Trust function

$$T = f(E, I)$$

Here, $E$ is the evidence set and $I$ is the incentive structure.

> **Game-theoretic formalization of incentives:** Suppose subject B faces two pure strategies in cooperation: comply ($C$) or breach ($D$). Define the payoff matrix:

> 
> | B's strategy | Comply (C) | Breach (D) |
> |----|---:|---:|
> | Payoff | $U_C$ | $U_D$ |


> $U_D$ includes the direct gain from breach, $R_D$, and the cost of punishment, $P_D$ (such as legal accountability, reputational loss, or loss of future cooperation): $U_D = R_D - P_D \\cdot \\delta$, where $\\delta$ is the probability of detection. The incentive structure can be represented as $I = (U_C, U_D)$. Subject A's trust in B is:
>
> $$Trust(A,B) = P(B \\text{ chooses } C \\mid E, I)$$
>
> When $U_D > U_C$, a rational subject has an incentive to breach. A proof system raises $\\delta$ by making breach easier to detect and prove, thereby lowering $U_D$. Incentive design and proof systems are complementary: adjusting $I$ changes the payoff difference, while strengthening $E$ changes the probability of detection. Together, they can shift the Nash equilibrium toward compliance.

**About the incentive structure $I$:** It describes the relative expected payoffs of compliance and breach in the current setting. When the long-term payoff from compliance greatly exceeds the short-term payoff from breach, $I$ favors compliance. When breach offers a high payoff and little penalty, $I$ favors breach.

This model explains a historical pattern: why is trust easier to establish in repeated games than in one-time games? Repetition changes incentive structure $I$: breach can damage long-term returns, making compliance the rational choice.

More precisely, cooperation emerges naturally from proof and agreements on interests:

**Cooperation = Emergence (Proof Set × Agreement on Interests)**

An agreement on interests is an internally formed, mutually beneficial understanding between subjects, distinct from the exogenous incentive structure $I$. Trust is a cognitive state; cooperation is its behavioral expression. An agreement on interests bridges the two. GnomonSystem supplies proof; subjects form their own agreements on interests.

**More importantly,** this model shows that proof systems and incentive mechanisms complement rather than replace one another:

* A proof system increases the credibility of $E$, making breaches easier to detect and prove.
* Incentive mechanisms adjust $I$ so that the expected payoff from breach is lower than that from compliance.
* Both are needed to establish sustainable trust among large numbers of unfamiliar subjects.

### 10.4 Trust entropy

Let trust entropy $H_t$ denote uncertainty about subject B's future behavior:

$$T \\propto \\frac{1}{H_t}$$

Trust is inversely related to trust entropy. When evidence density is sufficiently high and incentives are well aligned, $H_t \\rightarrow 0$ and $T \\rightarrow 1$ (complete trust). When evidence is absent and incentives favor breach, $H_t \\rightarrow \\infty$ and $T \\rightarrow 0$ (complete distrust).

### 10.5 Trust Emergence Theorem

**Proposition:** Trust emerges naturally when evidence density increases and incentives become aligned.

**Formal statement:**

$$\\text{If } |E| \\rightarrow \\infty,\\quad \\text{Evidence Quality} \\rightarrow \\text{High},\\quad \\text{and } I \\rightarrow \\text{Aligned}$$
$$\\text{then } H_t \\downarrow,\\quad T \\uparrow$$

**Proof:** By Axiom 4 (Evidence Dependence), prediction must depend on evidence. As the evidence set approaches completeness and each item becomes non-forgeable, predictive uncertainty approaches zero, $H_t \\rightarrow 0$, and therefore $T \\rightarrow 1$. When incentives are also aligned, the expected payoff from breach is lower than that from compliance, further strengthening the trust prediction. **Q.E.D.**

> **Evidence-consistency condition:** The proof of this theorem implicitly assumes that evidence set $E$ contains no contradictions. If evidence conflicts—for example, two contracts with different contents share the same timestamp—adding more evidence does not necessarily reduce trust entropy. An **evidence-adjudication rule** is then needed, such as majority rule, temporal precedence, or authority weighting. Within the Proof Stack, lower-level proof (such as time) can resolve conflicts in higher-level proof—for example, temporal order may establish which contract was modified later. A complete Proof Stack therefore offers a mechanism for resolving contradictions. In a system with sound P1–P4, evidence consistency can be established.

**Important clarification:** The Trust Emergence Theorem describes natural emergence, not creation. A proof system does not create trust; it creates the conditions for trust to emerge. This distinction matters: GnomonSystem does not claim to make people trust one another. It lowers the cost of obtaining credible evidence, making trust easier to emerge naturally.

---

## 11. A Model of Civilizational Expansion

### 11.1 Historical observation: three major reductions in cooperation entropy

In human history, cooperation entropy has undergone three major reductions associated with turning points, each accompanied by an order-of-magnitude increase in cooperation scale:

**First reduction (circa 3500–3000 BCE): the invention of writing and ledgers**

The earliest uses of Mesopotamian cuneiform tablets were transaction records. Writing upgraded oral cooperation, which depended on memory and witnesses, to written proof that could be checked later. It freed information from the passage of time. The emergence of cities and the invention of writing occurred at nearly the same time; this was not coincidental—cooperation at city scale required written proof.

**First-and-a-half reduction: the emergence of currency (circa 600 BCE)**

Standardized gold and silver coins minted by the Kingdom of Lydia were the first **pure value-proof (P7)** instrument in human history. Currency did not depend on the personal credit of an issuer; it depended on the scarcity and divisibility of metal, enabling exchange between strangers. Currency substantially lowered the cost of identity verification in transactions (the parties did not need to know each other) and authorization verification (transactions required no individual permission), producing another significant reduction in cooperation entropy. Ancient empires such as Persia, Greece, and Rome could conduct large-scale taxation and trade across languages and ethnic groups because both currency systems and written law were in place.

**Second reduction (circa seventeenth to nineteenth centuries): maturation of corporate institutions, accounting, and auditing**

The joint-stock company standardized proof of ownership relationships (P6), enabling large-scale cooperation among anonymous investors. Double-entry bookkeeping (developed in fourteenth-century Italy and systematized by Pacioli in the fifteenth century) standardized value proof (P7), allowing companies to provide financial transparency to unfamiliar investors. One factor behind the Industrial Revolution's emergence in this period was the reduction in cooperation entropy that made large-scale capital aggregation possible.

**Third reduction (late twentieth century to the present): Internet protocols and cryptography**

TCP/IP greatly reduced transmission loss (L2) in digital communication, making cooperation across physical distance possible. RSA encryption (1977) and digital signatures (1980s) introduced mathematical non-forgeability. HTTPS brought these capabilities into everyday cooperation. The emergence of Internet platforms made cooperation among billions of people possible.

**Current state:** The third reduction is not yet complete. The Internet provides initial proof capability for P1–P4, but trustworthy foundational proof mechanisms for P5–P7 (authorization, relationships, and value) remain lacking in the digital world. This is a central cooperation problem facing digital civilization and the historical reason proposed here for implementing a full Proof Stack.

### 11.2 Civilizational expansion equation

Let $C_v$ denote civilization scale. Let ProofDensity denote proof density per unit of cooperation. This paper proposes:

$$C_v \\propto \\frac{\\text{ProofDensity}}{H_c}$$

**Civilizational expansion is not population growth; it is growth in proof capability.** Proof capability grows in two directions: higher ProofDensity (more cooperative facts are covered by proof systems) and lower $H_c$ (each proof becomes more credible).

### 11.3 The civilizational evolution chain

**Time → Event → Subject → Proof → Confidence → Trust → Cooperation → Organization → Institution → Civilization**

GnomonSystem provides the proof layer. Confidence is formed independently by subjects based on proof; cooperation is triggered jointly by proof and agreements on interests; and civilization emerges across the chain as structural semantics.

**Historical evolution of proof infrastructure:**

| Era | Proof infrastructure | Layers covered | Limitation |
|----|----|----|----|
| Early societies | None (direct observation) | None | Cooperation mainly among familiar people |
| Ancient civilizations | Temples · priesthood (religious authority) | P1–P2 (time · event) | Depended on the credibility of authority |
| Agrarian empires | Law · bureaucracy | P1–P4 | Depended on state enforcement |
| Commercial societies | Accounting · auditing · notarization | P1–P5 | Depended on institutional credibility |
| Internet era | Cryptography · protocols | P1–P4 (initially) | P5–P7 remain incomplete |
| Digital civilization (proposed need) | Complete Proof Stack | P1–P7 | To be built |

This evolution suggests a pattern: **whenever proof infrastructure shifts from dependence on authority (religious, state, or institutional) to dependence on mathematics, the credibility and scalability of cooperation increase by an order of magnitude.** Cryptographic proof is the latest and most complete implementation of this trend.

---

## 12. Comparison with Existing Systems

### 12.1 Blockchain

**Strengths:** Blockchain is effective at proving temporal order (block height provides a global sequence), event occurrence (transactions are tamper-evident), and content integrity (Merkle-tree hash chains). Coverage of P1–P4 is a core value of blockchain.

**Fundamental limitations:**

*P5 Authorization:* A digital signature on a blockchain proves possession of a private key, but not that the key holder is authorized to represent an organization or legal subject. A stolen private key can produce a valid on-chain signature that does not represent legitimate authorization.

*P6 Relationships:* On-chain addresses are anonymous and cannot natively express legal relationships in the physical world, such as equity ownership, employment, or agency. Decentralized identity (DID) attempts to address this, but still depends on an off-chain mechanism for recognizing relationships.

*P7 Value:* An on-chain token transfer is a fact, but it does not prove that the transfer is lawful under the real-world legal framework; it could be a legitimate transaction or money laundering. Lawful value attribution requires the full support of P3–P6.

**Summary:** Blockchain provides strong proof for P1–P4, but its design has historically left P5–P7 outside its scope. Satoshi Nakamoto's white paper defined Bitcoin as “peer-to-peer electronic cash,” avoiding the complexity of authorization and relationships. This is a design choice, not a defect, but it means blockchain is not a complete cooperation infrastructure.

### 12.2 Public Key Infrastructure (PKI)

**Strengths:** Identity authentication (certificates bind public keys to identities), digital-signature verification (content integrity), and partial authorization (permission extensions in certificates). PKI is a backbone of secure Internet communication.

**Fundamental limitations:**

PKI uses a centralized trust model: certificate authorities (CAs) are the source of trust. This means CA credibility depends on legal compliance and commercial reputation rather than mathematics. If a CA is compromised or corrupt, the trust system can fail. Historical CA attacks—including the 2011 compromise of DigiNotar, which led to the CA's bankruptcy—illustrate this vulnerability.

PKI also does not provide global temporal proof (P1): certificate validity periods use calendar time, not cryptographically anchored physical time.

### 12.3 Decentralized Identity (DID)

**Strengths:** Self-controlled identity without dependence on a centralized institution, verifiable credentials, and privacy protection through selective disclosure. DID is an important complement to P3.

**Fundamental limitations:**

DID addresses an identity *claim* (“who I am”) but does not automatically establish the *timing* of that claim (“when I held this identity”). An expired DID document can still be presented; without a trustworthy temporal foundation, a verifier cannot determine whether the identity remains valid.

DID also does not manage authorization (P5) or relationships (P6). Knowing who a DID holder is does not establish what permissions that holder has in a particular context.

### 12.4 Zero Trust Architecture

**Strengths:** Dynamic authentication and authorization (“never trust, always verify”), access control, and network security. Zero Trust has significant value in enterprise security.

**Fundamental limitations:**

Zero Trust is a security architecture pattern, not a proof system. It revalidates identity and permissions at each access (P3, P5), but its result is a real-time access decision rather than a cryptographic proof that can be audited later. More importantly, Zero Trust does not address value attribution (P7) or relationships between subjects (P6). It asks “who can access what?” rather than “what legal relationship exists between whom?”

### 12.5 Coverage comparison

| System | P1 Time | P2 Event | P3 Subject | P4 Content | P5 Authorization | P6 Relationship | P7 Value |
|----|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Blockchain | ✓ | ✓ | Partial | ✓ | — | — | — |
| PKI | — | — | ✓ | ✓ | Partial | — | — |
| DID | Partial | — | ✓ | Partial | — | — | — |
| Zero Trust | — | — | ✓ | ✓ | ✓ | — | — |
| Traditional legal systems | Partial | Partial | ✓ | ✓ | ✓ | ✓ | ✓ |
| **GnomonSystem** | **✓** | **✓** | **✓** | **✓** | **✓** | **✓** | **✓** |

**Note:** Traditional legal systems cover P1–P7 but depend on trusted authorities—courts, notaries, and audit institutions. They do not offer mathematical non-forgeability and are difficult to extend to digital cooperation that crosses national jurisdictions.

---

## 13. Engineering Mapping to GnomonSystem

GnomonSystem is presented as an engineering implementation of the Proof Stack theory in this paper. The correspondence between the seven protocols and the Proof Stack is intended as a layer-by-layer mapping, not merely an analogy.

| Proof layer | Gnomon protocol | English name | Engineering mapping | Core function |
|----|----|----|----|----|
| P1 Time Proof | Tianshu Protocol | Prime | Cryptographic anchoring of physical time | Traceable time source linked to UTC(NTSC) atomic clocks; non-forgeable and non-retroactive |
| P2 Event Proof | Tianxuan Protocol | Polaris | Event Existence Anchor (EEA) and causal tree | Cryptographic proof of event occurrence; tamper-evident causal chain |
| P3 Subject Proof | Tianji Protocol | Iris | Identity-attribute assertions and selective disclosure | Minimum-necessary identity disclosure; reuse of attributes across contexts |
| P4 Content Proof | Tianquan Protocol | Scroll | Content hashing and integrity checking | Tamper-evident content; provable time of existence |
| P5 Authorization Proof | Yuheng Protocol | Grant | Authorization chain and AI Agent accountability | Cryptographically verifiable authorization; traceable multi-level delegation |
| P6 Relationship Proof | Kaiyang Protocol | Bond | Proof of relationship existence | Establishment and termination of relationships between subjects; temporally non-deniable |
| P7 Yield Proof | Yaoguang Protocol | Yield | Proof of value attribution and distribution | Value flows to the entitled party as agreed; distribution is non-repudiable |

**The dependency structure of the seven protocols corresponds exactly to the partial order of the Proof Stack** and is constrained by the Proof Irreversibility Theorem. The Tianji Protocol depends on the Tianxuan Protocol, and the Tianxuan Protocol depends on the Tianshu Protocol. This is presented as a logical necessity, not an engineering convention.

The protocol names are drawn from the seven stars of the Big Dipper (Tianshu is also the company name and corresponds to the temporal origin at P1), evoking a guide for trust in the digital era. Each English protocol name is also intended to carry a specific semantic association: Prime (first, foundational), Polaris (a navigational reference), Iris (recognition), Scroll (content), Grant (authorization), Bond (relationship), and Yield (harvest or transfer of value).

### 13.1 Use cases

**Case 1: Cross-border trade cooperation**

The process may involve exporters, importers, banks, logistics companies, customs authorities, and insurers. Time, events, identities, content, authorization, relationships, and value all need to be verifiable. Mapping the Proof Stack to the seven Gnomon protocols can produce auditable cryptographic evidence at each layer and reduce dependence on centralized trust institutions such as SWIFT.

**Case 2: Internal corporate approval**

Multi-level approval (department manager → finance → legal → CEO) accumulates cooperation entropy. Each level is a proof node; a missing proof at any node can lead to later disputes. The Proof Stack explicitly records authorization (P5) and relationships (P6) at each approval step, making the approval chain cryptographically verifiable and clarifying responsibility.

**Case 3: AI Agent governance**

When AI Agents perform high-value actions on behalf of people, the Yuheng Protocol (P5 authorization) and Tianji Protocol (P3 subject) can be used together to trace each Agent action to the authorizing natural person, creating a complete accountability chain. This is one of the most urgent Proof Stack applications in the digital-civilization era.

---

## 14. Theoretical Limitations and Falsifiability

### 14.1 Limitations

**Epistemic boundary (irreducible):**

L0 and L1 loss always exist; proof completeness does not equal absolute truth. Any proof based on the Proof Stack can establish only the integrity, within the digital layer, of facts that have already been digitized. It cannot establish whether the physical world was fully sampled before digitization. This is a hard boundary of the theory, not a defect, but a clear recognition of what can be known.

**The predictive nature of trust (irreducible):**

Trust $T = f(E, I)$ is a conditional probability, not a deterministic judgment. Even with complete evidence and aligned incentives, a subject may still deviate. Extreme cases, such as self-destructive behavior, fall outside the theory's predictive scope.

**Technical dependence (mitigable):**

Implementation of the Proof Stack depends on the security of cryptographic algorithms (SM2/SM3/Ed25519), the trustworthiness of hardware security modules (HSMs), and the reliability of temporal infrastructure (atomic clocks, BeiDou, and NTP). Advances in quantum computing may threaten current cryptographic algorithms, so post-quantum migration paths should be planned in advance.

**Human factors and incentive design (core challenge):**

Even with a complete proof system, a subject may deviate from a cooperation agreement for extreme gain. This is why incentive structure $I$ matters in $T = f(E, I)$: proof systems address evidence, while incentive mechanisms address motivation. Both are necessary. Building a complete trusted-cooperation system requires joint design of proof systems and incentives. The Proof Stack is a necessary condition, not a sufficient one.

### 14.2 Falsifiability

This theory makes the following falsifiable predictions:

1. **Testing the Cooperation Scale Law:** If empirical data show no negative correlation between $S_c$ and $H_c$, the Cooperation Scale Law is invalid.
2. **Testing Proof Stack completeness:** If a category of large-scale cooperation can operate sustainably without depending on any layer from P1 to P7, the Proof Completeness Theorem is invalid.
3. **Testing trust emergence:** If, after deploying the Proof Stack, trust does not increase significantly under otherwise equivalent evidence-density and incentive conditions, the Trust Emergence Theorem is invalid.
4. **Testing historical predictions:** If the Cooperation Scale Law cannot explain historical turning points in cooperation scale, the theory's explanatory power is insufficient.

Empirical testing may include quantitative measurement of cooperation entropy across industries, comparison of trust costs before and after Proof Stack deployment, and analysis of correlations between proof capability and cooperation scale in historical data.

### 14.3 Future research directions

* **Quantitative measurement of cooperation entropy:** Develop an operational framework so the Cooperation Scale Law can be empirically tested.
* **Integrating the Proof Stack with game theory:** Analyze the effect of the Proof Stack on Nash equilibria in repeated-game settings.
* **Cross-domain Proof Stack standards:** Develop interoperability standards for Proof Stacks across different legal systems.
* **Joint optimization of proof systems and incentives:** Study how to design $E$ (proof strength) and $I$ (incentive structure) together to maximize trust emergence.
* **Integrating AI decision-making with the Proof Stack:** Study how AI decision processes can be made provable within P4–P5.
* **Post-quantum proof systems:** Study the cryptographic foundations of the Proof Stack in the quantum-computing era.

---

## References

 1. Shannon, C. E. (1948). “A Mathematical Theory of Communication.” *Bell System Technical Journal*, 27(3), 379–423.
 2. Williamson, O. E. (1975). *Markets and Hierarchies: Analysis and Antitrust Implications*. Free Press.
 3. Coase, R. H. (1937). “The Nature of the Firm.” *Economica*, 4(16), 386–405.
 4. Nakamoto, S. (2008). “Bitcoin: A Peer-to-Peer Electronic Cash System.” *Cryptography Mailing List*.
 5. Mills, D. L. (1991). “Internet Time Synchronization: The Network Time Protocol.” *IEEE Transactions on Communications*, 39(10), 1482–1493.
 6. Putnam, R. D. (1993). *Making Democracy Work: Civic Traditions in Modern Italy*. Princeton University Press.
 7. Zucker, L. G. (1986). “Production of Trust: Institutional Sources of Economic Structure.” *Research in Organizational Behavior*, 8, 53–111.
 8. Axelrod, R. (1984). *The Evolution of Cooperation*. Basic Books.
 9. North, D. C. (1990). *Institutions, Institutional Change and Economic Performance*. Cambridge University Press.
10. Diffie, W., & Hellman, M. (1976). “New Directions in Cryptography.” *IEEE Transactions on Information Theory*, 22(6), 644–654.
11. Lamport, L., Shostak, R., & Pease, M. (1982). “The Byzantine Generals Problem.” *ACM Transactions on Programming Languages and Systems*, 4(3), 382–401.
12. Szabo, N. (1997). “Formalizing and Securing Relationships on Public Networks.” *First Monday*, 2(9).
13. Harari, Y. N. (2011). *Sapiens: A Brief History of Humankind*. Harper.
14. RFC-SYS-001 (2026). *GnomonSystem Operating-System Design Outline*. Hangzhou Tianshu Temporal Technology Co., Ltd.
15. Tianshu Protocol (RFC-P1-001) (2026). *Tianshu Protocol Time-Source Specification*. Hangzhou Tianshu Temporal Technology Co., Ltd.
16. Tianxuan Protocol (RFC-P2-001) (2026). *Tianxuan Protocol Event-Existence Proof and Causal-Tree Specification*. Hangzhou Tianshu Temporal Technology Co., Ltd.


*GnomonSystem*
CST-001 · Collaborative Science: A Theory of Emergent Trust and Collaborative Evolution Based on Layered Proof Structures · GnomonSystem Protocol Baseline v4.4 · 
Tianshu Time-Source Technology Co., Ltd. · 2026-09-05 · GnomonSystem Protocol Baseline v4.4
