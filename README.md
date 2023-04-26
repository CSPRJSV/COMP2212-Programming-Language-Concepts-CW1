# COMP2212-Programming-Language-Concepts-CW1
# VX: csprojhelp 备注: github
# COMP2212 专业辅导

In this coursework you are required to design and implement a domain speciﬁc programming language for specifying tiling patterns. For the purposes of this assignment we consider a tile to be a square of discrete cells. A tile of size N consists of N × N cells. A cell may either be ﬁlled or empty. You will need to create a language of your own design that allows users to create larger tiles built from given sets of small tiles.

You are welcome to research any existing languages to inspire the design of your own language. If you want, you could stick closely to the syntax of an existing language. Of course, you are also more than welcome to go your own way and be as original and creative as you want: it is YOUR programming language, and your design decisions.

You are required to (1) invent an appropriate syntax and (2) write an interpreter (possibly using Alex and Happy for lexing and parsing). Your overall goal is :

To design and implement a programming language for specifying large tiling patterns.

For the ﬁve example problems listed below, you will be required to produce a program, in your language, that solves each of the problems. These ﬁve programs, together with the Haskell sources for your interpreter, are the required deliverables for the ﬁrst submission.

Please keep a record of all the sources you consult that inﬂuence your design, and include them in your programming language manual. The manual will be required for the second submission, along with programs for ﬁve additional unseen problems, which we will make public after the deadline for the ﬁrst submission. You should anticipate that the additional problems will be comprised of variations and combinations of the ﬁrst ﬁve problems. You will ﬁnd more procedural details at the end of this document.

The speciﬁcation is deliberately loose. If we haven’t speciﬁed something, it is a design decision for you to make: e.g. how to handle syntax errors, illegal inputs, whether to allow comments, support for syntax highlighting, compile time warnings, any type systems etc. A signiﬁcant part (50%) of the mark will be awarded for these qualitative aspects, where we will also take into account the design of the syntax and reward particularly creative and clean solutions with additional marks. The remaining 50% of the mark will be awarded for correctly solving a number of problems using your programming language. The correctness of your solution will be checked with a number of automated tests.
