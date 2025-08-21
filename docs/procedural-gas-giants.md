# Procedural Gas Giants

Similar to Procedural Stars, Gas Giants are built with domain warped FBM noise, but the pattern is kept constant around the Y axis, to produce distinct vertical layers.

<video controls loop width="480" height="270">
    <source src="../assets/videos/jupiter.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

## Setup

As with procedural stars, the quickest way to add a new gas giant to your scene is by using the [custom menu commands](custom-menu-commands.md) added to Unity’s context menu. There's options for gas giants with and without asteroid rings.

## MonoBehaviour Component Reference
![Gas Giant Component](./assets/images/procedural-celestial-bodies/gas-giant-component.png)

Similar to the Stars, Gas Giants are built with domain warped FBM noise, but the pattern is kept constant around the Y axis, to produce distinct vertical layers.

You can control the variation along each axis using the X and Z Scaling and Y Gradient Scale and Strength Properties. Observe the difference between the Saturn and Jupiter samples in the Sample Scene.

## Gas Giant Glow

The glow effect is a full-screen 3D post-processing effect, same as the [Star Corona Glow](./procedural-stars.md/#star-corona-glow-techniques). In addition, it uses the main light direction to darken parts of the effect.

