# Abstract
This task formulates and develops recommendations and guidelines on how to incorporate usability requirements in security design, as well as a tool-supported method for assessing the effectiveness factor of usability. We will specify a unified validation framework to test both usability and security requirements of biometric-based and multimodal user authentication mechanisms and we will design of new behavioural-based user authentication mechanisms including countermeasures and defences against attackers, validated through some of the demonstration cases. The task will also provide users and administrators with awareness mechanisms to support visualisation of the system status and security risks, enabling effective and usable security controls. Key challenges include automation and AI to help users on their security and privacy decisions, secure and usable authentication, complexity assessment for new security policies, user informed consent on privacy policies and best ways to visualise security and privacy information.
# Overview
Security is often described as a combination of confidentiality, integrity and availability (the CIA triad). In day-to-day life, these are necessary but insufficient qualities for a secure system. Usability is an important attribute to all security solutions, because the vast majority of end users will refuse to use a product or service that is too difficult or makes the main objective harder to achieve when compared to the unsecured alternative.

In this task we were motivated by the need to empower users to make sensible security choises. We have researched methods on how to advise or convince users on different security solutions such as authentication methods or privacy settings, and how to make visible the underlying structures such as security policies or cryptographic protocols.

# Content
## Usability Evaluation
Usability evaluation can be performed during the design and development phase of a system, i.e., formative evaluation,   or   based   on   users'   studies   during   and   after   the   use of the   system,   i.e.,   summative evaluation.  According  to  Fernandez  et  al.,  usability  evaluation  methods  (UEMs)  can  be classified  into  two  different  types,  i.e.,  inspection  methods  and  empirical  methods.  Typically,  usability evaluation  methods  incorporate  techniques,  such  as  inspection,  testing,  or  survey,  for  the  assessmentofusability objectives accomplishment for a system.
### Usability inspection methods
In  the  usability  inspection  method,  experienced  practitioners  like  usability  specialists  and  security professionals examine the usability aspects of a system, i.e., there is no participation of real end-users. The goal  is  to  gather  some  useful  insights  by evaluating  the  designs  or  testing  the  systems  related  to  various components  that  involve  human-computer  interaction  (HCI).  This  can  range  from  checking  the  level  of achievement of specific usability attributes to heuristic evaluations for predictions of usability problems. 
The popular usability inspection methods are Pluralistic Walkthrough , Heuristic Evaluation, Cognitive Walkthrough, Heuristic Walkthrough, Task–Centred Walkthrough, Metaphors of Human  Thinking  (MOT), and Persona  Based  Inspection.
### Usability Testing with users
Usability testing approaches involve representative users to work on typical tasks using the system. The task execution result of each user is analysed to assess the system's friendliness. Testing methods for usability evaluation include Think Aloud Testing, Wizard of Oz, Coaching Method, Co-discovery Learning, Question asking  protocol,  Benchmark  Testing,  and  Retrospective  testing.
### Questionnaire and survey methods
Questionnaire and survey methods can be categorised as empirical methods, which rely on capturing and analysing usage  data from the real end-users. The software  product (or a prototype) is distributed to real end-users  to  perform  a  predefined  set  of  activities  and  the  outcomes  are  recorded  for  detailed  usability evaluation, later.
Empirical methods analyse the usability of a system by assessing 1) users' satisfaction to accomplish their objectives  with  the  system  and,  2)  the  mental  model perceived  by  users  after  using  the  system  for  some time.  In  this  category,  Rating  Scales,  Satisfaction  Questionnaire,  and  System  Usability  Scale  (SUS)  are some commonly used methodologies. 
## Usability dimensions and attributes
Eventually, to  determine  usability  requirements  in  security  and  privacy, end-users’expectations  and preferences on these aspects are required to be captured and translated into technical specifications.  Usability and User Experience (UUX) evaluation divides in  attributes, i.e., knowability, operability, efficiency, robustness, safety, and subjectivesatisfaction.
## Formal usability metrics to quantify usability and optimization criteria
An elegant way to validate usability is opened if easy to measure usability metrics are available. Having a complete  set  of  such  metrics  would  allow us  to  compare  or  optimize  usability  aspects  automatically  and reliable by aggregating metric scores or using them as optimization criteria.
While usability is influenced  by the  experience, preference,  and ability of each individual user, there  are some  aspects  of  usability  that  are  still  universal.  One  usability  goal,  for  example,  is  often  to  reduce complexity. One common way to find usability goals is to ask users about the difficulties or usability related tasks that they face and aggregate what the common problems are. The goals for access control rule set configuration there are the following:
* G1.Allow no more than the owner wants to be allowed. 
* G2.Allow everything the owner wants to be allowed. 
* G3.A rule must not be fully covered by another rule of the same ruleset. 
* G4.Two rules belonging to the same rule set must not conflict.
* G5.Minimize the number of ruleset elements.
* G6.Minimize maintenance effort in a changing system.
## Usability Requirements 
* User authentication
* Information visualization 
* Graphical  security  models
* Encryption  of  communications  
* Identity  and  privacy management  
* Error  reporting  
* Verifiable  credentials  
* Data  privacy
### Open Banking
* Efficiency
* Operability
* Knowability
* Safety
### Supply Chain security Assurance
* NoA
* Config
### Privacy-Preserving Identity Management
* Perfo
* Usab
* Transp
* Usab
* Efficiency
* Satisfaction
* Knowability
* Safety
* Operability
### Maritime transport
* Usab
* Operability
### Smart Cities
* Usab
* Operability
## Usability Validation
* User Authentication
* Encryption Techniques
* Identity and privacy management
* Data privacy
* GDPR compliant user experience
## Recommendations
1. Selection of appropriate dimensions or attributes to characterize usability requirements.
Different  users  can  have  different  expectations  and  preferences  with  regard  to  security  or  privacy mechanisms to be deployed in a system. Therefore, it is essential to select appropriate dimensions or attributes  (e.g., knowability,  operability(effectiveness), efficiency,  robustness,  safety, satisfaction)  to characterize usability requirements specific to each security and privacy mechanism
2. Selection  of  suitable  usability  inspection  methods  during the  design  and  development  phase  of security or privacy mechanisms pertaining to a system.
D3.5 recommended an early user involvement should be ensured for new security and privacy features Table 1presents  popular  usability  inspection  evaluation  methods,they should be  applied  for  the usability evaluation of security or privacy designs. The outcome of this step is to generate a usability requirements validation checklist that should be used as an input for usability testing with users.
3. Selection of more than one “usability testing with users”approaches.
D.5 recommended user modellingand/or user tests should be conducted for new security and privacy features. More than one usability testing with users approaches presented in Table 2should be selected tovalidate the usability requirements checklist generated as a result of Step 2.
4. Creation of a usability traceability matrix.
D3.5 recommended that usability research methods should be used throughout the design, development, and  assessment  of  security  mechanisms.  Thus,  a  traceability  matrix should be  prepared  that can  link between 1) the privacy or security specifications, 2) usability requirements for each privacy and security specification,  3)  usability  validation  checklist,  and  4)  the  test  cases,  surveys,  and  questionnaires  to synergize the usability validation framework.
5. Validation of usability requirements for authenticated encryption.
D3.5 recommended the use of authenticated encryption to protect the integrity of the communications as well as the privacy of the content. It is recommended to capture usability requirements for designing such  solutions  by  involving  a  wider  audience.  Subsequently,  their  nature  and  habits  to  be  studied  to prepare a usability validation checklist.
5. Validation of usability requirements for user authentication.
D3.5 recommended providing user authentication methods  that are  both secure  and privacy-friendly, suggesting  the  use  of  biometrics.  Generally,  a  user  generally  uses  a  number  of  smart  devices  and security-sensitive  applications  on  a  daily  basis.  Usability  validation  methods  must  ensure  that  user authentication schemes do not add cognitive load, easeof use, do not require any technical knowledge, and do not frustrate users.  

