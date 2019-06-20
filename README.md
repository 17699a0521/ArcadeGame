# Classic Arcade Game Clone Project
This Arcade game is awesome while playing this game i am so excited. I learned a lot of JavaScript object oriented concepts while developing this project.

## Table of Contents

- [Instructions](#instructions)
- [Contributing](#contributing)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking your submission.

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

Your **README.md** file should be updated with instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.
-----------------------------------------
## I had  following the below steps in order to develop this game.
+   Downloaded the skeleton project from GitHub link https://github.com/udacity/frontend-nanodegree-arcade-game which is given by Udacity in rubric structure.
+  Open index.html file in browser and I get a plain page with error in console.
+  I initialized a player class and Assigned to a variable.
+  I initialized bugs as `allEnemies[]` like array through their `bug positions`.
+   For enemy, I gave the dimensions in x and y directions. To move the enemies, I gave the speed to them.
+   In player class , I gave x and y dimensions and I kept one image and named as sprite.
+   for player I initialized `render()`, `update()`, `handleInput()` functions, as render used for  placing cards update for updating positions.
+   `handleInput()` is used for initializing arrow keys functioning ,__left arrow_ _right arrow_ _up arrow_ _ down arrow__ as they are used for movements of the player.
+   when the actor reaches to the top then again he must go to the initial position with adding some score.
+   I declared score as `score`  for counting the score of the game. Initially I declared both `score` to zero.
+   And I used bugs as enemies using array and gave some speed and positions, and if actor touches then bugs to show a `sweetalert` and again comes to the initial position.
+  I increased score value by 1 when player reaches the top water level and when the score is 3 game will end with a sweet alert.

+ When clicked on restart button game will start from beginning.
