# notes
Notes from my research for forest-lang, mostly in the form of links to reference later.

### High level design inspiration

* [Oberon – The Overlooked Jewel by Michael Franz](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.90.7173&rep=rep1&type=pdf)

> In order to find the optimal cost/benefit ratio, Wirth used a highly intuitive metric, the origin of which is unknown to me but that may very well be Wirth’s own invention. He used the compiler’s self-compilation speed as a measure of the compiler’s quality. Considering that Wirth’s compilers were written in the languages they compiled, and that compilers are substantial and non-trivial pieces of software in their own right, this introduced a highly practical benchmark that directly contested a compiler's complexity against its performance. Under the self- compilation speed benchmark, only those optimizations were allowed to be incorporated into a compiler that accelerated it by so much that the intrinsic cost of the new code addition was fully compensated.

* [Out of the Tar Pit](http://curtclifton.net/papers/MoseleyMarks06a.pdf)

### Lambda Calculus
* [The Implementation of Functional Programming Languages](https://www.microsoft.com/en-us/research/uploads/prod/1987/01/slpj-book-1987-r90.pdf)
* [An algorithm for optimal lambda calculus reduction](https://dl.acm.org/citation.cfm?id=96711)

### Data structures

* [Implementing strings](http://beza1e1.tuxen.de/strings.html)

### Parsing

* [Parsing: a timeline](https://jeffreykegler.github.io/personal/timeline_v3)
* [A typed, algebraic approach to parsing](https://www.cl.cam.ac.uk/~nk480/parsing.pdf)

### Types

* [Programming with Abstract Data Types by Liskov & Zilles](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.136.3043&rep=rep1&type=pdf)
* [Existential quantifiers in abstract data types](https://link.springer.com/chapter/10.1007/3-540-09510-1_7)
* [Seven Sketches in Compositionality: An Invitation to Applied Category Theory](https://arxiv.org/pdf/1803.05316.pdf)
* [Mathematical Logic in Computer Science](https://arxiv.org/pdf/1802.03292.pdf)
* [Fused effect systems in Haskell](https://github.com/robrix/fused-effects)
* [Simple explanation of Hindley Milner](https://eli.thegreenplace.net/2018/type-inference/)
* [Simple explanation of type unification](https://eli.thegreenplace.net/2018/unification/)
* [Jan's proposal to add Row Types to GHC](https://github.com/ghc-proposals/ghc-proposals/pull/180)
* [Type driven development in Idris](https://www.youtube.com/watch?v=mOtKD7ml0NU&feature=youtu.be)
* [A reckless introduction to Hindley-Milner type inference](http://reasonableapproximation.net/2019/05/05/hindley-milner.html)

### Proofs

 * [Fiat: Deductive Synthesis of AbstractData Types in a Proof Assistant](http://plv.csail.mit.edu/fiat/papers/fiat-popl2015.pdf)

### DOM

* ["A Theory of Changes for Higher-Order Languages" by Cai, Gairrusso, Rendel and Ostermann.](https://arxiv.org/pdf/1312.0658.pdf) - found from https://github.com/paf31/purescript-firkin

### Modules

* [1ML — core and modules united](https://people.mpi-sws.org/~rossberg/1ml/)

### Package Management

* [A Peer-to-Peer Distribution System for
Software Package Releases and Updates](http://www.cs.sfu.ca/~jcliu/Papers/apt-p2p.pdf)
* [Secure ledgers don't require proof-of-work](https://pfrazee.github.io/blog/secure-ledgers-dont-require-proof-of-work)

### Tests

* [Tools for Discovery, Refinement and Generalization of Functional Properties by Enumerative Testing](https://matela.com.br/paper/rudy-phd-thesis-2017.pdf)
