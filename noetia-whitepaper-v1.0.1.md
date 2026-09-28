# Noetia · Whitepaper

## Introduction

This book consists of three parts: A, B, and C. Part A develops in depth a specific approach attentive to intension, stating its commitments and costs, meaning and efficacy layer by layer. Part B develops political directions for effective differentiation and the organization of relations; Part C audits these developments as well as its own formulation and use.

## A

### F Layer

#### Commitments and Costs

This layer takes on the meaning and efficacy stated in K and C; FA describes concrete use. This layer and its presentation are themselves FA. A particular use may adopt a logic as a whole and make full, combined use of its consequences. Neither that adoption nor additions made in other layers thereby become shared commitments of F.

#### 1. W and K

Both the content under discussion and its use can be spoken of as FA. Within this KCFA scheme, W is an open role for marking the content under discussion; it does not specify any particular W in advance.
To speak of the identity of a W is to speak of that W itself, together with its intension, determinateness, and efficacy. Using it does not depend on exhaustively stating or knowing its determinateness.

\[
A\doteq_{\mathsf W}A
\]

Here, \(A\) stands for the W under discussion, and \(\doteq_{\mathsf W}\) denotes identity of W. Perspectives and interpretations likewise use the efficacy of the W at issue in keeping with its identity.

#### 2. C

\(\mathsf C(B,A)\) reads: B's determinateness in its entirety is fully contained in A. Full containment alone does not confer the substitutive efficacy of identity between the endpoints.

Speaking of A does not leave outside that presentation any other W that A fully contains but that has not been stated separately.

Speaking of A does not omit the intension, determinateness, or efficacy of the W itself merely because they have not been stated separately.

With the endpoints and the meaning of full containment fixed, presenting, proving, or reading does not independently change whether this judgment holds.

#### 3. Concrete Use (FA)

These roles may be used together according to the meanings and methods adopted in a particular use, without first requiring F to generate or prove the content being used. Adopting or declining to adopt something does not, by that choice alone, acquire priority.

### M Layer

#### Inheritance and Shared Adoption

This M fully inherits F and adopts the mathematical development of KCFA and the conventions of use stated here. Its additions and their consequences do not extend back into F.

The main body adopts constructive rules for implication, conjunction, disjunction, and quantification; persistent metalevel hypotheses; and the types, terms, judgments, relations, functions, finite data, closures, saturation, and presentation tools used here. Elimination from the empty data type, constructor disjointness, and quotients are adopted with their respective structures. Inclusion and equivalence of relations and predicates are understood pointwise. Complete presentations adopt associativity, commutativity, and idempotence modulo synonymy, and faithfully represent the original identity and full containment through the interfaces specified below.

KCFA follows F's logical divisions, while its adoption, interpretive responsibility, and efficacy are borne by the layer as a whole. Existing conditions and their consequences are used together in full. Additions or changes carry their actual conditions, and the relevant dependencies are updated accordingly. The supplement fully inherits the main body; its additional adoptions take effect within the supplement.

#### I. Km: The W Itself and Complete Use

##### K1. The Rule of Complete Use

W retains F's open role. The bare interpretation of this M may be empty; closed instances are supplied by actual constructions. A and B are labels for expressions, whose referents are fixed by the use in question.

A use fixes a syntactic signature \(\Sigma\) and a host context \(\Gamma\). It distinguishes the formation of W terms, \(\Sigma;\Gamma\vdash_m A:\mathsf W\); the formation of judgments, \(\Sigma;\Gamma\vdash_m\varphi\ \mathsf{jform}\); and derivability, \(\Sigma;\Gamma\vdash_m\varphi\). The reference host allows hypotheses to be copied and discarded. Parameters are substituted consistently according to their declared roles, preserving variable binding, types, and well-formed dependencies. Identity is used as a primitive judgment: two well-formed W terms may form an identity judgment, and a well-formed A satisfies \(A\doteq_{\mathsf W}A\). Other identities are introduced by explicit hypotheses or correct rules and used for substitution in the corresponding parameter positions. Identity retains the concrete representation supplied by the chosen interpretation.

The context rules inherit **the two sentences in F's C section**: the W itself and any W it fully contains are used together with their respective intensions, determinateness, efficacy, roles, and applicability conditions. Content not separately stated or unfolded remains included; particular acts of extraction, enumeration, computation, and decision are supplied by actual constructions.

Using the complete singleton presentation \([A]\) from C3 to mark the source of use, the rule of complete use (W3m) is:

\[
\frac{\Sigma;\Gamma\vdash_m C(B,A)\qquad
      \Sigma;\Gamma\vdash_m^{[B]}J}
     {\Sigma;\Gamma\vdash_m^{[A]}J}.
\]

Complete use of A inherits the original judgment J, preserving the B discussed in it, its other premises, and its dependency conditions. K2 extends this inheritance to complete sources and entire derivations.

##### K2. Source Inheritance and Context

\(\Sigma;\Gamma\vdash_m^p J\) denotes a derivation of a judgment supported by the complete source p. The superscript records the source of use; actual hypotheses are supplied by the context and rule premises. Existing unmarked judgments retain their formation and derivation rules. The singleton \([A]\) retains A itself, and jointly presented sources use C3's presentation layer.

Formation and derivation rules satisfy their source requirements through absorption. They preserve the original judgment premises and other applicability conditions, rather than separately determining applicability from the raw form in which a source is presented. Given \(q\le p\), each requirement is first absorbed by q and then, by transitivity, by p. Applying the same inheritance recursively to the premise derivations yields the original conclusion from p. Inheritance composes transitively and applies within nested and repeated uses. Synonymous sources absorb one another and therefore support the same judgments. Each derivation retains the finite sources and premises it uses.

With the source fixed, synonymy of complete presentations also permits substitution in the corresponding parameter positions: from derivable \(p\approx q\) and \(\mathscr H[p]\), obtain \(\mathscr H[q]\). Together with C3's absorption equation, \(C(b,a)\) makes \(\mathscr H[[a]]\) and \(\mathscr H[[a]\oplus[b]]\) interderivable. Contexts are formed by the chosen syntax according to the original parameter roles, and W parameters are substituted according to K1. FAm jointly accounts for interpretation and preservation at concrete positions.

#### II. Cm: Full Containment, Presentation, and Their Consequences

##### C1. Intended Meaning and General Rules

