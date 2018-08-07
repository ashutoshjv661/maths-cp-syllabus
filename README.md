# Competitive Programming Syllabus

## Geometry
* Graham Scan algorithm for Convex Hull O(n * log(n))
* Online construction of 3-D convex hull in O(n^2)
* Bentley Ottmann algorithm to list all intersection points of n line segments in O((n + I) * logn)
  + Suggested Reading - http://softsurfer.com/Archive/algorithm_0108/algorithm_0108.htm
* Rotating Calipers Technique
  + Suggested Reading - http://cgm.cs.mcgill.ca/~orm/rotcal.html
  + Problems - Refer the article for a list of problems which can be solved using Rotating Calipers technique.
* Line Sweep/Plane Sweep algorithms
* Area/Perimeter of Union of Rectangles.
* Closest pair of points.
  + Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=lineSweep
  + Problems - Follow the tutorial for list of problems.
* Area of Union of Circles.
* Delaunay Triangulation of n points in O(n * logn).
* Voronoi Diagrams of n points in O(n * logn) using Fortune’s algorithm.
* Point in a polygon problem -
  + O(n) solution without preprocessing.
  + O(logn) algorithm with O(n * logn) preprocessing for convex polygons.
* Problems on computational geometry -
  + BSHEEP, BULK, SEGVIS, CONDUIT, RUNAWAY, DIRVS, RAIN1, SHAMAN, TCUTTER, LITEPIPE, RHOMBS, FSHEEP,
    FLBRKLIN, CERC07P, BAC, ALTARS, CERC07C, NECKLACE, CH3D, RECTANGL, POLYSSQ, FOREST2, KPPOLY,
    RAIN2, SEGMENTS, ARCHPLG, BALLOON, CIRCLES, COMPASS, EOWAMRT, ICERINK on SPOJ.
  + CultureGrowth, PolygonCover on Topcoder.
* Suggested Reading - Computational Geometry: Algorithms and applications. Mark De Burg.

## String Algorithms

### Substring search
* KnuthMorrisPratt algorithm (Problems - NHAY, PERIOD on SPOJ)
* Suggested Reading - Cormen chapter on Strings.
* http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=stringSearching
* Aho Corasick algorithm
* Problems - WPUZZLES on SPOJ

### Suffix Arrays
* O(n^2 * logn) Naive method of suffix array construction
* O(n * logn^2) method of suffix array construction
* O(n * logn) method of suffix array construction
* O(n) method of suffix array construction
* O(n) LCA preprocess on Suffix Arrays to solve a variety of string problems

### Suffix Trees
* O(n) construction of Suffix trees using Ukkonon’s algorithm
* O(n) construction of Suffix Trees if provided with Suffix Arrays using Farach's algorithm

### Other
* Suffix Automata - O(n) Suffix Automaton construction.
* Dictionary Of Basic Factors - O(n * logn) method of DBF construction using Radix Sort.
* Manacher’s algorithm to find length of palindromic substring of a string centered at a position for each position in the string.
  Runtime -> O(n).
* Searching and preprocessing Regular Expressions consisting of '?' and '\*'

### Multi-dimensional pattern matching
* DISUBSTR, PLD, MSTRING, REPEATS, JEWELS, ARCHIVER, PROPKEY, LITELANG, EMOTICON, WORDS, AMCODES, UCODES, PT07H, MINSEQ, TOPALIN, BWHEELER, BEADS, SARRAY, LCS, LCS2, SUBST1, PHRASES, PRETILE on SPOJ
* http://www.algorithmist.com/index.php/Category:String_algorithms

## Graphs

