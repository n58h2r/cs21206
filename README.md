java c
CS 3800
Spring 2024
Homework 6
3. [14 Points] Pumping in regular languages. For each of the following languages (over Σ = {0, 1}), give its minimum pumping length and justify your answer.
(a) 1*0*
(b) ε
(c) (01)*(01)
(d) (111)*0*
(e) {w ∈ {0, 1}* | w contains neither 000 nor 111 as substrings}
4. [10 Points] Proving that languages aren’t regular. Use the Pumping Lemma to show that the following languages over Σ = {a, b} are not regular. In each case, carefully describe the string that will be pumped and explain why pumping it leads to a contradiction.
(a) {a a a bn an| n ≥ 0}
(b) {w w | w ∈ Σ*}
(w stands for w with each occurrence of a replaced by b, and vice versa.)
5. [5 Points] Regular or not? Is the language {aibj| 0 ≤ i ≤ j} regular or not? Carefully prove your answer. Aim for a proof that is as simple as possible. You may use any results from class.
6. ⋆[6 Points] Halfway through. Given a language A ⊆ Σ*, we write A2/1 to denote the set of left halves of words in A. That is
A2/1 = {x ∈ Σ* | ∃y (y ∈ Σ* and |x| = |y| and xy ∈ A)}
For example, if A = {ε, a, ba, aba, aabb}, then A2/1 = {ε, b, aa}.
Prove that if A is regular, then A2/1 is also regular.
[To do so, assume that A is accepted by some DFA M = (Q, Σ, δ, s, F) and construct a DFA (or NFA) M′ = (Q′, Σ, δ′, s′, F′) that accepts A2/1. Specify all components of M′ and explain what it does.]
7. [10 Points] Parse Trees. Consider the context-free gr代 写CS 3800 Spring 2024 Homework 6Processing
代做程序编程语言ammar for arithmetic expressions that was discussed in class. Its rules were
E → E + T | T
T → T × F | F
F → (E) | a
Give parse trees and derivations for the following strings
(a) a
(b) a + a + a
(c) a + a × a
8. [24 Points] CFGs. Give context-free grammars that generate the following languages over the alphabet Σ = {a, b}. In each case, try to minimize the number of variables and specify all components of the quadruple (V, Σ, R, S).
(a) The empty language ∅.
(b) Σ*.
(c) {w | the length of w is odd}.
(d) {ambn| 0 ≤ m ≤ n}
(e) {a a a bn an| n ≥ 0}
(f) {w | w contains at least four a’s}.
(g) {w | w ≠ ε and w begins and ends with the same symbol}.
9. [10 Points] CFGs. Construct context-free grammars that generate the languages below. For each grammar specify all components of the quadruple (V, Σ, R, S).
(a) L1 = {aibjck| j = i + k and i, j, k ≥ 0}
(b) L2 = {aibjck| i = j + k and i, j, k ≥ 0}
10. [9 Points] Right-regular grammars. Construct right-regular grammars for the following lan-guages.
(a) {w ∈ {a, b}* | the length of w is odd}
(b) {aibj| i, j ≥ 0 and i + j is odd}
11. [12 Points] Chomsky. Use the method from class (lecture 13) to convert each of the following grammars to Chomsky normal form. Note that not all passes are always needed.
(a) S → a S a b | B
B → b b C | b b
C → ε | c C
(b) S → A B
A → a | B
B → b | A | ε





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
