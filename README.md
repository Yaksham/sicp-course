# Structure and Interpretation of Computer Programs

This is a self-paced course in programming.

It is based on Berkley's course delivered in Spring 2011 of the same name.

The target audience are serious programmers looking to advance their knowledge beyond some specific  language or technology.

The course itself is based on the highly acclaimed [SICP ](http://sarabander.github.io/sicp/html/index.xhtml) book,  considered by many to be one of the most important Computer Science books ever written.

# Usage

Fork the repo.

Study each item in sequence, checking off each item as you finish it.  

You can use [Dr. Racket](https://racket-lang.org/) in [SICP compatibility mode](https://docs.racket-lang.org/sicp-manual/index.html?q=sicp#%28part._.Introduction_to_the__lang_sicp_language%29) to execute the code in the book.

# Course overview

Computer science isn’t about computers (that’s electrical engineering) and it isn’t primarily a science (we invent things more than we discover them).

CS is partly a form of engineering (concerned with building reliable, efficient mechanisms, but in software instead of metal) and partly an art form (using programming as a medium for creative expression).

Programming is really easy, as long as you’re solving small problems. Any kid in junior high school can write programs in BASIC, and not just exercises, either; kids do quite interesting and useful things with computers. But BASIC doesn’t scale up; once the problem is so complicated that you can’t keep it all in your head at once, you need help, in the form of more powerful ways of thinking about programming. (But in this course we mostly use small examples, because we’d never get finished otherwise, so you have to imagine how you think each technique would work out in a larger case.)

We deal with three big programming styles/approaches/paradigms:

* Functional programming (2 months)
* Object-oriented programming (1 month)
* Client-server programming (1 week)
* Logic programming (1 week)

The big idea of the course is abstraction: inventing languages that let us talk more nearly in a problem’s own terms and less in terms of the computer’s mechanisms or capabilities. There is a hierarchy of abstraction:

Application programs<br/>
High-level language (Scheme)<br/>
Low-level language (C)<br/>
Machine language<br/>
Architecture (registers, memory, arithmetic unit, etc)<br/>
circuit elements (gates)<br/>
transistors<br/>
solid-state physics<br/>
quantum mechanics<br/>

We look at lower levels; all are important but we want to start at the highest level to get you thinking right.

# Functional Programming &#x2611;

[&#x2611;] Watch [MIT 6.001 SICP - Lecture 1A: Overview and Introduction to Lisp](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/1a-overview-and-introduction-to-lisp)

[&#x2611;] Read [Section 1.1: The Elements of Programming](http://sarabander.github.io/sicp/html/1_002e1.xhtml#g_t1_002e1) 

[&#x2611;] Watch [Computer Science 61A - Lecture 1: functional programming 1](https://archive.org/details/ucberkeley_webcast_l28HAzKy0N8)

[&#x2611;] Watch [Computer Science 61A - Lecture 2: functional programming 2](https://archive.org/details/ucberkeley_webcast_TTK2lZoWbPQ)

[&#x2611;] Solve Week 1 Lab

[&#x2611;] Solve Week 1 Homework

# Higher-order procedures &#x2611;

[&#x2611;] Watch [MIT 6.001 SICP - Lecture 2A: Higher-order Procedures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2a-higher-order-procedures)

[&#x2611;] Read [Section 1.3: Formulating Abstractions with Higher-Order Procedures](http://sarabander.github.io/sicp/html/1_002e3.xhtml#g_t1_002e3)

[&#x2611;] Watch [Computer Science 61A - Lecture 3: higher-order procedures 1](https://archive.org/details/ucberkeley_webcast_ogIGxEzvnSE)

[&#x2611;] Watch [Computer Science 61A - Lecture 4: higher-order procedures 2](https://archive.org/details/ucberkeley_webcast_ZvH3wF2qg7Q)

[&#x2611;] Solve Week 2 Lab

[&#x2611;] Solve Week 2 Homework

# Recursion and iteration &#x2611;

[&#x2611;] Watch [MIT 6.001 SICP - Lecture 1B: Procedures and Processes; Substitution Model](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/1b-procedures-and-processes-substitution-model)

[&#x2611;] Read [Section 1.2-1.2.4: Procedures and the Processes They Generate](http://sarabander.github.io/sicp/html/1_002e2.xhtml#g_t1_002e2)

[&#x2611;] Watch [Computer Science 61A - Lecture 7: orders of growth](https://archive.org/details/ucberkeley_webcast_32L5j10rrK0)

[&#x2611;] Watch [Computer Science 61A - Lecture 8: recursion and iteration](https://archive.org/details/ucberkeley_webcast_0G3tNuBBO5I)

[&#x2611;] Solve Week 3 Lab

[&#x2611;] Solve Week 3 Homework

# Data abstraction, sequences &#x2611;

[&#x2611;] Watch [MIT 6.001 SICP - Lecture 2B: Compound Data](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/2b-compound-data)

[&#x2611;] Read [Sections 2.1: Introduction to Data Abstraction](http://sarabander.github.io/sicp/html/2_002e1.xhtml#g_t2_002e1)

[&#x2611;] Watch [Computer Science 61A - Lecture 9: data abstraction](https://archive.org/details/ucberkeley_webcast_Oy36XpGVyjA)

[&#x2611;] Read [Section 2.2.1: Representing Sequences](http://sarabander.github.io/sicp/html/2_002e2.xhtml#g_t2_002e2_002e1)

[&#x2611;] Watch [Computer Science 61A - Lecture 10: sequences](https://archive.org/details/ucberkeley_webcast__qGeRWplPgc)

[&#x2611;] Watch [Computer Science 61A - Lecture 11: Example: calculator](https://archive.org/details/ucberkeley_webcast_nzMPF59Ackg)

[&#x2611;] Solve Week 4 Lab

[&#x2611;] Solve Week 4 Homework

# Hierarchical data/Scheme interpreter

[&#x2611;] Read [Section 2.2.2: Hierarchical Structures](http://sarabander.github.io/sicp/html/2_002e2.xhtml#g_t2_002e2_002e2)

[&#x2611;] Read [Section 2.2.3: Sequences as Conventional Interfaces](http://sarabander.github.io/sicp/html/2_002e2.xhtml#g_t2_002e2_002e3)

[&#x2611;] Watch [Computer Science 61A - Lecture 12: hierarchical data](https://archive.org/details/ucberkeley_webcast_pSuEz5ZCVAg)

[&#x2611;] Read [Section 2.3.1: Quotation](http://sarabander.github.io/sicp/html/2_002e3.xhtml#g_t2_002e3_002e1)

[ ] Read [Section 2.3.3 Example: Representing Sets](http://sarabander.github.io/sicp/html/2_002e3.xhtml#g_t2_002e3_002e3)

[ ] Watch [Computer Science 61A - Lecture 13: hierarchical data](https://archive.org/details/ucberkeley_webcast_kbqJ3UGPgOc)

[ ] Watch [Computer Science 61A - Lecture 14: Example: Scheme-1 interpreter](https://archive.org/details/ucberkeley_webcast_3FjDrWv00Hc)

# Generic operators

[ ] Read [Section 2.4: Multiple Representations for Abstract Data](http://sarabander.github.io/sicp/html/2_002e4.xhtml#g_t2_002e4)

[ ] Read [Section 2.5 (through 2.5.2): Systems with Generic Operations](http://sarabander.github.io/sicp/html/2_002e5.xhtml#g_t2_002e5)

[ ] Watch [Computer Science 61A - Lecture 16: generic operators](https://archive.org/details/ucberkeley_webcast_rz_XpDhDtFI)

[ ] Watch [Computer Science 61A - Lecture 17: generic operators](https://archive.org/details/ucberkeley_webcast_8HDIqZ2ZqKI)

# Object-oriented programming

[ ] Read [Object-Oriented Programming | Above the line view](http://inst.eecs.berkeley.edu/~cs61a/reader/aboveline.pdf)

[ ] Watch [Computer Science 61A - Lecture 18: object-oriented programming](https://archive.org/details/ucberkeley_webcast_jq1v8YUftxE)

[ ] Watch [Computer Science 61A - Lecture 19: object-oriented programming](https://archive.org/details/ucberkeley_webcast_S9mGKy3Dzqw)

[ ] Watch [Computer Science 61A - Lecture 20: object-oriented programming](https://archive.org/details/ucberkeley_webcast_AYoW8-L2dTQ)

# Local state variables, environments

[ ] Read [Section 3.1: Assignment and Local State](http://sarabander.github.io/sicp/html/3_002e1.xhtml#g_t3_002e1)

[ ] Read [Section 3.2: The Environment Model of Evaluation](http://sarabander.github.io/sicp/html/3_002e2.xhtml#g_t3_002e2)

[ ] Read [Object-Oriented Programming | Below the line view](http://inst.eecs.berkeley.edu/~cs61a/reader/belowline.pdf)

[ ] Watch [Computer Science 61A - Lecture 21: assignment and state](https://archive.org/details/ucberkeley_webcast_crlcqL7lKME)

[ ] Watch [Computer Science 61A - Lecture 22: environments](https://archive.org/details/ucberkeley_webcast_uxvRoOV9nOk)

[ ] Watch [Computer Science 61A - Lecture 23: environments](https://archive.org/details/ucberkeley_webcast_jmDguUbxOns)

# Mutable data, queues, tables

[ ] Read [Sections 3.3.1-3.3.3](http://sarabander.github.io/sicp/html/3_002e3.xhtml#g_t3_002e3_002e1)

[ ] Watch [Computer Science 61A - Lecture 24: mutable data](https://archive.org/details/ucberkeley_webcast_OCocDioUZOo)

[ ] Watch [Computer Science 61A - Lecture 25: mutable data](https://archive.org/details/ucberkeley_webcast_YgUZP1YbHsM)

[ ] Watch [Computer Science 61A - Lecture 26: vectors](https://archive.org/details/ucberkeley_webcast_vV7gargdGxU)

# Client/server paradigm, Concurrency

[ ] Read [Section 3.4: Concurrency: Time Is of the Essence](http://sarabander.github.io/sicp/html/3_002e4.xhtml#g_t3_002e4)

[ ] Watch [Computer Science 61A - Lecture 30: client-server programming](https://archive.org/details/ucberkeley_webcast_Lr4zVJPpMrM)

[ ] Watch [Computer Science 61A - Lecture 31: concurrency](https://archive.org/details/ucberkeley_webcast_tfTD0B8dX7I)

[ ] Watch [Computer Science 61A - Lecture 32: concurrency](https://archive.org/details/ucberkeley_webcast_a_qhlzmXqAo)

# Streams

[ ] Read [Section 3.5.1-3.5.3](http://sarabander.github.io/sicp/html/3_002e5.xhtml#g_t3_002e5_002e1)

[ ] Read [Section 3.5.5: Modularity of Functional Programs and Modularity of Objects](http://sarabander.github.io/sicp/html/3_002e5.xhtml#g_t3_002e5_002e5)

[ ] Watch [Computer Science 61A - Lecture 33: streams](https://archive.org/details/ucberkeley_webcast_LLl89UwSflo)

[ ] Watch [Computer Science 61A - Lecture 34: streams](https://archive.org/details/ucberkeley_webcast_mtl0z0HgRTM)

[ ] Watch [Computer Science 61A - Lecture 35: Therac-25](https://archive.org/details/ucberkeley_webcast_nxX-aAvZbmM)

# Metacircular evaluator

[ ] Read [Section 4.1: The Metacircular Evaluator](http://sarabander.github.io/sicp/html/4_002e1.xhtml#g_t4_002e1)

[ ] Watch [Computer Science 61A - Lecture 36: metacircular evaluator](https://archive.org/details/ucberkeley_webcast_E8ZyYL1qWWY)

[ ] Watch [Computer Science 61A - Lecture 37: metacircular evaluator](https://archive.org/details/ucberkeley_webcast_0SbpbHiyyEU)

[ ] Watch [Computer Science 61A - Lecture 38: mapreduce](https://archive.org/details/ucberkeley_webcast_OVbHFr6SG_8)

[ ] Watch [Computer Science 61A - Lecture 39: mapreduce](https://archive.org/details/ucberkeley_webcast_tlABAGE-Tvc)

# Analyzing evaluator

[ ] Watch [Computer Science 61A - Lecture 40: analyzing evaluator](https://archive.org/details/ucberkeley_webcast_S9VoxtdsRyA)

# Lazy evaluator, Nondeterministic evaluator

[ ] Read [Section 4.2: Variations on a Scheme -- Lazy Evaluation](http://sarabander.github.io/sicp/html/4_002e2.xhtml#g_t4_002e2)

[ ] Read [Section 4.3: Variations on a Scheme -- Nondeterministic Computing](http://sarabander.github.io/sicp/html/4_002e3.xhtml#g_t4_002e3)

[ ] Watch [Computer Science 61A - Lecture 41: lazy evaluator](https://archive.org/details/ucberkeley_webcast_WJsgTZsFE3M)

# Logic programming

[ ] Read [Section 4.4.1-4.43](http://sarabander.github.io/sicp/html/4_002e4.xhtml#g_t4_002e4_002e1)

[ ] Watch [Computer Science 61A - Lecture 42: logic programming](https://archive.org/details/ucberkeley_webcast_JIMS_mspmug)

[ ] Watch [Computer Science 61A - Lecture 43: logic programming](https://archive.org/details/ucberkeley_webcast_i5XtLVwTcZY)

# Review

[ ] Watch [Computer Science 61A - Lecture 44: Review](https://archive.org/details/ucberkeley_webcast_zWiQru4tn-o)
