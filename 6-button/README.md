# [Pete-Lawrence.github.io](https://pete-lawrence.github.io)
# [SEGA 6-Button Mega Drive/Genesis](https://pete-lawrence.github.io/6-button)
![6 button Mega Drive](https://pete-lawrence.github.io/6-button/svg/6button.png)
### Video example: [LMAO THERE AIN'T ONE CURRENTLY)
SEGA 6-Button Mega Drive/Genesis skin for Mr McPowned's Gamepad Viewer by [Peter Lawrence aka MegaSphere](https://www.youtube.com/c/PeterLawrenceYT/videos) for OBS.

* [Link to the documentation for the hella goofy Switch Macros for the Retro-Bit SEGA 6-Button Controller](https://www.dropbox.com/s/vrwqay1wswrajj8/RB_SEGA%20Genesis_6B_USB_NA_MANUAL_06-26-19.pdf?dl=0)

* [If your Switch Macros get applied immediately, this is a bug and to fix it, update your firmware here.](https://retro-bit.com/controllers-support)

## Configuration for SEGA 6-Button Controller (USB pad from Retro-Bit)
Create a **Browser source in OBS** with a Width of **800** and Height of **600** and use this URL. (You may have to check your Switch Macros).
* [Configuration for SEGA 6-Button Controller (USB pad from Retro-Bit)](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2F6-button%2Fskin.css)


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