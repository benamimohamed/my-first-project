# THE PHISHING INCIDENT RESPONSE PLAYBOOK 
# Phase 1 : Preparation : 
Firstly, it's vital to determine the teams and roles involved in the incident response process.Clearly defined roles and responsabilities provide structure,reduce confusion, and ensure a swift and effective response.
Three critical teams are generally involved : the Incident Response Team (IRT) who coordinate the entire process, the IT Team, who ensure technical aspects are covered, and SOC Team, who monitor and analyse activity on networks,servers,endpoints,databases,applications,websites, and other systems, looking for anomalous activity that could be indicative of a security incident or compromise.
Now that our teams are in place and fully prapared, we are ready to pass to the next step.
# Phase 2 : Detection:
this step is where we actively look for any signs of phishing attempts, the first step in the detection is to configure our SIEM by creating phishing alerts will notify us of potential phishing activities, once an alert is trigged, it's time four our SOC Team to step up.They perform the initial triage, determining the saverity and credibility of the alert, if the alert is credible, our SOC team escalates to Incident Response Team, they take the lead from here, managing the potential phishing incident, with the detection phase Completed, it's time to delve deeper and uncover the facts, we transition to the next phase 
# Phase 3 : Investigation & Analysis 
The IRT analyzes the suspected phishing email, including sender information, content, and any attachements or embedded links.
step1: Examine the email header: analyze the email header to gather information about the sender, recipient,and email path, look for discreapancies in the sender's address and domain, as well as any usual routing information
step2: Inspected the mail content : scrutinize the email body for indicators of phishing, such as sense of urgency, grammatical errors, or requests for sensitive data. Pay attention to the tone and language used, and compare it to the sender's usual communication style .
step3: Investigate the URL and attachement: If the email contains links or attachements, analyze them for potential malicious content, check the URL for inconsistencies or redirections, and scan attachements for malicious payloads using antivirus software.
step4: Identify the attack type and primary indicators : Determine the phishing attack type, for example spear-phishing or whaling, based on the target and content, Identify primary indicators, such as email address, attachements, or URLs that can help in tracing the source of the attack.
step5: Assess the destribution methode and timeline : Determine how the phishing email was distributed, for example,mass email or targeted compaign, and establish a timeline of the attack, including when the email was sent, opened, and any subsequent actions taken by the recipient 
step6: Check for indicators Of Compromise(IOC): Search for IOCs, such as unautorized access or data exfiltration, in the affected systems. Review logs and alerts generated by security tools, like SIEM, to identify any suspicious activity related to the phishing email.
step7: Correlate the findings with threat intelligence:Copare the information gathered during the investigation with available threat intelligence to identify any known threat actors or compaigns, thhis help in understanding the attacker's motives, thecniques and potential next steps.
step8: Document the findings : Create a detailed report of the investigation, including the step taken, evidence collected, and conclusions drawn. This report will be used in the subsequent phases of the incident response process and can serve as a valuable reference for future incidents. Now that we have completed our investigation and analysis, its time to move on the next phase.
# Phase 4 : Containment & Eradication 

