### @explicitHints true

```template
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
```

# Turtle Logo - Moving and Turning

## Introduction @unplugged

In this tutorial you will create your first Turtle Logo program using Makecode Arcade. You will get a turtle showing up in your game console and have it say, "Hello, World!".

![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-hello_world/raw/main/assets/hello_world_screenshot.png)

## Step 1
Once you can make the **Turtle** show up and talk, the next step is to make it move.

## Step 2
Into the provided code below, drag out the ⇢``myTurtle move forward 25 steps``⇠ block and then see what happens to your **Turtle**.
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 25)
```

## Step 3
Hopefully you noticed the **Turtle** moved forwards and it left a trail behind when it moved.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_forward_screenshot.png)

## Step 4
You can change the **25** to different numbers to make it move more or less. You can also select the **forward** tab and change the direction to **backwards** to make it move in the opposite direction.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_backwards_screenshot.png)

## Step 5
Try moving the **Turtle** backwards 50 steps.
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Backward, 50)
```

## Step 6
Besides forwards and backwards, the **Turtle** can also turn. You use the ⇢``myTurtle turn right by 90°``⇠ block to turn the **Turtle**. Try making the **Turtle**:
- move forward 30 steps
- turn right 90°
- move forward 30 more steps
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 30)
myTurtle.turnDirectionByDegrees(TurtleTurnDirection.Right, 90)
myTurtle.moveDirection(TurtleDirection.Forward, 30)
```

## Step 7
Hopefully you noticed the **Turtle** moved like the image below.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_and_turn_screenshot.png)

## Step 8
Done.

You now know how to make the **Turtle** move and turn.
