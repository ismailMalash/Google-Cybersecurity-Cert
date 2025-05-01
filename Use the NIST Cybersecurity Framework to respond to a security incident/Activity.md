
# 🛡️ Activity: Use the NIST Cybersecurity Framework to Respond to a Security Incident

## 📘 Scenario

You are a cybersecurity analyst working for a multimedia company that provides web design, graphic design, and social media marketing services. The organization recently experienced a **Distributed Denial of Service (DDoS)** attack, which disrupted internal network services for **two hours**.

### 🧨 Incident Summary

During the incident, the organization’s network stopped responding due to a **flood of ICMP packets**. Investigation revealed that a malicious actor exploited an **unconfigured firewall**, allowing them to overwhelm the internal network. As a response, the team blocked incoming ICMP packets, shut down non-critical services, and restored critical ones.

### 🔧 Mitigations Implemented:

- New firewall rules limiting ICMP traffic
- IP spoofing prevention on the firewall
- Network monitoring tools for abnormal traffic
- IDS/IPS deployment to detect/filter suspicious ICMP traffic

---

## 📝 Task

Your role is to apply the **NIST Cybersecurity Framework (CSF)** to analyze the incident and develop a comprehensive security strategy. The CSF is divided into five core functions:

1. **Identify** – Assess vulnerabilities and identify affected systems.
2. **Protect** – Define policies and measures to prevent future incidents.
3. **Detect** – Implement tools to detect suspicious activity and threats.
4. **Respond** – Create a response plan for containment, investigation, and mitigation.
5. **Recover** – Plan for restoring systems and data to normal operations.

You will summarize the event and provide structured recommendations in each of these categories.

---

## 💡 My Approach

To solve this task, I reviewed the event scenario and mapped the timeline of the attack using the NIST CSF categories. I then created a practical response plan based on mitigation actions such as updating firewall configurations, implementing monitoring tools (like IDS and SIEM), and outlining procedures for response and recovery. Each step includes actionable recommendations tailored to prevent or minimize the impact of similar attacks in the future.
