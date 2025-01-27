# ML-Agents Racing Simulation

## Description
This project is a machine learning simulation built in Unity, showcasing the behavior of AI agents in a competitive racing environment. Using Unity's ML-Agents toolkit, two agents are trained with reinforcement learning algorithms to optimize their performance and achieve their objectives. The simulation emphasizes the adaptability and learning capabilities of AI models in a dynamic environment.

## Key Features

### Reinforcement Learning
- **Adaptive Learning**:  
  Agents refine their strategies through iterative training, receiving rewards for desired actions and penalties for errors.
- **Dynamic Adaptation**:  
  Agents adjust their behaviors based on evolving conditions and environmental changes.

### Agent Behaviors
- **Goal-Oriented Actions**:  
  Agents compete to reach the finish line, optimizing paths and minimizing penalties as they train.
- **Behavioral Progression**:  
  Agents learn progressively:
  1. **Balance**: Maintaining stability while moving.
  2. **Walk**: Efficient forward movement.
  3. **Run**: Reaching maximum speed toward the goal.
- **Behavioral Diversity**:  
  The competitive dynamic between the agents encourages diverse strategies and interactions, enhancing their adaptability.

## About the Project
This project explores the potential of reinforcement learning in Unity, using the **Unity ML-Agents Toolkit** to create a dynamic simulation. The goal was to demonstrate how AI agents can adapt and learn within a controlled, competitive environment. By introducing a second agent, the project created a competitive dynamic that significantly enhanced the training process, enabling faster learning and more diverse strategies.

This project highlights my skills in Unity development, machine learning, and behavior modeling. While not a game, it serves as a technical demonstration of AI-driven behavior in a racing scenario. Unity and C# were chosen for their robust toolsets and seamless visualization capabilities, making them ideal for developing and showcasing machine learning concepts.

## Learning Process and Parameters

### Rewards and Penalties
- **Efficiency and Accuracy**:  
  Agents are rewarded for completing the race efficiently.
- **Error Handling**:  
  Penalties discourage unwanted actions such as falling or losing the race.

### Reinforcement Learning Parameters

#### Agent 1 (Runner 1)
- **Objective**:  
  Reach the finish line faster than the other agent.
- **Rewards**:
  - Staying balanced.
  - Successfully completing the race.
- **Penalties**:
  - Falling or losing the race.

#### Agent 2 (Runner 2)
- **Objective**:  
  Compete with Runner 1 to reach the finish line.
- **Rewards**:
  - Staying balanced.
  - Reaching the finish line first.
  - Successfully completing the race.
- **Penalties**:
  - Falling or failing to complete the race.

## Discoveries During Simulation
- **Behavior Optimization**:  
  Agents learned to navigate more efficiently with each training iteration, adapting to the environment and refining their strategies.
- **Team Training Advantage**:  
  Initially, the project only had one agent. Adding a second agent introduced competition, which accelerated the training process by encouraging both agents to learn faster and adopt diverse strategies.

## Media
[Watch the Video Demo](https://drive.google.com/file/d/1IS2D83aCRbxlteJGPERPACedNlcXyw2W/view?usp=sharing)  
*See the agents balance, walk, and compete in real-time as they race toward the finish line.*

## Tools and Technologies
- **Unity**: Game engine for developing the simulation environment.
- **Unity ML-Agents Toolkit**: Framework for training and simulating AI agents.
- **C#**: Programming language for implementing agent behaviors and environment logic.
- **Visual Studio Code**: Primary IDE for scripting and debugging.
