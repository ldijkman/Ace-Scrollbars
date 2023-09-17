# Ace Editor Scrollbars
CSS Scrollbars for [Ace Editor](https://github.com/ajaxorg/ace)

Ace demo https://ace.c9.io/build/kitchen-sink.html

---

changes to original ext-scrollbar.js https://github.com/ldijkman/Ace-Scrollbars/blob/master/src/ext-scrollbar.js

treid to change

offset if editor does not start at windowpos zero

from pixel position to percent positions

works a bit better on different font sizes

Custom ScrollBars Demo https://ldijkman.github.io/randomnerd_esp32_wifi_manager/mrs/create_from_scratch/Insane%20in%20the%20Membrane/ACE_Editor_JumpMarks_ScrollMarks.html

Custom ScrollBars https://plnkr.co/edit/EYJWlWGjCdjNoui8?preview

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

<img src="./screenshot.png">
