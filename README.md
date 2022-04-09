# itproject-manager.com  
# IT 项目管理工具（进度管理，质量管理，成本管理，工时统计，绩效考核）
# IT Project Management Tools（Progress Management, Quality Management, Cost Management, Working hours Management，KPI management）

Hello Friends, 
I am Joe from China, let me introduce the self-developed project management tools to you.

This is an IT Project Management Tools, Develop with Java(JKD8,SpringBoot2.2 and Mysql5.7). The functions mainly include organization management, authority management, requirement management, task management, progress management, quality management, working hour filling and statistics, weekly report, KPI setting, filling and approve. Beside, include system monitoring function and code generator module. Our website is https://itproject-manager.com/

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

    You can report your work for one month, Let your leader know what you have done in the past month, your leader will examine you on the work you have done.
    
6.Working hours
    
    This module recored your working hours, for example: how many days are you working, how many extra hours did you work, how many hours of vacation did you take and so on.






Thanks for your reading. 

If you like this tool, you can pay some money and you will get all the source code. you can contact me through my personal email: 465230373@qq.com, or you can visit website: https://itproject-manager.com/

# Our Live Demo account are:

    demodeveloper/demodeveloper

    demomgr/demomgr

