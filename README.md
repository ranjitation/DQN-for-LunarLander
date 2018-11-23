# Deep-Q-Network

This repo contains the files for the Deep Q-Network used to solve the OpenAI Gym Environment called 'LunarLander-v2'.

# Description of the Environment

This environment involves a space ship that needs to land on a landing pad. The coordinates of the Landing Pad are at (0,0)
These coordinates are the first two numbers in the state vector.

Rewards for moving from top of the screen to the landing pad and at zero speed is about 100-140 points.

If the lander moves away from the landing pad it loses reward.

The episode finishes if the lander crashes or comes to rest, receiving an additional -100 or +100 points respectively. Each leg's ground contact nets +10 points. Firing the main engine costs 0.3 points on each frame.

The environment is considered solved once we achieve 200 points.

Landing outside the landing pad is possible. Fuel supply is infinite, so an agent can learn to fly and then land on its final attempt.

The action space: 4 discrete actions (do nothing, fire left orientation engine, fire main engine, fire right orientation engine)
