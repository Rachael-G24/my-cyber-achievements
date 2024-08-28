---
# CIA Triad Project
## *Assessing Security Culture* 
### 2024-07-05 | Rachael Griggs
---
Cybersecurity professionals should be champions of security culture. How do we mitigate common security risks, knowing that people are most often the cause of security breaches? 

My Cybersecurity boot camp through The Ohio State University provided the following scenario, which has been copied from the provided curriculum: 
> Employees at SilverCorp are increasingly using their personal devices for company work.
> * Specifically, over half of all employees check their work email and communications via Slack on their personal mobile phones.
> * Another 25% of employees do other work-related activities, using work accounts and work-related applications, on their phones.

> Allowing sensitive work information to be shared on employees' devices has several security implications. You must research these security risks and use the security culture framework to develop a plan to mitigate the concerns.

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

> 3. What methods would you use to measure how often employees are currently not behaving according to the preferred behavior? (For example, conduct a survey to see how often people download email attachments from unknown senders.)

👩‍🦰
* SilverCorp’s security team may use Splunk to analyze user behaviors and create quantifiable data for periodic review. For example, Splunk may monitor VPN usage among employees and help SilverCorp determine how much data is/is not being filtered/tunneled via a VPN per employee. (VPN usage may also be monitored using a network protocol analyzer such as Wireshark).
* Splunk may also detect any security incidents caused by password reuse or misuse for each employee and create reports that provide measurable feedback (at least, I think it can… or perhaps another SIEM?).
* Employees should activate MFA for their main SilverCorp accounts. The security team may monitor usage/nonusage via the company’s preferred authenticator software.

> 4. What is the goal that you would like the organization to reach regarding this behavior? (For example, to have less than 5% of employees downloading suspicious email attachments.)

👩‍🦰
* At the end of one year, 5% or less of SilverCorp’s employees:
     - will not have MFA associated with their main employee portal and email accounts.  
     - will not be accessing company websites via a VPN.
     - will be the source of password-related security incidents (such as credential stuffing or unauthorized access). 

💠 Involve the Right People 💠
> 5. List at least five employees or departments that should be involved. For each person or department, describe in 2–3 sentences what their role and responsibilities will be.

👩‍🦰
* The five employees/departments that should be involved are the following:

     - **HR Director** - The HR department will need to incorporate these security policies into the employees’ yearly performance reviews. Also, HR will know when the best days and times would be to train the workforce. Lastly, HR will need to develop incentives and disincentives to help motivate employees to engage in proper security behaviors. 

     - **Training & Education Manager** - The manager should be in the loop because he or she will develop training materials necessary to cultivate better security practices within the company. The manager will also have guidance on the best format in which the training should be delivered.

     - **CIO** - This officer needs to take another look at SilverCorp’s MDM policies and develop ways to promote the policy within the company. The CIO may also want to consider updating the policy to reflect the recent security incidents. He or she will assist with implementing the administrative control - which is the policy.

     - **CISO** - We will need the CISO’s help with implementing the technical and administrative controls needed to properly measure employees’ compliance with the MDM policy and the training guidelines that will be provided. The CISO may also need to implement new or revised frameworks according to governmental regulations and standards. 

     - **CFO** - He or she will determine if the suggested implementations will keep SilverCorp profitable. The CFO will consult the C-Suite regarding the costs and benefits of each proposed security control. 

     - **CEO** - Naturally, the CEO must be made aware of these security incidents, their causes, and the proposed plans to foster a healthy security culture within the company. He or she should also ensure that SilverCorp is compliant with agencies such as NIST.

💠 Training Plan 💠
> 6. How frequently will you run training? What format will it take (e.g., in-person, online, or a combination)?

👩‍🦰
* If SilverCorp has 500 employees, then 25% of the employees (125) will be trained every quarter. All employees will have completed the training in one calendar year.
* For each quarter, the training will be live and online (Zoom, MS Teams, etc.) with a Q&A session available at the end. This live training will be offered 3 times in one week and delivered at different times of the day (to ensure the training is available to workers on different shifts). Employees who missed the live sessions will watch a recording of the training.

