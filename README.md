# Unity AR Object Placement
### Unity AR project to place prefabs on flat surfaces.

![forthebadge](https://user-images.githubusercontent.com/86726474/152202421-3ee4053f-656c-4780-80c7-aad92f15223b.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-c-sharp.svg)

## INTRODUCTION:

I created this simple Augmented Reality app by following a tutorial to be more familiar with Unity's AR development kits. The app detects flat surfaces and places an indicator if the surface is good enough to place our spinning guy prefab. Then after detecting a touch input, our prefab gets instantiated. I used AR Foundation, ARCore XR Plugin and ARKit XR Plugin to achieve this interaction.

## SETUP AND BUG FIXES:

* Added AR Raycast Manager script to AR Session Origin to shoot rays from our AR Camera.
* Plane detection was not working so adding AR Plane Manager script to AR Session Origin fixed it.
* Placement indicator was not showing up so disabled AR Pose Driver script and instead used the legacy Tracked Pose Driver to fix it.

## SCREENSHOTS:

### The placement indicator

![Unity_AR_11](https://user-images.githubusercontent.com/86726474/213955456-5dac6f39-1953-451c-b726-03aa97a0955b.jpg)

### Placing the prefab with touch input

![c99944b7-c24e-42fe-ab2c-b670caa3fa98](https://user-images.githubusercontent.com/86726474/213955224-c89f9862-515d-4018-b7e1-d8f488242843.gif)

## CREDITS:

* @TheUnityWorkbench on YouTube

