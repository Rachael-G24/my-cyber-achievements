---
# CIA Triad Project
## *Assessing Security Culture*
### 2024-07-05
---
Cybersecurity professionals should be champions of security culture. How do we mitigate common security risks, knowing that people are most often the cause of security breaches? 

My Cybersecurity boot camp through The Ohio State University provided the following scenario, which has been copied from the provided curriculum: 
> Employees at SilverCorp are increasingly using their own personal devices for company work.
> * Specifically, over half of all employees check their work email and communications via Slack on their personal mobile phones.
> * Another 25% of employees are doing other work-related activities, using work accounts and work-related applications, on their personal phones.

> Allowing sensitive work information to be shared on employees' personal devices has a number of security implications. You must research these security risks and use the security culture framework to develop a plan to mitigate the concerns.

🌟 The following section includes three assignment prompts and my responses (indicated by 👩‍🦰). I researched my responses and applied course objectives. 


💠 Measure and Set Goals 💠
> 1. Using outside research, indicate the potential security risks of allowing employees to access work information on their personal devices. Identify at least three potential attacks that can be carried out.

👩‍🦰
* Three potential security risks include data breach (resulting in brand/reputation damage, identity or data theft, trouble with/fines from governmental regulatory agencies), stolen phone (leading to unauthorized access to sensitive information or stolen sessions), and significantly increased vulnerability to malware (due to using public WiFi) that could bring operations to a halt.

* Three potential attacks include Phishing, DDoS Attack, and XSS Attack (others include Man-in-the-Middle or Supply-Chain Attack, or if SilverCorp is Big Game, Ransomware from a cyber criminal org). 

> 2. Based on the previous scenario, what is the preferred employee behavior? (For example, if employees were downloading suspicious email attachments, the preferred behavior would be that employees only download attachments from trusted sources).

👩‍🦰
* Employees must ensure their phones are secure by installing/using the same security controls they would for a laptop or desktop computer. If employees want to use their personal phones because it is convenient, they should also invest in anti-virus software for the phone and a VPN service subscription (if SilverCorp does not provide these). It would be prudent to apply MFA to these websites and use an authenticator app or biometrics for access. This “defense in depth” approach would promote and reinforce a healthy security culture. 
* Employees must also use secure passwords, change them frequently, and avoid reusing or recycling them. These passwords for work should also not resemble any passwords used for personal online use, such as social media or shopping. Installing a password manager would be another helpful security layer.
* SilverCorp’s MDM policies likely prescribe these behaviors. We’ll assume that SilverCorp does have these policies and that they just haven’t been enforced. We’ll also believe that the company provides and already pays for a VPN service and that a well-defined password policy is in place.

> 3. What is the goal that you would like the organization to reach regarding this behavior? (For example, to have less than 5% of employees downloading suspicious email attachments).

👩‍🦰
* SilverCorp’s security team may use Splunk to analyze user behaviors and create quantifiable data for periodic review. For example, Splunk may monitor VPN usage among employees and help SilverCorp determine how much data is/is not being filtered/tunneled via a VPN per employee. (VPN usage may also be monitored using a network protocol analyzer such as Wireshark).
* Splunk may also detect any security incidents caused by password reuse or misuse for each employee and create reports that provide measurable feedback (at least, I think it can… or perhaps another SIEM?).
* Employees should activate MFA for their main SilverCorp accounts. The security team may monitor usage/nonusage via the company’s preferred authenticator software.
