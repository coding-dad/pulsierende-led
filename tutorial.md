# Pulsierende LED

## Ziehe den Code, um den Leucht-Zustand einer LED zu wechseln. 

```blocks
basic.forever( () => {
    led.toggle(0, 0)
})
```

## Setze die Position der LED, die pulsieren soll, in dem Du für die X- und Y-Position jeweils den Wert 2 einträgst.

```blocks
basic.forever(() => {
    led.toggle(0, 0)
})
```

## Da das Pulsieren der LED viel zu schnell erfolgt, ziehe einen Pause-Code-Block und 
gib als Wert für die Wartezeit die Zahl 100 ein und definiere so eine Wartezeit von 100ms, 
bevor die Schleife forgeführt wird. 

```blocks
basic.forever( () => {
    led.toggle(2, 2)
    basic.pause(100)
})
```

## Fertig :o)
