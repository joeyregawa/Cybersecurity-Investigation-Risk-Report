# Datacom Cybersecurity Job Simluation - Investigation & Risk Assessment

This project is inspired by Datacom cybersecurity virtual job simulation via [Forage](https://www.theforage.com/simulations/datacom/cybersecurity-zm6d)

## Objective: The goal of this project is to analyze a cyberattack and perform an in-depth risk assessment in collaboration with Datacom.
- Acquire practical experience in handling real-world cybersecurity threats.
- Use Open-Source Intelligence (OSINT) tools to analyze Advanced Persistent Threats (APTs), with a particular focus on APT34.
- Implement the MITRE ATT&CK Framework to detect and classify threats and vulnerabilities.
- Evaluate and record the effects of cyberattacks on the information security of organizations.
- Create a defense strategy to safeguard clients' networks and systems from future attacks.

## Skills Learned
- OSINT Techniques: Developed expertise in gathering intelligence on threat actors using OSINT tools like CrowdStrike, Dark Reading, and Symantec.
- MITRE ATT&CK Framework: Utilized the MITRE ATT&CK Framework to map out attack vectors, aiding in the identification and mitigation of security risks.
- Threat Intelligence & Analysis: Researched and analyzed APT34, a prominent threat group, to evaluate its tactics, techniques, and procedures (TTPs) in order to identify security risks for organizations.
- Incident Response: Investigated and documented an incident involving the theft of customer data and intellectual property, detailing the steps required to remediate the breach and prevent future occurrences.
- Risk Assessment & Mitigation: Performed an in-depth risk assessment of potential vulnerabilities, assigning risk ratings based on probability and impact, and recommended strategies for risk mitigation.
- Report Writing & Documentation: Compiled comprehensive reports that included risk scenarios, risk ratings, and tailored mitigation strategies for the client.
Scenario 1 Investigation
## Tools:
- OSINT: Mandiant Security Blog, CrowdStrike, Recorded Future, CyberScoop, Dark Reading, The CyberWire, SecureWorks, ThreatConnect, Kaspersky Lab, Symantec Threat Intelligence.
- MITRE ATT&CK Framework: is a widely used tool to categorise and identify cyberthreats. 
- Risk Matrix Created to evaluate the probability, impact, and risk levels of potential attack scenarios.
- Risk Assessment Tools: Utilized the padlock analogy and other conventional tools to assess security posture and suggest further security measures.

# Scenario 1 Investigation

In this task, you will be stepping into the role of a cybersecurity consultant here at Datacom. One of our leading tech corporation clients has fallen prey to a sophisticated cyberattack by a notorious Advanced Persistent Threat (APT) group known as APT34. The attack, believed to be sponsored by a foreign government, has left the organisation's network compromised, and valuable customer data and intellectual property has been stolen.
Your mission is to conduct initial research on this APT group, APT34, and assess the extent of the breach's impact on the organisation's information security. But fear not, for you will be provided with all the necessary tools required to understand cybersecurity concepts and principles, including cyberthreats, attack methods, and the importance of confidentiality, integrity and availability of information. In addition, you will also be familiarised with APT34's tactics, techniques and procedures (TTPs) and the common vulnerabilities they exploit to gain access to networks.
The objective of this task is to help our client conduct an initial investigation into APT34 and evaluate the potential impact of the attack on the organization. As a result, you will need to produce a comprehensive report documenting your findings and outlining key recommendations for improving the organisation's cybersecurity posture.
As you delve deeper into the world of cybersecurity, you will come to appreciate the critical role it plays in protecting organisations against cyberthreats. With the ever-increasing reliance on technology and the internet, cybersecurity has become a vital aspect of any organisation's operations. It is no longer a question of whether an organisation will be targeted but rather a question of when. This task provides you with an excellent opportunity to learn and gain practical experience in the cybersecurity field while making a positive impact on our client's security posture.

## Investigation
APT34 investigation based on MITRE ATT&CK Framework and Open-Source Intelligence (OSINT) tools.
1.	What is their history?
APT34 or HELIX KITTEN is a suspected Iranian threat group that has targeted Middle Eastern and international victims since at least 2014.
2.	Which nation/state are they associated with?
The group works on behalf of the Iranian government based on infrastructure details that contain references to Iran, use of Iranian infrastructure, and targeting that aligns with nation-state interests.
3.	Do they target specific industries?
Targeted a variety sector such as aerospace, energy, financial, government, hospitality and telecommunications business verticals mostly in the Middle East and the United States.
4.	What are their motives?
focuses on collecting sensitive intelligence, employing spear phishing campaigns, and abusing advanced techniques to infiltrate and maintain access within targeted networks.
5.	What are the TTPs they use to conduct their attacks?
APT34 uses a mix of public and non-public tools, often conducting spear phishing operations using compromised accounts, sometimes coupled with social engineering tactics such as spear phishing campaign targeting banks in the Middle East region that used macro-enabled attachments to distribute POWBAT malware, APT34 targeting a Middle East organization using a PowerShell-based backdoor that we call POWRUNER and a downloader with domain generation algorithm functionality called BONDUPDATER based on strings within the malware. The backdoor was delivered via a malicious.
6.	What security measures could the client implement to defend against cyberattacks conducted by this APT?
    -	Organizations are advised to implement strong password policies,
    -	conduct regular security training for employees, 
    -	maintain up-to-date security patches to defend against APT34's tactics.
    -	Monitoring for abnormal DNS requests and unusual network traffic can help detect potential APT34 activities early.
    -	Use MFA. It is a great way to protect identity if hacker manage to steal on credential data. By implementing MFA, the attackers need more than one method to get in to the system or to gain access.
    -	Implement endpoint detection system or protection system such as Anti-virus.
    -	Implement Network Segmentation to prevent the spread of malware from infected sub network.
    -	Implement incident respond plan to quickly resolve or fix the system when threats occur.
  
# Scenario 2 Risk Assessment

Your initial research on the APT group is a crucial step because it helps to identify the potential attackers and their methods, motives and targets. Understanding the TTPs of APT34 helps identify specific vulnerabilities and attack vectors that could be exploited. 
This has laid a solid foundation for the next task, which is to conduct a comprehensive risk assessment for the client. The client has a fence around the perimeter of its property and a padlock on its entrance gate to prevent unauthorised access. However, the leadership team is concerned about potential risks and vulnerabilities that could compromise the security of its information and systems. They require a comprehensive risk assessment to identify potential security threats and vulnerabilities in their system or network.
As a cybersecurity consultant, you understand that conducting a risk assessment is an essential component of any effective cybersecurity strategy. This involves identifying, evaluating and prioritising potential security threats and vulnerabilities to determine the level of risk and develop a plan to mitigate those risks. During the risk assessment, you will need to identify the assets that need to be protected, define the risk matrix and identify potential risk scenarios. You will assess the risk ratings for each scenario, both with and without existing measures in place. Finally, you will provide a risk assessment report to the client summarising your findings and recommendations for mitigating risks and improving the institution's security posture.
The goal of the risk assessment is to help the client prioritise and implement appropriate security measures to mitigate and minimise risks. This will ensure the confidentiality, integrity and availability of their information and systems, as well as protect their reputation and financial resources. Ultimately, your work will help the client comply with regulatory and legal requirements and standards and provide peace of mind knowing that their security is being handled by a knowledgeable and experienced cybersecurity expert.

## Solution Risk Assessment
The answer can be found on the attachment (`Joey Regawa - Risk Assessment.xlsx`).

## To complete this task, you will need to:

1. Define the context – Identify the assets that need to be protected. This could include sensitive information, customer data, financial information or any other critical assets that are important to the client.

2. Define the risk matrix – Define the likelihood, consequence and risk rating for each potential risk scenario. The likelihood is the probability of the risk scenario occurring, while the consequence is the severity of the potential impact. The risk rating is a measure of the overall risk posed by the scenario, calculated by multiplying the likelihood and consequence.

3. Define three risk scenarios – Identify the specific risks that the client is trying to protect their assets from. For example, a cyberattack, natural disaster or employee negligence.

4. Assess risk rating for each risk scenario – Calculate the inherent risk rating for each scenario, assuming there are no measures in place to reduce the risk (without fence and padlock in place).

5. Assess risk rating for each risk scenario with existing measures – Calculate the current risk rating for each scenario taking existing measures in place to reduce the risk into consideration (with fence and padlock in place).

6. Assess risk levels for each risk scenario with additional measures – Identify any additional measures that could be put in place to further reduce the risk. Calculate the target risk rating for each scenario with these additional measures in place.

7. Create a risk assessment report for the client that summarises the risk assessment findings, the risk mitigation strategy and any recommended measures for implementation.

Link: 
- [NIST Guide for Conducting Risk Assessments](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf)
- [SO/IEC 27001:2013 Information technology - Security techniques - Information security management systems - Requirements](https://www.iso.org/standard/54534.html)
- [SANS Institute: Risk Assessment Methodologies](https://www.sans.org/reading-room/whitepapers/auditing/risk-assessment-methodologies-32)
- [Guide to Getting Started with a Cybersecurity Risk Assessment](https://www.cisa.gov/sites/default/files/video/22_1201_safecom_guide_to_cybersecurity_risk_assessment_508-r1.pdf)
- [The Open Group Risk Management Standard](https://www.opengroup.org/forum/security-forum-0/securityriskmanagement)
