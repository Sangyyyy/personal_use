# SIMULATE SINGLE DECK BLACKJACK

The Blackjack Simulation project offers a collection of Python scripts designed to allow users to simulate and analyze various aspects of the classic card game, Blackjack. These simulations provide different perspectives on Blackjack gameplay, enabling users to explore different strategies, scenarios, and outcomes through simulation.

<img width="400" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/0a79a3b5-1eee-4672-9388-d4e00e89e81a">

## Overview

This project aims to simulate different strategies of Blackjack and compare the results.

#### Blackjack Simulation (Splitting pairs):

This explores the intricacies of splitting hands. It allows users to observe the effects of splitting specific pairs of cards on their chances of winning, losing, or tying against the dealer. Here we employ basic strategy and considers the conversion of Aces to optimize hand values.

#### Inexperienced Blackjack Simulation: 

Geared towards newcomers to the game, this one simplifies player actions to random choices between hitting and staying. It provides insights into win, loss, and push probabilities using basic gameplay decisions.

#### Simplified Blackjack Simulation (No Splitting):

This offers a straightforward experience without splitting. It models player decisions as hit or stay and allows users to explore the impact of different hand values on game outcomes.

## Strategies

<img width="500" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/608bbeb6-b17d-491c-9e31-20f60e6e3f4d">

## Flowchart 

<img width="500" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/da9cef8a-3459-4185-b26d-be8beede8aac">

## Getting Started

To run the Blackjack simulation codes on your local machine, follow these steps:

    1. Ensure you have Python 3.x installed on your system.

    2. Clone this repository or download the individual simulator scripts.

    3. Open a terminal or command prompt and navigate to the directory containing the simulator script you want to run.
    
## Usage

1. Run the desired simulator script using the following command:
```bash
  python blackjack_with_splitting.py
```
2. Replace blackjack_with_splitting.py with the name of the simulation script you want to run.

3. Follow the on-screen instructions to input the number of simulations you want to perform.

4. The simulator will execute the specified number of simulations and display the results, including win, loss, and push percentages. A bar chart visualization of the results will also be shown.

5. Experiment with different numbers of simulations and explore the outcomes based on the chosen simulator.

6. For the combined plot comparing all strategies with 100,000 simulations:
```bash
  python Blackjack_combined_plot_100000_sims.py
```
## Result

After running simulations for different blackjack strategies, we gain valuable insights into diverse blackjack scenarios. These results allow us to analyze the effectiveness of various strategies, explore potential outcomes, and better understand the probabilities associated with different decisions in the game.

Percentage of Wins: The portion of simulations where the player wins against the dealer.

Percentage of Losses: The portion of simulations where the player loses to the dealer.

Percentage of Ties/Pushes: The portion of simulations where the player's hand ties with the dealer's hand.

These results are visualized using bar charts, showcasing the distribution of different outcomes - Wins, Losses, and Pushes - over the course of the simulations.

The project culminates in a combined plot, comparing the strategies' simulation results. It showcases the distribution of wins, losses, and ties across 100,000 simulations, shedding light on the strategies' relative effectiveness.

#### Blackjack_with_splitting.py

<img width="350" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/ee5265d4-9c8b-4ed0-a051-fae1d4e4b2d4">

#### Blackjack_Inexperienced_player.py

<img width="350" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/836c1436-583f-4ab0-bd8c-e2d6cd74ae68">

#### Blackjack_simple_logic.py

<img width="350" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/3fb31ea8-240d-4fe3-93a7-c88c3b910f45">

#### Blackjack_combined_plot_100000_sims.py

<img width="350" alt="image" src="https://github.com/Sangyyyy/personal_use/assets/134233430/3c994a1f-67b9-44a8-b1b5-52236beba6c3">

## Target Audience

1. Individuals interested in learning Blackjack strategies.
2. Players who want to evaluate potential outcomes using simulations.
3. Enthusiasts who wish to experiment with and modify strategies.
4. Users seeking visual insights into Blackjack strategy outcomes.

## Contributors

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
