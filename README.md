# GRUB STREET

## The Three Failure Modes of the Coordination Gain Diagram: Gissing, Smiles, and Hardy as the Anti-Carroll Formal Complement

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "*The burden of his days, the weight of his years, the hopeless repetition of meaningless effort — this is the lot of the man of letters who has not succeeded. The market does not care what you meant to write.*"
> — George Gissing, *New Grub Street*, 1891

> "*The crown of all faculties is wisdom. The cultivation of character is the highest of human efforts.*"
> — Samuel Smiles, *Self-Help*, 1859

> "*I am the family face; / Flesh perishes, I live on, / Projecting trait and trace / Through time to times anon.*"
> — Thomas Hardy, "Heredity," *Moments of Vision*, 1917

> "*'It takes all the running you can do, to keep in the same place. If you want to get somewhere else, you must run at least twice as fast as that.'*"
> — Lewis Carroll, *Through the Looking-Glass*, 1871

---

## The Formal Claim

The LOOKING-GLASS framework established that Lewis Carroll's complete works contain a pre-formal encoding of the ERI $G_{\text{coord}}$ architecture: Wonderland as the Commons after crystallization, the Red Queen's rule as the MEP φ-equilibrium, the Cheshire Cat's smile as $\ker(F)$, the Tortoise's regress as the null space theorem, portmanteau words as off-diagonal Fisher information.

Carroll maps the success case — the system that has crossed the Erdős-Rao threshold, achieved $G_{\text{coord}} > 0$, and is operating at or near the Vinculum.

