# RoboMaze 2: An Online Tool for Swarm Robotics and Coordinated Navigation

Demo can be viewed at [Robomaze.org](https://robomaze.org/sandbox)

## API

### Sensing
canGoForward() -> Boolean

canGoRight() -> Boolean

canGoBackward() -> Boolean

canGoLeft() -> Boolean

### Moving
goForward()

turnRight()

goBackward()

turnLeft()

### Info
cellX() -> Number

cellY() -> Number

mazeHeight -> Number

mazeWidth -> Number

id -> Number

steps -> Number

### Communication
sendMessage(msg)

hasMessages() -> Boolean

recieveMessage() -> any

## Examples
