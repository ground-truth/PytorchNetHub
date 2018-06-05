# 代码注释

加入大量代码注释， 以便理解

----------

# 接下来工作
 
- Faster rcnn  源码解析
- FPN特征金字塔网络 源码解析
- R-fcn全卷积网络 源码解析
- FPN 源码解析

----------

# 注意事项
- chapter7、8项目仅供看注释，代码不完整，不能执行。
- 写代码建议参考 [原pytorch-book ][5]

----------

# 项目结构


- 总结构

  ![](http://boboprivate.oss-cn-beijing.aliyuncs.com/18-5-26/99053959.jpg)
  
  
- 项目结构

  1、定义网络
  
  ![](http://boboprivate.oss-cn-beijing.aliyuncs.com/18-5-26/16409622.jpg) 
  
   2、封装数据集
   
  ![](http://boboprivate.oss-cn-beijing.aliyuncs.com/18-5-26/38894621.jpg)
  
   3、工具类
   
  ![](http://boboprivate.oss-cn-beijing.aliyuncs.com/18-5-26/98583532.jpg)
  
   4、主函数
   
  ![](http://boboprivate.oss-cn-beijing.aliyuncs.com/18-5-26/32257225.jpg)
  



----------
# FatserRcnn实现
- 参考知乎[从编程实现角度学习FasterR-CNN](https://zhuanlan.zhihu.com/p/32404424)
- 基本理清结构，尚未完全理解
----------


# pytorch书
- dogvscat只加注释，不能运行  仅用于理解
- chapter7-GAN生成动漫头像

----------

# YOLO V1版本
- 基本实现： [pytorchYOLOv1master][2]

- 重构代码实现：[YOLOv1ByBobo][3]

- ~~目前可用，需要重构格式~~

- 模型在训练集上效果差不多，在测试集效果很不好

- 目前工作：

   1、~~抽时间重构代码，以便更容易理解~~

   2、~~仅重构完代码，效果一样~~

   3、~~需抽时间优化模型效果~~
   
   4、不再提升效果

----------


# 图像去噪论文复现

 - 实现：papersReproduced
 - 论文地址
 [基于深度卷积神经网络的图像去噪研究][4]


# FPN特征金字塔网络
- 实现：pytorch-FPN
- [原地址](https://github.com/kuangliu/pytorch-fpn) 


  [5]: https://github.com/chenyuntc/pytorch-book
  [2]: https://github.com/xiongzihua/pytorch-YOLO-v1
  [3]:https://github.com/bobo0810/AnnotatedNetworkModelGit/tree/master/YOLOv1ByBobo
  [4]: http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&amp;dbname=CJFDLAST2017&amp;filename=JSJC201703042&amp;uid=WEEvREcwSlJHSldRa1FhdXNXa0hIb3VVSnliNDU0a2dObEJYUVM1MzR2cz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4ggI8Fm4gTkoUKaID8j8gFw!!&amp;v=MTUzMzkxRnJDVVJMS2ZZdWRvRnk3blVydkJMejdCYmJHNEg5Yk1ySTlCWm9SOGVYMUx1eFlTN0RoMVQzcVRyV00=