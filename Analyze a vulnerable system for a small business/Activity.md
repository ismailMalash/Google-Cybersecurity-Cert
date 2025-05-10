# Analyze a Vulnerable System for a Small Business

## Scenario

You are a newly hired cybersecurity analyst for an e-commerce company. The company stores information on a remote database server, since many of the employees work remotely from locations all around the world. Employees of the company regularly query, or request, data from the server to find potential customers. The database has been open to the public since the company's launch three years ago. As a cybersecurity professional, you recognize that keeping the database server open to the public is a serious vulnerability.

You are tasked with completing a vulnerability assessment of the situation to communicate the potential risks to decision makers at the company. You must create a written report that explains how the vulnerable server is a risk to business operations and how it can be secured.

---

## Requirements

### Review information about the vulnerable server

- **System Description**: Evaluate components, architecture, and dependencies making up the attack surface.
- **Scope**: Define the boundaries of the assessment, focusing on data confidentiality, integrity, and availability—not physical security or related systems.

---

### Perform the Risk Assessment

#### Step 1: Explain the Purpose of the Information System
Define the server’s business value, the need for securing it, and the business impact of a compromise.

#### Step 2: Identify Potential Threat Sources
Using NIST SP 800-30 Rev. 1, identify at least three realistic threat actors relevant to the public-facing database server.

#### Step 3: Identify Potential Threat Events
Match each threat actor with a possible threat event that aligns with their capabilities and motivations.

#### Step 4: Calculate the Risk of Potential Threats
Estimate likelihood and severity for each identified threat event, then compute a risk score for prioritization.

---

### Part 3 - Propose Security Recommendations

#### Step 1: Explain Your Approach
Provide context on why the identified threats were chosen and explain their relevance to the business.

#### Step 2: Propose a Remediation Strategy
Suggest actionable security controls and strategies aligned with the risks identified. These may include MFA, least privilege, AAA framework, and other mitigation techniques.

---

## Remediation Strategy

To address the identified vulnerabilities, the following security controls and mitigation strategies are recommended:

- **Restrict Public Access**: Remove public access to the database server to reduce exposure to external threats.
- **Implement Multi-Factor Authentication (MFA)**: Require MFA for all remote employees accessing the system to prevent unauthorized access.
- **Apply Principle of Least Privilege**: Limit each employee’s access to only the data and systems necessary for their specific job responsibilities.
- **Deploy Endpoint Protection Tools**: Use antivirus, anti-malware, and intrusion detection/prevention systems (IDS/IPS) to protect endpoints from malicious software.
- **Establish a Defense-in-Depth Strategy**: Layer multiple security measures (e.g., firewalls, monitoring tools, and backups) to protect against various attack vectors.
- **Adopt the AAA Framework**: Improve access control and maintain detailed audit logs to monitor and detect suspicious user behavior.

These recommendations are designed to reduce the likelihood and impact of unauthorized access, data breaches, and malware infections.
