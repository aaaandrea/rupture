# Rupture Proposal
Rupture is based on the classic game "Breakout."

## MVPs
  * Start, pause, and reset the game
  * Move left and right with respective keys
  * Win and lose
  * View score
  * Toggle sound on/off

## Design Docs
  * [View Wireframes](https://github.com/adelrio1/rupture/tree/master/docs/Wireframes)

## Implementation Timeline
### Day 1
  * Create title/boxes that will contain the screen
  * Render an object on the canvas

### Day 2
  * Create player and render it on the screen
  * Create the player controls
  * Toggle sound on/off

### Day 3
  * Add logic to render boxes on the board
  * Add collision detection between ball and blocks
  * Create won/lost condition on the board
  * Create score logic and render

### Day 4
  * Add icons for player
  * Add icons for boxes
  * Create controls for game start/pause/reset

## Bonus
  * Ball speed power-up
  * Paddle length power up
  * Multiple levels

## Math
  * Distance between 2 points

    ```
      Dist([x_1, y_1], [x_2, y_2]) = sqrt((x_1 - x_2) ** 2 + (y_1 - y_2) ** 2)
    ```

  * Magnitude
    ```
      Norm([x_1, y_1]) = Dist([0,0], [x_1. y_1])
    ```