# Assets and Other Research
In this task the focus of research and development of assets is on the users and usability. Several assets are developed in neighbouring tasks as well. Besides the usability research on our assets, we also present other research conducted in this task that relates to usability of security solutions.

The assets can be divided into three groups according to their relationship with the user: the user layer,  the guidance layer and  the analysis layer. In the user layer the assets are directly used by either a layperson or a professional to achieve a goal, like authenticating themselves to access a service. In the guidance layer the user is still choosing to interact with the asset, but the purpose of the user is to learn something; these assets try to advise or influence the user, so that they can perform other tasks more securely. For example, when the user is trying to perform a data protection impact assessment (DPIA), they can consult the prepared DPIA template. The analysis layer is slightly different compared to the other two. It contains assets that analyze or model the actions of the user or the usability of other security solutions. Visualizations are used to make security information more understandable. 

From the research conducted on and with these assets we can also identify three main themes: data privacy and protection; solutions for fulfilling security requirements; and analysing and illuminating security for the benefit of users. Firstly, processing of personal data is a necessary step in many modern services. From the point of view of businesses, it is important to be in compliance with regulations, e.g., the General Data Protection Regulation (GDPR). Moreover, from the point of view of the citizen it is important to have knowledge and options on the ways their personal data can be used. This requires tools that enable the decision (i.e., privacy-enhancing tools so that there is a real possibility for managing personal information during interactions), but also that those tools are adapted to user preferences, or they will be dismissed by users in favour of more convenient (but privacy-harming) solutions. The second theme covers the research on security requirements. Validation of security requirements has been discussed in D3.7, and in D3.16 we present tools for eliciting and fulfilling them. And finally, the third theme is about enhancing the human understanding of security solutions. We have studied how to make security solutions more user friendly, and how to present security information to a user in a clear and understandable manner. The tools to achieve these goals include modelling, visualizations and development of suitable frameworks.

