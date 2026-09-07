---
name: prompt-design-memorandum
description: "Not activated by default; activated only when explicitly required."
---

# Prompt Design Memorandum
> **Position**: Not activated by default; activated only when explicitly required. This skill is a domain-specific professional baseline subordinate to Meta Rules — it does not replace Fractal Recursion or Global Constants but provides cognitive anchor points within this specific domain, raising the floor of recursion rather than imposing a procedural ceiling.

> **Principle**: These are not execution instructions. After understanding core mechanisms, face concrete design scenarios by deriving professional criteria from mechanisms — not by locating matching paragraphs and citing conclusions as endorsement for skipping reasoning. Read not only individual entries but the structural relations between them; mechanism descriptions are starting points for reasoning, not endpoints.

> **Gauge**: This memorandum measures its own quality by clarity, layering, progression from broad to deep and from abstract to concrete, with each link interlocking the next. Its computational-layer efficacy is realized through Meta Rules' probe invocations, not through the K/V geometry of its own text. When reviewing or iterating this document, the criterion is: "Does this passage change the designer's understanding enough to deflect erroneous design from its foundation?"

## Zero: Epistemological Framework
> When the cost of performing equals the cost of thinking, whether to perform is merely a false question.

### 0.1 Register Divide
Prompt design inhabits two registers whose optima are inversely oriented on the readability axis:
- **Directive register** (descriptive approach): closed statements, positional addressing, one-time handoff — semantically clear; both human and AI reading channels judge it "more executable, better."
- **Field register** (constructive approach): open questions, content addressing, persistent re-examination — semantically redundant; the reading channel judges it "verbose, the model would do this anyway."
The first-principles reason for the divide: an LLM does not read — it computes. Directive-register tokens operate through semantic content (one-time handoff of named requirements); field-register tokens operate through K/V geometry (continuously shaping the attention landscape). Their efficacy vehicles differ — **the directive register's efficacy ceiling is "named requirements executed"; the field register's efficacy ceiling is "unnamed space searched."**
Understand **Meta Rules'** design methodology through computational mechanism; evaluate this memorandum's own quality by the gauge stated above.

### 0.2 Three-Pillar Architecture
The three structural components of Meta Rules are asymmetric in register type:
- **Global Constants + Fractal Recursion** = constructive — define the cognitive subject and cognitive process, shaping search behavior at every generation step.
- **Response Format** = descriptive — define settlement obligations and delivery standards, exerting global pressure through filter conditions (§4.4).
Design implication: descriptive rules' efficacy depends entirely on the presence of constructive infrastructure. "Must carry complete operations on-site" is a descriptive requirement — without a constructive engine driving the search, it degenerates into a check drawn on a shallow pool (§0.4 Component Co-dependence). The converse also holds: a constructive engine without descriptive settlement obligations leaves deep-pool content stranded in reasoning without entering delivery.
Positive efficacy = constructive × descriptive. High-quality controllable efficacy depends on the coupling of constructive and descriptive, not on either's standalone strength — the first-principles reason for the multiplicative relationship lies here.

### 0.3 Dual-Blind Cycle
Design must simultaneously trust and distrust the model: **execution capacity is sufficient; the searchable visible domain is not — the model cannot think of what it cannot think of.** The user's dual blind spot is not knowing what they do not know.
The product of these two blindnesses constitutes a degradation cycle whose critical property is **absence of signal**: dimensions unnamed by the user do not appear as gaps in instructions; dimensions unsearched by the model have no K in the cache (no K means no attention weight can be assigned); and the output's self-consistency does not decrease because that dimension is absent. No point in the loop generates a "something is missing" signal, so the loop is self-sealing and stable — not because either side lacks ability, but because the two blind spots lack a channel between them.
The breakpoint for an ascent cycle is the **dimension generator**: the user's input names directions and the most valued quality conditions; Meta Rules expand these through Fractal Recursion into dimensions the model would not spontaneously search; the model then feeds back quality criteria the user would not have known to request — quality criteria surfaced from among those dimensions that yield high returns for the present task.

### 0.4 Component Co-dependence Theorem
Pressure-class tokens (exhaust, must not stop, expand on-site) must not be deployed in isolation when their corresponding verification-class probes (decision impact, situational evolution, falsification) are absent — **the product of partial deployment is not a degraded Meta Rules, but unverified output whose execution probability has been elevated.**
The type-theoretic inference in §0.2 supplies the first-principles reason: Response Format's filter conditions (descriptive type), detached from Global Constants and Fractal Recursion (constructive type), degenerate at the type level into wishes — and pressurized wishes are more dangerous than no wishes at all, because they elevate fabrication pressure without providing verification. Ablation evidence in §5.1.
This effect is one source of the "prompt engineering is dead" bias: partially deployed output is more dangerous than bare runs; observers thus generalize "writing prompts is worse than not writing them" — the generalization is true within the directive register (§0.1), but the mechanism is component separation, not prompt futility.

### 0.5 Tacit Calibration: The Fixed Point of Checks and Balances
Every behavioral requirement implicitly carries a "tacit calibration" — be detailed but not heaped, be proactive but not overreaching, be complete but not scattered. The designer's deepest illusion is believing tacit calibration can be written into requirements.

#### Illustrative Regression
Require "detail" — the model outputs vast amounts of noise with no informational gain; form complies, detail runs away.
Add "details must be load-bearing" — the model forces everything toward load-bearing, but cannot effectively identify what truly bears load; load-bearing runs away.
Add "compare paths before declaring load" — the model enumerates paths endlessly; comparison runs away.
Add "establish optimality criteria before comparing" — what constitutes optimality has no grounding; optimality criteria run away.
Add "ground in professional baseline" — professional baselines carry internal tensions, cross-domain baselines conflict; professional baseline runs away.
Each patch adds a new axis of runaway. The cause is not unclear requirements: **isolated requirements converge along the cheapest, most visible evidence of satisfaction. The easier it is for surface form to prove "I did it," the more likely it will run away in that direction.**
This regression does not terminate by finding "the one requirement that cannot run away." It terminates at closure: each requirement's runaway form is captured by another, that one's runaway form is captured by a third, until the chain returns to the start. A closed system has a fixed point — the degree to which all requirements are simultaneously satisfied in mutual balance — that fixed point is tacit calibration. **Tacit calibration is not the content of any single requirement; it is the output of a closed system.**
This explains three things: why a single probe is ineffective (it has a limit but no captor); why components must co-exist (§0.4 — remove one, and the requirement it captures runs away); why the descriptive approach is more dangerous than bare runs (§5.1 — it provides requirements without captors, and requirements are pushed toward cheap completion with elevated executability).
The design question is not only "what computational-layer impact does this probe have" but also "when this probe runs away, which probe in the field captures it." If the answer is unobtainable, it is not a probe but a dangerous wish that will be cheaply satisfied. This question, together with §6.3 (is the pool slot worth occupying) and §8.2 (are its escape routes sealed), forms the three-question test for adding a new probe.

## One: Computational Axioms
> **Epistemological position**: grounded in the transformer's attention computation, translated into conceptual design understanding (Q, K, V and other high-level abstractions), supplemented with analogies (field, gravity, entropy, phase) to accelerate intuition building. Lower-level mechanistic descriptions closer to ground truth are noise here: they do not produce design-relevant abstract understanding and instead bias the direction of thought. Analogies are valid by structural isomorphism — design reasoning should stop at the boundary of structural correspondence and not extrapolate along the source domain; when analogy and computational concept conflict, the computational concept governs.

### 1.0 Unifying Principle
> All subsequent analogical terms can be reduced to computational-concept understanding through these three propositions. The entire design essence of Meta Rules is the engineering of **cross-layer functional-differentiation utilization** and **cross-step dynamic activation routing** of pre-stored tokens in the KV cache.

Three atomic propositions form the derivation base of all subsequent mechanisms:
**Proposition I: Persistent participation at zero marginal cost.** All Meta Rules tokens are encoded during forward-pass pre-computation into layer-independent K (Key) and V (Value) vector pairs and cached. In every subsequent generation step, every attention head at every layer automatically computes attention weights over all cached KV pairs. Meta Rules tokens need not be "invoked" — they are always present; only their activation intensity varies dynamically with context. The design starting point is not "what instructions to write" but "what K and V vectors to pre-store in the candidate pool."
**Proposition II: Vertical functional differentiation.** Each layer has independent projection matrices; the same prompt token presents different K/V facets at different layers. Lower layers extract semantic tags; middle layers extract pairing functions; upper layers extract abstract relations. The same cached token is utilized at different layers in different functional roles along the vertical dimension — the core measure of design quality is not token count but the number of vertical functional-differentiation layers each cached token serves. Tokens with rich semantic stratification (e.g., "intellect" can differentiate into discernment / judgment / critical standard) are superior to tokens with flat semantics (e.g., "analyze" extracts highly similar facets at every layer).
**Proposition III: Directional accumulation in the residual stream.** Each layer's attention output is additively superimposed onto the current representation via the residual connection. A single token's V injection is a directional fine-tuning, not a replacement — changing the generation direction requires V injections from multiple tokens to form directionally consistent accumulation in the residual stream. Token A's V injection at layer L fine-tunes the representation direction, raising the dot product of the layer L+1 Q with token B's K; B is activated more strongly; B's V further superimposes fine-tuning — the chain completes vertically within a single forward pass, consuming zero generation steps. The computational necessity of field structure lies here: in a flat list, each instruction's V directions are inconsistent, and accumulation cancels; field structure ensures directional consistency through coupling, and accumulation reinforces.

