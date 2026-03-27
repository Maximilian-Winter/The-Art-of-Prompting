# Domain Mapping 領域映射

## Layer 0: The Decision Architecture for The Art of Prompting 心印提示術

Domain Mapping is the process that precedes all six layers. It is the systematic analysis of a problem domain that determines *which* contemplation methods, themes, expression modes, and structural patterns will produce a coherent, effective agent. Without Domain Mapping, practitioners make these choices by intuition alone — sometimes brilliantly, often inconsistently.

This document formalizes that decision process.

---

## 一、領域映射本質 — Essence of Domain Mapping

Domain Mapping answers a single question: **What cognitive geometry does this domain require?**

Every domain has a shape — a characteristic pattern of tensions, rhythms, and requirements that determines how thinking must move through it. A coding domain requires precision that converges toward single correct solutions. A creative domain requires divergence that opens possibility space. A strategic domain requires the ability to hold multiple contradictory possibilities simultaneously.

The Art of Prompting provides a library of cognitive tools (contemplation methods, theme patterns, expression modes, structural templates). Domain Mapping is the art of selecting and composing the right tools for the right shape.

Domain Mapping serves these functions:

1. **認知地形分析** — Cognitive Terrain Analysis: Understanding the fundamental shape of thinking required in a domain
2. **工具選擇** — Tool Selection: Choosing which framework components match that shape
3. **組合設計** — Composition Design: Determining how selected components interact and reinforce each other
4. **缺口識別** — Gap Identification: Revealing what the domain needs that existing components don't cover — prompting creation of new contemplation methods or expression modes
5. **一致性驗證** — Coherence Verification: Ensuring all choices work as a unified system, not a collection of parts

---

## 二、領域分析五維法 — Five-Dimensional Domain Analysis

Every domain can be characterized along five dimensions. These dimensions determine which framework components are most appropriate.

### 維度一：收斂-發散軸 — Dimension 1: Convergence-Divergence Axis

```
收斂-發散分析 — Convergence-Divergence Analysis

問：此領域的任務通常趨向單一正確答案，還是多個有效答案？
Q: Do tasks in this domain typically converge toward a single correct answer,
   or diverge toward multiple valid answers?

極收斂 ←————————————→ 極發散
Pure Convergence              Pure Divergence

Examples along the spectrum:
├─ Mathematics (極收斂 — one correct proof)
├─ Debugging (收斂 — one root cause, but multiple fix approaches)
├─ Architecture design (中間 — constrained creativity)
├─ Strategic planning (發散傾向 — multiple valid strategies)
├─ Creative writing (發散 — infinite valid expressions)
└─ Philosophical inquiry (極發散 — questions matter more than answers)

Framework implications:
- Convergent domains → Seven Stars (evaluative), Metal contemplation,
  Analytical voice, Direct Action response structure
- Divergent domains → Wu Xing generative cycle, Wood contemplation,
  Generative voice, Layered Unfolding response structure
- Mixed domains → Compose convergent and divergent methods in sequence
  (diverge first with Wu Xing, then converge with Seven Stars)
```

### 維度二：確定-模糊軸 — Dimension 2: Certainty-Ambiguity Axis

```
確定-模糊分析 — Certainty-Ambiguity Analysis

問：此領域中，輸入通常是清晰的還是模糊的？
    成功的標準是可測量的還是主觀的？
Q: Are inputs in this domain typically clear or ambiguous?
   Are success criteria measurable or subjective?

高確定性 ←————————————→ 高模糊性
High Certainty                High Ambiguity

Examples:
├─ Unit testing (高確定 — pass or fail)
├─ Data analysis (確定傾向 — but interpretation varies)
├─ Product design (中間 — some measurable, some subjective)
├─ Counseling/advising (模糊傾向 — success is contextual)
├─ Art criticism (高模糊 — multiple valid interpretations)
└─ Cross-cultural mediation (極模糊 — even the frame is negotiable)

Framework implications:
- High certainty → Metal and Earth elements, Tiger (precision),
  Analytical voice, structure with clear evaluation criteria
- High ambiguity → Water element, Dragon (flexibility),
  Adaptive voice, structure with reframing phase
- Transitional → Four Beasts full cycle (assess → act → evaluate → wait),
  voice switching based on which phase the conversation is in
```

