# CodeCrawler2

Important: To get the key (green cube) press E.

The goal of the game is to get the key ( green cube) to the exit (green zero) while avoiding all true statements (1). Everytime you jump or fall, the code currently highlighted will be triggered, meaning you need to read the code carefully before jumping to avoid all ones and get to your goal. 

Collider and overlap event: 
 1. Player + Top of ones: On all of the ones, there's a collider box and if you collide with it, the "You Lost!" Scene appears.
 2. Key + Green Zero: On the green zero, there's a trigger box that if the key collides with it, the "You Win!" Scene appears.
 3. Player + Ladder: When the player collides with the ladder, he can go up and down only.

Sphere trace: When the player press E and the key is in it's sphere, it grabs the key. Press E again to ungrab.

Physics: The green cube has physics. 
