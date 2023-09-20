# The Application
collapsed:: true
	- ![image.png](../assets/image_1694307885134_0.png)
	-
- # Example Application
	- The task introduction
	  collapsed:: true
		- ![image.png](../assets/image_1694308086743_0.png)
	- Step 1: Model
	  collapsed:: true
		- ![image.png](../assets/image_1694308298616_0.png)
	- Step 2: Goodness of Function
	  collapsed:: true
		- ![image.png](../assets/image_1694308452376_0.png)
		  ![image.png](../assets/image_1694308661145_0.png)
		  ![image.png](../assets/image_1694308809130_0.png)
		- The color is more red, the function is more worse.
		  collapsed:: true
			- ![image.png](../assets/image_1694308991235_0.png)
	- Step 3: Best Function ( Use gradient to choose it.  )
	  collapsed:: true
		- Gradient descent can solve all differentiable functions.
		  collapsed:: true
			- ![image.png](../assets/image_1694309107884_0.png)
		- The gradient descent solve detail.
		  collapsed:: true
			- ![image.png](../assets/image_1694309328860_0.png){:height 421, :width 551}
			  ![image.png](../assets/image_1694309529038_0.png)
			-
		- local minmnum ( but this don't happen on regression )
		  collapsed:: true
			- ![image.png](../assets/image_1694309642915_0.png)
		- How about two parameters?
		  collapsed:: true
			- ![image.png](../assets/image_1694309751429_0.png)
		- Featured gradient descent
		  collapsed:: true
			- ![image.png](../assets/image_1694310000364_0.png)
		- Worry?
		  collapsed:: true
			- ![image.png](../assets/image_1694310120923_0.png)
		- Formulation of $${\partial L}/{\partial w}$$ and $${\partial L}/{\partial b}$$
		  collapsed:: true
			- ![image.png](../assets/image_1694310230877_0.png)
	- How's the results?
	  collapsed:: true
		- Generalization
		  collapsed:: true
			- ![image.png](../assets/image_1694310737198_0.png)
		- Selecting another model (to get more better results)
		  collapsed:: true
			- ![image.png](../assets/image_1694311010782_0.png)
			  ![image.png](../assets/image_1694311079374_0.png)
			  ...
			  ![image.png](../assets/image_1694311292988_0.png)
			-
		- Model selection
			- train data error
			  collapsed:: true
				- ![image.png](../assets/image_1694311427759_0.png)
			- test data error (^^Overfitting^^)
			  collapsed:: true
				- ![image.png](../assets/image_1694311620656_0.png)
	- What are the hidden factors?
	  collapsed:: true
		- ![image.png](../assets/image_1694311843329_0.png)
	- Back to step 1: redesign the model (need the domain knowledge)
		- example
		  collapsed:: true
			- ![image.png](../assets/image_1694312324725_0.png)
			  ![image.png](../assets/image_1694312339971_0.png)
			-
		- results
		  collapsed:: true
			- ![image.png](../assets/image_1694312486447_0.png)
		- Any there any other hidden factors?
		  collapsed:: true
			- ![image.png](../assets/image_1694312534646_0.png)
		- don't have domain knowledge, can put all feature
		  collapsed:: true
			- ![image.png](../assets/image_1694312706295_0.png)
	- Back to step 2: regularization
		- not need to consider bias, because the bias just affect  the the function curve moving up and down. Regularization can make the model more robust. avoid overfitting, decrease the test error. the $$w_i$$ more near 0, the smaller function's input impact on the output.
			- ![image.png](../assets/image_1694315315827_0.png)
			  ![image.png](../assets/image_1694315450492_0.png)
		-
- # Conclusion & Following Lectures
	- the error will higher the test on class (Overestimate) . can be explain in validation.
		- ![image.png](../assets/image_1694315835158_0.png)
	-
-