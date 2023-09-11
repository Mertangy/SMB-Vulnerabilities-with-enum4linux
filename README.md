# SMB-Vulnerabilities-with-enum4linux
<b>Poorly secured and managed Windows server networks are a huge security risk. Penetration testers must uncover any vulnerabilities in file and print-sharing functions that can leave an organization vulnerable to attack. In this activity, we will explore the capabilities of the <i>enum4linux</i> tool to enumerate user and file-sharing information from Samba servers. Finally, we will use the smbclient utility to transfer files between systems.</b>
## enum4linux requires root privileges. To get help on different options:
![image](https://github.com/Mertangy/SMB-Vulnerabilities-with-enum4linux/assets/19343725/989f4ca8-66d0-423f-a06c-d73f00f6b64e)
## List configured users on the target using the below command:
![image](https://github.com/Mertangy/SMB-Vulnerabilities-with-enum4linux/assets/19343725/84b92e78-f013-402a-afcb-cc8a47a8cb37)
## Get a list of file shares configured using the command <<i>enum4linux -Sv target</i>>:
![image](https://github.com/Mertangy/SMB-Vulnerabilities-with-enum4linux/assets/19343725/08a51bfc-6d6a-4fbe-826b-8866d7e2b577)
## You can use <<i> enum4linux -P target</i>> to get a list of the password policies on the target system. This will help in brute force attacks to obtain login credentials:
![image](https://github.com/Mertangy/SMB-Vulnerabilities-with-enum4linux/assets/19343725/50f50a08-4876-4f5c-a261-2922e0406f5b)
## Smbclient is a component of Samba that can store and retrieve files, similar to an FTP client. You can use smbclient to transfer a file to the target system. This simulates exploiting a network host with malware through an SMB vulnerability.
![image](https://github.com/Mertangy/SMB-Vulnerabilities-with-enum4linux/assets/19343725/fc83addc-08f2-4833-9e9c-2f7004c30ef9)



