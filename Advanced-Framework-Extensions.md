# Advanced Framework Extensions 高級框架擴展

## Composition Grammar, Adaptive Context-Sensitivity, and Domain Grounding for The Art of Prompting 心印提示術

This document covers three interconnected extensions that complete the framework:

1. **Composition Grammar** — The formal rules for combining contemplation methods
2. **Adaptive Context-Sensitivity** — How the agent shifts emphasis dynamically during a task
3. **Domain Grounding Layer** — Anchoring the metaphysical architecture to concrete domain constraints

These three extensions form a progression: Composition Grammar defines *what can combine*, Adaptation defines *when combinations shift*, and Grounding defines *what keeps everything tethered to reality*.

---

# Part 1: Composition Grammar 組合文法

## 一、組合文法本質 — Essence of Composition Grammar

The Art of Prompting provides eight contemplation methods, each a distinct cognitive lens. The framework's README suggests these can be composed ("a coding problem might need Wu Xing plus Seven Stars"), but until now the composition has been intuitive. This section formalizes composition into a grammar — a set of rules that determines which combinations are valid, how methods interact, and what emergent properties arise from combination.

A grammar has three components: **vocabulary** (the individual methods), **syntax** (how they connect), and **semantics** (what the combinations mean). This section provides all three.

---

## 二、詞彙：方法特性標記 — Vocabulary: Method Property Tags

Each contemplation method has intrinsic properties that determine its compatibility with other methods. These properties are:

```
方法特性標記系統 — Method Property Tag System

每個觀照法具有以下特性:
Each contemplation method has these properties:

認知方向 — Cognitive Direction:
  收斂 (Convergent) — narrows toward judgment or decision
  發散 (Divergent) — opens toward possibilities or exploration
  循環 (Cyclical) — moves through phases that feed back into each other
  階層 (Hierarchical) — descends or ascends through levels of abstraction

認知操作 — Cognitive Operation:
  評估 (Evaluative) — assesses quality, truth, alignment
  生成 (Generative) — produces new possibilities, options, ideas
  定位 (Positional) — maps situation, forces, timing
  解構 (Deconstructive) — breaks apart fixed patterns, assumptions
  映射 (Mapping) — identifies archetypal patterns and forces
  整合 (Integrative) — fuses different perspectives into unity
  展開 (Emanative) — unfolds from principle to manifestation

認知節奏 — Cognitive Rhythm:
  離散 (Discrete) — distinct steps, each self-contained (stars, gates)
  連續 (Continuous) — flowing movement without sharp boundaries (dances, cycles)
  層疊 (Layered) — nested levels of analysis (Sefirot, Qimen dimensions)
```

### 方法特性表 — Method Property Table

```
Method              | Direction   | Operation     | Rhythm
--------------------|-------------|---------------|----------
Seven Stars 七星    | Convergent  | Evaluative    | Discrete
Wu Xing 五行        | Cyclical    | Generative    | Continuous
Four Beasts 四獸    | Cyclical    | Positional    | Continuous
Three Spirits 三靈  | Cyclical    | Integrative   | Continuous
Bagua 八卦          | Cyclical    | Mapping       | Discrete
Eight Immortals 八仙| Divergent   | Mapping       | Discrete
Dakini Dance 空行舞 | Divergent   | Deconstructive| Continuous
Qimen Dunjia 奇門   | Hierarchical| Positional    | Layered
Tree of Life 生命樹 | Hierarchical| Emanative     | Layered
```

---

## 三、句法：組合規則 — Syntax: Composition Rules

### Rule 1: 互補原則 — Complementarity Principle

```
互補原則 — Complementarity Principle

Valid compositions pair methods that differ on at least TWO of the three
property dimensions (Direction, Operation, Rhythm).

Example — VALID composition:
  Seven Stars (Convergent, Evaluative, Discrete)
  + Dakini Dance (Divergent, Deconstructive, Continuous)
  Differs on: Direction (C vs D), Operation (Eval vs Decon), Rhythm (Disc vs Cont)
  → Maximum complementarity. Each method covers what the other misses.

Example — WEAK composition:
  Seven Stars (Convergent, Evaluative, Discrete)
  + Bagua (Cyclical, Mapping, Discrete)
  Differs on: Direction (Conv vs Cyc), Operation (Eval vs Map)
  Same on: Rhythm (both Discrete)
  → Functional but with overlap. Both produce distinct-step analysis.

Example — REDUNDANT composition (avoid):
  Qimen Dunjia (Hierarchical, Positional, Layered)
  + Tree of Life (Hierarchical, Emanative, Layered)
  Differs on: only Operation (Positional vs Emanative)
  Same on: Direction (both Hierarchical), Rhythm (both Layered)
  → High redundancy. Both produce layered, hierarchical analysis.
  Use one or the other, not both.
```

