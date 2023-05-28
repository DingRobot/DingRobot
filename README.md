# RobotPro

## 1 介绍

此软件是图形化的[自定义钉钉群机器人](https://open.dingtalk.com/document/isvapp/group-chat-bot-overview)消息发送软件，使用python编写

> 本来一直用postman，但是postman实现加签功能有点复杂，所以就用python写了个程序 

使用前请确保电脑已安装python<u>（python2不受支持）</u>

下载后直接运行**robotproX.X.X**即可

## 2 最新版本

### [4.6.0](https://github.com/DingRobot/DingRobot/releases/tag/v4.6.0)

#### 更新内容

1. 增加了发送消息、保存快捷机器人的键盘快捷键
   
   - 发送消息：CTRL + Enter
   
   - 保存快捷机器人： CTRL + S



## 3 软件说明

### <mark>注意</mark>

1. 此软件目前无同步更新的exe版本，需要电脑安装python才可运行

2. 此软件使用[MIT协议](https://mit-license.org/)

3. 请文明使用钉钉机器人，**不要利用该功能发送任何违规内容**！

4. 作者目前准备中考，更新会比较慢

#### 此软件使用的python第三方库：

> requests
> 
> ttkbootstrap

*venv已经包含，一般情况下不需要额外安装*

### 快捷机器人

快捷机器人功能可以让你设置三个webhook和对应的加签密匙，方便快速切换机器人发送信息

##### 逻辑

    将快捷机器人配置保存在**save文件夹**下的**save_wb.txt**和**save_sc.txt**文件中。

    *如果无法保存，可以尝试直接修改txt文件（不建议）*


