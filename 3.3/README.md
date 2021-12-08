
# Abstract


# Overview


##  List of Content

### Assessing Security and Privacy Through the Entire Software Life Cycle 
#### Scenario 
A European consortium develops a new platform to support and promote sharing of medical data.
A long, thorough, process involving significant human resources is spent to certify that the platform
lives up to the strictest security and privacy regulations and guarantees. European hospitals,
pharmaceutical companies, and research institutes start using the platform as an effective tool to
boost research and development of new medical treatments. Shortly after the deployment of the
platform, a new cybersecurity threat is discovered. The users of the platform demand that the
consortium proves that their system still lives up to the security and privacy requirements despite
of the new threat. How can the consortium effectively show, at any time, and with reasonable effort,
that the platform is secure and privacy-respecting? 
#### Research Challenge
Security and privacy goals cannot always be assessed once and for all. Existing regulations like
GDPR depend on “the available technology at the time” , and new regulations are likely
to be introduced as a response to new threats and societal demands. Moreover, software is
continuously subject to updates and replacement of software units in the entire stack. As a
consequence, a software system that is deemed secure and privacy-respecting today, may not live
up to security and privacy guarantees tomorrow. Security and privacy goals must be considered
from the foundation of software systems and must be assessed continuously through their entire
life cycle, also after deployment and even after decommissioning. Such assessments can be
expensive, time-demanding and unreliable unless they are supported by effective, automated
analysis and verification tools based on theoretically well-founded techniques. 


