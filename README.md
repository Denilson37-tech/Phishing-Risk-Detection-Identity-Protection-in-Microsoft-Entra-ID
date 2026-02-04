Identity is the primary attack surface in cloud environments, and phishing is the most common method used to compromise cloud accounts. This project demonstrates how Microsoft Entra ID Identity Protection, Azure Monitor, and Kusto Query Language (KQL) can be applied to detect, analyze, and respond to phishing-driven identity risks in a simulated enterprise environment. 

The goal is to show practical identity risk detection, monitoring, and remediation aligned with real-world responsibilities of an Azure Security Engineer Associate.

The project is based on a mid-sized professional services organization with approximately 300 users operating in South Africa. The organization relies on Microsoft 365 and Azure services and supports a hybrid and remote workforce. 

Users are regularly targeted by phishing attacks, which can lead to credential theft, account takeover, and unauthorized access to sensitive data.

This project addresses high-risk threats including phishing-based credential compromise, risky sign-ins from unfamiliar locations, brute-force and password spray attempts, MFA fatigue attacks, and session hijacking following successful phishing. 

Detection of these threats is achieved through Identity Protection risk signals, sign-in logs, and Azure Monitor data. KQL queries are used to identify suspicious authentication patterns such as repeated failed sign-ins, anomalous locations, and high-risk events.

Remediation actions include forcing password resets, revoking active sessions, and recommending risk-based access restrictions. Conditional Access strategies are discussed to enforce risk-based controls and phishing-resistant authentication methods, including FIDO2 and passkeys. 

Break-glass accounts are accounted for to ensure secure fallback options in emergency scenarios. Where licensing prevents enforcement of certain policies, the project documents the intended enterprise-level controls and decision-making rationale.

Identity incidents are managed following a structured lifecycle that includes detection, analysis, containment, eradication, recovery, and post-incident review. This approach mirrors real-world cloud security operations and SOC workflows, ensuring threats are handled systematically. The project demonstrates the ability to integrate monitoring, detection, and response in a practical, repeatable, and enterprise-relevant way.

Tools and technologies used include Microsoft Entra ID, Entra ID Identity Protection, Azure Monitor, Log Analytics, and Kusto Query Language. Skills demonstrated include Azure identity security engineering, phishing threat detection, identity risk monitoring, incident response methodology, and alignment with AZ-500 security controls.

This project emphasizes that effective cloud security begins with identity. Detection alone is insufficient without timely response, and Secure Score improvements do not guarantee full protection. 

Risk-based controls, continuous monitoring, and structured remediation are critical for reducing the impact of phishing attacks in cloud environments. The project is intended for demonstration purposes only, and no real user or production data were used.
