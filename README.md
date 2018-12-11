

# ToodleBit Traffic Lights Package
This ToodleBit traffic lights package was developed by [ToodleBit](https://www.toodlebit.com/)

ToodleBit Traffic Lights has been designed for use in education, particularly the primary(KS2) sector. These code blocks have been created to provide an easier route for users to get their LEDs lit.


![ToodleBit Traffic Lights](https://github.com/ToodleBit/lights/blob/master/icon.png?raw=true)

## Code Example
```JavaScript
basic.forever(function () {
    ToodleBit.forward()
    if (ToodleBit.toodlebit_crash(DigitalPin.P1) == 0) {
        ToodleBit.back()
        basic.pause(500)
        ToodleBit.turnleft()
        basic.pause(500)
    }
})
```

## License
MIT

## Supported targets
for PXT/microbit (The metadata above is needed for package search.)

