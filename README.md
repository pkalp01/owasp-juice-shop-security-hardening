# OWASP-Juice-Shop
Analyzing OWASP Juice Shop deployment YAML files to identify security vulnerabilities in a mid-term group project, and implemented fixes for selected domains in the final project.

Midterm Project Task - Your group is tasked with assessing the security vulnerabilities of an e-commerce application's cloud infrastructure. The objective is to ensure the confidentiality, integrity, and availability of both the application and its data. This project covers several critical areas of cloud security, including identity and access management (IAM), data encryption, network security, vulnerability management, logging/monitoring, and disaster recovery.

Due to deliberate misconfigurations and security oversights, the infrastructure is highly vulnerable to potential attacks. Your assignment is to identify and exploit these vulnerabilities, demonstrate their potential impact, and provide actionable recommendations for remediation.

The vulnerable application stack is deployed using a provided CloudFormation template, which automatically sets up the necessary network and security configurations to enable access to the Juice Shop web application.

Finals Project Task - 

Scenario Overview: 
Building upon your midterm security assessment, your group is now tasked with designing and implementing a security hardening plan for the e-commerce cloud infrastructure. The goal is to move from identifying vulnerabilities to designing improvements that enhance the confidentiality, integrity, availability, and resilience of the system.

Your assignment is to select two focus areas based on your midterm findings and develop a comprehensive plan to remediate vulnerabilities, strengthen cloud security posture, and demonstrate simulated results.

This project moves beyond identifying vulnerabilities — you are now building secure cloud architectures.

Project Tasks: 
1. Select Two Focus Areas:

Your group must select two focus areas from the list below and develop hardening strategies for each:

Focus Area	Key Improvement Ideas
Application Security Hardening	Implement input validation, remediate OWASP Top 10 flaws (e.g., SQLi, XSS), deploy AWS WAF for web application protection.
Infrastructure and Compute Security	Patch EC2 instances, enforce IAM least privilege for instance roles, deploy resources into private subnets, remove unnecessary services.
Network and Access Control Security	Harden security groups, design private VPC architectures, restrict public IP access, configure VPN or Direct Connect options.
Data Protection and Encryption	Enable encryption for S3, RDS, and EBS; use AWS KMS for key management; secure sensitive data with Secrets Manager or Parameter Store.
Disaster Recovery and Monitoring	Configure AWS Backup and recovery plans, enable CloudTrail and CloudWatch monitoring, deploy GuardDuty for threat detection, simulate backup restores.
Note: Your improvement areas must be directly tied to vulnerabilities or risks you identified during your Midterm.

2. Key Improvement Expectations

For each focus area, your group must implement or simulate at least two key security improvements.

Across both focus areas, your project must demonstrate a minimum of four total improvements.

Each improvement must be:

Clearly justified based on your midterm findings,

Implemented or simulated using AWS services,

Validated with evidence (such as configuration outputs, screenshots, test results).

3. Research and Plan

Investigate AWS services, best practices, and security frameworks (e.g., NIST, CIS Benchmarks) applicable to your chosen areas.

Define clear objectives for each selected focus area (what you are securing, why it matters).

4. Implementation and Simulation

Develop a detailed, step-by-step plan for security enhancements:

Specify technical configurations (AWS services, IAM policies, CLI commands, architecture changes).

Provide simulation evidence if full deployment is not feasible (e.g., screenshots, configuration snippets, test outputs).

Include at least two technical artifacts across your submission (e.g., JSON policies, CloudFormation/IaC templates, monitoring dashboards, CLI results).

5. Validation

Demonstrate how you would validate your security improvements:

How will you confirm encryption is enabled?

How will you ensure WAF rules are blocking malicious traffic?

How would you test backup and recovery processes?

6. Impact Assessment and Reflection

Compare the security posture before and after applying your improvements.

Identify any residual risks that remain.

Reflect on lessons learned, challenges faced, and future recommendations for scaling security efforts.

Deliverable: 
Each group must submit a single professionally formatted PDF report containing the following sections:
1. Executive Summary 

Provide a clear and concise overview of your project.
State the two focus areas your group selected, summarize your overall security objectives, and briefly highlight the key improvements made.
2. Background: Connection to Midterm 

Summarize the specific vulnerabilities or risks identified during your Midterm that relate to your chosen focus areas.
Clearly explain how your selected improvements build upon your midterm findings.
3. Objectives 

For each focus area, define your objectives and outline the two key improvements your group chose to implement.
Explain what specific risks or vulnerabilities each improvement addresses.
4. Implementation Plan

For each focus area:

Detail the technical steps you followed for each of the two key improvements.

Describe the AWS services, tools, or configurations you used.

Include supporting materials such as CLI commands, JSON configurations, architecture diagrams, or code snippets.

Provide simulated evidence where full implementation is not feasible.

5. Validation and Testing

Describe the methods you used to validate that your improvements were successfully implemented.
Include evidence such as test outputs, screenshots, monitoring data, or other verification artifacts.
Note: Validation methods must be actionable and evidenced

6. Impact Assessment

Analyze how the security posture of your cloud environment improved after implementing the selected improvements.

Discuss what vulnerabilities were mitigated, what new controls were introduced, and any remaining risks or trade-offs.

7. Lessons Learned and Group Reflection 

Reflect briefly on your project experience:

What challenges did your group face while designing and implementing security improvements?

What were the most important lessons you learned about hardening cloud environments?

If you had more time or resources, what would you do differently or improve further?
