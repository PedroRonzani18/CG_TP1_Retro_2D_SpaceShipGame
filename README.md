# Retro2DAirplaneGame
- This game was developed as a Project for a Computer Graphics class

- External Libreries used: freeglut, SOIL.
 
- Operating system used: Linux (Ubuntu).

- Main language: C++

- Compile and run Project: make run

- Controls in Menu:
    W: up;
    S: down;
    SPACE: selects Level or Help ("Ajuda").
   
- Controls in Ajuda:
    SPACE: goes back to menu;
    
- Controls in Level:
    W: moves player up;
    A: moves player left;
    S: moves player down;
    D: moves player right;
    SPACE: shoots projectiles.
    
- Closing game at any given moment: ESC.

- Relevant Observations:
   1) When an enemy dies, there is a probability, set as the enemy's atribute, of him releasing an item that upgrades the player's weapon.

   2) Possible upgrades:
   
       a) damage increase;
       
       b) increases firerate;
       
       c) increases HP (MAX: 4);
       
       d) increases number of shots realesed in a cicle (1, 2, 3);
       
       e) changes the projectile's model (default, colides with walls, follows an enemy).

   3) The game ends when the player kills the boss, or when he dies (loses all 4 lives).

   4) There may or may not be something waiting for you after the credits.

- Thanks for your atention, and good luck!