#### Short-Term Research
Software must be developed with proactive security- and privacy-by-design methodologies that
consider security and privacy as part of the blueprint in all phases of its life cycle, from conception,
design and realisation, to deployment, operation and decommissioning. This requires the
development of modelling and programming languages supporting security- and privacy-by-design
methodologies, with by-construction and static analysis guarantees , and of automated tools
to verify, measure, assess and monitor security and privacy properties, risks and vulnerabilities
along the entire life cycle of software. We plan to conduct research in three key areas of research,
namely (i) logical foundations of privacy and security, (ii) protocol verification, and (iii)
quantitative security. 
#### Long-Term Research
The dominating approaches to development are agile and prioritizing fast deployment over security
and privacy guarantees. More research is needed to develop tools and techniques to support secureand privacy-by-design techniques within agile approaches, so that competitiveness and fast
deployment are not compromised by security and privacy requirements and so that changes in
privacy and security requirements can be efficiently reassessed even after the system has been
deployed. 
Research efforts are needed to further develop and promote lightweight formal methods that can
be gradually applied to increase the levels of assurances obtained. Methods must be developed to
support a spectrum of guarantee levels, each providing greater assurance but also requiring more
work, at a level more approachable than the common criteria . The enforcement must be
gradual in order not to close the opportunity for SMEs to deliver the software systems used in EU,
and appropriate tool support is need. Industrial compliance would be enhanced if GDPR were to
be extended with requirements for using formal methods and tools. 
### Assessing Privacy Properties of Complex Systems 
#### Scenario
Data is a treasure trove and having the right data in a right place can bring about enormous value
while at the same time posing challenges to privacy. Examples of such tension between
functionality and privacy can be found in the medical domain and, in particular, in systems like medical exchange platforms. We keep building such complex systems to support the exchange of data between
different parties, and to jointly perform data analyses, in order to find the best pharmaceuticals or
to design the best medical services. These systems have to find the right balance and present the
appropriate choices between the functionality offered to the users, and the privacy offered to the
data subjects. 
#### Research Challenge
Complex systems like the ones mentioned above release variously processed data to the involved
parties, thereby potentially violating the privacy of data subjects. Methods for assessing privacy
properties of complex systems are needed1
. Currently, there are no good means for the data subjects
to communicate, which pieces of their data they consider more or less sensitive, and the release of
which pieces could be acceptable for them, perhaps as a trade-off of certain benefits to themselves.
We also lack the analysis methods for these computational systems, in order to verify whether and
to what extent they satisfy the policies of data subjects. We do have certain definitions for output
privacy with better or worse compositional properties and thus amenability to
automated analysis, but these properties likely do not match well with the statements that data
subjects want to make about the use of their data . 
#### Short-Term Research
The challenge needs to address research developments in at least the following three areas: (i)
privacy definitions for complex systems, (ii) privacy policy languages for complex systems, and
(iii) privacy analysis for complex systems. 
#### Long-Term Research
In long term, we expect the analyses to become more holistic, considering at the same time the
privacy, utility, and efficiency properties of the systems and their trade-offs. We expect there to be
automated enhancements for complex systems, mostly concerning the placement of additional
PETs, or specifying the details of PETs. The
selection is made based on the results of privacy analyses, and has to consider the trade-offs
between privacy gain, utility loss, efficiency loss (all these potentially for each stakeholder of the
system), and invasiveness of modifications. 
### Privacy protection and User Empowerment in the Internet of
Things
#### Scenario
Modern cities are facing increasing pressure to become more efficient from economical, societal
and environmental standpoints. This has motivated a closer integration between different domains,
namely, transportation, energy, management and services. For every stated domain, there exists a
vast number of sensors spread within the cities, generating a significant volume of data. Several
smart-cities projects have appeared in the past trying to explore this data to promote a more efficient
and cost-effective management of the city. Nevertheless, most of these projects failed to succeed
in attaining safer cities, as the underlying platforms were not designed by default to be secured and
privacy friendly as they should be. 
#### Research Challenge
The ever-increasing volume of data produced by the Internet-of- Things (IoT) undermine some of
the fundamental privacy principles, including informative self-determination, data minimization,
consent and the rights to individual access . In most countries, public and private entities
should limit the collection of personal data to the bare minimum necessary towards achieving the
intended goals. Furthermore, these entities should also delete the data that is no longer required for
the purpose it was collected. However, a large set of companies
and entities are located in countries that do not legally enforce these obligations. This allows large
sets of data to be collected and used without respect for those international privacy rights. Therefore
it is mandatory to find mechanisms to ensure an adequate level of privacy protection and user
empowerment, through new applications and services based on access to personal information, in
order to solve the existing tension between legislation and technology . 
#### Short-Term Research
We plan to address some of these challenge by focusing on a set of key research problems: (i)
Identity management in the IoT, (ii) Authentication, Authorization and Access Control in the IoT,
and (iii) Secure infrastructures for the IoT. 
#### Long-Term Research
Given the volume and rising tide of increasingly sophisticated digital attacks, current environments
and platforms are unable to ensure data security, including data integrity and confidentiality .
This evidences that traditional approaches based on static or passive defense mechanisms are not
enough, and that systems have to evolve and offer introspection guarantees for ensuring security
even in the presence of intrusions.
Additionally, requirements for computing data containing sensitive information, renders the use of
public cloud infrastructures impossible given the inherent trust models. These rely solely on the 
reputation of providers, and no guarantees of enforcement can be made about possible introspection
on the workloads in these scenarios, either from internal actors or due to compromised
infrastructure.
Techniques such as homomorphic encryption  and multi-party computation [Gol98,
Can00] have shown potential for preserving strong levels of privacy when storing and processing
data on untrusted parties. However, performance and scalability issues still hinder their feasibility
in real-world deployments. This is especially true in contexts where large amounts of data are to
be securely stored and processed.
Thus, we envision the need for active or dynamic defense mechanisms (e.g., intrusion tolerant
solutions) allowing system to adapt and respond to attacks. However, the development and
deployment of highly resilient and secure infrastructures carries massive computational and
communicational overhead, as well as configuration and management burdens. Thus, more
research efforts are needed in order to achieve the goals of secure cyber infrastructures. 

