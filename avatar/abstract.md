#Avatar project description

##Problem

There are several techniques and approaches to manage the robotic systems via neuronal activity, and current main
interest is concentrated in the prosthesis approaches, for example: http://www.youtube.com/watch?t=27&v=9NOncx2jU0Q
This approach is well known and rises one problem of caring the equipment on the body of humans.
More than that there are a lot of situations where the personal human presence is not possible or not wanted,
for example the zones of nature and technogenic disasters, outer space, extraterrestrial environments.
Using non anthropomorphic robotic systems could expand the application field of the neuromorphic robotic systems.
The diversity of the applications could be supported and expanded using the option to decouple the
managing neuronal activity and a robotic system.

##Idea

We propose the decoupling of the managing (neuronal) activities and actuating activities (robotic system)
in the form depicted below:

![High level schema](modulor2.png)

In the first stage the neuronal activity of the human body and on the human body is been tracked and processed
in the form that could be transformed and transmitted into the operational commands of the remote robotic system.
We propose to develop the cloud platform that could be capable of the neuronal signals processing and translation
into the robotic system managing activity, proposed framework should be implemented heavily using neural network.

###Main components

![Components diagram](components.png)

We could identify following components:

1. **Filtering** the inbound neuronal activity to produce the valid spiking activity track.
1. **Sorting** the inbound neuronal activity identifying the originating cells that could be associated with the
desired actions of the robotic system.
1. **Normalization** the sorted activity of specific neurons to be translated to the commands of the robotic system.
1. **Translation** of the normalized neuronal activity into the robotic system managing commands.
1. **Transfer** the robotic system managing command via network to the remote robotic system.
1. Further feedback could be provided to the human operator in order to correct the management activity of the
operator.

##Expected results

The research field of this project is wide and we should firstly concentrate on analysis of the current state
of the art to propose approaches for:

- the processing of the neuronal signals including normalization
- the interpretation of the processed neuronal activity into robotic system operational commands
- the universal intermediate interface for the integrated neuromorphic robotic system

Approaches should be presented in the international conferences.
There should be created the series of the prototypes of the components listed above, also the integrated prototype
should be designed and validated on the simulated environment and real life environment.

