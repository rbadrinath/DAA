# Purpose
This repostory contains material for the Design and Analysis of Algorithms course at the Indian Statistical Instutute, Bangalore

Slide sets here are more to outline the topic touched and not intended to be self explanatory.

# References
* [SW](https://algs4.cs.princeton.edu/home/) Algorithms by Robert Sedgewick and Kevin Wayne. I will follow the coverage as in this text. You can use this online as a text book for the most part.
* [SAC](https://theswissbay.ch/pdf/Gentoomen%20Library/Algorithms/Algorithms%20in%20C.pdf) Algorithms in C by Robert Sedgewick. This has some material hat the above one does not.
* [DPV](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf) Algorithms by Sanjay Dasgupta, Christos H Papadimitriou, and Umesh V Vazirani

# Content
Not fully though out, but here is an outline (WIP). Where possible reference is made to the above reference material
* **Introduction** Notion of Analysis through examples - Insertion sort, selection sort, search, binary search, Algorithm complexity vs problem complexity, space versus time complexity., what is the parameter in the compexity function. Introducing the Big Oh (and Big Theta and Big Omega) concepts for characterizing complexity. Binary search vs Fibonacci search. Examples with bitwize add and multiply . Fast bitwise multiply. Recurrence relations and the Master Theorem.
* **Sorting**  Merge sort, heap and heap-sort
* **Searching**

# Lecture sequencing
* 23-July-24  Introduction section mentioned above, up to space vs time complexity. To read: Chap 0 of DPV, 1.4 and 2.1 of SW
* 25-July-24  Remainder of Introduction section - Fibonacci search, Formal complexity notation, bitwize operations. pp 22-24  and pp 51-55 of DPV
* 30-July-24  Faster multiply, Recurrence relations for analysis, the Master theorem pp 51-55  of DPV, and revisiting binary search and outline of merge sort as applications of the theorem. pp 56-57 of DPV .    Introduction to heaps 2.4 of SW.
* 01-August-24 Heaps, heap operations, heapsort and the notion of a priority queue 2.4 of SW. Difference between queues, arrays and priority queues. Introduction to amortized analysis by using the multi-pop stack example.
* 06-August-24 Binary counter - amortized analysis example. Finding the *k*th smallest (or *k* ranked element) in an unordered array - expected time/cost analysis in DPV pp 60-61. Recall Divide and Conquer as a strategy. Binary Search Trees O(*h*) for basic ops SW 3.2 - Motivation for balanced search trees.
* 08-August-24 BST-traversal and sorted order, 2-3 trees ( and a mention of m-ary trees and B-Trees), equivalence of 2-3 and red-black trees SW 3.3. Mentioned why B-Trees are common in storage solutions like databases. Hashing SW 3.4. Lowerbound of nlog(n) for comparison based sorting (n! leaves in the comparision tree of any sorting algorithm.) Radix-sort and counting-sort for 'faster' sorting    SAC ch.10.