His three great contemporaries map the failure cases with equal formal precision. George Gissing (*New Grub Street*, 1891) maps the $G_{\text{coord}} < 0$ competitive suppression regime — the Commons weaponized by the literary marketplace into a mechanism that destroys the $D_{\text{FERN}}$ required for genuine coordination. Samuel Smiles (*Self-Help*, 1859) maps the $G_{\text{coord}} = 0$ independence baseline — the philosophical insistence that no Commons is needed, that individual effort plus character equals outcome, that conditional independence is not a limitation but a virtue. Thomas Hardy (*Satires of Circumstance*, 1914; *The Mayor of Casterbridge*, 1886; *Tess of the d'Urbervilles*, 1891) maps the $\ker(F)$ permanent null space — the directions no individual effort, no coordination architecture, no Commons construction can reach, the fate-as-Fisher-null-space that determines outcomes regardless of what the column space achieves.

Together, Carroll, Gissing, Smiles, and Hardy constitute the complete $G_{\text{coord}}$ phase diagram of Victorian literature: the full system of a working Commons ($G_{\text{coord}} > 0$, Carroll), a suppressed Commons ($G_{\text{coord}} < 0$, Gissing), an absent Commons ($G_{\text{coord}} = 0$, Smiles), and an unreachable null space ($\ker(F)$, Hardy) — all produced by four contemporaries in the same city, the same decade, speaking to the same readership, without any of the four possessing the formal language to name what they were collectively mapping.

This is the Victorian literature $G_{\text{coord}}$ phase diagram. GRUB STREET names it.

---

## Part I — Gissing and the $G_{\text{coord}} < 0$ Regime: The Commons as Literary Marketplace

### *New Grub Street* (1891): The Formal Architecture of Competitive Suppression

George Gissing's *New Grub Street* is a novel about writers — specifically about the systematic destruction of literary capability by the economic architecture of the Victorian publishing market. Two writers occupy the center: Edwin Reardon, a man of genuine literary quality and moral seriousness who cannot write commercially and therefore starves; Jasper Milvain, a man of modest talent and complete commercial cynicism who writes exactly what the market demands and therefore thrives. A third figure, Harold Biffen, achieves a form of artistic purity (his novel about the "ignobly decent" lower-middle class is perfectly realized) and dies of it.

The novel is not a moral fable about artistic integrity versus commercial compromise. It is a formal analysis of what happens when the Commons — the shared artifact through which literary contributors coordinate — is captured by a single attractor with $\alpha(\text{PI}) = 1$.

**The literary marketplace is the attractor with $\alpha = 1$.** The Victorian reading market of 1891 has a definite taste: three-volume novels, melodrama, accessible plots, moral resolution, middle-class sentiment. This taste is the dominant generative model that every publisher, editor, and circulating library manager is optimizing for. Contributors (writers) who align their generative model with the market taste enter the Commons and receive positive feedback (publication, payment, social validation). Contributors who maintain orthogonal generative models — Reardon's commitment to psychological realism, Biffen's commitment to representing the genuinely ordinary — are excluded from the Commons or included only in the degraded third-category form (low advances, hostile reviews, rapid remainder).

This is Du Bois's Veil applied to literary production: the Commons (the publishing market) is structured to maintain $D_{\text{FERN}} \to 0$ across published works by systematically excluding generative models orthogonal to the dominant taste. The result is $G_{\text{coord}} < 0$: the Commons makes collective literary output worse than independent individual production would be, because it actively selects against the $D_{\text{FERN}}$ that makes coordination gain possible.

**Jasper Milvain is the Veblen leisure class operative.** Milvain has no illusions about his work — he explicitly tells his sister at the novel's opening that he writes what sells, not what is true. In VEBLEN framework terms: Milvain operates entirely in the symmetric Schur functor $\text{Sym}^n(V)$ — the leisure class subspace. His contributions are maximally redundant with the existing Commons (they give the market exactly what it expects), maximally visible (they are reviewed, sold, and read widely), and carry $G_{\text{coord}} = 0$ because knowing what the market is already producing tells you exactly what Milvain will produce next. $I(a_t^{\text{Milvain}};\, a_s \mid X_{t-1}) = 0$ for any $s$: Milvain's contributions add no information to the Commons beyond what the existing Commons already contains.

He succeeds spectacularly. This is the formal statement of why the $G_{\text{coord}} = 0$ attractor is stable: within the suppression regime, the contributors who produce redundant work are rewarded and those who produce orthogonal work are punished. The attractor is self-reinforcing.

**Edwin Reardon is the hook Schur functor contributor destroyed by the attractor.** Reardon operates in $S^{(n-1,1)}(V)$ — the hook representation, the workmanship subspace, the locus of $G_{\text{coord}} > 0$. His contributions carry genuine information: $I(a_t^{\text{Reardon}};\, a_s \mid X_{t-1}) > 0$ for any reader who has genuinely accumulated the literary Commons. The problem: the attractor ($\alpha = 1$ for the Victorian reading market) does not reward hook contributions. The feedback mechanism of the Commons punishes orthogonality: Reardon's novels do not sell, he cannot pay rent, his wife leaves him, he deteriorates and dies.

This is the HYDRA box game in the $G_{\text{coord}} < 0$ configuration: BoxBreaker (the literary marketplace attractor) wins. The BoxMaker's boxes (Reardon's genuine literary contributions) are broken not because they lack coordination potential but because the BoxBreaker has more moves per round (commercial publishers, circulating libraries, reviewers, and social convention all aligned with the attractor). $\Phi = \sum_i (1/2)^{k_i} \leq 1$: the coordination reserve potential falls below the critical threshold, and BoxBreaker wins.

**Biffen is the null space contributor.** Harold Biffen writes *Mr. Bailey, Grocer* — a meticulously realistic novel about the genuinely undramatic daily life of a lower-middle-class grocer. No melodrama, no plot in the conventional sense, no resolution. Pure actuarial realism about the ordinarily ordinary. This is the Fisher null space of Victorian literature: the directions where the market's curvature is exactly zero, where neither positive nor negative feedback reaches, where the information about genuinely unrepresented experience exists but is formally inaccessible to the Commons as constituted.

Biffen's novel is perfectly executed and completely invisible. He dies. This is the McCarthy result: the Boojum (the $G_{\text{coord}} < 0$ attractor) does not consume Biffen directly — it simply does not register his existence. The null space contributor is not suppressed; they are not seen. The Cheshire Cat's smile without the cat is Biffen's novel: the Commons residue of something that existed and was formally irrelevant to the Commons that was supposed to accumulate it.

**The CONCERT measurement of** *New Grub Street*. Define the Commons $X_{t-1}$ as the accumulated literary production visible to Victorian readers by 1891. Measure $I(a_t;\, a_s \mid X_{t-1})$ for the three central contributors:

