<div align="center"> 

# StaySafe
 An advanced repo on avoiding your account getting stolen.
 
 
 This particular script bellow takes your auth-session and sends it to discord webhook through requests.
 
 # 
 
 
# Understanding Script 


Obfuscation : 

the action of making something obscure, unclear, or unintelligible.

![image](https://user-images.githubusercontent.com/96681438/210075649-ea083d35-6b2c-411b-a660-ee2595f0bda0.png)

 
 If you got the script that's OBFUSCATED, start off by looking for KEY WORDS related to account security:
 
 ``API``
 ``AUTH``
 ``SESSION``
 ``WEBHOOK``
 ``POST``
 
 ![image](https://user-images.githubusercontent.com/96681438/210075877-c879a4df-ce30-49cb-8a0f-055cd6820818.png)

![image](https://user-images.githubusercontent.com/96681438/210075943-81543c20-a188-4ba1-b976-b4e6264bc785.png)

**You can also try deobfuscating it through free services such as:** 

- [de4js](https://lelinhtinh.github.io/de4js/)

- [Simple Deobfuscation Tool](https://deobfuscate.io/)

 ![image](https://user-images.githubusercontent.com/96681438/210076192-fa0fef39-2ec3-4f61-9ddb-56e126ae2db5.png)


***This can make looking for certain key-words easier.***
 
 ![image](https://user-images.githubusercontent.com/96681438/210076362-fb76505f-bd9d-4369-96a4-9465a5ec2219.png)


![image](https://user-images.githubusercontent.com/96681438/210076377-b3395394-38f0-4945-9f7c-38e0c84e707a.png)

# Finding Webhook
 
*Create for yourself new alternative account to protect your data.*


![image](https://user-images.githubusercontent.com/96681438/210076599-c459960f-0cbe-406b-a321-c2eb8ce9116a.png)


**Inject the script through tampermonkey**

![image](https://user-images.githubusercontent.com/96681438/210076834-2bd02976-0d8b-40ab-bb68-bf33861e4534.png)

**Open up Developer Tools - Network Settings**


![image](https://user-images.githubusercontent.com/96681438/210077118-effd7ab8-df0e-4e88-a990-d58ae79de3de.png)




**Trigger the script**

![image](https://user-images.githubusercontent.com/96681438/210077042-a09ee67b-3557-4b4a-aa0c-042c1aad6e47.png)

 
 
 **Head to Network**
 
 *Spot the odd element and click on it to locate discord webhook request*
 
 ![image](https://user-images.githubusercontent.com/96681438/210077814-141d26fc-015c-4c37-9de8-ecb831ef4ab0.png)


*Copy the Request URL*

``https://discord.com/api/webhooks/ID$/$Token/``

# Deleting the Webhook

*For safety of other fools*
 
``` Method #1: ```
Use [Webhook Deleter Tool](https://github.com/venaxyt/Discord-WebHook-Deleter) made in python. 
 
 ![image](https://user-images.githubusercontent.com/96681438/210078160-70b924e1-22e3-42ab-805e-027ff9c06d8c.png)

 


 </div>
