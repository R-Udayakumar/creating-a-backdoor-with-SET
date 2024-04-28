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

![Screenshot 2024-04-28 130950](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/5fec8fd6-b7e3-42eb-8d4c-d78bc3d01a6f)



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/dcc9f7f6-00a2-473c-84b7-44a0d7fa17e9)



It displays the following menu and select 2 for Website Attack Vectors:

![Screenshot 2024-04-28 131139](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/6a798433-b890-4fd2-9ba7-a1a0332d61bb)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2024-04-28 131207](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/b4e4db77-8463-4ba9-960e-c79ba7188e30)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2024-04-28 131506](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/117b1a69-9daf-4148-8c19-3de85ba95425)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2024-04-28 131546](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/ac0c9e27-e6e9-4bab-b94d-1e12a5a94ee8)



It shows the following screen in which the option Google can be selected:

![Screenshot 2024-04-28 131637](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/c0738b5c-aad9-4051-ad36-6e1898dbeb6e)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-04-28 132545](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/3e635e0c-9e80-47a0-aaf8-23baf1addf07)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image (1)](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/1c452b3a-acea-4b24-bfa2-50cf6b04846b)


SET logs the information regarding the Google credentials:

![image](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/6e5df47d-4599-496c-8636-69d3691512b6)

SET logs the information in the xml file under /root:

![Screenshot 2024-04-28 151106](https://github.com/R-Udayakumar/creating-a-backdoor-with-SET/assets/118708024/bfa2995b-ef7c-4498-bb48-1e9c9ceb764c)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
