# Rotate3D
Apply 3D like rotation to DOM elements. Responds to device orientation and mouse over.

Similar to how iOS will move the background as you move your device, this rotates a DOM element 

**Work in progress: Browser detection does not work yet**

## Using it

Simply include `Rotate3D.js` and `Rotate3D.css` in your project. The `.r3d-wrapper` should wrap anything you want to add the effect to. The class adds a `perspective` attribute, which brings out the 3D effect. The `.r3d` class adds the actual css components.

`Rotate3D(<className>, [options])` is all you have to do! 

The only option right now is intensity. Intensity is the max angle of rotation. It defaults to 10.
