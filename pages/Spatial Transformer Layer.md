- ^^CNN is not invariant scaling and rotation^^
- ![image.png](../assets/image_1701705896960_0.png)
- # Explain
  collapsed:: true
	- ![image.png](../assets/image_1701916848104_0.png)
	- ![image.png](../assets/image_1701916795223_0.png)
	- the image combined by pixel, we can rotate or scaling by changing the pixel location. ^^Notice^^, the pixel location is integer.
	  id:: 657138a7-59b4-4797-b65b-b028a7ee2f86
	- ![image.png](../assets/image_1701916984328_0.png)
	- ![image.png](../assets/image_1701917095407_0.png)
	- ![image.png](../assets/image_1701917178931_0.png)
	- ![image.png](../assets/image_1701917596694_0.png)
	- If we use round to process the radix, the gradient descend will be not valid. Thereby, we use the interpolation.
	  id:: 657137e2-bd6a-4226-af29-565312a0081b
	- ![image.png](../assets/image_1701917906807_0.png)
	- ![image.png](../assets/image_1701918051285_0.png)
	-
- # Application
  collapsed:: true
	- ![image.png](../assets/image_1701918495868_0.png)
	- ![image.png](../assets/image_1701918445072_0.png)
	- fix the two parameter make the layer only have the scaling function which is similar to focus on some part of object.