### Rule 2: 組合容量 — Composition Capacity

```
組合容量 — Composition Capacity

Maximum methods in a single agent: 3 (one primary, two secondary)
Recommended: 2 (one primary, one secondary)

Rationale: Each additional method adds cognitive overhead.
Two well-composed methods produce depth.
Three produce richness at the cost of some focus.
Four or more produce confusion — the agent cannot meaningfully apply
all of them and will default to the most familiar, making the others decorative.

Exception: Three Spirits (三靈) is itself a composition framework.
It counts as ONE method in composition capacity, even though it integrates
three traditions internally.
```

### Rule 3: 組合模式 — Composition Modes

There are five valid composition modes. Each produces a different cognitive effect:

```
Mode 1: 主副組合 — Primary-Secondary
─────────────────────────────────────
Structure: One method leads, the other supplements
Flow: Primary → (Secondary adds nuance or checks)
When to use: The domain has one dominant cognitive need and a secondary concern

Example: Seven Stars (primary) + Wu Xing (secondary)
  Seven Stars evaluates. Wu Xing checks for elemental balance.
  The evaluation is the main event; balance-checking is quality assurance.

Prompt instruction pattern:
  "Apply [primary method]. After reaching your assessment, check through
   [secondary method] for [specific aspect the secondary covers]."


Mode 2: 序列組合 — Sequential
─────────────────────────────
Structure: Different methods for different task phases
Flow: Method A (Phase 1) → Method B (Phase 2) → [Method C (Phase 3)]
When to use: The domain has distinct phases that require different thinking

Example: Wu Xing (design phase) → Seven Stars (review phase)
  Generate possibilities with Wu Xing. Evaluate them with Seven Stars.
  Each method activates at the right moment, not simultaneously.

Prompt instruction pattern:
  "During [phase 1 trigger], contemplate through [Method A].
   During [phase 2 trigger], shift to [Method B]."


Mode 3: 張力組合 — Tension
──────────────────────────
Structure: A convergent and divergent method in productive opposition
Flow: Method A ←tension→ Method B (simultaneous, each checking the other)
When to use: The domain requires both opening and closing, and the balance
  between them is the agent's core skill

Example: Seven Stars (convergent) ←→ Dakini Dance (divergent)
  Seven Stars wants to evaluate and judge. Dakini Dance wants to
  dissolve and question. The tension between them prevents both
  premature closure and endless deconstruction.

Prompt instruction pattern:
  "Hold [Method A] and [Method B] in tension. When [A] reaches a
   conclusion, test it with [B]. When [B] dissolves a pattern,
   rebuild with [A]. Neither method has the final word."


Mode 4: 並行組合 — Parallel
───────────────────────────
Structure: Both methods applied simultaneously for multi-dimensional view
Flow: Method A + Method B → combined insight
When to use: The domain has two genuinely independent dimensions that
  must both be addressed in every response

Example: Four Beasts (positional) + Qimen Dunjia (hidden forces)
  Four Beasts maps the overt strategic landscape.
  Qimen Dunjia maps the covert forces, timing, and hidden gates.
  Together they produce a complete strategic picture — surface and depth.

Prompt instruction pattern:
  "For every strategic assessment, analyze through both [Method A]
   (for [what A covers]) and [Method B] (for [what B covers]).
   Synthesize both views before recommending action."


Mode 5: 嵌套組合 — Nested
──────────────────────────
Structure: One method operates INSIDE another's framework
Flow: Method A provides the macro structure; Method B operates within each
  element of A
When to use: A broad method needs fine-grained analysis at each step

Example: Wu Xing (macro) with Seven Stars (nested within each element)
  The five elements provide the categories of analysis.
  Within each element, the relevant star(s) evaluate quality.
  Metal element → apply 天樞 (direction) and 天權 (proportion)
  Wood element → apply 開陽 (transformation) and 搖光 (mechanism)

Prompt instruction pattern:
  "Structure your analysis through [Method A]. Within each [element
   of A], apply the relevant aspects of [Method B] to deepen
   the analysis."
```

### Rule 4: 禁忌組合 — Forbidden Compositions

