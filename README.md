使用卷积神经网络进行图像分类

使用飞桨的卷积神经网络来完成图像分类任务，使用一个由三个卷积层组成的网络完成cifar10数据集的图像分类任务

在cifar10数据集上，使用简单的卷积神经网络，用飞桨可以达到70%以上的准确率

调整batch_size至64 准确率无明显变化

调整learning rate 从0.001至0.002 准确率无明显变化
再调整至0.004 准确率出现下降现象
