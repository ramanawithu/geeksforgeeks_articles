
# My contributions to [Geeksforgeeks.org](http://www.geeksforgeeks.org/)

*I was graduated in 2005 from the College of Engineering, [GITAM](http://www.gitam.edu/). Since I opted a diploma course at +2 level in ECE, I didn't have much choice than opting ECE in bachelors. But, I love ECE core, and relaxed all 4 years :) By the time out of college, I was at ground zero in terms of Computer Science subjects, yet opted career in SW (software) industry. During 2005, I used to memorize complexities of some basic algorithms for interview purpose.*

*It was in 2009, I realized that I need to improve my CS skills, if I have to excel in the SW industry. From then, I was self made in terms of Computer Science. Even today, I keep learning new stuff with full contentment. I don't believe in degrees (no disrespect to highly qualified professionals).*

*During my learning process, I contributed few articles to a public portal, and made few friends.*

*It is great feeling to read past articles, I am surprised to the quality of my content written five years ago. Sharing all of them here to have one page with all the links. Prior to the contributions I was at ground zero in terms of algorithms & data structures. It was an effort of 5+ years in self learning, and continuing ...*

Enjoy reading my past articles here.

----------------------------------------------

### 1. [Longest Increasing Subsequence Size (N log N)](http://www.geeksforgeeks.org/longest-monotonically-increasing-subsequence-size-n-log-n/)

It is one post took lot of time (6 hrs in one go) to prepare and helped many readers. I knew DP solution to the problem. But, finding size of longest increasing subsequence in linear arithmetic complexity, is one of the most appreciated article. All the thought process was triggered by a note in the book by Manber<sup>[1](#Manber)</sup>. Inteestingly the algorithm is an online algorithm.

### 2. Follow up to longest increasing subsequence, [construction of longest increasing subsequence](http://www.geeksforgeeks.org/construction-of-longest-monotonically-increasing-subsequence-n-log-n/).

If the reader does his/her paper work, writing code to construct LCS is easy job.

### 3. [Celebrity Problem](http://www.geeksforgeeks.org/the-celebrity-problem/)

A classic problem. Solution can be modeled in Graphs, Arrays and finally describes a linear algorithm. It was famous interview question. However, the hint to solution was found in Manber<sup>[1](#Manber)</sup>.

### 4. Why structure types requires padding in C/C++?

I was always clueless on why data types (both primitive & user defined) in C/C++ requires alignment. The article ['structure member alignment padding and data packing'](http://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/) debunks few of the myths. All the content was inspired from ALP <sup>[2](#Hyde)</sup>.

### 5. Pascal's identity and it's practical significance.

I focus on significance of mathematical identities while learning them. An example, [interesting fact observed in Pascal's Identity](http://www.geeksforgeeks.org/significance-of-pascals-identity/) describes on such case.

### 6. C++ Crash Macro

While going through [WebKit code](https://webkit.org/blog/5397/a-guide-to-assertion-macros-in-webkit/), the crash macro definition caught my attention. [Here](http://www.geeksforgeeks.org/crash-macro-interpretation/) is it's explanation.

### 7. C vs. C++ differences

I always emphasize on type aware programming. It helps in better (faster, compact/dense) code generation, less bugs and lucid code. [Few C++ vs. C differences](http://www.geeksforgeeks.org/g-fact-52/) and [another note](http://www.geeksforgeeks.org/g-fact-54/). Adaptive optimizations are an exception to static type advantages.

### 8. Type aware programming in C++

Every expression in C++ returns a type - [The ternary operator case](http://www.geeksforgeeks.org/cc-ternary-operator-some-interesting-observations/).

### 9. C/C++ trick to implement connected (referential) data structures

[An old C/C++ non-portable trick - Offsetoff macro](http://www.geeksforgeeks.org/the-offsetof-macro/).

### 10. NUL, 0 and '0'

An interesting low level fact in C++ - [differences among NUL, 0 and '0'](http://www.geeksforgeeks.org/g-fact-72/).

### 11. IEEE Floating Point Representation - An Introduction

While at Honeywell, I worked on some ARM based compiler intrinsics to emulate floating point math. I explored [some interesting basics of floating point representation](http://www.geeksforgeeks.org/floating-point-representation-basics/).

### 12. Image rotation algorithm

[Turning an image by 90 degree](http://www.geeksforgeeks.org/turn-an-image-by-90-degree/)

### 13. A clear binary search based on invariants

[Binary Search - Took long time to invent it](http://www.geeksforgeeks.org/the-ubiquitous-binary-search-set-1/). Algorithm emphasizes on invariant based proof.

### 14. Ceil of key in ordered collection

[Algorithm to find floor and ceil of input key in BST](http://www.geeksforgeeks.org/floor-and-ceil-from-a-bst/). Read above post also.

### 15. An incorrectly mentioned algorithm to transpose a matrix in-place.

[Algorithm to inplace Transpose of matrix](http://www.geeksforgeeks.org/inplace-m-x-n-size-matrix-transpose/). Not exactly inplace, by inplace I mean we should transpose the matrix within the matrix space.

### 16. Trie

[A meagre Trie implementation](http://www.geeksforgeeks.org/trie-delete/). Explore ternary trie, compressred tries as an extension of your learning.

### 17. C++ - Articles

I believe we need to unlearn to learn few new things. Object Oriented Programming is one of them, that needs to unlearn old learnings.

  [Leveraging virtual constructor in C++](http://www.geeksforgeeks.org/advanced-c-virtual-constructor/) - We can't have any other keyword except '*explicit & inline*' in front of C++ constructor. How can we mimic the behaviour of a constructor being virtual? The post unlocks the trick.

  [Leveraging virtual copy constructor in C++](http://www.geeksforgeeks.org/advanced-c-virtual-copy-constructor/) - An extension of virtual constructor trick that forms a solution to the repeated design problem faced by programmers. In short, how can we create an object from an existing object in the hierarchy? i.e. object creation is deferred to runtime, from the state of another object without type information.

  [Difference between definition and declaration of constructors in C++](http://www.geeksforgeeks.org/c-internals-default-constructors-set-1/) - Don't read if not interested in C++ internals.

  [C++ conversion operators](http://www.geeksforgeeks.org/advanced-c-conversion-operators/) - An interesting C++ trick, less obvious to beginner in C++.

### 18. A stream algorithm to find median

Finding median in a stream of integers. [An online algorithm](http://www.geeksforgeeks.org/median-of-stream-of-integers-running-integers/). Another online algorithm.

### 19. Fake coin puzzle

Decision Trees - [You may be interested in the analysis of the problem and mathematical derivation :)](http://www.geeksforgeeks.org/decision-trees-fake-coin-puzzle/) - I first read the problem statement in Timothy<sup>[3](#Timothy)</sup>.

### 20. Multidimensional arrays in C/C++

C/C++ - How to interpret array and [multidimensional arrays](http://www.geeksforgeeks.org/multidimensional-pointer-arithmetic-in-cc/) and why an array decays to pointer when passed to function. One of the reader comment was '*clears entire pointer concept in short :)*'.

### 21. Second Best in Tournament way

[Finding second best](http://www.geeksforgeeks.org/tournament-tree-and-binary-heap/) and [a foundational note](http://www.geeksforgeeks.org/g-fact-42/)

### 22. Bit twiddling - counting set bits

[Counting bits](http://www.geeksforgeeks.org/program-to-count-number-of-set-bits-in-an-big-array/) - A meta programming technique using C/C++ macros.

### 23. K-th order statistics in BST

[K-th Smallest in BST](http://www.geeksforgeeks.org/find-k-th-smallest-element-in-bst-order-statistics-in-bst/)

### 24. SNOOB

Inspired by [Gowri Kumar's](http://www.slideshare.net/gkumar007/bits-next-higher-presentation) presentation, also later read it in HD<sup>[4](#HD)</sup>. [The Snoob algorithm](http://www.geeksforgeeks.org/next-higher-number-with-same-number-of-set-bits/)

##Why I am not active on Geeksforgeeks or other platforms?

Content preparation & proof reading (self) is time consuming. Each post used to take atleast 2-3 hours. In the past I prepared content during travel time. These days, I am staying near to work location. Apart from keeping abreast of technology, learning new algorithms/problem solving techniques, I am focused on other career priorities - *databases & data stores, data visualization, highly concurrent systems & content marketing platforms in specific.*

--------------------------

## References:

<a name="Manber">1</a>: Introduction to Algorithms by Udi Manber

<a name="Hyde">2</a>: Art of Assembly Language Programming by Randall Hyde

<a name="Timothy">3</a>: Heard on the Street by Timothy Falcon Crack

<a name="HD">4</a>: Hacker's Delight
