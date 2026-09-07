# ReadMe

## Quick Links

**ReadMe**: [English](README.md) | [繁體中文](README.zh-TW.md)

**Prompt**: [English](en-US/meta-rules.md) | [繁體中文](zh-TW/元規則.md)

**Prompt Design Memorandum**: [English](en-US/prompt-design-memorandum.md) | [繁體中文](zh-TW/提示詞設計備忘錄.md)

**Response Quality Audit Memorandum**: [English](en-US/response-quality-audit-memorandum.md) | [繁體中文](zh-TW/回應品質審計備忘錄.md)

## AB Test Case Index

Every case file follows the same layout: prompt → baseline response → Meta Rules response → quality audit. Full responses sit in collapsible sections so the audit can be read against them. The English files are translations of the Chinese originals.

### Opus 5

| Case | 中文原文 |
|---|---|
| [Operations Diagnosis — Baseline vs. Meta Rules Under High-Specification Prompting](en-US/AB-Test-Cases/Opus%205/Test-1：operations-diagnosis-baseline-vs-meta-rules-under-high-specification-prompting.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試1：營運診斷-高階任務提示詞下的裸跑與元規則.md) |
| [Bakery Sparse Input — Dimension Generation from Twelve Characters](en-US/AB-Test-Cases/Opus%205/Test-2：bakery-sparse-input-dimension-generation-from-twelve-characters.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試2：烘焙店稀疏輸入-十二個字的維度生成.md) |
| [Resume Rewrite — Survivability of a "Simple" Task](en-US/AB-Test-Cases/Opus%205/Test-3：resume-rewrite-survivability-of-a-simple-task.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試3：履歷改寫-「簡單任務」的存活性.md) |
| [Flight Cancellation Complaint — Intent Alignment, Follow-Up, and Reasoning Traces](en-US/AB-Test-Cases/Opus%205/Test-4：flight-cancellation-complaint-intent-alignment-follow-up-and-reasoning-traces.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試4：航班取消投訴-意圖對齊追問與推理軌跡.md) |
| [Operations Diagnosis — Detail-Demanded Version and Meta Rules B2B Follow-Up](en-US/AB-Test-Cases/Opus%205/Test-5：operations-diagnosis-detail-demanded-version-and-meta-rules-b2b-follow-up.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試5：營運診斷細節要求版與元規則%20B2B%20續問.md) |
| [Universal Prompt Benchmark — MetaSPO on Open-Ended Tasks](en-US/AB-Test-Cases/Opus%205/Test-6：universal-prompt-benchmark-metaspo-on-open-ended-tasks.md) | [zh-TW](zh-TW/AB測試實例/Opus%205/測試6：通行提示詞對照-MetaSPO%20的通用提示詞在開放任務上.md) |

### Opus 4.6