### Securing Unsafe and Legacy Software
#### Scenario
Despite a significant evolution in software engineering and programming languages during the last
decades, many safety-critical domains still rely on legacy systems or even systems developed with
unsafe programming techniques. A paradigmatic example of such domains is the maritime
transport domain. A very frequent form
of software is memory unsafe systems, usually written in C/C++, where code can freely access
memory at run-time. This is a benefit for performance and sometimes required for certain
functionality, e.g., operating-system kernels need to read and write memory with no constraints.
Nevertheless, unconstrained access of memory may have severe consequences during attacks if
software contains memory-error vulnerabilities. Several such bugs can be abused and transformed
to powerful exploits using inputs, which drive the vulnerable program to perform malicious actions
(e.g., download malware) or to exfiltrate sensitive data by over-writing and over-reading its
memory intentionally. For example, consider the popular WannaCry ransomware; a program that
could randomly compromise vulnerable hosts, and propagate through the network. The
particular ranswomware did not leverage the human aspect for compromising hosts (i.e., a human
that accidentally clicks on a malicious link), but a memory bug found in the Windows kernel, and,
in particular, in the Server Message Block (SMB) –a protocol for mounting remote volumes of
storage– implementation . 
#### Research Challenge
Currently, there are different techniques for addressing memory unsafe programs. For instance, by
identifying and eliminating memory errors before deploying software or by entirely writing all
code using a safe programming language. Such solutions can be carried out during the early stages
of the software life cycle. Consider, for example, that identifying and eliminating errors can be
done using software testing and formal verification. However, such solutions are less adequate
when dealing with already running software and even worse with legacy software where testing,
verification and re-development may be difficult. There is an urgent need for Securing Unsafe and
Legacy Software of this kind. 
#### Short-Term Research
Within CS4EU we will address this challenge by developing research approaches for software
hardening. We elaborate below on the mechanics of software hardening, as well as on the available
options we have and we plan to investigate. Additionally, in our short-term research efforts, we
will explore and collect the different properties and requirements of a broad set of software
programs, since there is currently no universal method for hardening unsafe code. 
#### Long-Term Research
In the long term, more systematic effort should focus on strengthening software by design.
Hardening approaches should be included in state-of-the-art industrial compilers, completely
unsafe systems should be reduced (in terms of code base) and more research should be carried out
for standardizing these techniques. 
### Protecting Leaked Credentials
#### Scenario
Several applications, especially web apps, require an authentication component. For realizing this
component, text-based passwords are still the dominant option. Beyond the many usability issues
associated with handling several text-based passwords, security is also an important dimension.
Through the years, a significant amount of on-line services has been compromised and their stored
passwords have been leaked. Once the database is compromised, it takes little time for a program
to crack the cryptographically hashed (weak) passwords, no matter the algorithm used. The need
for protecting credentials once leaked is important for applications that handle sensitive personal
data.
#### Research Challenge
Despite the many technological investments and research, the protection of leaked
credentials is still an open problem. There is a need to develop novel approaches to protecting
leaked credentials.
#### Short-Term Research
Within CS4E we will address the challenge of protecting leaked credentials by developing
approaches to build easy-to-enable password-hardening services.
#### Long-Term Research
Someone could argue that credential leaks are possible, since currently authentication mechanisms
rely heavily on storing credentials that can fully authenticate anyone that has access to them. In the
past, there were protocols proposed that relied on storing part of the information needed (in the
form of a cryptographic challenge) to the server, nevertheless, their adoption was limited.
Today, researchers continue work on realizing systems that divert from the typical storage of reusable hashed passwords on the server. Unfortunately, such efforts need
substantial changes in how authentication works and, in many cases, the interface exposed to the
end user may change, imposing further usability challenges. However, we anticipate that the
myriads of problems stemming form currently deployed authentication systems will drive research
to new mechanisms, where credentials may have an entirely different form than the one we know
today. 
### Secure Access Control in Heterogeneous Systems 
#### In complex systems where a large number of agents are accessing many different kinds of services
provided by a multiplicity of software agents, it is critical to ensure that the logical and physical
interactions between these types of agents do not affect negatively the security properties of the
overall system. In particular, we consider heterogeneous systems where different types of network
architectures and providers are connecting devices of different natures, ranging from standard IT
equipment to special purpose embedded devices. Examples of such cases are easily found in
industrial systems and critical infrastructures where physical and cyber activities are strictly
intertwined. Such a scenario is also reflected in Smart Cities where
human agents perform heterogeneous tasks interacting with complex physical and cyber services
provided as a combination of several distributed components. 
#### Research Challenge
The challenge is to achieve secure access control in complex heterogeneous systems. In the
considered scenarios, the challenge stems from two main considerations: the first is that the
heterogeneous nature of the involved components is reflected in a non uniform distribution of
capabilities of their security mechanisms. Some elements, such as sensors, have low computational
power and other limitations (e.g. low energy consumption constraint) that greatly limit the security
mechanisms that can be deployed. The second consideration is that while a resource can behave
correctly in isolation, the situation can dramatically change when the same resource is then
combined with others. In practice, the challenge here is to be able to analyze and assess the security
of the overall system taking into account all its limitations and characteristics including all the
possible behaviors of the operating agents. 
#### Short-Term Research
Within the CS4EU project, we will pursue three directions to address this challenge: (i) use formal
verification approaches to secure access control, extending formal models to include other possible
causes of security threats in the system, and developing an approach able to propose solutions to
the identified problems.
#### Long-Term Research
One of the main problems that will become more urgent in the future, is the sheer number of objects
involved in the considered complex systems. Thinking specifically to the Smart Cities examples,
not only the number of agents and services involved will continuously increase but also the
complexity of their relationships and dependencies in the composition of more and more complex
services. In terms of security this will further expand the attack surface of the overall system.
Moreover, the complexity of the composition and interactions between agents and resources will
possibly hide new forms of cyber attacks and this must be addressed by general enough analysis
approaches that, at the same time, ensure scalability and efficiency.
This will exacerbate the already identified problems of the interpretation of the analysis results and
the process of finding a possible solution. In this matter, future research activities could focus on
the automatic generation of system configurations that, moreover, can be prepared in advance in
order to react quickly to adverse events. To support this approach it will also be necessary to
develop and further extend the use of formal methods in the verification of the involved models as
the effective usage of formal approaches is greatly affected by the increasing complexity of the
analysed systems. Another future problem to be addressed is the “live” identification of system
conditions and events that could lead to critical states. In the real world, events can happen in fast
sequences that should be quickly analysed and addressed in real-time. This will require a balance
between a deep enough analysis (to obtain correct and complete results) and a fast one. 
### Manageable and Understandable Security Engineering 
#### Scenario
The shift from traditional computer systems towards the Internet of Things, i.e. devices connected
via the Internet, wireless communication or other interfaces requires a reconsideration of secure
and trusted systems engineering processes. Especially, the introduction of mobility and its leitmotiv
“anytime, anywhere” reinforce this complexity due to the need of enabling various means of
connectivity, such as Ethernet, Wi-Fi, 5G and so on. Security is concerned with ensuring a system
is protected from accidental or deliberate external attack, some of which may target the system’s
reliability. Modern software systems existing in critical domains consist of many distributed and
interacting components that rely on extensive communication to achieve their intended
functionality. Efforts to secure such systems include securing the underlying infrastructure, the
information that they store, use and communicate. Scenarios from safety-critical domains like
healthcare , where humans and IT systems, including wearables, where human life is
at risk is a perfect example.
#### Research Challenge
Achieving manageable and understandable security engineering is challenging due to a set of
issues. (i) The need to exploit modeling languages and formal methods at a reasonable cost in an
industrial context. Contrary to the other aspects, security engineering requires well defined and
precise solutions to develop an accurate analysis, for evaluation and / or certification. In addition,
the early stages are not suitable for beginners (architects with llittle experience in the engineering
of secure systems), given the sensitive and delicate character of these systems. (ii) The need to
ensure conformity, validation and certification. Safety-critical systems are usually accredited or
certified. We must implement other types of software and means of generating validated artifacts,
such as programming language code and certification artifacts, which are capable of producing a 
restrictive set of artifacts that comply with domain standards. In other words, can we certify an
application by using security patterns? Can we show that a system built based on the use of security
patterns is secure? Intuitively, we can show that the application includes a pattern able to stop each
expected threat by a simple matching of threats to patterns. If we have a pattern for each threat, we
can consider the system secure at the model level.
#### Short-Term Research
We will address these challenges to make the security engineering process manageable and
understandable using novel methods and tools for engineering secure systems using patterns,
models and formal reasoning that ensure that system security solutions are built by design. We use
Model- Driven Engineering (MDE)  abstraction mechanisms to define and handle software
architecture maturity properties, threats and requirements through a metamodel that unifies those
concepts. In the context of our work, formal methods  will be used for the precise
specification of security and architecture. These techniques will be used to support validation of
security and architecture properties during the pattern-based security engineering process,
including properties of compositions of security properties. In particular, we introduce a new
formal modeling paradigm for software system security engineering within a pattern-based
approach as a foundation for novel security engineering practices. In particular we plan to advance
the state of the art in security for systems engineering in three relevant areas: (i) security properties,
(ii) threats and (iii) patterns. We employ the MDE and Domain Specific modeling 
technologies and attempt to add more formality to improve parts of the system design.
#### Long-Term Research
There is a need to ensure continuous (safe) service, and minimal maintenance costs. In a context
of fast changing cybersecurity threats, and ever emerging vulnerabilities, long-lived safety-critical
systems require a high level of maintainability. Maintenance in secure conditions (e.g., security 
patch installation) should be possible without having to re-accredit or re-certify the system.
Currently some security patches on systems are simply skipped because modifying the code, or
updating an anti-virus database, would require running the accreditation or certification process
anew. This situation is not sustainable. Architectural patterns may be suggested for the maintenance
under security conditions (MSC) of safety-critical systems.
With the expected results, it may also be possible to further study the relationship between threats
that have been detected in the software architecture model to determine whether the existence of
one threat facilitates the existence of another. As we have seen in the past, adversaries often will
exploit one vulnerability (which leads to a threat) in order to exploit another vulnerability to
escalate their reach in the system. The formal setting of the specification and detection of threats
approach will provide many essential mechanisms that will enable this kind of reasoning to aid in
identifying the root causes leading to the existence or emergence of detected threats. Such a
capability is expected to have a major impact on the time and resources required to treat treats in
software systems. 

