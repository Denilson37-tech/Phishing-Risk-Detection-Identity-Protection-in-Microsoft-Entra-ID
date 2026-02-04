Phishing Risk Detection and Identity Protection in Microsoft Entra ID

This project demonstrates how Microsoft Entra ID Identity Protection, Azure Monitor, and KQL can be used to detect and respond to phishing-driven identity risks in an enterprise Azure environment. 
Identity remains the primary attack surface in cloud environments, and phishing is the most common technique used to compromise user accounts. 

The goal of this project is to show practical identity risk detection, monitoring, and remediation aligned with the responsibilities of an Azure Security Engineer Associate (AZ-500).

The project is based on a simulated mid-sized organization with approximately 300 users operating in South Africa. The organization relies on Microsoft 365 and Azure services and supports a hybrid and remote workforce. Due to frequent phishing attempts, the organization requires better visibility into risky authentication behavior and faster response to potential account compromise.

The main threats addressed in this project include phishing-based credential theft, risky sign-ins from unfamiliar locations, brute-force and password spray attempts, MFA fatigue attacks, and session hijacking following successful credential compromise. These threats reflect common identity attack patterns seen in real enterprise environments.

The primary security objectives are to detect risky sign-ins and compromised identities, monitor authentication anomalies using identity and sign-in logs, reduce identity risk through appropriate remediation actions, and improve overall identity security posture and visibility within the tenant.

Microsoft Entra ID Identity Protection is used to identify user risk and sign-in risk signals. Azure Monitor and Log Analytics are used to collect and analyze sign-in logs, while KQL queries are applied to identify suspicious authentication patterns such as repeated failed sign-ins, anomalous locations, and high-risk sign-in events. 
When risks are identified, response actions such as forcing password resets and revoking active user sessions are applied. Where licensing limitations prevent direct enforcement, the intended enterprise security controls are clearly explained at a design level.

The project emphasizes the importance of risk-based access control rather than static per-user MFA. It explains how Conditional Access policies and phishing-resistant MFA methods, such as FIDO2 or passkeys, significantly reduce the success of phishing attacks. Considerations for protecting break-glass accounts and avoiding accidental tenant lockout are also discussed.

Identity incidents in this project follow a structured response lifecycle that includes detection, analysis, containment, eradication, recovery, and post-incident review. This approach aligns with real-world cloud security operations and SOC workflows, ensuring that identity threats are handled consistently and effectively.

The tools and technologies used in this project include Microsoft Entra ID, Entra ID Identity Protection, Azure Monitor, Log Analytics, and Kusto Query Language. The project demonstrates practical skills in Azure identity security engineering, phishing threat detection, identity risk monitoring and remediation, cloud security operations fundamentals, and AZ-500 aligned security concepts.
The key takeaway from this project is that effective cloud security starts with identity. Detection alone is not enough without response, and Secure Score by itself does not guarantee protection. Risk-based identity controls and continuous monitoring are essential for reducing the impact of phishing attacks in cloud environments.
This project is intended for learning and demonstration purposes only. No real users or production data were used.