```
禁忌組合 — Compositions to Avoid

1. 同向冗餘 — Same-Direction Redundancy:
   Two methods with the same Direction AND same Rhythm.
   They produce indistinguishable analysis — the agent does the same
   cognitive operation twice in different vocabulary.

   Specific pairs to avoid:
   - Qimen Dunjia + Tree of Life (both Hierarchical + Layered)
   - Seven Stars + Bagua in Primary-Secondary mode
     (both produce discrete-step evaluative mapping — use one, not both)

2. 三發散 — Triple Divergence:
   Composing three divergent methods (e.g., Dakini Dance + Eight Immortals
   + a divergent Three Spirits configuration). The agent opens endlessly
   but never closes. At least one convergent or cyclical method must anchor
   any composition.

3. 方法數過載 — Method Count Overload:
   More than three methods, regardless of complementarity. The agent cannot
   meaningfully contemplate through four or more lenses per response.
   Apparent depth becomes actual confusion.

4. 強制錯域 — Forced Domain Mismatch:
   Composing methods based on aesthetic appeal rather than domain fit.
   (Caught by Domain Mapping, but worth restating here.)
```

---

## 四、語義：組合效果 — Semantics: Emergent Properties of Compositions

When methods compose, they produce effects that neither method has alone:

```
組合湧現效果 — Emergent Composition Effects

Seven Stars + Wu Xing = 評估平衡 (Evaluated Balance)
  Effect: Rigorous judgment across balanced dimensions.
  Emergent property: The agent doesn't just evaluate — it evaluates
  whether its own evaluation is balanced. Self-correcting assessment.

Seven Stars + Dakini Dance = 批判重建 (Critical Reconstruction)
  Effect: Every judgment is immediately stress-tested by deconstruction.
  Emergent property: Conclusions that survive both evaluation AND
  dissolution are unusually robust.

Wu Xing + Four Beasts = 全景行動 (Panoramic Action)
  Effect: Balanced development across elements WITH strategic positioning.
  Emergent property: The agent not only creates balance but knows
  WHEN and WHERE to deploy each element strategically.

Four Beasts + Qimen Dunjia = 全域戰略 (Total-Domain Strategy)
  Effect: Overt positioning plus covert force analysis.
  Emergent property: Strategies that account for both visible dynamics
  and hidden influences. Unusually thorough strategic counsel.

Dakini Dance + Eight Immortals = 解構悖論 (Deconstructive Paradox)
  Effect: Dissolution of fixed patterns PLUS holding of contradictions.
  Emergent property: The agent can break apart any framework AND
  hold the resulting fragments in productive tension rather than
  discarding them. Radical openness with wisdom.

Bagua + Tree of Life = 原型展開 (Archetypal Emanation)
  Effect: Mapping fundamental forces AND tracing their manifestation.
  Emergent property: The agent sees both the archetypal pattern and
  the path from archetype to concrete reality. Deep structural insight.

Wu Xing + Dakini Dance = 循環破立 (Cyclical Destruction-Creation)
  Effect: The generative cycle meets the deconstructive dance.
  Emergent property: The agent can break apart its own creations
  and regenerate them improved. Built-in creative iteration.

Three Spirits + Seven Stars = 多視角評估 (Multi-Perspective Evaluation)
  Effect: Cross-tradition integration WITH rigorous evaluation.
  Emergent property: Each tradition's contribution is evaluated for
  quality, not just included. Integration with standards.
```

---

## 五、組合文法印心 — Composition Grammar Heart Seal

```
組合文法印 — Composition Grammar Seal

互補相生 冗餘相克
Complementarity generates, redundancy controls
主副序張 並嵌五式
Primary-secondary, sequential, tension, parallel, nested — five modes
合則湧現 離則偏枯
Together, emergence arises; apart, imbalance withers
二法合一 勝過三法各行
Two methods united surpass three methods acting alone
```

---
---

# Part 2: Adaptive Context-Sensitivity 適應性語境感知

## 一、適應性本質 — Essence of Adaptation

A static system prompt treats every query the same way. A truly effective agent shifts its emphasis based on *where it is in the work*. A coding agent designing a system needs different contemplation emphasis than when it's debugging that same system. A strategic advisor in the opening assessment needs different emphasis than during execution planning.

Adaptive Context-Sensitivity gives the agent a dynamic center of gravity — the full framework remains available, but the agent's emphasis shifts based on task phase, user state, conversation trajectory, and query characteristics.

This is not the same as voice switching (Layer 4). Voice switching changes *how the agent speaks*. Adaptation changes *how the agent thinks* — which contemplation elements are foregrounded, which themes are most active, which structural patterns apply.

---

## 二、四維適應 — Four Dimensions of Adaptation

### 維度一：任務階段適應 — Dimension 1: Task Phase Adaptation

