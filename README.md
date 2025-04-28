# cs550-exercise-1-solved
**TO GET THIS SOLUTION VISIT:** [CS550 Exercise 1 Solved](https://www.ankitcodinghub.com/product/cs550-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118151&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS550 Exercise 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Exercise 1

1 Propositional Logic

Exercise 1 (Sheffer Stroke). The operator ↑, also known as Sheffer stroke or NAND gate, has the following truth table:

↑ 0 1

0 1 1

1 1 0

Show that any propositional formula with language {∧,∨,→,¬,0,1} can be equivalently expressed using only the language {↑}

Exercise 2 (Decision Procedure for SAT). Recall the “Decision and Simplification” proof system (InferD):

CA Simp with F ⇝ F′

where ⇝ is the result of applying a finite sequence of any of the following simplifications anywhere in the formula:

0 ∧ F ⇝ 0 F ∧ 0 ⇝ 0 1 ∧ F ⇝ F F ∧ 1 ⇝ F

0 ∨ F ⇝ F F ∨ 0 ⇝ F 1 ∨ F ⇝ 1 F ∨ 1 ⇝ 1

¬0 ⇝ 1 ¬1 ⇝ 0

For each of the following formulas, express it using only the connectors ¬, ∧ and ∨. Then prove they are tautologies by assuming their inverse and deriving 0 using InferD.

1. ((a → b) → a) → a

2. ¬(a ∧ b) → (¬a ∨ ¬b)

3. ((¬a → b) ∧ (a → b)) → b

Exercise 3 (if-then-else).

1. Consider the two following small programs:

1 def f1(a:Boolean, b:Boolean, c:Boolean): Boolean = {

2 if a || b then

3 if b &amp;&amp; !a then

4 b &amp;&amp; c

5 else

6 !b &amp;&amp; c

7 else

8 c

9 }

1 def f2(a:Boolean, b:Boolean, c:Boolean): Boolean = {

2 if c then

3 if a then

4 !b

5 else true

6 else false

7 } ensuring ( == f1(a, b, c))

Are they equivalent on all inputs? Show that they are or aren’t by expressing those programs as propositional formulas. Note that the ensuring clause is automatically proved or disproved by Stainless!

2. Can any formula be expressed with only if a then b else c, where a, b and c are recursively constructed the same way? What if a is restricted to be a variable?

Exercise 4 (Propositional Tautologies). For each of the following propositional logic formulas determine whether it is valid or not. If it is valid, prove it (using any acceptable mathematical argument of your choice), otherwise give a counterexample. (From The Calculus of Computation by A.R.

Bradley and Z. Manna.)

1. (P ∧ Q) → P → Q

2. (P → Q) ∨ (P ∧ ¬Q)

3. (P → Q → R) → P → R

4. (P → Q ∨ R) → P → R

5. ¬(P ∨ Q) → R → ¬R → Q

6. (P → Q) → P → Q

7. ((P → Q) → P) → P

8. ((P → Q) → P) → Q

9. (¬Q → ¬P) → P → Q

10. (¬R → ¬Q → ¬P) → P → Q → R

11. (P ∨ Q) → (P ∨ ¬Q) → (¬P ∨ ¬Q) → P

12. (P ∨ Q) → (P ∨ ¬Q) → (¬P ∨ ¬Q) → Q

13. ¬(P ∧ Q) → P → ¬Q

2 Transition Systems and Invariants

Notation: M = (S,I,r,A) is a transition system where S are the states, I ⊆ S the set of initial states, r ⊆ S × A × S and A is the input alphabet.

Exercise 5 (Special Invariants). Prove the following:

1. S is an inductive invariant. It is the largest among all invariants.

2. Reach(M) is an inductive invariant.

3. Reach(M) is the smallest of all possible invariants.

Exercise 6 (Closure of Invariants). A set of closed under an operation if applying the operation to elements of the set gives the result in the set. For example, the set of even natural numbers is closed under addition, whereas the set of odd natural numbers is not closed under addition.

Is the set of all invariants of M closed under the following operations:

1. union

2. intersection

3. complement with respect to S

4. operation f : 2S → 2S defined by f(X) = Reach(M) ∪ (S X) Answer the same questions about all inductive invariants of M.

3 Relations

We consider relations (where A is just arbitrary set, nothing to do with the input signals of the transition systems). Here X ⊆ A. Define:

∆X = {(x,x) | x ∈ X}

r−1 = {(x,y) | (y,x) ∈ r}

X • r = r[X]

ran(r) = {y | ∃x.(x,y) ∈ r}

Exercise 7 (Relation Identities). Prove the following or give a counterexample.

1. (X • r1) • r2 = X • (r1 ◦ r2)

2. (r ∪ s) ◦ t = (r ◦ t) ∪ (s ◦ t)

3. (r ∩ s) ◦ t = (r ◦ t) ∩ (s ◦ t)

4.

5. X • r = ran(∆X ◦ r)

6. then and .

7. then and .

Exercise 8 (Transitive relations). Given a relation r ⊆ A × A, prove that r is transitive if and only if r ◦ r ⊆ r.

Exercise 9 (Symmetric relations). Recall that a relation r ⊆ A×A is symmetric if ∀x,y ∈ A. (x,y) ∈ r ⇒ (y,x) ∈ r.

Now let r be an arbitrary relation. Prove that r−1◦(r∪r−1)∗◦r is symmetric.

Exercise 10 (Transitive closure). Recall that we define the powers of a relation r ⊆ A × A as follows:

r0 = △A, r1 = r, and rn+1 = rn ◦ r

We showed that the reflexive and transitive closure r∗ = Sn≥0 rn is the smallest reflexive and transitive relation on A containing r. Show that for any relation r on a set A, (r∪r−1)∗ is the least equivalence relation containing r. Precisely, show that

(i) (r ∪ r−1)∗ is an equivalence relation, and

(ii) if s is an equivalence relation containing r, then (r ∪ r−1)∗ ⊆ s.

4 Finite State Machines with Boolean Variables

Exercise 11 (Finite State Machines with Boolean Variables). We consider in this exercise finite-state machines enriched with boolean variables (FSM for short). Formally, an FSM is a pair (V,Q,δ) where:

V is a finite set of (boolean) variable names,

Q is a finite set of states,

For every pair of states p and q, δ(p,q) is a propositional formula containing variables from V and V ′, where V ′ is a copy of V with primed variable names.

A configuration of the FSM is determined by a pair (q,m) where q is a state in Q, called the control state, m : V → {⊤,⊥} is a mapping from variable names to true or false.

The FSM can move from a configuration (p,m) to (q,m′) if the formula δ(p,q) is true when we interpret every variable from V using the mapping m, and every variable in V ′ using m′. We define the relation r ⊆ (Q×V → {⊤,⊥})×(Q×V → {⊤,⊥}) to contain all such pairs of configurations (p,m) and (q,m′).

Consider now the FSM in Figure 1, inspired from Peterson’s algorithm (we recommend reading this page before the exercise). We made use of two conventions when drawing the figure:

When there is no transition drawn from a state p to a state q, we mean that δ(p,q) = ⊥ in the FSM.

When a primed variable X′ does not appear in a transition, we leave the variable unchanged, meaning that there is an implicit conjunct X′ ↔ X in the transition.

For example, the transition from (0,0) to (0,1) can be taken regardless of the initial mapping of boolean variables. It changes variable A to ⊤, and leaves the variables B and C unchanged. The transition from (2,0) to (3,0) can only be taken when the mapping of boolean variables respects ¬A ∨ C, and leaves all variables unchanged.

Does there exist mappings m and m′ such that the FSM can move (using multiple steps) from configuration ((0,0),m) to ((3,3),m′), i.e. such that (((0,0),m),((3,3),m′)) ∈ r∗?

Figure 1: A finite-state machine with boolean variables {A,B,C}.
