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
![ShortCut Connection](https://img-blog.csdn.net/20180114184946861?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
