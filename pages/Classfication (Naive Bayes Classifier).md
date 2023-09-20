# Introduction
collapsed:: true
	- ![image.png](../assets/image_1694408637773_0.png)
- # Example Application
  collapsed:: true
	- example introduction
	  collapsed:: true
		- ![image.png](../assets/image_1694408778867_0.png)
		-
	- Features (use vector to describe them)
	  collapsed:: true
		- ![image.png](../assets/image_1694408907886_0.png)
	- How to do Classification?
	  collapsed:: true
		- Classification as Regression (the function for the Regression is not suitable for Classification
		  collapsed:: true
			- ![image.png](../assets/image_1694409025156_0.png)
			  ![image.png](../assets/image_1694409314304_0.png)
			-
		- ideal Alternatives
		  collapsed:: true
			- ![image.png](../assets/image_1694409480675_0.png)
	- Two classes
	  collapsed:: true
		- introduction
			- Bayes formula
				- ![image.png](../assets/image_1694409797467_0.png)
			-
		- Prior
		  collapsed:: true
			- ![image.png](../assets/image_1694409963005_0.png)
		- Gaussian Distribution
		  collapsed:: true
			- ![image.png](../assets/image_1694410419422_0.png)
			  ![image.png](../assets/image_1694410431592_0.png)
		- Probability from Class - Feature
		  collapsed:: true
			- ![image.png](../assets/image_1694410288344_0.png)
			  ![image.png](../assets/image_1694410330985_0.png)
			- ![image.png](../assets/image_1694410524865_0.png)
		- Maximum Likehood
		  collapsed:: true
			- ![image.png](../assets/image_1694661140587_0.png)
			-
		- Now we can do classification
		  collapsed:: true
			- ![image.png](../assets/image_1694661290179_0.png)
		- Example
		  collapsed:: true
			- ![image.png](../assets/image_1694661516427_0.png)
			-
	- Modifying Model
	  collapsed:: true
		- different distribution can share the same  $$\sigma$$, and this operation can decrease the number of parameters. We can see the conclusion proof in the Ref: Bishop.
			- ![image.png](../assets/image_1694662185628_0.png)
		- compare the results between the same $$\sigma$$ and different $$\sigma$$ ( the way to share the same $$\sigma$$ is Liner boundary )
		  collapsed:: true
			- ![image.png](../assets/image_1694662398047_0.png)
	- Three steps
	  collapsed:: true
		- ![image.png](../assets/image_1694662570342_0.png)
	- Probability Distribution
	  collapsed:: true
		- the different feature $$\sigma$$ is also important that can't be ignore.
		- ![image.png](../assets/image_1694662860987_0.png)
	- Posterior Probability
	  collapsed:: true
		- Math warning
		  collapsed:: true
			- ![image.png](../assets/image_1694696319029_0.png)
			- ![image.png](../assets/image_1694696348346_0.png)
			- ![image.png](../assets/image_1694696364359_0.png)
			- ![image.png](../assets/image_1694696400210_0.png)
			-