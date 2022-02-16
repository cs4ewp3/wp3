Task 3.2 “Research and Integration on Cybersecurity Enablers and underlying Technologies” of CyberSec4Europe had as one of its main goals to identify research challenges, requirements and approaches in privacy preserving tools. 

# Research Challenges addressed

The main outcomes are the following set of research challenges related to security and privacy issues:

1. Providing mechanisms for control how the information is disseminated, and control the private data on the communication.
2. Providing a mechanism for guaranteeing proper identity management of things for authentication end-to-end.
3. Providing anonymization mechanism for control on how the information is stored and control the private data on the communication.
4. Providing automatic facilities for assessing and testing access control systems that regulate/limit access to personal data 
5. Unnecessary over-identification and information disclosure due to a lack of awareness and usability drawbacks. 
6. User's privacy-preservation of transactions in distributed and immutable systems (e.g., blockchains).
7. Honest but curious Service Providers and Identity Providers that might be tracking users.
8. When uploading information to the cloud the user partially loses control over the data.
9. When using secure computing to analyze data, analysts are not able to see the individual data values

# Updated version of enablers and components

In the last update the assets are deployed using the smart-campus ecosystem to leverage three main scenarios: CCTV surveillance in the smart-campus, Identity Management and Service usage in Smart Campus, and Geolocation Service in Smart Campus. 
In these scenarios we integrated a total of 20 assets, showing how the enablers can help to improve privacy protection on general systems.

#Summary:

**ARGUS**
* Summary: Cloud storage allows users to remotely store their data, giving access anywhere and to anyone with an Internet connection. The accessibility, lack of local data maintenance and absence of local storage hardware are the main advantages of this type of storage. The adoption of this type of storage is being driven by its accessibility. However, one of the main barriers to its widespread adoption is the sovereignty issues originated by lack of trust in storing private and sensitive information in such a medium. Recent attacks to cloud-based storage show that current solutions do not provide adequate levels of security and subsequently fail to protect users' privacy. Usually, users rely solely on the security supplied by the storage providers, which in the presence of a security breach will ultimately lead to data leakage. We implemented a broker (ARGUS) that acts as a proxy to the existing public cloud infrastructures by performing all the necessary authentication, cryptography, and erasure coding. ARGUS uses erasure code to provide efficient redundancy (opposite to standard replication) while adding an extra layer to data protection in which data is broken into fragments, expanded, and encoded with redundant data pieces that are stored across a set of different storage providers (public or private). The key characteristics of ARGUS are confidentiality, integrity and availability of data stored in public cloud systems.
* Video: https://drive.google.com/file/d/1OuPbu3vOw6Cxu5T34qQd2_B1dFVIsuaw/view?usp=sharing
* Main publication: 
Resende, João. "Security Enhancing Technologies for Cloud-of-Clouds" (2021). Universidade do Porto

**PTASC**
* Summary: PTASC presents a decentralized, secure device-to-device communications solution in which device provisioning is focused on improving usability while providing security by default. The solution focuses on using a PKI where the CA is represented by a manager device that can be switched on/off to reduce single point of failure (SPOF) problems. The solution combines public-key cryptography and symmetric keys with the One Time Password (OTP) concept using a secure token. Device identity is guaranteed by physical access to this physical token.
* Video: https://drive.google.com/file/d/1jBS7Re9J9FCdtBzexlyPbvIXyAk-leQT/view?usp=sharing
* Main publication:
Sousa, Patricia. "Privacy Preserving Middleware Platform for IoT" (2021). Universidade do Porto

**Interoperability and cross-border compliance**
* Summary: The Interoperability and cross-border compliance enabler address issues related to different eIDAS (electronic Identification, Authentication and trust Services) implementations and legislation differences in EU member states, ultimately hampering the idea of a Single European Market. To a lesser degree, the report also looks at the differences between Member states from the perspective of the GDPR.
* Video: https://drive.google.com/file/d/1CwyrUx7YDG9Gn95HdlfB1thBSGzRXrth/view?usp=sharing

**GDPR compliant user experience**
* Summary: GDPR compliant user experience is combined from two sections. The first is the Guidelines for General Data Protection Regulation (GDPR) which present the regulation's requirements through the GDPR principles. The second part of the enabler is the Data Protection Impact Assessment (DPIA) template. As the name suggests, this part of the enabler can be used to help guide the user through the process of doing a DPIA and also serve as documentation for the performed analysis.
* Video: https://drive.google.com/file/d/10SIv_nk2JC9Js5QQHTj0FKnBetERrwRo/view?usp=sharing                                                   
* Main publication:


**FlexProd and ArchiStar**
* Summary: FlexProd is an integrity- and privacy-preserving platform for distributed computations on potentially sensitive data, using ArchiStar libraries as subcomponents. Like Sharemind (cf. Section 4.14), FlexProd is based on secure multi-party computation, which allows multiple computation nodes to jointly perform computations on their respective inputs, without the other nodes learning any information about the other nodes' input. Users can now share their data using the ArchiStar secret sharing libraries, and store one share for each compute node, which can then perform, e.g., statistical analytics on data from potentially numerous users.
* Video: https://drive.google.com/file/d/105Aij5Szlo6CEZqX_9_PsbD_xES8bsG4/view?usp=sharing                                                   
* Main publication:


**Issuer-Hiding Anonymous Credentials**
* Summary: Issuer-hiding anonymous credential systems provide a mechanism for privacy-friendly identity management. They enhance over the state of the art by not only offering means for selective disclosure and data minimization (cf. also asset SS-PP-IdM (Section 4.3) and cloud-based credentials (Section 4.15)), but also allow for hiding the issuer of a certain credential.
* Video: https://drive.google.com/file/d/105Aij5Szlo6CEZqX_9_PsbD_xES8bsG4/view?usp=sharing                                                    
* Main publication:


