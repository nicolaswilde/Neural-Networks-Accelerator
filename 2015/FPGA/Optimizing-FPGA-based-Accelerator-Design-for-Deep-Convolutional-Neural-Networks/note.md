### Optimizing FPGA-based Accelerator Design for Deep Convolutional Neural Networks

最早使用了roofline model？计算了很多访存和计算的数据，比TPU早诶。。。

结构跟DianNao很像。

![Architecture](./1.PNG)

对卷积层的循环安排不同的顺序和tiling大小，最终选取下图b中C点作为最终设计。

![Design Exploration](./2.PNG)
