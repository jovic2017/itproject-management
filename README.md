# IT Project Management Tools（Progress Management, Quality Management, Cost Management, Working hours Management，KPI management）

Hello Friends, 

I am Joe from China, I have more than ten years of java development experience and have the following skills:

    1.Familiar with java system development, having developed mall, chat system, gateway system, equipment monitoring system, EPR system, advertising system, banking system, etc
    
    2.Familiar with BDD automated testing, including desktop BDD, mobile BDD, API BDD
    
    3.Have some experience in mixed development of Android and IOS
    
    4.Have a project experience in desktop application development
    
    5.Be able to do daily linux system operation and maintenance
    
    6.About five years of project management experience
    
Now，I want to introduce a self-developed project management tools to you.

This is an IT Project Management Tools, Develop with Java(JKD8,SpringBoot2.2 and Mysql5.7). The functions mainly include organization management, authority management, requirement management, task management, progress management, quality management, working hour filling and statistics, weekly report, KPI setting, filling and approve. Beside, include system monitoring function and code generator module. Here is a list of all the features implemented:
![image](https://github.com/user-attachments/assets/ea6468b3-0db4-4e05-b168-0631d12b6c11)
Let's take a closer look at the specific functions of each module.


Now, let me show you how to use this system:
1. execute db/clear.sql to clear demo data
2. use superadmin login system, then create a new company, And create an administrator role for the company(Except that company management and system memus cannot be allocate to the role, others can be allocated), after create role , then create system account(aliadmin) for the company.
3. Now use aliadmin to login system, init your company data，such as department,post,employee,roles,account...

After data init

1.use Project director's account to do project planing，such as Requirement brain map,team member setting, KPI setting...

    1.1 add project in project planning(module and date planning)
  
    1.2 add project members

2.use Technical Manager's account to break down task, sprint planning, task dashboard setting, assign task...

    2.1 break down task
    
    2.2 sprint planning

3.Now, All system user can update the task progress and time spent, report your work to your leader...
    
    3.1 Enter "Update progress" from left menu, Update the progress before leaving work every day and explain what has been completed today, and report your blocking issue.


4.Weekly progress report

    You can report your work for one week, Let your leader know what you have done in the past week.
    
5.Monthly progress report(KPI)

    You can report your work for one month, Let your project manager know what you have done in the past month, your project manager will examine you on the work you have done.
    
6.Report project status to senior leaders of the company
    
    You can report project status to company senior leaders and let him/her know overall progress of the project(Enter "Project Planning" and update project progress, and then create week/month report.)
    
7.Working hours
    
    This module recored your working hours, for example: how many days are you working, how many extra hours did you work, how many hours of vacation did you take and so on.






Thanks for your reading. 

If you like this tool, you can pay some money and you will get all the source code. you can contact me through my personal email: 465230373@qq.com, or you can add my Wechat:

![image](https://github.com/user-attachments/assets/03b1eb34-1bda-426f-bbd6-c3d6a93ebed8)


