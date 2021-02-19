# A-Frame Gamepad example

WORK IN PROGRESS

Quick demo using a USB gamepad in [A-Frame](https://aframe.io/). Live at https://i3games.github.io/aframe-gamepad/. This setup is suited for cardboard VR where you can look around with the headset. 

![](setup.jpg)

Here I use an Speed Link SL 6603 to interact with the scene in first-person control. Other USB gamepads  work with my Android device as well - as long as they are connected through a USB OTG adapter. 

The `gamepadconnected` event contains information about that gamepad such as the `gamepad.id`: "SPEED-LINK Competition Pro  (Vendor: 040b Product: 6533)". The `gamepadbuttondown` event has the numbers of the buttons pressed in `event.detail.index`: 

```
Left: 0
Right: 1
Left Triangle: 2 
Right Triangle: 3
```

Other gamepads have different values. 

In this example the joystick is used to move and the triangular shoulder buttons to rotate. Left button toggles the color of the element (cube, sphere, cylinder) under the cursor. Right button triggers a sound.




MIT License 

## Third-Party Licenses

Image credits: kin design    
https://github.com/n5ro/aframe-extras Copyright (c) 2016 Don McCurdy             
A-Frame authors    
