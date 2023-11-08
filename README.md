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

## OUTPUT:
![output 1](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/d802d4b3-e028-40ec-8681-a2010a0c78e2)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![output 2](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/a0b4bd4c-e4cd-4e09-897e-4c504220fb66)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![output 3](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/8e8eefc7-74b0-4d74-99f7-a567c8ac16b2)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![output 4](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/42c6f8a4-c9e4-441e-8e18-f35e6b9fb36b)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![output 5](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/6420cfdc-b554-4504-b6eb-5d527bf6df46)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![output 6](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/cc817167-5b9a-4baa-a5fe-6faad10a474a)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![output 7](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/b484ea5d-9cc6-43e4-9c81-de20c6c07a4a)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![output 8](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/dc0cc60a-62bd-4c62-9830-76d0b2aa4ad6)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![output 9](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/36731024-fb08-4190-a86b-4239141a3261)

SET logs the information regarding the Google credentials:

## OUTPUT:
![output 10](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/6bcf653f-8939-405f-8e77-5ab5e3e0e819)


SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![output 11](https://github.com/madhan0809/creating-a-backdoor-with-SET/assets/119165530/90ed8687-1831-474c-b600-c54f8d25d2bc)



















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
