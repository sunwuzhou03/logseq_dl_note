- Assuming a fixed image size
  id:: 656dbef6-97c9-4e45-8746-d69f176b812a
- when the image are in different sizes, we can resize them in the same size.
- # image classification
  collapsed:: true
	- ![image.png](../assets/image_1701691563803_0.png)
	- the image combine by three dimensions.
	- In order to input the image into machine model, we can flatten the 3d-tensor(image)
	- ![image.png](../assets/image_1701691650500_0.png)
	- ![image.png](../assets/image_1701691673228_0.png)
	- when the model weight increasing, the possibility of overfitting will increasing
	- maybe we don't need to use fully connected network, we just need to extract some special feature
	- ![image.png](../assets/image_1701691793710_0.png)
	- ![image.png](../assets/image_1701691853948_0.png)
	- ![image.png](../assets/image_1701697825475_0.png)
	- can different neurons have different sizes of receptive field?
	- cover only some channels? no, some feature only appear in red(or green, blue) channel
	- not square receptive field?
	- ![image.png](../assets/image_1701697991649_0.png)
	- consider all channels, stride, padding
	- ![image.png](../assets/image_1701698108748_0.png)
	- each receptive field needs a "beak" detector? no, we can use share parameters
	- ![image.png](../assets/image_1701698245621_0.png)
	- ![image.png](../assets/image_1701698395770_0.png)
	- ![image.png](../assets/image_1701692693397_0.png)
	- ![image.png](../assets/image_1701698855402_0.png)
	- The above way use in image recognition will have low model bias. When we use cnn in other task, we need to consider if the pattern satisfy the above mode
- # Another story about convolutional neural network
  collapsed:: true
	- ![image.png](../assets/image_1701699104213_0.png)
	- ![image.png](../assets/image_1701699475087_0.png)
	- use filter to do the inner product
	- ![image.png](../assets/image_1701699718693_0.png)
	- ![image.png](../assets/image_1701699941499_0.png)
- # Pooling
  collapsed:: true
	- ![image.png](../assets/image_1701700121346_0.png)
	- pooling functions is to small the image(pool don't have parameters)
	- ![image.png](../assets/image_1701700178757_0.png)
	- ^^Notice^^: the pooling may also hurt the final model performance
	- ![image.png](../assets/image_1701700272813_0.png)
	-
- # Application: Playing Go
	- ![image.png](../assets/image_1701700477904_0.png)
	- the 48 channels come from domain knowledge. The expert use 48 numbers to describe the chess piece. it can be found in Alphago Paper
	  id:: 656de37f-579b-4208-b819-2ad14db5b2ba
	- ![image.png](../assets/image_1701700719793_0.png)
	- ![image.png](../assets/image_1701700794740_0.png)
	-