\(C(B,A)\) means that B's determinateness in its entirety is fully contained in A, directly concerning the endpoints themselves. Complete involvement is used transitively through full containment. The whole and its unfolding still concern the same A, and an actual back-reference likewise uses A itself. The effect of the fully contained B is already included; naming, reading, or making it explicit does not produce another independent effect outside that content. Facts supplied by a concrete relation need not exhaust C.

This M explicitly adopts internality / no-eye: full containment and its inheritance efficacy hold in accordance with the intensions of the original endpoints, rather than being determined by additional semantics independent of those intensions. With the endpoints and the meaning of full containment fixed, presentation, proof, reading, and computation exercise their efficacy in accordance with that meaning. Proofs or local hypotheses do not themselves produce the full-containment facts at issue.

Within K1's fixed syntax and host, any two well-formed W terms may form a C judgment; both endpoints are genuine W positions. Formation, derivability, and holding under a fixed interpretation are recorded separately. E and C denote, respectively, identity and full containment as they hold in the interpretation. This M adopts self-involvement, transitivity, and compatibility with identity:

\[
C(a,a),\qquad
C(d,b)\land C(b,a)\to C(d,a),\qquad
E(d,d')\land E(a,a')\land C(d,a)\to C(d',a').
\]

Compatibility with identity realizes substitution of identical terms at both endpoints. Together with self-involvement, it yields \(E\subseteq C\). Full containment supports source inheritance.

##### C2. Relational Closures and Transitive Unfolding

We first use only the relational premises already included in the efficacy of full containment. In the data \((X,E,C)\), X may be empty, E is an equivalence relation, and C is transitive, compatible with E at both endpoints, and contains E. The positive-length finite transitive closure of C is pointwise equivalent to C: one direction uses a one-step path, the other induction on paths. When the quotient \(X/E\) is adopted, C is well-defined on it. The stated relational premises give a preorder; they do not by themselves imply antisymmetry.

Given identity seeds \(\Delta_E\) and positive relation seeds \(\Delta_C\), first take the equivalence closure of the identity seeds. Saturate the positive seeds for compatibility at both endpoints, take their positive-length transitive closure, and include E:

\[
E=\operatorname{EqCl}(\Delta_E),\qquad
C_{\min}=E\lor\operatorname{TC}^{+}(\operatorname{Sat}_E\Delta_C).
\]

The positive-path component is the least E-compatible transitive relation containing the positive seeds. After including E, \(C_{\min}\) is the least compatible preorder containing E and those seeds, and is contained in every relation satisfying the corresponding conditions.

This construction gives a minimal realization of the stated relational conditions. The seeds' intended interpretation, the whole interface, and additional derivation rules are each used according to their actual adoption. The scope of complete derivations is determined by their rules; existence of a faithful absorption representation is governed by the conditions established in C3.

Transitivity also allows existing consequences to be transferred back along relations on either side. Given \(C(x,a)\) and \(C(b,y)\), the inner relation \(C(a,b)\) composes into the outer relation \(C(x,y)\). Retaining both side relations and the other original premises, any fixed conclusion derivable from the outer relation is also derivable from the inner relation.

For any relation, the pointwise disjunction of its direct component and its two-step component is pointwise logically equivalent to the direct component if and only if the relation is transitive. This is an expanded formulation of transitivity. C in this M is also reflexive, so \(C(d,a)\leftrightarrow\exists b\,[C(d,b)\land C(b,a)]\): take b=a in the forward direction and use transitivity in the reverse direction.

##### C3. Complete Joint Presentation and Absorption

This M develops complete involvement under C through the following presentation scheme: \([a]\) fully involves a itself, \(p\oplus q\) fully involves both items jointly, and \(\approx\) denotes synonymy of presentations. Presentations and the W itself, and presentation synonymy and identity E, are recorded separately. The scheme adopts synonymy as an equivalence relation, singleton faithfulness \([b]\approx[a]\leftrightarrow E(b,a)\), and associativity, commutativity, idempotence, and substitution of synonymous presentations modulo synonymy (ACI). Actual resources and events are accounted for under FA1's conventions of use.

Complete involvement also adopts an exact two-way interface: the singleton presentation of an item fully involves that item; joint presentation retains each item's existing involvement; synonymy transports complete involvement; and, once an item is fully involved, presenting it jointly again adds no determinateness. Define presentation absorption by \(p\le q\iff p\oplus q\approx q\). Then \([b]\le p\) if and only if p fully involves b. Under the full-containment interpretation whose requirements have been met:

\[
C(b,a)\quad\Longleftrightarrow\quad[b]\oplus[a]\approx[a].
\]

The forward direction uses the fact that involving an already involved item adds no content. The reverse direction transports the joint presentation's complete involvement of b back to \([a]\) through synonymy. If absorption holds in both directions, ACI gives synonymy of the endpoint singletons, and singleton faithfulness recovers E.

These interfaces make absorption reflexive and transitive, with mutual absorption exactly synonymy. Joint presentation is a least upper bound modulo synonymy:

\[
p,q\le p\oplus q,\qquad
p\oplus q\le t\Longleftrightarrow p\le t\land q\le t.
\]

Finite joint presentation reuses the binary results. Given a main item and a finite list of additions, their joint presentation is absorbed by a target if and only if both the main item and each added item are absorbed by that target. The joint presentation is synonymous with the main item if and only if each addition is already absorbed by it. With the complete-involvement interface, the joint presentation of a and the other items is synonymous with presenting a alone if and only if a already fully involves each item. Finite joint presentation is anchored by a main item; an empty list of additions still returns that item.

Using complete presentations as K2's sources, \(C(b,a)\leftrightarrow[b]\le[a]\) yields K1's singleton inheritance. More generally, \([b]\le p\) gives \(p\oplus[b]\approx p\), and inheritance in both directions makes these two sources support the same judgments J. This is the making explicit and elimination of already contained sources throughout a derivation: the content of p and the role, effect, and conditions of b are retained, while b need not serve as an additional independent source. The source p may be a joint presentation. It suffices to have grounds that the whole fully involves b; no single item need fully contain b on its own.

Identity of W enters sources through singleton compatibility and combines with identity substitution in judgments. Source elimination is compatible with these substitutions at the level of derivability; it does not thereby determine that proof objects or execution paths are identical. Within the same calculus, for graph judgments with fixed inputs and outputs, one-way source inheritance preserves existing judgments and domain witnesses. Two-way elimination of already contained sources makes the graph judgments and their existential domains equivalent, reusing the original witnesses.

