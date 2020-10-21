# The Turing Machine

Before we delve into what a Turing Machine is, let us present this definition of an __Algorithm__ as *a process or set of rules to be followed in calculations or other problem-solving operations, especially by a computer* <sup>1</sup>. In plain English, nothing more than series of steps that turns some data into a more desirable form (answer, solution, etc).

With the above in mind, the Turing Machine isn't really a machine so much as an abstract model of computation. It was never meant to be implemented in real hardware. Rather, it was intended as a mathematical tool for studying the execution and output of algorithms.

The machine derives its name from the late British computer scientist Alan Turing who came up with the model in a paper published in 1936 <sup>2</sup>.

Its goal at the time was to allow people to figure out the extent and limitations of computation and what it could and could not do.

## How it Works

This "machine" consists of a infinite __tape__ that is divided into an infinite number of __cells__.

Inside each cell can be the following:
* a `1`
* a `0`
* nothing

Above the tape is a __head__ that can perform the following actions <sup>3</sup>
* freely move about the tape (left/right)
* read a cell
* write to a cell
* change its internal state (which determines the next course of action for the head)
* end the computation

The following diagram is a visual representation of the above:

<p align="center">
  <img  src="/Classical-Computation/Turing-Machine/turing-machine.png">
</p>

<p align="center">
   <i> Source: <a href=https://www.sciencedirect.com/science/article/pii/B9780444826183500887> Quantum-Logical Computer by August Stern </a> </i>
</p>

The model itself is made more remarkable by the __Church-Turing Thesis__ which you'll be introduced to in the next section.

Citations:

1. [Google Definition](https://www.google.com/search?sxsrf=ALeKk03AhA_grrmIg-ZNfZFQusF0Nav9Ew%3A1603221517710&source=hp&ei=DTiPX9zNKKG2ggf-6Y4g&q=algorithm&oq=algorithm&gs_lcp=CgZwc3ktYWIQAzIECCMQJzIKCAAQsQMQyQMQQzIICAAQsQMQgwEyBQgAELEDMgIIADIFCAAQsQMyAgguMgUILhCxAzICCAAyAggAOgcILhAnEJMCOgQILhBDOggILhCxAxCDAToLCC4QsQMQxwEQowI6CgguEOoCECcQkwI6BwgjEOoCECc6BwguEOoCECc6DQguEMcBEKMCECcQkwI6CggAELEDEIMBEEM6BwgjECcQnQI6BAgAEEM6BwgAELEDEEM6DAgjECcQnQIQRhD6AToNCAAQsQMQgwEQyQMQQzoFCAAQyQM6CAgAELEDEMkDOgQIABAKOgcIABAUEIcCOgoILhDJAxAnEJMCOg0IABCxAxCDARAUEIcCULcDWM65AWChuwFoLXAAeAaAAaMEiAH5KZIBCjAuMzAuMS41LTGYAQCgAQGqAQdnd3Mtd2l6sAEK&sclient=psy-ab&ved=0ahUKEwiciLrI8cPsAhUhm-AKHf60AwQQ4dUDCAk&uact=5)
2. [Encyclopedia Britannica Entry on Alan Turing](https://www.britannica.com/biography/Alan-Turing)
3. [Quantum Computing and Shor's Algorithm by Matthew Hayward - section on Turing Machines](https://quantum-algorithms.herokuapp.com/299/paper/node5.html)