# Goals of Quantum Computing

In the previous sections, we covered the idea of Turing Machines, the Church-Turing Thesis, as well as giving the mathematically accepted definition of complexity and how we can use it to quantitatively understand algorithm performance.

With all that behind you, you'll be able to understand the two main interests driving Quantum Computing.

They are as follows:

> 1. Can a Quantum Computer execute algorithms which are considered uncomputable on classical computers?

> 2. Given an algorithm a TM can compute but is intractable, can it be made tractable through Quantum Computing?

The second point can also be understood in the more broad terms of, "Can a Quantum Computer provide some speed-up of an algorithm that a classical computer cannot?"

## Speed-Up Examples

Some examples of these speed-ups are __Grover's Algorithm__ and __Shor's Algorithm__, two of the most commonly cited algorithms in Quantum Computing.

### Grover's Algorithm

__Grover's Algorithm__ can, given an output value and a function, find the specific input value required to produce that output value in: 

\\[ O(\sqrt{n})\\]

time-complexity. This is fairly astounding considering that at the bare minimum, you need:

\\[ O(n) \\]

time complexity to check each element within the domain of the function. 

### Shor's Algorithm

__Shor's Algorithm__ is an algorithm for integer factorization. It has garnered a lot of attention due to the fact that, should it be implementable in the future, can pose a threat to public-key cryptography which relies on the fact that integer factorization for large values is incredibly prohibitive to do on classical computers.

The current fastest algorithm for integer factorization on classical computers is the __General Number Field Sieve__ which works in sub-exponential but superpolynomial time:

\\[ O(e^{1.9(log \ N)^{1/3}(log \ log \ N)^{2/3}}) \\]

Shor's promises the following speed-up:

\\[ O((log \ N)^{2} (log \ log \ N)(log \ log \ log \ N))\\]

An exponential speed-up over __General Number Field Sieve__
