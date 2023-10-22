# bw8
> ## *If you wish to make an apple pie from scratch, you must first invent the universe.*
> <sub>Carl Sagan</sup>

A homebrew 8-bit ISA with reference implementations and custom tooling.

## Instruction Set
The uniting element of all projects in this organization is the bw8 instruction set. This is a custom 8-bit ISA which was developed with ease of use-by-humans in mind. This goal is juxtaposed against the reality of the set using 8-bit opcodes - there's very little space to provide rich addressing modes and spacious register sets. As such, bw8 has an eccentric but undeniably unique personality. After sufficient umming and ahhing over instruction inclusion, its effectively found balance in the stated design goals. With a stable instruction set in hand, this GitHub organization emerges as a collection of projects implementing the set in one way or the other.

## Opal
Opal is a homebrew source level language developed to fulfill two separate goals:
1. To develop a native and self hosted language; that is, the language must compile to machine code executable by the host system, and that the compiler must be written in the source language.
2. To develop a multi-tasking kernel for BW8 Machine (actual name pending...), the computer built around the bw8 CPU - a task deemed too daunting to tackle using assembly alone. Given no languages target bw8, a compiler must be constructed.

The design and development of Opal is documented within this organization, via [discussions](https://github.com/orgs/bw8-systems/discussions) and [repositories](https://github.com/bw8-systems/opyl).
