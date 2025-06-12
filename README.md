# CS360-Assignment-4-solution

Download Here: [CS360 Assignment 4 solution](https://jarviscodinghub.com/assignment/cs360-assignment-4-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. Let us call a language Reg-pumpable if it satisfies the conclusion of the pumping lemma for regular
languages. Namely, L is Reg-pumpable if there exist some n such that for every w ∈ L, if |w| > n then
the is a decomposition w = xyz so that for any i ≥ 0, xyi
z ∈ L.
Similarly, say that a language L is CF-pumpable if it satisfies the conclusion of the CFL pumping
lemma.
(a) [5 points] Prove that every language that is Reg-pumpable is also CF-pumpable.
(b) [5 points] Prove that the converse of the above claim is false. Namely, find a language that is
CF-pumpable but not Reg-pumpable. Prove your claims.
(c) [5 points] A language L over some alphabet, Σ, is a Length language if, for any word, w ∈ L,
every w
0 of the same length is also in L (namely, ∀w, w0
, |w| = |w
0
| implies w ∈ L if and only if
w
0 ∈ L). Prove that every CF-pumpable length language is also Reg-pumpable.
(d) [10 points] Prove that Lcube = {a
n
2
: n ≥ 0} is not a context-free language.
2. For each of the following languages determine whether it is a regular language or not, and whether it
is a CFL or not:
(a) [5 points] Lsq = {a
nb
m : n ≡ m(mod 3)}.
(b) [10 points] Lp = {w ∈ {a, b}
∗
: |w| is a prime number }.
(c) [5 points] Lodd eq = {a
j
b
k
c
`
: j is odd or k = `}.
3. Define a grammar, G = (V, T, S, P), by setting V = {S}, T = {a, b} and P = {S 7→ ab|aSb|aSSb}.
(a) [10 points] Prove that L(G) = I

{ab}, {
w
awb ,
w1, w2
aw1w2b
}

. That is, L(G) equals the language that
is defined by structural induction as the closure of the core set, {ab}, under the operations, w
awb
and w1, w2
aw1w2b
.
(b) [5 points] Prove that, for every w ∈ L(G), na(w) = nb(w).
(c) [5 points] Prove that for every w ∈ L(G), if w
0
is a proper initial segment of w (that is, there
exist some word w
00 6= , such that w = w
0w
00) then na(w
0
) > nb(w
0
).
(d) [5 points] Is L(G) a regular language? Prove your claim.
4. For a language L over some finite alphabet, Σ define a new language F0(L) = {0
|w|
: w ∈ L}. That is,
the set of all strings of 0’s that have the same length as some word in L.
(a) [10 points] Prove that for every regular language L the language F0(L) is also regular.
(b) [10 points] Prove that for every context free language L the language F0(L) is also context free.
(c) [10 points] Find a language L such that L is not a context free language but F0(L) is regular.
Prove your claims.

