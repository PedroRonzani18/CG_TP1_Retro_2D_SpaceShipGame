# Strike-Gunner-CTC

## Initial information

- This game was developed as a Project for a Computer Graphics class
- Operating system used: Linux (Ubuntu).
- Main language: C++

## Necessary libs

- Freeglut: `sudo apt-get install freeglut3-dev`
- SOIL: `sudo apt-get install libsoil-dev`

## How to compile and execute

- Compile: `make all`
- Run separately: after compiling, use `./main`
- Compile and run: `make run`
- Clear: `make clear`

## Keyboard Controls

### Controls in Menu
- **W**: up
- **S**: down
- **SPACE**: enters selected 
- **ESC**: Closes the game
   
### Controls in Ajuda
- SPACE: goes back to menu
- ESC: Closes the game

### Controls in Level:
- W: moves player up;  
- A: moves player left;  
- S: moves player down;
- D: moves player right;  
- SPACE: shoots projectiles.
- ESC: Closes the game

## Relevant Observations:
1. When an enemy dies, there is a probability, set as the enemy's atribute, of him releasing an item that upgrades the player's weapon
2. Possible upgrades
   1. damage increase
   2. increases firerate
   3. increases HP (MAX: 4)
   4. increases number of shots realesed in a cicle (1, 2, 3)
   5. changes the projectile's model (default, colides with walls, follows an enemy)
3. The game ends when the player kills the boss, or when he dies (loses all 4 lives)
4. There may or may not be something waiting for you after the credits
5. Link to [previous versions](https://github.com/PedroRonzani18/Arquivos_Programas/tree/master/Computa%C3%A7%C3%A3o%20Gr%C3%A1fica/Avaliacoes/TP1) of this project

## Thank you for your atention, and good game!
