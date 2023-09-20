# Review
collapsed:: true
	- do the batch before epoch
	- ![image.png](../assets/image_1694843381208_0.png)
- # Small Batch vs Large Batch
  collapsed:: true
	- Not parallel
	  collapsed:: true
		- ![image.png](../assets/image_1694843581401_0.png)
	- Parallel operation situation
	  collapsed:: true
		- ![image.png](../assets/image_1694843798421_0.png)
		- ![image.png](../assets/image_1694843991125_0.png)
		- ![image.png](../assets/image_1694844072043_0.png)
	- Small batch noisy help the training
	  collapsed:: true
		- experiment
		  collapsed:: true
			- ![image.png](../assets/image_1694844206647_0.png)
		- why?
		  collapsed:: true
			- ![image.png](../assets/image_1694844291578_0.png)
	- Small batch is better on testing data
	  collapsed:: true
		- experiment
		  collapsed:: true
			- ![image.png](../assets/image_1694844400932_0.png)
		- Flat Minima and Sharp Minima (the test data and train data have different distribution)
		  collapsed:: true
			- ![image.png](../assets/image_1694844615507_0.png)
			-
	- Comparison
	  collapsed:: true
		- ![image.png](../assets/image_1694844686235_0.png)
- # Have both fish and bear's paw?
  collapsed:: true
	- ![image.png](../assets/image_1694844744334_0.png)
- # Momentum
  collapsed:: true
	- Introduction
	  collapsed:: true
		- ![image.png](../assets/image_1694844871006_0.png)
	- (Vanilla) gradient descent
	  collapsed:: true
		- ![image.png](../assets/image_1694844927783_0.png)
	- Gradient Descent + Momentum
	  collapsed:: true
		- ![image.png](../assets/image_1694845111133_0.png)
		- ![image.png](../assets/image_1694845224180_0.png)
		- ![image.png](../assets/image_1694845286976_0.png)
- # Concluding Remarks
  collapsed:: true
	- ![image.png](../assets/image_1694845320143_0.png)