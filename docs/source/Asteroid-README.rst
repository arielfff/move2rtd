![asteroid](asteroid-small.png)

**Asteroid**

Asteroid is an open source, dynamically typed, multi-paradigm programming language heavily influenced by [Python](https://www.python.org), [Rust](https://www.rust-lang.org), [ML](https://www.smlnj.org), and [Prolog](http://www.swi-prolog.org) currently under development at the University of Rhode Island.  Asteroid implements a new programming paradigm called *pattern-matching oriented programming*.  In this new programming paradigm patterns and pattern matching are supported by all major programming language constructs making programs succinct and robust.  Furthermore, patterns themselves are first-class citizens and as such can be passed to and returned from functions as well as manipulated computationally.

**The Basics**

OK, before we get started here is the obligatory ''Hello World!'' program written in Asteroid,



``load "io".``

``println "Hello World!".``



Since pattern matching is at the core of Asteroid we find that the simplest pattern matching occurs in Asteroid's `let` statement. For example,

``let [x,2,y] = [1,2,3].``

here the list  ``[1,2,3]`` is matched against the pattern ``[x,2,y]`` successfully with the corresponding assignments x→1 and y→3. Pattern matching can also occur in iteration. Consider the following program that prints out the names of persons whose name contains a lower case 'p'......
