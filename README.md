# Render_Without_Personal

To create a without some functions must be added to the unity render, in this case, I use the **Universal render pipeline**

1. In the universal render pipeline we are going to add a **Render Object (experimental)**

![image](https://user-images.githubusercontent.com/26027219/107083580-d8e37100-67c3-11eb-9512-2ff91ff75c98.png)

In the name part, we add the name we want as required

![image](https://user-images.githubusercontent.com/26027219/107083646-f44e7c00-67c3-11eb-9c94-491794aeafc7.png)

2. We create a layer for the object, in this case, the without is for the character

![image](https://user-images.githubusercontent.com/26027219/107083713-0cbe9680-67c4-11eb-994e-622d1e7707a9.png)

3. We do not add this layer where it says Filters in layer mask, within the render features

![image](https://user-images.githubusercontent.com/26027219/107083843-3972ae00-67c4-11eb-877b-afdb1b40915e.png)

4. In the Overrides section, we must add a material, which will be the one that represents the without, create a material and add it to Overrides / material, in the Depth part, we deactivate the write depth

![image](https://user-images.githubusercontent.com/26027219/107083878-4d1e1480-67c4-11eb-87a5-f02785877e61.png)

5. We add another Render Object (Experimental), and we assign the name of #NAME_Front, and we add the layer in the Filters section layer mask, in this case, I add player

![image](https://user-images.githubusercontent.com/26027219/107083950-67f08900-67c4-11eb-80e9-c1cbae6dbef3.png)

6. Create the shader graph: We create a shader graph of type unlit graph and assign it to the material created previously

![image](https://user-images.githubusercontent.com/26027219/107084024-7ccd1c80-67c4-11eb-9835-e967fd5af237.png)

7. Finally, we add the layer to the object "Character", and this would be the final result

![image](https://user-images.githubusercontent.com/26027219/107084164-b30a9c00-67c4-11eb-8e85-ec45ff90f05b.png)
