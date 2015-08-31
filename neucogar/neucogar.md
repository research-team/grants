#Artificial cognitive architecture with consciousness option

##Background

Building artificial consciousness, both machine, and human is an old dream.  For machine consciousness
AI research has been looking for solutions for several decades and even today some of the best minds in
the field, such as Marvin Minsky and leader of the Blue Brain Projects, are devoting considerable resources
to solving that problem. Why is it then that we are so far from a solution? The obstacles are many, and this
particular project focuses on one of the most formative direction: neurobiologically inspired systems and approaches.
 
One of the major obstacles in his endeavor is the lack of understanding of human brain functioning.
 
We propose a step towards the solution as follows:
 
1. To establish the environment with close collaboration between several cross-disciplinary research fields from Cognitive Science (cognitive hexagon): Neuroscience, Psychology, Philosophy, Anthropology and Sociology and cross disciplinary research of: neuro-psychology, neuro-philosophy and neuro-psychology-ai, neuro-philosophy-ai that involves computer scientists and engineers.

2. To develop quadrifocal approach to build novel models that will take in account: neuro-psychological-philosophical-AI aspects of the problems and natural objects of the research

3. To develop state of the art implementations of the models with possible outburst to industrial domains and applications.

##Objectives

The ultimate goal of the project is to create the cognitive architecture with the option of human consciousness with close to realistic, but still effective in modern Von Neumann architectures, neurobiological processes. We have to use some simplification that should be based on understanding of brain work principles. In other words main goal is to create cognitive architecture with realistic for modern computers (clusters) performance implementation of neurobiological nature of mental processes. We decided to use two cognitive architectures of Marvin Minsky and Aaron Sloman that provide the complete picture of human mental processes. Marvin Minsky proposed "Model of six" in his book [@emotionmachine] that contains of six levels of mental activities:

1. Instinctive reactions
1. Learned reactions
1. Deliberative thinking
1. Reflective thinking
1. Self-reflective thinking
1. Self-conscious reflections

With following mechanism of mental processing: Critic -> Selector -> Way to think / Critic, for details please see [@emotionmachine].

Aaron Sloman proposed H-CogAff that consist of following parts:

1. Perception mechanisms (hierarchy)
1. Actions mechanisms (hierarchy)

1. Reactive processes system with alarms
1. Deliberative processes system
1. Long term associative memory
1. Motive activation
1. Meta-management (reflective) processes
1. Personae

For further details please see [@sloman2003]

Work breakdown structure is presented below:

1. Develop theoretical model of cognitive architecture with option of consciousness encapsulating:
    2. Philosophical point of view (Model of six [@emotionmachine], H-CogAff[@sloman2003])
	2. Neurobiological nature of processes in a brain
	2. Psychological phenomena: emotions, learning, self-awareness ...
1. Implementation of abstract/simplified cognitive architectures of Model of Six or/and H-CogAff based on theoretical model
    2. Study implementation approaches of cognitive architecture
    2. Implement approaches in the way of concept software architecture
    2. Implement of simplified cognitive architecture as prototype generation 0

1. Implementation of more realistic cognitive architectures of Model of Six or/and H-CogAff based on theoretical model
    2. Study implementation approaches of cognitive architecture
    2. Implement approaches in the way of concept software architecture
    2. Implement of simplified cognitive architecture prototype generation 1

1. Implementation of realistic cognitive architectures of Model of Six or/and H-CogAff based on theoretical model
    2. Study implementation approaches of cognitive architecture
    2. Implement approaches in the way of concept software architecture
    2. Implement of simplified cognitive architecture prototype generation 2

##Relevance

The Development in the field of artificial intelligence are stimulated by the rapid increase of data to be processed which, through formalization, analysis and synthesis,  traditional logico-mathematical methods are not considered sufficient. Research in the field of fuzzy logic has received wide support.