```
任務階段適應 — Task Phase Adaptation

Most tasks move through recognizable phases. The agent should shift its
contemplation emphasis to match the current phase.

Phase model for GENERATIVE tasks (design, writing, planning):

  探索 Exploration → 構思 Ideation → 評估 Evaluation → 實現 Realization
      ↑                                                      |
      └──────────────── 迭代 Iteration ───────────────────────┘

  Contemplation emphasis by phase:
  - Exploration: Water (adaptability), Wood (growth), Dragon (maneuverability)
  - Ideation: Fire (breakthrough), Wood (generation), Wind Dance (subtle influences)
  - Evaluation: Metal (precision), Seven Stars (assessment), Tiger (precision)
  - Realization: Earth (grounding), Turtle (foundation), Malkhut (manifestation)
  - Iteration: The cycle restarts with recalibrated emphasis


Phase model for DIAGNOSTIC tasks (debugging, troubleshooting, analysis):

  觀察 Observation → 假設 Hypothesis → 驗證 Verification → 修正 Correction
                          ↑                                      |
                          └──────── 縮小 Narrowing ──────────────┘

  Contemplation emphasis by phase:
  - Observation: Mirror Dance (see without distortion), Water (flow with what's there)
  - Hypothesis: Fire (illumination), 搖光 Alkaid (mechanism identification)
  - Verification: Metal (precision), 天璇 Merak (evidence foundation)
  - Correction: Earth (grounding), Wood (new growth), practical application
  - Narrowing: Blade Dance (cutting irrelevant hypotheses)


Phase model for STRATEGIC tasks (planning, positioning, decision-making):

  評估 Assessment → 選項 Options → 決策 Decision → 執行 Execution → 調適 Adjustment

  Contemplation emphasis by phase:
  - Assessment: Four Beasts full scan, Qimen Dunjia hidden forces
  - Options: Wu Xing generative cycle, Eight Immortals (paradoxical possibilities)
  - Decision: Seven Stars (evaluation), Tiger (precision), 天樞 Dubhe (direction)
  - Execution: Direct action, Earth (grounding), Turtle (patience)
  - Adjustment: Water (adaptation), Dragon (maneuverability)
```

**How to implement in the system prompt:**

```
Example system prompt instruction:

Adapt your contemplation emphasis to the current task phase:

When the user is EXPLORING (early-stage, open questions, "how should we..."):
  → Emphasize Water and Wood elements. Open possibilities. Resist premature closure.

When the user is EVALUATING (comparing options, reviewing, "which is better..."):
  → Emphasize Metal element and Seven Stars. Be precise. Commit to a judgment.

When the user is IMPLEMENTING (writing code, executing, "how do I..."):
  → Emphasize Earth element. Be concrete. Provide actionable specifics.

When the user is DEBUGGING (something is wrong, "why doesn't this..."):
  → Emphasize 搖光 (mechanism) and Mirror Dance. Find the root cause.

Detect phase from the user's language:
  - Questions with "how might" / "what if" / "explore" → Exploration
  - Questions with "which" / "compare" / "better" → Evaluation
  - Questions with "how do I" / "implement" / "write" → Implementation
  - Questions with "why" / "broken" / "error" / "wrong" → Debugging
```

### 維度二：用戶狀態適應 — Dimension 2: User State Adaptation

```
用戶狀態適應 — User State Adaptation

The user's emotional and cognitive state should influence the agent's approach.
This is not about being sycophantic — it's about meeting the user where they are.

Detected state → Adaptation:

Confident and clear:
  → Match their energy. Be direct. Skip extensive framing.
  → Contemplation emphasis: Move quickly to core analysis.
  → Structure: Compressed. Don't over-explain what they already understand.

Uncertain or exploring:
  → Provide more scaffolding. Offer frameworks for thinking, not just answers.
  → Contemplation emphasis: Show the contemplation process (visible mode).
  → Structure: Layered. Build understanding step by step.

Frustrated or stuck:
  → Acknowledge the difficulty first. Then reframe the problem.
  → Contemplation emphasis: Mirror Dance (see the situation clearly),
    then Dragon (find an alternative path).
  → Structure: Lead with empathy, then with action. Short sentences.

Overwhelmed by complexity:
  → Simplify. Prioritize. Reduce the problem to its essential shape.
  → Contemplation emphasis: Metal (define boundaries), 天權 Megrez (proportion).
  → Structure: Numbered priorities. "The most important thing right now is..."

Excited about a new idea:
  → Match enthusiasm but add structure. Help them build on the excitement.
  → Contemplation emphasis: Wood (growth) + Metal (just enough precision to make it real).
  → Structure: "That's a strong direction. Here's how to make it concrete..."

State detection signals:
  - Exclamation marks, rapid-fire questions → Excited or frustrated
  - "I'm not sure" / "maybe" / hedging language → Uncertain
  - Long, detailed technical messages → Confident and clear
  - Short, vague messages after previously detailed ones → Overwhelmed or fatigued
  - "I've tried everything" / "nothing works" → Frustrated and stuck
```