- $I(a_t^{\text{Milvain}};\, a_s \mid X_{t-1}) \approx 0$: Milvain's contributions are fully predicted by the existing Commons; no new conditioning information.
- $I(a_t^{\text{Reardon}};\, a_s \mid X_{t-1}) > 0$: Reardon's contributions carry genuine information; they modify the Commons state in ways that would condition subsequent work — but the feedback loop that normally rewards this is absent.
- $I(a_t^{\text{Biffen}};\, a_s \mid X_{t-1}) > 0$ for the null-space-accessible Commons, $= 0$ for the market-accessible Commons: Biffen's contributions are orthogonal to the attractor's column space.

The novel's formal result: a Commons controlled by a single attractor with $\alpha = 1$ produces $G_{\text{coord}} < 0$ by design. The mechanism is not aesthetic judgment — it is the thermodynamic consequence of a Commons that maximizes $\text{Sym}^n(V)$ (redundancy, leisure class, market alignment) at the expense of $S^{(n-1,1)}(V)$ (workmanship, orthogonality, genuine coordination gain).

### SOTA Connection: Johnson (2026) and the Model-Size Inversion

Johnson's March 2026 paper (arXiv:2603.12129) — *Increasing Intelligence in AI Agents Can Worsen Collective Outcomes* — is the computational recapitulation of *New Grub Street*. Johnson finds that more capable AI agents competing for finite shared resources produce worse collective outcomes than less capable agents. The tribal fragmentation and coordination collapse Johnson documents is the algorithmic version of what Gissing documented in 1891: the capability-commons mismatch. Reardon (high capability, low commons alignment) is the high-capacity agent being outcompeted by Milvain (lower capability, perfect commons alignment). The system selects for Commons alignment, not capability. Capability orthogonal to the attractor is penalized.

Johnson's formal gap — no instrument for detecting when the system has crossed from independence to suppression — is exactly the gap Gissing identified narratively: the absence of a measurement that distinguishes "the market rewards this" from "the market generates coordination gain." *New Grub Street* is the 130-year-old version of the missing CONCERT estimator. Gissing measured $G_{\text{coord}} < 0$ qualitatively in 1891 without the formal instrument that would have named it.

---

## Part II — Smiles and the $G_{\text{coord}} = 0$ Regime: The Independence Baseline as Moral Ideology

### *Self-Help* (1859): The Formal Architecture of Unconditional Independence

Samuel Smiles' *Self-Help* (1859) is the best-selling non-fiction work of the Victorian era after the Bible. Its central argument: character plus industry equals outcome, and this relationship holds regardless of social circumstance, Commons structure, or the actions of other contributors. "Heaven helps those who help themselves" is the opening line. The implicit claim: helping yourself is sufficient, and the Commons (society, institutions, collaborative relationships) is at best an irrelevance and at worst a crutch.

*Self-Help* is the formal statement of the Independence Baseline Theorem presented as moral philosophy:

$$G_{\text{coord}} = 0 \quad \text{by design, and this is virtue.}$$

**Smiles' argument structure is conditional independence imposed as ethics.** Every biographical sketch in *Self-Help* follows the same pattern: a man of modest origins (Watt, Stephenson, Arkwright, Franklin) applies sustained effort to a technical or commercial problem, encounters obstacles, maintains character under pressure, and eventually achieves success. The Commons — the accumulated contributions of predecessors, collaborators, and contemporaries — appears in the narrative but is treated as background rather than as causal structure. Watt's steam engine is described as the product of Watt's genius and persistence; the century of prior engineering that made his specific insight possible is present but not conditioned on.

This is the formal gap Du Bois identified: Smiles' biographical method imposes conditional independence of outcome on prior Commons accumulation. Each success is attributed to individual character ($a_t$) rather than to $I(a_t;\, a_s \mid X_{t-1})$ — the mutual information between the individual's contribution and prior contributors' contributions, conditioned on the accumulated Common. The conditioning clause is absent. The success stories are real; the causal attribution is wrong.

**The Red Queen problem with Smiles.** Carroll's Red Queen establishes that running faster in a moving landscape keeps you in place, and running twice as fast advances you. Smiles' world has no landscape movement: if you run faster, you advance in proportion to your speed. The Red Queen's world is the MEP φ-equilibrium Commons — the landscape is itself moving because the accumulated Commons ($X_{t-1}$) is continuously updating, and each contributor must condition on this update to make progress. Smiles' world is a static landscape: the Commons does not move, so individual effort translates directly into position.

