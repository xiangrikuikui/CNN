# CNN
Olivetti Faces是纽约大学的一个比较小的人脸库，由40个人的400张图片构成，即每个人的人脸图片为10张。每张图片的灰度级为8位，每个像素的灰度大小位于0-255之间，每张图片大小为64×64。本实验所用的训练数据就是这400个样本，40个类别。
运行 python train_CNN_olivettifaces.py 可以得到相应参数所对应的CNN模型，参数就在生成的 params.pkl 文件中。
运行 python use_CNN_olivettifaces.py 可以使用得到的模型进行人脸识别。
最后测试的结果，仍然以整副 olivettifaces.gif 作为输入，得出其类别后，跟真正的label对比，程序输出被错分的那些图像。
