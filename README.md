# 基于NUAA_ClassSchedule项目的在线课表

## Description

NUAA_ClassSchedule  
登录南京航空航天大学新教务系统，获取课表及考试信息，解析后生成 iCal 日历及 xlsx 表格文件，进而导入 Outlook 等日历。同时，解析生成课表当前周信息的js文件，前端解析生成在线课表，从此查看课表不在需要复杂的登录流程。



### **Important!! 免责条款**

本项目课表由官方教务系统导出，但使用时 **请仔细对照教务系统核对是否所有课程均正常导出！**  

**对于解析异常导致的各种后果请自行承担！**   

 技术问题请提 issue，非技术问题原则上不予处理，请咨询有关部门，谢谢！  

>点击访问[**南航新版教务系统**](http://aao-eas.nuaa.edu.cn/eams/login.action)



## 使用 

1. fork本项目，这一步是最重要的；
2. 在setting->secrets中设置四个变量，GIT_EMAIL、GIT_NAME、USER_NAME、USER_PWD，分别是你的github邮箱、github用户名、你的学号、你的教务处密码；
3. 设置github的page服务，路径选择`/docs`,然后访问本项目;
4. 确定访问github的page服务时