### Basic Graphs
* Representation of graphs as adjacency list, adjacency matrix, incidence matrix and edge list and uses of different representations in different scenarios
* Breadth First Search (Problems - PPATH, ONEZERO, WATER on SPOJ)
* Depth First Search
* Strongly Connected Components (TOUR and BOTTOM on SPOJ)
* Biconnected Components, Finding articulation points and bridges (RELINETS, PT07A on SPOJ)
* Dijkstra algorithm (SHPATH on SPOJ)
* Floyd Warshall algorithm (COURIER on SPOJ)
* Minimum Spanning Tree (BLINNET on SPOJ)
* Flood-fill algorithm
* Topological sort
* Bellman-Ford algorithm.
* Euler Tour/Path (WORDS1 on SPOJ)
* Suggested reading for most of the topics in Graph algorithms -
  http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=graphsDataStrucs1.
* Also refer to the tutorial for problems concerning these techniques.
* Cormen chapter 22 to 24.

### Flow networks/ matching
* Maximum flow using Ford Fulkerson Method
  + Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=maxFlow
  + problems - TAXI, POTHOLE, IM, QUEST4, MUDDY, EN, CABLETV, STEAD, NETADMIN, COCONUTS, OPTM on SPOJ.
* Maximum flow using Dinic’s Algorithm (PROFIT on spoj)
* Minimum Cost Maximum Flow.
* Successive Shortest path algorithm.
* Cycle Cancelling algorithm - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=minimumCostFlow1
* Maximum weighted Bipartite Matching (Kuhn Munkras algorithm/ Hungarian Method)
  + problems - GREED, SCITIES, TOURS on SPOJ | http://www.topcoder.com/stat?c=problem_statement&pm=8143
* Stoer Wagner min-cut algorithm.
* Hopcroft Karp bipartite matching algorithm (ANGELS on SPOJ)
* Maximum matching in general graph (blossom shrinking)
* Gomory-Hu Trees (MCQUERY on Spoj)
* Chinese Postman Problem
  + problems - http://acm.uva.es/archive/nuevoportal/data/problem.php?p=4039
  + Suggested Reading - http://eie507.eie.polyu.edu.hk/ss-submission/B7a/
* Suggested Reading for the full category ->
* Network flow - Algorithms and Applications by Ahuja
* Cormen book chapter 25.

## Dynamic Programming.
* Suggested Reading - Dynamic Programming(DP) as a tabulation method
* Cormen chapter on DP
* Standard problems (you should really feel comfortable with these types)
  + http://www.topcoder.com/stat?c=problem_statement&pm=8570&rd=12012&rm=269199&cr=7581406
  + http://www.topcoder.com/stat?c=problem_statement&pm=10765&rd=14183
* State space reduction
  + http://www.topcoder.com/stat?c=problem_statement&pm=10902
  + http://www.topcoder.com/stat?c=problem_statement&pm=3001
  + http://www.topcoder.com/stat?c=problem_statement&pm=8605&rd=12012&rm=269199&cr=7581406
* Solving in the reverse - easier characterizations looking from the end
  + http://www.spoj.pl/problems/MUSKET
  + http://www.topcoder.com/stat?c=problem_statement&pm=5908
* Counting/optimizing arrangements satisfying some specified properties
  + http://www.topcoder.com/stat?c=problem_statement&pm=8306
  + http://www.topcoder.com/stat?c=problem_statement&pm=784
* Strategies and expected values
  + http://www.topcoder.com/stat?c=problem_statement&pm=10765&rd=14183
  + http://www.topcoder.com/stat?c=problem_statement&pm=10806
  + http://www.topcoder.com/stat?c=problem_statement&pm=7828
  + http://www.topcoder.com/stat?c=problem_statement&pm=7316
* DP on probability spaces
  + http://www.topcoder.com/stat?c=problem_statement&pm=7422
  + http://www.topcoder.com/stat?c=problem_statement&pm=2959
  + http://www.topcoder.com/stat?c=problem_statement&pm=10335
