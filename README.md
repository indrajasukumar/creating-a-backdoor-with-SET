# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:



![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/824d4c33-2189-480e-aadd-08e196c23b51)

It displays the following menu and select 2 for Website Attack Vectors:


![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/b028fb45-6e41-49b3-b252-e152b89c67d8)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:



![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/acfdde59-94a0-4224-aafa-12f6ae98b46a)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:


![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/260de18a-c5e3-4e42-909b-1b3468cbae91)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:


![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/dd4b726b-b4cc-4bfd-b287-f9d8ff0feeff)

It shows the following screen in which the option Google can be selected:


![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/e85c8555-581a-4b90-bb42-11069320e631)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: image

![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/636eae38-75d7-4be6-90ed-2948101efe49)

In windows IE, on giving the url http://192.168.43.135, the fake Google page is displayed. The victim can enter the username and password: image

![image](https://github.com/indrajasukumar/creating-a-backdoor-with-SET/assets/145115195/0353f471-04af-4f09-90e4-23548f88e3ac)

SET logs the information regarding the Google credentials: image





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
