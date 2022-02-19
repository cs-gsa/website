+++
title = "Testing Polymorphic Functions with Ease"
date = 2022-02-04

[extra]
speaker = "Zhuyang Wang"
+++


# Abstract
In statically typed languages, a polymorphic function takes types as arguments, and it can be specialized later when used. Thus it is an effective way to avoid boilerplate. It turns out that polymorphic functions are also easier to test, The reason is that we know little about the types, so it is more restrictive to write a polymorphic function. In this talk, I will present an efficient method for testing polymorphic functions, The method works by eliminating a large class of unnecessary test cases, and it has been implemented in Haskell for property-based testing of polymorphic functions.

# About the speaker
Zhuyang Wang is a third-year Ph.D. student at the Department of Computer Science & Engineering, advised by Favonia. His interests include program testing and type theory.