A common context preserves absorption: adjoining any presentation to both sides of an existing absorption preserves it. Fix two such presentation layers and an actual map. If the map preserves synonymy and makes “jointly present, then map” synonymous with “map each item, then jointly present,” it preserves absorption and is compatible with finite joint presentation. If synonymy in the image additionally implies synonymy of the original presentations, absorption is also reflected: a finite joint presentation in the image is synonymous with the image of its main item if and only if the corresponding statement holds for the original presentations.

ACI also gives a formal reduction of direct synonymy tests. When the final criterion is a synonymy judgment whose two sides are formed solely from the singletons of the same two endpoints and nonempty finite joint presentations, each side reduces to presenting one endpoint alone or both jointly. The test therefore reduces to one of four cases: always holding, synonymy of the endpoint singletons, forward absorption, or reverse absorption. What is reduced is the final presentation judgment in this format, not the identity of the endpoints. Hypotheses, intermediate presentations, and logical reasoning retain their original rules.

These results concern the presentation layer. Even when the singleton representation is faithful, its image need not contain the results of joint presentation; no join of the W contents themselves is thereby generated automatically.

For any given data satisfying C2's relational premises, an ACI formal representation satisfying singleton faithfulness and the exact C-absorption equation exists if and only if:

\[
\forall a,b,\qquad C(a,b)\land C(b,a)\to E(a,b).
\]

Necessity follows from absorption in both directions. For sufficiency, use nonempty finite lists as presentations, singleton lists as singleton representations, and concatenation as joint presentation. Define two lists to be synonymous when each item of either list is fully contained in some item of the other. Reflexivity and transitivity of C yield equivalence and substitution under synonymy, together with ACI. A singleton [b] is absorbed by a list if and only if some item of the list fully contains b. Singleton synonymy is exactly mutual C; the stated condition then recovers E.

Formal complete involvement can be defined as absorption of the corresponding singleton by the list. Self-involvement, joint preservation, and transport under synonymy then follow from ACI. The construction uses lists permitted by the host. Raw lists may differ; there is no need to compare or remove duplicates, choose representatives, or decide E, C, or synonymy. Any given whole presentation continues to be used under its own interfaces.

Applying the same condition to the minimal closure yields the seed corollary: on a fixed carrier with the original E, a compatible preorder extension containing the specified positive seeds and admitting a faithful absorption representation exists if and only if mutual relatedness under \(C_{\min}\) already recovers E. Necessity follows because the minimal closure is contained in every extension; sufficiency follows by taking that closure itself.

The construction preserves the given E throughout, and the required condition is used through positively supplied grounds. This establishes the existence of a formal representation for the relational data. Its correspondence with the content at issue remains subject to FA2's interpretive requirements.

#### III. FAm: Actual Adoption and Combined Use

##### FA1. A Single Use, Preservation, and Change

Use of this M combines the W itself, identity, and full containment, and includes M's own statements, developments, and proofs. Within a single statement and within rule instances without a comparison bridge, the syntax, formation rules, host discipline, referents, relation interpretations, and grounds of introduction are preserved. Changes are described in terms of what actually changes and the scope of preservation claimed. Knowledge of fixed content is distinguished from changes to that content itself.

Constructions and parameters enter the syntax according to their declared roles, with the corresponding interpretive responsibilities fulfilled at each position. Reindexing, transport, and coherence at dependent positions are accounted for by the actual structure. Resource discipline is used together with the corresponding composition of contexts. The intension, determinateness, normativity, and efficacy of the W itself are inherited together; actual inputs, resources, and events retain their effects. Source elimination removes the redundant listing of content already included.

Pure renaming preserves formation, holding, and consequences. Within a fixed rule system, reversible pure renaming also preserves derivations. Comparisons and mappings take place in explicit backgrounds and well-formed positions, fulfilling the preservation and reflection claimed. Once the endpoints, the role of full containment, and its meaning have been confirmed to be the same, the original full containment is preserved directly. Actual construction, reading, and return across uses are each used according to the work they undertake.

##### FA2. Content and Formal Results

This M takes responsibility for correctness and for the appropriateness of derivation and interpretation to the original roles. Formal results are used with their premises, interpretations, and scope of coverage. A representation may unfold only part of the content, while the content itself and its effects are still inherited in full. Correctness and appropriateness require actual grounds; fixing an interpretation does not replace that argument. Models and countermodels are used under the roles and conditions they actually fulfill.

When the subject is text, reading “01” and “1” as the same numerical value establishes only that the numerical readings agree. When the subject is the same numerical value, different spellings do not create a numerical difference. The object under discussion and the scope of the judgment follow the original use; the result of reading or representation cannot retroactively replace them.

When preservation of an operation is claimed, **its domain and output are preserved together**. When the corresponding inputs are related by the identity or presentation synonymy appropriate to that position, definedness is preserved; where defined, outputs are preserved under the relation in use, and the choice of evidence for definedness leaves no unaccounted-for difference in output. Comparing outputs only where both operations are available overlooks the original domain. If an implementation imposes additional conditions that restrict an operation already established to be preserved, the question is whether the implementation fulfills that inheritance.

Given an interpretation of identity or full containment, constructing a candidate relation that satisfies a set of observations and compatibility conditions yields a result for that candidate problem. Establishing agreement with the original interpretation is a different task. Existing inheritance of the intended meaning is used on its original grounds; further coverage and return are checked against the concrete claim.

##### FA3. Formal Examples of Labels and Decorations

With the same data, syntax, and rules, a phantom label that selects no different data may be erased or replaced while preserving formation and holding for the construction.

If every fiber of an added decoration is contractible under host equality—a center is supplied, together with equality of each element to that center—and the relation interpretation is pulled back along the erasure map, the corresponding two-way reduction and relation preservation follow. Where preservation of formation, availability, or consequences is also claimed, the construction must preserve the corresponding structures as well.

On fixed nonempty algebraic data, the everywhere-empty and everywhere-full markings are both E-saturated, yet differ. Used as rule conditions, they respectively close and open the rules. Such actual decorations are used together with their effects.

The reference calculus for complete use tests the structural interface of source inheritance. The requirements concerning the original syntax, dependent transport, and interpretation must be fulfilled by the concrete adoption. These checks do not amount to verification of M as a whole.

#### Supplement: A Restricted Calculus and Logical Consequences

This supplement fully inherits the adoptions of M's main body and their efficacy. It additionally adopts the usual constructive propositional logic and rules for quantification with bottom elimination, interpreting negation as \(\neg q:=q\to\bot\) and taking positive and negative polarities to be the same judgment q and its negation.

The supplement as a whole bears these additional adoptions and the consequences that depend on them; they do not extend back into the main body. Inherited results retain their actual conditions. General excluded middle and the corresponding decision procedures are not shared adoptions of this supplement.