### Unreliable Risk Estimates 
#### Scenario
In 2017, a collision between an American military vessel and a civilian container ship killed 10
sailors. The investigations following the event revealed that part of the accident was due to the
pilots failure to understand how the touch screen-driven integrated bridge and navigation system
worked. Further, the federal safety investigators found that when the system was in computerassisted manual mode, watch standers behind other stations could unintentionally and unilaterally
take over steering control. The story illustrates that digitalization of safety critical systems
comes with a risk. In this case, the accident was caused by a unintended failure, but we can very
well imagine even more severe incidents when we take the increasing cyber threat picture into
account.
#### Research Challenge
There is a large body of knowledge, data and statistics available for risk assessment when the events
that are taken into account are caused by random failures. Hardware failures are statistically
predictable, and methods exist to assess the reliability and security of software, under the
assumption that the software will not be updated or changed. In contrast, cybersecurity risk
estimates today tend to be based on gut feeling and best guesses; the main reasons being the lack
of relevant publicly available historical data, the ever- increasing threat picture, the constant
disclosure of new vulnerabilities and the subsequent roll-out of patches to address them, and the
difficulties to foresee security incidents that have simply never occurred before. Improved
justification and traceability of cybersecurity risk estimates can be achieved through data-driven
decisions. This is, however, not straight-forward to achieve. With evolving technology and
constantly emerging attack methods (and motivations), basing security decisions on past incidents
is typically referred to as driving by looking in the rear-view mirror and cannot be considered
reliable.
To provide better and more accurate estimates of cybersecurity risks, we will need to apply datadriven models that are looking into the future, rather than providing a historical picture. More
specifically, we need to understand what types of empirical data that can be used as relevant input
to cyber risk models. We also need to survey the possible sources of such data, and to investigate
how the data can be aggregated and combined to form indicators of cyber security risks. Such
knowledge and such models will be a fundamental part of assessing cybersecurity risks for evolving
systems.Typical sources of the empirical data include: logs, statistics, measurements, expert
judgments and thought experiments. They are often combined in order to instantiate the risk
indicators and obtain the estimates. 
#### Short-Term Research
To address the above described challenge we will investigate research approaches in the area of
requirements for data-based risk estimates. 
####Long-Term Research
Security risk indicators can only be as as good as their validity and reliability. Particularly indicator
definitions, usage of the indicators, as well as the quality of indicator data sources are subject to
validity threats. We therefore need to provide explicit and structured guidelines for assessing the
validity and reliability of the indicators. There should also be established guidelines for improving
the levels of validity and reliability of the indicators in general and their data sources in particular.
The guidelines should comprise methods of maintaining, removing and adding indicators in the
risk models, as well as ways of interpreting the indicator values. The guidelines should be targeted
towards pre-defined stakeholder groups, i.e. the major roles being involved in developing and using
the evidence-based security risk models. 