**Cloud-Based Credentials**
* Summary: Cloud-based credential systems provide a mechanism for privacy-friendly identity management. They enhance the state of the art by not only offering means for selective disclosure and data minimization (cf. also asset SS-PP-IdM) but by additionally focusing on resource-constrained devices. This is achieved by outsourcing all computationally heavy operations to the cloud without putting a user’s privacy at risk.
* Video: https://drive.google.com/file/d/1jP6fU4oMATR2crVWEvAYmNWN7tkAMMNl/view?usp=sharing                                                    
* Main publication:


**Sharemind**
* Summary: Sharemind is a secure computing platform that consists of Sharemind MPC (based on secret sharing) and Sharemind HI (based on trusted execution environments). Here we will describe Sharemind HI, which is a development platform for the confidential analysis of data from multiple parties on a centralized server with full control overexposing the data and results to others.
* Video: https://drive.google.com/file/d/1PI7-vZ7yImfe83vR2t3LXuEJq1TEaCxU/view?usp=sharing	                                                    
* Main publication:


**Blockchain Platform**
* Summary: This asset provides a blockchain-as-a-service platform but with improvements over state-of-the-art solutions (e.g., Hyperledger Fabric) that address a number of important issues the technology suitable for the fintech world10. Namely: Privacy, Scalabilty and Lack of Governance.
* Video: https://drive.google.com/file/d/1GuLBCVfjheiWsLK-l2JYiKPn-Kdnxqqk/view?usp=sharing                                                   
* Main publication:


**GENERAL_D**
* Summary: Therefore, GENERAL_D asset (or enabler) has the following objectives: OBJ 1: defining a GDPR-based Life Cycle for authorization systems. This means to define a specific and integrated process development life cycle for the specification, deployment, and testing of adequate fine-grained authorization mechanisms able to take into account legal requirements.  OBJ 2: providing an integrated environment for automatically enforcing the data protection or privacy regulations. Indeed, we define an integrated environment where some of the available solutions are combined for: specifying the privacy requirements, controlling personal data, processing them, and demonstrating compliance with the GDPR in collecting, using, storing, disclosing, and/or disposing of the personal data GENERAL_D Life cycle.
* Video: https://drive.google.com/file/d/1y_7r1J7omVLsD3fF1A9_NIUT4vxe6y3J/view?usp=sharing                                                 
* Main publication:


**PP4Genomic**
* Summary: We presented a novel filtering approach to detect sensitive nucleotides in long reads, which are now produced by the newest sequencing technologies. In this context, our asset has focused on read filtering, i.e., the early detection of sensitive nucleotides in reads at the mouth of, and possibly inside, the sequencing machines. Requirements for an early read filtering method include i) to detect a maximum of nucleotide deemed sensitive; ii) not to be a throughput bottleneck (i.e., it must filter reads faster than the sequencing machine produces them); and iii) to be practical (i.e., it can be implemented in, or close to, a sequencing machine, with limited hardware resources).
* Video: https://drive.google.com/file/d/1BUR9Qo8RKhhKveNpIMfLcBjDiLFI3YeM/view?usp=sharing                                                   
* Main publication:

**Backdoor-resistant TEEs**
* Video: https://drive.google.com/file/d/1eAIAyy88FqoFjCeyIX4VeRAplNV8_m2u/view?usp=sharing
* Main publication:

**Elastic Deployment of TEE-based**
* Video: https://drive.google.com/file/d/1CudeUP_lcfLRifNSpxDm9InXmOlG8zJl/view?usp=sharing
* Main publication:

**Cryptovault**
* Video: https://drive.google.com/file/d/1dPYFWjUg3EMeatZ9LUB18RKb7r7qVCPE/view?usp=sharing
* Main publication:

**DANS**
* Video: https://drive.google.com/file/d/1VmyEBShh260Qa48ONsp9c38i_bxmC4T4/view?usp=sharing                                                   
* Main publication:

**Privacy-Aware Aggregate Programming**
* Video: https://drive.google.com/file/d/15_JW3VZW2OGxxQzXBfsJ1qxoOG18kCRk/view?usp=sharing                                                   
* Main publication:

**Edge-Privacy**
* Video: https://drive.google.com/file/d/1-HPavIH_7CXQluPhBqQGmpldVcI1xrph/view?usp=sharing                                              
* Main publication:

**Password-less authentication**
* Video: https://drive.google.com/file/d/1GpjutgdyqpWmXQ_AfIPByX7pOOIiqCC-/view?usp=sharing
* Main publication:

**SS-PP-IdM**
* Summary: SS-PP-IdM uses OLYMPUS virtual identity provider, which is comprised of multiple individual IdPs, to manage user identities and authentication. It relies on distributed p-ABCs to offer privacy- preserving (minimal disclosure and unlinkability) and authentication (presentation of attributes) linked to eIDAS. Moreover, the asset proposes a trust framework based on Blockchain to complement the usage of credentials.
* Video: https://drive.google.com/file/d/1gxqsa_pjZ1bFIbiojzUFOCzrdrzz3pNa/view?usp=sharing
* Main publication:


# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1,” CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)

[2 - J. Resende, "D3.13 Updated version of enablers and components"  CyberSec4Europe, 2021.](https://cybersec4europe.eu/wp-content/uploads/2022/02/D3.13-Updated-version-of-enablers-and-components-v3.0-submitted.pdf)

