# Computational Logic 1
Final project from Computational Logic 1 - 2018/1, turma B.

#### Group Members
Gabriel Bessa   16/012081   
Vitor Dullens  16/0148260   
Giovanni Guidini  16/0122660   
Diogo Pontes  16/0117992   

## Project
 Prove some results that the first phase of Ford Johnson's sorting algorithm *(aka merge-insertion sort)* using the proof assistant [PVS](http://pvs.csl.sri.com/). The formalizations use Gentzen's Sequent Calculus.

## Project tasks:
There are 2 mandatory tasks in the project:    
[X] Question 02 - Prove the conjecture `seqfjBottPreservesElements`. It states that, for all `finseq s`, it holds that `seqfjBottleneck(s)` is a permutation of the sequence `s`.

[X] Question 03 - Prove the conjecture `structural_correctionFP`. It states that the predicate `structER?` holds fora sequence `s0` after the aplication of function `seqfjBottleneck` on it.

There is one optional task in the project:    
[ ] Question 01 - Prove conjecture `comparePeservesElements`. It states that applying function `compare2to2` in a `finseqfj` doesn't alter its elements.