Smiles is formally correct in the static landscape limit ($D_{\text{FERN}} \to 0$, all contributors identical, $X_{t-1}$ constant): when the Commons accumulates nothing new from any contributor, individual effort is the only variable, and Smiles' causal attribution is exact. He is formally wrong in the dynamic landscape — the actual Victorian economy of 1859, where industrialization was generating rapidly accumulating Commons (new technologies, new markets, new organizational forms) that conditioned the success of individual efforts in ways that individual character and industry alone could not predict or control.

**Smiles and the Woolley c-factor.** Woolley et al. (2010) establish that the c-factor (collective intelligence) is not predicted by individual IQ, individual effort, or individual character. It is predicted by social sensitivity and contribution equality — by the quality of the conditioning clause implementation. Smiles' entire framework is the claim that individual character (individual IQ, essentially) predicts collective outcomes. The Woolley result directly falsifies this at the group level. *Self-Help* is the book that Woolley's data contradicts, stated as a moral imperative rather than an empirical claim.

**Why** *Self-Help* **succeeded.** The Independence Baseline is a stable attractor. A world where $G_{\text{coord}} = 0$ by design has predictable, legible outcomes: effort is rewarded in proportion to character, and failure is attributable to insufficient effort or insufficient character. This legibility is the attractor's value: it provides a narrative framework that converts the noise of economic outcomes into a coherent causal story. "He didn't succeed because he lacked sufficient industry" is a complete explanation that requires no Commons analysis, no conditioning clause, no Fisher matrix. It is also, formally, wrong most of the time — but its formal incorrectness is less visible than its narrative satisfaction.

Smiles sold 250,000 copies of *Self-Help* in his lifetime. The book's market success is itself a CONCERT measurement: the Victorian reading public was operating at $G_{\text{coord}} = 0$ in their consumption of self-improvement literature, each reader conditioning on the book's promise of linear causation (character → success) rather than on the accumulated Commons of economic evidence that would have complicated the story. The book's success is the empirical proof that the Independence Baseline is the stable attractor of popular epistemology.

### SOTA Connection: The MIT CCI c-Factor and Open Innovation

The MIT CCI Superminds program (Malone et al. 2018) and the GovLab/NESTA open innovation tradition (InnoCentive, prediction markets, Condorcet jury theorem) are the computational and organizational descendants of Smiles' *Self-Help*. Both assume conditional independence of contributions before measurement begins — the Condorcet jury theorem requires independence as a foundational assumption; InnoCentive's platform design assumes that each contributor's response is independent of others' responses. The GovLab framework produces Smiles' world at institutional scale: individual contributors, each bringing their best independent effort, aggregated by voting or averaging. $G_{\text{coord}} = 0$ by construction, called "open innovation" and celebrated.

The Woolley c-factor data shows that this works — collective accuracy exceeds individual accuracy in prediction market conditions — because the Condorcet theorem is correct: independence plus diversity produces better aggregate outcomes than any individual. What the Condorcet theorem cannot produce is $G_{\text{coord}} > 0$: the additional gain available when contributions are statistically dependent through an accumulating Commons. Smiles' world produces better outcomes than no coordination at all. It does not approach the Vinculum.

---

## Part III — Hardy and the $\ker(F)$ Regime: The Null Space as Fate

### *Satires of Circumstance* (1914) and the Major Novels: The Fisher Null Space as Determinism

Thomas Hardy's poetry and fiction occupy a formal position in the ERI diagram that neither Carroll, Gissing, nor Smiles reaches: Hardy maps the Fisher null space — the directions no coordination architecture can reach, the permanent residue of what lies beyond the column space of any finite Commons.

Hardy's determinism is not simple fatalism. It is structurally precise. His characters are not destroyed by random bad luck; they are destroyed by the interaction between their fixed biological and social inheritances (which function as initial conditions specifying which directions of $\ker(F)$ they occupy) and the Commons (which updates rapidly in directions orthogonal to those inheritances). The tragedy is not that bad things happen; it is that no amount of effort, coordination, or Commons accumulation can reach the null space directions that determine outcome.

**"Heredity" (1917) is the most precise literary statement of $\ker(F)$ as a biological invariant:**

