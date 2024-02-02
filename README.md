# Python-Cybersecurity-Automation-Case
> This project is inspired by Automate Cybersecurity Tasks with Python. Pleave visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

## Introduction 
There are three scenarios that I developed and modified for this project. 
* First, automate the login process with Python.
* Second, analyze the logins with Python.
* Third, use regular expressions to find patterns. 

## Scenario 1: Automate the login process

The security analyst team at XYZ Corp has asked you to automate the login process system. They require you to use python for automation. The objective is to automate the login process so the administrators do not have to approve the authentication manually.  

The following are the information you need to solve this task: 

* Approved users and devices list:

<div align="center">

| Users | Devices |
|---|---|
| keith | 789uk |
| john | jfklsdjf |
| jimmy | 9djflksf |
| sarah | 342dfsf |

</div>

* If the username matches the users list, the system will print `the user is approved`. Then, if the device id matches the devices list, the system will print `device_id is the assigned device for the users`. If the device id does not match the devices list, the system wil print `the device id is not their assigned device`. All in all, if the username does not match the users list, the system will print `the username is not approved to access the system` and the system will just print this statement without continuing to device id. 

* Please pay attention to lowercase or uppercase of the username. 

## Solution 1: Automate the login process

![VSCodium_go3t4U6SkQ](https://github.com/Kwangsa19/Python-Cybersecurity-Automation-Case/assets/135963482/5655f761-60f7-49a0-b226-eb267e0f79c4)


## Scenario 2: Analyze the logins

The security analyst team at XYZ Corp has asked you to analyze the login activities in a conditional statements. They require you to use python for automation. The objective is to analyze the login activities by printing `Current day login total for the user`, `Average logins per day for the user`, and `Alert` if the account has more login activity than normal. 

The following are the information you need to solve the task: 

* Users info

<div align="center">

| Username | Current_day_logins | Average_day_logins |
|---|:---:|:---:|
| keith | 8 | 4 |
| john | 7 | 6 | 
| jimmy | 6 | 1 |
| sarah | 9 | 2 | 

</div>

* If the `login ratio` is more than 3, the output will alert the system. `Login ratio` is current day login/average day login. 
* For this task, use the `widget` and `display`to show interactive display. 
* For curiosity, you may prepare more than one way to analyze the user logins. 
* Present your results in order: Model 1 simple solution, Model 1 Widget, Model 2 solution, Model 2 widget. 

## Solution 2: Analyze the logins

![VSCodium_nr5xTiy4QT](https://github.com/Kwangsa19/Python-Cybersecurity-Automation-Case/assets/135963482/74d9e2e2-e787-4daa-8df1-a440cc8c5413)

![VSCodium_HDOTgERsrM](https://github.com/Kwangsa19/Python-Cybersecurity-Automation-Case/assets/135963482/f7783f9c-c6fd-4774-95cd-b9a20dde4eef)

## Scenario 3: Regular expression to find patterns

The security analyst team at XYZ Corp has asked you to investigate patterns in the activities. They require you to use python for automation. The objective is to find the patterns behind it by using regular experessions. 

The following are the information you need to solve the tasks:

* Find the hex signature from this data: `The malware signature is 0x9ACDAB and needs analysis`.
* Find the device IDs that start with r15 and display the results from: `r262c36 67bv8fy 41j1u2e r151dm4 1270t3o 42dr56i r15xk9h 2j33krk 253be78 ac742a1 r15u9q5 zh86b2l ii286fq 9x482kt 6oa6m6u x3463ac i4l56nq g07h55q 081qc9t r159r1u`.  
* Find the IP adddress in the form of 192.xxx.xxx and analzye the logs. These are the logs : `eraab 2022-05-10 6:03:41 192.168.152.148 \niuduike 2022-05-09 6:46:40 192.168.22.115 \nsmartell 2022-05-09 19:30:32 192.168.190.178 \narutley 2022-05-12 17:00:59 1923.1689.3.24 \nrjensen 2022-05-11 0:59:26 192.168.213.128 \naestrada 2022-05-09 19:28:12 1924.1680.27.57 \nasundara 2022-05-11 18:38:07 192.168.96.200 \ndkot 2022-05-12 10:52:00 1921.168.1283.75 \nabernard 2022-05-12 23:38:46 19245.168.2345.49 \ncjackson 2022-05-12 19:36:42 192.168.247.153 \njclark 2022-05-10 10:48:02 192.168.174.117 \nalevitsk 2022-05-08 12:09:10 192.16874.1390.176 \njrafael 2022-05-10 22:40:01 192.168.148.115 \nyappiah 2022-05-12 10:37:22 192.168.103.10654 \ndaquino 2022-05-08 7:02:35 192.168.168.144`.
  
## Solution 3: Regular expression to find patterns 
