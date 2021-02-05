# Render_Without_Personal

To create a without some functions must be added to the unity render, in this case, I use the universal render pipeline

1. In the universal render pipeline we are going to add a render object (experimental)

photo

In the name part, we add the name we want as required

2. We create a layer for the object, in this case, the without is for the character

photo

3. We add this layer where it says Filters in layer mask, inside the render features

photo

4. In the Overrides section, we must add a material, which will be the one that represents the without, create a material and add it to Overrides / material, in the Depth part, we deactivate the write depth

photo

5. We add another Render Object (Experimental), and we assign the name of #NAME_Front, and we add the layer in the Filters section layer mask, in this case, I add player

photo

6. Create the shader graph: We create a shader graph of type unlit graph and assign it to the material created previously

photo
