# Introduction

## Exercises

### 1.

**(a)** **Factor $2^{15} − 1 = 32,767$ into a product of two smaller positive integers.**

> Given,\
> $2^{15} − 1 = 32767$\
> $\Rightarrow 32767 = (2^5)^3 - (1)^3$\
> $\Rightarrow 32767 = (2^5 - 1) ((2^5)^2 + 2^5.1 + (1)^2)$\
> $\Rightarrow 32767 = 31 * 1057$ (Ans.)

**(b)** **Find an integer $x$ with $1 < x < 2^{32767}-1$ such that $2^{32767}-1$ is divisible by $x$.**

Let's use the standard divisibility fact for powers:

> If $d\mid n$, then $a^d-1$ divides $a^n-1$.

> Let, $n = dm$.\
> $\therefore a^n-1 = (a^d)^m-1$\
> $= (a^d-1) \sum_{k=0}^{m-1}(a^d)^k$\
> $\therefore a^d-1$ is a factor.

We know that (from **(a)**)

> $32767 = 2^{15}-1 = 31 * 1057$\
> $\therefore 31\mid 32767$\
> $\therefore 2^{31}-1\mid 2^{32767}-1$\
> $\because 1 < 2^{31}-1 < 2^{32767}-1$\
> $\therefore x = 2^{31}-1 = 2147483647$ (Ans.)

### 3. **The proof of Theorem 3 gives a method for finding a prime number different from any in a given list of prime numbers.**

**(a)** **Use this method to find a prime different from 2, 3, 5, and 7.**

> According to Theorem 3 (Euclid), multiply all primes in the list and add 1:  
> $m = 2 \cdot 3 \cdot 5 \cdot 7 + 1 = 210 + 1 = 211$
>
> Check if $m$ is prime:
>
> - 211 is not divisible by 2, 3, 5, or 7
> - Check other small primes up to $\sqrt{211} \approx 14.5$: 11, 13
> - 211 ÷ 11 → remainder ≠ 0, 211 ÷ 13 → remainder ≠ 0
>
> Therefore, 211 is prime and different from the list.

> **Answer:** $211$

**(b)** **Use this method to find a prime different from 2, 5, and 11.**

> Multiply all primes in the list and add 1:  
> $m = 2 \cdot 5 \cdot 11 + 1 = 110 + 1 = 111$
>
> Factor $m$:
>
> - $111 = 3 \cdot 37$
> - Both 3 and 37 are primes not in the list.
>
> Therefore, we can pick either 3 or 37 as a new prime.

> **Answer:** $3 \text{ or } 37$
