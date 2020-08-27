# Online course schedule based on [NUAA_ClassSchedule](https://github.com/miaotony/NUAA_ClassSchedule) project

[中文介绍](README.md)

## Description

Log in to NUAA's new educational administration system to obtain class schedule and exam information, and parse it to generate iCal calendar and xlsx form files, and then import them into calendars such as Outlook.

The parsing generates a .js file containing the current week information of the timetable, and the front-end parses and generates an online timetable, so that viewing the timetable does not require a complicated login process.

## Disclaimer 

The data of this project is from the [NUAA educational administration system](http://aao-eas.nuaa.edu.cn/eams/login.action). Please carefully check the curriculum schedule when using it. Any problems caused by this project should be taken care of by yourself.

## Usage 

1. Fork this project. This step is very important;
2. Set four variables in setting->secrets, GIT_EMAIL, GIT_NAME, USER_NAME and USER_PWD, which are your github email address, github user name, your student number and your educational administration system password respectively;
3. Set up the Github Page service, select '/docs' as the root directory, and then visit the Page page.
4. Make sure you are not using China Unicom's network when visiting github's Page service;
5. If you have your own domain name, set your domain name to github page service so you don't have to worry about what carrier network you're using.
##Attention
1. Since the school term has not yet begun, I set the starting date to 2020.8.3, so as to facilitate debugging。
2. If you have weekend classes, click to `切换课表`.
## TODO
1. Automatically switch schedules

2. Add exam schedule