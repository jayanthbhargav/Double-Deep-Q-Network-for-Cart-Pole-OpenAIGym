# Double-Deep-Q-Network-for-Cart-Pole-OpenAIGym

The following are the parts of the code:

o class q Network(nn.Module): implements functions for: computing epsilon greedy action
and forward pass of neural network (which approximates the q function)

o class experienceReplayBuffer: implements functions for sampling a batch of experiences
from memory and handling the buffer memory

o class DDQN: implements functions for applying action, training the agent by computing loss
and updating the network parameters