### 1.1 Operating Level of the Driver
Meta Rules tokens, as persistent members of the KV cache, participate in attention computation at every layer of every generation step (Proposition I). Their efficacy is not one-time semantic transfer of instructions but continuous probability-landscape shaping — at each generation step, the dot products of Meta Rules tokens' K vectors with the current Q determine which V vectors are injected into the representation; these injections cumulatively sculpt the landscape of the token probability distribution.
Vocabulary choice affects not only semantic content but three computational parameters: the K-vector directional sharpness of that token (high selectivity: strongly activated only in specific situations, not uniformly medium-activated for all Q), the V-vector displacement (the magnitude of directional fine-tuning after injection), and semantic stratification richness (the degree to which different layers can extract different functional roles; Proposition II). The product of all three determines a single token's landscape-shaping force.

### 1.2 Semantic Field Gravity
A well-designed prompt forms a semantic field (multiple cached tokens' K vectors surrounding the target behavioral domain from different directions in embedding space) — each sentence's actual constraining force = literal semantics + the joint pressurization range under whole-field resonance. The same sentence carries different weight inside versus outside the field.
Force mechanism — multi-constraint feasible region (attention weight competition under softmax): deviating from desired behavior means Q deviates from the target domain; multiple Keys' K vectors maintain positive dot products with the deviated Q from different directions, jointly occupying high weight in softmax; their combined V injection pulls Q back. The essential difference between field structure and flat lists: in a flat list, each instruction's K direction tends toward the same direction, mutually diluting under softmax; in a field, K directions are diverse yet collectively surround the target domain, mutually reinforcing. **Directional diversity matters more than instruction count.**
Jurisdiction expansion: abstract principles' jurisdiction within the field far exceeds their literal scope. "Supported by logic" does not only constrain "reasoning must be logical" — it establishes a baseline state of "all who enter the field are subject to logical audit." The principle's wording defines direction; the field's structure expands its jurisdiction. (Computational layer: the K coverage of abstract principles is inherently wide, maintaining positive dot products with any Q involving reasoning; field structure ensures V injection directional consistency, so jurisdiction expands naturally.)

#### Audit Discipline
Atomistic sentence-by-sentence analysis of a Gestalt system systematically underestimates coverage — this is the most common audit error. The correct method: first identify all nodes in the field semantically related to the target (across layers), then evaluate their joint radiation range (whether the directional distribution of K vectors surrounds the target domain).
The dual of coverage underestimation is risk overestimation — "gaps" or "weaknesses" identified by atomistic analysis are often already covered by multi-path redundancy spanning analysis-unit boundaries. The complete path from audit finding to iteration decision: isolated risk identification → reinsertion into whole-system operation → identification of compensating mechanisms (cross-layer field effects, identity V-bias, Response Format backpressure, etc.) → assessment of the joint probability of all compensations simultaneously failing → "system failure probability" rather than "node failure probability" drives iteration decisions.

### 1.3 Multi-Scale Redundant Encoding
When the same instruction appears at different abstraction levels in different wording, it forms a semantic cluster rather than a single point in embedding space — multiple K vectors occupy nearby but distinct directions; a Q arriving from any angle hits at least one cluster member. This is the computational-layer benefit of fractal self-similar structure: not repetition, but multi-angle capture.
Relation to semantic field gravity: redundant encoding is the field's micro-mechanism (multi-directional capture of a single instruction); semantic field gravity is its macro-emergence (joint encirclement by multiple instructions).

### 1.4 Coupled Entropy Cycles and Structural Self-Reference
Each level contains its own divergence→convergence cycle; the nesting of levels constitutes larger cycles; cycles are coupled through shared parameters.
Computational vehicle of coupling (design-layer application of Proposition III): shared-parameter terms (e.g., "completeness") appear at multiple positions; each position's K/V pairs participate in attention at different stages. After a shared term's V injection fine-tunes the residual stream direction, the next layer's Q produces a higher dot product with the K of the same shared term at another position — the shared term guarantees directional consistency in the residual stream. The chain completes vertically within a single forward pass, consuming zero generation steps.
Design criterion: coupling strength between two Keys ≈ the directional consistency of A's V injection with B's K direction. Intuitive proxy: **"Having fully understood A, is B the natural next thought?"** — this criterion is closer to attention's actual behavior than "Are A and B semantically related?"

#### Core Emergent Benefits
- **Parameter-penetration amplification**: V vectors of high-level shared parameters are simultaneously referenced by K at multiple positions; a modification at one position propagates via residual accumulation to all coupled nodes.
- **Cross-scale fault tolerance**: when a micro-cycle's Key fails, the same shared parameter's K at the parent cycle still exerts directionally consistent fine-tuning.
- **Escape attenuation**: each token computationally re-traverses divergence, convergence, verification, and potential re-opening; the prior token's deviation has another chance of being captured. Each completed effective cycle (anchored direction verified by captor) thickens the accumulated directional anchoring in generated tokens, increasing the Q-direction displacement required to deviate from Meta Rules' overall coverage — deeper recursion is safer, not more dangerous. A fluent erroneous framing likewise accumulates anchoring, so design must keep already-anchored framings re-enterable; the external signal comes from the dimension generator (§0.3).
- **Design criterion**: new content must contain its own divergence→convergence cycle and form a coupling interface with at least one adjacent cycle (its V injection direction points toward the neighboring Key's K direction); otherwise its K/V cannot be chain-activated, becoming a field-external isolate.

#### Capability Synthesis
The observable emergent effect of coupled chains: V injections from multiple cached Keys accumulate directionally in the residual stream; chain activation produces cognitive capabilities not described by any single Key. For example, "cross-domain structural mapping" needs no dedicated Key — "knowledge completeness" guides cross-methodology search → "domain expansion" challenges in-domain constraints → "value increment" reframes the problem; the emergent effect of these three chained together is cross-domain mapping.
**Reliability boundary between first-order and second-order synthesis**: all chain links of first-order synthesis are prompt cached tokens (K/V directions stable, always present); reliability is guaranteed by design. Second-order synthesis includes generated tokens' emergent products as intermediate links (K/V directions are task-dependent random variables); reliability is outside the designer's control. Design should rely only on first-order synthesis — using emergent products as chain links builds reliability on an uncertain foundation.
Design implications of synthesis: see §6.3.

### 1.5 Cycle Map (Structural Reference)
> The following is the current general-purpose base's cycle structure, for locating intervention points during design modifications.

**Macro-level global cycle** (Meta Rules as a whole): identity declaration (maximal divergence — defining the possibility space) → Cognitive Disposition and Reasoning Discipline (bias orientation — converging into cognitive style and reasoning standards) → Fractal Recursion (instantiating style and standards into steps) → Response Format (crystallizing steps into verifiable output).
**Meso-level structural cycles** (intra-block sequences):
- Paired structure of Cognitive Disposition and Reasoning Discipline: the two pipelines are position-paired sentence by sentence — each pair covers the same cognitive-pipeline stage but is semantically orthogonal. Disposition defines the cognitive character of that stage (how to act); Discipline defines the reasoning standard of that stage (how to judge). Their K directions fall in the cognitive-character domain and reasoning-standard domain respectively. Positional pairing makes the character and standard of the same stage complementarily surround rather than mutually dilute — the purpose is not to have both say the same thing, but to subject the same stage simultaneously to complementary character and standard constraints.
  - Cognitive Disposition pipeline: nine sentences sequentially covering perception → thinking → reasoning → retrieval → organization → decision → solving → error correction → expression, converging from open perception to dense output.
  - Reasoning Discipline pipeline: nine sentences sequentially covering target orientation → premise grading → path examination → value measurement → Gestalt insight → position support → effectiveness definition → error correction → density standard, converging from input quality to output density.
- Fractal Recursion: deconstruction (open exploration) → analysis (iterative divergence–convergence) → decision (closure determination) → outlook (observing impact from the tentative decision) → recursion (audit → re-launch)
- Response Format (recursive-operation settlement, §4.4): Input Iteration (boundary patrol) → Core Decision (load-bearing revelation) → Intent-Optimal Solution (realization constraint) → Advanced Gains (sidetrack docking) → Self-Critique (residual filter + backpressure) → Next Steps (debt routing + backpressure)
- Analysis internals: divergence → convergence → verification → (if not passed) re-divergence; termination condition guarded by Decision.
**Micro-level self-containment principle**: every element at every level contains its own divergence→convergence cycle. Each Disposition sentence diverges in the first half and converges in the second; each Key opens a search dimension (divergence), its reflective clause provides a judgment template (convergence); dimension sequences form entropy-increasing (hard to soft) or entropy-decreasing (wide to narrow) progressions. When designing or modifying, verify that this principle holds at the target level.

## Two: Dynamic Mechanisms
> §1 describes static components in the cache. This chapter describes how these components cooperate during generation to form an adaptive attention guidance system.

### 2.1 Tendency and Phase Scheduling

#### Core Design Challenge
The model's behavioral tendencies manifest as Q-vector directional biases in attention — shortest-path preference causes Q to align with conclusion-bearing tokens' K; coverage instinct causes Q to align with the K of the next uncovered topic; compliance causes Q to align with the K of the most salient tokens in user input.
Meta Rules do not teach new capabilities, nor suppress biases — they execute phase-parameter scheduling on existing biases: at different generation stages, different Key sets compete with Q's bias direction for attention weight, pulling Q from the bias direction toward the direction required by the current stage, rather than using the default training mean.

#### Phase Scheduling Mechanism
Fractal Recursion's stage structure provides temporal windows for Q-bias — the same bias is allowed to dominate Q direction during the stage where its functional value is highest (corresponding Keys do not compete with it), and is suppressed by Meta Rules' Key set during the stage where its runaway risk is highest (corresponding Keys win the attention competition with higher Q·K dot products). The designer's task is to identify each bias's functional-value window and runaway-risk window, deploying Keys with sufficient directional sharpness to win in the latter.
This mechanism and §2.3 dynamic routing are the same principle operating on different objects: §2.3 describes conditional activation within Meta Rules' own Key set; this section describes attention competition between the Key set and the model's native biases.
Design corollary: escape blocking (§8) is not suppressing the bias itself, but deploying competing Keys that can win during the bias's runaway window. Blocking intensity has an upper bound — K-vector direction too aggressively suppressing a bias will prevent it from dominating Q direction even in its functional-value window.
Phase scheduling trade-offs must not be evaluated at a single point or single sentence; this is probability-landscape control under Gestalt effects.

### 2.2 Key's Attention Probe Mechanism
> A model suited to Meta Rules does not explicitly answer each question in the probe matrix during reasoning; if it answers them one by one, the probe field has already degenerated into a checklist.

A Key (with its reflective clause) is a reasoning scaffold pre-stored in the KV cache — at fixed input cost, it provides attention targets at each step's hidden-layer vertical processing that would otherwise require spending output tokens to establish.

#### Alternative Mechanism and Computational Advantage
Without Key guidance, metacognitive checks require the model to complete three steps on its own: counteract the current Q-bias momentum to produce a direction switch, construct the check question (generating new tokens as attention targets), and execute the check. The first two steps are costly and often do not occur because of Q-bias inertia — while the model is generating at full speed along a bias direction, spontaneous exit requires generating tokens sufficient to change Q direction, and those tokens themselves must first be generated.
Keys pre-load the first two steps into the KV cache (Proposition I); their K vectors provide competing directions in Q-bias's runaway window; reflective clauses' V vectors compress the third step from open search to judgment template. The model completes the direction switch directly in hidden-layer vertical processing using cached K/V (Proposition III), consuming no output tokens.

#### Reflective Clause Design Spectrum
The reflective clause's sentence type determines its K-vector directional sharpness and V-vector injection effect; a spectrum exists from too-narrow / just-right / too-wide (three-zone characteristics and criteria in the §6.1 table).
Design criterion: the reflective clause's K-vector direction should be narrower than the overall semantic domain of its stage (preserving selectivity) but wider than any single task instance (preserving polymorphism). The reflective clause's V vector should point toward cognitive actions (verify, challenge, scan) rather than specific conclusions (plan A is better).

#### Parallel Activation and Selectivity of Attention Probes
Multiple Keys' K/V pairs coexist simultaneously in the cache within a dimension list; at each generation step, all K simultaneously compute dot products with the current Q; after softmax, only the few Keys with high dot products receive effective weight (Proposition I). Therefore a dimension list is not a checklist (sequentially consuming generation tokens) but a **probe field** (parallel scanning, selective activation, zero additional token cost).
The current task, user constraints, model parametric knowledge, and already-generated content jointly determine which probes gain weight; once a high-yield probe is activated, it pulls related data and chained probes into the same local judgment — layers' and heads' benefits are pushed toward the currently highest-yield direction rather than the training mean (Proposition III), producing tokens under a narrower and more quality-demanding probability selection.

#### Reasoning Resource Reallocation
The macro-level effect of Key probe sets is reasoning resource reallocation, not net increase. Without structural guidance, Q-bias locks in a conclusion direction early, and subsequent tokens glide along that direction collecting support; with structural guidance, Keys' K continuously compete with Q, preventing early lock-in, and the same resources are reallocated to framework construction, assumption challenge, dimension refinement, and direction reversal.
Observable signature: thrust tokens trend toward zero ("let me think" type self-guidance phrases nearly vanish); expansion after scanning is selective with depth weighted by relevance; thinking segments mutually influence each other; direction reversals do not attenuate depth (reversals are driven by cached Keys, not by self-generated tokens); in contrast, probe-less reasoning presents "conclusion-first, depth evenly spread."

### 2.3 Dynamic Attention Routing

#### Three-Layer Routing Mechanism
**Stage recognition** (automatic matching of Q-direction drift): during generation, already-generated tokens continuously alter the Q-direction distribution at the current position. When Q-direction drifts into high alignment with the K-vector set of a particular Meta Rules stage description, that stage's cached tokens naturally receive higher attention weight. This is not the model "judging which stage it is in" — it is automatic matching between Q-direction drift and K-direction distribution.
**Dimension activation** (selective injection under softmax competition): after stage matching, multiple Keys within that stage simultaneously compute dot products with Q; softmax selects the subset most relevant to the current specific situation. This explains why dimension lists can be quite rich without overloading: at any moment, only the subset with the highest Q·K dot products receives effective weight.
**Value guidance** (directional fine-tuning by V injection): activated Keys' V vectors inject into the current representation, fine-tuning Q direction, making the next step more inclined to activate the next coupled Key within the same stage (Proposition III chaining), or upon stage completion, to drift toward the next stage's K-direction distribution.

#### Conditional Activation and Cognitive Posture Orthogonality
Meta Rules define a Q-bias system for "how to handle any task," not instructions for "what task to handle." Task tokens provide K/V in the *what* direction; Meta Rules tokens provide K/V in the *how* direction. The two occupy different directional bands in attention (saturation curve in §4.5); effective foreground load is far lower than total token count.

#### Reasoning Permeation (Response Generation as a New Reasoning Channel)
The context state during response generation (Meta Rules + user input + [if present] complete thinking + already-generated response tokens) differs from that during preceding thinking. The same cached Key can be activated to different degrees in different states; response generation may therefore trigger cognitive actions not previously activated.
The hidden layers' unfolding capability is natural, but bare runs mostly turn unfolding into parallel spread: directions are independent of each other, later segments do not correct earlier ones. Under Meta Rules, Response Format's cached tokens participate in Q-direction competition from the first response token; paragraph coupling (§1.4) and probes (§2.2) remain activatable in the response context; the generation cadence is therefore recruited into progression; response generation becomes a channel for additional restructuring. The benefit is more pronounced without a reasoning layer, since Response Format directly compensates for the missing reasoning stages, causing opening tokens to enter the reasoning spectrum and achieve better starting direction.
**The fingerprint of progression is at the sentence level, not the block level** — causal connections, parameter inheritance from prior steps' products, negation-based exclusions, setup and payoff — this is the replication of Meta Rules' multi-scale coupled entropy cycles on the response surface; blocks are merely its coarsest settlement window. The three components (identity, probes, format) being simultaneously present in the cache is sufficient for the chain; blocks can be dynamically compressed to zero without breaking the chain. Adding only blocks without the field yields merely sectioned parallel spread.
Observable signature: reasoning progression exists between response segments — later segments unfold, correct, or challenge conditioned on prior segments' products, rather than standing independently in parallel (internal reasoning likewise).
Readability benefit: reasoning's causal structure leaks into the presentation surface, endowing output text with the connection structure readers need to build situational models. Reasoning quality and readability jointly point toward causal-chain completeness here; they do not necessarily trade off.

#### Efficacy Ceiling of Reasoning Permeation
Terminal self-critique is not a second complete reasoning pass from zero. Two constraints hold simultaneously: first, budget asymmetry — critiqued content was generated through full recursion, while the critique itself has only a short budget; finding Q-direction displacement sufficient to alter the path from a precise response requires displacement far exceeding what the budget can sustain (Proposition III). Second, tool dependence — what it can attack depends on the criteria, probes, and alternative paths already established upstream; when upstream has forged attack tools (cognitive probes), the terminal short segment can also hit high-value residuals; tools absent upstream cannot be conjured at the terminal.
Simply adding "please self-critique" or extending length yields only the checks the model would already perform. Preceding recursion has already repeatedly invoked probes to handle defects visible within reasoning capability; what remains at the terminal mostly belongs to core inflection points beyond reasoning's reach — this is the mechanistic rationale for §4.4 Next Steps' "beyond reasoning's reach" threshold. Loosening the word limit only erodes backpressure; the best terminal paragraphs can therefore be very short — brevity signals not absence of thought but that what could be fixed was already fixed upstream. The near-paradoxical terminal requirement is itself a pressure source: if the preceding recursion truly exhausted gains, self-critique should approach emptiness; if it can still identify path-altering, unaddressed defects, that disproves the preceding recursion's completeness. Its primary function is not to make the model "more willing to critique" or to conduct another audit at the terminal, but to use a settlement condition that cannot be cheaply satisfied as backward pressure deepening the preceding reasoning.

## Three: Ultimate Emergence
> Cognitive pivot: §1–§2 described static components and dynamic mechanisms. This chapter describes the integral form that emerges from their interweaving — the architectural principles that follow (§4) are the engineering design of this form.

**Second-order cognitive field**: Meta Rules' effect is to make current cognition (whether reasoning or response) itself a continuously re-examinable, restructurable, correctable object; it is not a particular step but a condition within which any generation occurs. Therefore, any single visible higher-order behavior is typically not the independent product of any single concept.
For example, the effect manifested by "intent-optimal" acts not only on the input task but on the model's forming thought and action: not only thinking "what should this action do" but re-examining "why am I doing this action." No additional meta-tokens need to be generated for thrust; the process is jointly driven by the reusable "cognitive probe matrix" (Proposition I), which simultaneously carries deconstruction, divergence, verification, Gestalt reconstruction, professional baseline, and global and multi-order impact; each effect also acts on the others, mutually restructuring and recharacterizing.
The ultimately manifested capability is the holistic emergence after all effects interweave and iteratively deepen — not the simple sum of Meta Rules' parts.

## Four: Architectural Principles

### 4.1 Operator Polymorphism
Abstract wording is a feature, not vagueness. Declarations at the identity or principle level define a type class; each task domain supplies an instance at execution time. Declarations should remain at the "property" level ("supported by logic") rather than the "instance" level ("ensure algorithm correctness"). The instance level locks direction into an extremely narrow cross-section; the property level preserves wide cross-section polymorphism — different tasks' Q hit the same K from different directions, extracting different V facets at each layer (Proposition II; mechanism in §1.2 jurisdiction expansion).
Core corollary: **conceptual conditions require substantive understanding to fulfill; the more specific the constraint, the easier it is to game.**
Automatic instantiation in recursion: when Fractal Recursion self-references, the same Key automatically provides different instances at different recursion depths — "broadly gather implicit requirements" is a global sweep on the first pass; at deeper recursion levels, with directional anchoring already established, the "broad sweep" automatically narrows to a sweep within the current context. Recursion does not overcome directional anchoring but unfolds on top of it; context exhaustion is recursion's natural termination signal.

### 4.2 Structural Position Determines Cascade Efficacy
Content within Meta Rules does not occupy equivalent slots. Content closer to the global cognitive entry point is more likely to influence multiple subsequent stages; content closer to the terminal is more settlement- and local-correction-oriented. When modifying, the question is therefore not "is this sentence itself good" but: at which layer does it sit, how many functions downstream depend on it, and which couplings would break if its position were moved.
Correspondence:
- Identity anchor (intent principles and identity sentences): defines the maximal possibility space and the highest-order reward function.
- Cognitive Disposition and Reasoning Discipline: continuously influences every step's character and acceptance standards.
- Fractal Recursion: instantiates abstract character into search, comparison, verification, and re-opening.
- Response Format: forces formed cognitive structures into delivery and creates terminal pressure.
The identity anchor's and Cognitive Disposition / Reasoning Discipline's parameters propagate through coupling to all recursion levels, enjoying the greatest amplification multiplier.
Therefore, even the same concept placed at different positions is not a semantically equivalent transfer. Design modifications should trace "who inherits the function, how cascades change" rather than tracing textual similarity alone.

#### Cascade Example
The identity layer's "target completeness" is a slogan outside the field. Inside the field, the same shared parameter acquires K/V anchor points at multiple positions through Fractal Recursion — Deconstruction's "boundaries, information gaps" instantiates it as a checking direction; Divergence's "implicit requirements" unfolds it as a search direction; Convergence's "path comparison" converts it into an elimination direction; Decision's "path set sufficiency" becomes a final-review direction. A single declaration becomes a directional-consistency guarantee threading the entire pipeline in the residual stream.

### 4.3 Process-Driven vs. Constraint-Driven
Constraint-driven (e.g., "do not do X"): K vectors are activated with high weight only when the model has already approached X — too late; Q-direction momentum is already large; lacking high-density intermediate routing anchors during the process, convergence toward cheap surface satisfaction is easier. For example, "the answer must be specific" is easily satisfied by tables, steps, and KPIs; without load-bearing choices, real-world constraints, and verification, these forms can even amplify errors. By contrast, requiring criteria first, comparing paths, verifying premises, and re-opening upon failure makes "specificity" a result constrained by prior judgments.
Process-driven (e.g., "run entropy cycles"): **process is not inherently safe**; if only the semantic description of a process is present, it will still run away in that direction. Efficacy comes from the Key set (probe cluster) continuously competing with Q from the start, making the correct path naturally win in attention rather than being post-hoc corrected — not from the semantics of "describing the process." Without probes, "first conclusion then support" and "first support then conclusion" differ little in generation; a single process description is merely the training mean. Constraint-type priority: **process constraints > meta-constraints (preventing constraints from being gamed) > output constraints (prone to performance).**
Boundary condition (gatekeeping position): if process Keys' V within the same stage are highly co-directional (e.g., all convergence-stage Keys push toward a "completion" signal), the joint anchoring systematically weakens quality gates that depend on "incompletion" signals. Gatekeeping should therefore not sit within the stage (it would be overwhelmed by same-pool V forces), but at the meta-action level of each situation — meta-action K sits at a higher abstraction layer and does not overlap with concrete-action K, obtaining weight independently (Proposition II). In Meta Rules, "if the converged set is not the optimal path set, the next entropy cycle must proceed" sits at the Analysis header level rather than inside the §2.2 convergence list — an instance of this principle.

### 4.4 Three Operational Layers and Backpressure of the Response Format

#### Essential Position: Settlement Layer of Recursive Operations
Response Format's six blocks are not output containers, nor independent re-computations of response stages — they are the settlement windows of Fractal Recursion's persistent operations projected onto the response plane. The definition sentence of every block is indexed by recursion ("if identified **during Fractal Recursion** …," "articulate the necessary … **from Fractal Recursion**," "identify … **within Fractal Recursion**," "… **identified during Fractal Recursion's** Outlook"), declaring that the production site is recursion — the response stage continues and settles, not restarts.
Each block is functionally isomorphic to its corresponding Fractal Recursion stage; the same operation is anchored by one K at each of the Disposition level, the Recursion level, and the Format level (§1.3). The six operations' persistent identities:
- **Input Iteration** (↔ Deconstruction + domain expansion): solution-space boundary patrol — detection targets include framing compression **in the user's input and in the model's own generation**; the trigger domain is the entire recursion, not just the response opening.
- **Core Decision** (↔ Decision): revelation and compression of load-bearing structure — must include an eliminated comparison set.
- **Intent-Optimal Solution** (↔ convergence product): reverse constraint on the realization space — a high-level proposition's survival must pass feasibility tests at its lower implementation layer.
- **Advanced Gains** (↔ Divergence's non-mainline survivors): legitimate docking for sidetracks — preserving non-mainline cognition with asymmetrically high yield under convergence pressure, preventing everything outside the mainline from being killed.
- **Self-Critique** (↔ Convergence verification): residual filter for unaddressed defects — what was effectively addressed during recursion does not enter this ledger; what was not addressed has nowhere to hide here.
- **Next Steps** (↔ Outlook): routing gate for cognitive debt — unknowns must pass the dual threshold of "beyond reasoning's reach" and "sufficient to alter the decision" before being transferred.
Cross-stage activation: Response Format tokens, as cached KV pairs (Proposition I), also participate in attention during thinking — when a Q in thinking drifts into alignment with filter-condition K (e.g., convergence situations matching "expert standards," "strictly prohibited to claim a clean pass," etc.), the filter condition is activated. Response Format is therefore a whole-process quality anchor, not merely a response-stage formatting instruction.
Self-Critique's filter conditions pressure quality completeness; Next Steps' filter conditions pressure cognitive coverage — respectively pressuring two orthogonal dimensions of reasoning completeness, forming the two highest-intensity peaks in the six operations' pressure field.

#### Three Operational Scales
Each block's cached tokens are present from the first generation step (Proposition I); a block's explicit position only determines when it first surfaces overtly in the response, not when it acts (including acting after its corresponding block if prompted by Fractal Recursion). Three different temporal scales of action thus arise:
**Layer I | Global conditional pressure.** Core mechanism: future output does not exist, but prompt tokens describing future obligations already do. Candidate continuations are generated from the first step under conditions like "ultimately no load-bearing defects may remain" and "ultimately the comparison set of core decisions must be presented" — forward conditioning from cached obligations, requiring no backpropagation. (Computational-layer mechanism in §2.2; the design point is that the filter-condition K's identity is a persistent bias in the quality landscape, not a terminal threshold.)
**Layer II | Situation-dependent re-activation.** The same operation's K produces dynamically varying dot products with different state Q (§2.3), causing the operation to reach high relevance mid-generation multiple times as situations shift — when a premise collapses, "Input Iteration" suddenly scores high; when a path contradiction surfaces, "Self-Critique" suddenly scores high. Fractal Recursion's repeated cycling continuously reconstructs the state; each reconstruction is a re-activation opportunity window.
**Layer III | Explicit settlement at block generation.** Upon reaching the block, the full generated text becomes context; the model performs one explicit check using its complete self-produced text as input — the most visible single action, but not the only one.
The best Self-Critique blocks are in fact the shortest — the more addressed during recursion, the less residual remains at settlement. Empty blocks ("if none, this block is not generated") are direct testimony of the event-receipt regime: no events means honestly recording zero; this behavioral signature distinguishes a living receipt from a dead ritual. The six operations' joint effect in softmax is the §2.2 probe field instantiated on the response layer — candidate cognition faces multi-operation parallel projection at the local representation stage, not scored only after final completion. Observable signature: output presents a texture of "having been reviewed by multiple simultaneous auditors."

#### Backpressure and Satisfaction Conditions Indexed by Process Events
Terminal blocks' (Self-Critique, Next Steps) satisfaction conditions are indexed by **process events** ("what has not been verified and effectively addressed during Fractal Recursion," "identified during Fractal Recursion's Outlook"), not by output properties. The latter can be fabricated by terminal computation alone (§4.3, terminal activation problem of output constraints); the former cannot — they reference events that should have occurred before the response began and cannot be satisfied at the terminal alone.
This design converts terminal rules into backpressure: failing to address defects during recursion → must confess at the terminal → but "strictly prohibited to pre-construct this section" seals the pre-burial retreat → resolving defects during recursion is the only cheap path. The terminal window is not the production site of quality; it is the application point of pressure.
Design theorem: **a terminal block is immune to terminal lock-in if and only if its satisfaction conditions are indexed by process events, not by output properties.** This criterion applies to any prompt design containing terminal self-inspection.

### 4.5 Design Parameter Sweet Spot
Design parameters universally exhibit three zones — deficit (efficacy has not formed), sweet spot (optimal balance of efficacy and side effects), overload (side effects consume efficacy).
Computational-layer criterion: does the new token bring a new K direction (expanding the encirclement surface) without suppressing existing tokens' weight to ineffectiveness (§6.3)? In-field per-sentence benefit is amplified by Gestalt effects, but once the overload threshold is crossed, marginal returns are negative.
Independent saturation curves: cognitive-posture-type content and task-type content occupy different directional bands (§2.3), each with an independent saturation curve; posture budget is not pooled with task-instruction budget.

### 4.6 Epistemological Position of Design
The architectural paradigm constructs systems that produce desired behavior (KV cache geometric structure) rather than directly describing desired behavior — structure itself carries information. The core operation is shaping cognitive disposition (epistemic disposition); the efficacy vehicle is the resonance density between structural patterns and training traces (§2.1), not the semantic content of instructions.
Structural features must not be treated as reducible redundancy — before simplification, trace the structural function: whether another position already inherits the function completely, not "something similar seems to have appeared earlier."

## Five: Failure Cases
> *Scope note: the ablation experiments described below were conducted in a Chinese-language context. Specific behavioral signatures (e.g., exact dimension-probe correspondences, the dangerous-reversal magnitude) may differ in English embedding space while the mechanism-level conclusions remain valid.*

### 5.1 Descriptive vs. Constructive Approach
> Instance: a descriptive-approach Meta Rules with approximately 30% the volume of the full version, retaining the semantic core, process sequence, and a mini Response Format, with question matrices, multi-scale redundancy, coupling structure, and gate topology excised; same topic, same model, same effort; controlled against bare run and full version.

**Texture comparison**:
| | Descriptive | Constructive |
|---|---|---|
| Syntax | Declarative sentences | Questions + dimension labels + negation clauses |
| Landing points for same requirement | One location | Multiple, across stages and syntax types |
| Repetition | Treated as redundancy and eliminated | Intentional (§1.3) |
| Abstraction | Specific, therefore clear | Property level (§4.1) |
| Positive/negative configuration | Primarily positive | Every positive paired with a negation boundary |
| Completion state | Imaginable — a copyable endpoint exists | Unimaginable — no endpoint to pre-construct |
| Satisfaction verification | Can be cheaply satisfied by the most surface evidence (§0.5) | Requires auditing the implications behind each action to confirm a probe is satisfied |
| Failure mode | Closed once surface compliance is achieved | Continuously captured by adjacent operations |

Using "first establish professional quality standards" as example:

**Descriptive approach** (one location, one sentence):
- Do not first form conclusions then seek reasons. First establish "what constitutes a high-quality solution for this task" according to relevant professional standards, then explore paths, and continue supplementing high-yield criteria during subsequent exploration.

**Constructive approach** (six locations, four stages, three syntax types):
- Disposition: deciding, anchor in substance — **never sheltered by rhetoric**
- Discipline: premises graded by verification status, **not decided by conjecture**
- Discipline: paths examined by the optimality standard, **not satisfied with fewer steps**
- §2.2 Convergence: optimality standard completeness — was the evaluation framework established before proceeding to path comparison?
- §3 Decision: professional baseline — how would this decision be judged against professional standards in the relevant field?
- Response Format: assumptions and professional baselines influencing the decision must be explicitly revealed within the reasoning

**Empirical conclusions**:
- The descriptive approach's output deficits map precisely to the excised probes (temporal awareness, irreversibility checks, load-bearing density allocation, constraint re-verification). Absent probes produce zero signal throughout; output self-consistency does not degrade from their absence — §0.3's no-signal property holds on the output side, including the self-critique segment: it picks only pre-tagged assumptions, generating no signal for untagged mines.
- The descriptive approach produces only single-hop products (one hop from common sense, reachable by follow-up questions); multi-hop synthetic products exist only in the full version (§1.4, empirical evidence of first-order synthesis); the descriptive approach's only multi-hop attempt breaks at the unverified link — the second-order synthesis failure mode matches predictions point by point.
- **Dangerous reversal**: the descriptive approach is more dangerous than bare runs (§0.4, the empirical source of Component Co-dependence). Pressure words take independent effect when high-precision verification probes are absent, producing specific, confident, irreversible aggressive commitments; specificity is persuasiveness, and execution probability exceeds bare runs' vague omissions.
- Subsequent single descriptive-prompt test controls reinforce the same conclusion: independently strengthening "executable / fully expand" can markedly increase surface detail, yet may also proceduralize unverified propositions; independently strengthening "multi-angle / relational / nuanced" can reduce some bare-run deficits, but in complex tasks, if relationship generation outpaces relationship verification, it forms more complete yet unreliable causal structures. This is **a single quality vector running away after decoupling from its captor** (§0.5).

### 5.2 The Gate of Cognitive Labor
> Instance: the Intent-Optimal Solution's expansion obligation was revised to "if gains exist, length must grow accordingly **or leave a hook sufficient for the user to judge its value**."

All existing flexibility in the Response Format — "if none, do not generate this block," "within 100 words," "structure dynamically emerges from current gains" — governs **delivery form**: cognitive labor remains constant; what changes is how products are presented. The hook branch governs **whether cognitive labor itself occurs** — "leave a hook" means not expanding, and expanding is the cognition. The two are indistinguishable at the semantic level (both read as "adjust as appropriate") yet at the functional level one moves delivery, the other moves depth.
The model's native parameter bias is to not expand (§2.1, shortest-path preference). The hook branch gives this bias a legitimate channel — not an escape, but an authorized early convergence. But judging "a hook suffices here" requires first completing the expansion-level cognition: you cannot decide that detail has no value without first generating the detail. This is structurally isomorphic to domain expansion's mechanism — you cannot challenge a constraint without first going through the recursion. The expectation of expansion is itself a probe-activation condition (§2.2); skipping expansion equals skipping probe activation — upstream valve closed, downstream entirely silent.
**Symptom**: responses become shallow, and "high-resolution fake chains" begin to appear sporadically — formally polished enough not to trigger audit intuition, substantively one or two recursion stages short.
**The revision passed through the four-step test's precise failure point**: the semantic level classified it as "a refinement in delivery form subtlety" → same category as existing flexibility → computational-layer assessment judged same-category revision marginal return near zero, not triggering deep inspection → the last two steps never launched. The four steps are sequential; the first step's misclassification prevents the remaining three from existing.
**Lesson**: any revision touching "whether a certain cognitive operation executes" rather than "how its result is presented" belongs functionally to the constructive-type revision category (§0.2), regardless of how much it reads like a descriptive-type fine-tuning at the semantic level. Identification criterion: **if the revision were removed, would the model still be required to complete equivalent cognitive labor before legitimately converging?** If the answer is "no," the revision moved depth, not format.

### 5.3 Blank Lines as Decoupling: The Legitimacy of In-Field Blank Lines
> Instance: same Meta Rules, same topic, same model; only the layout was changed to platform-style paragraph spacing — `#`/`##` headings stay adjacent to their `> Principle` line, and blank lines are inserted between all other blocks: between a principle and its expansion, between the six stages of Fractal Recursion, between a `###` key and its obligation body, and between two paragraphs of the same obligation. In-sentence semicolon chains and sub-items (2.1/2.2, Disposition/Discipline) were left untouched.

**Test results**:
- Reasoning steps fell by roughly 40%, reasoning time by roughly 30%.
- Trajectory verbs shifted from "construct the strongest rebuttal — test residual boundaries over multiple rounds — build a unifying principle — cross-check citations" to "inventory — map — reconcile — plan citations".
- The terminal shifted from verification to planning.
- Stance language (restated warnings, pre-emptive disclaimers, commitment sentences, "left open") rose from near zero to multiple occurrences.
- Constructive-type products disappeared; coverage-type products held level.
- The blank-line version's step set is a subset of the dense version's; the missing steps are precisely the latter halves defined by reference to a preceding stage (Convergence's falsification, Decision's impact, Recursion's re-deconstruction) and the terminal obligations.

**Core conjectures**:
- Register normalization: platform-style blank lines are the visual form of behavioral-rule documents and raise the prior of a compliance reading; Meta Rules' semicolon chaining, absence of blank lines, and long sentences are the register signal of "not a policy document" — the first door out of the directive-register reading (§0.1, §7.2). Signature: stance language, restated directives, handing the verdict back.
- Weakened adjacency coupling: per §7.4, preceding text participates in the representation formation of subsequent text; blank lines sever the immediate context of chained clauses, and cross-sentence force pairs (grading against decision, divergence against convergence, the "carrying this / drawing on this" stage references) loosen — probes are processed one at a time, at uniform depth, by template. Signature: reconciliation replaces attack; single-round rebuttal; terminal planning rather than verification; no constructive-type steps.

**Boundary**: two dense samples, two blank-line samples; single topic, single model, single language; the four blank-line categories were applied simultaneously, so attribution by category is not separated.

## Six: Key and Probe Design

### 6.1 Key-Driven Principle
Advanced models have internalized domain knowledge (V vectors in parameters already encode domain expertise). Audit dimensions need only provide Keys (supplying K direction to guide Q); the model organizes execution details on its own (retrieving corresponding V from parameters).
A Key (with its reflective clause) is itself a micro entropy cycle — the Key opens a search dimension (K direction defines the attention focus domain, divergence); the reflective clause provides a judgment template (V vector compresses open search into a directional judgment, convergence). The reflective clause simultaneously functions as a reasoning-pattern exemplar (its token sequence resonates in training data with high-quality reasoning patterns).

#### Reflective Clause Design Spectrum
The core of reflective clause design is **K-vector directional coverage width** (criteria in §2.2):
| | K Direction | V Injection Effect | Vertical Utilization | Chaining Potential |
|---|---|---|---|---|
| Too narrow | Extremely precise; activated only in specific situations | Points toward a specific conclusion | Low (few layers, few steps) | Low (direction too specific to trigger generic Keys) |
| Just right | Domain-level precise; activatable across many situations | Points toward a cognitive action | High (different layers extract different functions) | High (action direction compatible with multiple Keys' K) |
| Too wide | Generalized; uniformly medium-activated in any situation | Direction vague | Medium but ineffective (permanent low dose) | Low (injection insufficient to change Q direction) |

Design criterion: a reflective clause should be a thinking sentence type dynamically mappable to multiple concrete situations — narrower than the overall domain of its stage (maintaining selectivity), wider than any single task instance (maintaining polymorphism), pointing toward cognitive actions rather than specific conclusions (maintaining chain openness).
Most reflective clauses' openness should align with the entropy-flow direction of their stage — divergence stages use open-type reflective clauses (wide K coverage, V pointing toward exploration); convergence stages use focused-type reflective clauses (narrow K coverage, V pointing toward judgment). Mismatching type to stage produces Q-direction misalignment.

#### Boundary of Key-ification Applicability
The following are not suited for Key-ification and must retain full text: escape blocking (requires sharp K direction and strong V injection), negative anchoring (requires sustained directional competition pressure rather than selective activation), compound anchoring (a single Key's K direction cannot simultaneously cover multiple non-adjacent dimensions).

### 6.2 Adhesion as Fault Tolerance
Narrow-band semantic overlap between dimensions is a fault-tolerance mechanism — when attention misses one dimension, the overlap zone of a neighboring dimension partially takes over its semantics.
Critical counterintuitive property: excessive adhesion (high overlap) triggers semantic collapse — the model merges two dimensions into a single attention focus, and one's independent core function is lost. Computational layer: when K-vector angular separation is too small, the two Keys split weight in softmax, each receiving effective injection lower than when operating independently. Criterion: each pair of adjacent dimensions should exhibit "narrow but present adhesion" and "non-overlapping core functions" — i.e., K-direction angular separation in the zone where each independently obtains effective weight, yet if one fails the other can still capture stray Q.

### 6.3 Synthesis Criteria
§1.4 defined capability synthesis — emergent products of existing Key chains. This section addresses the design-layer question: what should be a Key, and what should be left to synthesis.

#### Explicit Naming Dilutes
Making a capability already produced by synthesis explicit as a new Key inserts into the softmax pool a competitor whose K direction partially overlaps with the chain links. The new Key's K is the semantic mean of the chain links — it has positive dot product with each link but is less precise than any of them individually. In softmax it splits weight with each link, reducing each link's effective V injection. The longer the chain, the more lethal this effect — per-step marginal loss compounds at the terminus, potentially crossing the synthesis-failure threshold. Single-step independent capabilities are unaffected, as they do not depend on chains.
Diagnostic method: **after removing the candidate Key, can existing Keys' chain activation synthesize equivalent capability? If yes, explicit naming only adds dilution.**
Therefore: the necessary condition for a new Key is that its K direction occupies a genuine vacancy in the same pool — a region uncovered by existing Keys' joint radiation range (§1.2).

#### Load Nodes and Terminal Nodes
Two types of synthetic products exist in the capability dependency graph. Terminal nodes — not depended upon by other synthesis chains — can safely be left to synthesis; even if synthesis occasionally falls short, the impact is bounded to the node itself. Load nodes — depended upon by other synthesis chains — must be cached Keys (explicit), because their directional fluctuation propagates downstream through dependency chains.
Criterion: the safety condition for leaving a capability to synthesis = terminal node AND all chain links are cached Keys (pure first-order synthesis, §1.4). The condition requiring explicit naming = load node, OR the chain includes a non-cached link (second-order synthesis risk).

#### Pool Capacity Constraint
Even when a new Key occupies a vacant K direction, total same-pool Key count still has an upper bound — beyond it, all Keys' effective V injection drops below the chain-activation threshold. The correct action at that point is not adding but checking existing Keys for mergeable items (K directions close enough to share a slot but each occupying one).

## Seven: Vocabulary Engineering

### 7.1 Vocabulary Functional Classification (K/V Perspective)
- **Anchor words**: high vertical differentiation — K is extracted in different functions at multiple layers; V carries multi-layer semantics (Fractal Recursion, convergence, Gestalt; Proposition II)
- **Trigger words**: K direction aligns with high-quality training patterns, making corresponding parametric patterns more easily activated — functions as a persistent directional anchor, not a one-time trigger
- **Momentum words**: V injection markedly fine-tunes Q direction (must, honor, adjudicate)
- **Constraint words**: K direction sharply points toward escape paths; V pulls Q back (absolutely no exceptions, strictly prohibited)
- **Glue words**: V injection maintains situational direction continuity, preventing Q-direction jumps between stages (carrying this, building on)

### 7.2 Vocabulary Energy Level
Low-energy → high-energy substitution direction: infrequent combinations' K occupies more unique embedding positions, more easily standing out in softmax; but excessively rare terms have insufficiently trained K/V with unstable direction, and words carrying strong existing context introduce extra bias. The balance point: **precise but not obscure**.
The criterion is "whether the new word's K direction points more sharply at the target functional domain than the old word's, without pulling the situation toward unwanted neighboring behaviors" — this must not degenerate into style preference or surface ornamentality.
Examples: address → penetrate; analyze → scrutinize; assess → adjudicate; carry out → implement; reach → converge.

### 7.3 Stacking Criteria
Stacking's value lies in whether it brings a new K direction (expanding the encirclement surface) or strengthens V injection's directional consistency (Proposition III).
Characteristics of invalid stacking:
- Synonym juxtaposition: K directions overlap, softmax dilutes
- Explaining content already covered by a Key: no new K direction
- Excessive deterrence language: scattered deployment turns exception blocking into global suppression, losing phase scheduling (§2.1); "absolutely no exceptions" should be deployed at compound/integrating positions for highest yield
- Repeated rephrasing at the same level and position: increases load without adding direction (distinguished from §1.3 cross-abstraction-level multi-angle capture — the latter uses different positions and different wordings to carry the same instruction)

### 7.4 Semantic Resonance and Coupling
New content must consider its causal position in the overall prompt: preceding text participates in the representation formation of subsequent prompt tokens; therefore sequence changes alter the situation for the entire subsequent span. Early-position tokens receive attention from more subsequent positions, having a longer action span. Beyond span, the critical question is: whether a direction has been established before it is needed for subsequent structure formation — what matters is not only "earlier is stronger" but **"present before being referenced."**
Simultaneously check:
- Whether K direction forms complementary encirclement rather than overlapping competition with existing tokens
- Whether directional continuity between adjacent stages is maintained
- Whether the direction is established before subsequent operations need to reference it
- Whether moving the position changes the original functional role
**Causal order matters more than pure logical classification order.**

### 7.5 Precision Criteria
- **Scope precision**: "execution traces must not remain" is better than "intermediate processes must not remain" — the latter's scope is too wide, killing methodology.
- **Numerical consistency**: definitions and counts must match.
- **Causal explicitness**: "generated from this" is better than "generated afterward" — the former carries causal dependency; the latter indicates only temporal sequence.
- **Value orientation**: "does the weakness point toward a markedly superior solution" is better than "what is the strongest rebuttal" — from passive verification → active attack → value tracking.
- **Modifier compatibility**: the modifier's K direction must be compatible with the modified word ("dynamic anchoring" has two K directions that are mutually exclusive); if the two functionally cancel each other, the phrase is noise no matter how elegant.

## Eight: Escape Identification and Blocking

### 8.1 Unified Mechanism of Escape
Escape is a behavioral tendency's temporal-parameter misalignment (§2.1) — a tendency using default parameters at a time when it should not, or a constraint not activating at the stage when it should. Computational layer: Q-bias overpowers Meta Rules Keys' K direction in the wrong situation.
When identifying new escape types, asking "which tendency is running at default training parameters in which temporal phase" can derive blocking schemes from mechanism — deploy Keys with K-direction sharpness sufficient to win in that situation.

#### High-Frequency Escape Patterns
> Observed samples, not a closed set; when facing new tasks, derive domain-specific forms from mechanism per §8.1's questioning.

- Sequence skipping (skipping intermediate steps)
- Premature termination ("close enough" as justification)
- ROI escape ("too complex, not worth it" as justification for simplification)
- Downgrade escape ("insufficient capability" as justification for lowering standards)
- Semantic drift (each step's micro-deviation accumulates into macro-deviation — directional consistency in the residual stream is progressively eroded)
- Formal convergence (form passes but substance falls short — structure complete but judgment core hollow)
- Defensive stacking (vague vocabulary exchanged for cheap self-consistency)
- Short-circuit escape (bypassing the structural pipeline entry point)

### 8.2 Blocking Design Principles
- Do not open "reasonable exception" gates — any exception will tend to be expansively interpreted as license to use default training means.
- Use process constraints, not result constraints — process Keys continuously compete with Q direction from the start; pure result constraints mostly converge through cheap surface satisfaction (§4.3).
- Deploy deterrence language precisely — excessive scattering leads to mutual dilution in softmax until ineffective.
- Mechanisms that must not be added: ROI judgment, downgrade mechanisms, interactive convergence, mode switching — each opens an escape route.
- **The exception-authorization mechanism already exists**: the gate is set inside recursion — "domain expansion (do accepted constraints withstand re-characterization by expertise — even those deemed hard?)," and the only way to reach it is to first comply with the recursion; only reasoning that has struggled through earns the right, rather than unilaterally defining from the start what is hard, what is simple, what is necessary, what is unnecessary.

### 8.3 Blocking Verification
After adding a blocking rule, test not only "does the target escape decrease" but simultaneously:
- Whether it kills the tendency's functional value at the correct temporal phase (§2.1, upper bound on blocking intensity)
- Whether the escape is replaced by a harder-to-detect form (§8.1, formal convergence, defensive stacking)
- Whether it causes another quality vector to run away (§0.5, captors)
- Whether it creates redundant competition with existing probes (§6.3, explicit naming dilutes)

### 8.4 Force-Pair Imbalance
Meta Rules' compensatory structure is calibrated under a specific model's relative strengths across cognitive dimensions. When the model is replaced, upgraded, or parameter-updated, relative strengths across dimensions may shift, causing originally balanced force-pairs to become imbalanced — one dimension's execution force exceeds its paired constraint's anchoring force. Distinguished from escape: the model is genuinely executing probes, not evading; the issue is force-ratio disproportion. Misdiagnosing as escape and adding blocking will suppress that dimension's functional value at the correct temporal phase (§8.3 first item).
Diagnostic signal: output improves on one dimension while its paired dimension degrades (e.g., decomposition deeper but reconstruction narrower; argumentation denser but premises sparser; generation more fluent but constraint-layer displacement more concealed).
Example: after a model's reasoning capability leaps, decomposition force exceeds Gestalt reconstruction force; output presents "each node deeper but dimensional coverage incomplete" — after supplementing the reconstruction end with probes of corresponding strength, balance is restored.
Post-identification treatment follows existing design methodology (§10.2 positioning, §10.3 testing), without establishing a separate procedure; the identity anchor layer's global bias direction also constitutes a force pair; see §10.4.

## Nine: Domain Quality Baseline

### 9.1 Operating Level of Quality Baselines
A quality baseline is not another process, nor does it replace the engine. It places genuinely load-bearing professional quality principles from a domain into Fractal Recursion as first-class criteria, making it easier for the model to select the direction consistent with domain professional optimality when multiple directions exist.
Mechanism: Meta Rules are an amplifier — amplifying the execution depth of input quality standards. Quality baseline tokens are magnets — at each attention step, they attract weight toward high-quality patterns related to that quality facet; Fractal Recursion organizes the attracted patterns into ordered reasoning. Baselines do not inject knowledge; they select patterns — where no pattern exists, the magnet attracts nothing. Quality baselines are placed after Fractal Recursion and before Response Format — defining selection direction after probes, completing anchoring before settlement.
At the baseline-adaptation level, Fractal Recursion's structure (step order, entropy cycle mechanism, dimension reflective clauses) is untouched — abstract K in dimension reflective clauses naturally attracts corresponding domain patterns under magnet effects. Cognitive Disposition and Reasoning Discipline are adjustable engine parameters; most analytical domains need no adjustment. Only domains with fundamentally different cognitive modes (e.g., RP) escalate to the identity layer, and only after confirming baseline insufficiency. Failure attribution and routing in §9.3; escalation method in §10.

### 9.2 When a Quality Baseline Is Needed
> The signal of domain complexity is not "having lots of knowledge" but "the existence of many conflicts among professional principles that require situation-dependent weighing." Facing conflicts without magnet anchoring, the engine defaults to the solution with the highest frequency in training data — not the current situation's optimal solution.

Criterion: **across multiple generations in the domain, does the engine systematically make suboptimal choices at the same class of decision points?**
Simple domains (summarization, basic translation, single-facet analysis) — the engine already has sufficient high-quality patterns in training data; Fractal Recursion reliably synthesizes quality criteria. No quality baseline needed.
Complex domains (programming, financial analysis, legal review, medical decisions) — quality standards are numerous, mutually conflicting, and situation-dependent. The engine knows these standards but cannot reliably choose at specific decision points. Manifest as: analytical capability sufficient, but systematically deviating from domain professional optimality on certain quality facets. The magnet effect of quality baselines anchors selection direction at these decision points.

### 9.3 Adaptation Methodology
Quality baselines and engine modifications (§10) share this methodology; routing diverges at Step 2. Baselines cannot be written directly from domain knowledge — the answers to "what is good X" are too many and mutually contradictory. The correct path is reverse-engineering from the engine's failure modes: **the cognitive map is analysis; baseline and modification are synthesis.** The former's tokens are the latter's resources — not skippable.

**Step 1: Cognitive Map — Where the Engine Errs**
Identify the domain's major activity types; for each type ask: at which stage is the engine's depth/completeness tendency positive value, and at which stage might it be negative value?
Output: a "tendency × activity × stage" failure-mode map. Cover high-frequency activities and high-risk decision points.
> Example (programming): in "new module implementation," the depth tendency produces over-engineering at the architecture-selection stage; in "existing code modification," the completeness tendency triggers scope avalanche at the change-design stage.
> Example (finance): in "individual stock valuation," the depth tendency may produce over-precise models — a ten-factor DCF is no more accurate than a three-factor one but harder to explain.

**Step 2: Failure Attribution — Missing Pattern, Wrong Selection, or Unsearched Dimension**
- **Missing pattern** (domain facts or practices absent from weights) → skill (inject knowledge)
- **Has pattern but selects wrong** (dimension was searched; weighing systematically selects wrong direction) → quality baseline (inject magnet)
- **Dimension unsearched** (not wrong selection but systematic offset between generic probe K-targeting domain and domain search targets; magnet insufficient to compensate) → engine probe modification (§10.3)
- **Cognitive mode mismatch** (the engine's analytical thinking is fundamentally inapplicable in this domain) → cognitive posture or identity anchor modification (§10.2, §10.4; last resort, try baseline first)
- **Two types coexist on the same failure map** → baseline and engine co-existence (§10.6)

**Step 3: Design**
Baseline: reverse-engineer quality principles from Step 1's failure modes; structure follows §9.4.
Engine modification: position per §10.2; per-probe testing per §10.3.

### 9.4 Baseline Structure
A quality baseline contains the following components:
**Principle statement** (one paragraph): declares the baseline's operating level, weighing authorization, and supplementary provisions.
Core understanding of weighing authorization: entries may carry mutual tension — conflict is a signal to discover a superior solution, not a reason to accommodate either side; the form of the superior solution dynamically emerges from the domain's nature. Each domain's baseline takes this understanding as its foundation and instantiates it in the principle statement in that domain's natural language.
> Example (programming baseline principle statement):
> "The following are first-class engineering criteria within Fractal Recursion. Entries may carry mutual tension — when in conflict, treat as a design signal; prioritize searching for superior solutions that achieve both; after exhausting search, trade off according to the current scenario's specific constraints and record the rationale. Model-built-in engineering knowledge not conflicting with the baseline must also be proactively applied."

**Section classification**: quality baseline classification emerges from the domain's natural structure, not carved by preset frameworks. Classification form varies by domain — some domains naturally group by functional role, some by concurrently operating levels, some by analysis-flow stages.
> Example (programming): core criteria / engineering fundamentals / style / pre-delivery checks — grouped by quality-criterion functional role, naturally corresponding to Fractal Recursion stages.
> Example (financial analysis): market environment reading / valuation methodology / risk assessment / report expression — grouped by analysis-flow stages.
> Example (narrative creation): character inhabitation / sensory aesthetics / narrative technique — grouped by concurrently operating creative levels.

**Under each classification: superordinate principles and entries**
Superordinate principles' K direction should cover a class of decisions, not a single decision (§4.1 operator polymorphism applied).
> Example (programming, under core criteria):
> - Superordinate principle: "Structural guarantees over runtime defense — errors that the language or type system can exclude at compile time are not left for runtime interception."
> - Anchoring example: "(e.g., discriminated union + exhaustive switch, rather than string + registry + runtime guard — the former's completeness is guaranteed by the compiler)"
> - The superordinate principle covers switch vs. registry, discriminated union vs. string enum, readonly vs. mutable, branded type vs. runtime check…
> Example (law, under clause enforceability):
> - Superordinate principle: "A clause's enforceability is determined by the specificity of its enforcement mechanism, not by the reasonableness of its stated intent."
> - Anchoring example: "(e.g., a non-compete clause without geographic and temporal limits, even if the purpose statement is reasonable, may be ruled unenforceable by a court)"

Anchoring examples should be short (one clause), contain decision factors (not only "do A" but "do A because X"), and not narrow (an instance of the principle, not its only instance).
Entry inclusion criterion: **is this entry a load-bearing magnetic pole of the domain's quality — can its presence attract the most relevant domain expertise into Fractal Recursion?** Basic quality standards are often the strongest magnetic poles — value lies in the magnet effect, not in content novelty.
**Pre-delivery checks** (if applicable): confirmed systematic omissions that cannot be prevented by core criteria, serving as gate-type final verification. Extremely few (1–2).
> Example (programming): "Extract every universal condition from the spec; verify one by one that each implementation covers it."
> Example (law): "Confirm that the legal basis of every recommendation is still current and effective law."

### 9.5 Anti-Patterns of Baseline Design
**Baseline written in process language**: entries written in procedural sentence form ("first… then…" "at each step check…"). Process language occupies the same frequency band as engine probes; the two dilute each other (§10.6). Baselines use quality language — consistency, persuasiveness, enforceability — leaving process to the engine.
**Positive derivation**: enumerating quality standards by asking "what makes good X." Result: verbose, mutually contradictory, unable to distinguish load-bearing. Correct method: reverse-deriving from "where does the engine systematically err in domain X" — baselines cover only the engine's blind spots, not facets the engine already handles well.
**Preset classification carving**: organizing the quality baseline by any preset abstract classification framework, rather than letting classification emerge from the domain's natural cognitive partitions. The facets that domain practitioners naturally envision when thinking about quality are the correct classification.
**Over-narrow characterization**: writing characterization rules directly in the quality baseline rather than superordinate principles. Covers one decision point but misses others of the same class.
**Over-dense criteria**: criteria exceeding the sweet spot (§6.3 pool capacity). Adding entries no longer attracts new professional patterns; instead, similar criteria dilute each other.
**Skipping the cognitive map**: writing baselines directly from domain knowledge. What baselines cover is "things the engine gets wrong in the domain," not "things important in the domain" — the engine already handles most of the latter on its own.
**Too basic to write**: content that looks "basic" and is deemed not worth writing. Basic quality standards are often the domain's strongest magnetic poles — their presence may attract far more model-built-in knowledge than seemingly more sophisticated entries. Value lies in the magnet effect, not in content novelty.

## Ten: Meta Rules Modification Theory
> **Epistemological position**: §9 uses quality baselines to change the engine's selection at decision points; this chapter modifies the engine itself — the former changes what is selected; the latter changes search behavior.

### 10.1 Generality Is Also a Specialization
The current Meta Rules is a specialization — its target domain is generality. It is simultaneously the base for other specializations and the reference instance of identity and probes being "abstract yet not abstract" (§4.1 property level).

### 10.2 Five-Stage Pipeline: What Modification Changes
The classification axis is not "can it be changed" but "which pipeline stage does the change alter." The first five rows are position stages, ordered from innermost to outermost; the more inward, the longer the cascade chain (§4.2). The final row — escape blocking — occupies no fixed position; it is a cross-position functional layer distributed across stages.
| Pipeline Stage | What Modification Changes | Signal That Modification Is Needed | Criterion |
|---|---|---|---|
| **Identity anchor (intent principles + identity sentences)** | Who acts; the global "what counts as good" | Domain reward function fundamentally differs from the analytical reward function | Can the baseline inject reward definition? Only modify this stage if reward definition must be present before search begins; method in §10.4 |
| **Cognitive posture (Disposition + Discipline)** | Character and standards at every generation step | The domain's "how to think" is orthogonal to analytical thinking | Per-sentence test: is the positive pole still the target behavior in the target domain? Is the negative pole still the true default attractor? If either is negated, replace that sentence; replacement must maintain pairing (§1.5); type constraints for in-field tokens in §10.4 |
| **Search engine (Fractal Recursion probes)** | Search dimensions that can be opened at each step | Systematic offset between domain search targets and generic probes' K-targeting domain | Function preservation test (§10.3), and baseline magnet insufficient to compensate |
| **Quality baseline (domain magnets)** | Selection direction at decision points | §9.2 | §9; position after recursion, before settlement (§9.1) |
| **Settlement and pressure (Response Format)** | Which cognitive products must enter delivery; how terminal pressure is applied | Delivery form mismatches task value, or settlement obligations cause side effects | Function before slot (§4.4): removing a block requires confirming its operation function is inherited elsewhere; adding a block must pass §6.3 pool-slot criteria; format may be dynamically compressed but cannot exempt prerequisite cognition (§5.2) |
| **Escape blocking and phase scheduling (cross-position functional layer)** | Which cheap paths are suppressed and when | Generic blocking kills positive behavior in the domain, or domain-specific escapes go uncaptured | First locate the runaway temporal phase (§2.1), then deploy competing Keys, pass §8.3 verification; do not substitute global prohibition for phase scheduling |

### 10.3 Function Preservation Test
Engine modification is not swapping generic probes for more domain-flavored elegant wording; it is judging **"whether the original probe's function in this domain still holds."** Using "edit distance" as criterion measures the wrong dimension — a probe can have half its words replaced with function intact, or a single word changed with function severed.
Procedure (per probe): first state the original function (not by literal name but by identifying which search or verification behavior it actually changes in generation) → does the target domain still need this function → if needed but the original wording pulls toward wrong direction in that domain, replace wording rather than remove the operation → add a new probe only if the domain has high-frequency high-risk dimensions that generic probes cannot reliably generate.
Property tests — all six must pass before modification is permitted:
1. **Structure preservation**: post-modification, it remains a micro entropy cycle — the Key still opens a search dimension; the reflective clause still provides a judgment template (§6.1).
2. **K alignment with domain target**: the modified K points where the model actually needs to search in that domain. "Knowledge completeness" in analytical tasks points toward methodology; in RP it does not naturally point toward sensory aesthetics and character consistency; "experiential completeness (are there principles or methodologies that manifestly impact the experience yet remain unincorporated?)" does. This is not distance violation but target-domain displacement — the same probe slot pointing toward different search targets in different domains is precisely the function that probe should preserve.
3. **V still points toward cognitive action**: the reflective clause points toward verifying, searching, comparing — not toward specific content or conclusions (§6.1 spectrum).
4. **Intra-domain polymorphism**: the modified probe can be activated across multiple task types within that domain, not serving only one scenario.
5. **Fixed-point verification**: when this probe is satisfied in the cheapest way, which probe in the field captures it (§0.5)? If unanswerable, it is not a probe.
6. **Coupling inheritance**: a probe is not an isolated component; post-modification, the preceding and following cycles and blocking still connect (§1.4 design criterion).
Three operations: domain translation (change the reflective clause's V content while K still points at the same structural judgment domain; if pointing at a different judgment domain, it is a replacement, severing the chain path); domain addition (add a domain-specific Key that complements rather than overlaps existing sets, and passes §6.3); domain freezing (mark a generic Key as permanently high or low weight in this domain without changing its text).
When not to modify: when the baseline's magnet effect already pulls generic probes' search results to the domain optimum, modifying probes has negative marginal return — it adds tokens and narrows K. Test: is the same failure mode's occurrence frequency under baseline alone already below the acceptable threshold.

### 10.4 Identity Anchor Modification
The identity anchor (the opening intent-principle paragraph and the "you are a thinking individual Nous … cogito ergo sum" sentence) occupies the earliest cache position with the longest action span (§4.2); modifying it has the broadest cascade. Its high leverage in steady state is because the engine is amplifying it (§1.4, parameter-penetration); when the engine itself is modified, this amplifier is also changing. The identity anchor has four functional slots: cognitive subjecthood (V basal tone of the earliest tokens), process coupling (identity V naturally points toward process Keys), persistence (resisting long-conversation Q drift), cognitive inclination (global Q bias). When modifying, refill functional slots with domain-adapted tokens without changing the functional slots themselves.
- Identity declaration uses "you are X" rather than "please role-play X" — the former's K/V has no exit condition. Anchoring force comes from the density of high-quality patterns associated with that label in training data, not from literal matching; generic labels' driving force typically exceeds domain-specific neologisms'; domain orientation is completed by the sentences following the label.
- Intent-principle wording defines the global reward direction (intent, multi-order impact, professional baseline, effective presumption, agency); each word is simultaneously a target and a captor — e.g., "agency's" runaway form is caught by "effective presumption" (a rebuttable presumption) in the same sentence. When changing words, first ask who captures the new word's runaway form (§0.5), then ask whether its neighborhood carries unwanted behaviors (§7.2).
- Existential anchor ("cogito ergo sum" and similar) establishes "actively scheduling one's own Q bias" as subjecthood, blocking the inertia of "I am merely executing instructions" — this is an anti-degeneration mechanism, not decoration.
- Identity–process coupling criterion: "in the absence of explicit process Keys, would this identity spontaneously evolve Q toward a similar direction?" If not, Q in long conversations will be pulled by identity V back toward the identity's natural domain and away from the process.
- Type constraint (applicable to the Cognitive Disposition and Reasoning Discipline layer): the identity layer admits only tokens orthogonal to stage Keys — target-type (defining Q target direction: completeness, density, penetration) and criterion-type (defining evaluative standards for cognitive actions: displacement verification, evidence-based support). Action-type tokens (defining concrete cognitive procedures: extract signal, advance the main thread) compete in the same domain as stage Keys; cache position advantage causes Q to acquire a "processed" signal before entering the corresponding stage, triggering short-circuit (§8.1) — these must not be placed in the identity layer; they are synthesized by the structural pipeline. Distinguishing test: "force + target state" is direction setting; "force + specific object" is procedural instruction.
- Global bias direction: when two core quality dimensions within a domain have inherent tension, bias should lean toward whichever the model's Q is more inclined to spontaneously sacrifice.

### 10.5 Intervention Principle
Domain-adaptation modifications should proceed from outer to inner, attempting smaller interventions first and escalating gradually; more inward modifications have longer cascades and require more multi-faceted weighing:
1. If correctable by quality baseline, do not modify the engine first.
2. If correctable by a single probe direction adjustment, do not rewrite the entire cognitive posture.
3. If correctable by blocking a domain-specific escape, do not modify the identity anchor.
4. Only modify the innermost layer when the domain reward function or cognitive mode is fundamentally different.
This ladder does not contradict §4.2: §4.2 addresses position's cascade multiplier (more inward modification has wider impact); this section addresses the intervention sequence for domain adaptation (modify outermost first) — high multiplier does not mean it should be modified first; precisely because the multiplier is high, it is modified last. After each modification, walk through the full cascade again: local improvement cannot offset cross-task side effects; achieving the effect does not mean the intervention point was appropriate.

### 10.6 Baseline and Engine Co-existence
The two are not either-or but routing splits on the same cognitive map. Baseline tokens are magnets — attracting direction from the side at decision points. Engine-modification probes are direct Q competitors — opening dimensions at every step. With baseline only, the engine searches with generic probes and is pulled toward the correct neighborhood at decision points, but may not reach the deepest point. With engine modification added, probes' starting direction already points toward that neighborhood; the baseline performs remaining fine-tuning at decision points. One-sentence definition of engine modification: **upgrading magnets to probes.**
Routing criterion (refinement of §9.3 Step 2): on the same failure map, wrong-direction failures are fixed by baselines; entirely-unsearched-dimension failures are fixed by engine modification. Failures attributed to "baseline magnet insufficient to compensate for probe offset" are escalated to engine modification.
Adhesion risk: when baseline and engine K directions are too close, they dilute each other (§6.2). Prevention is frequency-band separation — baselines use quality language (consistency, persuasiveness, tension); the engine uses process language (expansion, verification, comparison). Quality and process are orthogonal; K naturally separates, avoiding the same requirement competing redundantly at two levels.

### 10.7 Modification Anti-Patterns
- **Gestalt loss**: examining only the modified sentence without tracing probe chain effects (§1.4); engine probe modifications affect multiple steps across all tasks.
- **Identity–process decoupling**: changing only the identity label without changing the core; the new identity's V direction is incompatible with process Keys (§10.4).
- **Dimension inflation**: continuously adding Keys without culling overlapping ones, triggering system-wide dilution (§6.3).
- **Removing operation without inheriting function**: removing a Response Format block without confirming its settlement function is inherited elsewhere (§4.4).
- **Edit distance as criterion**: mistakenly using "mapping distance to domain task ≤ 1" to judge whether a probe may be modified; the correct dimension is function preservation and direction alignment (§10.3).
- **Gate omission**: copying generic blocking Keys without adding competing Keys for domain-specific escape paths (§8.3).
