# CubemapFog
Add the use of a cubemap as a color source for fog to the GlobalFog Image Effect.

![Cubemap Fog On](https://dl.dropboxusercontent.com/u/1812933/Unity/CubemapFog.png)

![Cubemap Fog Off](https://dl.dropboxusercontent.com/u/1812933/Unity/OnColorFog.png)

# How to use

Set project to Linear color space and deferred shading.

Then add GlobalFog.cs to your camera.

You can specify your own cubemap as a source of color for the fog, just make sure "Glossy Reflection" is enabled.

You can also let the script to use the cubemap from your skybox material but you'll have to enable "Glossy Reflection" aswell and you need to use the custom skybox shader provided ("cCharkes/Skybox/Cubemap LOD Fix") or artefacts will appear in your sky.

# References

- [Waylon Brinck and Andrew Maximov, Siggraph16] "The Technical Art of Uncharted 4"

