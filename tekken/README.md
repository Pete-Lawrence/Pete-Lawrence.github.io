# [Pete-Lawrence.github.io](https://pete-lawrence.github.io)
# [Tekken-Gamepad](https://pete-lawrence.github.io/tekken)
![Tekken-Gamepad-Preview](https://pete-lawrence.github.io/tekken/screenshots/gamepad-new.png)
## Tekken 8
Create a **Browser source in OBS** with a Width of **1536** and Height of **512**. For the URL, use this [https://gamepadviewer.com/?p=1&css=https://pete-lawrence.github.io/tekken/tekken-new.css](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken-new.css)

To set your button mappings, there's no need to mess with gamepadviewer's remap this time around. Paste this into Custom CSS and modify it fit your mappings. I've tried to make it as straight forward as possible even if you're unfamiliar with CSS. You just edit the value of **background-position-x:** per button, that's all!

```css
/*X / Square*/
.custom .button.x.pressed { opacity: 1; 
background-position-x: -512px;	} /*1*/

/*Y / Triangle*/
.custom .button.y.pressed { opacity: 1; 
background-position-x: -1024px;	} /*2*/

/*A / Cross*/ .custom .button.a.pressed { opacity: 1; 
background-position-x: -1536px;	} /*3*/

/*B / Circle*/ .custom .button.b.pressed { opacity: 1; 
background-position-x: -2048px;	} /*4*/


/*RB / R1*/ .custom .bumper.right.pressed { opacity: 1; 
background-position-x: -8192px;	} /*HEAT*/

/*RT / R2*/ .custom .trigger-button.right.pressed { opacity: 1; 
background-position-x: -8704px;	} /*RAGE*/

/*RS / R3*/ .custom .stick.right.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/


/*LB /L1*/ .custom .bumper.left.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/

/*LT /L2*/ .custom .trigger-button.left.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/

/*LS /L3*/ .custom .stick.left.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/


/*Start (Menu) / Options*/ .custom .start.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/

/*Back (View) / Touchpad*/ .custom .back.pressed { opacity: 1; 
background-position-x: 0px;	} /*NONE*/

/*		MAPPINGS LIST
/*		
/*		background-position-x: 0px;	} /*NONE*/
/*		
/*		background-position-x: -512px;	} /*1*/
/*		background-position-x: -1024px;	} /*2*/
/*		background-position-x: -1536px;	} /*3*/
/*		background-position-x: -2048px;	} /*4*/
/*
/*		background-position-x: -2560px;	} /*1+2*/
/*		background-position-x: -3072px;	} /*2+4*/
/*		background-position-x: -3584px;	} /*3+4*/
/*		background-position-x: -4096px;	} /*1+3*/
/*		
/*		background-position-x: -4608px;	} /*1+2+4*/
/*		background-position-x: -5120px;	} /*2+3+4*/
/*		background-position-x: -5632px;	} /*1+3+4*/
/*		background-position-x: -6144px;	} /*1+2+3*/
/*		
/*		background-position-x: -6656px;	} /*2+3*/
/*		background-position-x: -7168px;	} /*1+4*/
/*		
/*		background-position-x: -7680px;	} /*1+2+3+4*/
/*		
/*		background-position-x: -8192px;	} /*HEAT*/
/*		background-position-x: -8704px;	} /*RAGE*/
```
Extra Skins still WIP although if you want PC/Xbox styled buttons add this to Custom CSS as well
![Tekken-Gamepad-Preview](https://pete-lawrence.github.io/tekken/screenshots/gamepad-new-pc.png)
```css
/*Buttons*/
.custom .button,
.custom .start,
.custom .back,
.custom .stick,
.custom .bumper,
.custom .trigger-button {
	top: 0px;
	right: 0px;
    position: absolute;
	width: 512px;
	height: 256px;
	opacity: 0;
	background: url(https://pete-lawrence.github.io/tekken/tekken-buttons-pc.svg);
}
```
---

# Legacy Tekken Gamepad Viewer Below
## (None of this applies to Tekken 8 Gamepad Viewer above)
---

![default pc/xbox style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-pc.png)
### Video example: [https://www.youtube.com/watch?v=fvnVDxeJVcg](https://www.youtube.com/watch?v=fvnVDxeJVcg)
Tekken skin for Mr McPowned's Gamepad Viewer by [Peter Lawrence aka MegaSphere](https://www.youtube.com/c/PeterLawrenceYT/videos) for OBS.
This skin supports all built-in button macros for Tekken.
<br>

## 1. Here are some premade configurations.
Create a **Browser source in OBS** with a Width of **1000** and Height of **400**. For the URL, pick one of the links below with the description that best fits you.
* [Completely default Tekken, R1 is Rage Art, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%5D%7D)

* [Default Tekken but R1 is 1+2 and R2 is 3+4, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%227%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%225%22%7D%5D%7D)

* [Korean Style, Shifts inputs 1 row to the right. Tri = 1, R1 = 2, Circle = 3, R2 = 4](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%221%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%220%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%222%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%223%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%223%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%221%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%227%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%223%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%225%22%7D%5D%7D)

* [Peter's Tekken config, default Tekken but R2 is 1+4, L2 is 1+2+3+4, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%226%22%7D%5D%7D)

* [Peter's other Tekken config, Korean Style but Cross = 3+4, Square = 1+2, L1 = RA, L2 = 1+4](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%220%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%222%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%224%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%226%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%220%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%221%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%221%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%227%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%222%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%223%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%223%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%225%22%7D%5D%7D)
<br>

## 2. Setting up your own configuration.

### Step 1.<br>Go to 'Button Rebinding' on gamepadviewer.

**[Go to 'Button Rebinding' here,](https://gamepadviewer.com/#remap)** When the page loads, press a button on your controller and select **"Player 1"** for **"Please select the controller to use as a mapping base"**.

---


### Step 2.<br>Setting up your button macros to match your own configuration ingame.

* Click **"Add New Mapping"** and select the button in the dropdown menu that has the button macro you desire as listed in **[Default Mapping](https://pete-lawrence.github.io/tekken/#3-default-mapping)**.

* Click **"Click to Set"** and press the button on your controller that you want the button macro applied to (before **"Waiting for Button Press..."** times out).

* Click **"Add New Mapping"** again and select the button in the dropdown menu you applied the macro to and click **"Disable"**. This prevents button macros from overlapping.

* Repeat as many times as needed to cover all your button macros before moving onto disabling unused buttons.

---


### Step 3.<br>Disable all the unused buttons.

When you're done setting up button macros, time to tidy things up by disabling all the unused buttons.
* Click **"Add New Mapping"** and select the button in the dropdown menu that has a button macro you **DO NOT USE** as listed in **[Default Mapping](https://pete-lawrence.github.io/#3-default-mapping)** and then click **"Disable"**. Don't worry if that button you disabled is a button you want to apply a *different* macro to.

---


### Step 4.<br>Export the configuration.


<br>When you are done follow these steps in this order, 
1. Press **"Apply Mapping"**

2. Press **"Export Mapping to URL Generator"**

3. Paste this link into **"Custom CSS URL:**" [https://pete-lawrence.github.io/tekken/tekken.css](https://pete-lawrence.github.io/tekken/tekken.css)

4. Finally create a **Browser source in OBS** with a Width of **1000** and Height of **400** and paste in the **generated URL**.

---

<br>

## 3. Default Mapping.
![Default Mapping](https://pete-lawrence.github.io/tekken/screenshots/gamepad-mapping.png)

X/Square = **1**

Y/Triangle = **2**

A/Cross = **3**

B/Circle = **4**
<br><br>

RB/R1 = **RA**

RT/R2 = **1+4**
<br><br>

LB/L1 = **2+4**

LT/L2 = **2+3**
<br><br>

RS/R3 = **3+4**

LS/L3 = **1+2**
<br><br>

Start = **1+3**

Back/Select = **1+2+3+4**

<br>

## 4. Bonus Skins (optional).
**Copy and paste the css code into "custom CSS" in the browser window for OBS to add the skin.**
<br>Note: You will have to wait around 20 seconds before it updates so don't panic if it doesn't instantly work.

---

![default ps style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-ps.png)

PlayStation button colours css.

```css
/*Face Buttons*/
.custom .button.x.pressed { background: #DFA1B4; } /*1*/
.custom .button.y.pressed { background: #0398A8; } /*2*/
.custom .button.a.pressed { background: #5092C0; } /*3*/
.custom .button.b.pressed { background: #C96280; } /*4*/

/*Button Combos*/
.custom .start,
.custom .back,
.custom .stick,
.custom .bumper,
.custom .trigger { background: url(https://pete-lawrence.github.io/tekken/tekken-button-combos-ps.svg); }
```




---

![clear white style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-clear-white.png)

Clear theme css.

```css
/*Face Buttons*/
.custom .button.x.pressed { background: #FFFFFF; } /*1*/
.custom .button.y.pressed { background: #FFFFFF; } /*2*/
.custom .button.a.pressed { background: #FFFFFF; } /*3*/
.custom .button.b.pressed { background: #FFFFFF; } /*4*/

/*Button Combos*/
.custom .start,
.custom .back,
.custom .stick,
.custom .bumper,
.custom .trigger { background: url(https://pete-lawrence.github.io/tekken/tekken-button-combos-clear.svg); }

/*Button Panel*/
.controller.custom {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear.svg);
background-position-x: -650px;
filter: drop-shadow( 1px 1px 0.75px rgba(0, 0, 0, 0.8));
}

/*Movement Inputs*/
.custom .fstick { background: url(https://pete-lawrence.github.io/tekken/tekken-clear.svg); }

/*Rage Art*/
.custom .bumper.right.pressed {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear.svg);
background-position-x: -910px; }
```

---

![clear red/white style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-clear-red.png)

Clear theme with red arcade style button colours css.

```css
/*Face Buttons*/
.custom .button.x.pressed { background: #CD0000; } /*1*/
.custom .button.y.pressed { background: #CD0000; } /*2*/
.custom .button.a.pressed { background: #CD0000; } /*3*/
.custom .button.b.pressed { background: #CD0000; } /*4*/

/*Button Combos*/
.custom .start,
.custom .back,
.custom .stick,
.custom .bumper,
.custom .trigger { background: url(https://pete-lawrence.github.io/tekken/tekken-button-combos-red.svg); }

/*Button Panel*/
.controller.custom {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-red.svg);
background-position-x: -650px;
filter: drop-shadow( 1px 1px 0.75px rgba(0, 0, 0, 0.8));
}

/*Movement Inputs*/
.custom .fstick { background: url(https://pete-lawrence.github.io/tekken/tekken-clear-red.svg); }

/*Rage Art*/
.custom .bumper.right.pressed {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-red.svg);
background-position-x: -910px; }
```

---

![clear pc/xbox style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-clear-pc.png)

Clear theme with PC/Xbox style button colours css.

```css
/*Button Panel*/
.controller.custom {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-pc.svg);
background-position-x: -650px;
filter: drop-shadow( 1px 1px 0.75px rgba(0, 0, 0, 0.8));
}

/*Movement Inputs*/
.custom .fstick { background: url(https://pete-lawrence.github.io/tekken/tekken-clear-pc.svg); }

/*Rage Art*/
.custom .bumper.right.pressed {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-pc.svg);
background-position-x: -910px; }
```

---

![clear ps style](https://pete-lawrence.github.io/tekken/screenshots/gamepad-clear-ps.png)

Clear theme with PlayStation button colours css.

```css
/*Face Buttons*/
.custom .button.x.pressed { background: #DFA1B4; } /*1*/
.custom .button.y.pressed { background: #0398A8; } /*2*/
.custom .button.a.pressed { background: #5092C0; } /*3*/
.custom .button.b.pressed { background: #C96280; } /*4*/

/*Button Combos*/
.custom .start,
.custom .back,
.custom .stick,
.custom .bumper,
.custom .trigger { background: url(https://pete-lawrence.github.io/tekken/tekken-button-combos-ps.svg); }

/*Button Panel*/
.controller.custom {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-ps.svg);
background-position-x: -650px;
filter: drop-shadow( 1px 1px 0.75px rgba(0, 0, 0, 0.8));
}

/*Movement Inputs*/
.custom .fstick { background: url(https://pete-lawrence.github.io/tekken/tekken-clear-ps.svg); }

/*Rage Art*/
.custom .bumper.right.pressed {
background: url(https://pete-lawrence.github.io/tekken/tekken-clear-ps.svg);
background-position-x: -910px; }
```

---