##### The Restricted Calculus

Take the bare subcalculus generated only by finitely many identity hypotheses, reflexivity, and substitution at the left and right positions of identity judgments, retaining the discipline of persistent hypotheses. Its derivable identities are exactly the equivalence closure of its hypotheses. Symmetry and transitivity therefore need not be added separately; without off-diagonal hypotheses, there are only diagonal consequences.

If a reflexive relation contains the original hypotheses, is contained in their equivalence closure, and supports one-sided transport—from a common left endpoint related to each of two items, derive a relation from the first item to the second—then it is pointwise logically equivalent to that closure. Redundant rule statements whose rules are derivable may still be removed.

##### Logical Consequences

A proposition q is called stable when \(\neg\neg q\to q\). Negated propositions are stable. Stability is closed under conjunction, universal quantification, and implication with a stable consequent. For a stable target, derivability from a premise is equivalent to derivability from the double negation of that premise. In the forward direction, first obtain the double negation of the target and then use stability. The reverse direction uses the fact that each proposition implies its own double negation.

The supplement's logic yields the double negation of the conjunction of any fixed finite list of excluded-middle instances. If a stable target follows from that list, the list can be eliminated to obtain the target while preserving the other original premises. What is eliminated is this finite list of propositional hypotheses. A global excluded-middle oracle, choice, or Decidable data is used under its own conditions.

Use the two Bool codes to record the positive and negative branches. Exactly one code satisfies its corresponding proposition if and only if \(q\lor\neg q\), and the double negation of this “exactly one” is always obtainable. When there are grounds for the stability of the target, the additional premise that “exactly one polarity holds” can be eliminated from a derivation, while the other original premises are retained. Exhaustiveness of the codes does not mean that one of their corresponding propositions must hold.

For two propositions known to be mutually exclusive, their disjunction satisfies excluded middle if and only if each proposition does. If this positive disjunction already holds, both propositions are also stable.

Taking bottom as the target in C2's transfer of consequences gives propagation of an existing negation along relations on either side.

The distinctions among judgment formation, holding in an interpretation, and derivability follow K1 and C1. Polarity facts, evidence for branches, decision data, and effective programs are each used according to their actual grounds and constructions. Absence of a proof or undecidability does not itself provide evidence of negation or of a truth-value gap.

### E Layer

#### Commitments and Costs

This E fully inherits M's main body and the F inherited by it, and organizes the use and optional constructions of concrete #x protocols built on this M. The supplement is inherited under its actual conditions. Each concrete protocol is specified by its own norms.

The shared background and existing results are reused directly. Additional adoptions and their consequences are borne within their respective scopes: shared conventions apply within E, optional constructions take effect when selected, and additions specific to a #x remain within that #x. These additions do not extend back into F or M, or across to other #x protocols. Concrete components work within the scope they implement, while the inherited theoretical content is preserved in full.

#### 1. From Local Understanding to #x

Normative arrangements can be understood and organized around the intension, determinateness, relations, and efficacy of the W under discussion. “A posteriori” here concerns grounds. An arrangement may be adopted first in operational order and used to form, present, and continue W; operational order does not itself confer philosophical priority.

In this use, #x emphasizes explicit operational arrangements; a local god's-eye view emphasizes reflection on their normative shape; and the W level emphasizes open discussion not yet employed as an explicit scheme. These are different emphases within related content, and reflection and discussion are themselves used according to their actual content. Arrangements can continue to be revised, differentiated, and reinterpreted. When used as W, they are used together with their own determinateness and efficacy.

#### 2. Shared Use Under This M

A concrete #x specifies the constructions selected, how they are used together, and the scope retained. The existing shared background can be invoked directly. Positions for the W itself and for presentation parameters follow K1 and K2; interpretation and preservation of partial operations are fulfilled under FA1 and FA2.

Complete use and actual back-reference directly involve the content itself. Extraction, enumeration, computation, and decision are supplied by concrete constructions. Components work within their claimed scope, and formal results support the judgments at issue through interpretations whose requirements have been met.

#### 3. Optional Constructions and Tools

A concrete task may interweave construction, reading, representation, and recovery. A construction specifies the content under discussion, its actual effects, and the scope of preservation. Local preservation relations provide grounds for C through their interpretations.

Composition in M's presentation layer is reused under its existing conditions. When constructing combinations of W contents themselves or new partial interfaces, the construction bears responsibility for their domains, outputs, and preservation relations. Cross-use comparisons and return follow FAm. Publication, parameterization, and revision are organized according to the actual adoption, distinguishing corrections to knowledge of fixed content from changes to the construction itself.

Mappings, candidate intervals, and joint conditions are optional tools. Each is used according to the selected result and its premises.

### P Layer

#### 1. The Status and Layers of Interpretation

This P clarifies the existing content of F, M, and E and the connections among them, according to the meanings, conditions, and scopes adopted by each layer. It adds no formal or semantic obligations. Clarification can enable fuller use of existing content; P is itself a concrete use.

#### 2. Openness and Actual Efficacy

W's open role does not fill in content in advance. Actual use proceeds with the intension, determinateness, and efficacy of what is under discussion. Concrete structures may be adopted, with their holding and implementation accounted for according to the actual case. Content not unfolded, or not yet handled by a component, remains within the original use.

No-eye also distinguishes whether fixed content holds from our knowledge of it. Knowledge may develop further, and concrete capabilities are supplied by actual resources and constructions.

#### 3. Content, Presentation, and Knowledge

How names and representations participate in content depends on what is actually under discussion. Judgments about text and judgments about different spellings of the same object each have their own scope. Representations and proofs support the judgments at issue according to the inheritance they fulfill. Complete involvement does not require disclosure to everyone in the same byte form; disclosure and transmission are organized according to the corresponding adoption.

Corrections to knowledge of fixed content are distinguished from changes to actual constructions or uses. Absence of evidence supplies no negative fact. Semantic clarification can make connections explicit, rule out shifts in what is being discussed, and support inferences. Any added grounds are assessed by their actual content.

#### 4. Full Containment, Unfolding, Back-Reference, and Iterated Layering

M's general full containment is used together with the identity, determinateness, and efficacy of what is fully contained. Unfolding and back-reference bring existing content into use; particular observations, records, and computations are performed by their respective mechanisms. Composition at the presentation layer and constructions that return W contents themselves follow M's and E's corresponding interfaces and conditions.