### Automated and Verified Network Security Configuration in Highly Dynamic Environments 
Scenario
A European service provider company operating in the field of smart cities, stimulated by the
requirements for higher dynamicity coming from its customers, has decided to introduce
automation of network management, based on the emerging network softwarization paradigm. Two
main innovative technologies are introduced. Network Functions Virtualization (NFV),
which allows the company to substitute hardware components with software modules that can be
deployed on general-purpose servers with agility, and Software-Defined Networking (SDN), which allows the company to control and dynamically adapt its network architecture
by means of software. Even though these technologies already provide ways to ease the work of
the company’s network administrator, all the tools that he or she exploits in this virtualized
environment – i.e., NFV and cloud orchestrators, such as Open Baton and Kubernetes – mainly
target general network management, without providing enough automation of network security
management. As a consequence, the network administrator of this company must manually create
the virtual services and configure each network security function. This manual approach is,
however, leading to a number of drawbacks. Firstly, the time required for a manual configuration
is very high: the administrator has to carefully analyze the security requirements of the service
users and then manually access to each function to install the proper configuration. Secondly,
human operations are difficult and error-prone: in a distributed network architecture, the
introduction of anomalies in the configuration of the functions is difficult to avoid, opening the
path to several cybersecurity attacks. Because of these reasons, the service provider network has
already been victim of a number of attacks; this should not be surprising, because in the world
misconfiguration has actually become the third most frequent cause of breaches for attacks, with
an increasing trend from the previous years. Similar scenarios may occur in smart city
environments like the ones described, where solutions that make it easy to
protect and isolate parts from vulnerabilities are envisaged. 
#### Research Challenge
The main challenge is that providing automatically a formally verified solution is very complex,
especially when the complexity of the network increases. Of course, this complexity contrasts with
the need for fast operation. 
#### Short-Term Research
The formal verification problem, i.e. checking the correctness of a given security configuration,
which is less difficult than the synthesis problem addressed by this challenge, can be solved with
reasonable computation resources, even for large networks . The expected trend
of research for the next few years is to make also the automated search of a solution feasible for
dynamic virtualized networks, at least for the most common security functions. Within CS4E, we
are committed to work on this challenge with research in two directions, namely (i) automation of
network security functions and (ii) performance and scalability of such automations.
#### Long-Term Research
The improvements on performance and scalability that are possible in the short term will not
probably lead to techniques capable to deal with very large networks, such as the ones that can be
created today in large data centers. In the long term, we expect a continuation of the research along
this line, in order to finally achieve this goal. When considering large cloud-based networks,
another aspect which research will need to address in order to achieve full network security
autonomy is the automatic elicitation of security policies. Currently, an automatic process still
needs interaction with a human being from which it receives the security policies that must be
fulfilled by the computed configurations. Instead, in the future, an autonomic process could extract
the information needed for policy refinement from the network itself, thus closing an actionreaction loop that would not involve external interventions anymore. This would require the
definition of intrusion prevention methodologies that would be able to perform the so-called policy
discovery – i.e., extraction of policies from network monitoring –. New algorithms based on
machine learning and artificial intelligence could be defined to perform the autonomic
reconfiguration of the security service whenever the statistics computed from the extracted
information would characterize an ongoing cyber-attack. Alongside with this achievement, a fully
autonomic platform should be also capable of keeping safe all the service functionalities even in
short periods where some security defenses have been temporarily compromised, until a full
reconfiguration does not confine the danger. 
### Scalable and Private Industrial Blockchain 
#### Scenario
Supply-chains are complex systems moving products or services from suppliers to customers.
Supply-chain processes unfold over a multitude of stages and geographical locations, making it
very hard to trace particular events and investigate incidents. It also makes it more difficult to track
the ownership of goods and inventory at each step. Furthermore, transactions between these
companies usually involve manual paper transfer of records (orders, invoices, etc.), a costly
bureaucracy subject to human errors, losses, damages, thefts, and frauds. This inherent complexity
only leads to economical losses, inefficiencies, and delays that will upset both a company’s health
and its customers’ satisfaction. Customers have no reliable to way to verify and validate the value
of the goods that they purchase, because of a lack of transparency and prices that do not reflect the
true costs of production. In some extreme cases, there might be serious legal consequences. In a
hard to manage supply-chain it is hard to detect illicit activities such as counterfeiting, or forced
labor in factories. 
#### Research Challenge
Existing blockchain deployments have shortcomings that researchers must address For
example, supply chains comprise many organizations willing to share information with a restricted
number of partners. However, in existing blockchain architectures, transactions and their
information are public. Encrypting transactions is insufficient because it still allows everyone to
know when an exchange occurred.
Another key problem issue is scalability. Permissionless blockchains’ (e.g., Bitcoin) scalability is
excellent, but they sacrifice the network’s throughput (e.g., Bitcoin achieves 7 transactions per
second). On the other hand, permissioned blockchains can reach a higher throughput at the expense
of scalability. The challenge here is to design an architecture able to scale to thousands of nodes
without sacrificing throughput.
Finally, supply chains comprise private organizations and service providers that want to oversee
their business networks and be able to grant or deny access to their services.
#### Short-Term Research
Within CS4EU we plan to address those challenges with research activities in three areas: (i)
scalable secure and practical consensus layers, (ii) smart contract security, and (iii) efficient
privacy-preserving blockchain protocols. 
Approaches to achieve scalable and private industrial blockchains need to be investigated. 

