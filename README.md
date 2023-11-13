# Space-Invaders-2.O

Demo :- https://relaxed-cheesecake-48a604.netlify.app/

The game is fully developed by using JavaScript.Some basic explanation about the game:-

1. class Player :- handle movements and animations of the main player character - 'The robotic spaceship'. player-game.png and player_jets-game.png are the image used for it.
 
2. class Game :- contain the main logic of the code base, this is the main brain that send commands everywhere and it holds all of this together.
 
3. class Enemy :- draw and animate enemies and organize them into grids and how to make them come in larger and larger waves as the game goes. There are 3 types of enemies in this game : class Beetlemorph, class Rhinomorph and class Boss.

4. class Projectile :- handle lasers that the player will be shooting. Projectile object hits an enemy object then enemy object will be deleted.

5. class Laser :- Two types of lasers :-
  
5.a. class SmallLaser :- Press '2' for it , it hits enemies for 0.3 lives per animation frame and we are running this at 60 frames per second or even faster. We slow down the rate of damage by put them in the condition of spriteUpdate is true.

5.b. class BigLaser :- Press'3' for it , it hits enemies for 0.7 lives.

6. Press '1' for the normal hits.