Iterated layering, including ordinal-indexed layering, may be constructed under concrete conditions. The rule, the results of each iteration, and their labels retain their actual connections and differences. Repeated use of the same label does not itself give \(A=f(A)\). Differences of time, path, or event are likewise used according to the content under discussion. An existing effect does not lapse merely because no additional increment is produced.

#### 5. Open Use and Comparison

Comparison concerns actual objects, purposes, and methods. Metrics, translations, and consequence relations are used together with their scopes. Conclusions about upper bounds, optimality, and uniqueness are obtained on the corresponding grounds; structures within a concrete model remain within the scope of its adoption.

A concrete use may adopt rich resources from the outset and make full use of strong results already available. Further expansion is studied with its additional content and conditions. These interpretations prescribe no uniform order of research, implementation path, or resource preference.

## B

### 1. Making the “Branch” More Like a “Branch”

The preceding account offers an approach attentive to intension, connecting intension with determinateness and efficacy and developing these connections through full containment, complete presentation, and inheritance of use. It is a powerful approach developed through concrete research and testing.

Obtaining efficacy goes together with its determinateness; taking on determinateness likewise goes together with its efficacy. The inquiry goes downward into what is taken on in each case and its efficacy, rather than upward by expanding a common category and then using it to subsume different relations. **How can relations be organized to make fuller use of “taking on determinateness and obtaining efficacy”?** The direction pursued here is a continuing increase in effective dimensions: enabling actual differences to operate separately, and making the “branch” more like a “branch”.

Here, “branch” and “trunk” refer to specific relations of support (for example, the full containment discussed above). Such relations can form hierarchies; their efficacy remains supported by their actual determinateness, without conferring any additional normative height. Compare two branching patterns, with each row listing the branches at the corresponding juncture:

| Juncture | Earlier branching, with continued unfolding | Fewer, later branches |
| --- | --- | --- |
| A | A₁, A₂ | A₁ |
| B | B₁, B₂, B₃ | B₁ |
| C | C₁, C₂, C₃, C₄, C₅ | C₁ |
| D | D₁, D₂ … D₁₀ | D₁, D₂, D₃ |
| E | Effective branches continue to form | Terminal branches still pass through A₁—B₁—C₁ |

On the right, whichever D is selected, the path passes through A₁—B₁—C₁. Different terminal choices continue this set of conditions as a package; within this arrangement, the specific conditions and effects of each segment are difficult to use separately for adjustment and reorganization.

On the left, if actually usable C₁ and C₂ form under B₁, the shared conditions of B₁ and the specific conditions of each branch can more readily be used separately for selection, adjustment, and continuation. These distinctions thereby enter the actual organization of relations, rather than remaining solely matters of understanding.

Growth in effective dimensions is reflected in differences being able to operate separately in more directions, without being drawn together by centralization. What matters is effective differentiation: whether branches can sustain their own operation and continuation, where branching occurs, and which conditions remain controlled through the same point of access. There may be many names at the endpoints while roles and dependencies remain unchanged; content may also fluctuate frequently while the locus determining change remains fixed. The direction pursued here is therefore for the growth of effective dimensions to outpace the consolidation brought about by centralization, allowing differentiation to continue.

Final outcomes, adjudication, and coordination also proceed from specific grounds, and existing arrangements and proposed changes are subject to the same questioning. The “branch” can be rich and powerful; centers, tails, and advantages still need to be understood separately along different directions.

#### Typicality in the Tails and Reciprocal Elites

As effective dimensions increase, being “central everywhere” requires satisfying more conditions at once. As a concrete mathematical illustration, with the scope and distribution under discussion held fixed, if successive dimensions keep placing part of the previous common center in the tails, with a uniform positive lower bound on the proportion removed at each step, the common center’s share keeps shrinking, and being in a tail in at least some directions gradually becomes typical.

The labels “normal”, “legitimate”, or “common sense”, as well as a numerical majority, louder voices, or greater power, do not in themselves confer normative authority to control or assimilate the tails, nor can they substitute for the specific grounds required to deal with, criticize, or exclude the tails. Relations are organized with these differences as their starting point, rather than first completing an arrangement that takes the common center as its default and then accommodating the remaining positions.

With existing capabilities and judgments unchanged, adding requirements that must be satisfied simultaneously cannot enlarge the set that satisfies them. When advantages are actually distributed across different positions, a relation of reciprocal elites emerges: one position provides capability in one direction and uses capability from elsewhere in another. Elite positions interweave across specific relations, and cooperation develops along these differences.

But how deeply can branching reach? If different relations must still return to the same kind of time, space, physical world, substrate, or continuity, additional dimensions may reconverge at these default premises. Making the “branch” more like a “branch” also requires opening up these deepest shared premises.

### 2. Against Shared Premises

This section develops two interrelated perspectives:

**First, examination of actual use.** Continuing the preceding inquiry into making the “branch” more like a “branch”, it examines whether the correspondence expressed by “taking on determinateness and obtaining efficacy” is used fully and appropriately, identifying how specific effects are bundled, obscured, or substituted for one another in use. Origins, attributes, or underlying entities reached through inquiry are used in judgment according to their actual contribution to the determinateness at issue; their “behind-the-scenes” status alone does not justify extending the scope of judgment or control.

**Second, a value orientation in politics.** This part pursues a continuing increase in effective dimensions, promoting precision in judgment and decoupling in relations, and opposing both the direct compression of different dimensions into a single scalar and the use of underdefined universal evaluations to make overall judgments. It actively promotes the decoupling of shared dependencies, enabling the relations involved to be organized and continued separately, with exit, branching, and mobility further extending this differentiation.

The following develops six interrelated aspects.

#### Against Defaults

Examination, precision, and decoupling run throughout the actual use of all content and arrangements, and can continually advance by drawing on distinctions already made. This part opposes using defaults in place of actual grounds to presume that some content already holds, has been adopted, or ought to be continued. Setting a default is itself a concrete adoption; it operates together with the corresponding determinateness and acquires neither additional efficacy nor exemption from further examination merely by being set as the default.

#### Anti-Foundationalism

Anti-foundationalism here means opposition to any ultimate truth and any ultimate ground. Judgments, theories, and their grounds exercise efficacy together with their own determinateness; using one of them as a foundation does not make it the ground to which other unfoldings must ultimately defer.

#### Against the “Subject”

No phenomenon—psychology, mind, will, religion, culture, continuity, a physical, biological, or informational substrate, expressed preference, or anything else—is allowed to stand in for a supposed “subject” behind it, and then, through that “subject”, claim to obtain efficacy exceeding the determinateness of the grounds for the judgment. From expressed preference to a subject, and from a subject to continuing identity, rights, or responsibilities, whatever is added at each step goes together with the corresponding grounds.

