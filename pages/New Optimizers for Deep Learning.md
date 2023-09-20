# What you have known before?
collapsed:: true
	- ![image.png](../assets/image_1695177434324_0.png)
- # Some Notations
  collapsed:: true
	- ![image.png](../assets/image_1695176429780_0.png)
- # What is optimization about?
  collapsed:: true
	- ![image.png](../assets/image_1695176638587_0.png)
- # On-Line vs Off-Line
  collapsed:: true
	- ![image.png](../assets/image_1695176711609_0.png)
- # Optimizers
  collapsed:: true
	- SGD
	  collapsed:: true
		- ![image.png](../assets/image_1695176823723_0.png)
	- SGD with Momentum (SGDM)
	  collapsed:: true
		- ![image.png](../assets/image_1695176858564_0.png)
		- ![image.png](../assets/image_1695176980742_0.png)
	- Adagrad
	  collapsed:: true
		- ![image.png](../assets/image_1695177154377_0.png)
	- RMSProp
	  collapsed:: true
		- ![image.png](../assets/image_1695177259688_0.png)
	- Adam
	  collapsed:: true
		- ![image.png](../assets/image_1695177374971_0.png)
	- Why Momentum?
	  collapsed:: true
		- ![image.png](../assets/image_1695177072792_0.png)
- # Optimizers: Real Application
  collapsed:: true
	- Bert, Tacotron, Transformer
	  collapsed:: true
		- ![image.png](../assets/image_1695177584565_0.png)
	- YOLO, Mask R-CNN, ResNet
	  collapsed:: true
		- ![image.png](../assets/image_1695177655375_0.png)
	- Big GAN, MAML (MEMO)
	  collapsed:: true
		- memo can learn something quickly
		  collapsed:: true
			- ![image.png](../assets/image_1695177775729_0.png)
- # Adam vs SGDM
  collapsed:: true
	- ![image.png](../assets/image_1695183883397_0.png)
	- ![image.png](../assets/image_1695177884735_0.png)
	- ![image.png](../assets/image_1695177903219_0.png)
	- ![image.png](../assets/image_1695177947066_0.png)
	- ![image.png](../assets/image_1695177987769_0.png)
	-
- # Simply combine Adam with SGDM
  collapsed:: true
	- ![image.png](../assets/image_1695178174502_0.png)
- # Towards Improving Adam
  collapsed:: true
	- Trouble
	  collapsed:: true
		- ![image.png](../assets/image_1695178257597_0.png)
		- ![image.png](../assets/image_1695178375880_0.png)
	- Solve
	  collapsed:: true
		- Way 1:
		  collapsed:: true
			- ![image.png](../assets/image_1695183220939_0.png)
			-
		- Way 2:
		  collapsed:: true
			- ![image.png](../assets/image_1695183298030_0.png)
			- ![image.png](../assets/image_1695183411660_0.png)
- # Towards Improving SGDM
  collapsed:: true
	- Trouble
	  collapsed:: true
		- ![image.png](../assets/image_1695183475626_0.png)
	- Try to find a learning rate (do a experiment)
	  collapsed:: true
		- ![image.png](../assets/image_1695183507597_0.png)
	- Cyclical LR
	  collapsed:: true
		- ![image.png](../assets/image_1695183556199_0.png)
	- SGDR
	  collapsed:: true
		- ![image.png](../assets/image_1695183617670_0.png)
	- One-cycle LR
	  collapsed:: true
		- ![image.png](../assets/image_1695183726194_0.png)
- # Does Adam need warm-up?
  collapsed:: true
	- Conclusion
	  collapsed:: true
		- ![image.png](../assets/image_1695183960614_0.png)
	- Another way
		- ![image.png](../assets/image_1695184177145_0.png)
	- RAdam
	  collapsed:: true
		- ![image.png](../assets/image_1695184242724_0.png)
- # RAdam vs SWATS
  collapsed:: true
	- ![image.png](../assets/image_1695184650368_0.png)
- # K step forward, 1 step back
  collapsed:: true
	- How?
	  collapsed:: true
		- ![image.png](../assets/image_1695184985619_0.png)
	- results
	  collapsed:: true
		- ![image.png](../assets/image_1695185022377_0.png)
	-
- # More than momentum...
  collapsed:: true
	- run from the right at the beginning
	  collapsed:: true
		- ![image.png](../assets/image_1695185415201_0.png)
- # Can we look the future?
  collapsed:: true
	- What?
	  collapsed:: true
		- ![image.png](../assets/image_1695185686947_0.png)
		- ![image.png](../assets/image_1695185817675_0.png)
	- Math warning to prove if we need to maintain two parameters?
		- ![image.png](../assets/image_1695186132335_0.png)
- # Adam in the future (Nadam)
  collapsed:: true
	- ![image.png](../assets/image_1695186369724_0.png)
- # Do you really  know your optimizer?
  collapsed:: true
	- A story of regularization
	  collapsed:: true
		- ![image.png](../assets/image_1695186559801_0.png)
	- use the follow way, regularization won't affect the $$v_t$$ and $$m_t$$
	  collapsed:: true
		- ![image.png](../assets/image_1695186760200_0.png)
	- ^^L2 regularization or weight decay^^ (the most practical trick in this page)
	  collapsed:: true
		- ![image.png](../assets/image_1695186904400_0.png)
	-
- # Something helps optimization
  collapsed:: true
	- ![image.png](../assets/image_1695186997780_0.png)
	- ![image.png](../assets/image_1695187356080_0.png)
	- ![image.png](../assets/image_1695187432411_0.png)
- # What we learned today?
  collapsed:: true
	- ![image.png](../assets/image_1695187584055_0.png)
	- ![image.png](../assets/image_1695187631399_0.png)
- # Advices
  collapsed:: true
	- ![image.png](../assets/image_1695187703335_0.png)
- # Universal Optimizer
  collapsed:: true
	- ![image.png](../assets/image_1695187737117_0.png)
- [选修-深度学习新的优化器-2_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1m3411p7wD?p=21&spm_id_from=pageDriver&vd_source=4509a4938eb6aed461dbcca76232f0dc)