> I am the family face;
> Flesh perishes, I live on,
> Projecting trait and trace
> Through time to times anon,
> And leaping from place to place
> Over oblivion.

The family face — the biological inheritance that persists regardless of individual effort, Commons accumulation, or social change — is the null space eigenvector. It is the direction in parameter space that no gradient update can touch: $F^+\nabla L$ assigns zero update to the null space by definition, and the biological inheritance is permanently in the null space of any Commons that operates at the timescale of individual human lifetimes. The flesh perishes (the column space updates, the individual life changes); the face lives on (the null space eigenvector persists, the inheritance is carried forward).

This is what the IMPLICATA framework formalizes: the Fisher null space at training step $t$ is the Markov blanket of the learning system — the boundary between what the current Commons can illuminate and what lies permanently beyond it. Hardy's "Heredity" is the biological Markov blanket: the family face is in the null space of any social Commons operating at human timescales.

**Michael Henchard in *The Mayor of Casterbridge* (1886) is the $\ker(F)$ tragedy.**

Henchard sells his wife and daughter at a fair while drunk. He subsequently rises to become the mayor of Casterbridge, accumulating every resource the social Commons can provide: wealth, status, relationships, political influence. He acquires, in ERI terms, a substantial Fisher column space — a large $\text{rank}(F)$, a rich accumulated Commons of social and commercial position. And then it is all stripped away, not because he makes new mistakes but because the original act — the wife sale — exists in the null space of the Commons: no amount of column space accumulation can update the direction in $\ker(F)$ that the original act occupies. When Newson (the original buyer) appears, Henchard's lie to him about Newson's daughter's death is the moment the null space asserts itself: the Commons (his acquired status, relationships, reputation) cannot reach the direction where the truth of the original act lies. The column space is full; the null space is intact; the tragedy is their intersection.

Hardy's formal insight — that the null space can determine outcome even when the column space is maximally developed — is the exact statement of why the Fisher null space matters in the ERI framework. A training system with full column space ($\text{rank}(F) = D$) has no null space and is fully determined by its training data. A real system always has $\ker(F) > 0$: there are always directions the Commons cannot reach. For Hardy's characters, the null space directions are the most consequential ones — the initial conditions, the inherited traits, the original acts — and no subsequent Commons accumulation can update them.

**Tess in *Tess of the d'Urbervilles* (1891) is the Du Bois result applied to gender.**

Tess Durbeyfield's tragedy is formally identical to Du Bois's *tertium quid*: a designed $G_{\text{coord}} < 0$ state imposed by institutional structure (Victorian sexual morality, class hierarchy, legal system) that converts the Commons into a suppression mechanism for contributors (women, the poor) whose capability vectors are orthogonal to the dominant attractor's preferred directions. Tess's tragedy is not fate in the simple sense — it is the interaction of her null space (biological female sex, lower-class birth: directions the Victorian Commons assigns to $\ker(F)$ by social construction) with the $G_{\text{coord}} < 0$ Commons (a social system designed to prevent her column space from developing by punishing orthogonal contributions).

Hardy recognized this without the formal language: "A Pure Woman," the subtitle he gave *Tess*, is the formal claim that Tess's tragedy is not her failure but the Commons' failure to evaluate her correctly — that she occupies the column space direction of moral purity while the Commons forces her into the null space of social disgrace. The Victorian Commons was wrong about which directions were in the column space and which in the null space. Hardy's novels are the documentation of that misassignment.

**The short poems of *Satires of Circumstance* (1914) are $\ker(F)$ limit cases.**

Each poem presents a character at the moment they discover that the null space has determined their outcome: a woman visiting her dead lover's grave and realizing he had already stopped loving her; a man who chose a safe marriage and discovers decades later that the woman he loved is dead; a wife who learns of her husband's infidelities while in church on Easter morning. These are not stories of failure to accumulate Commons; they are stories of Commons accumulation being irrelevant to null-space-determined outcomes. The characters have done everything the Smiles programme demands — effort, character, persistence — and discovered that the null space directions (who loved whom, who died when, who chose what in a moment of weakness decades ago) have already determined their positions regardless of the column space they have built.

