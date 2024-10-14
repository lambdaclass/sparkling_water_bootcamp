# Sparkling Water Bootcamp in Cryptography 01b0

## About

This is the second edition of the Sparkling Water Bootcamp in Cryptography. It is intended to provide an overview of proof systems and some topic in cryptography. It has a duration of 8 weeks of lectures, exercises and coding practice.

## Intended roadmap

The roadmap is dynamic and may change as the bootcamp progresses.

### Week 1 - Fundamentals I

- Math preliminaries: groups, rings and fields
- Finite fields
- RSA cryptosystem
- Univariate polynomials over finite fields
- Shamir secret sharing
- Examples of commonly used finite fields in Cryptography

#### Learning materials:

- [An introduction to mathematical cryptography](https://books.google.com.ar/books/about/An_Introduction_to_Mathematical_Cryptogr.html?id=BHuTQgAACAAJ&source=kp_book_description&redir_esc=y) - Chapter 1 & 3.
- [The MiniGoldilocks prime](https://xn--2-umb.com/22/goldilocks/)
- [Summary on Montgomery arithmetic](https://eprint.iacr.org/2017/1057.pdf)
- [Mersenne primes](https://eprint.iacr.org/2023/824.pdf)
- [Binary fields by Vitalik](https://vitalik.eth.limo/general/2024/04/29/binius.html)
- [Finite Fields](https://www.youtube.com/watch?v=MAhmV_omOwA&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=8)
- [Constructing finite fields](https://www.youtube.com/watch?v=JPiXFn9WA5Y&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=6)
- [Cyclic groups](https://www.youtube.com/watch?v=UIhhs38IAGM&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=3)

#### Motivation

- [Mersenne primes' performance in STWO](https://www.youtube.com/watch?v=_eha0QqAbIA)
- [Circle STARKs](https://www.youtube.com/watch?v=NAhLYMysSdk&list=PLj80z0cJm8QFy2umHqu77a8dbZSqpSH54&index=17)
- [Binius](https://www.youtube.com/watch?v=rgRWcWOll0w&list=PLj80z0cJm8QFy2umHqu77a8dbZSqpSH54&index=4)

#### Exercises

- Find all the multiplicative subgroups of the multiplicative group of integers modulo 17.
- Define a field in lambdaworks.
- Write simple code using the different field operations in lambdaworks.
- Implement a basic version of Shamir secret sharing.

### Week 2 - Fundamentals II

- Elliptic curves over finite fields.
- Diffie-Hellman key exchange
- Small subgroup attacks
- Collision-resistant hash functions
- Merkle trees
- KZG polynomial commitment scheme

#### Recommended material

- [Moonmath Manual](https://leastauthority.com/community-matters/moonmath-manual/) - Chapter 5, until 5.3
- [Programming Bitcoin](https://books.google.fr/books/about/Programming_Bitcoin.html?id=O2aHDwAAQBAJ&source=kp_book_description&redir_esc=y) - Chapters 2 & 3.
- [Introduction to Mathematical Cryptography](https://books.google.com.ar/books/about/An_Introduction_to_Mathematical_Cryptogr.html?id=BHuTQgAACAAJ&source=kp_book_description&redir_esc=y) - Chapter 5 until 5.5
- [Serious Cryptography](https://books.google.com.ar/books/about/Serious_Cryptography.html?id=1D-QEAAAQBAJ&source=kp_book_description&redir_esc=y) - Chapters 11 & 12.
- [KZG basics and application to Mina Bridge](https://blog.lambdaclass.com/mina-to-ethereum-bridge/)

### Week 3 - BabySNARK

- SNARKs - fundamentals.
- Elliptic curve pairings.
- KZG commitment scheme.
- Square span programs
- BabySNARK
- Field extensions

#### Reading material

- [Pairings for beginners](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf)
- [BabySNARK](https://github.com/lambdaclass/lambdaworks/tree/main/examples/baby-snark)

#### Exercises

- Create a simple boolean circuit, generate the square constraint system and generate a proof of execution and verify it.
- Explain what polynomial commitments are and how KZG commitment works.
- Create a false proof if you know the value of the parameter beta.
- Explain the drawbacks of a trusted setup.
- Solve [exercise 2 in lambdaworks](https://github.com/lambdaclass/lambdaworks/tree/main/exercises/challenge_2)

### Week 4 - STARKs and the FRI protocol

- Algebraic intermediate representation (AIR)
- FRI protocol
- STARK protocol
- Comparison between virtual machines

### Week 5 - Groth 16

- R1CS
- Quadratic arithmetic programs
- Groth 16

### Week 6 - Plonk

- Plonkish arithmetization
- Permutation checks
- Different flavors of Plonk

### Week 7 - Lookup arguments and folding schemes

- Lookup arguments
- Plookup
- LogUp
- Folding schemes
- Proof-carrying data (PCD)
- Nova

### Week 8 - More advanced topics

TBD

## Challenges and exercises