#### Long-Term Research
The research goals listed above are fundamental building blocks to a secure blockchain system. On
the long run, the goal is to combine those building blocks in a unique blockchain solution ready to
tackle industrial challenges. We will also focus on how to make the blockchain compliant with
important EU regulations. For example, the immutability of the blockchain’s ledger does not sit
well with the EU General Data Protection Regulation (GDPR). The blockchain is able to securely
handle users’ data, but it needs to do it according to EU regulations, or industries and citizens will
not adopt it. A possible solution could be storing only metadata on the blockchain, but we will
investigate more to find the best possible solution(s). 
### Scaling TEEs for Cloud Applications 
#### Scenario
Smart cities are expected to generate a vast amount of data from a multitude of heterogeneous
sensors . Creating value out of such data require distributed algorithms and considerable
computing resources. If computing resources are not available “in-house”, the cloud is an effective
alternative to process large amounts of data with a small investment. However, data generated by
sensors in smart cities is likely to carry sensitive information that should not be disclosed to a thirdparty data processor such as a cloud provider. 

#### Research Challenge
Trusted Execution Environments (TEE) allow running private computations in untrusted
environments. As such, they represent a promising solution to the problem of cloud-based data
processing in scenarios where data to be processed must be kept hidden from the host.
Nevertheless, current TEEs are not compatible with cloud deployments where elasticity and
resources consolidations are key to the cloud provider business. In particular,
applications running in the cloud are dynamically assigned resources depending on the current
load. Further, the cloud minimizes the number of used resources by co-locating different
application on the same hosts. Thus, running an application in the cloud requires that the cloud
provider be able to add or remove instances of an application depending on the current load, and
to migrate instances of an application across machines. Current TEEs simply do not allow such
operations. 
#### Short-Term Research
In the context of this CS4EU we plan to design protocols that enable the use of TEEs in cloudbased applications. 
#### Long-Term Research
Short-term research must cope with the design of available TEEs and provide ad-hoc solutions to
its shortcomings. Long-term research should address the weak points of current TEE “by design”.
In particular, during the long term we plan to design novel TEEs that keep the expected property
of security and privacy while, at the same time, offer enhanced flexibility to be used in different
scenarios, from stand-alone client machines to massive cloud deployments. Cache reservation
mechanisms will be explored as well as hardware-software co-design, with the goal of mitigating
side-channels while minimizing the trusted computing base. Alongside “clean-slate” TEE desing,
we will also explore minimal set of changes required in available TEEs in order to minimize
vulnerabilities. This activity will provide guidelines to manufacturers to design future revisions of
their TEEs.
