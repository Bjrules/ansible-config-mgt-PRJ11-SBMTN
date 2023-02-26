#####  This  particular project intends to Improve upon the project 11 such that our codes are refactored, Also Improve the jenkins build to a directory of our choice in other to make our jenkins cleaner and consume less disk space  witht the help of 'copy artifact plugins' 

#### Banjo Babade's project 12 at Darey.io DevOps Platform

### NB project folder can be found in refactor branch of https://github.com/Bjrules/ansible-config-mgt.git 

#### PROJECT DIAGRAM

![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_231435.png)0


#### created the folder ansible-config-artifact for the artifacts and set the permission 
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_154905.png)

##### find copy artifacts under available plugins via plugin manager
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_155336.png)

#### downloading and installing the copy artifact plugins
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_155355.png)

#### configuring the artifact to work
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_155942.png)

#### configurtaions of the plugins

[label](README.md%0D) [label](IMG-SCREENSHOTS/Screenshot_20230210_155954.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230210_160427.png%0D) ![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_160833.png)
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_160846.png)

#### files were copied into the directory after a successful buld and now our Jenkins is cleaner
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_162634.png)

##### triggered an entry buy updating the read me file 
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_164306.png)
![Alt text](IMG-SCREENSHOTS/Screenshot_20230210_164236.png)

#### refactored and common-del.yml is now imported into site.yml which is to uninstalled wireshark that was installed  in project 11 on all servers
[label](README.md%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_120122.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_120058.png%0D) ![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_120041.png)

#### Create two UAT servers web1-UAT and web2-UAT
![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_121708.png)

### creating roles folder in ansible-config-mgt
![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_123905.png)

#### running ' ansible-galaxy init webserver' and then removing unwanted folders
![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_124457.png)

#### Configuring uat webserver inventory file and setting the path for roles by modifying the file /etc/ansible/ansible.cfg by uncommenting roles_path and filling in the desired details 
[label](README.md%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_124823.png%0D) ![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_125152.png)

#### writting the task command inside task/main.yml
![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_125650.png)

#### running playbooks/site.yml on inventory/uat.yml and debuging unreachable errors, ssh-agent errors etc until successful.
[label](IMG-SCREENSHOTS/Screenshot_20230214_224209.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_224222.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_224235.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_224241.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_225346.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_225523.png%0D) [label](IMG-SCREENSHOTS/Screenshot_20230214_225614.png%0D) [label](README.md)

### NB project folder can be found in refactor branch of https://github.com/Bjrules/ansible-config-mgt.git 

![Alt text](IMG-SCREENSHOTS/Screenshot_20230214_231435.png)

## DEVOPS ROCKS