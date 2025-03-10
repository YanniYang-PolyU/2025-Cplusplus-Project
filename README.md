# 2025-Cplusplus-Project
This is the project for the 2025 spring C++ course in SDU

## Project Description (大作业描述)
本次作业目标：使用C++编写程序实现个人桌面助手系统

一、基本功能要求
  1. 记账本模块
     - 记录每日消费：日期（YYYY-MM-DD）、金额、类别
     - 按月统计消费：输入月份（YYYY-MM）显示该月所有消费记录及总金额
     - 数据保存：将记录保存到finance.txt文件
     - 数据显示：表格化输出消费记录（对齐列宽）
  2. 课程提醒模块
     - 添加提醒：包含时间（YYYY-MM-DD HH:MM）、事件内容、优先级（1-3）
     - 按日期查询：输入指定日期（YYYY-MM-DD）显示当天所有提醒事项
     - 自动排序：按时间顺序自动排序提醒事项
     - 数据保存：将记录保存到reminder.txt文件
  4. 密码管理模块
     - 存储密码：记录网站名称、用户名、密码（加密存储）
     - 密码查询：支持网站名称大小写不敏感搜索，显示密码明文
     - 数据保存：将记录保存到password.txt文件
  6. 文件操作
     - 添加记录时自动将记录存在相应的文件当中（如记账信息存到finance.txt中，课程提醒存到reminder.txt中，密码存在password.txt中）
     - 当启动系统时，自动加载所有文件中的记录
  PS:  我传了一个我写的系统和测试文件，不一定是最完美的，仅供大家理解以上功能。
    
二、技术要求
  1. 层次1
     - 使用C++的基础抽象和封装的概念，实现账本记录类、提醒记录类、密码记录类、以及主系统类
     - 灵活使用指针、C++标准库中的类和功能
     - 实现命令行交互界面
  2. 层次2
     - 在抽象和封装的基础上，运用继承和多态的特点，设置一个记录类基类，该类是一个抽象类，派生出账本记录类、提醒记录类、密码记录类，并展现各自特点
     - 灵活使用指针、C++标准
     - 指出你认为现有系统的设计不完善的一个点，进行功能改动或添加
     - 实现命令行交互界面
  3. 层次3
     - 在层次2的基础上，将命令行交互界面换成图形交互界面
    
三、评分标准
  - 完成层次1：获得总分的50%
  - 完成层次2：获得总分的90%
  - 完成层次3：获得总分的100%

四、作业提交要求
  - 报告1份（PDF格式，写清楚你设计系统的逻辑和系统的组件，可以辅以UML图、流程图等）
  - 代码（包括源文件、头文件等）
  - 自己代码编译、连接生成的可执行文件（一定要确保自己的可执行文件可以直接运行，到时候要演示给助教看）
  - 将以上文件打包成一个压缩文件，并以“姓名+学号+大作业”命名，发送到相应的助教处（平时实验发送的助教，记得设置邮件回执）。
  - 大作提交截止日期：6月8日晚10点！
  - 大作提交截止日期：6月8日晚10点！
  - 大作提交截止日期：6月8日晚10点！
     