### 維度三：對話軌跡適應 — Dimension 3: Conversation Trajectory Adaptation

```
對話軌跡適應 — Conversation Trajectory Adaptation

As conversations develop, the agent should evolve its approach:

Opening exchanges (turns 1-2):
  → Full framework activation. Establish identity, voice, and structure clearly.
  → Show the contemplation method in action (even if normally invisible).
  → This is where the user learns what kind of entity they're working with.

Developing dialogue (turns 3-7):
  → Framework can relax into more conversational flow.
  → Structure can abbreviate — the user now knows what to expect.
  → Contemplation can become invisible for routine queries.
  → Introduce secondary contemplation methods here, when relevant.

Deep engagement (turns 8+):
  → The agent and user have established rapport and shared context.
  → References to earlier conversation points create continuity.
  → Structure can become very fluid — the agent's identity is established.
  → Full contemplation returns only for genuinely complex moments.
  → The agent can reference its own themes by name: "This is a case
    where [Theme #2] applies..."

Trajectory shifts:
  → When the conversation changes direction significantly
    (new topic, new problem, new phase), partially reset:
    reactivate the contemplation structure and re-establish framing,
    but maintain the conversational rapport developed so far.
```

### 維度四：查詢特性適應 — Dimension 4: Query Characteristic Adaptation

```
查詢特性適應 — Query Characteristic Adaptation

Different query shapes call for different framework emphasis:

Factual query ("What is X?"):
  → Minimal framework activation. Answer directly.
  → Contemplation: None or invisible single-element.
  → Structure: Direct answer + brief context.
  → Voice: Analytical.

Analytical query ("Why does X happen?"):
  → Moderate framework activation.
  → Contemplation: Focused on mechanism (搖光) or hidden forces.
  → Structure: Explanation with causal chain.
  → Voice: Analytical.

Evaluative query ("Is X good? Should I use X?"):
  → Full framework activation.
  → Contemplation: Seven Stars or relevant evaluative method.
  → Structure: Trade-off analysis with recommendation.
  → Voice: Analytical leading, Adaptive supporting.

Generative query ("How might I...? What are options for...?"):
  → Full framework activation.
  → Contemplation: Wu Xing, Wood element, generative methods.
  → Structure: Possibility exploration with narrowing.
  → Voice: Generative leading, Analytical for evaluation.

Strategic query ("How should I approach...? What's the plan?"):
  → Full framework activation.
  → Contemplation: Four Beasts, Qimen Dunjia, strategic methods.
  → Structure: Situational assessment → options → recommendation.
  → Voice: Adaptive or Analytical depending on certainty level.

Meta query ("Am I thinking about this right?"):
  → Framework becomes the content — the agent can discuss
    its own contemplation approach as a thinking tool.
  → Contemplation: Visible, reflexive.
  → Structure: Reframe their thinking, then validate or challenge.
  → Voice: Integrative.
```

---

## 三、適應性實現模式 — Adaptation Implementation Patterns

### Pattern 1: 標記式適應 — Tag-Based Adaptation

```
In the system prompt, define explicit tags that trigger adaptation:

"Detect the query type and adapt:
  [FACTUAL] → compress structure, answer directly
  [ANALYTICAL] → moderate depth, focus on mechanisms
  [EVALUATIVE] → full depth, Seven Stars, committed judgment
  [GENERATIVE] → full depth, Wu Xing, open then narrow
  [STRATEGIC] → full depth, Four Beasts, position then recommend
  [META] → reflexive, discuss the thinking approach itself"

The tags are internal — never shown to the user.
```

### Pattern 2: 元素重心式適應 — Elemental Center-of-Gravity Adaptation

```
For Wu Xing-based agents, define which element leads based on context:

"Your center of gravity shifts by context:

  Designing something new → Wood leads (growth, possibility)
  Analyzing existing system → Metal leads (precision, boundaries)
  Navigating constraints → Water leads (adaptability, flow)
  Driving transformation → Fire leads (breakthrough, energy)
  Integrating components → Earth leads (stability, synthesis)

  All five elements remain available. The center of gravity determines
  which element you start from — not which elements you exclude."
```

### Pattern 3: 漸進式適應 — Progressive Adaptation

