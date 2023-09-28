# Lambda's Sparkling Water Bootcamp - Repo for challenges and learning path

Public repository for exercises, challenges and all the needs of the Sparkling Water Bootcamp.

## Week 1 - Forging your tools: Finite Fields

This first week will be focused on the development of one of the building blocks of Cryptography: Finite Fields. 

### Recommended material:
- [An introduction to mathematical cryptography](https://books.google.com.ar/books/about/An_Introduction_to_Mathematical_Cryptogr.html?id=BHuTQgAACAAJ&source=kp_book_description&redir_esc=y) - Chapter 1.
- [Finite Fields](https://www.youtube.com/watch?v=MAhmV_omOwA&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=8)
- [Constructing finite fields](https://www.youtube.com/watch?v=JPiXFn9WA5Y&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=6)
- [Cyclic groups](https://www.youtube.com/watch?v=UIhhs38IAGM&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=3)
- [Summary on Montgomery arithmetic](https://eprint.iacr.org/2017/1057.pdf)
- [Mersenne primes](https://eprint.iacr.org/2023/824.pdf)

### Challenges:
- [Implement Montgomery backend for 32 bit fields](https://github.com/lambdaclass/lambdaworks/issues/538).
- [Implement efficient Mersenne prime backend](https://github.com/lambdaclass/lambdaworks/issues/540).
- [Implement efficient backend for pseudo-Mersenne primes](https://github.com/lambdaclass/lambdaworks/issues/393).
- Compare specific field implementations with ordinary Montgomery arithmetic.

### Cryptography content:
- [Serious Cryptography](https://books.google.com.ar/books/about/Serious_Cryptography.html?id=1D-QEAAAQBAJ&source=kp_book_description&redir_esc=y), Chapters 9 & 10.

### Exercises
- Implement naïve version of RSA.
- $7$ is a generator of the multiplicative group of $Z_p^\star$, where $p = 2^{64} - 2^{32} +1$. Find the generators for the $2^{32}$ roots of unity. Find generators for subgroups of order $2^{16} + 1$ and $257$.
- Define in your own words what is a group, a subgroup, a ring and a field.
- What are the applications of the Chinese Remainder Theorem in Cryptography?
- Find all the subgroups of the multiplicative group of $Z_{29}^\star$

## Supplementary Material
- [Polynomial Secret Sharing](https://decentralizedthoughts.github.io/2020-07-17-polynomial-secret-sharing-and-the-lagrange-basis/)
- [Polynomials over a Field](https://decentralizedthoughts.github.io/2020-07-17-the-marvels-of-polynomials-over-a-field/)
- [Fourier Transform](https://www.youtube.com/watch?v=spUNpyF58BY)
- [Fast Fourier Transform](https://www.youtube.com/watch?v=h7apO7q16V0)

## Week 2 - Enter Elliptic Curves

During the second week we'll continue with Finite Fields and begin with Elliptic Curves and dive deeper into Rust

### Recommended material

- [Moonmath Manual](https://leastauthority.com/community-matters/moonmath-manual/) - Chapter 5, until 5.3
- [Programming Bitcoin](https://books.google.fr/books/about/Programming_Bitcoin.html?id=O2aHDwAAQBAJ&source=kp_book_description&redir_esc=y) - Chapters 2 & 3.
- [Introduction to Mathematical Cryptography](https://books.google.com.ar/books/about/An_Introduction_to_Mathematical_Cryptogr.html?id=BHuTQgAACAAJ&source=kp_book_description&redir_esc=y) - Chapter 5 until 5.5
- [Serious Cryptography](https://books.google.com.ar/books/about/Serious_Cryptography.html?id=1D-QEAAAQBAJ&source=kp_book_description&redir_esc=y) - Chapters 11 & 12.
- [Pairings for Beginners](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf) - Chapters 1 & 2

### Exercises

- Define an elliptic curve element type.
- Implement the basic operations: addition and doubling.
- Implement scalar multiplication.
- Check that the point belongs to the correct subgroup.
- The BLS12-381 elliptic curve is given by the equation $y^2 = x^3 + 4$ and defined over $\mathbb{F}_p$ with p = 0x1a0111ea397fe69a4b1ba7b6434bacd764774b84f38512bf6730d2a0f6b0f6241eabfffeb153ffffb9feffffffffaaab. The group generator is given by the point p1 = (0x04, 0x0a989badd40d6212b33cffc3f3763e9bc760f988c9926b26da9dd85e928483446346b8ed00e1de5d5ea93e354abe706c) and the cofactor is $h_1 = 0x396c8c005555e1568c00aaab0000aaab$. Find the generator $g$ of the subgroup of order 
r = 0x73eda753299d7d483339d80809a1d80553bda402fffe5bfeffffffff00000001.
- Implement a naïve version of the Diffie - Hellman protocol
- Implement point compression and decompression to store elliptic curve points

### Challenges

- Special CTF challenge (will be revealed later)
- [Implement BN254](https://github.com/lambdaclass/lambdaworks/issues/548)
- Implement Secp256k1
- Implement Ed25519

### Rust Workshop

- [Aguante Rust](https://youtu.be/nYpMbjzb1t8?si=HNanyXYWcu1xDjG5)

## Week 3: Polynomials

### Recommended material

- [Polynomials](https://www.youtube.com/watch?v=HiaJa3yhHTU&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=6)
- [Lagrange interpolation](https://www.youtube.com/watch?v=REnFOKo9gXs&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=10)
- [Lagrange interpolation and secret sharing](https://www.youtube.com/watch?v=3g4wZnhl4m8&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=3)
- [Moonmath](https://leastauthority.com/community-matters/moonmath-manual/) - Chapter 3.4
- [Convolution polynomial rings - Introduction to Mathematical Cryptography](https://books.google.com.ar/books/about/An_Introduction_to_Mathematical_Cryptogr.html?id=BHuTQgAACAAJ&source=kp_book_description&redir_esc=y) - Chapter 6.9

### Supplementary

- [Roots of unity and polynomials](https://www.youtube.com/watch?v=3KK5RuAgOpA&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=2)
- [Fast Fourier Transform](https://www.youtube.com/watch?v=toj_IoCQE-4)
- [FFT walkthrough](https://www.youtube.com/watch?v=Ty0JcR6Dvis)

### Exercises

- Define a polynomial type.
- Implement basic operations, such as addition, multiplication and evaluation.
- Implement Lagrange polynomial interpolation.
- Implement basic version of Shamir's secret sharing.
