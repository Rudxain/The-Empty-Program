# Definition
An empty program is defined as a program that runs an implementation of the empty algorithm. The empty algorithm does **literally nothing**.

A program is considered an "instance" of TEP if and only if it does nothing. There are 3 sets/categories an instance may belong to:

0. **Identity** to The Empty Program is defined in terms of [payload](https://en.wikipedia.org/wiki/Payload_(computing)) size. A program is identical if and only if the payload of its "container" is absolutely empty. This container can be (but it's not limited to) a text file, a raster image file, and audio file, [chemical bonds](https://en.wikipedia.org/wiki/Chemical_computer), etc. An example of identity is a 0x0 pixel image interpreted using a programming language in which pixels are "OpCodes" (like in [Piet](https://esolangs.org/wiki/Piet)). If a program is identical to TEP, it's considered *"pure"*.

1. **Equality** is defined in terms of payload content. If a program has no instructions to execute, but it has compiler or interpreter directives (or anything akin to directives), it's considered equal. An example is a program that imports a library, then proceeds to do nothing. Another example is a program that activates "strict mode" then does nothing.

2. **Equivalence** is defined in terms of actions, effects, and output. If a program has instructions, but these instructions do not affect the environment in a meaningful way, and/or the program doesn't output any data, it may be considered equivalent. An example is a program that loops 4 times but halts and does nothing else. Another example is a program entirely composed of "No-Ops" (operators, functions, and/or subroutines that do nothing but waste time).

The set of identical programs is a subset of the equal programs. The set of equal programs is a subset of equivalent ones.
Programs outside all these 3 sets are not EPs. However, a program may belong to one of these sets *depending on how it's interpreted*, which depends on both the chosen (arbitrarily) programming lang and its implementation of it. Source code comments are kind of controversial, because in some langs (like JS) they can have a subtle impact in the runtime of a program and its interaction wtih other components, even when `eval` isn't involved.

# Computational Complexity
Any identical and/or equal program has a time complexity of O(0), and only identical programs have space complexity of O(0). Any other equivalent program has O(1) for the reasons mentioned above. [More info on SO](https://stackoverflow.com/questions/3209139/is-the-time-complexity-of-the-empty-algorithm-o0)

# Validity
This program is a [polyglot](https://en.wikipedia.org/wiki/Polyglot_(computing)) in **a lot** of langs. But it's also a *true polyglot* in the sense that it does exactly the same thing in many langs.

It can also be considered a trivial [quine](https://en.wikipedia.org/wiki/Quine_(computing)), but since the program doesn't make use of I-O, it doesn't output an empty string, it outputs an undefined value, which is not quite the same.

The code coverage is either `undefined` or `Infinity` lol

# More info & related stuff
[RosettaCode](https://www.rosettacode.org/wiki/Empty_program)

[No Code](https://github.com/kelseyhightower/nocode)
