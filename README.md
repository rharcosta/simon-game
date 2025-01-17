# simon-game


Go to the Game: https://rharcosta.github.io/simon-game/

The Simon game is a classic memory game where the player has to mimic a sequence of lights and sounds. 
## Here's how the game works:

**1. Game Board:** 
* Typically, the Simon game has four colored buttons (e.g., red, green, blue, yellow).
* Each button is associated with a unique sound and light.

**2. Sequence Generation:**
* The game starts by lighting up one random button (with its sound).
* The player must click the same button to replicate the sequence.
* If the player is correct, the game adds another random button to the sequence, and the process repeats.

**3. Player's Turn:**
* The player must repeat the entire sequence in the correct order.
* As the sequence grows longer, it becomes harder to remember and repeat.

**4. Failure:**
* If the player presses the wrong button, the game ends (or resets) and may play a failure sound.
* The goal is to see how long the player can continue replicating sequences correctly.

## This implementation was developed in JavaScript, HTML, CSS and jQuery.

**HTML:**
* A layout with four buttons representing the colors.
* A display for messages like "Level 1" or "Game Over."

**CSS:**
* Styled buttons for colors with animations.
* Layout positioning to make it look neat and visually appealing.

**JavaScript and jQuery:**
* Randomly generate the sequence.
* Play the corresponding sound for each button when it lights up.
* Handle user input to check if the sequence is correct.
* Increment levels and add difficulty.

<img src="https://github.com/rharcosta/simon-game/blob/main/simon-game.png" />
