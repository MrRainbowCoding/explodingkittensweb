# Exploding Kittens Web Edition

## How to Play

The game starts with Player 1 against the AI. Each player begins with a hand of cards and a Defuse card.

### Taking a Turn

1. Play any number of playable action cards from your hand, or skip playing cards.
2. Draw a card to end your turn.
3. Follow the card's effect immediately if it is an Exploding Kitten.

Click a card in your hand to play it. Click the draw pile or use **Draw Card & End Turn** to draw.

### Card Effects

- **Attack:** End your turn without drawing. The next player must take two turns.
- **Skip:** End the current turn without drawing.
- **Shuffle:** Randomize the draw pile.
- **See the Future:** Reveal the top three cards of the draw pile.
- **Favor:** Make the opponent give you a card.
- **Nope:** Cancel an opponent's action when the Nope window is available.
- **Cat cards:** Play two matching cats to steal a random card, or three matching cats to request a named card.

### Exploding Kittens

If you draw an Exploding Kitten and have a Defuse, the Defuse is used automatically. Choose whether to put the Kitten on top, at the bottom, or at a random position in the draw pile.

If you have no Defuse, you explode and the other player wins. The game also ends when the draw pile is empty.

### Game Builds

- **index.html:** Main game. Supports AI and Local 2P modes.
- **testing.html:** AI testing build with controls for adding cards to Player 1's hand and simulating an Exploding Kitten draw.
- **index-gsites.html:** Main game build using card images hosted from GitHub for Google Sites.
