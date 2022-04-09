# itproject-manager.com

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

3.Now, All system user can update the task progress and time spent, report your work to your leader...
