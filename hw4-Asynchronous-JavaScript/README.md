测试操作：
    在命令行进入文件夹 node server.js。
    在chrome浏览器打开 localhost:3000/S*/index.html，其中＊为1、2、3、4、5。

注意事项：
    根据提议，我的一些细节处理如下：
    1、S2,S3,S4,S5同时满足S1的所有约束条件。包括A~E5个按钮都是可以单独按下的，与@+按钮不冲突。
    2、S2,S3,S4,S5中，点击@+按钮后，应当灭活（但颜色不变），当计算出总和后，或者重置后，@+按钮重新激活。
    3、S5中，处理异常时，显示红色提示，并等待一秒以便清楚看到提示。显示正常message时，以绿色字体呈现。
    4、模拟机器人过程中，因为行为是即时的，所以按钮和大气泡背景色的变化非常快，以至于会看不到按钮恢复蓝色和大气泡变成蓝色的过程。