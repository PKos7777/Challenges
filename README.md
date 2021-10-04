# Challenges

## Challenge 1:  Build Switch Access System ( for next/select, scan-mode-control, ...)

### Background:
Switch access allows people with limited mobility and/or reach to use phones, tablets, and PC's via the use of switches.  The switches are of many forms (big buttons, capapcitive-buttons, sip&puff switches, etc).

### Problem / Challenge
While the software is common and sometimes free by default (for example on Android and iPhones) affordable hardware is not common or cheap => and it could / should be.  All that is needed is system to send a unique keyboard-hid-event for 1 or 2 switches.  The event can be sent over USB or Bluetooth to the host-device.

Sub-challenge is to see how cheap we can build this.  If someone is using a $50 Android phone, they won't pay $200 for switch-access-hardware but they may be $10.  Can we build a system that sells for $10?

### Source
Entered by Paul Kos

### Related Links: 

- [About Switch Access for Android](https://support.google.com/accessibility/android/answer/6122836)

-------------------------------------------------------------------------------------------------------------

## Challenge 2:  Build Switch Access System ( for next/select, scan-mode-control, ...)

### Background:
Control a device (PC/tablet/phone) or application  with just a single button with an external scan-mode implementation.  This is needed because not all applications support switch-access-mode.  With an external scan-mode system, we can use 1 (or 2) buttons to emulate each function of a mouse.  We do this by "scanning" thru modes and selecting which mode you want the button to be in.  The button can "move left", "move right", "move up", "move down", "left click", "right click", "middle click", "click and hold", ...

### Problem / Challenge
The hardware is not difficult but off-the-shelf-solutions are not common.  We just need a button, a brain, some LED's and a little code.  Reference the example at the link below

### Source
Entered by Paul Kos

### Related Links: 
-  [external scan mode system example](https://youtu.be/Luvadk9oKYs?t=238) 


-------------------------------------------------------------------------------------------------------------
