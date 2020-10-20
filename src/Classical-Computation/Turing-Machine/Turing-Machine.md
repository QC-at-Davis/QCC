# The Turing Machine

Before we delve into what a Turing Machine is, let us present this definition of an __Algorithm__ as *a process or set of rules to be followed in calculations or other problem-solving operations, especially by a computer*. In plain English, nothing more than series of steps that turns some data into a more desirable form (answer, solution, etc).

With the above in mind, the Turing Machine isn't really a machine so much as an abstract model of computation. It was never meant to be implemented in real hardware. Rather, it was intended as a mathematical tool for studying the execution and output of algorithms.

The machine derives its name from the late British computer scientist Alan Turing who came up with the model in a paper published in 1936.

Its goal at the time was to allow people to figure out the extent and limitations of computation and what it could and could not do.

## How it Works

This "machine" consists of a infinite __tape__ that is divided into an infinite number of __cells__.

Inside each cell can be the following:
* a `1`
* a `0`
* nothing

Above the tape is a __head__ that can perform the following actions
* freely move about the tape (left/right)
* read a cell
* write to a cell
* change its internal state (which determines the next course of action for the head)
* end the computation

The following diagram is a visual representation of the above:

<p align="center">
  <img  src="/Classical-Computation/Turing-Machine/turing-machine.png">
</p>

The model itself is made more remarkable by the __Church-Turing Thesis__ which you'll be introduced to in the next section.