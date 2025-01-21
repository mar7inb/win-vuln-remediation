# win-vuln-remediation
Manually remediating vulnerabilities 

I created a virtual machine with Windows 10 and scanned it for vulnerabilites using Tenable. Here are the results:

![image](https://github.com/user-attachments/assets/f559ad34-9da4-42b6-a854-bdbe2bba2d6a)


Then I purposely added more vulnerabilites manually, I disabled firewall, enabled SMBv1 (SMBv1 has a number of vulnerabilities that allow for remote code execution on the target machine.), and downloaded an outdataed version of Firefox. I scanned the VM once again and here are the results:

![image](https://github.com/user-attachments/assets/2c8a599a-aa69-4e32-95ea-049b89b36cf1)


Based on these results I started the remediation process. I ran windows updates, disabled SMBv1, and uninstalled Firefox. Here are the results of the remediations:


![image](https://github.com/user-attachments/assets/082ea223-d0a2-4a04-9df1-06955621318b)


It's interesting to see how much we can minimize a computers attack surface by running latest updates, disabling certain programs, and uninstalling apps. It goes to show how important it is to keep Operating Systems and applications up to date. 
