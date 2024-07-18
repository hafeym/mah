# micro-led

## Toggle an led

Drag the code from LED toolbox to toggle an LED

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

## Randomize x

Drag the code to pick a random ``x`` index
between ``0`` and ``4`` from the Math toolbox.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), )
})
```
## Randomize y

Drag the code to pick a random ``y`` index
between ``0`` and ``4`` from the Math toolbox.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```

## All the code

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```