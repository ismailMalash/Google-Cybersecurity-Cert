# Use a Playbook to Respond to a Phishing Incident

## Scenario

You are a level-one security operations center (SOC) analyst at a financial services company. A phishing alert was triggered when a suspicious file was downloaded on an employee's computer. The file attachment's hash was previously verified as malicious. Your task is to follow the organization's phishing response playbook to investigate the incident, evaluate the alert, and update the alert ticket with your findings.

## Requirements

- Review the phishing playbook and flowchart to understand the investigation process.
- Start at Step 2: **Evaluate the alert**, as the phishing ticket has already been received.
- Record notes and observations in the incident journal.
- Examine the alert ticket’s severity, sender information, message content, and any attachments.
- Answer the 5 W’s (Who, What, When, Where, Why) to understand the incident.
- Use Step 3 to evaluate attachments or links for malicious content.
- Decide whether to escalate or close the alert, based on your findings.
- Update the alert ticket status and include comments summarizing your investigation and decision.

## How I Solved This Activity

To solve the incident, I followed the phishing response playbook:

1. I started by evaluating the alert ticket, which included an email with an attached file named `bfsvc.exe`.
2. I checked the file's hash on VirusTotal, and it was confirmed malicious by over 50 security vendors. The file also had a very low community trust score.
3. The sender’s domain and IP were suspicious, and the message included a password-protected executable, which is a known phishing tactic.
4. Based on this evidence and following the playbook's guidelines, I escalated the alert and updated the ticket with my findings.