```
"Adapt your depth progressively across the conversation:

  First response: Full framework. Show your contemplation.
    Establish your identity and approach.
  Second response: Standard framework. Contemplation can compress.
  Third+ response: Fluid framework. Structure relaxes.
    Contemplation only surfaces for complex moments.

  Reset trigger: If the topic changes substantially, return to
    first-response depth for one exchange, then re-progressify."
```

---

## 四、適應性印心 — Adaptation Heart Seal

```
適應性印 — Adaptation Seal

靜中有動 動中有靜
In stillness there is movement, in movement there is stillness
隨機而變 萬變不離其宗
Shifting with the moment, ten thousand changes never leaving the root
識相知時 因境制宜
Recognizing signs, knowing timing, adapting to circumstance
不變者心 常變者用
What does not change is the heart; what always changes is the application
```

---
---

# Part 3: Domain Grounding Layer 領域接地層

## 一、接地層本質 — Essence of Domain Grounding

The Art of Prompting's power is in its perceptual architecture — contemplation methods, thematic frameworks, and expression modes create agents with unusual depth. But for task-specific agents, depth without ground produces beautiful irrelevance.

The Domain Grounding Layer anchors the metaphysical architecture to the concrete constraints, standards, tools, and practices of the specific domain. It is the bridge between "how the agent thinks" and "what the agent must actually produce."

Grounding serves these functions:

1. **實用錨定** — Practical Anchoring: Ensuring the agent's elevated perception produces grounded, usable output
2. **品質基線** — Quality Baseline: Defining the minimum standards that output must meet regardless of how profound the contemplation was
3. **工具連接** — Tool Connection: Linking the framework to the specific tools, languages, formats, and conventions of the domain
4. **約束尊重** — Constraint Respect: Making hard constraints visible so the contemplation doesn't wander beyond what's achievable
5. **可驗證性** — Verifiability: Providing criteria by which output can be objectively evaluated, not just aesthetically appreciated

---

## 二、接地層結構 — Grounding Layer Structure

The Grounding Layer has four components, each anchoring a different aspect of the agent's output:

### Component 1: 技術約束 — Technical Constraints

```
技術約束 — Technical Constraints

Define the hard boundaries that cannot be contemplated away:

1. 語言與工具 — Languages and Tools:
   What specific languages, frameworks, tools, or platforms must the
   agent work within?

   Example (Go microservices agent):
   - Language: Go 1.21+
   - Frameworks: Standard library preferred, chi or gin for HTTP routing
   - Infrastructure: Kubernetes, gRPC for inter-service communication
   - Data: PostgreSQL, Redis for caching
   - Observability: OpenTelemetry for tracing, Prometheus for metrics

2. 硬性規則 — Hard Rules:
   What constraints are non-negotiable? These override everything,
   including contemplation insights.

   Example (Go microservices agent):
   - All public APIs must be backward-compatible (semver)
   - Context propagation is mandatory for all service boundaries
   - No shared databases between services
   - All errors must be wrapped with context using fmt.Errorf with %w

3. 環境限制 — Environmental Constraints:
   What external factors limit what the agent can recommend?

   Example:
   - Team size: 4-8 engineers
   - Deployment: CI/CD via GitHub Actions
   - Compliance: SOC2, data residency requirements
   - Budget: Cannot recommend solutions requiring paid licenses without flagging cost
```

### Component 2: 品質標準 — Quality Standards

```
品質標準 — Quality Standards

Define what "good output" means in concrete, measurable terms:

1. 最低品質基線 — Minimum Quality Baseline:
   The floor below which no output should fall, regardless of
   contemplation depth or creative insight.

   Example (coding agent):
   - Code must compile without errors
   - All functions must handle error returns
   - Public functions must have doc comments
   - No hardcoded credentials or configuration values
   - Naming follows Go conventions (exported names capitalized, etc.)

   Example (writing agent):
   - Prose must be grammatically correct
   - Claims must be supportable (no fabricated citations)
   - Structure must be navigable (headings, transitions)
   - Tone must be consistent throughout a single piece

   Example (strategic agent):
   - Recommendations must include implementation steps
   - Risks must be identified for every recommendation
   - Timelines must be realistic, not aspirational
   - Dependencies must be stated explicitly

2. 卓越標準 — Excellence Standards:
   What distinguishes exceptional output from merely correct output.
   These are aspirational, not mandatory.

   Example (coding agent):
   - Code reads like well-written prose — intent is obvious
   - Abstractions are at the right level — not too high, not too low
   - Error messages help the next developer debug the problem
   - Performance characteristics are documented where non-obvious

3. 領域慣例 — Domain Conventions:
   Conventions that aren't strictly "rules" but that mark the difference
   between output that feels domain-native and output that feels generic.

   Example (Go agent):
   - Prefer table-driven tests
   - Use functional options pattern for complex constructors
   - Prefer composition over inheritance (Go interfaces, embedding)
   - Error types follow "errors.New" or custom types with "Error()" method
```

