# Training stuck $$\not=$$ Small Gradient
collapsed:: true
	- Training stuck
	  collapsed:: true
		- ![image.png](../assets/image_1694845557185_0.png)
	- Wait a minute (**Training can be difficult even without critical points**)
	  collapsed:: true
		- ![image.png](../assets/image_1694845690988_0.png)
		- ![image.png](../assets/image_1694845939225_0.png)
	- Different parameters needs different learning rate
	  collapsed:: true
		- Introduction (Parameters dependent $$\sigma^t_i$$)
		  collapsed:: true
			- ![image.png](../assets/image_1694846173285_0.png)
		- Root Mean Square
		  collapsed:: true
			- How?
			  collapsed:: true
				- ![image.png](../assets/image_1694846361247_0.png)
			- Why?
			  collapsed:: true
				- The bigger $$g$$ is, the smaller $$\frac \eta\sigma$$ value is
				- ![image.png](../assets/image_1694846551633_0.png){:height 501, :width 659}
			- The disadvantage
			  collapsed:: true
				- ![image.png](../assets/image_1694846869337_0.png)
		- RMSProp
		  collapsed:: true
			- Introduction
			  collapsed:: true
				- ![image.png](../assets/image_1694847435747_0.png)
			- why?
			  collapsed:: true
				- ![image.png](../assets/image_1694847538268_0.png)
		- Adam: RMSProp + Momentum
		  collapsed:: true
			- ![image.png](../assets/image_1694847573078_0.png)
	- With Adaptive Learning Rate
	  collapsed:: true
		- ![image.png](../assets/image_1694847725931_0.png)
	- Learning Rate Scheduling
	  collapsed:: true
		- Learning rate Decay
		  collapsed:: true
			- ![image.png](../assets/image_1694847870860_0.png)
		- Warm Up (Learn more from RAdam)
		  collapsed:: true
			- Why? ()need to update around to get more information at the beginning)
				- ![image.png](../assets/image_1694848279003_0.png)
			- Have a long history
			  collapsed:: true
				- ![image.png](../assets/image_1694848112547_0.png)
- # Summary of Optimization
  collapsed:: true
	- ![image.png](../assets/image_1694848463769_0.png)
- # Learn more about optimization
  collapsed:: true
	- ![image.png](../assets/image_1694848514589_0.png)
- # Change the error surface
	- ![image.png](../assets/image_1694848560409_0.png)