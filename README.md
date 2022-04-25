# DEVOPS-INTERVIEW-QUESTIONS
THIS SHEET CONTAINS QUESTIONS AND ANSWERS ASKED IN A DEVOPS INTERVIEW


Telephonic interview-7
 
- Where to store the global credentials in jenkins??
- For example, I have to set global creds for GIT. 
How to achieve that thing in jenkins???
- Revise how you did GIT AND JENKINS INTEGRATION ??
 
2. Can you override user passwords credentials for a git repo. In jenkins under git integration??
Can we do that on a job level??  Or admin is needed for this 
task ???
 
3. Is there a mechanism available in the jenkins on a job level how this upper part can be achieved??
 
4. 2 diff repos one is svm repo and git repo. You have to take code from both and then do a compilation and create a single build… Can we achieve this ????
Do we have an option to select or have a git and svn repo selected at the same time in a single job??
 
5. Can you use multiple git repos in a single jenkins job??
Can we do it one for svm and one for git??
 
6. Are you comfortable with ANT?
 
7. For maven can you explain the architecture of Maven and how maven works??
What is the heart of maven??
-pom.xml file usage in maven.
Steps to configure maven with jenkins. 
-Assigning path of Java_home and M2 in maven. Etc.
- Role of setting .xml in Maven???
- Can a build happen without a pom.xml file in Jenkins and maven??
-Concept of setting .xml

 
AWS:


8. Created oneAMI INSTANCE. Took a snapshot template. Deleted the snapshot, Can we create an instance with that AMI. 
Snapshot deleted…. 
 
- Snapshot deleted for that instance. Can we use that instance to launch a new instance???
When was the snapshot deleted??
 
9. Where does the VPC come into picture in AWS???
- Can you change the vpc. 
After creation of an instance ??
- Where does VPC belong?? Belongs to region or something else??
 
- Can we communicate with 2 VPCs ??
-What is VPC peering??
 
10. What is S3??
- Object level storage.
 
11. What is Ec2??
 
12. How many type of storage services does AWS provide?
EFS S3 Glacier ELB.
 
13. What is Route53??
Use Cases of Route53??
GIT:
 
14. I am merging 2 sub branches and getting a “Merge Conflict” in that. How to handle Merge conflicts error???? 
Can I achieve this with CLI or GUI??
 
15. Do you know about Configuration management tools??
Chef puppet ansible..
- In ansible you have multiple nodes having diff versions of python..
What steps do you need to follow to work all your nodes in a single snapshot???
Like any command you have to run on all the nodes???
- I guess we have to bring them all on the same python version for the connection..
 
16. There is a key change on one of your nodes. Ssh key is changed for one of your nodes. What steps do you need to take to connect it again????
 
17. Diff between WAR FILE AND EAR FILES??
 
 
Does tomcat support ER ENTERPRISE ARCHIVE files??
 
WHICH APP SUPPORTS ER FILES?
Which Application servers support it. Weblogic?
 
18. In a single tomcat instance how many Catlina I can have or create??
 
19. Can I create 2 applications on the same tomcat instance????
New application with the same names??
Can we direct them to different ports? To resolve this??? Or is it completely impossible??
 
20. What is JVM?
Java virtual machine. 
 
21. App running in tomcat and it is utilising 100% memory. You have allocated extra memory on the server.
And now you have to extend your app tomcat memory as well. Where you will have to make those changes????
 
- Ram not storage.
 
22. What is the log file name for tomcat???
Default name ??
 
23. Can we have 2 diff middleware like TOMCAT and WEBSPHERE on a single machine??? Or weblogic…
 
Where exactly we will need to do the settings. 
Can both work/executed parallelly?
 
24. If we have to provide security of a particular application. What are the things we will consider? Secure open application. 
Tomcat for security…???
Question was a bit confusing. It was in general a sec question or related to tomcat didn’t get that. Search for both the cases.
 
25. Can we set some kind of https setting for opening an app or a url??
- it is there by default. 
- Can we change it
 
26. How comfortable you are with shell scripting ??
Perl and shell scripting??
 
27. How comfortable with Linux?
 
28. Suppose you have to find. No of files or processes by a particular PID how will you find out ??
No of files used by a particular user??
 
Over.




 
============================
 
Devops interview 8:
 
1. Can you explain about your current roles and responsibilities? 
Which company are you working with??
What tools for configuration management??
Version control system tools you are using? 
Sprint what is it?
- Ansible ? 
 
2. What type of playbooks have you written in Ansible??
What automation did you do using Ansible playbooks in your current role??
 
What is backup utilities in ansible/git
- playbook to install apache tomcat for developers.
 
3. Have you worked on any CI CD TOOLS?


-Can you explain the integration of Jenkins with GIT? 


How is this achieved?
- Continuous integration??
-What build tool are you using?
- Do you know about J-Unit?
- How to establish an ssh channel between git and Jenkins?
- maven: targets java home and m2 path setups. How is this done?
-Post build activity ?
- Console output role in Jenkins?
- What is Artefact?



 
4. Any experience you have with Databases?
- RDS 
- Installing SQL database?
- Retrieving data using SQL.
 
5. What about bash scripting ?
- Continuous Deployment using Ansible.
- Taking artefacts and deploying it on end servers.
 
6. Do you have any programming knowledge?
Most of my experience: Implementation and automation.
 
===========================
 
DEVOPS INTERVIEW 9:
 
1. What is a version control system?
What is GIT PULL?
What is the difference between GIT PULL & GIT UPDATE? 
 
2. I HAVE 10 commits in my repo. And I do a GIT PULL. So what would happen in this case. How will you resolve this?
- How will you resolve this conflict??
 
