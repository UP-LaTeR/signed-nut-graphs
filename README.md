# Signed nut graphs

The present repository contains examples of sign-unbalanced nut graphs that
were used in the paper

N. Bašić, P. W. Fowler, T. Pisanski and I. Sciriha,
On Singular Signed Graphs with Nullspace Spanned by a Full Vector: Signed Nut Graphs,
https://arxiv.org/abs/2009.09018

for verification of Table X and Theorems X and X. Each entry gives an adjacency list,
together with the pattern of positive and negative weights and the kernel eigenvector
as a list of integer entries. Each graph is given with three lines:

 * The first line contains integers `n` and `r`, where `n` is the order and `r` is the
   degree of the regular graph.
 * The second line contains description of the `m = nr / 2` edges. Each edge is represented
   as a triple of the form `u v s`, where `u` and `v` are endvertices of the edge and `s`
   is the sign (either 1 or -1).
 * The third line contains `n` integers that specify the kernel eigenvector. 

The file `small-order-sign-unbalanced.txt` contains an example of a sign-unbalanced nut graph
for each entry in Table 1 of the paper marked only with a Maltese cross (i.e. those parameters
for which no sign-balanced nut graph exists). 

The file `low-degree-sign-unbalanced.txt` contains sign-unbalanced nut graphs for low degrees.
They are indicated by a tick and a Maltese cross in the Table 1 of the paper (i.e. both
a sign-balanced and a sign-unbalanced nut graph exists). These are needed for the proof of
Theorem X in the paper.