> 7. What topics will you cover in your training, and why? (This should be the bulk of the deliverable.)

👩‍🦰
* The topics of the training will include the following:
     - The assignment of **specific** security behaviors the employees need to begin practicing. To include:
       - an explanation of how a VPN and an MFA work and why one is required to use them
       - instructions on how to install and use a VPN and MFA on one's phone
       - guidance on how to check for the latest updates for one’s phone and why this is important in terms of vulnerability and risk management
       - an explanation of SilverCorp’s MDM policy and that it is mandatory to follow
       - a review of the company’s password policy
     - The **goal** of the project, explained quantitatively
     - The **big picture** regarding how a weak security culture affects the business, its employees and customers, stakeholders, and reputation, to increase awareness among employees of the **implications** of their lack of due diligence.
     - The **rewards and consequences** of a weak security culture. To include:
       - rewards such as merit certificates, gift cards, and/or highlighting employees during the town hall meetings.
       - consequences such as a verbal warning, a written warning, removal of the option to work from one’s phone, and potential termination of employment and/or the confiscation and purging of the mobile device.
     - An explanation of how and why employees’ user behaviors will be monitored.
     - An explanation of the Acceptable Use Policy that everyone will need to sign.
     - Contact information for IT specialists who may assist employees with implementing any of the security controls mentioned during the training.
 
> 8. After you’ve run your training, how will you measure its effectiveness?

  👩‍🦰
* Quantitative:
  - All employees will take a quiz. They must pass the quiz with a 90% or higher.
  - 14 days after the training, employees will take a survey that asks the following questions: (1) Have you been using a VPN/MFA on your mobile device? (2) Do you have the most recent OS updates on your phone? (3) How often do you use public WiFi? (4) Which of the following security measures do you take while using public WiFi to ensure you are keeping SilverCorp’s data secure? (multiple choice)...etc.
* Qualitative:
  - The results of the survey will be reviewed at the departmental level; managers will review the results and open the floor for discussion and address/problem-solve any barriers to implementing the training guidelines. Managers and leaders in the organization must be role models in the prescribed behaviors. 
* Lastly, the security team will begin to monitor user behaviors to determine if secure behaviors have increased (as mentioned in #3 and #4).
  
💠 Bonus: Other Solutions 💠
> 9. List at least two other potential solutions. For each one, indicate the following:
>    - What type of control is it? Administrative, technical, or physical?
>    - What goal does this control have? Is it preventive, deterrent, detective, corrective, or compensating?
>    - What is one advantage of each solution?
>    - What is one disadvantage of each solution?

👩‍🦰
* Another potential solution would be for SilverCorp to install a Web Application Firewall, which is a technical security control. Since the firewall could be used to try to catch security incidents in real-time and/or block requests suspected of malicious intent, such as an SQLi or XSS attack, it may be considered a detective control. One advantage of the firewall is how fast it may detect security incidents (i.e. as they happen). One disadvantage is that this service can be expensive, and the CFO might pitch the idea after looking at the numbers.
* Another control would be to offer employees a tour of the security operations center, especially for employees who are resistant to the MDM policy. In this case, this solution could be corrective. 
Employees could chat with the security team and sit at their desks for a while to learn more about what they do and why. The security team would show employees software, platforms, or activities that prove how secure behaviors are beneficial and necessary (but they would only share what would not be too sensitive, depending on need-to-know, departmental standards, etc.). This control would be technical because the employees would gain technical insight. This control could also be somewhat administrative if the tour is a part of a performance improvement plan. 
This solution is advantageous in that it would help create a healthy security culture; the employees and security team could develop a rapport. A disadvantage is the potential cost of this idea; even though a tour would not cost money, it would cost time - time away from desks, real-time monitoring, and at-task working behaviors, which could ultimately cost the company money.






