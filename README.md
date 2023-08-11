# Blackjack Simulators

The Blackjack Simulators project provides a collection of Python scripts that allow users to simulate and analyze various aspects of the classic card game, Blackjack. These simulators offer different perspectives on Blackjack gameplay, enabling users to explore different strategies, scenarios, and outcomes through simulation.

## Table of Contents

    1. Overview

    2. Simulators

    3. Getting Started

    4. Usage

    5. Result
    
    6. Target Audience

    7. Contributors

## Overview

Blackjack Simulators is a project designed for Blackjack enthusiasts, beginners, and anyone interested in exploring different Blackjack scenarios without the risk of real money. The project consists of three distinct simulators, each focusing on a specific aspect of the game:

#### Blackjack Simulator with Splitting:
This simulator explores the intricacies of splitting hands. It allows users to observe the effects of splitting specific pairs of cards on their chances of winning, losing, or tying against the dealer. The simulator employs basic strategy and considers the conversion of Aces to optimize hand values.

#### Inexperienced Blackjack Simulator: 
Geared towards newcomers to the game, this simulator simplifies player actions to random choices between hitting and staying. It provides insights into win, loss, and push probabilities using basic gameplay decisions.

#### Simplified Blackjack Simulator (No Splitting):
This simulator offers a straightforward experience without splitting. It models player decisions as hit or stay and allows users to explore the impact of different hand values on game outcomes.
## Simulators

Each simulator is implemented as a separate Python script:

### blackjack_simulator_with_splitting.py: 

This simulator provides a more comprehensive and strategic blackjack experience. It includes features like splitting pairs and follows a basic blackjack strategy for player decisions. Here's an overview:

#### Deck and Cards:
The deck comprises standard playing cards, ranging from 2 to 10, along with special cards represented as strings: 'J' (Jack), 'Q' (Queen), 'K' (King), and 'A' (Ace).
 
Suits are not considered.

Each card value (2 to 10) appears four times, and the value of 10 appears four times (to represent  J, Q, K, A).

#### Player Decisions:
The player's decisions are guided by a basic blackjack strategy.

The player can split pairs of 2s, 3s, 7s, or 8s.
The player's decisions are influenced by their hand value and the dealer's upcard.

The player can hit, stand, or split based on these factors.

#### Dealer's Decisions:
The dealer follows standard blackjack rules: hits if the hand value is less than 17 and stands otherwise.

The dealer's decisions are automated.

#### Outcome Analysis:

The simulator performs multiple simulations and calculates the percentage of wins, losses, and ties based on the defined strategy and decisions.

It displays the results in the form of a bar chart, showing the distribution of outcomes.

### inexperienced_blackjack_simulator.py: 
This simulator simulates gameplay by an inexperienced player who makes decisions entirely at random:

#### Deck and Cards:
Same as the original simulator.

#### Player Decisions:
The player's decisions are random and do not follow any specific strategy.

The player can hit or stand randomly.

#### Dealer's Decisions:

The dealer's decisions follow the same rules as the original simulator.

#### Outcome Analysis:

Similar to the original simulator, this version analyzes the outcomes of random decisions and displays the distribution of wins, losses, and push in a bar chart.

### simplified_blackjack_simulator.py: 

This simulator offers a simpler version of blackjack, where splitting pairs is not considered:

#### Deck and Cards:
Same as the original simulator.

#### Player Decisions:
The player's decisions are again made randomly between hitting and standing.

The simulator uses a basic blackjack strategy to decide when the player should hit or stand based on their hand value.

#### Dealer's Decisions:
The dealer's decisions are consistent with the original simulator.

#### Outcome Analysis:
Like the other simulators, this version provides insight into the outcomes of games played with the simplified strategy and displays the results in a bar chart.

## Getting Started

To run the Blackjack simulators on your local machine, follow these steps:

    1. Ensure you have Python 3.x installed on your system.

    2. Clone this repository or download the individual simulator scripts.

    3. Open a terminal or command prompt and navigate to the directory containing the simulator script you want to run.## Usage

1. Run the desired simulator script using the following command:
```bash
  python blackjack_simulator_with_splitting.py
```
2. Replace blackjack_simulator_with_splitting.py with the name of the simulator script you want to run.

3. Follow the on-screen instructions to input the number of simulations you want to perform.

4. The simulator will execute the specified number of simulations and display the results, including win, loss, and push percentages. A bar chart visualization of the results will also be shown.

5. Experiment with different numbers of simulations and explore the outcomes based on the chosen simulator.
## Result

After running each simulator, we will obtain valuable insights into the outcomes of different blackjack scenarios. The result outputs will help to analyze the effectiveness of different strategies, explore potential outcomes, and gain insights into the probabilities associated with various decisions in the game.

#### Blackjack Simulator with Splitting:

Percentage of Wins: The portion of simulations where the player wins against the dealer.

Percentage of Losses: The portion of simulations where the player loses to the dealer.

Percentage of Ties: The portion of simulations where the player's hand ties with the dealer's hand.

    Results after 10000 simulations:
    Win: 42.059999999999995%
    Loss: 51.53%
    Tie: 6.41%

#### Inexperienced Blackjack Simulator:
Percentage of Wins: The percentage of simulations where the inexperienced player wins.

Percentage of Losses: The percentage of simulations where the inexperienced player loses.

Percentage of Pushes: The percentage of simulations where the game results in a push (tie between player and dealer).


    Total games played: 10000
    Win percentage: 28.71%
    Loss percentage: 66.99%
    Push percentage: 4.30%

#### Simplified Blackjack Simulator (No Splitting):
Percentage of Wins: The percentage of simulations where the player wins using the simplified strategy.

Percentage of Losses: The percentage of simulations where the player loses.
Percentage of Pushes: The percentage of simulations resulting in a push.

    Total games played: 10000
    Win percentage: 40.13%
    Loss percentage: 49.95%
    Push percentage: 9.92%









## Target Audience

It is particularly useful for those who wish to:

#### Learn Blackjack Strategies:
The project offers insights into different strategies players can employ, including basic strategies, splitting strategies, and simplified approaches.

#### Evaluate Outcomes: 
Users can run simulations to assess the potential outcomes of various strategies, gaining a better understanding of the probabilities associated with different decisions in the game.

#### Experiment with Modifications: 
The open-source nature of the project allows users to modify the scripts, test new strategies, and observe how these changes impact game results.

#### Visualize Results: 
Through the inclusion of pie charts, users can visually analyze the distribution of outcomes, making it easier to interpret the simulation results.

Overall, the "Blackjack Simulators" project is a valuable tool for both newcomers to Blackjack and experienced players looking to explore different gameplay scenarios and refine their understanding of the game's dynamics. It serves as an educational resource and a platform for experimentation and analysis in the realm of Blackjack strategies.


## Contributors

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.