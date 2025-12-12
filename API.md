# 什么是API？
1. API（Application Programming Interface)：应用程序编程接口
	1. 例如：编写程序去控制机器人各种行动，机器人产商一定会提供一些用于控制机器人的接口类，这些接口类定义了操作机器人各种动作的方法，就是提供给应用程序编程的的接口，也就是API。
	2. 对API的学习就是学习别人提供的类并学会调用（比如之前使用过的Scanner）
	3. Java的API集合在Java帮助文档
	4. 类在Java lang包下是不需要导包的（核心包）
	5. 实例即是对象的意思
# 窗体结构介绍
1. getContentPane()组件集合的方法（按钮、图片、文字都算组件）
2. 窗体对象.getContentPane().add(放这);--通过这个格式使用，称之为链式编程，比如stu.getStudent().getName();
3. 组件进入窗口后就被设置成默认布局，需要先取消--setLayout(null)；
# Jbutton
1. 构造方法：
	1. JButton();//空参构造
	2. JButton(String text);//创建一个带文本的按钮
# JLabel
1. 用于展示文本和图片（图片不能独立存放）
	1. JLabel();
	2. JLabel(String text);
	3. JLabel(Icon image);
2. JLabel对象就是一块区域
3. 多个组件摆放在同一个位置，后添加的组件会被压在底部
# 2048数字展示
1. 
# 石头迷阵界面分析