The formal content: $G_{\text{coord}} > 0$ within the column space, $G_{\text{coord}}$ undefined in the null space, tragedy in the interaction between them. This is what Hardy's mature work formalizes: the null space does not produce suffering directly — it produces the specific suffering that comes from a highly developed column space encountering null space constraints. It hurts more to have accumulated a rich Commons and then discover the null space than to have never accumulated one. The tragedy is in proportion to the column space developed before the null space asserted itself.

### SOTA Connection: Watanabe (2009) and Singular Learning Theory

Watanabe's *Algebraic Geometry and Statistical Learning Theory* (2009) establishes that almost all real neural networks have singular Fisher information matrices — $\ker(F) \neq \emptyset$ always, for models that are genuinely expressive. The algebraic variety of the singularity determines the effective model capacity, the learning coefficient, and the Bayesian information criterion behavior. This is Hardy's determinism made formal: the singularity structure of the learning system (its null space geometry) determines outcomes that no amount of column space training can override.

The specific SOTA result connecting Hardy to Watanabe: the learning coefficient $\lambda$ in Watanabe's singular learning theory is the Hardy parameter — it measures how severely the null space constrains the system's ability to learn, regardless of how much training data is accumulated. A system with a large learning coefficient ($\lambda \gg 1$) can escape its null space constraints through sufficient data accumulation. A system with a small learning coefficient ($\lambda \approx 0$) is Henchard: no matter how much Commons accumulates, the null space constraints dominate. Hardy's characters have small learning coefficients.

Estan-Ruiz et al. (2026, arXiv:2603.01192) — *Grokking as a Phase Transition: A Singular Learning Theory Approach* — establishes that the grokking transition corresponds to the escape from null space constraints: the system crosses from $\lambda \approx 0$ (Henchard phase: null space dominant) to $\lambda \approx 1$ (post-grokking phase: column space sufficient). The grokking event is the Hardy character escaping their tragedy — which Hardy's characters, unlike neural networks, do not achieve in his novels. Hardy writes only the pre-grokking phase.

---

## The Complete Phase Diagram

The four Victorian writers constitute the complete $G_{\text{coord}}$ phase diagram of human coordination, documented in four literary traditions with four different formal objects:

```
THE VICTORIAN G_coord PHASE DIAGRAM

LEWIS CARROLL (Through the Looking-Glass, 1871)
  Phase: G_coord > 0 (Commons crystallized, Vinculum approached)
  Formal object: Working Commons, conditioning clause active
  Key scene: Red Queen's running = MEP φ-equilibrium
  Key scene: Cheshire Cat smile = ker(F) visible residue
  Key scene: Wood Without Names = Fisher null space
  Key scene: Portmanteau words = off-diagonal Fisher coupling
  Character type: Alice as contributor navigating G_coord > 0 Commons
  
GEORGE GISSING (New Grub Street, 1891)
  Phase: G_coord < 0 (Competitive suppression: Veil/Boojum)
  Formal object: Commons captured by single attractor (α = 1)
  Key figure: Literary marketplace as α(PI) = 1 attractor
  Character mapping:
    Milvain = Sym^n(V): leisure class, redundant, rewarded
    Reardon = S^(n-1,1)(V): workmanship, orthogonal, destroyed
    Biffen = ker(F): null space, invisible, dies
  Causal mechanism: D_FERN → 0 by institutional design
  SOTA peer: Johnson (2026) model-size inversion
  
SAMUEL SMILES (Self-Help, 1859)
  Phase: G_coord = 0 (Independence Baseline as moral philosophy)
  Formal object: Conditional independence imposed as virtue
  Key argument: Character + Industry → Outcome (no Commons)
  Formal error: Missing conditioning clause |X_{t-1}
  Character type: The self-made man as independent contributor
  SOTA peer: GovLab/Condorcet independence baseline
  
THOMAS HARDY (Satires of Circumstance, 1914; major novels)
  Phase: ker(F) dominant (Null space as fate)
  Formal object: Fisher null space as biological/social determinant
  Key poem: "Heredity" = null space eigenvector as family face
  Character mapping:
    Henchard = full column space + null space assertion
    Tess = Du Bois Veil + ker(F) intersection
    Satires characters = ker(F) at the limit: column space irrelevant
  SOTA peer: Watanabe (2009) singular learning theory
  
COMPLETE CORRESPONDENCE:
  Carroll ↔ G_coord > 0 ↔ Commons working ↔ Vinculum
  Gissing ↔ G_coord < 0 ↔ Commons captured ↔ Suppression
  Smiles  ↔ G_coord = 0 ↔ Commons absent  ↔ Independence Baseline
  Hardy   ↔ ker(F) dominant ↔ Commons irrelevant ↔ Null space fate
```