Specific arrangements of subjecthood hold according to their actual content; the designation “subject” supplies no additional efficacy. Human identity is also subject to this questioning.

#### Against the Global

This part opposes the global efficacy claimed by universal human rights, universal ethics, universal moral consciousness, universal faith, universal rights against all others, and universal principles such as “private property is inviolable”. Content, value judgments, and starting points, whatever names they appear under, operate together with their own determinateness; taking on only local determinateness does not warrant a claim to global efficacy.

A value being cherished, a right holding within specific relations, and an arrangement remaining effective over a long period each have actual meaning. The additional scope and operation involved in moving from these grounds to the claim that all relations should be bound by them cannot be left out. This part promotes organizing different rights, responsibilities, and continuations separately according to their respective grounds, and opposes making conformity to a universal principle a normative prerequisite for all relations.

#### Against Single-Point Dependence

Governments, political parties, religions, social security arrangements, public blockchains, networks, trading platforms, and similar structures can become shared points of access for multiple relations, bundling resources, information, rights, and obligations into a single continuation. This part promotes the differentiation of these dependencies so that each relation can be sustained, adjusted, migrated, and continued separately, reducing the scope of what must be continued as a package.

#### Against a Unified Background

Time, space, the physical world, causality, substrate, and continuity likewise cannot be installed in advance as the shared point of access to all relations. They can become specific content and fully exercise their corresponding effects; which description of reality is adopted, which relations are connected, and how continuation takes place still need to be developed separately. “Reality” itself likewise has no efficacy as a unified background beyond its own grounds.

For example, following A's approach of introducing intension and connecting it with determinateness and efficacy, Alice as a whole, Alice at a particular time, and an identity within a particular contract can each be discussed as a W. If Alice as a whole is what is meant, life and death can be part of its content, but are not external events that make this W appear or disappear; if Alice at a particular time is meant, continuation with other times still needs to be explained; if a contractual identity is meant, what is undertaken is the corresponding set of rights and responsibilities, not a package containing all other identities. The issue is what exactly “the same Alice” preserves and which relations it continues.

These critiques, together with their grounds and scope, are likewise subject to examination.

### 3. Demonstrating Organizational Capacity

#### How Continuation Holds

The persistence, coming into being, or cessation of the content under discussion is not independently determined by a presupposed external time; time can enter its determinateness, and continuation across time can also hold through specific relations. Not presupposing time does not mean having zero duration, nor does it predetermine that the content under discussion is an instantaneous instance.

Relative to a particular relation of rights and responsibilities, continuation is not presupposed; actual continuation can hold for an entire package, or hold separately in relation to some of its content, certain rights, or certain responsibilities. The manner of continuation, its conditions of application, and its corresponding operation together constitute the determinateness of this continuation. The scope of continuation can be partial, while the content that is continued still exercises its corresponding efficacy according to its actual determinateness.

For example, if the rights and responsibilities of A, B, C, D, and E are continued but those of F are not, what holds is the continuation of the first five; F does not continue along with them. Continuation itself can also differentiate along different rights and responsibilities.

There is therefore no ontological exit button independent of specific continuations. What is called exit is the situation manifested by the non-continuation of corresponding rights and responsibilities; the actual retention, losses, constraints, and transfers involved are discussed in the next subsection.

#### Expulsion, Staking, and Exit

Here, expulsion means disconnection relative to a particular relation of rights and responsibilities, including self-expulsion through self-initiated disconnection; it does not presuppose punishment. **Relative to that relation, expulsion is the upper bound of punishment:** if bearing a punishment more severe than disconnection requires continuation of that relation, the increase in punishment does not itself provide that continuation; without continuation, the additional demand loses its support.

Within a continuation, what can be retained, and what will be lost through breach or disconnection? Resources already committed, credit, services, and the value of continued cooperation, among other things, serve as stakes when they give performance and non-performance actual consequences. If losing a continuation entails no loss, the loss of that continuation cannot impose a constraint; when credit is established through these consequences, the constraining effect required must be supported by corresponding stakes and the capacity to realize them.

If multiple continuations share a controllable, necessary point of access, a change at one point may affect other relations at the same time. Which can be sustained separately, and which can be transferred or reorganized, influence the specific forms that exit, mobility, and decoupling take.

When different continuations can be sustained separately, room opens up for exit, mobility, and decoupling. When these changes allow previously bundled rights and responsibilities to continue separately, and allow new relations of cooperation and support to operate separately, effective dimensions also increase, further expanding the room for each continuation to change separately.

#### How Relations Connect and Propagate

The spread of effects and connectivity are themselves relations. What is called “external” is always relative to some specific scope; an influence coming from outside that scope has already formed a corresponding relation. Discussing externalities requires specifying what they are external to and how their effects arise and propagate.

To speak of a “shared reality” is also to take on the determinateness of its shared content and scope; without this undertaking, one cannot presuppose that there is always a shared reality that first bundles different relations together.

A change in conditions at one point can, through different connections, expand the possibilities for some continuations and tighten the conditions for others; these changes may in turn alter the original conditions. The transmission of capabilities, information, and resources, and the provision and withdrawal of support, all operate within these relations. Enabling more content to be used mutually, and enabling these connections to be organized separately, continues the direction pursued here.

### 4. The Examination and Transit of Ideas

The explanations, judgments, and demands of a body of thought also operate together with their determinateness. Examination begins with the content and grounds actually adopted, identifying the shared background on which it depends, the efficacy it obtains, and how these dependencies enter into the standing and scope of its claims. Examination proceeds on the basis of these actual relations, without requiring changes to the ideas or acceptance by the parties.

Multiple bodies of thought can be examined alongside one another, together with their respective grounds, demands, and consequences; comparison and selection develop through this examination. Claims that depend on more shared background cannot be placed on an equal footing with those that depend on less while leaving that additional dependence out of the comparison. When something specifically adopted is made a common threshold, the burden that originally called for explanation can easily become a deficiency attributed to ideas that do not adopt it. A “branch” is thereby treated as a “trunk”, while differences in the long tail are required to be supplemented with that same background, making it difficult for them to develop on their own grounds. Which ideas and arrangements are more Noetia is discerned by how fully they make use of “taking on determinateness and obtaining efficacy”. The political orientation of this part also takes shape through such examination and comparison.

