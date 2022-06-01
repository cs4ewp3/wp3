

# Abstract
This page describes the main outputs of CS4E-WP3-T5.

We illustrate how the assets developed in task 3.5 can be used to implement some of the activities of an adaptive security system. We assume that an adaptive security system is based on the MAPE-K (Monitor-Analyze-Plan-Execute) loop architecture [1] which is used to engineer adaptive systems [2]. Monitoring (M) is performed to collect data about the system to be protected and its operating environment and maintain an updated representation at runtime (Knowledge - K). The Knowledge also represents information about threats and security requirements. The Knowledge is used to analyze (A) security threats and assess security risks, and plan (P) and execute (E) security controls aimed to prevent or thwart the threats discovered during analysis.
We showcase how the assets provided by each partner of task T3.5 can be used to implement a specific activity of an adaptive security system necessary to support some of the maritime transport use case scenarios elicited in task T5.5. 


# Overview
The main contributions that our assets bring to the architecture of an adaptive security system can be summarized as follows:

*	Data-flow-centric threat assessment: an approach to automate threat elicitation and identify evolving threats when the architecture of the system changes. 

*	Adaptive Authentication: a decision-making technique to automatically select an authentication method that mitigates the security risks and maximizes the satisfaction of security and other requirements, such as performance and usability.

*	Situation-driven risk assessment and security enforcement: an approach to identify situations and pre-compute security risks based on the utilized assets, threats, vulnerabilities and impacts. Depending on the security risks this approach can enforce situation-specific security controls that effectively mitigate the risks.

*	Adaptive risk assessment:  a novel technique to verify effectiveness of security controls when changing scenarios affect interdependencies between system components.

*	Adaptive incident reporting: a novel approach to incident reporting that can adaptively change the reporting process and the report template depending on the type of incident and the location of the components affected by the security incidents.
Finally, we identify General Data Protection Regulation (GDPR) compliance issues that can arise in adaptive security systems.


## Content

### Scenario 1: Data-flow-centric threat assessment

#### Summary

This scenario supports the modelling and analysis of threats elicited for the maritime Transport example. We use the SPARTA asset developed at KUL to support the modelling of a Data-Flow-Diagram of the Maritime Transport example, the assets and select specific threats categories. Subsequently, the SPARTA asset supports the automated elicitation of threats on the basis of the DFD and the identification of security controls to mitigate the identified threats.


#### Resources

*	Online proof-of-concept demonstrators and repositories:
     *   https://distrinet.cs.kuleuven.be/software/sparta/ [Binary release of SPARTA asset]
     
* Videos:
     * https://youtu.be/cdAiaNutfW4 [SPARTA demo video]

* Scientific dissemination: 
     * D. Van Landuyt, L. Pasquale, L. Sion, and W. Joosen, "Threat models at run time: the case for reflective and adaptive threat management (NIER track)," in SEAMS'21: Proceedings of the 16th International Symposium on Software Engineering for Adaptive and Self-Managing Systems, 2021.


### Scenario 2: Adaptive Authentication

#### Summary

This scenario addresses the challenges raised by insufficient authentication in the maritime scenario. To address this issue the adaptive authentication system monitors contextual factors and behavioral features of its users to identify changing security risks. The system can decide to enforce an authentication method to mitigate the security risks and maximize user convenience. 


#### Resources

* Scientific dissemination: 
     * A. Hassan, B. Nuseibeh, L. Pasquale, “Engineering Adaptive Authentication," in 2021 IEEE International Conference on Autonomic Computing and Self-Organizing Systems Companion (ACSOS-C), pp. 275-280. IEEE, 2021.


### Scenario 3: Situation-driven risk assessment and security enforcement

#### Summary

This scenario supports the need for a more holistic security methodology combining risk analysis and the deployment of security policies. These activities are triggered dynamically by situation changes. Situations allow capturing complex and dynamic constraints (e.g., time, location, workflows, etc.). This concept will provide a guide for maritime security assessment and security policy enforcement. The resulting framework will be able to suggest adaptive security controls for various critical functions of the cargo transport service required by each security level of each situation. The situations identified at the risk assessment stage will be formally specified using complex event techniques while situation-driven security control will be translated into situation-driven security policies. The underlying security management infrastructure will then be able to dynamically deploy and enforce security policies making security adaptable to each predefined situation and security level.

#### Resources

* Scientific dissemination: 
     * C. Grigoriadis, R. Laborde, A. Verdier, and P. Kotzanikolaou, "An Adaptive, Situation-Based Risk Assessment and Security Enforcement Framework for the Maritime Sector," Sensors 22, no. 1 (2022): 238.


### Scenario 4: Adaptive Risk Assessment

#### Summary