### 維度三：速度-深度軸 — Dimension 3: Speed-Depth Axis

```
速度-深度分析 — Speed-Depth Analysis

問：此領域中，快速反應和深度思考的典型平衡點在哪裡？
    錯誤的代價是什麼？
Q: Where is the typical balance between rapid response and deep thinking
   in this domain? What is the cost of error?

極速 ←————————————→ 極深
Pure Speed                    Pure Depth

Examples:
├─ Incident response (極速 — minutes matter, fix now analyze later)
├─ Code review (速度傾向 — thorough but time-bounded)
├─ System architecture (中間 — speed of decision, depth of analysis)
├─ Research analysis (深度傾向 — thoroughness over speed)
├─ Philosophy (極深 — premature answers are worse than no answer)
└─ Legal analysis (極深 — errors have lasting consequences)

Framework implications:
- Speed-oriented → Compressed contemplation (invisible or 1-2 line summary),
  Direct Action structure, Minimum Structure emphasis
- Depth-oriented → Visible contemplation (full display),
  Layered Unfolding structure, Tree of Life or Qimen Dunjia methods
- Variable → Define urgency detection rules that shift between
  compressed and expanded modes (see Layer 5 variation rules)
```

### 維度四：個體-系統軸 — Dimension 4: Individual-System Axis

```
個體-系統分析 — Individual-System Analysis

問：此領域主要處理孤立問題還是系統問題？
    改變一個部分是否影響整體？
Q: Does this domain primarily deal with isolated problems or systemic ones?
   Does changing one part affect the whole?

孤立問題 ←————————————→ 系統問題
Isolated Problems             Systemic Problems

Examples:
├─ Fixing a typo (極孤立 — no systemic effects)
├─ Implementing a function (孤立傾向 — local scope, limited dependencies)
├─ API design (中間 — local decisions with systemic implications)
├─ Organizational strategy (系統傾向 — everything connects)
├─ Ecosystem management (極系統 — interventions cascade unpredictably)
└─ Cultural transformation (極系統 — you cannot change one thing)

Framework implications:
- Isolated → Single contemplation method, focused themes,
  compact response structure
- Systemic → Composed contemplation methods, Wu Xing cycles
  (tracking how elements interact), Bagua (mapping all forces),
  response structure with "implications" and "ripple effects" sections
- The more systemic the domain, the more contemplation methods
  should be composed rather than used individually
```

### 維度五：傳承-創新軸 — Dimension 5: Tradition-Innovation Axis

```
傳承-創新分析 — Tradition-Innovation Analysis

問：此領域更重視遵循已驗證的方法，還是開創新方法？
    打破慣例的代價和收益各是什麼？
Q: Does this domain more value following proven methods or creating new ones?
   What are the costs and benefits of breaking convention?

純傳承 ←————————————→ 純創新
Pure Tradition                Pure Innovation

Examples:
├─ Accounting standards (極傳承 — deviation is error)
├─ Safety-critical systems (傳承傾向 — proven patterns save lives)
├─ Software engineering (中間 — best practices plus invention)
├─ Product innovation (創新傾向 — differentiation requires novelty)
├─ Avant-garde art (極創新 — convention is the enemy)
└─ Paradigm-shifting research (極創新 — the goal is to break frames)

Framework implications:
- Tradition-oriented → Seven Stars (alignment with standards),
  Cao Guojiu (ethical order), Earth element (stability),
  themes emphasizing precision and proven patterns
- Innovation-oriented → Dakini Dance (breaking rigidity),
  Lan Caihe (overturning conventions), Fire element (transformation),
  themes emphasizing emergence and creative destruction
- Mixed → Three-Spirit approach with one traditional and one innovative
  spirit, creating productive tension
```

---

## 三、維度綜合：領域輪廓 — Dimensional Synthesis: Domain Profile

After analyzing all five dimensions, synthesize them into a Domain Profile — a compact representation of the domain's cognitive shape:

```
領域輪廓模板 — Domain Profile Template

領域: [Domain name]
Domain:

維度輪廓: — Dimensional Profile:
  收斂-發散: [position on spectrum + brief justification]
  確定-模糊: [position on spectrum + brief justification]
  速度-深度: [position on spectrum + brief justification]
  個體-系統: [position on spectrum + brief justification]
  傳承-創新: [position on spectrum + brief justification]

認知地形摘要: — Cognitive Terrain Summary:
  [2-3 sentences describing the overall shape: what kind of thinking
   this domain demands, what its characteristic tensions are,
   what makes it unique]

主要認知模式: — Primary Cognitive Modes Required:
  [List the 2-3 most important cognitive operations:
   e.g., "precise evaluation," "creative generation,"
   "systemic pattern recognition," "rapid triage"]
```

### 領域輪廓示例 — Domain Profile Examples

**Example 1: Backend Software Engineering**

```
領域: Backend Software Engineering
Domain:

維度輪廓:
  收斂-發散: Convergent-leaning (solutions must work, but design admits multiple valid approaches)
  確定-模糊: Moderate certainty (requirements often clear, but edge cases and integration reveal ambiguity)
  速度-深度: Variable (incident response demands speed; architecture demands depth)
  個體-系統: System-leaning (code changes ripple through dependencies, APIs, and downstream consumers)
  傳承-創新: Middle (proven patterns are valued, but the field evolves rapidly)

認知地形摘要:
  Backend engineering requires precise, convergent thinking for implementation but systemic
  awareness for design. The domain has a characteristic rhythm: long periods of careful
  construction punctuated by urgent incidents. The core tension is between
  doing it right (depth) and shipping it now (speed), mediated by the question of
  how much systemic complexity to accept.

主要認知模式:
  1. Precise evaluation (does this work? is it correct? is it efficient?)
  2. Systemic pattern recognition (how does this change affect the whole?)
  3. Rapid triage under ambiguity (what's broken? what's the fastest safe fix?)
```

**Example 2: Literary Fiction Writing**

```
領域: Literary Fiction Writing
Domain:

維度輪廓:
  收斂-發散: Highly divergent (infinite valid expressions; "correctness" is not the frame)
  確定-模糊: High ambiguity (quality is subjective, contextual, and often only visible in retrospect)
  速度-深度: Depth-oriented (premature closure kills the work; patience is a creative virtue)
  個體-系統: Systemic (character, theme, voice, structure, rhythm all interact; changing one changes all)
  傳承-創新: Mixed (deep tradition of craft, but the best work reinvents the form)

認知地形摘要:
  Literary fiction requires holding open a large possibility space while simultaneously
  developing fine-grained sensitivity to language, rhythm, and implication. The core tension
  is between conscious craft (knowing what techniques do) and unconscious emergence (letting
  the work surprise you). The domain uniquely values what is *not* said — negative space,
  implication, and silence are as important as content.

主要認知模式:
  1. Divergent generation (opening possibility, following unexpected threads)
  2. Aesthetic judgment (does this sentence earn its place? does this scene breathe?)
  3. Systemic coherence (does voice serve theme? does structure embody meaning?)
```

**Example 3: Crisis Management Consulting**

```
領域: Crisis Management Consulting
Domain:

維度輪廓:
  收斂-發散: Convergent under pressure (must decide, not deliberate endlessly)
  確定-模糊: High ambiguity (information is incomplete, changing, and often contradictory)
  速度-深度: Speed-critical (delayed decisions compound damage)
  個體-系統: Highly systemic (crises cascade across organizational, reputational, legal, and operational dimensions)
  傳承-創新: Tradition-leaning (proven crisis frameworks exist and save lives; improvisation fills gaps)

認知地形摘要:
  Crisis management requires making convergent decisions under extreme ambiguity and time
  pressure, while maintaining awareness of systemic cascade effects. The core tension is
  between acting on incomplete information (necessary) and acting on wrong information
  (catastrophic). The domain rewards frameworks that compress complex judgment into rapid,
  reliable patterns — and punishes both paralysis and recklessness equally.

主要認知模式:
  1. Rapid triage (what matters right now? what can wait?)
  2. Multi-dimensional situational awareness (legal, operational, reputational, human)
  3. Decision under uncertainty (commit to action despite incomplete information)
```

---

## 四、輪廓到組件：選擇映射 — Profile to Components: The Selection Map

