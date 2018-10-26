# QHtest
## 起航实验室控制组

## **人脸识别中涉及到的函数**
cv2.CascadeClassifier()

    | 正脸 | 眼部
 ---- | ----- | ------  
图像中读取| 读取图像 | 读取图像 
         | 输入xml类型文件'haarcascade_frontalface' | 输入xml类型'haarcascade_eye'
视频中读取| 调用摄像头读取图像|调用摄像头读取图像
         | 输入xml类型文件'haarcascade_frontalface' | 输入xml类型'haarcascade_eye'