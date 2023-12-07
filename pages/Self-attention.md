# Introduction( what is input? )
collapsed:: true
	- word input
	- ![image.png](../assets/image_1701919466964_0.png)
	  id:: 657139b9-d436-46bf-a7a3-e21a16de0a23
	- audio input
	- ![image.png](../assets/image_1701919595755_0.png)
	- graph input
	- ![image.png](../assets/image_1701919682040_0.png)
	- ![image.png](../assets/image_1701919730112_0.png)
- # What is output
  collapsed:: true
	- ![image.png](../assets/image_1701919899754_0.png)
	- ![image.png](../assets/image_1701920018368_0.png)
	-
- # Sequence labeling
	- ![image.png](../assets/image_1701920404395_0.png)
	- we can find the first saw and second saw is different, but only use fc can't discriminate them. To do this, we can set window to let model consider context.
	- we can't consider long sequence just using maximum window size which will create the overfitting and hard to compute. In order to complete this task, we can use self-attention
	- ![image.png](../assets/image_1701920717361_0.png)
	- the output vector is the vector considering the context
	- ![image.png](../assets/image_1701920803618_0.png)
	- we can use self-attention many times
	- ^^Attention is all you need^^ is famous paper
	- ![image.png](../assets/image_1701921019196_0.png)
	- ![image.png](../assets/image_1701921121460_0.png)
	-