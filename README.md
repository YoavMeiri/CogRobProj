﻿# CogRobProj
We consider the problem of spatial path planning, in an environment containing
moving obstacles. In contrast to the classical solutions, in this work we learn a planner
from the data (in a supervised learning manner) that allows us to leverage statistical
regularities from past data. For that purpose we will use a state of the art machine
learning model. In the setting where the ground truth map (real distance from the
goal from each tile) is not known to the agent, we leverage pre-trained deep learning
models (which in our case will contain convolutional neural networks) in an end-to-end
framework that has the structure of mapper and planner built into it which allows
seamless generalization to new maps and goals.