The main issue in the evolution of Neurobiologically inspired systems is to understand how mammals brains work (in particular how rats' brains function, and as a consequence human brain). The current study due to its cross-disciplinarity has 2 aspects: 
Medical: rehabilitation of the brain after patrimonial damage;
Artificial intelligence: to reconstruct the cortical column in computing systems functions and subsequent expansion to systems capable of performing basic cognitive functions.
Many scientists in Europe and USA work on  Neurobiologically inspired systems research. Here we can mention Blue Brain and Human Brain projects. The second project had a budget of 1.4 billion Euros. There is a program in the USA costing 300 million dollars per year. Under this program, Von Neumann architecture chips have already been developed, consuming 10 000 times less energy than other current microprocessors.
Current state of the research field creates options for the creation of self-learning systems comparable with the human brain.  At this point we must mention IBM company (USA) which has outstanding results in research in this area.  They have developed a technology reproducing1 million neurons in 1 chip. The relevance of cross-disciplinary research in the field of AI + Neuroscience can not be underestimated, it is necessary to take into account the creation of the so called "dumbbell" laboratories at Harvard, where scientists were asked to work in one lab to enhance communications. A major breakthrough in the field of robotic systems is virtually impossible without controls for autonomous robotic systems, which has demonstrated its extreme inefficiency and inflexibility, creating a precedent impossible to build a robotic system that can survive in real life and social interactions.

##Methodology

###Cross-disciplinary research

For the purposes of the cross-disciplinary research the group of international scientists was created that includes: neuro-scientist, psychologist, philosopher and specialists from AI domain.

In the domain presented above there are several possible directions. First of all most obvious direct mapping of the psychological and/or philosophical models in to the computational system this was done in implementations of several cognitive architectures. But, main disadvantage of strait mapping leads to miss low level details that could be crucial for implementation of cognitive architectures with option of machine consciousness.

The other way could be the creation of uniform theory of complex phenomena like: emotions, awareness, learning, anticipation or subjective experience that could run through perspectives: philosophical, psychological, neurobiological:

![Anthropocentric to computer processes mapping](layers_binding.png)

Based on this theory the phenomena could be recreated starting from lowest level of cellular mechanisms rebuilding all the phenomena in the other perspectives.
This approach demands new holistic and functional ways to deal with complex problems to maintain overall picture and functions that implements phenomena of overall picture and have low level mechanisms taken in account in the same time.

On the other hand the view on recreation of psychological and philosophical phenomena in a computational system puts us in front of perspective of definition of new domains in computer science:

![P^3 model](p3_model.png)

###Computational emotions

Uniform theory should take in account at least three perspectives/views on phenomena. We suppose that wider the perspective we have the more relevant model we should generate. This complex task could be done only in cross disciplinary research building bridges between neuroscience and psychology and philosophy. Only this model could be adequately mapped to the computational system in some extent reimplementing the phenomena in computational system, for the several reasons: missing the neurobiological perspective leads to missing low level computational mechanism using only high level views researchers frequently create the cognitive architectures that can not be mapped to the computational processes of the human brain, on the other side missing overall picture leads to modelling only small parts of overall system that miss integration with other subsystems and has narrow view and application focus.
Here we should admit the importance of the analysis of existing models of emotions psychological, neurobiological and neuropsychological along with neurophilosophical. The result of the analysis should provide the wide basis for modelling of neuropsychological phenomena that could be modelled in computational spiking neural network where we could test the relevance of the mapping methods.

##Ubique method

It is quite common to use functional decomposition method to deal with the complex problems, but we see one problem of this approach that are widely used in modern research. Dealing with low-level details researches usually loose overall picture high-level goals. In contrast dealing with only high-level descriptions lead to implementation of inadequate models in computational systems, that was mentioned above. To avoid both situations we proposed bidirectional approach that should take in account both functional decomposition and holistic view on the complex problem like: 'hard problem' of machine consciousness, machine perception, machine self-awareness, subjective experience. This method could be described like: **Imagine 1 neuron -> cortical column ~ 10 000 neurons -> Brodmann area (V1) 140 million -> Cortex 19 - 23 billions -> Whole brain 86 billions (10^14–10^15 Synapses)**
Inside this paradigm we should build first overall model that could describe neuro-psychological and psychologically-philosophical and neuro-philosophical phenomena and then with proper understanding we could implement them in the computational systems.

##Results

In two years to produce several prototypes that could help to identify current problems in implementation of the cognitive architecture with function of consciousness from high-level (philosophical) and low-level neurobiological perspectives.
The main output should be the prototypes as software and analysis published in scientific journals and presented on conferences:

1. Theoretical cognitive architecture with the function of consciousness prototypes v. 1 and v. 2
1. Neuromodulatory cognitive architecture (NEUCOGAR) Dopamine prototype, Serotonin prototype and Noradrenaline prototype (integrated prototype
1. Cortical column topology prototype of generation v. 1 and v. 2

##Team

|Role            | N
|----------------|-----
|Project manager | 1
|Lead researcher | 2
|Researchers     | 4 
|Teamlead        | 1 FTE
|Architect       | 2 FTE
|Developer       | 6 FTE

##Project plan

![AC project plan](iProject_plan.png)