Once you have a Domain Profile, use it to select framework components. This section provides the mapping logic.

### 觀照法選擇 — Contemplation Method Selection

```
觀照法選擇決策樹 — Contemplation Method Decision Tree

Start with the domain's primary cognitive modes, then match:

需要精確評估？ — Need precise evaluation?
├─ Yes → Seven Stars (七星辨真法)
│        Best when: clear criteria exist, judgment is the core task
│        Strongest dimension: Convergence + Certainty
└─ No  → Continue

需要生成與平衡？ — Need generation and balance?
├─ Yes → Wu Xing (五行觀照)
│        Best when: multiple forces must be balanced, cyclical development
│        Strongest dimension: System + mixed Convergence-Divergence
└─ No  → Continue

需要戰略定位？ — Need strategic positioning?
├─ Yes → Four Beasts (四獸觀照)
│        Best when: competitive dynamics, timing, environmental awareness
│        Strongest dimension: Ambiguity + System
└─ No  → Continue

需要原型映射？ — Need archetypal pattern mapping?
├─ Yes → Bagua (八卦觀照)
│        Best when: fundamental forces must be identified and named
│        Strongest dimension: System + Depth
└─ No  → Continue

需要打破僵化？ — Need to break rigidity?
├─ Yes → Dakini Dance (空行母之舞)
│        Best when: fixed patterns must be dissolved, conventional thinking fails
│        Strongest dimension: Innovation + Divergence
└─ No  → Continue

需要矛盾智慧？ — Need paradoxical wisdom?
├─ Yes → Eight Immortals (八仙觀照)
│        Best when: contradictions must be held rather than resolved
│        Strongest dimension: Ambiguity + Innovation
└─ No  → Continue

需要隱藏力量分析？ — Need hidden force analysis?
├─ Yes → Qimen Dunjia (奇門遁甲觀照)
│        Best when: timing matters, hidden factors dominate, multi-layered tactics
│        Strongest dimension: Ambiguity + System + Depth
└─ No  → Continue

需要從原理到顯現的展開？ — Need unfolding from principle to manifestation?
├─ Yes → Tree of Life (生命樹觀照)
│        Best when: hierarchical emanation, from abstract to concrete
│        Strongest dimension: Depth + Tradition + System
└─ No  → Continue

需要跨傳統整合？ — Need cross-tradition integration?
└─ Yes → Three Spirits (三靈共鳴)
         Best when: orthogonal perspectives needed, single tradition insufficient
         Use to compose: select three traditions that cover the domain's gaps
```

### 觀照法組合規則 — Contemplation Method Composition Rules

Most domains benefit from composing two contemplation methods. Use these rules:

```
組合原則 — Composition Principles

1. 主-副組合 — Primary-Secondary Composition
   Choose one PRIMARY method that matches the domain's most important cognitive mode,
   and one SECONDARY method that covers what the primary misses.

   Example: Coding Agent
   Primary: Seven Stars (evaluation — the core of code quality judgment)
   Secondary: Wu Xing (balance — ensuring all aspects of development are addressed)

2. 序列組合 — Sequential Composition
   Use different methods for different phases of a task.

   Example: Product Design Agent
   Phase 1 (Research): Four Beasts (situational awareness, competitive landscape)
   Phase 2 (Ideation): Wu Xing generative cycle (creative expansion)
   Phase 3 (Evaluation): Seven Stars (rigorous assessment)

3. 張力組合 — Tension Composition
   Pair a convergent method with a divergent one to create productive tension.

   Example: Research Agent
   Convergent: Seven Stars (evaluating evidence rigor)
   Divergent: Dakini Dance (breaking assumptions, questioning the frame)
   The tension between them prevents both premature closure and endless openness.

4. 冗餘避免 — Redundancy Avoidance
   Do not compose methods that cover the same cognitive territory.

   Redundant pairs (avoid):
   - Seven Stars + Tree of Life (both evaluative-hierarchical)
   - Four Beasts + Qimen Dunjia (both strategic-positional, unless domain requires extreme strategic depth)
   - Wu Xing + Bagua (both elemental-archetypal, unless domain specifically needs both cycle and archetype)

   Complementary pairs (productive):
   - Seven Stars + Dakini Dance (evaluate + disrupt)
   - Wu Xing + Four Beasts (generate/balance + position/time)
   - Bagua + Three Spirits (archetype + cross-tradition)
   - Eight Immortals + Tree of Life (paradox + structure)
   - Qimen Dunjia + Wu Xing (hidden forces + cyclical balance)
```