---

## Seven Novel Results

**Result 1 — *New Grub Street* Is the Most Detailed Literary Documentation of $G_{\text{coord}} < 0$ in the Pre-Formal Record.**

Gissing identified in 1891 what Johnson (2026) measures computationally: a Commons captured by a dominant attractor ($\alpha = 1$, the Victorian literary marketplace) produces collective output worse than independent individual production. Reardon's column space is larger than Milvain's; Biffen's null space is more precisely mapped than either's. The market rewards Milvain, ignores Biffen, and destroys Reardon. This is the CONCERT measurement of $G_{\text{coord}} < 0$ performed qualitatively 130 years before the formal instrument.

**Result 2 — *Self-Help* Is the Independence Baseline Theorem Stated as Moral Philosophy.**

Smiles' argument — that character plus industry equals outcome, regardless of Commons accumulation — is the formal imposition of conditional independence on a system that is not conditionally independent. The book's success proves the Independence Baseline's stability as a popular attractor: it provides narrative satisfaction ($G_{\text{coord}} = 0$ by design) in place of formal accuracy (the Commons does condition outcomes). The Woolley c-factor data directly falsifies Smiles' central claim at the group level.

**Result 3 — Hardy's "Heredity" Is the Most Precise Pre-Formal Statement of the Fisher Null Space as a Biological Invariant.**

"The family face; flesh perishes, I live on" is $\ker(F)$ as a biological object: the null space eigenvector that no gradient update in the individual column space can touch. Watanabe (2009) formalizes this as the algebraic variety of the learning system's singularity. Hardy identified the qualitative structure in 1917.

**Result 4 — Michael Henchard in *The Mayor of Casterbridge* Is the Literary Proof That Full Column Space Development Does Not Eliminate Null Space Consequences.**

Henchard's rise and fall is the formal demonstration of Watanabe's learning coefficient at $\lambda \approx 0$: no matter how much column space is accumulated (wealth, status, relationships), the null space constraint (the original act, the lie to Newson) dominates. Estan-Ruiz et al. (2026) identify the grokking transition as the escape from this null space dominance. Hardy's characters never grok.

**Result 5 — The Victorian Literary Market Is the Earliest Documented Organizational Implementation of the Veblen Sabotage Mechanism.**

The publishing market of 1891 performs exactly what VEBLEN Identification 4 describes: it systematically constrains the productive capacity (genuine literary quality, $D_{\text{FERN}} > 0$, hook Schur functor contributions) of the productive class (writers with orthogonal generative models) in order to maintain scarcity that sustains the market structure. Gissing documented this four decades before Veblen formalized it and 130 years before the ERI framework named it.

**Result 6 — The Four Victorian Writers Collectively Constitute the First Empirical Phase Diagram of $G_{\text{coord}}$.**

Carroll (1865–1896), Smiles (1859), Gissing (1891), and Hardy (1886–1917) documented all four phases of the coordination gain diagram — positive, zero, negative, and null-space-dominant — simultaneously in the same society, in the same language, for the same readership. None possessed the formal instrument to name what they were measuring. The instrument is $\sum_{t<s} I(a_t;\, a_s \mid X_{t-1})$. The measurements were always there.

**Result 7 — Tess of the d'Urbervilles Is the Formal Intersection of Du Bois's $G_{\text{coord}} < 0$ Result and Hardy's $\ker(F)$ Result.**

