# Lernprogramm

## It's time to code! @showHint

Let's get real bright. We're going to make all the lights flash on your board!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional step to split up the activity.
```block
    export function baa() {
        basic.showString("Alois")
        console.log("alois")
    }
``` 

```block
    basic.forever(function() {
        basic.showNumber(input.temperature())
        basic.pause(1000)
        basic.showString("alois")
    })

```


## Make a new variable @showdialog

Let's get real bright. We're going to make all the lights flash on your board!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display 

```block
length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional s**te**p 

```

# Zweite Hauptüberschrift 


Mit diesem Kurs lernst du, wie du Microbit entdecken kannst!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional step to split up the activity.
```block
    export function baa() {
        basic.showString("Alois")
        console.log("alois")
    }
``` 

![Hier muss ein Bild stehen](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/bild.png)

## Step 2
# Anleitung 

Sehr gut!

![Bild](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/b.png)

![Bildreferenzen richtig](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/w.png)

## Introduction @unplugged

Have the agent build a tower! Make a command to tell it how many levels to build.
![Agent building a tower](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/mb.png)



## Schritt Show the temperature

Get a ``||input:temperature||`` block and place it in the value slot of ``||basic:show number||``.

```block
    basic.forever(function() { 
        basic.showNumber(input.temperature())
        basic.pause(1000)
    })


    basic.forever(function() {
        basic.showNumber(input.temperature())
        basic.pause(1000)
        basic.showString("alois")
    })
```

