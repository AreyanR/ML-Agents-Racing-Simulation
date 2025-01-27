# ML-Agents Racing Simulation

## Description
This project is a machine learning simulation built in Unity, showcasing the behavior of AI agents in a competitive racing environment. Using Unity's ML-Agents toolkit, two agents are trained with reinforcement learning algorithms to optimize their performance and achieve their objectives. The simulation emphasizes the adaptability and learning capabilities of AI models in a dynamic environment.

## Key Features

### Reinforcement Learning
Agents refine their behaviors through rewards and penalties, adapting to changing conditions over time.

### Agent Behaviors
- **Goal-Oriented Actions**:  
  Agents compete to reach the finish line, optimizing paths and minimizing penalties as they train.
- **Behavioral Progression**:  
  Agents learn progressively:
  1. **Balance**: Maintain stability while standing.
  2. **Walk**: Move forward steadily with improved stability.
  3. **Run**: Reach maximum speed while maintaining control and balance.
- **Behavioral Diversity**:  
  The competitive dynamic between the agents accelerates learning and enhances their adaptability, encouraging the development of diverse strategies.

## About the Project
The goal was to demonstrate how AI agents can adapt and learn within a controlled, competitive environment. By introducing a second agent, the project created a competitive dynamic that significantly enhanced the training process, enabling faster learning and more diverse strategies. 

This project highlights my skills in Unity development, machine learning, and behavior modeling. While not a game, it serves as a technical demonstration of AI-driven behavior in a foot race scenario. Unity was selected for its powerful tools  and visualization capabilities.

## Learning Process and Parameters

### Rewards and Penalties
- Agents are rewarded for completing the race efficiently.
- Penalties discourage unwanted actions such as falling or losing the race.

### Reinforcement Learning Parameters

#### Agent 1 (Blue)
- **Objective**:  
  Reach the finish line faster than the other agent.
- **Rewards**:
  - Staying balanced.
  - Reaching the finish line first.
  - Successfully completing the race.
- **Penalties**:
  - Falling.
  - Losing the race.

#### Agent 2 (Red)
- **Objective**:  
  Reach the finish line faster than the other agent.
- **Rewards**:
  - Staying balanced.
  - Reaching the finish line first.
  - Successfully completing the race.
- **Penalties**:
  - Falling.
  - Losing the race.

## Discoveries During Simulation
- **Behavior Optimization**:  
  Agents learned to navigate more efficiently with each training iteration, adapting to the environment and refining their strategies.
- **Team Training Advantage**:  
  Initially, the project had only one agent, which took about 7 hours to learn how to walk and reach the goal line. However, adding a second agent introduced competition, significantly accelerating the training process and reducing the time to around 3 hours. This competitive dynamic encouraged faster learning and the development of more diverse strategies.
  

## Media
[Trained Agents Demo](https://drive.google.com/file/d/1fzPdLlhJZcMVbY1OmpAedB2_hmkmz6jU/view?usp=sharing)  

## Tools and Technologies
- **Unity**: Game engine for developing the simulation environment.
- **Unity ML-Agents Toolkit**: Framework for training and simulating AI agents.
- **C#**: Programming language for implementing agent behaviors and environment logic.
- **Visual Studio Code**: Primary IDE for scripting and debugging.
