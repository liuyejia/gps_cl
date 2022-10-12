# Navigating Memory Construction by Global Pseudo-Task Simulation for Continual Learning

[[Paper](https://openreview.net/forum?id=tVbJdvMxK2-)] [[Project Page](https://liuyejia.github.io/publication/nuerips/)] [[GitHub](https://github.com/liuyejia/gps_cl)]

This is the official implementation of **Navigating Memory Construction by Global Pseudo-Task Simulation for Continual Learning**, 
a novel experience replay method in continual learning. 

Continual learning faces a crucial challenge of catastrophic forgetting. To address 
this challenge, experience replay (ER) that maintains a tiny subset of samples
from previous tasks has been commonly used. Existing ER works usually focus
on refining the learning objective for each task with a static memory construction
policy. In this paper, we formulate the dynamic memory construction in ER as a
combinatorial optimization problem, which aims at directly minimizing the global
loss across all experienced tasks. We first apply three tactics to solve the problem
in the offline setting as a starting point. To provide an approximate solution
to this problem in the online continual learning setting, we further propose the
Global Pseudo-task Simulation (GPS), which mimics future catastrophic forgetting
of the current task by permutation. Our empirical results and analyses suggest
that the GPS consistently improves accuracy across four commonly used vision
benchmarks. We have also shown that our GPS can serve as the unified framework
for integrating various memory construction policies in existing ER works.

