# Pygame-Based Blackjack Game

## Overview

This Python script is a graphical implementation of the classic card game, Blackjack, using the Pygame library. Enjoy the thrill of Blackjack with a visual interface. While the current code doesn't include a betting process, it offers the core gameplay elements of Blackjack, including card dealing, player decisions, and determining the round outcomes.

## Features

- Play Blackjack in a graphical user interface powered by Pygame.
- Experience the excitement of the popular card game with visually appealing card graphics.
- Interact with the game through simple button controls for hitting and standing.

## Getting Started

To play the Pygame-based Blackjack game, follow these steps:

# 1. Clone this repository to your local machine:

```shell
git clone https://github.com/yourusername/pygame-blackjack.git
```
# 2. Install the required dependencies. Ensure that you have Python 3.x and Pygame installed on your system. If not, you can download Python from the official Python website (https://www.python.org/downloads/) and install Pygame using pip:

```shell
pip install -r requirements.txt
```
# 3. Run the game:

```shell
python blackjack.py
```
# 4. Enjoy the game!

## How to Play

1. **Launch the Game**: Start the game to begin playing.

2. **Initial Deal**: At the beginning of each round, both you and the dealer will receive two cards. One of the dealer's cards remains face-down.

3. **Objective**: Your goal is to achieve a hand value as close to 21 as possible without exceeding it. Card values are as follows:
   - Numbered cards are worth their face value.
   - Face cards (Kings, Queens, and Jacks) are worth 10.
   - Aces can be worth either 1 or 11, depending on which value benefits your hand.

4. **Player's Turn**: You can make choices during your turn:
   - Click the "Hit" button to receive another card (if your hand total is below 21).
   - Click the "Stand" button to keep your current hand.

5. **Busting**: If your hand total exceeds 21 points, you "bust" and lose the round.

6. **Dealer's Turn**: If you haven't busted, the dealer reveals their face-down card and plays according to standard Blackjack rules. The dealer typically hits until they have a hand value of 17 or higher.

7. **Determining the Winner**: The player with the hand value closest to 21 (without busting) wins the round.

8. **Continuing Rounds**: You can continue playing rounds until you decide to quit. Aim to accumulate the highest score possible.

Now you're ready to enjoy the game of Blackjack! Good luck!

