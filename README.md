# Snake-Water-Gun Game

This is a simple **Snake-Water-Gun Game** written in **C**. The player chooses one option (Snake, Water, or Gun), and the computer randomly picks one as well. The winner is determined based on the following rules:

- Snake drinks Water → Snake Wins
- Gun kills Snake → Gun Wins
- Water douses Gun → Water Wins
- Same choices → Draw

## How to Run

1. Make sure you have a C compiler installed (e.g., GCC).
2. Compile the program:
   ```bash
   gcc main.c -o game
