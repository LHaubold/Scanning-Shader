# **Scanning Shader** 

This Shader creates a translucent force field that can dissolve. This is accomplished using simplex noise. I wrote this shader for  [this](https://teamtorte.itch.io/veneris) project i worked on with two artists to visualize a scanning mechanic, as well as some ambient lighting effects. A normal map can be applied to give the force field some form of texture and there are some other features briefly explained below. 

**Funktions:**
- Main Colour:        The colour of the force field
- Emission:           The Colour of the border inbetween dissolved and intact parts
- Texture:            The normal map used
- Fresnel intensity:  Glow around the Edges
- Fresnel with:       Transparency intensity
- Distort:            Intensity of the distortion effect when looking through the force field
- Highlight of intersection threshold: Intensity of glow highlitghting forcefield colliding with surfaces
- Scroll U Speed:     Horizontal texture movement
- Scroll V Speed:     Vertical texture movement
- Frequency:          Noise frequency
- Speed:              Noise movement speed
- Emission Border:    Size of the border inbetween dissolved and intact parts
- Dissolvepercentage: Handle to change the amount of force field dissolved from 0% to 100%
- Extrusion amount:   Mesh extrusion handle


**Shader at 0%, 50%, 80% dissolvepercentage:**

![force field dissolved: 0%, 50%, 80%](https://github.com/LHaubold/Scanning-Shader/blob/master/example.PNG)
Screenshot taken with Post-Processing bloom effect on
