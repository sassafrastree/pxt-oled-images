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
oledImages.drawText("Hello world", 0, 0, true)
```
## Clearing Screen

```blocks
// Initiates the screen at the start of the program
oledImages.init()
// clears screen
oledImages.clear()
// Draws text
oledImages.drawText("Hello world", 0, 0, true)
```

## Supported targets

* PXT/microbit

## License

MIT
