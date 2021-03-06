
--------------------------
|学号|班级|姓名|照片|
|:-------:|:-------------: | :----------:|:---:|
|201510414410|软件(本)15-4|刘俊成||

实验六 ：基于GitHub的实验管理平台的分析与设计
------------

## 1. 概述
- 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB
页面上。
- 学生的功能主要有：选择自己的课程，设置自己的GitHub用户名，查询自己的实验成绩。学生的GitHub用户名是公开的，但成绩不公开。
- 老师的功能主要有：发布实验，批改每个学生的成绩，查看每个学生的成绩。
- 管理员的功能主要有：录入院系、班级、课程信息，管理教师、学生信息，导入学生（教师）与课程的对应关系。
- 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
- 实验成绩按数字分数计算，每项实验的满分为100分，最低为0分。
- 系统自动计算每个学生的所有实验的平均分。

## 2. 系统总体结构
![](./img/xitong.png)



## 3. 用例图设计 [源码](./src/用例图.puml)
![](./img/yongli.png)

## 4. 类图设计 [源码](./src/类图.puml)
![](./img/leitu.png)

## 5. 数据库设计
- ### [参见数据库设计](./数据库设计.md)

## 6. 用例及界面详细设计

- ### [“登录”用例](./yongli/登录.md),[界面](https://987413629.github.io/is_analysis/test6/ui/login_html.html)
- ### [“登出”用例](./yongli/登出.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“查看用户信息”用例](./yongli/查看用户信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“修改用户信息”用例](./yongli/修改用户信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“修改密码”用例](./yongli/修改密码.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“录入班级信息”用例](./yongli/录入班级信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入课程信息”用例](./yongli/录入课程信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入学生信息”用例](./yongli/录入学生信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入教师信息”用例](./yongli/录入教师信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“录入院系信息”用例](./yongli/录入院系信息.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“学生所修课程导入”用例](./yongli/学生所修课程导入.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“教师所授课程导入”用例](./yongli/教师所授课程导入.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-admin_html.html)
- ### [“发布实验”用例](./yongli/发布实验.md),[界面](https://987413629.github.io/is_analysis/test6/ui/publishtest_html.html)
- ### [“成绩录入”用例](./yongli成绩录入.md),[界面](https://987413629.github.io/is_analysis/test6/ui/correct_html.html)
- ### [“打印成绩”用例](./yongli/打印成绩.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“选择学期”用例](./yongli/选择学期.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“学生列表”用例](./yongli/学生列表.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-teacher_html.html)
- ### [“课程列表”用例](./yongli/课程列表.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
- ### [“查看成绩”用例](./yongli/查看成绩.md),[界面](https://987413629.github.io/is_analysis/test6/ui/index-student_html.html)
