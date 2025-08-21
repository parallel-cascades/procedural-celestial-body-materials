# Procedural Asteroid Rings

Inner and Outer Radius control the shape of the asteroid ring.

The patterns in asteroid rings are built by sampling a detailNoise texture assigned by default to each Procedural Asteroid Shader. As an advanced user, you can plug your own textures here to get different patterns.

## Advanced Effects

You can use two asteroid rings on the same parent gas giant to get a more varied effect:

![Gas Giant with Two Rings](./assets/images/procedural-celestial-bodies/double-ring.png)
/// caption
The ring is composed of two overlapping asteroid ring meshes, with the inner ring's outer radius slightly smaller than the outer ring's inner radius (repeat that 5 times, ha!).
///