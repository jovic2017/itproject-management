# IT Project Management Tools（Progress Management, Quality Management, Cost Management, Working hours Management，KPI management）
I am Jo from China, I have more than ten years of software development and automation testing experience.

This is an IT Project Management Tools, Develop with Java(JKD8,SpringBoot2.2 and Mysql5.7). The functions mainly include organization management, authority management, requirement management, task management, progress management, quality management, working hour filling and statistics, weekly report, KPI setting, filling and approve. Beside, include system monitoring function and code generator module. Here is a list of all the features implemented:
![image](https://github.com/user-attachments/assets/ea6468b3-0db4-4e05-b168-0631d12b6c11)
![image](https://github.com/user-attachments/assets/6b13f06b-d1e2-40c2-9381-419ff1cbea3e)





<b>Now, you can have a look at the modules one by one, and then I will show you how to use this tool step by step.</b>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/01.Organization.md" target="_blank">1. Organization module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/02.Auth.md" target="_blank">2. Auth module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/03.Requirement.md" target="_blank">3. Requirement module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/04.Task.md" target="_blank">4. Task module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/05.Progress.md" target="_blank">5. Progress module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/06.Quality.md" target="_blank">6. Quality module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/07.Cost.md" target="_blank">7. Cost module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/08.KPI.md" target="_blank">8. KPI module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/09.WorkingHour.md" target="_blank">9. WorkingHour module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/10.Developer.md" target="_blank">10. Developer module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/11.SystemMonitor.md" target="_blank">11. System Monitor module</a>
### <a href="https://github.com/jovic2017/itproject-management/blob/main/12.BasicService.md" target="_blank">12. Basic service module</a>



<br><br>
# <b>Now, let me show you how to use this system step by step:</b>
### 1. First Execute db_en/clear.sql to clear all business data
![image](https://github.com/user-attachments/assets/8b85343e-0590-43a6-8c5c-7d40e70295ea)

### 2. And the use account and password superadmin/itproject2022 to login system，Create a company called Apple Inc and assign an administrator role to the company (except for company management and system resources that cannot be assigned, everything else can be assigned)
![image](https://github.com/user-attachments/assets/bef9a004-e639-447e-84a5-512290d839b8)
![image](https://github.com/user-attachments/assets/ea4b46d2-fe85-4efd-a398-e55f179aa9d3)
![image](https://github.com/user-attachments/assets/20443240-e7f8-4d5e-9361-647c2e5b7d3e)


### 3. Logout superadmin and login account apple/apple  continue init your department,post and employee, or create other account for your colleague.
![image](https://github.com/user-attachments/assets/c67b952b-4fa7-40b7-91dd-95c5f6720c6e)
![image](https://github.com/user-attachments/assets/e8a12c50-dbf6-4fe5-91c6-3fc77f0b4485)
![image](https://github.com/user-attachments/assets/05bbc9ed-7112-4231-a2fd-698bea97ecb7)
![image](https://github.com/user-attachments/assets/4bff06f1-5903-47c1-8e23-63658e424da7)
![image](https://github.com/user-attachments/assets/622df554-f972-4aba-a2cd-2d60d27b2aca)


### 4. Project requirement, planning, task and project member settings.
![image](https://github.com/user-attachments/assets/59b8ad21-c3f9-4aff-b490-de9be5333f6a)
![image](https://github.com/user-attachments/assets/0a0482d1-f9dd-440c-8a59-7dcc8af7a0fd)
![image](https://github.com/user-attachments/assets/17548f63-1728-4f0b-9213-eb10977a3233)
![image](https://github.com/user-attachments/assets/7fb5b600-540f-4896-971c-25ae43d49db1)
![image](https://github.com/user-attachments/assets/f326c203-1c67-4a85-b382-c24b0a4b7c62)
![image](https://github.com/user-attachments/assets/7fd29326-0be2-4fa1-9ce7-0235f179c315)
Further, you also can plan the task sprint by sprint, but this step is not necessary
![image](https://github.com/user-attachments/assets/d15c2af3-1e00-4690-9cb1-ce8b992f4b53)
![image](https://github.com/user-attachments/assets/3182b1cf-81b8-4c5a-a3f4-2853916b7855)


### 5. Update task progress, create someone weekly report to his manager, create project weekly/monthly report to company boss
After you assign task to them, they begin to work on the task and fill the hours and detail, and they can report the task status to you at the weekend. Also you can report the project status to your boss(Senior management of the company).
![image](https://github.com/user-attachments/assets/1492709c-e5e7-4a77-9cd4-ef67646a771e)
![image](https://github.com/user-attachments/assets/b51723a4-013c-4c5a-899b-596a4af1b6ad)
![image](https://github.com/user-attachments/assets/fafb9e45-e3c5-44cb-9144-3122f1b3021c)
As you see, there is a common task for each project, you can fill the hour to this task such as team meeting. After filling the hours, you can export weekly report to your manager, or export to excel and send the report to your manager by email.
![image](https://github.com/user-attachments/assets/6474eb7c-5ecf-40dd-9f95-13e64b3a5c73)
![image](https://github.com/user-attachments/assets/77df2e0d-c520-46e9-934d-e224a5711587)
If you are project manager, you can update project progress status, and report the project status to your boss by week/month
![image](https://github.com/user-attachments/assets/1a69605b-92fd-4003-b7dc-3d7e6f47f243)
![image](https://github.com/user-attachments/assets/18e0136b-24cc-4abc-9e71-7c6a24c1d218)
![image](https://github.com/user-attachments/assets/25186e35-1ef3-40ac-81d2-ff0c1c7a17df)
![image](https://github.com/user-attachments/assets/9729a9ea-35f2-46d1-ba8b-8074c48badae)
![image](https://github.com/user-attachments/assets/0de50e16-3f9b-4b99-8aae-47556cc4e122)

### 6. Project quality, include test case and bug management.
![image](https://github.com/user-attachments/assets/d070f3e5-044a-455c-a540-7302336e1622)
![image](https://github.com/user-attachments/assets/78d8b2ce-76c6-4c32-a07e-e5587512e2d8)
![image](https://github.com/user-attachments/assets/3d961c98-f24b-47e6-a87a-44c7c174da8f)
![image](https://github.com/user-attachments/assets/ee3c06df-e980-41b4-b9b6-b5094834d260)


### 7. Project cost
![image](https://github.com/user-attachments/assets/6a0386bb-d3a4-4ec9-8964-e16370f213cb)
![image](https://github.com/user-attachments/assets/2a1db219-da13-4704-ba92-c2a01b30d50f)


### 8. KPI setting, submit your KPI and review
Normally, at the end of the month, you can fill your KPI, tell your manager what you do this month, and how you evaluate yourself, your manager will review it and give you finally KPI score.
![image](https://github.com/user-attachments/assets/e3945531-b7d9-43fe-a1f5-d51efe2cad2c)
![image](https://github.com/user-attachments/assets/907fbc3a-ce7d-45c8-b911-06557dc05e32)
![image](https://github.com/user-attachments/assets/710a5988-9c90-4fa7-a603-d0053e1b48bc)
![image](https://github.com/user-attachments/assets/d9eec971-9fe3-44d1-a975-67f9c166a332)

### 9. Working hours
You can apply for a leave and OT, and you can update the hours with your manager approval.
![image](https://github.com/user-attachments/assets/dfdaee9e-d901-4ff9-bdbb-215c3c340425)
![image](https://github.com/user-attachments/assets/ed4fc4d4-b4d7-45d1-a83d-1bb5524f4e1a)
![image](https://github.com/user-attachments/assets/56e3e2a1-700b-4c79-9b4d-49bed5cec506)
After your manager approve your leave and ot application, you will see your working hour as below, and you can submit it for approval.
![image](https://github.com/user-attachments/assets/5a30a918-35ac-4708-920a-be992db7957d)


### 10. Developers


# <b>If you like this tool, you can pay some money and you will get all the source code. you can contact me through my personal email: 465230373@qq.com</b>
# <b>Or you can add my Wechat</b>

![image](https://github.com/user-attachments/assets/be5f87af-e68b-4694-bd7c-c663d95a5216)

# <b>Or you can add my Skype</b>

![image](https://github.com/user-attachments/assets/6905b386-1c9e-461b-84c4-5fb166ce8311)

# <b>Or you can add my Alipay</b>

![image](https://github.com/user-attachments/assets/abb56971-c356-4a51-b44c-be8f8b441995)



