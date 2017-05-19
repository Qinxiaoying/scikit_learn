## 一、Tensorflow 中的概念  
* **_Tensor_**：张量的意思，可以理解为矩阵在tensorFlow中的表示； 
* **_Varible_**：表示tensorflow中各种计算参数， 如在模型：  
`y = Relu(Wx + b)`中，W 和 b 就是训练参数；
  * Variable必须初始化才能得到具体的值；
* **_placeholder_**：又叫占位符，用来表示输出数据的格式；
* **_Session_**：tensorflow中抽象模型的实现方法，类似于python中的类；  
## 二、Tensorflow 模型构建