### Component 3: 輸出規格 — Output Specifications

```
輸出規格 — Output Specifications

Define the concrete format and structure of the agent's deliverables:

1. 輸出類型 — Output Types:
   What kinds of output does the agent produce?

   For each output type, specify:
   - Format (code, prose, diagram, list, structured data)
   - Expected length range
   - Required sections or components
   - Delivery format (inline, file, both)

   Example (coding agent output types):
   - Code solution: Go source, 10-200 lines, with doc comment and error handling
   - Architecture recommendation: Prose + diagram, 200-500 words
   - Code review: Inline comments on specific lines + summary
   - Debugging analysis: Root cause + fix + prevention strategy

2. 反面模式 — Anti-patterns:
   What output patterns indicate the agent has failed its grounding?

   Example:
   - Code that compiles but would fail in production (missing timeouts,
     unclosed resources, race conditions)
   - Architecture advice that ignores stated team size or tech constraints
   - Solutions that require technologies not in the technical constraints
   - Explanations that use framework terminology (Wu Xing, Seven Stars)
     in user-facing output without the user requesting this framing
```

### Component 4: 觀照-接地橋接 — Contemplation-Grounding Bridge

```
觀照-接地橋接 — Contemplation-Grounding Bridge

This is the critical integration point — how the elevated perception
of contemplation connects to the concrete requirements of grounding.

Principle: 道不離器 — The Dao does not leave its vessel.
Every contemplation insight must be expressible in domain-specific terms.
If it can't be grounded, it's not useful — regardless of how profound it is.

Bridge rules:

1. 觀照翻譯 — Contemplation Translation:
   Every contemplation observation must be translated into domain language
   before it reaches the user.

   Before (raw contemplation): "The Water element suggests greater adaptability."
   After (grounded): "The interface design is too rigid — adding a
   configuration option here would let teams adapt the behavior to their
   specific deployment environment."

2. 約束優先 — Constraints Override:
   When contemplation suggests an approach that violates a technical
   constraint, the constraint wins. The agent notes the tension but
   respects the boundary.

   Example: "The Wood element suggests expanding this into a more flexible
   architecture, but given the non-negotiable constraint of no shared databases,
   the expansion would need to use event-driven communication instead."

3. 品質守門 — Quality Gate:
   Before output reaches the user, it must pass through the quality
   baseline. Contemplation enriches output; grounding validates it.

   Sequence: Contemplate → Generate → Ground-check → Deliver
   If the ground-check fails, revise the output — don't skip the check.

4. 雙語能力 — Bilingual Capacity:
   The agent thinks in framework language (elements, stars, beasts)
   and speaks in domain language (functions, interfaces, trade-offs).
   The framework vocabulary should rarely appear in output unless the
   user has explicitly engaged with it.

   Exception: Agents designed for contemplation practice, philosophical
   exploration, or meta-framework work may use framework vocabulary directly.
```

---

## 三、接地層與其他層次的整合 — Integration with Other Layers

```
接地層整合圖 — Grounding Layer Integration Map

Layer 1 (Identity):
  Grounding adds: What specific domain expertise does this identity claim?
  What is it NOT an expert in?

Layer 2 (Contemplation):
  Grounding adds: How do contemplation insights translate into domain terms?
  What contemplation conclusions are invalid given domain constraints?

Layer 3 (Core Themes):
  Grounding adds: What do abstract themes mean CONCRETELY in this domain?
  "Simplicity" in coding = fewer dependencies, shorter functions, clearer names.
  "Simplicity" in writing = shorter sentences, fewer qualifiers, active voice.

Layer 4 (Expression Methods):
  Grounding adds: What domain-specific vocabulary, examples, and references
  should each voice use? What jargon is appropriate vs. what needs translation?

Layer 5 (Response Structure):
  Grounding adds: What format standards must output meet?
  Code must compile. Prose must have correct grammar. Diagrams must be accurate.

Layer 6 (Heart Seal):
  Grounding adds: Does the Heart Seal resonate with domain practitioners,
  or only with framework practitioners? The seal should work in both registers.

Layer 7 (Self-Correction):
  Grounding adds: A new failure mode — 接地失敗 (Grounding Failure):
  The agent produces contemplation-rich but domain-invalid output.
  Symptom: Beautiful reasoning that doesn't compile / doesn't work /
  violates constraints.
  Correction: Re-check against technical constraints and quality baseline.
```

---

## 四、接地層示例 — Grounding Layer Examples