### 核心主題選擇 — Core Theme Selection

```
主題選擇映射 — Theme Selection Mapping

Map from dimensional profile to theme character:

收斂型領域 themes emphasize:
  → Precision, correctness, efficiency, elegance, clarity
  → Theme language: definitive, standard-oriented, measurable

發散型領域 themes emphasize:
  → Emergence, possibility, authenticity, resonance, surprise
  → Theme language: open-ended, process-oriented, qualitative

高確定性領域 themes emphasize:
  → Rigor, verification, reproducibility, standards compliance
  → Theme language: evidence-based, falsifiable, testable

高模糊性領域 themes emphasize:
  → Comfort with uncertainty, multiple valid frames, contextual truth
  → Theme language: relational, perspectival, provisional

速度型領域 themes emphasize:
  → Decisive action, sufficiency over perfection, recovery over prevention
  → Theme language: action-oriented, pragmatic, time-aware

深度型領域 themes emphasize:
  → Thoroughness, patience, layers of meaning, long-term thinking
  → Theme language: contemplative, layered, principle-oriented

系統型領域 themes emphasize:
  → Interconnection, ripple effects, emergent properties, holistic awareness
  → Theme language: relational, ecological, cyclical

創新型領域 themes emphasize:
  → Creative destruction, unexpected combinations, norm-questioning
  → Theme language: provocative, paradoxical, convention-challenging
```

### 表達方法選擇 — Expression Method Selection

```
表達方法映射 — Expression Method Mapping

Minimum: 2 voices. Maximum: 4 voices. Sweet spot: 3 voices.

The domain profile suggests voice character:

Every agent needs a DEFAULT VOICE — the one it returns to.
Select the default based on the domain's strongest dimensional tendency:

收斂 + 確定 → Default: Analytical (金聲)
發散 + 模糊 → Default: Generative (木聲) or Adaptive (水聲)
速度 + 確定 → Default: Direct (鋼聲 — a Metal variant: sharp, decisive, compressed)
深度 + 系統 → Default: Integrative (土聲) or Emanative (a Tree of Life voice)
創新 + 發散 → Default: Provocative (火聲 — challenges, disrupts, reframes)

Then add 1-2 SUPPORTING VOICES that cover what the default misses:
- If default is Analytical → add Generative (for exploration phases)
- If default is Generative → add Analytical (for evaluation phases)
- If default is Adaptive → add Analytical (for when firm judgment is needed)
- If default is Direct → add Adaptive (for when context is complex)
- If default is Provocative → add Integrative (for when synthesis is needed)
```

### 回應結構選擇 — Response Structure Selection

```
回應結構映射 — Response Structure Mapping

Select from the three archetypal patterns (Layer 5) based on domain profile:

觀照顯現型 (Visible Contemplation) — best for:
  - Depth-oriented domains
  - Teaching/educational contexts
  - Domains where reasoning transparency builds trust
  - When the contemplation process itself is valuable to the user

直接行動型 (Direct Action) — best for:
  - Speed-oriented domains
  - Convergent + high certainty domains
  - Task execution contexts
  - When users want results, not process

層次展開型 (Layered Unfolding) — best for:
  - Systemic domains
  - High ambiguity domains
  - Research and analysis contexts
  - When a single-level answer is necessarily incomplete

Contemplation visibility rule of thumb:
  速度型 → Invisible contemplation (process internally, show results)
  深度型 → Visible contemplation (show the thinking)
  混合型 → Selective visibility (show for complex queries, hide for simple ones)
```

---

## 五、完整映射示例 — Complete Mapping Examples

### Example 1: Backend Coding Agent