Noetia also serves as a transit hub for ideas. Different bodies of thought enter into relations with one another together with their content; each party examines the others’ ideas and also opens its own ideas and judgments to their examination. This can identify determinateness undertaken in common and the corresponding efficacy, and can also bring disagreements into sharper focus. What is shared is used on its actual grounds; the remaining content retains its respective relations and differences. Transit does not aim to unify ideas or reach consensus. Each body of thought can remain as it is, while their contents can still be examined, drawn upon, and developed further. Examination and transit also have the capacity to build architectures: existing content can reveal consequences that have not been fully used, and relations among ideas can support new adoptions, norms, and constructions.

### 5. Growth in Effective Dimensions

#### The Difficulties of Fixed Shared Premises

Fixing shared premises as irreplaceable conditions requires new content to keep conforming to the existing organization. Once previously omitted differences alter actual consequences, work saved earlier can readily turn into accumulating difficulties in accommodating tail, unknown, and boundary problems.

#### Continuing the Work Without Starting Over

The examination of actual use, precision in judgment, and the decoupling of relations cannot stop at boundaries set in advance; nor can the grounds and methods employed be exempted from this work merely because they have been adopted. Work already done cannot be treated as not having been done and then demanded again from scratch. These developments are not presupposed to belong to an encompassing whole or to be measured by a single uniform quantity.

#### Mutual Use and Further Development

Examination, precision, and decoupling continue to advance, allowing actual differences to operate separately through combination, substitution, and other means, and making fuller use of the correspondence expressed in “taking on determinateness and obtaining efficacy”. Existing understanding, methods, and connections, among other things, can be reused; their acquisition costs are not paid anew merely because they are reused. Different contents can draw on one another without having to be unified, while connections and uses can be separately adjusted and recombined to form interwoven support. The connections and practices formed in this way can themselves continue to be examined, separated, and recombined; this process does not terminate because of a change in scale, level, or perspective, nor does it take an established use as its endpoint.

## C

The preceding developments have all proceeded through concrete formulations, intuitions, and judgments. Do they also turn what they adopt into a common threshold? Self-examination seeks to identify the premises brought in and whether actual distinctions still constrain what is said and inferred. The following uses trivial and banal to distinguish these two directions and proposes two sentences as an attempt at such examination.

### 1. trivial, banal, and the Two Sentences

Here, trivial means not fixing entities, distinctions, or their nature in advance; banal means failing to preserve actual differentiation in the matter under discussion, so that actual distinctions do not constrain what is said or inferred. Non-banal preserves this constraint.

|  | banal | non-banal |
| --- | --- | --- |
| trivial | Does not build in substantive premises, but does not preserve actual differentiation either. E.g., later Wittgenstein’s therapeutic conception of philosophy in *Philosophical Investigations*. | Does not build in substantive premises; actual distinctions still constrain what is said and inferred. |
| non-trivial | Introduces substantive premises, yet still renders the distinctions under discussion ineffective. E.g., Della Rocca’s radical Parmenidean monism in *The Parmenidean Ascent*. | Adopts particular premises and lets actual distinctions enter judgments and inferences. E.g., Kant’s transcendental idealism in *Critique of Pure Reason*. |

The quadrants and their examples indicate the relative orientations of particular formulations and uses along these two dimensions. Particular norms may adopt substantive premises and obtain corresponding results; what we seek here is a formulation that is both trivial and non-banal. “Openness” helps convey that content is not filled in beforehand; “firmness” helps convey that actual distinctions remain constraining.

This leads to the two sentences:

> Do not presuppose that distinctions exist.  
> If there is no distinction, there can be no distinction.

The first sentence leaves even “something must exist before distinctions can be discussed” as something to be adopted in a particular use. Not presupposing existence does not presuppose that only absence is possible, nor does it supply all possible things in advance. “Distinction” itself is likewise not installed as an antecedent entity.

The second sentence makes explicit how actual distinctions constrain what is said and inferred: without a corresponding distinction, a mere change of name cannot obtain the effect of there being a distinction; nor are existing distinctions erased because they have not been recognized or unfolded. “If there is no distinction, there can be no distinction” preserves a directed connection here, rather than merely repeating “there is no distinction” unchanged. How negation and implication work, and what it means for a judgment to hold, are understood in conjunction with the reading being used.

The first sentence continues to act on the interpretation of the second. For example, giving “negation” and “distinction” separate names does not suffice to build in two independent fundamental operations. If a difference between them is adopted, that difference also falls within the scope of the inquiry. The question is whether the two sentences can preserve both the absence of built-in premises and actual constraint.

### 2. Stress Tests, Positive Construction, and Checks

#### Stress Tests

The stress tests ask whether the two sentences themselves force the introduction of any substantive premise that has not been separately adopted. This is precisely the non-triviality we are unwilling to pay for here; even a familiar or useful additional conclusion would be a problem. Not being forced to introduce these additional premises, while preserving the operations and properties of the reading used, is a good result for this test.

The tests conducted let each kind of reading work with its own account of negation, implication, what it means for a judgment to hold, and identity. They found none of the forced presuppositions they tested:

| Reading tested | Main question examined |
| --- | --- |
| Classical reading | Whether the excluded middle, negation, and other resources used are read back into the two sentences as content they themselves require. |
| Constructive reading | Whether existential witnesses, the ability to decide, or a determinate branch must still be supplied when the general law of excluded middle has not been assumed in advance. |
| Paraconsistent reading | Whether a uniform exclusion or explosion rule must be added when positive and negative judgments can both hold without explosion. |
| Removing or restricting the law of self-identity | Whether entities with universally valid self-identity must still be introduced in advance when A=A is not generally provided. |
| A probe that directly denies A=A and adopts A≠A | Whether a reading that positively denies self-identity is necessarily excluded by the two sentences. |
| Continuous-valued reading | Whether degrees and operations are forced back into a uniform two-valued true/false structure. |

The first sentence often does the initial work here: the logic used in a test is used according to that reading, rather than retrospectively counted as a presupposition of the two sentences. The two sentences do not come with a uniform meta-level truth table already installed. After changing truth values or identity rules, one must still identify where any additional conditions enter.

#### Positive Construction

The positive task is to provide a faithful reading: one that preserves actual constraint without turning the material used in the example into common premises of the two sentences. This is an existence task.

First compare two arrangements. Two positions can continue separately: one can be changed while the other is preserved, and vice versa. If two names both point to the same position, however, changing the state they refer to changes both references together. Actual distinctness is given by how continuation works.

