# Mic-Mute-Pin
README WIP

A button/pin that indicates to others if you're muted. 

## How it works

Tied to the VRChat 'DetectMute' parameter, it toggles on when you mute yourself and disables mouth animations. An optional provided detector can enable/disable the pin's functionality.

## Install guide

VIDEO TUTORIAL COMING SOON

This assumes you know a little bit about Unity Animators and VRChat Avatars.


2) Position mic_mute_pin.fbx on your avatar as desired, move under parent bone to follow as desired 
(for example, if on chest put it under the Chest bone).

3) add preferred color texture (black/white or red/black)

4) Create 2 animations,  1 with the pin toggled on, 1 with the pin toggled off

5) In your FX layer, create/copy the animation layers mirroring the provided example FX layer. Add the respective animations to the layer accordingly.

6) In your VRCExpressionParameters add a boolean called 'DetectMute'

7) In your VRCExpressionsMenu add a Toggle tied to the 'DetectMute' bool you previously made.

8) Upload, test, and if working, enjoy!

## Contact me

Uh, if you need help or have issues, I can be found on [Twitter](https://twitter.com/PurposeUnkn0wn).
