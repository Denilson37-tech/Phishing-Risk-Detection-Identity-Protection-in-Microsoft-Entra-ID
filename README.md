 Phishing-Risk-Detection-Identity-Protection-in-Microsoft-Entra-ID
A junior cloud security project demonstrating detection and mitigation of phishing-related identity risks using Microsoft Entra ID and Azure monitoring tools.Focuses on early threat detection, investigation, and preventive response, without creating phishing attacks.
Background: Abuja Fraud Case

In 2024, a small consulting firm in Abuja experienced an attempted credential theft. An employee received a convincing email and entered credentials on a fake login page. Within hours, unusual sign-ins from an unfamiliar location and failed MFA challenges were detected. Quick review and response prevented further compromise.

Lesson: Phishing is an identity security problem, not just an email problem.
Objective

Enable security teams to detect phishing-related risks in cloud identities, respond quickly, and improve overall identity security posture using log analysis and Azure-native tools.
Solution Overview

Tools & Services Used:

Microsoft Entra ID Sign-in & Audit Logs

Azure Monitor & Log Analytics Workspace

Kusto Query Language (KQL)

Role-Based Access Control (RBAC)

Detection Approach:

Multiple failed sign-ins followed by success

Sign-ins from unusual locations

Abnormal MFA challenge patterns

Sudden changes in authentication behavior.
Response Actions:

Force password reset for compromised accounts

Revoke active sessions

Enforce or strengthen MFA

Adjust Conditional Access policies

Educate users on phishing awareness
Outcome

Suspicious activity detection and alerting via Entra ID logs

Reduced risk of credential compromise

Improved cloud security visibility and readiness

Demonstrated ability to translate log data into actionable security decisions


Sample KQL queries are included in /kql-queries.