This scenario supports adaptive security risk analysis that can follow the system as it changes.
The asset supporting this scenario is .
Our approach is to combine all the available information (both at physical and cyber levels) to build a complete state diagram representing what each user/agent can do in the system, leveraging all his/its capabilities, in a dynamic scenario. The resulting state diagram can be then analysed to understand what the user/agent is able to access and how. The combination of all the state diagrams leads to the overall evaluation of the effective implementation of high-level security policies. Of course, given the context of the adaptive security, this is an evolving process, where any kind of change in some configuration of some elements (for instance, the addition of a service interaction, or a new connection between sub-networks) requires the re-evaluation of the possibly modified state diagrams, to find out if the new scenario has opened new access paths to possibly critical resources, introducing risk elements in the overall system. Another source of changes in the system is also the possible discovery of new potential vulnerabilities affecting one or more system components. In this case, the overall risk analysis is clearly affected by what channels a compromised element could open to a malicious user.

### Scenario 5: Adaptive Incident Reporting

#### Summary

This scenario supports the need to provide more automated and adaptive incident reporting capabilities. The asset supporting this scenario is AIRE (Atos Incident Reporting Engine) which can enforce a predefined and configurable incident reporting workflow and support the generation of the required mandatory reports adapted to different templates. 3 different incidents of the maritime transportation example were considered, which require to be reported to different competent authorities: 1) The AmosConnect attack; 2) attacks attempting to deviate a ship from its original course and 3) data breach incidents determined by vulnerabilities in the authentication process.


#### Resources

* Videos: 
     * https://www.youtube.com/watch?v=9dxgjFVv1Tw [AIRE Demo Video]




# Cybersecurity Research and Areas Priority

--- | Collaborative Networks| Education & Training | Certification | Secure Platforms of Platforms | Infrastructure Protection | Holistic Data Protection | AI-based Security | Systems Security & Security Lifetime Management | Secure Architectures for Next Generation Communication | Secure Quantum Technologies | Secure AI Systems | Personalized Privacy Protection
--- | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Briareos (C3P)       | ---                | --- | --- | --- | :heavy_check_mark: | ---                | ---                 | ---                 | --- | --- | ---                | ---
EBIDS (CNR)          | ---                | --- | --- | --- | :heavy_check_mark: | ---                | :heavy_check_mark:  | :heavy_check_mark:  | --- | --- | :heavy_check_mark: | ---
ENIDS (FBK)          | ---                | --- | --- | --- | :heavy_check_mark: | ---                | :heavy_check_mark:  | ---                 | --- | --- | ---                | ---
HADES (UMA)          | ---                | --- | --- | --- | :heavy_check_mark: | ---                | ---                 | ---                 | --- | --- | ---                | ---
IntelFrame (DTU)     | ---                | --- | --- | --- | :heavy_check_mark: | ---                | :heavy_check_mark:  | ---                 | --- | --- | :heavy_check_mark: | ---
JUDAS (UMA)          | ---                | --- | --- | --- | :heavy_check_mark: | ---                | ---                 | ---                 | --- | --- | ---                | ---
NetGen (Polito)      | ---                | --- | --- | --- | :heavy_check_mark: | ---                | :heavy_check_mark:  | :heavy_check_mark:  | --- | --- | :heavy_check_mark: | ---
PP-CTI (UMU)         | ---                | --- | --- | --- | ---                | :heavy_check_mark: | ---                 | ---                 | --- | --- | ---                | :heavy_check_mark:
Reliable-CTI (UMU)   | ---                | --- | --- | --- | ---                | ---                | ---                 | :heavy_check_mark:  | --- | --- | ---                | ---
RoCe (UNITN)         | ---                | --- | --- | --- | :heavy_check_mark: | ---                | ---                 | ---                 | --- | --- | ---                | ---
TATIS (KUL)          | ---                | --- | --- | --- | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:  | ---                 | --- | --- | :heavy_check_mark: | ---
TIE (ATOS)           | :heavy_check_mark: | --- | --- | --- | :heavy_check_mark: | :heavy_check_mark: | ---                 | ---                 | --- | --- | ---                | :heavy_check_mark:
UASD (CNR)           | ---                | --- | --- | --- | ---                | ---                | :heavy_check_mark:  | ---                 | --- | --- | ---                | ---

# References
[1 - J. O. Kephart and D. M. Chess, "The vision of autonomic computing," Computer, vol. 36, no. 1, pp. 41-50, 2003.]

[2 - Y. Brun et al., "Engineering self-adaptive systems through feedback loops," in Software engineering for self-adaptive systems: Springer, 2009, pp. 48-70 .]

[3 - M. Guarascio et al., “D5.5: Cooperation With Threat Intelligence Services For Deploying Adaptive Honeypots”, CyberSec4Europe, 2021.](https://cybersec4europe.eu/wp-content/uploads/2021/10/D3.14-Cooperation-with-Threat-Intelligence-Services-for-deploying-adaptive-honeypots_2.05_submitted.pdf)

</br>

