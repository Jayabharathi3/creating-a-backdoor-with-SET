# Creating-a-backdoor-with-SET
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

![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/48965543-21aa-4d04-bf19-f810c1b47270)

### The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/e00385bf-4552-4ed0-846a-b6cec1565a84)
![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/8e27290b-7218-4307-a3e9-8ea69e9e3742)


### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected

![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/521b61a9-bc0e-4cae-97ca-350c04e3c529)


### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected

![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/cc0a2e6a-cc20-4b93-8343-600fafca5582)


### It shows the following screen in which the option Google can be selected
![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/1d064d3a-7aa3-4031-9935-ffbb4d951e06)


### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done

### In windows IE, on giving the url (http://192.168.237.134/), the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/e8be7983-157d-4e93-a80b-585e679b5ff7)


### SET logs the information regarding the Google credentials

![image](https://github.com/Jayabharathi3/creating-a-backdoor-with-SET/assets/120367796/da11945c-1df9-4c98-ba1d-55a03152cad2)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
