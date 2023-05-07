Download Link: https://assignmentchef.com/product/solved-mlcs-homework2-ef-games-and-non-expressibility
<br>
<ol>

 <li>EF-games and (non)-expressibility</li>

</ol>

<strong>Exercise 1.1. </strong>Prove using EF-games that the property <em>P </em>= “having domain of finite cardinality” is not finitely expressible in any first-order language over the class of all structures. Is the property finitely expressible over finite structures?

<strong>Exercise 1.2. </strong>Consider the following two structures G<sub>1 </sub>and G<sub>2 </sub>for the language of graphs: Write at least

two sentences distinguishing the two structures. Discuss the EF-game played on these structures: for what <em>k </em>can the Duplicator win the <em>k</em>-rounds game? For what <em>k </em>can Spoiler win?

<strong>Exercise 1.3. </strong>Consider the property of being an Eulerian graph. This is equivalent to the fact that every node has even degree. Use the following structure to prove that the Eulerian (boolean) query is not finitely expressible in the language of graphs over finite graphs:

G<em><sub>n</sub></em>: The set of vertices is {<em>a</em><sub>1</sub><em>,…,a<sub>n</sub>,v,w</em>}. The only edges are as follows: each <em>a<sub>i </sub></em>is connected by an edge to <em>v </em>and to <em>w</em>. Show that for every <em>m </em>≤ <em>n </em>the Duplicator wins the <em>m</em>-moves game on G<em><sub>n </sub></em>and G<em><sub>n</sub></em><sub>+1</sub>.

<strong>Exercise 1.4. </strong>Express the following queries with first-order sentences in the language of graphs:

<ul>

 <li><em>G </em>is a complete graph.</li>

 <li><em>G </em>has two isolated nodes.</li>

 <li><em>G </em>has degree at least 2.</li>

 <li><em>G </em>contains a path of length 4.</li>

</ul>

<strong>Exercise 1.5. </strong>Consider the following two structures (for the language of graphs):

<ul>

 <li>G<sub>1 </sub>is a cycle of length 4<em>n</em>;</li>

 <li>G<sub>2 </sub>consists of two disjoint cycles of length 2<em>n</em>.</li>

</ul>

Analyze the EF games on these structures for <em>n </em>= 1<em>,</em>2 and write a sentence of minimal quantifier rank distinguishing the two structures for <em>n </em>= 1<em>,</em>2.

BONUS: Formulate a generalization of your observations and prove that the Connectivity query is notexpressible in the language of graphs over finite graphs, using EF-games.

<strong>Exercise 1.6. </strong>Consider the following two graphs:

<ul>

 <li>G<sub>1 </sub>is a line of length 4<em>n</em>;</li>

 <li>G<sub>2 </sub>consists of a line of length 2n and a cycle of length 2n (the two components are disjoint).</li>

</ul>

Analyze the EF games on these structures for <em>n </em>= 1<em>,</em>2 and write a sentence of minimal quantifier rank distinguishing the two structures for <em>n </em>= 1<em>,</em>2.

BONUS: Formulate a generalization of your observations and prove that the Acyclicity query is notexpressible in the language of graphs over finite graphs, EF-using games (a graph is acyclic iff it does not contain a cycle).

1

<strong>Exercise 1.7. </strong>Consider the proof of the following Theorem in Handout 8: if A and B are finite linear orders of size larger than 2<em><sup>k </sup></em>then A ≡<em><sub>k </sub></em>B in the language L = {<em>min,max,&lt;</em>}.

<ul>

 <li>Show by an example that the proof can fail if the Duplicator answers a move of the Spoiler without guaranteeing conditions (1) and (2) in the Inductive Hypothesis but only condition (3) (partial isomorphism).</li>

 <li>Does the proof work if A and B are of cardinality exactly 2<em><sup>k </sup></em>and 2<em><sup>k </sup></em>+ 1, respectively?</li>

 <li>What can you say about (bounded) elementary equivalence of finite linear orders A and B if they have the same cardinality?</li>

</ul>

<ol start="2">

 <li>Other</li>

</ol>

<strong>Exercise 2.1. </strong>Let <em>S </em>be a class of formulas over a finite relational language L. We denote by <em>BC</em>(<em>S</em>) the class of all Boolean Combinations of formulas in <em>S </em>(i.e., the class of all formulas obtained by applying Boolean connectives ¬, ∧, ∨ to formulas in <em>S</em>). A class <em>S </em>of formulas is finite modulo logical equivalence if there exists a finite subset <em>S</em><sub>0 </sub>⊆ <em>S </em>such that for each <em>F </em>∈ <em>S </em>there exists a <em>G </em>∈ <em>S</em><sub>0 </sub>such that <em>F </em>≡ <em>G</em>. Show the following two points:

<ul>

 <li>Let <em>T </em>= <em>BC</em>(<em>S</em>). If two structures A and B satisfy the same formulas in <em>S </em>then they also satisfy the same formulas in <em>T</em>.</li>

 <li>If <em>S </em>is finite modulo logical equivalence then <em>T </em>is finite modulo logical equivalence.</li>

</ul>

<strong>Exercise 2.2. </strong>Let L be a finite vocabulary with no constant or function symbols. The atomic formulas in some fixed set of variables <em>x</em><sub>1</sub><em>,…,x<sub>n </sub></em>are obviously finitely many. Let A be a structure adequate for L and (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) and (<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) be two vectors in <em>A</em>. We write (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) ≡<em><sub>at </sub></em>(<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) iff the two vectors satisfy the same atomic formulas in A. It is easy to observe that in this case they also satisfy the same quantifier-free formulas, a fact we denote by (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) ≡<em><sub>qf </sub></em>(<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>).

Let <em>T </em>be a theory in L. We say that <em>T </em><strong>admits Quantifier Elimination </strong>if for all formulas of the form

∃<em>x<sub>n</sub></em><sub>+1</sub><em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub>,x<sub>n</sub></em><sub>+1</sub>) there exists a quantifier-free formula <em>G</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>) that is <em>T</em>-equivalent to it.

We say that <em>T </em><strong>has the Extension Property </strong>if the following holds: for all models A of <em>T</em>, for all (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) and (<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) in <em>A<sup>n</sup></em>, if (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) ≡<em><sub>at </sub></em>(<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) then for any <em>a<sub>n</sub></em><sub>+1 </sub>∈ <em>A </em>there exists a <em>b<sub>n</sub></em><sub>+1 </sub>∈ <em>A </em>such that (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub>,a<sub>n</sub></em><sub>+1</sub>) ≡<em><sub>at </sub></em>(<em>b</em><sub>1</sub><em>,…,b<sub>n</sub>,b<sub>n</sub></em><sub>+1</sub>).

<ul>

 <li>Show that for each (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) in <em>A<sup>n </sup></em>there exists a formula <em>H</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>) with free variables <em>x</em><sub>1</sub><em>,…,x<sub>n </sub></em>such that for all (<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) in <em>A<sup>n</sup></em></li>

</ul>

(<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) ≡<em><sub>at </sub></em>(<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>) if and only if A |= <em>H</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>)[<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>]<em>.</em>

<ul>

 <li>Show that if <em>T </em>admits Quantifier Elimination then <em>T </em>has the Extension Property.</li>

</ul>

BONUS: Show that if <em>T </em>has the Extension Property and is semantically complete then <em>T </em>admits Quantifier Elimination.

<strong>Exercise 2.3. </strong>Show that the theory <em>DLO </em>has the Extension Property (defined in the previous Exercise).

<strong>Exercise 2.4. </strong>Show that the Random Graph Theory has the Extension Property (defined above).