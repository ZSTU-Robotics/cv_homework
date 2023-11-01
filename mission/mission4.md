# 视觉组任务 4 识别矩形（也许是圆角矩形）
## 任务目标
在压缩包内有一张名为*mission_4.png*的图片，请识别出图片中的所有**蓝色**圆角矩形并为它们绘制最小外接矩形，并完成下列输出

- 输出绘制了所有外接矩形后的彩色原始图片。*output.png* 

为了降低难度，最右边的蓝色轮廓在本次任务中可忽略，不做进一步处理

## 任务提示
1. 使用OpenCV的颜色空间转换函数。 cv::cvtColor
2. 使用OpenCV的颜色阈值分割函数。 cv::inRange
3. 使用OpenCV的查找轮廓函数。cv::findContours
4. 使用OpenCV的最小外接圆函数。cv::minAreaRect
5. 使用OpenCV的绘制直线函数。cv::line
6. 使用OpenCV的保存函数。cv::imwrite

---

# 将源码及输出图片提交至战队邮箱
## 求求学学用PR的方式提交至GitHub仓库吧
仓库地址
```
https://github.com/ZSTU-Robotics/cv_homework
```