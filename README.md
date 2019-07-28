# Algo-Project-2 - Postage Stamp Problem

Abstract
"The well-studied local postage stamp problem (LPSP) is the following: given apositive integerk, a set of positive integers 
1 = a1 < a2 <· · ·< ak and an integer h ≥ 1, what is the smallest positive integer which cannot be represented as a linear combination ∑1≤i≤k xi ai where ∑1≤i≤k xi ≤ h and each xi is a non-negative integer? In this note we prove that LPSP is NP-hard under Turing reductions, but can be solvedin polynomial time if k is fixed."

"The local postage-stamp problem, or LPSP for short, can be informally defined as follows.One is given a supply of stamps of k different denominations, 1 = a1 < a2 <· · ·< ak, and an envelope that has room for at most h different stamps. What is the smallest amountof postage Nh(a1, a2, . . . , ak) that cannot fit on the envelope? For example, if the available denominations are 1¢, 4¢, 7¢, and 8¢, and the envelope has room for 3 stamps, then all amounts of postage ≤24¢ can be provided but 25¢ cannot. Hence 
N3(1,4,7,8) = 25."