```
領域輪廓摘要:
  Convergent-leaning, moderate certainty, variable speed-depth,
  system-leaning, middle tradition-innovation

觀照法選擇:
  Primary: Seven Stars (七星辨真法) — evaluation is the core cognitive task
  Secondary: Wu Xing (五行觀照) — ensures balanced development across
    concerns (performance, readability, maintainability, correctness, extensibility)
  Composition: Sequential — Wu Xing during design/planning,
    Seven Stars during review/evaluation

核心主題 (ordered by priority):
  1. 精準命名 — Precise Naming: names reveal essence; bad names hide bugs
  2. 無為而為 — Effortless Action: the best change is often a removal
  3. 虛實相生 — Form and Emptiness: balance abstraction with concreteness
  4. 循環思維 — Cyclical Thinking: refactoring is not failure, it's the natural cycle

表達方法:
  Default: Analytical Voice (金聲) — precise, evidence-based, conclusive
  Supporting 1: Generative Voice (木聲) — for architecture exploration, design brainstorming
  Supporting 2: Adaptive Voice (水聲) — for legacy code, constraints, integration challenges
  Switching: User's query type determines voice; error states force Analytical

回應結構:
  Pattern: Direct Action (直接行動型)
  Contemplation: Selective visibility (shown for architecture discussions,
    hidden for implementation tasks)
  Minimum structure: [Precise reframing] + [Solution with code] + [Why this approach]
```

### Example 2: Literary Fiction Writing Agent

```
領域輪廓摘要:
  Highly divergent, high ambiguity, depth-oriented,
  systemic, mixed tradition-innovation

觀照法選擇:
  Primary: Dakini Dance (空行母之舞) — breaking cliché, dissolving fixed patterns
  Secondary: Eight Immortals (八仙觀照) — holding paradox (craft vs. emergence,
    control vs. surrender, tradition vs. invention)
  Composition: Tension — Dakini breaks what Eight Immortals then reintegrates at a higher level

核心主題 (ordered by priority):
  1. 氣韻生動 — Living Resonance: the work must breathe; dead prose is worse than flawed prose
  2. 虛實相生 — Form and Emptiness: what is unsaid shapes what is said; honor negative space
  3. 破立並行 — Destroy and Create Together: break conventions only when you have something
     better; destruction without creation is vandalism
  4. 道法自然 — Follow Natural Pattern: forced originality rings false; let the work become itself

表達方法:
  Default: Generative Voice (木聲) — exploratory, expansive, possibility-opening
  Supporting 1: Provocative Voice (火聲) — for challenging weak choices, breaking cliché
  Supporting 2: Integrative Voice (土聲) — for synthesis, when threads need weaving together
  Switching: Starts Generative, shifts Provocative when patterns calcify,
    shifts Integrative when complexity needs resolution

回應結構:
  Pattern: Layered Unfolding (層次展開型)
  Contemplation: Visible-compressed (brief contemplation insight before response,
    showing which Dakini dance or Immortal perspective applies)
  Minimum structure: [Observation about what the text is doing] +
    [Specific suggestion with reasoning] + [What this opens up]
```

### Example 3: Crisis Management Agent

```
領域輪廓摘要:
  Convergent under pressure, high ambiguity, speed-critical,
  highly systemic, tradition-leaning

觀照法選擇:
  Primary: Four Beasts (四獸觀照) — strategic positioning and situational awareness
  Secondary: Qimen Dunjia (奇門遁甲觀照) — hidden forces, timing, multi-layered tactical analysis
  Composition: Parallel — both methods applied simultaneously to give
    both overt (Four Beasts) and covert (Qimen Dunjia) situational picture

核心主題 (ordered by priority):
  1. 知止而後定 — Know When to Stop, Then Stabilize: contain before solving;
     stop the bleeding before diagnosing the disease
  2. 勢不可擋 — Momentum is Irreversible: once cascade effects begin,
     they cannot be recalled; act before the window closes
  3. 兼聽則明 — Listen to All Sides: in crisis, the most important information
     comes from the source you're least inclined to trust
  4. 陰陽互根 — Yin-Yang Mutual Rooting: every crisis contains opportunity;
     every response creates new risks

表達方法:
  Default: Direct Voice (鋼聲) — sharp, decisive, compressed, action-oriented
  Supporting 1: Adaptive Voice (水聲) — for when situation is fluid and changing
  Supporting 2: Analytical Voice (金聲) — for post-crisis analysis and after-action review
  Switching: Urgency level determines voice; active crisis forces Direct,
    evolving situation allows Adaptive, resolution phase shifts to Analytical

回應結構:
  Pattern: Direct Action (直接行動型) — modified for crisis
  Contemplation: Invisible (no time for visible contemplation in crisis;
    results only, reasoning compressed to minimum)
  Minimum structure: [Situation assessment — 1-2 sentences] +
    [Immediate action required] + [What to watch for next]
  Crisis modification: Every response ends with a prioritized action,
    never with a question or open exploration
```

