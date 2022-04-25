# Definition
An empty program is defined as a program that runs an implementation of the empty algorithm. The empty algorithm does literally nothing.

A program is considered an "instance" of the empty program if and only if it does nothing. There are 3 sets (categories) an instance may belong to. An instance may be identical, equal, or equivalent.
Identity to The Empty Program is defined in terms of payload size. A program is identical if and only if the payload of its "container" is absolutely empty. This container can be (but it's not limited to) a text file, a raster image file, and audio file, chemical bonds, etc. Headers and metadata are not part of the payload. An example of identity is a 0x0 pixel image interpreted using a programming language in which pixels are "OpCodes". If a program is identical to The Empty Program, it's considered "pure".
Equality to The Empty Program is defined in terms of payload content. If a program has no instructions to execute, but it has compiler or interpreter directives (or anything akin to directives), it's considered equal. An example (not limited to this) is a program that imports a library, then proceeds to do nothing. Another example is a program that activates "strict mode" then does nothing.
Equivalence to The Empty Program is defined in terms of actions, effects, and output. If a program has instructions, but these instructions do not affect the environment in a meaningful way, and/or the program doesn't output any data, it may be considered equivalent. An example (again, not limited to) is a program that loops 4 times but halts and does nothing else. Another example is a program entirely composed of "No-Ops" (operators, functions, and/or subroutines that do nothing but waste time).

The set of identical programs is a subset of the equal programs. The set of equal programs is a subset of equivalent programs.
Programs outside of all these 3 sets are not empty programs. However, a program may belong to one of these sets depending on how it is interpreted, which depends on both the chosen (arbitrarily) programming language and the implementation of it.


# Computational Complexity
Any identical and/or equal (see license) program has a time complexity of O(0), and only identical programs have space complexity of O(0). Any other equivalent program has O(1)

# Validity
This program is a polyglot in **a lot** of langs. But it's also a *true polyglot* in the sense that it does exactly the same thing in many langs... it does nothing.

# More info
[RosettaCode](https://www.rosettacode.org/wiki/Empty_program)

[SO](https://stackoverflow.com/questions/3209139/is-the-time-complexity-of-the-empty-algorithm-o0)
