# Purpose
This repostory contains material for the Design and Analysis of Algorithms course at the Indian Statistical Instutute, Bangalore

Slide sets here are more to outline the topic touched and not intended to be self explanatory.

# References
* [SW](https://algs4.cs.princeton.edu/home/) Algorithms by Robert Sedgewick and Kevin Wayne. I will follow the coverage as in this text. You can use this online as a text book for the most part.
* [SAC](https://theswissbay.ch/pdf/Gentoomen%20Library/Algorithms/Algorithms%20in%20C.pdf) Algorithms in C by Robert Sedgewick. This has some material hat the above one does not.
* [DPV](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf) Algorithms by Sanjay Dasgupta, Christos H Papadimitriou, and Umesh V Vazirani
* [BB](https://jainakshay781.files.wordpress.com/2017/12/gilles-brassard-and-paul-bartley-fundamental-of-algorithmics.pdf) Algorithmics Theory and Practice. Gilles Brassard and Paul Bratley
* [GJ](https://perso.limos.fr/~palafour/PAPERS/PDF/Garey-Johnson79.pdf) Computers and Intractability by Michael Garey and David Johnson.

# Lecture sequencing
* 23-July-24  Introduction section mentioned above, up to space vs time complexity. To read: Chap 0 of DPV, 1.4 and 2.1 of SW
* 25-July-24  Remainder of Introduction section - Fibonacci search, Formal complexity notation, bitwize operations. pp 22-24  and pp 51-55 of DPV
* 30-July-24  Faster multiply, Recurrence relations for analysis, the Master theorem pp 51-55  of DPV, and revisiting binary search and outline of merge sort as applications of the theorem. pp 56-57 of DPV .    Introduction to heaps 2.4 of SW.
* 01-August-24 Heaps, heap operations, heapsort and the notion of a priority queue 2.4 of SW. Difference between queues, arrays and priority queues. Introduction to amortized analysis by using the multi-pop stack example.
* 06-August-24 Binary counter - amortized analysis example. Finding the *k*th smallest (or *k* ranked element) in an unordered array - expected time/cost analysis in DPV pp 60-61. Recall Divide and Conquer as a strategy. Binary Search Trees O(*h*) for basic ops SW 3.2 - Motivation for balanced search trees.
* 08-August-24 BST-traversal and sorted order, 2-3 trees ( and a mention of m-ary trees and B-Trees), equivalence of 2-3 and red-black trees SW 3.3. Mentioned why B-Trees are common in storage solutions like databases. Hashing SW 3.4. Lowerbound of nlog(n) for comparison based sorting (n! leaves in the comparision tree of any sorting algorithm.- See pp 59 of DPV) Radix-sort and counting-sort for 'faster' sorting    SAC ch.10.
* 13-August-24 Strassen's method for multiplication pp 62-63 of DPV.  The Fast Fourier Transform algorithm - as part ofpolynomial multiplication pp 64-71 DPV. We also did the average case analysis for quicksort, but did not complete it.
* 20-August-24 Disjoint set union-find algorithm : pp 30-34 of BB, started Depth First Search (DFS) on graphs.
* 22-August-24 DFS with pre and post numbering, components in undirected graphs, DFS in DAGs and topological sort, introduced ideas for strongly connected component - Ch3 of DPV.
* 24-August-24 Algorithm for stronlgly connected components - Ch 3 of DPV, Breadth First Search, distance in unidrected graphs.
* 29-August-24 Shortest-path problems: Dijkstra's algorithm, Bellman-Ford's algorithm - Ch4 of DPV, Notion of greedy algorithms, Min Wt Spnning tree: Prim's algorithm - P143-145 of DPV
* 03-September-24 Kruskal's algorithm for Min Wt SPanning Trees (- pp 134-138 of DPV). Proof of Prim's and Kruskal's algorithms. Introduction to ideas in Huffman coding.
* 19-September-24 Finished Huffman coding see pp 146-150 of DPV, Algorithm of Floyd-Warshal for all pair shortest paths see pp 176-177 od DPV, A* algorithm for searching.
* 24-September-24 Finished A* (see [this link](https://courses.cs.duke.edu/fall11/cps149s/notes/a_star.pdf) ). Dynamic programming, Shortest paths in DAGs and Longest increasing sub-sequence problem see pp 161-163 of DPV. Introduction to Network Flow.
* 01-October-24  Network Flow and application to Bipartite matching, see pp. 199-206 of DPV (Ford-Fulkerson, Edmond-Karp); Knapsack by dynamic programming See pp171-173 of DPV.
* 03-October-24  Chained Matrix multiplication pp 174-175 of DPV. Notion of precomputation - Anscestor in a rooted tree pp.207-208 (note the pre/postnum is a bit different from what we did in class) , KMP string-searching pp.213-215 of BB. 
* 08-October-24  Introduced the classes P, NP and several NP Complete problems; the notion of polynomial time reduction See pp 233-244 of DPV.
* 10-October-24  Several reductions HamPath->TSP(s,t), 3SAT->VC, SAT->3SAT, 3SAT->3DM See 244-251 of DPV. For details of 3SAT->3DM see pp 51-53 of GJ.
* 15-October-24  reductions: CIRCUIT-SAT-> SAT and a sketch of why any NP problem can reduce to CIRCUIT-SAT pp 259-261 of DVP.
