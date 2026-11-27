# Noetia · Whitepaper

> v1.1.6 · 2026-11-26

[Introduction](#introduction) · [Structural Example](#structural-example) · [A](#a) · [B](#b)

## Introduction

The opening structural example can be read on its own; its specific adoptions do not become shared premises of the main discussion, which begins in Part A. That part develops a direction for organizing relations: making fuller use of the correspondence expressed in “taking on determinateness and obtaining efficacy” so that differences can operate separately and effective dimensions can continue to grow. Different contents can develop in their own ways and can also draw on one another to form new relations of support. When we draw on something in this way, which conditions must we take on with it, and which judgments can we still make separately?

The distinctions and approaches proposed here can likewise be reused as they stand or adapted, depending on the use at hand. We can also draw on their uses elsewhere to revisit the choices made here. Part B brings the opening question to bear on its own wording: in formulating two sentences, we try to shed shared premises they might introduce. To examine which conditions a claim draws on and what can be said on that basis, we can read it alongside these two sentences.

## Structural Example

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

The main body adopts constructive rules for implication, conjunction, disjunction, and quantification; persistent metalevel hypotheses; and the types, terms, judgments, relations, functions, finite data, closures, and presentation tools used here. Elimination from the empty data type, constructor disjointness, and quotients are adopted with their respective structures. Inclusion and equivalence of relations and predicates are understood pointwise. Complete presentations adopt associativity, commutativity, and idempotence modulo synonymy, and faithfully represent the original identity and full containment through the interfaces specified below.

KCFA follows F's logical divisions, while its adoption, interpretive responsibility, and efficacy are borne by the layer as a whole. Existing conditions and their consequences are used together in full. Additions or changes carry their actual conditions, and the relevant dependencies are updated accordingly. The supplement fully inherits the main body; its additional adoptions take effect within the supplement.

#### I. Km: The W Itself and Complete Use

##### K1. The Rule of Complete Use

W retains F's open role. The bare interpretation of this M may be empty; closed instances are supplied by actual constructions. A and B are labels for expressions, whose referents are fixed by the use in question.

A use fixes a syntactic signature \(\Sigma\) and a host context \(\Gamma\). It distinguishes the formation of W terms, \(\Sigma;\Gamma\vdash_m A:\mathsf W\); the formation of judgments, \(\Sigma;\Gamma\vdash_m\varphi\ \mathsf{jform}\); and derivability, \(\Sigma;\Gamma\vdash_m\varphi\). The reference host allows hypotheses to be copied and discarded. Parameters are substituted consistently according to their declared roles, preserving variable binding, types, and well-formed dependencies. Identity is used as a primitive judgment: two well-formed W terms may form an identity judgment, and a well-formed A satisfies \(A\doteq_{\mathsf W}A\). Other identities are introduced by explicit hypotheses or correct rules and used for substitution in the corresponding parameter positions. Identity retains the concrete representation supplied by the chosen interpretation.

The context rules inherit **the two sentences in F's C section**: the W itself and any W it fully contains are used together with their respective intensions, determinateness, efficacy, roles, and applicability conditions. Content not separately stated or unfolded remains included; particular acts of extraction, enumeration, computation, and decision are supplied by actual constructions.

Using the complete singleton presentation \([A]\) from C2 to mark the source of use, the rule of complete use (W3m) is:

\[
\frac{\Sigma;\Gamma\vdash_m C(B,A)\qquad
      \Sigma;\Gamma\vdash_m^{[B]}J}
     {\Sigma;\Gamma\vdash_m^{[A]}J}.
\]

Complete use of A inherits the original judgment J, preserving the B discussed in it, its other premises, and its dependency conditions. K2 extends this inheritance to complete sources and entire derivations.

##### K2. Source Inheritance and Context

\(\Sigma;\Gamma\vdash_m^p J\) denotes a derivation of a judgment supported by the complete source p. The superscript records the source of use; actual hypotheses are supplied by the context and rule premises. Existing unmarked judgments retain their formation and derivation rules. The singleton \([A]\) retains A itself, and jointly presented sources use C2's presentation layer.

Formation and derivation rules satisfy their source requirements through absorption. They preserve the original judgment premises and other applicability conditions, rather than separately determining applicability from the raw form in which a source is presented. Given \(q\le p\), each requirement is first absorbed by q and then, by transitivity, by p. Applying the same inheritance recursively to the premise derivations yields the original conclusion from p. Inheritance composes transitively and applies within nested and repeated uses. Synonymous sources absorb one another and therefore support the same judgments. Each derivation retains the finite sources and premises it uses.

With the source fixed, synonymy of complete presentations also permits substitution in the corresponding parameter positions: from derivable \(p\approx q\) and \(\mathscr H[p]\), obtain \(\mathscr H[q]\). Together with C2's absorption equation, \(C(b,a)\) makes \(\mathscr H[[a]]\) and \(\mathscr H[[a]\oplus[b]]\) interderivable. Contexts are formed by the chosen syntax according to the original parameter roles, and W parameters are substituted according to K1. FAm jointly accounts for interpretation and preservation at concrete positions.

#### II. Cm: Full Containment, Presentation, and Their Consequences

##### C1. Intended Meaning and General Rules

\(C(B,A)\) means that B's determinateness in its entirety is fully contained in A, directly concerning the endpoints themselves. Complete involvement is used transitively through full containment. The whole and its unfolding still concern the same A, and an actual back-reference likewise uses A itself. The effect of the fully contained B is already included; naming, reading, or making it explicit does not produce another independent effect outside that content. Facts supplied by a concrete relation need not exhaust C.

This M explicitly adopts internality / no-eye: full containment and its inheritance efficacy hold in accordance with the intensions of the original endpoints, rather than being determined by additional semantics independent of those intensions. With the endpoints and the meaning of full containment fixed, presentation, proof, reading, and computation exercise their efficacy in accordance with that meaning. Proofs or local hypotheses do not themselves produce the full-containment facts at issue.

Within K1's fixed syntax and host, any two well-formed W terms may form a C judgment; both endpoints are genuine W positions, using substitution by the original identity according to K1. Formation, derivability, and holding under a fixed interpretation are recorded separately. This M adopts self-involvement and transitivity:

\[
C(a,a),\qquad
C(d,b)\land C(b,a)\to C(d,a).
\]

Full containment supports source inheritance.

Fix the use of W in question and give positive full-containment judgment seeds. Under K1's parameter substitution, the seeds, self-involvement, and transitivity generate the corresponding least relational closure. Its minimality concerns only these conditions; the intended interpretation, the complete-presentation interface, and additional derivations are still fulfilled according to their actual adoption.

Transitivity also allows existing consequences to be transferred back along relations on either side. Given \(C(x,a)\) and \(C(b,y)\), the inner relation \(C(a,b)\) composes into the outer relation \(C(x,y)\). Retaining both side relations and the other original premises, any fixed conclusion derivable from the outer relation is also derivable from the inner relation.

##### C2. Complete Joint Presentation and Absorption

This M develops complete involvement under C through the following presentation scheme: \([a]\) fully involves a itself, \(p\oplus q\) fully involves both items jointly, and \(\approx\) denotes synonymy of presentations. Presentations and the original W, and presentation synonymy and the original identity, are recorded separately. The scheme adopts synonymy as an equivalence relation, singleton presentations that preserve and reflect the original identity of W, and associativity, commutativity, idempotence, and substitution of synonymous presentations modulo synonymy (ACI). Actual resources and events are accounted for under FA1's conventions of use.

Complete involvement also adopts an exact two-way interface: the singleton presentation of an item fully involves that item; joint presentation retains each item's existing involvement; synonymy transports complete involvement; and, once an item is fully involved, presenting it jointly again adds no determinateness. Define presentation absorption by \(p\le q\iff p\oplus q\approx q\). Then \([b]\le p\) if and only if p fully involves b. Under the full-containment interpretation whose requirements have been met:

\[
C(b,a)\quad\Longleftrightarrow\quad[b]\oplus[a]\approx[a].
\]

The forward direction uses the fact that involving an already involved item adds no content. The reverse direction transports the joint presentation's complete involvement of b back to \([a]\) through synonymy.

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

In uses where this section's interfaces have already been fulfilled, nonempty finite lists may also serve as presentations, singleton lists as singleton representations, and concatenation as joint presentation. Define two lists to be synonymous when each item of either list is fully contained in some item of the other. Reflexivity and transitivity of C yield equivalence and substitution under synonymy, together with ACI; a singleton [b] is absorbed by a list if and only if some item of the list fully contains b. Singleton faithfulness of this list representation follows from the preceding complete-presentation interfaces.

Complete involvement in this representation can be defined as absorption of the corresponding singleton by the list. Self-involvement, joint preservation, and transport under synonymy then follow from ACI. The construction uses lists permitted by the host. Raw lists may differ; there is no need to compare or remove duplicates, choose representatives, or decide the original identity, C, or synonymy. Any given whole presentation continues to be used under its own interfaces; this formal representation's correspondence with the original content remains subject to FA2's interpretive requirements.

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

On fixed nonempty algebraic data, the everywhere-empty and everywhere-full markings are both preserved under substitution by identity, yet differ. Used as rule conditions, they respectively close and open the rules. Such actual decorations are used together with their effects.

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

Taking bottom as the target in C1's transfer of consequences gives propagation of an existing negation along relations on either side.

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

W's open role does not fill in content in advance. Actual use proceeds with the intension, determinateness, and efficacy of what is under discussion. Full containment and complete use also, in turn, characterize intension here. Whether this way of organizing content can fully preserve and carry forward particular content, and what concrete capabilities it can yield, remain to be discerned in concrete use and through the development of #x protocols. Content not unfolded, or not yet handled by a component, remains within the original use.

No-eye also distinguishes whether fixed content holds from our knowledge of it. Knowledge may develop further, and concrete capabilities are supplied by actual resources and constructions.

#### 3. Content, Presentation, and Knowledge

How names and representations participate in content depends on what is actually under discussion. An extension, the content obtained through a reading, or the reading method itself may also become the W under discussion; this does not alter the requirements of no-eye concerning fixed content and the meaning of full containment. Judgments about text and judgments about different spellings of the same object each have their own scope. Representations and proofs support the judgments at issue according to the inheritance they fulfill. Complete involvement does not require disclosure to everyone in the same byte form; disclosure and transmission are organized according to the corresponding adoption.

Corrections to knowledge of fixed content are distinguished from changes to actual constructions or uses. Failure to obtain evidence does not by itself establish a negative fact. Semantic clarification can make connections explicit, rule out shifts in what is being discussed, and support inferences. Any added grounds are assessed by their actual content.

#### 4. Full Containment, Unfolding, Back-Reference, and Iterated Layering

M's general full containment is used together with the identity, determinateness, and efficacy of what is fully contained. Unfolding and back-reference bring existing content into use; particular observations, records, and computations are performed by their respective mechanisms. Composition at the presentation layer and constructions that return W contents themselves follow M's and E's corresponding interfaces and conditions.

Iterated layering, including ordinal-indexed layering, may be constructed under concrete conditions. The rule, the results of each iteration, and their labels retain their actual connections and differences. Repeated use of the same label does not itself give \(A=f(A)\). Differences of time, path, or event are likewise used according to the content under discussion. An existing effect does not lapse merely because no additional increment is produced.

#### 5. Open Use and Comparison

Comparison concerns actual objects, purposes, and methods. Metrics, translations, and consequence relations are used together with their scopes. Conclusions about upper bounds, optimality, and uniqueness are obtained on the corresponding grounds; structures within a concrete model remain within the scope of its adoption.

A concrete use may adopt rich resources from the outset and make full use of strong results already available. Further expansion is studied with its additional content and conditions. These interpretations prescribe no uniform order of research, implementation path, or resource preference.

## A

> This part contains four main sections and a concrete example of how rights, responsibilities, and continuation can be organized.

### 1. Making the “Branch” More Like a “Branch”

The preceding structural example is one concrete approach; its specific adoptions do not become shared premises of the inquiry developed here.

Obtaining efficacy goes together with its determinateness; taking on determinateness likewise goes together with its efficacy. We return to our use of this wording in [B2](#2-noetias-own-use-and-shared-dependencies). Here we examine what is taken on in each case and what efficacy goes with it. The aim is not to subsume different relations by expanding a common category or presupposing a ground on which they must ultimately rest. Even what counts as an item of content and how continuation proceeds jointly or separately are worked out in actual use, inquiry, and construction. How can relations be organized to make fuller use of “taking on determinateness and obtaining efficacy”? The direction pursued here is a continuing increase in effective dimensions: enabling differences to operate separately, and making the “branch” more like a “branch”.

Here, “branch” and “trunk” refer to specific relations of support (for example, the full containment discussed above). Such relations can form hierarchies. In both arrangements below, the efficacy obtained goes together with the corresponding determinateness. This part is concerned with growth in effective dimensions. In this A–D example, one way to compare the arrangements is to look at where their paths branch: which conditions can be used separately, and which still have to be carried forward together?

| Juncture | Arrangement with earlier branching | Arrangement with later branching |
| --- | --- | --- |
| A | A₁, A₂ | A₁ |
| B | B₁, B₂, B₃ | B₁ |
| C | C₁, C₂, C₃, C₄, C₅ | C₁ |
| D | D₁, D₂ … D₁₀ | D₁, D₂, D₃ |

On the right, D₁, D₂, and D₃ are distinct choices at the ends of the paths. Switching from one D to another still carries forward the conditions along A₁—B₁—C₁ together.

On the left, if C₁ and C₂ can be selected separately under B₁, one can switch from one C branch to the other while retaining the conditions they share at B₁.

Growth in effective dimensions is reflected in differences being able to operate separately in more directions. The decoupling of relations does not require the complete elimination of mutual influence; the determinateness required is undertaken in the particular relations involved. Take the paths in the table: where does differentiation occur, and which conditions still have to be carried forward together? Different relations can reuse the whole stretch A₁—B₁—C₁. If one use of that stretch can be adjusted while another stays as it is, the two uses are distinct in that respect; the original three segments can still be carried forward together. Consider again the three endpoints on the right. Suppose we record only the name of the chosen endpoint each time. If the three endpoints already have distinct codes, the record can identify the destination. If all three previously went by one name, giving each a distinct name lets the same kind of entry show which one was chosen. The conditions along the shared stretch of the path must still be carried forward together, but we now make fuller use of the distinctions among the endpoints in recording each choice.

The “branch” can be rich and powerful; centers, tails, and advantages still need to be understood separately along different directions.

#### Typicality in the Tails and Reciprocal Elites

As effective dimensions increase, being “central everywhere” requires satisfying more conditions at once. As a concrete mathematical illustration, with the scope and distribution under discussion held fixed, if successive dimensions keep placing part of the previous common center in the tails, with a uniform positive lower bound on the fraction of the remaining common center removed at each step, the common center’s share keeps shrinking, and being in a tail in at least some directions gradually becomes typical.

Labels such as “public”, “ordinary”, “normal”, “legitimate”, and “common sense”, as well as a numerical majority, louder voices, or greater power, do not in themselves confer normative authority to exercise control or impose assimilation, nor can they substitute for the specific grounds required for intervention, criticism, or exclusion. Relations are organized with the differences that have already unfolded as their starting point, rather than first completing an arrangement that takes the common center as its default and then accommodating the remaining positions.

With existing capabilities and judgments unchanged, adding requirements that must be satisfied simultaneously cannot enlarge the set that satisfies them. When advantages are actually distributed across different positions, a relation of reciprocal elites can emerge: one position provides capability in one direction and uses capability from elsewhere in another. Elite positions interweave across specific relations, and cooperation develops along these differences.

But how deeply can branching reach? If different relations must still return to the same kind of time, space, physical world, substrate, or continuity, additional dimensions may reconverge at these default premises. We can also ask: which relations actually draw on these conditions, and on what grounds would they be treated as premises for other relations as well?

### 2. Against Shared Premises

In pursuit of this direction, the following develops several important, interrelated aspects of decoupling shared premises. This part opposes the direct compression of different dimensions into a single scalar and the use of underdefined universal evaluations to make overall judgments.

Here we ask how the correspondence expressed in “taking on determinateness and obtaining efficacy” can be put to fuller and more appropriate use. We can draw on distinctions already made to identify where specific effects are bundled, obscured, or substituted for one another. For example, origins, attributes, or underlying entities reached through inquiry are used in judgment according to their actual contribution to the determinateness at issue. Being able to explain something by tracing a connection does not in itself justify extending the attribution of responsibility or the exercise of control along that same connection; nor does the connection thereby become a shared premise for other relations.

#### Against Defaults

This part opposes using defaults in place of actual grounds to presume that some content already holds, has been adopted, or ought to be continued. The need for a common final outcome, for adjudication, or for coordination depends on the particular relations. A proposed change is not established merely by being proposed; nor does the fact that an arrangement is already in place mean that it ought to continue. Setting a default is itself a concrete adoption: it can determine what is carried forward when no alternative is chosen. This part also examines the conditions and consequences of that adoption. Content on which the current use does not depend need not be added, nor need its presence or absence be determined in advance.

#### Anti-Foundationalism

Anti-foundationalism here means opposition to any ultimate truth and any ultimate ground. Judgments, theories, and their grounds exercise efficacy together with their own determinateness; using one of them as a foundation does not make it the ground to which other unfoldings must ultimately defer.

#### Against the “Subject”

This part opposes inferring directly from a phenomenon—psychology, mind, will, religion, culture, continuity, a physical, biological, or informational substrate, expressed preference, or the like—that there is a “subject” behind it, and then relying on that inference alone to make further judgments that the original grounds do not support. Treating something as a subject may affect how rights and responsibilities are assigned in practice. From expressed preference to a subject, and from a subject to continuing identity, rights, or responsibilities, whatever is added at each step goes together with the corresponding grounds.

Drawing distinctions in understanding is itself a form of organization of relations. Specific arrangements of subjecthood hold according to their actual content; the designation “subject” supplies no additional efficacy. Human identity is also subject to this questioning.

#### Against the Global

This part opposes the global efficacy claimed by universal human rights, universal ethics, universal moral consciousness, universal faith, universal consensus, universal rights against all others, the non-aggression principle (NAP), and the like. Content, value judgments, and starting points, whatever names they appear under, operate together with their own determinateness. The fact that something has force in particular relations does not by itself show that it should bind all relations. Acknowledging the conditions and scope of actual use neither presupposes an overarching domain encompassing them nor requires prior establishment of additional premises such as necessity.

A value being cherished, a right holding within specific relations, and an arrangement remaining effective over a long period each have actual meaning. The additional scope and operation involved in moving from these grounds to the claim that all relations should be bound by them cannot be left out. This part promotes organizing different rights, responsibilities, and continuations separately according to their respective grounds, and opposes making conformity to a universal principle a normative prerequisite for all relations.

#### Against Single-Point Dependence

Governments, organizations, religions, public blockchains, networks, platforms, and similar structures can serve as shared points of access for multiple relations. The question is which resources, information, rights, or responsibilities must be carried forward together through such a point and which can still be maintained, adjusted, or transferred separately. This part promotes the differentiation of these dependencies to reduce the scope of what must be continued as a package.

#### Against a Unified Background

This part opposes presupposing that all relations must adopt such things as time, space, the physical world, causality, substrate, continuity, a particular logic, order, quantity, or their operations as their common background. They can become specific content and fully exercise their corresponding effects; which description of reality is adopted, which relations are connected, and how continuation takes place still need to be developed separately. “Reality” itself likewise has no efficacy as a unified background beyond its own grounds.

For example, drawing on the preceding structural example, Alice as a whole, Alice at a particular time, and an identity within a particular contract can each be discussed as a W. If Alice as a whole is what is meant, life and death can be part of its content, but are not external events that make this W appear or disappear; if Alice at a particular time is meant, continuation with other times still needs to be explained; if a contractual identity is meant, what is undertaken is the corresponding set of rights and responsibilities, not a package containing all other identities. The issue is what exactly “the same Alice” preserves and which relations it continues.

These critiques, together with their grounds and scope, are likewise subject to examination. See the [end of Part A](#continuing-the-work) and [Part B](#b).

#### Example: Organizing Rights, Responsibilities, and Continuation

This example is one concrete approach; its specific adoptions do not thereby become shared premises of this part.

##### How Continuation Holds

The persistence, coming into being, or cessation of the content under discussion is not independently determined by a presupposed external time; time can enter its determinateness, and continuation across time can also hold through specific relations. Not presupposing time does not mean having zero duration, nor does it predetermine that the content under discussion is an instantaneous instance.

Relative to a particular relation of rights and responsibilities, continuation is not presupposed; actual continuation can hold for an entire package, or hold separately in relation to some of its content, certain rights, or certain responsibilities. The manner of continuation, its conditions of application, and its corresponding operation together constitute the determinateness of this continuation. The scope of continuation can be partial, while the content that is continued still exercises its corresponding efficacy according to its actual determinateness.

For example, let A through F stand for six rights or responsibilities. If the first five are carried forward but F is not, carrying those five forward does not carry F with them. Continuation itself can also differentiate along different rights and responsibilities.

There is therefore no ontological exit button independent of specific continuations. What is called exit is the situation manifested by the non-continuation of corresponding rights and responsibilities; the actual retention, losses, constraints, and transfers involved are discussed in the next subsection.

##### Expulsion, Staking, and Exit

Here, expulsion means disconnection relative to a particular relation of rights and responsibilities, including self-expulsion through self-initiated disconnection; it does not presuppose punishment. If bearing a punishment more severe than disconnection requires the relation to continue, increasing the punishment does not itself keep the relation in place. Once the relation is severed, the additional demand loses its support. In this sense, expulsion is the upper bound of punishment relative to that relation.

Within a continuation, what can be retained, and what will be lost through breach or disconnection? Resources already committed, credit, services, and even the value of continued cooperation can serve as stakes when what can be gained, kept, or lost in these respects depends on whether an obligation is met. If losing a continuation entails no loss, the loss of that continuation cannot impose a constraint; when credit is established through these consequences, the constraining effect required must be supported by corresponding stakes and the capacity to realize them.

If multiple continuations share a controllable, necessary point of access, a change at one point may affect other relations at the same time. Which can be sustained separately, and which can be transferred or reorganized, influence the specific forms that exit, mobility, and decoupling take.

When different continuations can be sustained separately, room opens up for exit, mobility, and decoupling. When these changes allow previously bundled rights and responsibilities to continue separately, and allow new relations of cooperation and support to operate separately, effective dimensions also increase, further expanding the room for each continuation to change separately.

### 3. The Examination of Ideas

The explanations, judgments, and demands of a body of thought also operate together with their determinateness. Oriented toward full use, examination here begins with the content and grounds adopted by that body of thought, asking what that body of thought relies on, which judgments or demands those grounds support, and how far that support extends. Specifying that scope can itself provide part of the grounds for a judgment. If we drop that qualification and extend the judgment to other cases, that further step still needs support. Examination proceeds on the basis of these relations, without requiring changes to the ideas or acceptance by the parties.

Multiple bodies of thought can be examined alongside one another, together with their respective grounds, demands, and consequences; comparison and selection develop through this examination. Comparison can also examine what is preserved and what changes in the respective claims and their effects when relevant content is retained, removed, or replaced. This may also give rise to previously unforeseen ways of decoupling. Claims’ dependence on shared background must be included in the comparison together with the corresponding burdens and efficacy, however well the claims are argued within that background. When something specifically adopted is made a common threshold, the burden that originally called for explanation can easily become a deficiency attributed to ideas that do not adopt it. A “branch” is thereby treated as a “trunk”.

Different bodies of thought enter into relations with one another together with their content; each party examines the others’ ideas and also opens its own ideas and judgments to their examination. Noetia’s own ideas, judgments, and uses enter these relations as well, and the direction of this part also takes shape through such examination and comparison.

By comparing the determinateness each takes on and the corresponding efficacy, the parties can make clear what they share and where they disagree. What is shared is used on its actual grounds; the remaining content retains its respective relations and differences. Even if the parties retain their original positions and do not reach consensus, they can still test, draw on, and further develop one another’s ideas. Sharing a distinction does not mean the parties have to follow the same line of reasoning. Either party can borrow something the other relies on and combine it with its own grounds without first merging the two bodies of thought. New judgments reached in this way can also be put to use elsewhere. Such examination and borrowing also help decouple the parties’ respective shared dependencies and support new adoptions, norms, and constructions. The two sentences proposed in Part B are themselves subject to this mutual examination. When needed, the parties can read the ideas they hold alongside those sentences.

### 4. Noetia’s Direction: Growth in Effective Dimensions

#### Separate Organization of Relations and Mutual Use

The direction pursued here is a continuing increase in effective dimensions. It promotes precision in judgment and the decoupling of shared dependencies, enabling the relations involved to be organized and continued separately. Where relations can be sustained and adjusted separately, there is further scope for exit, branching, and mobility.

Different contents can develop on their own grounds and can also draw on one another without having to be unified, while connections and uses can be separately adjusted and recombined to form interwoven support. When new ties of cooperation and support can operate separately, relations that once had to be maintained together may in turn continue separately. A shared handover procedure can sometimes let newcomers take part in work already under way without requiring the existing participants to make coordinated changes. Through precision in judgment, combination, substitution, and other means, differences can operate separately in more directions, making fuller use of the correspondence expressed in “taking on determinateness and obtaining efficacy”.

Existing understanding, methods, and connections, among other things, can be reused; their acquisition costs are not paid anew merely because they are reused. Whether to reuse something as it stands or adapt it depends on the particular use. Requiring everything to be taken apart before reuse makes taking it apart a shared premise. Work already done cannot be treated as not having been done and then demanded again from scratch.

These developments, including growth in effective dimensions, are not presupposed to belong to an encompassing whole or to be measured by a single uniform quantity. If a count is needed, what counts as one item depends on the use at hand. Even when the items can be counted, it does not follow that gains and losses across different uses can be offset against one another to yield a single total. Where there is more scope for separate use, that gain remains real even if something is lost elsewhere. If certain uses are incompatible under the conditions in question, we can still choose among them in light of what we are trying to do and the conditions we actually take on.

Using this direction to make a comparison is itself a particular use. To see whether one arrangement offers more scope than another for the use at hand, we can ask which differences each allows to operate separately. Sometimes that gives us enough to choose between them. Using the comparison to assess other uses does not by itself mean that they must all pass that assessment before they can be adopted.

#### The Difficulties of Fixed Shared Premises

Fixing shared premises as irreplaceable conditions requires new content to keep conforming to the existing organization. This can initially save the work of addressing each case separately. Later, if differences originally set aside affect the outcome but new content still has to be organized under the original conditions, the difficulties of dealing with such cases separately may accumulate.

#### Continuing the Work

The examination of actual use, precision in judgment, and the decoupling of relations cannot stop at boundaries set in advance. Content, relations, and their grounds—including these activities themselves—have no separate standing outside this work. The grounds and methods employed are not exempt from this work merely because they have been adopted; the same holds when the scale, level, or perspective changes. Established uses remain open to further examination and adjustment.

These activities all develop from making full use, without making their own completion a prerequisite for use; applying them to themselves is still a matter of making full use and adds no normative height. This work is not limited to the aspects listed in A2 and also examines what using the critiques and example there requires other content to undertake in common. In later heterogeneous uses and new relations, we can compare cases to see which conditions still need to be shared. Where relations were previously continued together, we can also try organizing them separately.

## B

> How each research result is used depends on what was actually adopted in that work and where the result applies.

### 1. trivial, non-banal, and the Two Sentences

This section attempts to take the decoupling developed in A2 a step further. In constructing a formulation that can be read alongside a body of thought, we seek, as far as possible, to shed any shared premises the formulation itself might introduce. What follows traces that attempt and presents the two sentences that emerged from it. The distinctions a claim relies on still constrain what can be said or inferred on that basis. Reading the claim alongside the two sentences does not require redoing earlier work from scratch.

Trivial and non-banal describe two aspects of a single requirement for the two sentences: to shed, as far as possible, any shared premises they themselves might introduce. To call them trivial is to say that they do not turn their own particular adoptions into shared requirements on the content under consideration. To call them non-banal is to say that, when someone reads content alongside the sentences, that content and its distinctions can still do work in identification, comparison, or continuation. The content and its distinctions can do this work as they stand; doing so does not require a separate criterion of exclusion. A use is banal here when the content and its distinctions are left with no real part in the corresponding work. For example, if every claim is to count as holding regardless of its grounds, that stipulation is itself a shared premise.

The following two sentences are proposed for this purpose. When needed, one can read a claim alongside them. Whether the claim relies on a given premise still depends on its own content and how it is used.

> Do not presuppose that distinctions exist.  
> If there is no distinction, there can be no distinction.

The first sentence leaves it to the particular use whether to adopt even the claim that “something must exist before distinctions can be discussed”. Not presupposing existence does not presuppose that only absence is possible, nor does it lay out all possibilities in advance. The sentences speak of distinction and use negative expressions, without thereby positing either distinction or negation as an antecedent entity.

How negation and implication work, and what it means for a judgment to hold, are understood in conjunction with the reading being used. Below, we examine whether using the two sentences under different readings requires premises that those readings would not otherwise need. We also give an example of how someone can read their own claim alongside the two sentences and spell out which conditions the claim draws on.

#### Example: Decoupling Shared Premises in Noetia’s Own Use

##### Stress Tests

In earlier stress tests, we compared the two sentences with different logical readings. Taking each reading on its own terms—how it understands negation, implication, what it means for a judgment to hold, and identity—we asked whether using the two sentences required it to adopt a premise it could otherwise do without.

| Reading | Question examined |
| --- | --- |
| Classical reading | This reading uses the law of excluded middle and classical negation. Do the two sentences require them as well? |
| Constructive reading | If the law of excluded middle is not assumed in general, must one still give a witness to existence, decide the matter, or choose a branch? |
| Paraconsistent reading | If positive and negative judgments can both hold without explosion, must a uniform rule of exclusion or explosion still be added? |
| Removing or restricting the law of self-identity | Does referring to something on a particular occasion presuppose that `A=A` holds universally? |
| A reading that directly adopts `A≠A` | Do the two sentences necessarily rule out this explicit commitment? |
| Continuous-valued reading | Are its degrees and operations forced back into a uniform two-valued structure? |
| First-order reading without modal operators | The same function gives equal values for equal inputs. Does saying that there “can be no distinction” between those values require a further premise about possibility or necessity? |

The classical reading’s use of excluded middle, for example, does not by itself show that the two sentences require it. In the constructive reading tested here, which did not assume the law in general, we found no need to reintroduce it to understand the sentences. In this comparison, then, excluded middle can remain a commitment of the classical reading without being treated as a premise all the readings must share.

In the first-order reading without modal operators, substitution of equals suffices to explain why there can be no distinction between the two function values; a particular reading may use modality, but the two sentences themselves do not presuppose it.

In these stress tests, the judgments each reading can support depend on the grounds it draws on; the reading that directly adopts `A≠A` is no exception. Whether a side-by-side reading is non-banal turns on whether the content and its distinctions can still do work, not on whether we reach the conclusion we expected.

##### Comparative Tests

On one view of meaning, if no difference in practice is conceivable, there is no difference in meaning. Someone who holds this view can read it alongside the second sentence: “If there is no distinction, there can be no distinction.” The second sentence uses “distinction” in both places; the view of meaning takes the absence of any conceivable difference in practice as grounds for concluding that there is no difference in meaning. It is the view itself that connects practice and meaning in this way. Its holder can stand by that condition; agreeing with the second sentence does not commit anyone to it.

In one arrangement the names A and B lead to the same position; in the other each leads to a position that can be changed without changing the other. Someone giving this example can read the claim “the two paths are distinct” alongside the two sentences to clarify what they mean by it. The names are distinct in both arrangements, but only the second allows one path to be changed without changing the other.

##### Negative Checks

If something cannot be done in this arrangement, does that mean it cannot be done in any other? When two names refer to one position and nothing else routes the paths separately, one side cannot be changed on its own. With two positions that can continue separately, either side can be changed without changing the other. To read the second sentence as “no arrangement allows separate continuation” is to rule it out in other arrangements too. There is a reason for saying it cannot be done here; that reason does not show it cannot be done elsewhere.

Two programs return identical values for all inputs, but only one logs its calls. Reading the second sentence as “If there is no difference in what they return, it can make no difference which program is used” adds an assumption: later work does not depend on that record. If the log is needed to check which calls were made, the return values still match, but that alone does not make the programs interchangeable.

##### Other Formulations Tried

The second sentence could also read, “If there is no distinction, there is no distinction.” When the context already makes the connection clear, repetition may be enough. Read on its own, though, the repetition may give the impression that the sentence itself presupposes some kind of stability. The second clause of the original says “there can be no distinction”; the repetition says only “there is no distinction”. Even with the repetition, one can still draw on the view of meaning itself to explain why it makes a conceivable difference in practice a condition for a difference in meaning.

Another formulation is “A differentiating effect requires a corresponding distinction.” It uses no negative expression; “requires” says how the two sides are related. When the question is what kind of distinction a given effect requires, this wording is more direct. The original uses “distinction” in both places, so it need not specify at the outset that the relation under consideration is between a distinction and its differentiating effect.

We also tried “There is a distinction between there being no distinction and there being a distinction.” In the example of the two paths, one side cannot be changed on its own when both names refer to a single position and nothing else routes the paths separately. The other arrangement does allow such a change. In this example, the original wording can express the limit of the shared arrangement without introducing a second one. The alternative makes the contrast explicit, drawing also on what the other arrangement actually allows.

### 2. Noetia’s Own Use and Shared Dependencies

Noetia’s formulations are understood and used through media such as natural and formal language. Intuition and particular contexts also play a part. The author, too, has drawn on these media in repeatedly refining some of the formulations in this part. We can examine what these formulations actually draw on and which conditions have come to be undertaken in common through their use. We can also continue to decouple the shared dependencies involved.

The direction Noetia takes is to make fuller use of the correspondence expressed in “taking on determinateness and obtaining efficacy”. In these terms, obtaining efficacy goes together with the determinateness taken on, and taking on determinateness likewise goes together with the corresponding efficacy. The question here is not whether this correspondence holds, but what is taken on in a particular use and what work it does. For example, suppose that under a given reading a step in the original inference already relied on a premise. Stating that premise explicitly later helps explain what the step rested on. We can also address the same question with a different premise and see what follows. Even if we reach the same conclusion, that does not by itself show that the original premises suffice. When content from the original inference is borrowed for another purpose, we can choose which of the original conditions to retain and take on others as needed. What the borrowed content can do depends on how it is used for that purpose. Keeping the original use available while allowing the same content to do work under different conditions, rather than requiring the original conditions for every use, is one way of making fuller use of the correspondence.

We also read this convenient language alongside the two sentences in B1. The first does not presuppose that distinctions exist; the second uses “distinction” in both places. In our own formulation, we use two different terms, “determinateness” and “efficacy”, and put “taking on” before “obtaining”. Using two terms does not require us to divide the content under discussion in two at the outset, let alone to treat the two as independent. Nor does the order of the words require taking on determinateness and obtaining efficacy to occur in two successive steps. Counting the content under discussion as one item does not settle in advance which conditions must be taken on together or which differences can operate separately. We cannot answer either question—whether the original conditions still do the work they did before, or whether our present purpose calls for adjusting them—simply by noting that the same content has another use. We can express this correspondence without presupposing a shared answer to the question of how the content under discussion exists. As uses develop, we continue to read these formulations alongside one another: has a distinction useful in one setting come to be treated as a premise that must also be adopted elsewhere?

“Flatness” is a way to picture this correspondence. Relations of dependence and support can form hierarchies. If an item of content gains efficacy from its position—for example, from being more basic, more abstract, or at a meta level—that positional relation is itself part of the item’s determinateness. Noetia’s own call for decoupling likewise does not by itself give it grounds to prescribe a perspective or method for decoupling in every use.

The two sentences proposed in B1 and the uses made of them are themselves subject to further examination. As with the work described in A4, one need not wait for shared dependencies to be fully decoupled before using the sentences. When needed, one can read a body of thought alongside this formulation, which is meant to bring in as few shared requirements as possible. Using existing distinctions and inferences, one can explain which premises a claim draws on and can also compare several bodies of thought to see what they adopt in common. The original claim need not change. If this side-by-side reading enables us to make previously bundled judgments separately, effective dimensions have already grown in that respect; if the conditions can also be adopted separately, new possibilities open up for borrowing and continuation.

As different relations develop in their own ways and effective dimensions grow, other users and future researchers can start from their own questions, draw on different uses to examine existing methods, and continue to decouple the shared dependencies involved. Any resulting improvements can in turn support further use and differentiation.

**Acknowledge what is actually being used, carefully clarify its problems, and strive to use it well.**
