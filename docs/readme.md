# Ace Editor Custom Scrollbar 

# Ace_Seventh_Heaven
Ace Editor Seventh Heaven

Heaven 7

Demo: https://ldijkman.github.io/Ace_Seventh_Heaven/Seventh_Heaven.html

Source: https://github.com/ldijkman/Ace_Seventh_Heaven/tree/main/docs


![Ace_Editor_Seventh_Heaven](https://github.com/ldijkman/Ace_Seventh_Heaven/assets/45427770/5177ca3b-b75e-464c-a003-c50e455db494)


# Demo

demo https://ldijkman.github.io/Ace-Scrollbars/Ace_editor_custom_scrollbar.html

source https://github.com/ldijkman/Ace-Scrollbars/tree/master/docs


---










map search / highlight select on vertical scrollbar

CSS Scrollbars for [Ace Editor](https://github.com/ajaxorg/ace)

Ace demo https://ace.c9.io/build/kitchen-sink.html

---
ace kitchen-sink demo custom scrollbars did not work nice i think

so searched and found this one that worked better i think

changes to original ext-scrollbar.js https://github.com/ldijkman/Ace-Scrollbars/blob/master/src/ext-scrollbar.js

treid to change

offset if editor does not start at windowpos zero

from pixel position to percent positions

works a bit better on different font sizes

Ace Editor Custom ScrollBars Demo https://ldijkman.github.io/randomnerd_esp32_wifi_manager/mrs/create_from_scratch/Insane%20in%20the%20Membrane/ACE_Editor_JumpMarks_ScrollMarks.html

Ace Editor Custom ScrollBars Demo https://plnkr.co/edit/EYJWlWGjCdjNoui8?preview

Ace Editor Custom ScrollBars Demo https://codepen.io/ldijkman/pen/ZEVXOEv

---

Simple to use CSS styled scrollbars:

Just link to two files then initialise the scrollbars after initialising Ace.

    <link rel="stylesheet" type="text/css" href="ext-scrollbar.min.css">
    <script src="ext-scrollbar.min.js"></script>

    <script>
    // Ace initialisation
    var editor = ace.edit("editor")
    // Create new scrollbars
    new AceScrollbars(editor)
    ...
    </script>
### Added search/occurance map

Ace Editor Custom ScrollBars Demo https://plnkr.co/edit/EYJWlWGjCdjNoui8?preview

Ace Editor Custom ScrollBars Demo https://codepen.io/ldijkman/pen/ZEVXOEv

![2023-09-17-083638_1920x1080_scrot](https://github.com/ldijkman/Ace-Scrollbars/assets/45427770/efe9dcb7-a4ea-4004-b846-27209076058d)

---

<img src="./screenshot.png">

