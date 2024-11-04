# Ph.D.-manuscript

This repository holds the LaTeX code for generating the PDF file of the "Safe and Energy Efficient Decision/Control Architecture for a Formation of Multi-Vehicle System
in Dynamic Environment" thesis, written by Lyes Saidi and defended in January 2024.
If you want to read the thesis directly, the pre-compiled PDF is available [Here](https://saidilyes.github.io/#experience)." thesis, written by Lyes Saidi and defended in January 2024.
If you want to read the thesis directly, the pre-compiled PDF is available [Here](https://saidilyes.github.io/#experience).

## Abstract 
The widespread use of Intelligent Transportation Systems (ITS) primarily stems from the
imperative to mitigate human errors contributing to accidents. However, addressing the
“individual” Automated Vehicles (AVs) alone remains insufficient, given that a number
of situations require the “coordination” of the relative movements of AVs.
Within the Multi-Vehicle System (MVS) paradigm, AVs derive advantages from connectivity
and road preview information. Consequently, they can sense more accurately,
process more information, and can be more tightly controlled. The collaborative assessment
of safety within MVS allows for the establishment of advanced collision-avoidance
strategies, particularly in challenging scenarios such as intersection crossings and onramp
mergings. Moreover, MVS technology facilitates the reduction of gaps between
vehicles, enhancing road capacity and traffic flow. The MVS’s shorter response time
enables improved control of AV dynamics, paving the way for promising energy-centric
strategies.
The main aim of the research done in this Ph.D. manuscript is to propose a safe and
energy efficient decision/control architecture for MVS that navigates in dynamic and complex
environment such as on-ramp merging and multi-road navigation in highway. Based
on the multi-controller foundational control architecture a Cooperative Multi-Controller
Architecture (C-MCA) is proposed.
The first part of the proposed C-MCA deals with the decision-making level. This level
involves a multi-behavior decision-making strategy, responsible for activating the MVS’
suitable behavior based on the safety metric. Two distinct behaviors are proposed: (a)
The nominal behavior, designed for executing the merging scenario while adhering to the
individual goals of the MVS vehicles. It is activated when no collision risk is detected,
(b) The cooperative behavior, activated by the decision-making level when both of the
safety and the energy efficiency requirement are not satisfied by the nominal behavior.
Its objective is to solve the merging conflict by generating a safe and energy efficient
passing order of the MVS vehicles in the merging zone.
The second part of the proposed C-MCA focuses on the local trajectory planning level.
Each behavior is assigned a dedicated controller tailored to meet its specific requirements.
For instance, the cooperative behavior controller has the responsibility of translating the
vehicle’s passing order into feasible dynamics (i.e., trajectory, velocity, etc.). The translation
task is facilitated through the proposed dynamic formation reconfiguration strategy.
In essence, the approach leverages the multi-vehicle system’s formation navigation capabilities
to conceptualize the merging challenge as a formation reconfiguration problem. A
formalization of the formation reconfiguration problem is presented, employing a flexible
and generic formal approach. The proposed dynamic formation reconfiguration strategy,
employs virtual dynamic targets to ensure a secure reshaping of the formation toward
the desired configuration based on the selected passing order. The overall architecture’s
performance is assessed through co-simulation using Matlab/Simulink and SCANeR studio.
#### Keywords: Highway cooperative navigation, Multi-vehicle system, Multi-controller architecture, Multi-behavior decision-making strategy, Dynamic formation reconfiguration strategy.
