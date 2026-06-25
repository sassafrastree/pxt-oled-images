# oled-images

## Basic Images

```blocks
// Initiates the screen at the start of the program
oledImages.init()
// Draws an image with a pixel map
oledImages.drawImage(oledImages.imageMapS(`
    . . . . . . . . . . . . . . . .
    . . # . . # . . . # . . . . . .
    . . # . . # . . # # # . . . . .
    . . # . . # . . . # . . . . . .
    . . # # # # . . . . . . . . . .
    . . # . . # . . . # . . . . . .
    . . # . . # . . . # . . . . . .
    . . # . . # . . . # . . . . . .
    `), 0, 0)

```

## Using Text

```blocks
// Initiates the screen at the start of the program
oledImages.init()
// Draws text
oledImages.drawText("Hello world", 0, 0)
```
## Clearing Screen

```blocks
// Initiates the screen at the start of the program
oledImages.init()
// Draws text
oledImages.drawText("Hello world", 0, 0)
basic.pause(1000)
// clear screen
oledImages.clear()

```

## Supported targets

* PXT/microbit

## License

MIT
