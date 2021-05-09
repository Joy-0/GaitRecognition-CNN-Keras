# GaitRecognition-CNN-Keras

· loss不收敛 稳定在0.69=-ln(0.5)
1. 打印卷积层的输出是否存在NaN的情况
2. 最后一层全连接层的激活函数不应使用relu
3. 降低学习率，减小batch size
4. 加入正则化(weight decay)
5. 加入归一化层
6. 更换初始化方法(kernel initializer)