If separate preservation is genuinely removed from the original arrangement, and no other content takes on the work of routing the paths separately, merely giving the shared position two aliases cannot restore separate continuation. If names or source records actually perform separate routing, their contribution is counted as well. What is examined here is whether actual distinctness is preserved or removed; being unknown or unlisted does not constitute removal.

In this reading, a “distinction” is actual distinctness in the respect under discussion, and its differentiating effect is the work that this distinctness does in that respect. The whole sentence makes their connection explicit. Unfolding it again, or applying the two sentences to themselves, still puts the same connection into effect: explanation and understanding may increase, while the substantive connection preserved in the first unfolding remains preserved. This is the fixed point being examined.

Further work reformulated the second sentence as “There is a distinction between there being no distinction and there being a distinction,” and checked the passage in both directions using the same example of separate and joint continuation. The two formulations put the same connection into effect in the respect under discussion; “there is no” and “cannot” are also borne by the particular arrangement and the scope of its operations. Even if “negation” and “distinction” do differ in a particular use, that difference already falls within the scope of the first sentence. Retaining the original sentence does not require first proving that the two concepts are wholly identical across all uses.

Positions, states, and local capabilities are explicitly adopted for this witness. Within this reading, the internal arguments for preserving real constraints, introducing no additional assumptions at the core level, and self-application have been completed.

#### Checks

Six possible ways of strengthening the witness were also examined:

| Potential additional premise | Method of checking |
| --- | --- |
| Actual absence is expanded into the impossibility of presence. | Compare arrangements with and without a differentiating effect. |
| Not excluding something in advance is treated as guaranteeing its possibility. | Examine local modal arrangements that admit only one side. |
| Local reference requires a global identity or a transworld essence. | Compare separate routing through two ports with routing through one port plus source labels. |
| A constitutive constraint requires an antecedent cause or sufficient reason. | Use hypothetical constructions that do not presuppose an antecedent producer or causal relation. |
| Formal equivalence is extended beyond the scope of the comparison. | Compare programs with identical return values but different logs. |
| Undetermined content must first be placed into a sharp dichotomy. | Examine classifications with undetermined boundary membership and faithful reproductions of them. |

These checks found no forced introduction of the additional premises tested. Undetermined boundaries and continuous truth values were examined separately. The hypothetical constructions test whether a causal premise is forced; realizability in practice is a separate question.

The proof method was also subjected to negative controls. Adding or removing content before obtaining stability, clearing a relation before obtaining idempotence, or ignoring isolated points or an empty carrier may all yield some kind of fixedness without preserving the original content. Inserting the conclusion to be proved into a definition, or making any arbitrary claim automatically satisfy the definition, likewise renders ineffective the distinctions the test was meant to examine. Subsequent invariance cannot undo the additions or removals made at the first step.

The relational prototype has also been mechanically checked. Within a selected mathematical setting, it preserves the original relation on arbitrary carriers, including the empty carrier, without requiring that relation to be reflexive, transitive, or decidable. The formalization passed compilation, and 15 key declarations had no dependencies on additional axioms.

The completed results include a positive existence witness in an explicitly stated reading, together with the actual multi-logic tests, six-direction checks, and methodological negative controls. They hold under the specified interpretations and constructions; they do not provide universal certification across all readings.

### 3. Flatness and Micro-Level Tolerance

**Determinateness and efficacy have no freedom to vary independently of one another.** “Flatness” is an image for this picture: no determinateness or efficacy can independently appear in excess and constitute an absolute vertical height. Such height has not been removed; it was never there. Dependence, support, and full containment can form actual hierarchies within particular relations and exercise their corresponding efficacy in full. Content can increase, relations can deepen, and results can become stronger, all unfolding together with their corresponding determinateness and efficacy.

The contents at issue carry their actual normativity and efficacy; they cannot be dismissed wholesale as false from the standpoint of some supposed ultimate truth. Judgments of truth and falsity themselves work in conjunction with particular grounds. However broad the scope of explanation, traversal, or subsumption, it does not thereby acquire a global status of its own.

This correspondence already holds. What B pursues is to make full use of “taking on determinateness and obtaining efficacy” in the actual organization of relations. The ongoing increase in effective dimensions provides this use with more relations that can be developed, adjusted, and continued separately. Making full use of “taking on determinateness and obtaining efficacy” to examine other formulations and arrangements often reveals the roughness of “branches” that do not behave like “branches,” together with connections and consequences that can still be unfolded.

The expression and use of the two sentences are no different. Becoming more basic, more abstract, or more meta does not add a position detached from its own determinateness. Once a purportedly “transcendent” truth is expressed and used, it too bears its actual determinateness and does actual work.

The two sentences are understood through natural language and actual intuition. Context, conceptual usage, and matters not yet fully clarified all participate in this use; even how “faithful reflection” holds comes from the actual work of the intuition being used. We must therefore acknowledge a certain non-trivial remainder in this expression and maintain a micro-level “agnosticism” about what has not yet been fully clarified.

Keeping this at the micro level means keeping these remainders tied to particular questions: where an ambiguity changes a crucial inference, continue clarifying it there; distinctions and inferences that are already clear continue to work. This cannot be expanded into the macro-level banal claims that “everything is unknowable” or “every distinction can be revoked.” What is acknowledged here is the conditions and remainders of actual use, while preserving the differentiation that can already be made.

The resulting attitude is: **acknowledge what is actually being used, carefully clarify its problems, and strive to use it well.** To use a medium is to use it together with its conditions and capabilities. Continue improving what can be improved, and make full use of the understanding and inferences already available. The preceding norms and political claims, as well as the present analysis, are themselves part of this actual use; their examination likewise remains open to further checking from here.

### 4. Generalization, Moving to the Meta Level, and Testing

As methods for further research, generalization, moving to the meta level, and concrete testing can be interwoven and developed recursively as needed. Analogies extend the possibilities; different generalizations test one another, refine the structures they preserve, and prompt reconsideration of how the question is formulated. Return to the concrete question to check premises, counterexamples, and subsequent inferences. A single concrete test can also send several successive layers of generalization or reflection on the framework in a new direction.

Long-tail questions, non-obvious connections, and conjectures that temporarily lack direct evidence can serve as starting points for research. Pursue their mechanisms, conditions, boundaries, and consequences to test their explanatory potential, keeping the strength of conclusions proportionate to their actual grounds.

Make full use of the consequences of existing premises, and state conclusions that depend on additional conditions together with those conditions. Draw the inquiry to a close when there is no substantive gain; continue when there are new distinctions and effects. Approaches such as Minimax Regret and antifragility may also be adopted to develop arguments from other angles and derive corresponding results under their respective actual premises.
