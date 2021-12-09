

# Abstract
This task will explore the development of flexible security solutions that can quickly adapt security controls in response to security changes such as new attacks or changes in security requirements. To improve the modelling and  analysis  of  dynamic systems,  we will  provide  tools  and  techniques  to support  elicitation  and  representation  of assets, security requirements and threats, focusing on interconnected systems in various domains (e.g., cloud systems and Internet of Things). This task will also provide scalable architectures supporting security situation computation and risk assessment, and also selection and deployment of security controls that could satisfy security requirements and  policies,  also  enabling  awareness  of  the  current  system  status.  Finally,  the  acceptance  of  adaptive  systems  by stakeholders will be addressed developing techniques to provide explanations (assurances) about why certain security controls should be adapted.


# Overview
In the last years we have seen an increasing amount of large-scale, severe breaches, such as the Equifax
breach in 2017  or the Marriot breach in 2018. Such events pose huge costs to organizations and
governments. For example, the average cost of cybercrime by consequence of the attack in 2018 was
estimated to amount to $13 million. Cyber attacks can also threaten critical infrastructure and disrupt
individual’s lives. For example, in October 2016, the Mirai botnet caused disruptions of major sites such
as Etsy and Twitter . Although security has been considered a critical concern during the design and
development of modern software systems, the number and severity of cyber security incidents is expected
to increase in the next years .
One of the reasons behind this is that software systems are traditionally developed by enacting static security
controls. However, unanticipated changes can occur in the environment where the system operates (e.g.,
new assets require to be protected), in the system itself (previously unknown vulnerabilities are discovered)
and/or in the security properties
that a system must satisfy. These changes may render ineffective the security controls deployed, making the
system more vulnerable to potential attacks. Note that although security controls support the satisfaction of
security properties, they can negatively affect other requirements, such as usability and performance. Thus,
different approaches have been proposed in previous research to build adaptive security systems , which
can self-protect from the varying risk of harm by adjusting their security controls, in a way that minimally
impacts other system requirements.
Surveys about adaptive security systems demonstrate that existing research in this domain has
been fairly recent. Existing surveys have mainly focused on how adaptive security systems are designed and
implemented, without considering other important dimensions such as the who and why dimensions. The
“who” dimension covers the interactions that an adaptive security system has with its stakeholders who
design, build, use, and certify it. While, the “why” dimension covers the objectives that an adaptation of
security controls should achieve. Also, existing surveys focus on adaptive security systems proposed for
purely software and large-scale systems, without considering the application domains where adaptive
security systems have been adopted.
# Content
## Roles
### The Role of Stakeholders in Adaptive Security
The majority of the surveyed papers were aimed to securing communications in
IoT systems (33%), mobile devices (15%) virtual and private networks (12%), cloud and web services (12%)
and autonomous vehicles (9%). A central problem in these domains are to balance the tradeoff between secure communication, performance and energy consumption.
Other approaches have been applied to prevent security threats and hazards in smart buildings (9%), or are
application-independent. One of the papers that was surveyed considered securing blockchain-based logs.
An interesting finding is that user authentication did not emerged as an application domain. This is surprising
considering emerging research on continuous authentication and current “zero-trust” approach. . As cyber-physical systems are becoming more ubiquitous more holistic adaptive security solutions able to analyze the extended attack surface
of cyber-physical systems should be provided. These solution should be capable to enact and
coordinate security controls in both the cyber and physical spaces where the system operates.
### The Role of Stakeholders in Adaptive Security
We identified three types of stakeholders: users, software engineers and security engineers/human operators.
Users can trigger changes in the security controls. Thus, their (personal) data may need to be monitored
during the adaptation loop to select security controls. Also, enactment of security controls can affect the
user’s interaction with the system. However, existing work on adaptive security has not focused on how to
inform users about what personal data are required to be collected for adaptive security purposes. Existing
research has provided information and explanations about enacted security controls in the form of warning
messages or arguments, generated by exploiting traceability links between security policies,
requirements and domain assumptions. Software engineers are responsible for designing and implementing
the adaptive security behavior of the system. To support software engineers, previous work has considered
providing them with scenarios  and formal languages  to specify adaptive security requirements.
Finally, security engineers and operators can provide insights about effectiveness of security controls during
decision making. However, no artifact has been proposed to encourage their involvement in the analysis
and planning activities of the adaptive security loop.
### The Role of Requirements in Adaptive Security
* Detection. Previous research on adaptive security has tackled the problem of security threats and attack
detection rather sporadically
* Prevention. The majority of existing approaches proposed to support adaptive security are aimed to prevent
security threats and attacks. 
* Mitigation. Surprisingly, very little work has focused on adaptive security strategies that could
adaptively support harm containment after an attack occurs.
* Management of Trade-offs between Security and other System requirements. Management of the
tradeoff between security and other requirements of the systems has been considered in various application
domains.
* Mathematical functions have been often used to represent and measure trust of messages’ senders in
wireless sensor networks and cloud services , in order to identify an appropriate
authentication and encryption mechanism to be adopted
* Rule-based approaches have been proposed to guide decision making.
* Stochastic games have been used to balance the tradeoff between conflicting requirements in IoT systems.

## Recommendations
### A holistic approach to adaptive security
It is necessary to design and develop adaptive security solutions that can be applied to heterogeneous cyberphysical systems composed of cyber, physical and human components.
### Integration between adaptive security objectives
Adaptive security systems should be designed with the capability to enact and adapt their adaptive security
objectives (detect, prevent and mitigate). 
### Explicit consideration of the stakeholders
Existing adaptive security systems should be designed assuming that their stakeholders can be involved in
the execution of some of the activities of the MAPE loop.
### Perpetual security assurances
Existing adaptive security approaches have used formal techniques to support decision making.
### Reducing security uncertainties
Existing adaptive security approaches operate under the assumption that the possible set of security controls
is pre-determined and do not evaluate effectiveness of security controls at runtime.
