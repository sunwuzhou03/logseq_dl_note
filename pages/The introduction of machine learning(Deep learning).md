- Machine Learning $\approx$ Looking for function. For example, it's very difficult for human to draw the function of image, speech recognition and playing go. So we need to the machine help us to look for these hard tasks function.
  collapsed:: true
	- ![image.png](../assets/image_1694167012479_0.png)
- # Different types of Functions
  collapsed:: true
	- **Regression**: The function outputs a scalar, such as predict the PM2.5.
	  ![image.png](../assets/image_1694167124450_0.png)
	- **Classification**: Given the options(**classes**)
	  ![image.png](../assets/image_1694167196653_0.png)
	  ![image.png](../assets/image_1694167231631_0.png)
	- **Structured Learning**: create something with structure (images, documents)
	  ![image.png](../assets/image_1694167441914_0.png)
- # How to create a model to predict something?
  collapsed:: true
	- ## 1. Function with unknown parameters
	  collapsed:: true
		- Domain knowledge use to find a suitable initial function style, such as the $y=b+wx$
		- ![image.png](../assets/image_1694167829780_0.png)
		- {{embed ((64fafcc0-c00d-49f0-b8be-3652e8f10f53))}}
	- ## 2.Define Loss from Training Data
	  collapsed:: true
		- ![image.png](../assets/image_1694168355061_0.png)
		- {{embed ((64faf8f2-939e-40ae-9b68-946c27db9472))}}
	- ## 3. Optimization
	  collapsed:: true
		- The way to optimization in this course is **Gradient Descent**
		- ![image.png](../assets/image_1694169154028_0.png)
		- When we do the deep learning, the local minima is not the truly problem we need to deal with.
		- how to use this way?
		  collapsed:: true
			- ![image.png](../assets/image_1694169323253_0.png){:height 398, :width 520}
			  ![image.png](../assets/image_1694169434700_0.png)
		- {{embed ((64fb0362-4c77-4d24-bfd0-938856e67e3c))}}
- Machine learning is so simple with the three steps(only use to train). we need to know the train loss and the test loss, the second one is loss for the unseen data.
  collapsed:: true
	- ![image.png](../assets/image_1694169702908_0.png)
	- According the model performance, we need to change the model according to the domain knowledge. For example, the first model in the follow first figure is bad. And we rewrite a new model(can see in the second figure) by observing the data we collected. Then we compare the test loss among the different models. In second figure, we improve model by adding the days need to thinking. We can find that when the number of days considered reaches a certain value, the model's ability can no longer be improved.
	  collapsed:: true
	  All of the follow models is **Liner model**.
		- ![image.png](../assets/image_1694169922136_0.png)
		  ![image.png](../assets/image_1694170110194_0.png)
- Liner models are too simple to solve the more difficult tasks. We need to the more sophisticated models . This model limitation is from the **model bias**.
  id:: 64fafcc0-c00d-49f0-b8be-3652e8f10f53
	- We can use the constant and the sum set of blue function to make the red curve.  
	  collapsed:: true
	  **Liner curve**
	  **Piecewise Liner curve**(the red curve in the first figure)
	  **Beyond Piecewise Liner**.
		- ![image.png](../assets/image_1694172398304_0.png) 
		  ![image.png](../assets/image_1694170359105_0.png)
		  ![image.png](../assets/image_1694170756078_0.png)
		  ![image.png](../assets/image_1694170863326_0.png)
	- How to write the curve?
	  collapsed:: true
		- Just to add sigmoid function and adjust the $w$, $c$ and $b$ to get the different blue function. Then we combine many blue function to get more sophisticated red function.
			- ![image.png](../assets/image_1694171299704_0.png)
			  ![image.png](../assets/image_1694171335476_0.png)
			  ![image.png](../assets/image_1694171520677_0.png)
			-
		- We get the new model that have more features.
			- ![image.png](../assets/image_1694171657449_0.png)
			  ![image.png](../assets/image_1694171860171_0.png)
			  ![image.png](../assets/image_1694171996236_0.png)
			  ![image.png](../assets/image_1694172124997_0.png)
			  ![image.png](../assets/image_1694172853013_0.png)
- When rewrite the model(function), how to calculate loss function?
  id:: 64faf8f2-939e-40ae-9b68-946c27db9472
	- ![image.png](../assets/image_1694173166128_0.png){:height 421, :width 550}
- Optimization of new model
  id:: 64fb0362-4c77-4d24-bfd0-938856e67e3c
  collapsed:: true
	- ![image.png](../assets/image_1694173386352_0.png)
	  ![image.png](../assets/image_1694173446978_0.png)
	- use batch randomly gradient descent
		- ![image.png](../assets/image_1694173583146_0.png)
		- update means update the para every time, epoch means see all batches. Can tel the different between the batch and the epoch in the follow image.
		  ![image.png](../assets/image_1694173781972_0.png)
- More variety of models
  collapsed:: true
	- We also get the blue function by using relu.
		- ![image.png](../assets/image_1694174026164_0.png)
		- ![image.png](../assets/image_1694174083925_0.png)
	- Experimental Results
		- ![image.png](../assets/image_1694174151668_0.png)
- We can continue to improve the model. Just increase the depth(how many layers we need).
  collapsed:: true
	- ![image.png](../assets/image_1694174207191_0.png)
	- Experimental Results
		- ![image.png](../assets/image_1694174306020_0.png)
		  ![image.png](../assets/image_1694174326110_0.png)
- Give a fancy name.
  collapsed:: true
	- ![image.png](../assets/image_1694175001274_0.png){:height 421, :width 550}
- Deep $=$ Many hidden layer
  collapsed:: true
	- ![image.png](../assets/image_1694175137492_0.png)
- Why don't we go deeper?
  collapsed:: true
	- ![image.png](../assets/image_1694175206609_0.png)