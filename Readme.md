<!-- <a  style="display:block;text-align:center;" href="https://www.jste.net.cn/uids/index.jsp"><img src="https://www.jste.net.cn/uids/skin/css/light/images/login_main.jpg" alt="江苏教师教育" height="200"></a> -->

<!-- ![](https://www.jste.net.cn/uids/skin/css/light/images/login_main.jpg) -->

<p align="center">
<a href="https://www.jste.net.cn/uids/index.jsp">
<img src="https://www.jste.net.cn/uids/skin/css/light/images/login_main.jpg" alt="江苏教师教育" height="256">
</a></p>

- [jsjsjy\_ACC\_v2.4.4](#jsjsjy_acc_v244)
- [简介](#简介)
- [主要功能](#主要功能)
- [使用说明](#使用说明)
  - [运行](#运行)
  - [使用](#使用)
- [更新日志](#更新日志)
- [注意事项](#注意事项)
  - [注意事项](#注意事项-1)
  - [系统要求（运行环境）](#系统要求运行环境)
  - [特别说明](#特别说明)
- [声明](#声明)
- [其他](#其他)
  - [关注](#关注)
  - [打赏](#打赏)

# jsjsjy_ACC_v2.4.4

# 简介
欢迎您使用江苏教师教育ACC（Auto Cut Class）系统（以下简称“本软件”）。  
本软件利用 **python3** <a href="https://www.python.org/"><img src="https://www.python.org/static/img/python-logo.png" alt="python" height="40"></a> 语言编程、**Visual Studio Code** <a href="https://code.visualstudio.com/"><img src="https://img.sj33.cn/uploads/202106/7-210621202634K8.jpg" alt="vs code" height="40"></a>（简称“VS code”）为工具开发的一个自动化脚本。

# 主要功能
只需要输入账号和密码并按回车，将自动登录并自动ACC。

# 使用说明
## 运行
将下载的程序释放至本地，运行根目录下 `jsjsjy_ACC_v2.4.4.exe` 文件。

- [下载地址1](https://github.com/Sam-CXM/jsjsjy_ACC/releases/tag/jsjsjy_ACC_v2.4.4)
- [下载地址2](https://www.aliyundrive.com/s/bEgTa93stwX
"提取码: zj69")   

![start](image/start.png)

## 使用
根据提示输入账号和密码，按回车键 `Enter` 键即可。

# 更新日志
- [x] 版本：v13.4   日期：2023/04/21  
  - 【优化】bug修复

- [x] 版本：v13.0   日期：2022/11/25  
  - 【新增】在线验证运行环境，如果环境异常则修复
  - 【优化】其他bug修复

- [x] 版本：v12.0   日期：2022/11/20
  - 【新增】头部提示
  - 【优化】开始运行函数顺序调整
  - 【优化】**秒后进入下一课改为时间进度条
  - 【优化】代码精简

- [x] 版本：v11.0   日期：2022/11/17
  - 【新增】对网站错误的判断，传递相应的输出信息
  - 【优化】判断已播放视频逻辑，播放完点击弹窗中“确定”进入下一节课
  - 【优化】验证码识别判断逻辑
  - 【优化】修改验证码图片路径为：D:\codePic.png

- [x] 版本：v10.0   日期：2022/11/16
  - 【优化】输出界面美化
  - 【优化】导入第三方库的优化，方便后期打包

- [x] 版本：v9.0   日期：2022/11/16
  - 【新增】判断播放下一课时逻辑
  - 【优化】动态获取课程数量  
  ~~【删除】第三方库的安装函数~~

- [x] 版本：v8.0   日期：2022/11/16
  - 【新增】获取已学视频时长
  - 【优化】判断验证码图片是否存在

- [x] 版本：v7.0   日期：2022/11/14
  - 【优化】安装第三方库逻辑

- [x] 版本：v6.0   日期：2022/11/13
  - 【优化】计算时长逻辑
  - 【优化】其他未知bug

- [x] 版本：v5.0   日期：2022/11/13
  - 【新增】交互安装第三方库
  - 【优化】封装全部函数体
  - 【优化】其他未知bug

- [x] 版本：v4.0   日期：2022/11/13
  - 【新增】判断是否正确登录
  - 【优化】webdriver打开优化，用with语句
  - 【优化】封装全部函数体
  - 【优化】其他未知bug

- [x] 版本：v3.0   日期：2022/11/12
  - 【新增】识别验证码并填入
  - 【优化】封装函数体
  - 【优化】隐藏一些不重要的错误

# 注意事项
## 注意事项
本软件运行时请保持网络流畅，运行过程中尽量 **不要操作** 自动打开的网页，否则可能出现错误。如果出现错误导致异常退出，请重新打开本软件。

## 系统要求（运行环境）
|           系统           |        磁盘        |   浏览器   |
| :----------------------: | :----------------: | :--------: |
| Windows10/Windows11 64位 | 至少需要320M的空间 | Edge浏览器 |

## 特别说明
软件有时会出错导致异常退出，大多数是因为Edge浏览器版本升级导致 `msedgedriver.exe` 文件失效。**解决方法**：请重新运行本软件，根据提示操作即可。

# 声明
本软件 **非盈利且开源** 仅用于学习交流，版权归第三方作者所有，***请勿用于商业用途***。

# 其他
在使用过程中如果您有任何问题可以将 **错误截图** 加 **问题描述** 发送至邮箱 3038693133@qq.com。
同时欢迎您对本软件提出意见或建议，将 **描述** 发送至邮箱 3038693133@qq.com。

## 关注
![关注](image/CXM-Studio.png)

## 打赏
![打赏](image/QR.png)
