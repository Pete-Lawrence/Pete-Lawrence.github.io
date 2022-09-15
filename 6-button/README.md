# [Pete-Lawrence.github.io](https://pete-lawrence.github.io)
# [SEGA 6-Button Mega Drive/Genesis](https://pete-lawrence.github.io/6-button)
![6 button Mega Drive](https://pete-lawrence.github.io/6-button/svg/6button.png)
### Video example: [LMAO THERE AIN'T ONE CURRENTLY)
SEGA 6-Button Mega Drive/Genesis skin for Mr McPowned's Gamepad Viewer by [Peter Lawrence aka MegaSphere](https://www.youtube.com/c/PeterLawrenceYT/videos) for OBS.

* [Link to the documentation for the hella goofy Switch Macros for the Retro-Bit SEGA 6-Button Controller](https://www.dropbox.com/s/vrwqay1wswrajj8/RB_SEGA%20Genesis_6B_USB_NA_MANUAL_06-26-19.pdf?dl=0)

* [If your Switch Macros get applied immediately, this is a bug and to fix it, update your firmware here.](https://retro-bit.com/controllers-support)

## Configuration for SEGA 6-Button Controller (USB pad from Retro-Bit)
Create a **Browser source in OBS** with a Width of **800** and Height of **600** and use this URL.
<br>Note: You may have to check your Switch Macros and have the controller set to X Input mode.
* [Configuration for SEGA 6-Button Controller (USB pad from Retro-Bit)](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2F6-button%2Fskin.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%226%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%225%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%227%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%224%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2212%22%2C%22disabled%22%3Afalse%2C%22choiceOperand%22%3A%22-%22%2C%22choiceType%22%3A%22axes%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2213%22%2C%22disabled%22%3Afalse%2C%22choiceOperand%22%3A%22%2B%22%2C%22choiceType%22%3A%22axes%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2214%22%2C%22disabled%22%3Afalse%2C%22choiceOperand%22%3A%22-%22%2C%22choiceType%22%3A%22axes%22%2C%22choice%22%3A%220%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2215%22%2C%22disabled%22%3Afalse%2C%22choiceOperand%22%3A%22%2B%22%2C%22choiceType%22%3A%22axes%22%2C%22choice%22%3A%220%22%7D%5D%7D)


## Enable Additional Trigger Buttons (optional).
**Copy and paste the css code into "custom CSS" in the browser window for OBS to add the skin.**
<br>Note: You will have to wait around 20 seconds before it updates so don't panic if it doesn't instantly work.

---

![Additional Trigger Buttons](https://pete-lawrence.github.io/6-button/svg/6button_triggers.png)

Additional Trigger Buttons css.

```css
.custom .triggers {
background: url(svg/6button-triggers.svg);
    position: absolute;
    width: 800px;
    height: 600px;
}

.custom .trigger.left {
background: url(svg/6button-triggers-L.svg);
    position: absolute;
    width: 800px;
    height: 600px;
}

.custom .trigger.right {
background: url(svg/6button-triggers-R.svg);
    position: absolute;
    width: 800px;
    height: 600px;
}
```
