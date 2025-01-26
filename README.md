# Snake-Water-Gun Game

This is a simple **Snake-Water-Gun Game** implemented in **C**. The player competes against the computer by selecting one of the three options: Snake, Water, or Gun. The computer randomly selects its choice, and the winner is determined based on the game's rules.

---

## Game Rules

- **Snake vs Water** → Snake Wins
- **Water vs Gun** → Water Wins
- **Gun vs Snake** → Gun Wins
- **Same choices** → It's a Draw!

---

## Features

- Random choice generation for the computer.
- User-friendly input for the player.
- Clear and concise result display.
- Error handling for invalid inputs.

---

## How to Play

1. **Compile the Program**:
   ```bash
   gcc main.c -o snake_water_gun_game
## Example Gameplay
Choose 0 for Snake, 1 for Water, and 2 for Gun: 1
Computer chose 0
You win!

Choose 0 for Snake, 1 for Water, and 2 for Gun: 2
Computer chose 2
It's a Draw!

Choose 0 for Snake, 1 for Water, and 2 for Gun: 0
Computer chose 2
You lose!