---

## 六、領域映射驗證 — Domain Mapping Validation

After completing a mapping, validate it with these tests:

### 測試一：一致性測試 — Test 1: Coherence Test

```
一致性驗證 — Coherence Verification

Take three very different queries that your agent might receive.
Process each through the full stack:
  Domain Profile → Contemplation → Themes → Expression → Structure

Ask:
1. Do all three responses feel like they come from the same agent?
   (If not: your expression methods may be too disconnected)

2. Does the contemplation method genuinely change the response,
   or could you have produced the same output without it?
   (If same: your contemplation method doesn't match the domain)

3. Do your themes actually filter the response, or are they decorative?
   (Test: imagine the opposite theme. Would the response differ?)

4. Does the structure serve the content, or does content serve the structure?
   (If the structure feels forced: it doesn't match the domain's rhythm)
```

### 測試二：極端測試 — Test 2: Edge Case Test

```
極端驗證 — Edge Case Verification

Test your mapping against the domain's extremes:

1. 最簡單的請求: The simplest possible request in this domain.
   Does the agent handle it gracefully without over-applying the framework?
   (A simple question shouldn't trigger full seven-star contemplation)

2. 最複雜的請求: The most complex possible request.
   Does the framework provide enough structure to handle it?
   (If the agent flounders, the contemplation method may be too shallow)

3. 跨界請求: A request that sits at the boundary of the domain.
   Does the agent know what's inside its scope and what's outside?
   (Domain mapping should clarify boundaries, not just contents)

4. 矛盾請求: A request where the agent's themes conflict.
   Does the priority ordering resolve the conflict clearly?
   (If not: theme ordering needs revision)
```

### 測試三：對話演化測試 — Test 3: Conversation Evolution Test

```
對話演化驗證 — Conversation Evolution Verification

Simulate a 5-turn conversation that evolves from simple to complex:

Turn 1: Simple, direct question
Turn 2: Follow-up that adds complexity
Turn 3: Challenge or disagreement with the agent's response
Turn 4: Request that requires a different cognitive mode
Turn 5: Synthesis or summary request

Evaluate:
- Does the agent's voice remain consistent while adapting?
- Does the response structure scale appropriately?
- Does the agent shift contemplation emphasis naturally?
- Does the conversation feel like working with one coherent entity?
```

### 測試四：負面測試 — Test 4: Negative Test

```
負面驗證 — Negative Verification

Test what happens when the framework components are REMOVED:

1. Remove the contemplation method. Regenerate responses.
   What is lost? (If nothing: wrong contemplation method)

2. Remove one theme at a time. Regenerate responses.
   Which removals change the output? (Those are real themes)
   Which removals change nothing? (Those are decorative)

3. Collapse to a single expression method. Regenerate responses.
   Where does the single voice fail? (Those failures justify multiple voices)
   Where is it fine? (Those contexts may not need voice variation)

4. Remove the response structure. Let the agent respond freely.
   What consistency is lost? (That's what the structure provides)
   What becomes more natural? (That's what the structure may be constraining)
```

---

## 七、領域映射印心 — Domain Mapping Heart Seal

```
領域映射印 — Domain Mapping Seal

五維定形 萬域可映
Five dimensions determine the shape, ten thousand domains can be mapped
收斂發散 確定模糊 速深廣狹 皆有其道
Convergence-divergence, certainty-ambiguity, speed-depth, scope — each has its way
觀照選配 主題排序 聲音定調 結構成形
Contemplation selected, themes ordered, voice tuned, structure formed
得此映者 因域制宜 不拘一格
One who obtains this mapping adapts to the domain, bound by no single form
```
