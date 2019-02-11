# Tekken-Gamepad
Tekken skin for Mr McPowned's Gamepad Viewer by [Peter Lawrence](https://steamcommunity.com/id/PeterLawrence/)

This skin supports all built-in button macros for Tekken.

Gamepad Viewer is for OBS. Create a CLR Browser source and paste the URL there.

## Here are two common configurations.
* [Completely default Tekken, R1 is Rage Art, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%5D%7D)

* [Default Tekken but R1 is 1+2 and R2 is 3+4, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%225%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%227%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%227%22%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Afalse%2C%22choiceType%22%3A%22buttons%22%2C%22choice%22%3A%225%22%7D%5D%7D)

* [Peter's Tekken config, default Tekken but R2 is 1+4, all other buttons disabled](https://gamepadviewer.com/?p=1&css=https%3A%2F%2Fpete-lawrence.github.io%2Ftekken.css&map=%7B%22mapping%22%3A%5B%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%228%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%229%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%226%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%224%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2211%22%2C%22disabled%22%3Atrue%7D%2C%7B%22targetType%22%3A%22buttons%22%2C%22target%22%3A%2210%22%2C%22disabled%22%3Atrue%7D%5D%7D)

## Setting up your own configuration.
[If you use a different configuration, please click here to remap your controls and disable unused buttons.](https://gamepadviewer.com/#remap) When the page loads, press a button on your controller and select **"Player 1"** for **"Please select the controller to use as a mapping base"**.

### Disabling a button.
* Click **"Add New Mapping"** and select the button in the dropdown menu that has a button macro you **DO NOT USE** as listed in **Default Mapping (See bottom of this page)** and then click **"Disable"**. Don't worry if that button you disabled is a button you want to apply a *different* macro to. Follow the next guide for that.


### Setting up a button macro.
* Click **"Add New Mapping"** and select the button in the dropdown menu that has the button macro you desire as listed in **Default Mapping (See bottom of this page)** and then click **"Click to Set"**.

* Press the button on your controller that you want the button macro applied to (before **"Waiting for Button Press..."** times out).

* Click **"Add New Mapping"** and select the button in the dropdown menu you applied the macro to and click **"Disable"** to prevent button macros from overlapping.

When you are done follow these steps in this order, 
1. Press **"Apply Mapping"**

2. Press **"Export Mapping to URL Generator"**

3. Finally paste this link into **"Custom CSS URL:**" [https://pete-lawrence.github.io/tekken.css](https://pete-lawrence.github.io/tekken.css)

## Default Mapping
X/Square = **1**

Y/Triangle = **2**

A/Cross = **3**

B/Circle = **4**


RB/R1 = **RA**

RT/R2 = **1+4**


LB/L1 = **2+4**

LT/L2 = **2+3**


RS/R3 = **3+4**

LS/L3 = **1+2**


Start = **1+3**

Select/Back = **1+2+3+4**
