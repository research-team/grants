#Mem project intro

##Problem

Current robotics systems usually do not have enough memory and computational capacity to run advanced learning and
behavioral algorithms.

For example AR-601 - CPU: Memory:

In case of emotional behavioral simulations we probably need some intermediate layer to be stored and used on the
robotic system and while realistic NN should be used to generate this intermediate layer using super-computer like
Lomonosov.

##Solution

We propose to use "add one more layer of abstraction paradigm":

1. Develop intermediate layer in probabilistic logic or better [NARS](https://github.com/opennars/opennars):
   2. Develop reasoning environment deployable on robotic system (ex: AR-601)
   2. Develop approach to NARS facts based description of the behavior
1. Develop realistic NN (rNN) approach for of training and behavior including emotions
   2. Develop the rNN structure as the basement for the training and behavior
   2. Implement in the supercomputer simulation
   2. Develop rNN to NARS translation mechanism
   2. Implement the rNN to NARS mechanism

...