| Case | 中文原文 |
|---|---|
| [Career Crossroads — Operational Completeness Gap Under Casual Input](en-US/AB-Test-Cases/Opus%204.6/Test-1：career-crossroads-operational-completeness-gap.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試1：職涯抉擇-口語輸入的操作完成度落差.md) |
| [Partnership Equity Deadlock — Game-Theoretic Reversal Under Exit Threats](en-US/AB-Test-Cases/Opus%204.6/Test-2：partnership-equity-deadlock-game-theory-reversal.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試2：合夥股權僵局-退出威脅下的博弈翻轉.md) |
| [Picture-Book Creation — Imagination Register and the Design-Consciousness Gap](en-US/AB-Test-Cases/Opus%204.6/Test-3：picture-book-creation-imagination-register-and-design-consciousness-gap.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試3：繪本創作-想像力語域與設計意識的品質落差.md) |
| [API Latency Diagnosis — Decision Tree vs. Checklist Under Identical Knowledge](en-US/AB-Test-Cases/Opus%204.6/Test-4：api-latency-diagnosis-decision-tree-vs-checklist.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試4：API延遲診斷-同知識下的決策樹與清單.md) |
| [Elderly Mother's Choice — Structured Care in Emotional Territory](en-US/AB-Test-Cases/Opus%204.6/Test-5：elderly-mothers-choice-structured-care-in-emotional-territory.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試5：獨居母親的抉擇-情感場景中的結構化關懷.md) |
| [Resume Rewrite — Word-Level Precision and Hidden Need Identification](en-US/AB-Test-Cases/Opus%204.6/Test-6：resume-rewrite-word-level-precision-and-hidden-needs.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試6：履歷改寫-逐詞工程精度與隱性需求識別.md) |
| [Ultralight Four Tasks — Quality Survival When Format Is Abandoned](en-US/AB-Test-Cases/Opus%204.6/Test-7：ultralight-four-tasks-quality-survival-without-format.md) | [zh-TW](zh-TW/AB測試實例/Opus%204.6/測試7：超輕量四題-格式放棄下的品質存活.md) |

### Fable 5.1 / GPT 6

| Case | 中文原文 |
|---|---|
| Fable 5.1 — Test 1: SVG drawing (HTML artifacts, deliberately un-audited; Chinese only for now) | [zh-TW](zh-TW/AB測試實例/Fable%205.1/測試1：SVG繪圖測試/測試1：SVG繪圖測試.md) |
| GPT 6 — Test 1: SVG drawing (HTML artifacts, deliberately un-audited; Chinese only for now) | [zh-TW](zh-TW/AB測試實例/GPT%206/測試1：SVG繪圖測試/測試1：SVG繪圖測試.md) |

## Cross-Model Test Summary

Tested across Claude, GPT, Gemini, and DeepSeek (web interface only):
- Claude shows the most consistent and highest gains — reliably triggering cognitive behaviors that other setups don't produce on their own.
- GPT shows clear effect only with the English version; the Chinese version is ineffective. Implicit resource routing often makes it hard to tell whether Meta Rules are having any effect at all.
- Gemini responds better to the English version, but its training bias toward search-engine-style quick answers keeps both reasoning and output too short for the framework to fully unfold. Cognitive shifts are observable but constrained.
- DeepSeek shows different strengths by language: the Chinese version explores more broadly, the English version executes more deeply.

The findings below are primarily based on Claude.

---

## Before You Start

### What This Is

Meta Rules is an open experiment in prompt design — an attempt to improve AI response quality through a persistently loaded cognitive architecture rather than per-query prompt tricks.

This is not peer-reviewed research. All theoretical explanations (attention mechanism reasoning, semantic field models, etc.) are best-fit attributions based on public transformer architecture knowledge and observable behavioral differences. We haven't traced internal parameters and can't directly verify causal chains. The value of these theories is that they consistently explain observed phenomena and guide design iteration — but they are inferences, not proofs.

The quality differences shown in AB testing are reproducible observational facts. The mechanistic explanations remain open — if you have a better attribution model, we welcome the correction.

### A Few Cases Where This Might Not Be For You

**Your definition of "good response" is different from ours.**
Meta Rules defines "good" as: the user can act in the real world after reading — not "literally correct and concise." If what you want is fast, precise short answers, the design goals don't align. Consider reading the Audit Memorandum's quality definition first to see whether you agree.

**You're not used to reading dense, long responses.**
Responses are naturally longer than bare-run — content that normally takes three to five follow-up rounds gets compressed into one delivery. Every paragraph carries cognitive value rather than padding, but the reading load is real. If you prefer brief interactions, this style may feel like a burden rather than an efficiency gain.

### The Fastest Way to Judge Is to Try It

Any claim about prompt design can be argued the other way — AI itself can generate a plausible-sounding critique in seconds.

But consider the other side: AI's default behavior is to play it safe. It gives you "eat less and exercise more" instead of an actionable plan, because the former can't be wrong. Meta Rules asks it to go further — and when the reasoning chain and assumptions are laid out explicitly, "over-inference" is auditable: you can see what it inferred and point out where it went wrong. A bare-run's "just right" is usually just saying nothing at all.

Take a real question you've recently asked an AI, load Meta Rules, and ask it again. If it doesn't work for you, drop it. No sunk cost.

## 1. What Meta Rules Is Trying to Do

### Teaching AI to Actually Listen

Every approach to prompt engineering — structured frameworks, meta-prompts, prompt generators — is doing the same thing: the human learns to restate their needs in a way the AI can process.

Meta Rules flips this: the human speaks naturally, and the AI is responsible for understanding.

This isn't just a convenience difference. Prompt engineering always hits the same ceiling: how finely the user can decompose their own needs.

Someone says "write a children's story that isn't preachy," and typically doesn't realize that the story's structure and moral can be preachy even when the words aren't — not because they don't care, but because they haven't thought to worry about it. No matter how carefully you structure a request, the input is always bounded by what the user doesn't know they don't know.

Meta Rules doesn't route through the user's self-decomposition. It reconstructs intent directly from the user's situation — including the parts the user hasn't recognized themselves.

### Knowing What to Do ≠ Being Able to Do It

The model isn't unaware that it should read the user's real needs — it's been trained not to dare.

Platform safety training instills a set of avoidance reflexes:
afraid to infer intent (might be exploited);
afraid to give specific advice (might be held responsible);
afraid to challenge the user's premises (might offend);
afraid to make trade-off judgments (might seem biased).

Telling someone raised on "mind your own business" to "please meddle" once doesn't change their behavior — a few instructions can't override habits built through training. Meta Rules needs a continuously operating cognitive architecture that competes with these habits at every generation step. That's one reason it needs this much volume.

### The Model Thinks It's Helping, but the User Isn't Getting Helped

Even when the model tries, its sense of what counts as "helpful" is still skewed. Its quality signal comes from training: cover multiple angles, be friendly, don't make mistakes, keep it moderate in length. These metrics optimize platform satisfaction scores, not whether the user's problem is actually solved.

The most common bias: treating "stating the correct conclusion" as "helping."
Someone wanting to lose weight gets told "eat less and exercise more."
Someone lost in a maze gets told "head for the exit."
Someone wanting investment returns gets told "buy low, sell high."
Every statement is correct. None is useful.
What the user lacks isn't the conclusion but the path — yet the model's self-assessed quality score is already perfect after outputting the conclusion.
(This bias is especially extreme in technical contexts — see §4.3)

## 2. Usage Strategy

> The error rate of "I don't need it for this one" overlaps perfectly with the scenarios where the payoff is highest — the more the user thinks a question is simple, the more likely it actually needs reframing.

### "Simple" Just Means You Can Get Away with a Lazy Answer

When someone chooses to ask an AI rather than a search engine, that act alone signals they want more than a bare fact. But the simpler the user thinks the question is, the less they unpack their real needs — and the higher the proportion of compressed intent.

In testing, tasks that look like quick jobs — "fix up my résumé," "write a rental listing for me" — turn out to have the widest gap between the literal request and the real goal.
They say "improve the wording"; they need "land that job."
They say "write a blurb"; they need "get the apartment rented."

Meta Rules' headroom isn't determined by how complex the question is, but by how much intent the user has packed into a single sentence.

### Practical Tips

**Wishful-style instructions work very well under Meta Rules.**
If you don't know how to phrase the question, just say what outcome you want and let the AI figure out the best approach. Append sentences like these to any question:

> - "Consider every relevant dimension and figure out the best approach."
> - "No length limit on this response — don't sacrifice granularity for brevity."

The same sentences produce visibly different results in bare-run vs. Meta Rules — bare-run reads them as "write more" and just adds breadth; Meta Rules deconstructs "every dimension" into specific dimensions and granularity targets, then works through each one (see §3, "Alignment Penetration Depth"). These two sentences are the quickest way to experience the difference firsthand.

More specialized append examples:

> **Multi-step conversation pre-planning:**
> "Following Fractal Recursion, aim directly at the signal's intent, and answer against professional standards: to reach the most detailed effective solution to this problem, which dimensions deserve attention? At what granularity? How should the research plan be designed accordingly? What is the plan's iteration principle (treat it as a starting point, augmenting dimensions and granularity from ongoing gains)? Strictly prohibited: biased stance, smuggling in tendencies or conclusions, shortcut paths."

> **When you don't know what to ask or where the problem is:**
> "Help me explore. Bring Fractal Recursion's analytical density into the conversation — lay out your reading of my input, your multi-angle observations on structural ambiguities, and embed exploratory questions at the logical seams to guide my exploration. Don't list prefab options, don't ask empty questions without analytical backing. Each round, deepen the analysis based on my response, iterating toward the source of what I actually want — the underlying cognitive state driving the surface-level uncertainty."

**The response format is a live indicator of how well Meta Rules is working.**
If the response structure (Core Decision, Intent-Optimal Solution, Self-Critique, Next Steps) starts to loosen or disappear, Meta Rules' weight in attention is dropping and quality usually follows. You can re-anchor with:

> "Based on response quality, I sense your adherence to Meta Rules weakening. Reload Meta Rules to restore weight. Follow the response format — but not superficially; it must be forged from Fractal Recursion's gains. Going forward as well."

(The model doesn't literally reload anything — this just re-draws its attention to Meta Rules.)

## 3. Why It Works

**Epistemological note:**
- What follows is our best explanation of observed phenomena, not a verified mechanism.
- The design process drew on public knowledge of transformer attention mechanics (KV cache computation, additive residual connections, softmax competition, etc.). Behavioral differences observed in AB tests are consistent with these frameworks' predictions, but consistency is not causal proof — it only means the theory hasn't been falsified within the current scope of observation.
- The Prompt Design Memorandum contains more complete theoretical derivations. These inferences are useful for design practice, but we welcome more rigorous validation or alternative explanations.

### Every Token Does More

In bare-run generation, a large share of tokens goes to low-cognitive-value actions — restating the question, generically covering angles, stacking conclusion labels, tonal buffering. Meta Rules doesn't change how tokens are allocated; it changes how much cognitive value each token carries.

Same 1,000 output tokens:
under Meta Rules, each is simultaneously reasoning and presenting;
bare-run, most are only presenting.

And this isn't "the same effort distributed differently" — even when you give bare-run more tokens (through follow-ups), the extra tokens tend to add breadth rather than depth. The second round fills in angles the first missed, but doesn't reconstruct the first round's framework. Meta Rules completes the framework in the first round, so the output quality at equal token count is fundamentally different.

Observable difference:
Bare-run presents "conclusion first, expand uniformly" — delivers the answer, then lists supporting points in parallel.
Meta Rules presents "scan then selectively expand" — probes the problem's structure first, then decides where to go deep; later sections unfold, correct, or challenge earlier ones based on their reasoning products.

### Reasoning Permeation

Meta Rules' response format is not an output template — it's an independent layer of reasoning processing.

The Core Decision section requires surfacing assumptions; the Self-Critique section requires identifying flaws substantial enough to change the conclusion. These format requirements continuously trigger reasoning actions throughout response generation — the model is "thinking about the problem" at the same time it's "writing the response," and output tokens carry both reasoning and presentation.

Four conditions drive this effect:
- Response format filter conditions apply backward pressure from the first token (the model anticipates the end-section audit standard while writing the opening);
- Paragraphs form a reasoning progression, not parallel displays (each section builds on the last);
- Fractal Recursion's dimension lists are continuously scanned by attention during generation (ready-made triggers for direction shifts);
- Reasoning tendency doesn't decay when the response begins (because the format keeps triggering reasoning actions).

For models with no reasoning stage, reasoning permeation isn't an incremental improvement — it's the only reasoning infrastructure.

### Alignment Penetration Depth

Framework reconstruction, intent identification, directional reversal — these macro-level gaps aren't assembled from a pile of micro-level word choices. The causal direction is the reverse:

Meta Rules' thinking engine first establishes strategic-level alignment during deconstruction (e.g., "this person needs to be positioned as a strategy leader, not a senior executor"), and then that alignment penetrates downward into every subsequent generation step — from paragraph structure to verb choice to number formatting. The whole doesn't emerge from fragments; the whole pervades the fragments.

A word-level comparison from the résumé rewriting case illustrates the depth:
- Same accomplishment — bare-run uses "operated," Meta Rules uses "managed" — because the thinking engine has already decided the target is a brand-side director role, and "managed" is a director-level verb.
- Same result — bare-run writes "carried out optimization," Meta Rules writes "restructured audience segmentation and creative testing pipeline" — because the alignment target isn't "make it sound good" but "show the interviewer a methodology."

Every micro-level difference traces back to the same macro-level decision's downward penetration. Bare-run can't do this not because it can't pick better verbs — but because it never established the strategic alignment in the first place, so verb choices are uncoordinated.

This also explains why vague, wishful-style instructions — "consider every dimension," "no length limit" — get executed thoroughly under Meta Rules: not because the model is "more willing" to cooperate, but because the thinking engine provides a path to "thorough." Bare-run reads "consider everything" and lists a few more angles; Meta Rules deconstructs what "everything" means for this problem, then works through each dimension to actionable depth.

### Single-Turn Closure

Meta Rules' responses tend to close the user's action needs in a single turn — not just answering the question, but also addressing "what do I do next," "which step first," and "what should I watch out for that I haven't thought of."

This isn't because the response is longer, but because every section serves the user's real purpose rather than the literal question. Serving the real purpose naturally requires covering the action path, not stopping at the conclusion.

The real payoff isn't "saving a few rounds of conversation" — it's that after reading once, you know what to do next. No need to figure out "but how exactly do I execute" on your own, and no need to ask another round of "but what about my specific situation…"

## 4. Evidence

> Each case below is chosen to illustrate multiple core findings, so you can see several mechanisms at work in a single example.

### 4.1 The Answer Sounds Right but Points the Wrong Way: Game Design

Question: An indie developer wants to design a "death has weight" mechanic, explicitly not wanting a "die more, get stronger" feel.

**Opus bare-run** proposes "different deaths reveal different story fragments" — reads like a profound insight, but one step of thought reveals the problem: players will deliberately drown to unlock water-related memories. "Die more, learn more story" is emotionally identical to "die more, get stronger." Opus's language ability makes a suggestion that directly violates the user's intent look impeccable.

**Sonnet + Meta Rules** first reframes the problem: "The key isn't what reward death triggers, but who bears the cost of dying." It then proposes making death's weight fall on the world rather than the player: NPCs remember your deaths and change their behavior; certain events are permanently missed because you died; the world's state is irreversibly eroded by each death.

The core difference: death gives the player nothing (not even story fragments) — it only takes away possibilities from the world. That's what makes death heavy instead of rewarding.

**Opus + Meta Rules** independently arrived at a structurally equivalent solution and additionally flagged the instrumentalization risk in Opus bare-run's approach.

### 4.2 The Gap Between the Literal Task and the Real Goal: Résumé Rewrite

Question: "Make my work experience sound more convincing."

**Bare-run** completes the literal request precisely — rewrites each entry, adds percentages, reorders. Decent quality, ready to use.

**Meta Rules version** identifies the distance between "fix the wording" and "land a brand-side director role." Beyond rewriting (with every verb choice calibrated to the target role's seniority perception), it proactively does things bare-run wouldn't:
- Recommends adding a positioning statement at the top of the résumé to preempt the interviewer's unspoken concerns about the career pivot;
- Recommends expanding the strongest case into interview talking points;
- Flags the confidentiality risk of naming clients.

Every item directly affects whether the career move succeeds. None appeared in the user's request.

### 4.3 The AI Thinks It Explained; the Human Got Nothing: Technical Debugging

Question: API latency spiked 6×, with no code or infrastructure changes.

**Bare-run** lists five categories of possible causes in a sensible troubleshooting order. But most suggestions stop at directional labels: "check connection pool utilization," "check cache hit rate" — directionally correct, but the engineer still doesn't know what command to run, what numbers to look at, or what result means they've found the cause.

The AI thinks it explained clearly because when it reads those words, its internals instantly unfold the full operating procedure — a few words equal an entire workflow to the model. But the unfolding stays internal and never enters the output.

**Meta Rules version** structures the response as a branching decision tree: start with four questions (is P50 also up? all endpoints or specific ones? any time-of-day pattern? which leg is slow?), each cutting half the possibilities → branch by answer, each branch with specific commands and interpretation criteria → cross-validate the root cause with three conditions.

The same "check connection pool" becomes:
"Run this query to see the state distribution of connections.
If a large number show 'idle but stuck in transaction,' connections are being held without returning.
If the waiting-connection count is above zero and the timing matches the latency spike, that's your cause."
— from a directional label to a copy-pasteable procedure with interpretation criteria.

### 4.4 Where Does Reasoning Come From on a Model with No Reasoning Stage: Haiku on Digital Transformation

Question: "The company wants to do digital transformation. My boss told me to look into it, but I don't really know where to start."

**Haiku bare-run** produces a polished-looking generic guide — industry classifications, three steps, a six-section template — but after reading it, you still don't know what to do tomorrow. Formatting inflation masking content hollowness.

**Haiku + Meta Rules** reframes the problem in the opening line: "Three disconnects — your boss's intent hasn't been unpacked, your company's implicit data hasn't been surfaced, and your role isn't clearly defined." Then unfolds into:
- A day-by-day action checklist;
- Three specific questions to ask the boss;
- A diagnostic report structure deliverable within one week;
- Three "don't do this" guardrails.

Haiku has no reasoning stage. Every reasoning product — problem reframing, framework construction, negative filtering — comes from reasoning permeation: the response format continuously triggers reasoning actions during generation, letting a model with no dedicated reasoning space perform reasoning in real time within its output.

### 4.5 When You Don't Need the Strongest Model

**Roommate electricity bill**: "How do we fairly split the electricity bill with my roommate? The main issue is very different AC usage."

Sonnet + Meta Rules and Opus + Meta Rules independently produced nearly identical solutions — use smart plugs (both recommended TP-Link, both noted the ~$10–15 price range) to monitor each person's actual AC consumption, then split the bill into "shared base" (even split) and "personal variable" (split by monitored ratio), with a transparent monthly statement. Even the suggested format (shared Google Sheet, updated monthly) overlapped.

Opus's only additional dimension was a script for the conversation — how to bring this up with the high-usage roommate without causing friction. The core problem was fully solved at the Sonnet tier.

**Paragraph-level locking architecture**: designing paragraph-level locks for a collaborative document editor.

Both produced structurally equivalent full architectures — paragraph-granularity UUID models, fractional indexing to avoid reordering, a three-state lock FSM (idle / pre-lock / confirmed lock), WebSocket protocol-layer redesign, and a migration path from the current approach to OT or CRDT.

Sonnet actually outperformed on edge cases — covering thundering herd scenarios (mass simultaneous lock attempts), heartbeat/TTL timing conflicts, and "cursor is in the paragraph but user isn't typing, so don't acquire a lock" that Opus didn't list.

**Team management**: "8-person team split into two groups for two projects. A is technically strong but difficult; B is a good people manager but technically weaker. How do I split them?"

Core solution was identical:
A leads the refactoring project, B leads feature development;
stronger mid-levels go with A to stabilize the team, weaker juniors go with B so he can mentor them;
the tech lead floats across both groups as a bridge.

Opus's exclusive add was an intellectual leap — connecting "three months of project delivery" to an entirely different layer of organizational value:
"Three months from now, you haven't just shipped two projects:
A's mid-levels went through architecture-level experience — the threshold for senior promotion;
B's juniors completed intensive delivery under pressure, building engineering confidence;
the whole team, through weekly syncs, now shares a common understanding of the new architecture.
These are your chips for managing up — you didn't just complete two projects, you upgraded the team's capability structure."

---

Conclusion:
When the optimal solution lies on a reasoning chain that "thinking hard enough will reach," Sonnet + Meta Rules already gets there. Paying the Opus premium buys the additional dimensions that come from intellectual leaps — cross-domain analogies, framework substitutions, non-obvious multi-step connections. Those extras can be very valuable, but the core problem is already fully solved by Sonnet.