* DP on trees
  + http://www.topcoder.com/stat?c=problem_statement&pm=10800
  + http://www.topcoder.com/stat?c=problem_statement&pm=10737
  + http://www.topcoder.com/stat?c=problem_solution&rm=266678&rd=10958&pm=8266&cr=7581406
  + DP with data structures
  + http://www.spoj.pl/problems/INCSEQ/
  + http://www.spoj.pl/problems/INCDSEQ/
  + http://www.spoj.pl/problems/LIS2/
  + http://www.topcoder.com/stat?c=problem_statement&pm=1986
* Symmetric characterization of DP state
  + http://www.topcoder.com/stat?c=problem_statement&pm=8610
* A good collection of problems
  + http://codeforces.com/blog/entry/325
  + http://problemclassifier.appspot.com/index.jsp?search=dp

## Greedy
* Chapter on Greedy algorithms in Cormen
* http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=greedyAlg
* Problems - refer to the topcoder tutorial.

## Number Theory

### Modulus arithmetic
* Basic postulates (Including modular linear equations, Continued fraction and Pell's equation)
* Suggested Reading -
  + Chapter 1 from Number Theory for Computing by SY Yan (Recommended)
  + 31.1, 31.3 and 31.4 from Cormen
  + www.topcoder.com/tc?module=Static&d1=tutorials&d2=primeNumbers
* Problems
  + http://projecteuler.net/index.php?section=problems&id=64
  + http://projecteuler.net/index.php?section=problems&id=65
  + http://projecteuler.net/index.php?section=problems&id=66
  + http://www.topcoder.com/stat?c=problem_statement&pm=6408&rd=9826
  + http://www.topcoder.com/stat?c=problem_statement&pm=2342

### Fermat's theorem, Euler Totient theorem (totient function, order, primitive roots)
* Suggested Reading
  + 1.6, 2.2 from Number Theory by SY Yan
  + 31.6 , 31.7 from Cormen
* Problems
  + http://projecteuler.net/index.php?section=problems&id=70
  + http://www.spoj.pl/problems/NDIVPHI/

### Chinese remainder theorem
* Suggested Reading
  + 31.5 from Cormen
  + 1.6 from Number Theory by SY Yan
* Problems
  + Project Euler 271
  + http://www.topcoder.com/stat?c=problem_statement&pm=10551&rd=13903

### Primality tests
* Deterministic O(sqrt(n)) approach
* Probabilistic primality tests - Fermat primality test, Miller-Rabin Primality test
* Suggested Reading -
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=primalityTesting
  + Cormen 31.8
  + 2.2 from Number Theory by SY Yan
* Problems
  + PON, PRIC, SOLSTRAS on SPOJ
  + http://www.topcoder.com/stat?c=problem_statement&pm=4515
* Prime generation techniques - Sieve of Erastothenes (PRIME1 on SPOJ)

### GCD using euclidean method
* Suggested Reading - 31.2 Cormen
* Problems
  + GCD on SPOJ
  + http://uva.onlinejudge.org/external/114/11424.html

### Logarithmic Exponentiation
* Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=primalityTesting

### Integer Factorization
* Naive O(sqrt(n)) method
* Pollard Rho factorization
* Suggested Reading
  + 2.3 from Number Theory SY Yan
  + 31.9 Cormen
* Problems -
  + http://www.topcoder.com/stat?c=problem_statement&pm=2986&rd=5862
  + http://www.spoj.pl/problems/DIVSUM2/
  + http://www.topcoder.com/stat?c=problem_statement&pm=4481&rd=6538

### Other
* Stirling numbers
* Wilson theorem
* nCr % p  in O(p) preprocess and O(log n) query
* Lucas Theorem
* Suggested Reading for Number Theory -
  + Number theory for computing by Song Y Yan (Simple book describing concepts in details)
  + Concepts are also superficially covered in Chapter 31 of Introduction to Algorithms by Cormen
  + http://www.codechef.com/wiki/tutorial-number-theory
  + http://www.algorithmist.com/index.php/Category:Number_Theory
* Problems on Number Theory -
  + http://www.algorithmist.com/index.php/Category:Number_Theory
  + http://problemclassifier.appspot.com/index.jsp?search=number&usr=

## Math (Probability, Counting, Game Theory, Group Theory, Generating functions, Permutation Cycles, Linear Algebra)

### Probability
* Basic probability and Conditional probability
  + http://www.spoj.pl/problems/CT16E/
  + http://www.spoj.pl/problems/CHICAGO/
* Random variables, probability generating functions
* Mathematical expectation + Linearity of expectation
  + http://www.spoj.pl/problems/FAVDICE/
  + http://www.topcoder.com/stat?c=problem_statement&pm=10744
* Special discrete and continuous probability distributions
  + Bernoulli, Binomial, Poisson, normal distribution
  + http://acm.sgu.ru/problem.php?contest=0&problem=498
* Suggested Readings
  + Cormen appendix C (very basic)
  + Topcoder probabilty tutorial http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=probabilities
  + http://en.wikipedia.org/wiki/Random_variable
  + http://en.wikipedia.org/wiki/Expected_value
  + William Feller, An introduction to probability theory and its applications

### Counting
* Basic principles - Pigeon hole principle, addition, multiplication rules
* Problems
  + http://acm.timus.ru/problem.aspx?space=1&num=1690
  + http://www.topcoder.com/stat?c=problem_statement&pm=10805
* Suggested readings
  + http://en.wikipedia.org/wiki/Combinatorial_principles
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=combinatorics
  + http://www.maa.org/editorial/knot/pigeonhole.html
* Inclusion-exclusion
  + http://en.wikipedia.org/wiki/Inclusion–exclusion_principle
  + http://www.topcoder.com/stat?c=problem_statement&pm=4463&rd=6536
  + http://www.topcoder.com/stat?c=problem_statement&pm=10238

### Special numbers
* Stirling, eurlerian, harmonic, bernoulli, fibonnacci numbers
* http://en.wikipedia.org/wiki/Stirling_number
* http://en.wikipedia.org/wiki/Eulerian_numbers
* http://en.wikipedia.org/wiki/Harmonic_series\_(mathematics)
* http://en.wikipedia.org/wiki/Bernoulli_number
* http://en.wikipedia.org/wiki/Fibonnaci_numbers
* Concrete mathematics by Knuth
* Suggested problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=1643
  + http://www.topcoder.com/stat?c=problem_statement&pm=8202&rd=11125
  + http://www.topcoder.com/stat?c=problem_statement&pm=8725
  + http://www.topcoder.com/stat?c=problem_statement&pm=2292&rd=10709

### Advanced counting techniques - Polya counting, burnsides lemma
* Suggested reading
  + http://en.wikipedia.org/wiki/Burnside's_lemma
  + http://petr-mitrichev.blogspot.com/2008/11/burnsides-lemma.html
* Problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=9975
  + http://www.spoj.pl/problems/TRANSP/

## Game theory
* Basic principles and Nim game
* Sprague grundy theorem, grundy numbers
* Suggested readings
  + http://en.wikipedia.org/wiki/Sprague%E2%80%93Grundy_theorem
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=algorithmGames
  + http://www.ams.org/samplings/feature-column/fcarc-games1
  + http://www.codechef.com/wiki/tutorial-game-theory
* Suggested problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=3491&rd=6517
  + http://www.topcoder.com/stat?c=problem_statement&pm=3491&rd=6517
* Hackenbush
  + http://en.wikipedia.org/wiki/Hackenbush
  + http://www.ams.org/samplings/feature-column/fcarc-partizan1
* Suggested problems
  + http://www.cs.caltech.edu/ipsc/problems/g.html
  + http://www.spoj.pl/problems/PT07A/

## Linear Algebra

### Matrix Operations
* Addition and subtraction of matrices
  + Cormen 28.1
* Multiplication (Strassen's algorithm), logarithmic exponentiation
  + Cormen 28.2
  + Linear Algebra by Kenneth Hoffman Section 1.6
* Problems
  + http://uva.onlinejudge.org/external/111/11149.html

### Matrix transformations (Transpose, Rotation of Matrix, Representing Linear transformations using matrix)
* Suggested Reading - Linear Algebra By Kenneth Hoffman Section 3.1,3.2,3.4,3.7
* Problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=6877
  + JPIX on Spoj
* Determinant, Rank and Inverse of Matrix (Gaussean Elimination , Gauss Jordan Elimination)
  + 28.4 Cormen
  + Linear Algebra by Kenneth Chapter 1
* Problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=8174
  + http://www.topcoder.com/stat?c=problem_statement&pm=6407&rd=9986
  + http://www.topcoder.com/stat?c=problem_statement&pm=8587
  + HIGH on Spoj

### Solving system of linear equations
* Suggested Reading
  + 28.3 Cormen
  + Linear Algebra by Kenneth Chapter 1
* Problems
  + http://www.topcoder.com/stat?c=problem_statement&pm=3942&rd=6520

### Using matrix exponentiation to solve recurrences
* Suggested Reading
  + http://www.topcoder.com/tc?module=Static&d1=features&d2=010408
* Problems
  + REC, RABBIT1, PLHOP on spoj
  + http://www.topcoder.com/stat?c=problem_statement&pm=6386
  + http://www.topcoder.com/stat?c=problem_statement&pm=7262
  + http://www.topcoder.com/stat?c=problem_statement&pm=6877

### Eigen values and Eigen vectors
* Problems - http://www.topcoder.com/stat?c=problem_statement&pm=2423&rd=4780

### Polynomials
* Roots of a polynomial (Prime factorization of a polynomial, Integer roots of a polynomial, All real roots of a polynomial)
  + http://www.topcoder.com/stat?c=problem_statement&pm=8273&rd=10798
  + POLYEQ , ROOTCIPH on Spoj
* Lagrange Interpolation
  + http://www.topcoder.com/stat?c=problem_statement&pm=10239
  + http://www.topcoder.com/stat?c=problem_statement&pm=8725

## Permutation cycles
* Suggested Reading - Art of Computer Programming by Knuth Vol. 3
* Problems - ShuffleMethod, Permutation and WordGame on topcoder.

## Group Theory
* Burnside Lemma
* Polya’s theorem
* Suggested Reading
  + Hernstein's topics in algebra
  + http://petr-mitrichev.blogspot.com/2008/11/burnsides-lemma.html
* Problems
  + TRANSP on spoj
  + http://www.topcoder.com/stat?c=problem_statement&pm=9975

## Generating functions
* Suggested Reading
  + Herbert Wilf's generating functionology
  + Robert Sedgewick and Flajoulet's Combinatorial analysis

## Data Structures

### Basic
* Arrays/Stacks/Queues
* Problems
  + https://www.spoj.pl/problems/STPAR/
  + https://www.spoj.pl/problems/SHOP/
  + https://www.spoj.pl/problems/WATER/
* Reading:
  + CLRS: section 10.1
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=dataStructures

### Singly/Doubly Linked List
* Problems - https://www.spoj.pl/problems/POSTERS/
* Reading: CLRS: section 10.2, Mark Allen Weies Chapter 3

### Hash Tables
* Problems
  + https://www.spoj.pl/problems/HASHIT/
  + https://www.spoj.pl/problems/CUCKOO/
* Reading: CLRS: Chapter 11, Mark Allen Weies Chapter 5

### Circular linked list / queue
* Problems - https://www.spoj.pl/problems/CTRICK/

### Binary/n-ary trees
* Reading
  + CLRS: section 10.4
  + CLRS: Chapter 12
  + Mark Allen Weies Chapter 4
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binarySearchRedBlack

### Heaps
* Problems
  + https://www.spoj.pl/problems/PRO/
  + https://www.spoj.pl/problems/EXPEDI/
* Reading : Mark Allen Weies Chapter 6

### Trie
* Problems
  + https://www.spoj.pl/problems/MORSE/
  + https://www.spoj.pl/problems/EMOTICON/
* Reading

### Interval trees / Segment Trees
* Problems
  + https://www.spoj.pl/problems/ORDERS/
  + https://www.spoj.pl/problems/FREQUENT/
* Reading

### Fenwick (Binary Indexed) trees
* Problems - https://www.spoj.pl/problems/MATSUM/
* Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binaryIndexedTrees

### Disjoint data structures
* Problems
  + https://www.spoj.pl/problems/BLINNET/
  + https://www.spoj.pl/problems/CHAIN/
* Reading:
  + http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=disjointDataStructure
  + Mark Allen Weies Chapter 8

### Range minimum Query (RMQ)
* Problems
  + https://www.spoj.pl/problems/GSS1/
* Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=lowestCommonAncestor

### Customized interval/segment trees (Augmented DS)
* Problems
  + https://www.spoj.pl/problems/GSS3/
  + https://www.spoj.pl/problems/RRSCHED/
* Reading: CLRS: Chapter 14 (augmented DS)

### AVL Trees
* Problem - https://www.spoj.pl/problems/ORDERS/

### Miscellaneous
* Splay Trees
* B/B+ Trees
* k-d Trees
* Red-black Trees
* Skip List
* Binomial/ Fibonacci heaps

### Exercices
* https://www.spoj.pl/problems/LAZYPROG/ (Hint: Heaps)
* https://www.spoj.pl/problems/HELPR2D2/ (Hint: Interval Trees)
* https://www.spoj.pl/problems/SAM/ (Hint: Heaps)
* https://www.spoj.pl/problems/PRHYME/ (Hint: Trie)
* https://www.spoj.pl/problems/HEAPULM/ (Hint: Interval Trees)
* https://www.spoj.pl/problems/CORNET/ (Hint: Disjoint)
* https://www.spoj.pl/problems/EXPAND/
* https://www.spoj.pl/problems/WPUZZLES/
* https://www.spoj.pl/problems/LIS2/

## Search Techniques/Bruteforce writing techniques/Randomized algorithms.

### Backtracking (beginner)
* N queens problems
* Knights Tour
* Sudoku Problem
* Tiling Problem
* 15 puzzle.

### Dancing Links and Algorithm X given by Knuth (advanced)
* problems - PRLGAME, SUDOKU, NQUEEN on SPOJ
* Suggested reading - http://www-cs-faculty.stanford.edu/~uno/papers/dancing-color.ps.gz

### Binary Search (beginner)
* problems - AGGRCOW on SPOJ. Refer the tutorial for more problems.
* finding all real roots of a polynomial using binary search (intermediate)
* Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=binarySearch

### Ternary Search (intermediate)
* Problems
  + http://www.spoj.pl/problems/KPPOLY/
  + http://www.codechef.com/DEC09/problems/K1/
  + http://www.topcoder.com/stat?c=problem_statement&pm=4705&rd=7993
  + http://www.topcoder.com/stat?c=problem_statement&pm=7741&rd=10671
  + http://www.topcoder.com/stat?c=problem_statement&pm=6464&rd=9994
  + http://www.topcoder.com/stat?c=problem_statement&pm=3501&rd=6529
  + http://www.topcoder.com/stat?c=problem_statement&pm=4567&rd=6539

### Meet in the middle (Intermediate)
* problems - http://www.spoj.pl/problems/MAXISET/

### Hill Climbing (Advanced)

### Regular Iteration to reach a fixed point (Advanced)
* Newton-Raphson method to find root of a mathematical function.
* Iterations to solve linear non homogeneous system of equations.

## Representing sets with bitmasks and manipulating bitmasks (Beginner)
* Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=bitManipulation
* problems - refer to the tutorial link in Suggested reading section.

## General programming issues in contests
* Arithmetic Precision (Beginner)
* Suggested Reading - http://www.topcoder.com/tc?module=Static&d1=tutorials&d2=integersReals
