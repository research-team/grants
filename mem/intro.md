#Dream project intro

##Problem

Current robotics systems usually do not have enough memory and computational capacity to run advanced learning and
behavioral algorithms.

For example AR-601:

* CPU  - 4th Gen Intel® Core™ i7-4700EQ 4-Core 3.4GHz processor;
* System Memory -  1 x204-Pin DDR3L 1333MHz SO-DIMMup to 8 GB;

In case of emotional behavioral simulations we probably need some intermediate layer to be stored and used on the
robotic system and while realistic NN should be used to generate this intermediate layer using super-computer like
Lomonosov.

##Solution

We propose to use "add one more layer of abstraction paradigm" that is depicted below:

Data structures:

1. Lightweight ontology
1. Realistic neural network (rNN)

![Components diagram](components.png)

- a. In this position robotic system transfers the accumulated experience in the lightweight ontologies structures into rNN
- b. Processing is done as follows:
  - Firstly the accumulated experience in the form of light weight ontologies is transferred from a robotic system to
  the processing center
  - Light weight ontologies should be translated in the form applicable to the rNN
  - Then applied to the rNN that is trained and is producing new updated behavior strategies during some period of
  time (over night) updating the neuronal circuits
  - Then updated neuronal circuits should be translated in the form of lightweight ontologies applied to the robotic system
- c. The updated lightweight ontologies are transferred to the robotic system and applied to it.
- d. The robotic system runs updated behavioral strategies in current environment and accumulate new experience to be processed again starting from a.

###Development plan

1. Develop intermediate layer in probabilistic logic or better [NARS](https://github.com/opennars/opennars):
   2. Develop reasoning environment deployable on robotic system (ex: AR-601)
   2. Develop approach to NARS facts based description of the behavior
1. Develop realistic NN (rNN) approach for of training and behavior including emotions
   2. Develop the rNN structure as the basement for the training and behavior
   2. Implement in the supercomputer simulation
   2. Develop rNN to NARS translation mechanism
   2. Implement the rNN to NARS mechanism

...
