# Apply OS Hardening Techniques: Brute Force Attack Incident

## Scenario

You are a cybersecurity analyst for **yummyrecipesforme.com**, a company that sells recipes and cookbooks. A former employee performed a brute force attack to gain access to the website’s admin panel using a known default password. Once logged in, the attacker modified the website’s source code by embedding malicious JavaScript. This code caused a file download prompt and redirected users to a malicious fake website (**greatrecipesforme.com**) that contained malware.

Customers reported strange behavior after visiting the website, prompting an internal investigation. The security team used a sandbox environment and packet capture (`tcpdump`) to analyze the attack flow.

## Requirements

- Identify the protocol involved in the incident using the TCP/IP model.
- Document the sequence of events and provide a detailed report of the incident.
- Recommend a security measure to prevent brute force attacks in the future.

## How I Solved This Activity

1. I analyzed the `tcpdump` log file and found that **HTTP** was the main protocol used during the attack. It handled both the website access and the malware download.
2. I documented the incident by summarizing the attack timeline, the method of compromise, and the malware behavior. I also included the DNS and HTTP traffic leading to the redirect.
3. I recommended the following security measures to increase the organization's security posture and limit future brute force attacks:

   - **Multi-Factor Authentication (MFA)** 
   - **Strong Password Policies** 
   - **Using HTTPS instead of HTTP** 

   These combined measures significantly reduce the risk of future brute force attacks.
