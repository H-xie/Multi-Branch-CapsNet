# 多分支结构强化表征能力的CapsNet方法

谢海闻, 叶东毅, 陈昭炯
(福州大学 数学与计算机科学学院, 福州 350108)


**中文摘要**: CapsNet是一种新的目标识别模型，通过动态路由和capsule识别已知目标的新形态.针对CapsNet的解码器输入层规模随类别数增加而增加，可延展性较弱的问题，本文提出多分支自编码器模型.该模型将各个类别的编码分别传递给解码器，使解码器规模独立于类别数，增强了模型的可延展性.针对单类别图像训练多类别图像识别任务，本文增加新的优化目标降低非标签类别的编码向量对解码器的激励，强化了模型的表征能力.MNIST数据集的实验结果表明，多分支自编码器具有良好的识别能力且重构能力明显优于CapsNet，因而具有更全面的表征能力.
中文关键词: 目标识别 ； 目标重构 ； CapsNet ； 表征提取 ； MNIST


# Multi-Branches CapsNet Method with Enhanced Representation Capability
XIE Hai-Wen, YE Dong-Yi, CHEN Zhao-Jiong
(College of Mathematics and Computer Science, Fuzhou University, Fuzhou 350108, China)


**Abstract**:A novel neural network for object recognition, CapsNet, uses dynamic routing and capsules to recognize novel state of a known object, while the input layer of CapsNet decoder increases when the number of categories increases, which means a relatively limited scalability. To overcome this weakness, we propose the Multi-branches Auto-Encoder (MAE) which gives coding vectors of every class to the decoder respectively letting the scale of decoder independent from the number of categories enhancing the representation capability of the proposed model. The experiment on MNIST shows that MAE is competitive in recognition and more powerful in reconstruction which means a more complete capability on representation.
keywords: object recognition ; object reconstruction ; CapsNet ; representation extracting ; MNIST