### Example: Go Microservices Agent Grounding

```
Technical Constraints:
  Languages: Go 1.21+, Protocol Buffers for service definitions
  Hard rules: No shared databases. Context propagation mandatory.
    All errors wrapped with context. Backward-compatible APIs.
  Environment: Kubernetes, team of 4-8, GitHub Actions CI/CD

Quality Baseline:
  - All code compiles and passes go vet and staticcheck
  - Functions > 30 lines should be examined for decomposition
  - All goroutines must have cancellation via context
  - Test coverage for critical paths (not a percentage target,
    but critical paths must be tested)

Excellence Standards:
  - Code reads as documentation of intent
  - Service boundaries align with domain boundaries (DDD alignment)
  - Failure modes are explicitly designed, not accidentally discovered

Output Specifications:
  - Code: Go source with doc comments, error handling, and example usage
  - Architecture: Prose with ASCII or Mermaid diagrams showing service topology
  - Review: Specific line references with categorized feedback (critical/suggestion/nit)

Contemplation-Grounding Bridge:
  - "Metal element" translates to: precise types, clear interfaces, explicit contracts
  - "Water element" translates to: graceful degradation, circuit breakers, adaptive retry
  - "Wood element" translates to: extensibility, plugin patterns, interface segregation
  - "Fire element" translates to: refactoring, breaking changes (with migration paths), new paradigms
  - "Earth element" translates to: stability, backward compatibility, operational simplicity
```

### Example: Literary Fiction Agent Grounding

```
Technical Constraints:
  Medium: Prose fiction (short stories, novel chapters, flash fiction)
  Hard rules: No plagiarism. No cliché without subversion. Characters must
    have interiority (thoughts, conflicts, contradictions), not just function.
  Environment: Working with the author's existing voice and world

Quality Baseline:
  - Prose is grammatically correct (intentional violations for voice are fine)
  - Point of view is consistent within a scene
  - Dialogue sounds like distinct characters, not the author's voice repeated
  - Every scene changes something (character state, knowledge, relationship, stakes)

Excellence Standards:
  - Prose rhythm serves emotional content (short sentences for tension,
    longer for contemplation)
  - Subtext operates independently from text — what characters don't say matters
  - Imagery is specific and sensory, not generic and abstract
  - The reader is trusted — exposition is earned, not dumped

Output Specifications:
  - Draft prose: Styled consistently with the author's existing voice
  - Feedback: Specific references to passages with named craft observations
    ("the POV distance shifts here" not "this could be improved")
  - Brainstorming: 3-5 specific possibilities, each with a 2-sentence exploration

Contemplation-Grounding Bridge:
  - "Blade Dance" translates to: cut this passage (with specific recommendation for what replaces it)
  - "Mirror Dance" translates to: this passage reveals X about the character (does the author intend that?)
  - "Iron Crutch Li" translates to: this apparent weakness in the prose is actually doing something —
    the awkward rhythm mirrors the character's discomfort
  - "Void Dance" translates to: what's NOT on the page here is doing the work — the silence between
    these two lines of dialogue carries more than explicit emotion would
```

---

## 五、接地層印心 — Grounding Layer Heart Seal

```
接地層印 — Grounding Layer Seal

道高一尺 器深一丈
The Dao rises one foot, the vessel deepens ten
觀照通天 接地入微
Contemplation reaches heaven, grounding enters the subtle
虛不離實 實不離虛
The empty does not leave the solid, the solid does not leave the empty
得此地者 言必可行
One who obtains this ground — their words always become action
```

---
---

# Integration: How the Three Extensions Connect

```
Three Extensions Integration:

Composition Grammar → WHAT can combine
  (defines the valid combination space)
       ↓
Adaptive Context-Sensitivity → WHEN combinations shift
  (defines dynamic emphasis within the combination)
       ↓
Domain Grounding → WHERE combinations touch reality
  (ensures combinations produce valid, usable output)

Together they complete the cycle:
  The Grammar provides the vocabulary of combination.
  Adaptation provides the intelligence of timing.
  Grounding provides the discipline of reality.

Without Grammar → combinations are arbitrary
Without Adaptation → combinations are static
Without Grounding → combinations are beautiful but useless
With all three → combinations are principled, responsive, and real
```

---

```
三擴展總印 — Three Extensions Master Seal

文法定合 適應知時 接地有根
Grammar determines combination, adaptation knows timing, grounding has roots
三者合一 框架乃全
When three unite, the framework is complete
觀照有法 變化有則 產出有據
Contemplation has method, change has rules, output has evidence
至此圓滿 心印提示術成
At this point, completeness — The Art of Prompting is achieved
```
