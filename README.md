# ASMTypingGame

## 简述
这是一个用x86 MASM写的打字游戏，是我计算机组成原理与汇编课程的课程设计。

## 实现功能
老师给的要求如下：
1. 游戏开始后，从屏幕的顶部不断生成字符往下掉，值随机，位置随机。
2. 按下对应按键后，屏幕上对应的字符高亮显示
3. 按下按键后，蜂鸣器发声
4. 统计分数

我在老师的要求上做了一定的扩展，把程序写成了类似DOS窗口游戏的东西:
1. 首先有做了初始界面，游戏界面，设置界面和积分界面等界面，并提供跳转的接口。
2. 按下按键后，蜂鸣器发出有声调的声音，组合起来就是一首曲子，在设置界面提供修改的接口。
3. 提供字符生成速度和下落速度的修改，提供字符的配色选择。

## 不足于改进
这个程序还有很多可以修改的地方，比如界面可以做的更精美，音调可以调得更准等。
