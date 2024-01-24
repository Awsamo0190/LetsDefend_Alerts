Alert Information:

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/766419fe-e6cb-42fe-9b0a-1b5ebcbabd82)

Slides:

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/44c8d780-2ca9-4fd4-8914-d7608fe5d87b)

- Unknown or Unexpected outgoing internet traffic 

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/96b1283e-1327-462d-8ec4-b2089a78b23a)

- Not Quarantined

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/d39cf793-cb7b-4df9-8589-8dc3b395b118)

- Malicious (See Investigation Section)

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/a9e164b6-a261-4271-ba76-af2a38682aa0)

- Accessed

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/f1ee21bb-397f-4835-87e5-f3763849d5ab)


![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/f865f9a9-7f7e-423e-b160-227a0dee61e1)

- Contained
 
![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/75128032-77b5-4561-8585-a95dbd41fdbd)


 ![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/6725760d-b56f-47ef-abc1-321d969bbfa4)

Investigation: 

Downloaded file on Windows VM and opened it with Notepad in. 
 - File was obfuscated and unreadable. 

Tested File Hash on Virus Total. 
 - Hash was found to be malicious 
![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/7099c045-8bee-4077-98ae-2fe9bbceec98)


 
VirusTotal also shows Crowdsource IDS rules with potenially bad network traffic to the IP Address: 177.53.143.89

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/4cd36219-f277-4016-a73f-3f73e046237d)


![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/2427f157-5150-4c00-8cb4-8ef5e4130191)


 Log Management shows similar traffic from the host Sofia (172.16.17.56)

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/b6d9097f-1dd0-4a73-a5ec-92d5b7c7bc7f)


Log Management shows no inbound traffic from the flagged IP Address 177.53.143.89 to Sofia (172.16.17.56)

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/5f04ef47-7a94-4b47-8b93-53e91262c8d9)


Checked AnyRun for possible Sanbox view and found similar Network Traffic observed in Log Management. Which was marked as malicious. 

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/95303c2f-fbff-4630-b2e1-bb38db598f4a)


- Photo two is just a focused shot of the Connections Tab
![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/ed733b4f-4e29-42de-a1ea-a720ef85fb43)


Results: 

![image](https://github.com/Awsamo0190/LetsDefend_Alerts/assets/99389724/d5cfb4f6-5182-4471-b1ea-7bb0a6227050)

