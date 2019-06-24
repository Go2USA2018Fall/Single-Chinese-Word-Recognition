# Single-Chinese-Word-Recognition
## Image Processing methods Based on Opencv(Data Augmentation)
![Several Methods Based on Opencv](https://img-blog.csdn.net/20180626230235498?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzI3MjYxODg5/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
1. mean filter </br>
`cv2.blur(img, (7,7))`
2. Guassian filter </br>
`cv2.GaussianBlur(img,(7,7),0)`
3. Median filter </br>
`cv2.medianBlur(img, 5)` 
4. Bilateral Filter </br>
`cv2.bilateralFilter(img,9,75,75)`
## ResNet基本原理
#### shortcut connection
其中ResNet提出了两种mapping：一种是identity mapping，指的就是图1中”弯弯的曲线”，另一种residual mapping，指的就是除了”弯弯的曲线“那部分，所以最后的输出是 y=F(x)+x </br>
identity mapping顾名思义，就是指本身，也就是公式中的x，而residual mapping指的是“差”，也就是y−x，所以残差指的就是F(x)部分。</br>
理论上，对于“随着网络加深，准确率下降”的问题，Resnet提供了两种选择方式，也就是identity mapping和residual mapping，**如果网络已经到达最优，继续加深网络，residual mapping将被push为0，只剩下identity mapping，这样理论上网络一直处于最优状态了，网络的性能也就不会随着深度增加而降低了。**
source：</br> https://blog.csdn.net/lanran2/article/details/79057994 

![ShortCut Connection](https://img-blog.csdn.net/20180114184946861?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