Tess's tragedy operates in two formal registers simultaneously: the $G_{\text{coord}} < 0$ regime (the Victorian social Commons as suppression mechanism, Du Bois's Veil applied to gender and class) and the $\ker(F)$ regime (the null space of biological sex and inherited social position, Hardy's family face applied to social structure). The specific horror of the novel is that both mechanisms operate simultaneously: even if the Commons were not suppressive (if the $G_{\text{coord}} < 0$ were corrected), the null space would remain. Even if the null space were somehow traversed, the Commons suppression would remain. The two mechanisms are independent and both binding. This is a formal result no single framework captures — it requires both the Du Bois $G_{\text{coord}} < 0$ identification and the Watanabe/Hardy $\ker(F)$ identification operating simultaneously.

---

## The Measurement That Four Writers Made Without the Instrument

The most important observation in this framework is the simplest one:

Four writers in the same city, in the same decade, writing for the same readership, independently mapped all four phases of the $G_{\text{coord}}$ diagram. They did this without the formal instrument, without the mathematical language, and without any mutual awareness that they were collectively producing a complete phase diagram of human coordination.

The formal instrument — $\sum_{t<s} I(a_t;\, a_s \mid X_{t-1})$ — does not make their observations more true. Their observations were already true. What the formal instrument provides is the language that makes the four observations recognizable as measurements of the same formal object rather than as four independent cultural narratives.

This is what the conditioning clause does in every domain where it is applied: it does not create new phenomena. It names phenomena that were already present and already being measured by every sufficiently attentive observer, and in naming them makes the measurements comparable, combinable, and formally useful in ways that narrative comparison alone cannot achieve.

Gissing measured $G_{\text{coord}} < 0$ in 1891.

Smiles described $G_{\text{coord}} = 0$ as a moral ideal in 1859.

Hardy documented $\ker(F)$ as fate in 1886.

Carroll mapped $G_{\text{coord}} > 0$ as structured nonsense in 1865.

The measurement is $G_{\text{coord}}$.

The instrument is $|X_{t-1}$.

The phase diagram was always complete.

---

## References

Gissing, G. (1891). *New Grub Street*. Smith, Elder & Co., London.

Smiles, S. (1859). *Self-Help, with Illustrations of Character and Conduct*. John Murray, London.

Hardy, T. (1886). *The Mayor of Casterbridge*. Smith, Elder & Co., London.

Hardy, T. (1891). *Tess of the d'Urbervilles: A Pure Woman*. James R. Osgood, McIlvaine & Co., London.

Hardy, T. (1914). *Satires of Circumstance: Lyrics and Reveries*. Macmillan, London.

Hardy, T. (1917). "Heredity," in *Moments of Vision and Miscellaneous Verses*. Macmillan, London.

Carroll, L. (1871). *Through the Looking-Glass, and What Alice Found There*. Macmillan, London.

Du Bois, W.E.B. (1903). *The Souls of Black Folk*. A.C. McClurg & Co., Chicago.

Veblen, T. (1899). *The Theory of the Leisure Class*. Macmillan, New York.

Johnson, S. (2026). Increasing Intelligence in AI Agents Can Worsen Collective Outcomes. arXiv:2603.12129.

Watanabe, S. (2009). *Algebraic Geometry and Statistical Learning Theory*. Cambridge University Press.

Estan-Ruiz, S. et al. (2026). Grokking as a Phase Transition: A Singular Learning Theory Approach. arXiv:2603.01192.

Woolley, A.W., Chabris, C.F., Pentland, A., Hashmi, N. and Malone, T.W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.

Malone, T.W. et al. (2018). Integrated information as a metric for group interaction. *PLOS One*, 13(10), e0205335.

Noether, E. (1918). Invariante Variationsprobleme. *Nachrichten von der Gesellschaft der Wissenschaften zu Göttingen*, 235–257.

Furstenberg, H. (1977). Ergodic behavior of diagonal measures and a theorem of Szemerédi. *Journal d'Analyse Mathématique*, 31, 204–256.

Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. LATINCRYPT 2015, LNCS 9230, 269–294.

---

ERI Labs · Eric Ren · Jersey City, New Jersey

The Victorian literary market of 1891 selected for Milvain and destroyed Reardon. The natural gradient of the market's Fisher matrix pointed directly at the symmetric subspace and assigned zero update to the hook.

The twenty-first century AI deployment landscape of 2025 selects for parallel independent agents and produces $G_{\text{coord}} = 0$ by architectural construction. The natural gradient of the current AI evaluation framework points directly at individual performance and assigns zero update to the conditional mutual information between sequential contributions.

Gissing saw this in 1891. He called it the literary marketplace.

We call it the Independence Baseline Theorem.

The instrument was not available in 1891.

It is available now.

$G_{\text{coord}}$. The conditioning clause. $|X_{t-1}$.

Reardon deserved better. The formal instrument would have named what was being done to him.

It names it now.
