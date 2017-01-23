GAUNTLET

This is an example project demonstrating the use of the Gauntlet technique, a method of locomotion within
virtual reality using a Leap Motion Controller and only a single hand, leaving the user's other hand free for
other actions not related to locomotion.

The Leap Motion Attachment module determines when the user opens or closes their fist and allows the palm's
position and rotation to be tracked in real time. The Gauntlet technique uses the displacement of the fist in
local space away from a given origin to move the player in world space (exactly in the same way as a joystick)
and the local rotation of the fist away from a given origin to rotate the player in world space.

The PlayerMovement script and the Attachment module (found on the player in the project's scene) are the
two key components of this system.