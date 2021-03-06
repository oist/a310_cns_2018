# A310 Computational Neuroscience - Okinawa Institute of Science and Technology, 2017/2018
This repository is for modeling practice materials and homework of Computational Neuroscience course at Okinawa Institute of Science and Technology in 2018.

In modeling classes, we focus on implementing physiological concepts about how neural systems function as computer simulations, which will help us understand how diverse phenomena in real neural systems arise from the underlying principles. For this, we will mainly use the [NEURON](https://www.neuron.yale.edu/neuron/) simulation platform, which uses [Python](https://www.python.org) programming language for interface. We will also cover some basic analysis techniques for neural data, but most of our focus will be constructing models and running their simulations.



## Software

We use NEURON 7.5 with Python 3.6. **We recommend using our [Docker](https://en.wikipedia.org/wiki/Docker_(software)) container:** NEURON has non-trivial dependency on Python, the C++ compiler, and other libraries (e.g., MPI), which is quite challenging for fist-time users to make right. **See the [installation guide](./docker/ReadMe.md) for how to install and use the Docker and container**. If you do not want to use this, we recommend compiling the source by following the [instruction](https://www.neuron.yale.edu/neuron/download/getstd) carefully. We discourage installation via binary installers, which has been a source of frustration in the past.



## Schedule of modeling classes and homework dues

### Modeling class: introduction — Jan 18, 2018

In our first modeling session, we will cover the very basic of Python programming language and model/simulation construction by using NEURON.

#### Homework #1 — due: Feb 7, 2018 (extended)

Our first homework is about developing skills in basic Python and handling numerical data in Python and NEURON.

### Modeling class #1 — Feb 8, 2018

In the second modeling class, we will go through how to add synapses on neurons and how to activate them by connecting presynaptic neurons or artificial spike generators --- a neural network!

#### Homework #2 — due: Feb 28, 2018

The second homework is mainly about intergration and transfer of synaptic inputs.

### Modeling class #2 — Mar 1, 2018

The third modeling class will be about active membrane and intracellular mechanisms.

### Modeling class #3 — Mar 22, 2018

The fourth modeling class will focus more on active mechanisms, and also building a networks simulation.

### Modeling class #4 — April 12, 2018  

In our final session, we will work on network simulations with synaptic plasticity.

---
_Written by Sungho Hong, Computational Neuroscience Unit, Okinawa Institutes of Science and Technology_

_January 2018_
