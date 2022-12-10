# SpeechRecognition
人机交互实验四 基于百度语音识别搭建语音识别的系统GUI

1. 登录百度语音在线识别平台，免费领取180天的语音识别接口调用权限。
2.	在应用列表创建应用以实现调用语音识别API接口的功能。可以基于应用创建成功后获取的**API ID**、**API Key**及**Secret Key**，进行接口调用操作及相关配置。
client = AipSpeech(APP_ID, API_KEY, SECRET_KEY)
3. 在python中安装实验要用到的第三方库，如下为主要用到的库：

（1）	Baidu-aip：百度面向python的语音识别框架

（2）	PyAudio：基于python的声音检测，录制麦克风声音

（3）	PyQt5:  python的GUI库，实现图形化界面

（4）	Wave： 音频操作的库

4.	编写语音识别代码：recognition.py

5.	编写GUI代码：window.py

6.	运行recognition.py，并根据GUI界面指示进行录音操作，程序会根据录音出来的音频文件将语音识别成文字，并显示在GUI界面中。

7.	选择一种进行识别的语言类型。
8.	点击“开始录音”按钮，录制一段音频。
9.	点击“结束录音”按钮，结束录音。
10.	点击“开始识别”按钮，进行语音识别，将识别出来的结果打印在屏幕上。
