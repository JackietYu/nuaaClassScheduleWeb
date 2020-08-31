# 基于NUAA_ClassSchedule项目的在线南航课表

[English  introduction](README_EN.md)

## 介绍

本项目的爬虫基于[NUAA_ClassSchedule](https://github.com/miaotony/NUAA_ClassSchedule)简单修改开发，感谢[@miaotony](https://github.com/miaotony)大佬的开源。

此项目的基本功能：登录南京航空航天大学新教务系统，获取课表及考试信息，解析后生成 iCal 日历及 xlsx 表格文件，进而导入 Outlook 等日历。同时，解析生成课表当前周信息的js文件，前端解析生成在线课表，从此查看课表不在需要复杂的登录流程。



### 免责条款

本项目课表由官方教务系统导出，但使用时 **请仔细对照[**南航教务系统**](http://aao-eas.nuaa.edu.cn/eams/login.action)的课表，核对所有课程是否正常导出！对于解析异常导致的各种后果请自行承担！**   

## 使用 

1. fork本项目，这一步是最重要的；
2. 在setting->secrets中设置四个变量，GIT_EMAIL、GIT_NAME、USER_NAME、USER_PWD，分别是你的github邮箱、github用户名、你的学号、你的教务系统密码；
3. 设置github的page服务，路径选择`/docs`,然后访问本项目;
4. 确定访问github的page服务时，你不是用的联通的网络；
5. 如果你有自己的域名，最好能设置你自己的域名为page的域名，这样就不用考虑使用的是什么运营商的网络了。
##注意
1. 由于目前还没到开学时间，因此我把起始日期设置成了2020.8.3；
2. 如果你的课表有周末的课程，请点击切换课表。
## TODO
1. 自动切换课表

2. 添加考试安排