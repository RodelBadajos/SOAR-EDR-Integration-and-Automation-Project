# SOAR-EDR-Integration-and-Automation-Project

## Objective

The SOAR/EDR Integration and Automation Lab project aimed to develop and implement a security automation workflow using Tines (SOAR) and LimaCharlie (EDR). This involved creating custom detection rules, designing an automated incident response playbook, and successfully automating the process from EDR detection to notification and potential endpoint response.
### Skills Learned

- Development and implementation of security automation workflows 
- Provisioning and configuration of Windows VM environments for security testing 
- Deployment of EDR agents and creation of custom detection rules 
- Designing automated incident response playbooks, including workflow visualization 
- Integration of SOAR with EDR alerts as triggers 
- Utilization of Slack for user prompts and status updates in automated workflows 
- Orchestration of API calls for endpoint response 
- Incident Response Workflow 

### Tools Used


- Tines (SOAR): Used to develop and implement the security automation workflow and implement the incident response playbook. 
- LimaCharlie (EDR): Deployed as an EDR agent for creating custom detection rules and facilitating endpoint response via API calls. 
- Vultr (Cloud VM): Used to provision and configure the Windows VM environment for security testing and automation development. 
- Windows: This operating system was used in the VM environment for security testing and automation development. 
- Slack Integration: Utilized for user prompts and status updates as part of the automated incident response playbook. 

## Steps
![image](https://github.com/user-attachments/assets/c902563c-017a-4d7a-a09b-36539f10e499)




Ref 1: This flowchart illustrates a Security Orchestration, Automation, and Response (SOAR) playbook for Endpoint Detection and Response (EDR).

![image](https://github.com/user-attachments/assets/10fd73f5-00b5-4101-9f77-a8fe7a948653)
Ref 2: This screenshot displays the detection alerts that popped up when a malicious file was downloaded on the VM



![image](https://github.com/user-attachments/assets/3ad11922-665b-4c92-a72e-419b62a08606)
Ref 3: Upon detection by Lima Charlie, an alert is automatically dispatched to Slack and an email notification is simultaneously sent out.
![image](https://github.com/user-attachments/assets/147c79d0-c227-41d8-b9da-d246ccd09142)
Ref 4: Upon receiving an alert, the analyst is provided with all critical data pertaining to the affected device, along with the option to either isolate the device or decline isolation.


