# AI-Virtual-Keyboard-using-OpenCV
## 基于OPENCV的手势识别键盘探索

##### 本项目全程跟随 [网址](https://www.computervision.zone/lessons/video-lesson-4/)此项目依次进行

### 心路历程

在跟随视频学习中踩了许多的坑，例如代码中的findPosition函数报错出现：

```
can't find findposition :AttributeError: 'HandDetector' object has no attribute 'findPosition'
```

这种情况是由于 cvzone 已于 2021 年 8 月 31 日使用 HandTrackingModule 更新了他们的库（您可以在[此处](https://github.com/cvzone/cvzone/commits/master)观看提交）并从 1.5.0 版起删除了 findPosition 函数。

于是可以

```
pip install cvzone==1.4.1
```

还有看教程的过程中有很多同学出现装不上medidpipe的情况，实际上清华源是可以pip下载的，不过需要

```
pip install -user medidpipe
```

![如图](https://github.com/Season111/AI-Virtual-Keyboard-using-OpenCV-/blob/main/image/123.png)
