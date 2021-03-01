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

# Turtle Logo - Pen and Colour

## Step 1
Sometimes when you move the **Turtle** you might not want to leave a trail. Like this:
![pen up and down](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-pen_and_color/raw/main/assets/pen_up_and_down.gif)

## Step 2
To do this you use the ⇢``myTurtle pen up``⇠ block  
```blocks
myTurtle.pen(TurtlePenMode.Up)
```

## Step 3
Try making the **Turtle**:
- move forward 25 steps
- turn left 90°
- lift pen up
- move forward 25 more steps
- put pen down
- move forward 25 more steps
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-pen_and_color/raw/main/assets/pen_and_and_down.png)

## Step 7
Did you use blocks like these?
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
myTurtle.turnDirectionByDegrees(TurtleTurnDirection.Left, 90)
myTurtle.pen(TurtlePenMode.Up)
myTurtle.moveDirection(TurtleDirection.Forward, 25)
myTurtle.pen(TurtlePenMode.Down)
myTurtle.moveDirection(TurtleDirection.Forward, 25)
```


## Step 8
Done.

You now know how to make the **Turtle** move and turn.
