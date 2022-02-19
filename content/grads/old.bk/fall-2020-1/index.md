+++
title = "Semantic Preservation in Extensible Languages"
date = 2020-10-02

[extra]
speaker = "Dawn Michaelson"
+++

{{ image(image="participants.png") }}

# Abstract
Extensible languages, composed of a host and independently-developed
extensions, allow users to select the language features they wish to use, which
simplifies programming.  However, there is currently no strong guarantee that
independent extensions will interoperate correctly, so some of the features
introduced in one extension may not work correctly when other extensions are
included.  We introduce a method for proving that independent extensions will
preserve language properties when composed.  Our method allows both the host and
extensions to introduce language properties defining correct behavior of the
semantics introduced.  The host and extensions have modular proof obligations
for their properties, which will provide a full proof of their properties even
when other, unknown extensions are added to the language.

# About the speaker
Dawn Michaelson is a fourth-year graduate student officially advised by Eric
Van Wyk and unofficially advised by Gopalan Nadathur.  She is working on proving
metatheoretic properties of extensible languages and using monads implicitly in
attribute grammars.  She is originally from Wisconsin.