3. Have you used any tools for checking code quality?? 
- find bugs etc. 
- Sonarqube
- How do you integrate sonarqube with Jenkins?
 
4. I have multiple projects in my GIT repo. All of them have their own pom file. 
I want to pull the code from this repo and build it on the GIt server. 
The code will be deleted once build is done. 
How will you achieve this?
 
5. Poll scm. What is it?
Post commit scripts. 
 
6. What are post commit cooks in GIT?
 
7. In github have you automating the code review process?? 
Sonarqube??etc
Gerrit for code review. 
 
8. Helm with jenkins. 
If i want to enforce developers. How is the coding standard set on sonarqube?
 
9. Do you have any exposure in managing any Big Data projects??
 
10. Which tools have you used for configuration management:
>>Chef rundeck ansible puppet…
 
11. Any exposure using the containers??
—Docker image??
- Are you Using private images or public images??
— Who creates docker images in your organisation.
— Docker Hub is a public one.
 
12. For example if I want to configure my env. Are you creating your own images or taking docker images from the docker hub??
 
13. Are you creating your own docker images? 
In dockerfile we input the reqs
 
14. Why do you want to switch this job?
-More exposure to other technologies.
 
15. Vaxaxy technologies project important for interview. 
Source code committed, the pipeline should directly perform the deployment without any manual interpretation. 
 
16. Are you familiar with the Java or dev languages??
 
17. How to fix errors in Maven? How to perform troubleshooting on Maven errors??
 
18. Prepare documentation of each and every issue and how it was implemented from scratch???
Performing documentation on what devops tasks were performed and how they were performed??
 
19. Kubernetes or docker?
 
==========================
 
DEVOPS INTERVIEW-10:
INFOSYS
 
1. How will you define DEVOPS? 
Its a methodology.
 
2. What all tools have you used in DevOps?
 
3. Vagrant VM.. what is this?
 
4. Ansible configuration tool.
-EC2 setup
- Normal day to day tasks. 
 
5. Are you comfortable with windows or linux?
 
6. How do you rate yourself in Jenkins?
User administration
Master slave configuration for load balancing. 
Plugins
How to make a job from scratch. 
 
7. Installation procedure of jenkins?
What are ways we can install jenkins????
 
8. How to change the port of jenkins ? Can we do that ??
>>answer in documents i created.
>> install apache web server 
In opt directory you put your jenkins file. Google for other ways of doing this thing. 
 
 9. Jenkins plugins used. Tell me about 5 plugins you have used while working in your organisation??
- Green balls plugins.
- GIT, ANSIBLE,MAVEN,AWS PLUGINS, docker plugins, Nexus.
 
10. In what directories will you have your jenkins passwords saved??
 
11. You have 2 jobs in jenkins.  You want to add parameters so that after one is completed another will start….
How to achieve that in Jenkins??
 
12. What is the use of Poll Scm?? Is it used for parameter passing??
 
13. One single job in jenkins and you want to hedge code from svn repos in a single job.. is it possible ??
Or else in git is it possible ??
 
14. Are you aware of any built in variables in Jenkins??Can you name a few of them?
 
15. Have you worked in the APIs of jenkins?? Do you know any of them??
 
16. Jenkins installed on some machine and you DON’T have access to that machine. 
You have to restart the Jenkins after installing the plugin.. How can you do that ??
 
Can you do it from the browser/ jenkins link ??
 
17. Can you explain why we use upstream and downstream jobs in Jenkins. And have you created any such jobs?
 
18. What work have you done in Jenkins??
What all pipelines or freestyle jobs have you performed in your current role????
 
19. What are Artefacts and warfiles?? 
 
20. If you want to configure a devops pipeline. When a user or developer commits into a GIT repo. The job will be triggered for this. 
Only poll scm can resolve this ? 
Or can we achieve this while creating the job itself?? YES
 
 
21. What is your level of comfort in Maven??
- Pom.xml file
 
22. What are the life cycles of Maven?
Clean package etc. there are almost 7-8 steps in its cycle..
 
23. What is the mvn package and mvn install??? What is the difference between them? 
When you mention them in the jenkins job what do they do ???
 
GIT:
 
24. Is GIT A CENTRALISED OR DISTRIBUTED??
 
25. What are  the advantages of GIT OVER ANY OTHER TOOL IN THE MARKET OR SVN tool??
 
26. Diff between SVN and GIT VERSION CONTROL SYSTEMS. 
 
27. What is the use of hooks?
 
28. Configure an email id on GIT. How to set the global user and set password on cmd.
 
29. What is the term Merging called ? When will it be done??
 
30. What is the use of tags in GIT? When do we use tags in GIT.
 
31. Apache and griddle.maven what are these tools??
Griddle for java application.
 
32. Docker. 
What is the http port for docker daemon?
 
33. If you want to get the metadata of the running docker container. Which command will you use for this??
What fields will we get in this ???
 
34. If you want to execute some command to the running docker container? How will you do that ??
Run command
Docker exec - it <contid>
 
35. What is the difference between  -i  and  -p commands in DOCKER??? Tell me any 5 Docker commands.
 
 
36. Have you used Docker swarm ?
You need to know the basics of this one as well. 
Although it is not used that much these days.
 
37. How will you create a data source in JD ENV?
1521 def port no.




 
38. Vagrant and Ansible:


Ansible level of understanding??
- Configuration??
- what are Ad Hoc commands
- Format of Ansible file? .yml
- What are the variable tags you have used while writing Ansible Playbooks???
 
Need to know the important fields in Ansible playbook & best practices related to Ansible playbooks.
 
39. What are the advantages of Ansible against puppet and chef???
 
40. Dry run of your playbook? What is the command for that ?
 
41. If you want to change the url from where you fetch the artefacts. So which file will you change the label ??
 
============================