In the following table the assets and other research are listed and mapped to the three user layers (denoted with User, Guidance and Analysis) and research themes (denoted with Privacy, Requirements and Human).

|     Asset                             |     Non-asset   research           |     Asset   layer          |     Research Theme        | Reference |
|---------------------------------------|------------------------------------|----------------------------|---------------------------|---|
|     Privacy-preserving   IdM          |                                    |     User                   |     Privacy               |[Moreno et al.](https://ieeexplore.ieee.org/document/9495805)|
|     DPIA   template                   |                                    |     Guidance   and User    |     Privacy               ||
|                                       |     Privacy settings prediction    |     Guidance   and User    |     Privacy               ||
|     HATCH                             |                                    |     Analysis               |     Human                 |[Beckers and Pape](https://ieeexplore.ieee.org/document/7765507)|
|     CyberSecurity   Awareness Quiz    |                                    |     Guidance   and User    |     Human                 |[Pape et al.](https://link.springer.com/chapter/10.1007%2F978-3-030-62433-0_4)|
|     LiSRA                             |                                    |     Guidance   and User    |     Human                 |[Schmitz and Pape](https://www.sciencedirect.com/science/article/pii/S0167404819301993)|
|                                       |     Privacy notifications          |     User   and Guidance    |     Requirements          ||
|     Adaptive   Authentication         |                                    |     User                   |     Requirements          ||
|     HAMSTERS                          |                                    |     Analysis               |     Human                 |[Broders et al.](https://link.springer.com/chapter/10.1007/978-3-030-64266-2_4)|
|     EEVEHAC                           |                                    |     User                   |     Human                 |[Hekkala et al.](https://www.scitepress.org/Papers/2021/105178/105178.pdf)|
|     SYSVER                            |                                    |     Analysis               |     Human                 ||
|     AuthGuide                         |                                    |     Guidance   and User    |     Human                 |[Preuveneers et al.](https://www.springerprofessional.de/en/authguide-analyzing-security-privacy-and-usability-trade-offs-in/19616856)|
|                                       |     Privacy concerns               |     Analysis               |     Human and Privacy     ||
|     LEECH                             |                                    |     Guidance   and User    |     Human and Privacy     |[Pape et al.](https://www.usenix.org/conference/soups2021/presentation/pape)|
## Publications
[Moreno, R. T., García-Rodríguez, J., Bernabé, J. B., & Skarmeta, A. (2021). A Trusted Approach for Decentralised and Privacy-Preserving Identity Management. IEEE Access, 9, 105788-105804.](https://ieeexplore.ieee.org/document/9495805) [repository](https://github.com/rafaeltm/OLChainEnabled)
[Beckers, K. and Pape, S.: A Serious Game for Eliciting Social Engineering Security Requirements. In Proceedings of the 24th IEEE International Conference on Requirements Engineering, IEEE Computer Society, RE '16 , 2016](https://ieeexplore.ieee.org/document/7765507) [preprint](https://pape.science/paper/BP16re/)
[Pape, S.; Goeke, L.; Quintanar, A. and Beckers, K.: Conceptualization of a CyberSecurity Awareness Quiz. In Computer Security - ESORICS 2020 International Workshops MSTEC, pages 61-76, Springer International Publishing, Cham, LNCS 12512, 2020.](https://link.springer.com/chapter/10.1007%2F978-3-030-62433-0_4) [preprint](https://pape.science/paper/PGQB20mstec/)
[Schmitz, C. and Pape, S.: LiSRA: Lightweight Security Risk Assessment for Decision Support in Information Security. In Computers & Security, 90, 2020.](https://www.sciencedirect.com/science/article/pii/S0167404819301993) [preprint](https://pape.science/paper/SP20cose/)

[Broders, N., Martinie, C., Palanque, P., Winckler, M., Halunen, K. (2020). A Generic Multimodels-Based Approach for the Analysis of Usability and Security of Authentication Mechanisms. In Proc. of Human-Centered Software Engineering - 8th IFIP WG 13.2 International Working Conference, HCSE 2020, Eindhoven, The Netherlands, November 30 - December 2, 2020, HCSE 2020. Lecture Notes in Computer Science 12481, pp. 61-83. Springer 2020.](https://link.springer.com/chapter/10.1007/978-3-030-64266-2_4)

[Martinie, C., Grigoriadis, C., Kalogeraki, E.-M., Kotzanikolaou, P. (2021). Modelling Human Tasks to Enhance Threat Identification in Critical Maritime Systems. In 25th Pan-Hellenic Conference on Informatics, PCI 2021, November 26–28, 2021, Volos, Greece. ACM, New York, NY, USA, 6 pages.](https://dl.acm.org/doi/10.1145/3503823.3503892)

[Halunen, K., & Latvala, O. M. (2021). Review of the use of human senses and capabilities in cryptography. Computer Science Review, 39, 100340.](https://doi.org/10.1016/j.cosrev.2020.100340)

[Hekkala, J., Nikula, S., Latvala, O. M., & Halunen, K. (2021). Involving Humans in the Cryptographic Loop: Introduction and Threat Analysis of EEVEHAC. In 18th International Conference on Security and Cryptography, SECRYPT 2021 (pp. 659-664). SciTePress.](https://www.scitepress.org/Papers/2021/105178/105178.pdf)

[Preuveneers, D., Joos, S., & Joosen, W. (2021, September). AuthGuide: Analyzing Security, Privacy and Usability Trade-Offs in Multi-factor Authentication. In International Conference on Trust and Privacy in Digital Business (pp. 155-170). Springer, Cham.](https://www.springerprofessional.de/en/authguide-analyzing-security-privacy-and-usability-trade-offs-in/19616856)

[Pape, S.; Klauer, A. and Rebler, M.: Leech: Let's Expose Evidently bad data Collecting Habits - Towards a Serious Game on Understanding Privacy Policies (Poster). In 17th Symposium on Usable Privacy and Security (SOUPS 2021), 2021.](https://www.usenix.org/conference/soups2021/presentation/pape) [preprint](https://pape.science/paper/PKR21soupsposter/)

# Cybersecurity Research and Areas Priority

--- | Governance and Capacity Building | Trustworthy Ecosystems of Systems | Trust-Building Blocks | Disruptive Emerging Development
--- | --- | --- | --- | ---
Example Asset  | :heavy_check_mark: | - |  - | :heavy_check_mark: 
Privacy-preserving   IdM  | - | - |  :heavy_check_mark:  | :heavy_check_mark: 
DPIA   template | - | - |  :heavy_check_mark: | :heavy_check_mark:
HATCH | :heavy_check_mark: | - |  - | -
CyberSecurity   Awareness Quiz | :heavy_check_mark: | - |  - | -
LiSRA | :heavy_check_mark: | - |  - | -
Adaptive   Authentication | - | - |  - | -
HAMSTERS | - | - |  - | -
EEVEHAC | - | - |   :heavy_check_mark:  | -
SYSVER | - | - |  - | -
AuthGuide | - | - |  - | -
LEECH | :heavy_check_mark: | - |  - | -

<p></p>

--- | Collaborative Networks| Education & Training | Certification | Secure Platforms of Platforms | infrastructure Protection | Holistic Data Protection | AI-based Security | Systems Security & Security Lifetime Management | Secure Architectures for Next Generation Communication | Secure Quantum Technologies | Secure AI Systems | Personalized Privacy Protection
--- | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Example Asset 1 | :heavy_check_mark:  | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Example Asset 2 | --- | --- | --- | --- | --- | :heavy_check_mark:  | --- | --- | --- | --- | --- | :heavy_check_mark:  
Privacy-preserving   IdM  | --- | --- | ---  | --- | --- | :heavy_check_mark:  | --- | --- | --- | --- | --- | :heavy_check_mark:  
DPIA   template | --- | --- | ---  | --- | --- | :heavy_check_mark: | --- | --- | --- | --- | --- | :heavy_check_mark: 
HATCH | --- | :heavy_check_mark: | ---  | --- | --- | :heavy_check_mark: | --- | :heavy_check_mark: | --- | --- | --- | --- 
CyberSecurity   Awareness Quiz | --- | :heavy_check_mark: | ---  | --- | --- | :heavy_check_mark: | --- | --- | --- | --- | --- | --- 
LiSRA | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Adaptive   Authentication | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
HAMSTERS | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
EEVEHAC | --- | --- | ---  | --- | --- | ✔️ | --- | --- | ✔️ | --- | --- | --- 
SYSVER | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
AuthGuide | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
LEECH | --- | :heavy_check_mark: | ---  | --- | --- | --- | --- | --- | --- | --- | --- | :heavy_check_mark: 

# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1,” CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)

[2 - K. Halunen, "D3.5 Usable security & privacy methods and recommendations", CyberSec4Europe, 2020](https://cybersec4europe.eu/wp-content/uploads/2020/02/D3.5-Usable-security-privacy-methods-and-recommendations-Submitted.pdf)

[3 - B. Crispo, "D3.7 Usability Requirements Validation", CyberSec4Europe, 2020](https://cybersec4europe.eu/wp-content/uploads/2020/03/D3.7_Usability_requirements_validation_Submitted.pdf)

[4 - O.-M. Latvala, "D3.16 Security Requirements and Risks Conceptualization", CyberSec4Europe, 2021](https://cybersec4europe.eu/wp-content/uploads/2022/01/D3.16-Security-requirements-and-risks-conceptualization-v1.0_submitted.pdf)

[5 - C. Martinie, "D3.17 Integration to demonstration cases", CyberSec4Europe, 2022](https://cybersec4europe.eu/wp-content/uploads/2022/02/D3.17-Integration-to-demonstration-cases_v1.0_submitted.pdf)
