+++
title = "Strategic Tree Rewriting in Attribute Grammars"
date = 2020-11-13

[extra]
speaker = "Lucas Kramer"
+++

{{ image(image="participants.png") }}

# Abstract
Attribute grammars and strategic term rewriting are two formalisms commonly used in programming language implementation.  Attribute grammars work by decorating abstract syntax trees with attributes that define analyses and computations, while term rewriting specifies rewrite rules and strategies that define incremental transformations on terms.  While each approach has its respective advantages, they are typically not used together and some tasks (such as transformations that rely on semantic context) are not well served by either approach.  In this talk I will present strategy attributes, a seamless integration of strategic term rewriting into attribute grammars, that works by automatically generating attribute equations from rewrite rules and strategies.  Several applications of strategy attributes will be demonstrated, including optimizing a simple expression language, evaluation of the lambda calculus, regex matching using derivatives, normalizing C for-loops, and in the optimization of strategy attribute translations.

# Bio
Lucas is a ~4th year Ph.D. candidate working in the Minnesota Extensible Language Tools group at the University of Minnesota. His research interests include extensible programming language engineering and attribute grammar systems.  He additionally holds a part-time student researcher position at Google, working to leverage concepts from functional programming in the Bluespec hardware description language to minimize boilerplate in specifying new operations.  When not busy designing new programming language features, Lucas enjoys reading, hiking, biking and kayaking in his spare time.
