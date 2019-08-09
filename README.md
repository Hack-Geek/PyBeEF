# PyBeEF
BeEF is short for The Browser Exploitation Framework. It is a penetration testing tool that focuses on the web browser.<br/>
BeEF Proivdes lot of command modules to perform different types of penetration testing phases.<br/>
Using the REST API proivded by BeEF, this tool (PyBeEF) is Created to perform the pentesting task automatically<br/>
PyBeEF is short for Python Browser Exploitation Framework completely designed with python programming language<br/>

### Required Python Packages
1) requests<br/>
2) tabulate

### How PyBeEF Works
PyBeEF requires Beef Server and Apache Server which has to run on the same port, by default port 3000 is taken by beef<br/>
To generate api key provide BeEF Credentials, default username and password is beef<br/>
Provide the BeEF Server and Apache Server Details<br/><br/>
![Screenshot from 2019-08-09 16-38-50](https://user-images.githubusercontent.com/53365786/62775371-13802680-bac5-11e9-8b33-609cdc066fe6.png)
<br/><br/>
This Tool provides the list of options to the user and each option performs different tasks<br/>
1) Get List of Sessions for active zombies <br/>
2) Information (Initial or Detailed) related to Online Hooked Browsers<br/>
3) Information (Initial or Detailed) related to Offline Hooked Browers<br/>
4) Get all the Logs performed by you<br/>
5) Get Browser related logs (active zombie browser) for already performed commands or action<br/>
6) Get List of Command Modules available in BeEF<br/>
7) Brief Explanation of each command module<br/>
8) Information about specific command module<br/>
9) Perform the Attack based on command module id provided by the user/attacker<br/>
10) Perform all attacks in one shot, where victim intervention is not required<br/>
11) Perform all attacks in one shot, where victim intervention is required (Use Edit_Modules.txt file to add information required for specific module)<br/><br/>
![Screenshot from 2019-08-09 16-49-21](https://user-images.githubusercontent.com/53365786/62775823-6f977a80-bac6-11e9-9d7d-0b5f2adb3c6d.png)
<br/><br/>
## Note: 
This tool is designed for the purpose of testing browsers functionalities, use tool in ethical way. The main aim of this tool is used to know about how BeEF is working in real time
