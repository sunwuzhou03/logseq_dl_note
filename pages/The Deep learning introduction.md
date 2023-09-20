- ![image.png](../assets/image_1694229371714_0.png)
- # Ups and downs of Deep Learning
  collapsed:: true
	- ![image.png](../assets/image_1694230017828_0.png)
- # Three steps for deep learning
  collapsed:: true
	- ![image.png](../assets/image_1694232303877_0.png)
	- step 1: {{embed ((64fbe613-ba0a-4b95-a77b-d4e11c14452a)) }}
	- step 2:
	- step 3:
- # How to connect the layers?
  id:: 64fbe613-ba0a-4b95-a77b-d4e11c14452a
  collapsed:: true
	- Fully Connect Feedforward network
	  collapsed:: true
		- ![image.png](../assets/image_1694230346648_0.png)
		  ![image.png](../assets/image_1694230522630_0.png)
	- Deep $$=$$ Many hidden layer
	  collapsed:: true
		- The Residual Network beat the human in the image recognition.
			- ![image.png](../assets/image_1694230682568_0.png)
	- NN is a series of maxtrix operation
	  collapsed:: true
		- ![image.png](../assets/image_1694231002764_0.png) 
		  ![image.png](../assets/image_1694230951593_0.png)
	- output layer
		- hidden layer extract feature. we consider the output layer as multi-class classifier so we need to add the softmax function after the output layer.
		  collapsed:: true
			- ![image.png](../assets/image_1694231110884_0.png)
		- example
		  collapsed:: true
			- ![image.png](../assets/image_1694231817459_0.png)
	- FAQ
	  collapsed:: true
		- When we use machine learning before, we need to do some feature engineer. But now, we can use deep learning that can use hidden layer extract the feature. What we need to know is converting one question into another question.
		  ![image.png](../assets/image_1694232219595_0.png)
- # How to define goodness of loss function?
  collapsed:: true
	- Loss for an example
	  collapsed:: true
		- ![image.png](../assets/image_1694232504396_0.png)
	- Total Loss
	  collapsed:: true
		- ![image.png](../assets/image_1694232541961_0.png)
	- Gradient Descent
	  collapsed:: true
		- ![image.png](../assets/image_1694232646132_0.png){:height 398, :width 520}
		  ![image.png](../assets/image_1694232734452_0.png)
	- Backpropagation
	  collapsed:: true
		- in the past time, it's very difficult for the people who want to do deep learning because they need to implement the backpropagation. Now we have many tools to do the backpropagation. The reason why we need to do backpropagation is that it's efficient to calculate differential when the model's parameters is huge.
			- ![image.png](../assets/image_1694233096508_0.png)
			-
- # Why do we do the deep learning?
  collapsed:: true
	- Deeper is Better?
	  collapsed:: true
		- ![image.png](../assets/image_1694233224997_0.png)
	- There is a theory.
	  collapsed:: true
		- Any continuous function f can be realized by a network with one hidden layer (given enough hidden neurons).
		  ![image.png](../assets/image_1694233402645_0.png)
		- Why choose deep not the fat? This questions will will be answered in the following courses.
		-
- # References
  collapsed:: true
	- ![image.png](../assets/image_1694233559947_0.png)