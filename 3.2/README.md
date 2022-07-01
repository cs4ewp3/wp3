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
* Summary: Sharemind is a secure computing platform that consists of Sharemind MPC (based on secret sharing) and Sharemind HI (based on trusted execution environments).
  * Sharemind MPC uses secret sharing and secure multi-party computation to protect confidential data at rest, in transit and in use. Data is secret-shared by the data provider at the source. All calculations on secret-shared data are done using secure multi-party computation, thus protecting data during the whole analysis lifecycle. Even the Sharemind MPC hosts providing the service will not have access to unencrypted data. Sharemind MPC is built as a client-server service. The solution is based on tasks that run on Sharemind virtual machines that compute on secret-shared data using hundreds of implemented protocols for different operations and data types.
  * Sharemind HI is a development platform for the confidential analysis of data from multiple parties on a centralized server with full control over exposing the data and results to others. The data is encrypted at the source, by the data owner, and only then sent to the Sharemind HI service. The host of the service will not have access to the unencrypted data nor the encryption keys. Sharemind HI does not remove the data protections even while processing it, the data will remain protected by cryptographic means during the whole analysis. Sharemind HI relies on a trusted execution environment (TEE) technology to provide security guarantees. A TEE isolates the security sensitive parts of an application from the rest of the system with the help of trusted hardware. The TEE technology used in Sharemind HI to implement the privacy-preserving data processing is Intel® Software Guard Extensions (SGX) which is available in modern Intel® processors.
* Video (Sharemind HI): https://drive.google.com/file/d/1PI7-vZ7yImfe83vR2t3LXuEJq1TEaCxU/view?usp=sharing	                                                    
* Video (Sharemind MPC): https://drive.google.com/file/d/1WDxKVk6dZIhwL4wBYVt9sFRY8nvbxNWq/view?usp=sharing
* Sharemind MPC overview and documentation: https://docs.sharemind.cyber.ee/
* Main publication: Bogdanov, D. "Sharemind: programmable secure computations with practical applications". PhD Thesis. 2013. University of Tartu Press. https://dspace.ut.ee/handle/10062/29041


**PLEAK DP analysers**
* Summary: The web-based tool PLEAK (pleak.io) has been described in Task 3.3 (https://github.com/cs4ewp3/wp3/tree/main/3.3). PLEAK allows to model and analyse business processes specified in privacy-enhanced Business Process Model and Notation (PE-BPMN). It supports several different kinds of privacy leakage analysis of PE-BPMN models. This asset analyses the need and determines the parameters for differential privacy in PLEAK. The definition of differential privacy is based on comparing two settings: when the output is computed from the input with the private data of Alice, and without private data of Alice. It assumes a probabilistic output. If the probability of getting the same output in both cases is “nearly” the same (quantified by a privacy parameter ε), then Alice can feel safe since the output does not depend “much” on her private data. This property must hold not just for Alice, but for any individual whose data is in the dataset. Since the output of a BPMN process is typically deterministic, differential privacy can be achieved by adding a certain amount of random noise to the released output, making it probabilistic. Ideally, the user would like to see an interactive plot representing the relation between the privacy level and the noise level. This visual interface has been developed as a complementary component to PLEAK.
* Video: https://drive.google.com/file/d/1E_h4Tqj-ZUx8RdbnMsoIP3ZZEg2mgKpK/view?usp=sharing
* Main publications:
  *  Pankova, Alisa; St. John, Mark F.; Denker, Grit; Laud, Peeter; Martiny, Karsten; Pavlovic, Dusko (2021). Decision Support for Sharing Data Using Differential Privacy. 18th IEEE Symposium on Visualization for Cyber Security, VizSec 2021, online, 27.10.2021. IEEE, 1-10. https://doi.org/10.1109/VizSec53666.2021.00008
  * Elkoumy, Gamal; Pankova, Alisa; Dumas, Marlon (2021). Mine Me but Don’t Single Me Out: Differentially Private Event Logs for Process Mining. 3rd International Conference on Process Mining (ICPM). IEEE Computer Society, 80−87. https://doi.org/10.1109/ICPM53251.2021.9576852

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
* Summary: SR-EPID is a subversion resilient version of Enhanced Privacy ID, the protocol used by Intel SGX for remote attestation. In the context of Trusted Execution Environments, remote attestation enables a party to establish trust in a TEE running on a remote platform. In the context of the demonstrator described earlier in this document, SR-EPID may be used in the geolocation scenario so that the integrity of the devices where geolocation data is going to be processed, is verified before such data is uploaded. All the popular remote attestation protocols balance authenticity and privacy by using group signature schemes. The latter is a digital signature scheme that allows a verifier to verify a signature as issued by a member of a trusted set while keeping the signer itself anonymous (within that set). In the context of Intel SGX, remote attestation uses a special system enclave, named Quoting Enclave, that certifies the application enclaves running on the same platform. Certification
* Video: https://drive.google.com/file/d/1eAIAyy88FqoFjCeyIX4VeRAplNV8_m2u/view?usp=sharing
* Main publication:

**Elastic Deployment of TEE-based**
* Summary: Processing a large amount of sensitive data requires secure and scalable solutions. For example, location data – as the one processed in the geolocation scenario - is considered as a privacy-sensitive data type so that the platform processing the data should be secured to minimize data leakage. At the same time, the platform should allow for dynamic resource allocations so to cope with different amounts of data to be processed. ReplicaTEE is a solution that enables dynamic enclave replication and de-commissioning for TEE-based applications in the cloud. In particular, ReplicaTEE is designed to enable replication of applications that use Intel SGX – arguably the most popular TEE for workstations – as the undelaying TEE. Given the current deployment model of Intel SGX enclaves, replication of an enclave across machines requires the application owner to either be always online so to provision secret material to newly deployed enclaves, or to trust the cloud provider with managing the enclave secrets. An always- online application owner reduces the benefit of outsourcing to the cloud; trusting the cloud provider with managing enclave secrets voids the advantages of using a TEE.
* Video: https://drive.google.com/file/d/1CudeUP_lcfLRifNSpxDm9InXmOlG8zJl/view?usp=sharing
* Main publication:

**Cryptovault**
* Summary: CryptoVault is a system intended for users of different blockchain technologies. It comprises a hardware wallet that securely stores and manages the sensitive user keys, and a reliable method for backing up these keys as independent shares stored in multiple locations. The aim is to combine the best features of different wallet types while minimizing the risks related to these wallets. CryptoVault generates keys with high entropy, offers end-to-end protected key backup, signs transactions inside a trusted execution environment and can run key recovery without a single point of failure.
* Video: https://drive.google.com/file/d/1dPYFWjUg3EMeatZ9LUB18RKb7r7qVCPE/view?usp=sharing
* Main publication:

**DANS**
* Summary: The main aim of the Data Anonymization Service (DANS) tool is data protection, namely preserving personal data privacy. Considering regulatory aspects anonymized data are excluded from GDPR regulation because anonymized data is no longer “personal data”. In this way, the DANS asset is an anonymization tool that avoids user tracking and user re-identification by the use of privacy and risk models which prevents privacy threats when data are managed. As perfect anonymization is not possible it is necessary to balance between privacy and data accuracy for analytics.
* Video: https://drive.google.com/file/d/1VmyEBShh260Qa48ONsp9c38i_bxmC4T4/view?usp=sharing                                                   
* Main publication:

**Privacy-Aware Aggregate Programming**
* Summary: Privacy-aware aggregate programming is a programming model centered around privacy protection and aggregate programming. The key concern is the trade-off between data utility and privacy protection. To illustrate this paradigm, consider one of the classical use-cases of aggregate programming for computing a so-called proximity field. The problem in this use-case is a 2D map where several agents, obstacles and locations of interest are spread. The agents want to collaborate in helping each other to find the locations of interest but they do not want to share their actual position with each other or with any central system. The aggregate programming solution to this problem is to build a proximity field: each agent in the map will indicate to closely located agents a notion of proximity. To calculate this field the agents, execute a simple aggregation-based program: iteratively aggregate the neighbors’ proximity with the “min” operation, adding an estimate of the neighbor’s distance.
* Video: https://drive.google.com/file/d/15_JW3VZW2OGxxQzXBfsJ1qxoOG18kCRk/view?usp=sharing                                                   
* Main publication:

**Edge-Privacy**
* Summary: The Privacy Manager is devised as a virtualized service that can be deployed in edge-ready devices. It allows data owners to decide under what circumstances the data collected from IoT devices are released to third parties and the level of detail at which these data are shared. The privacy preferences of the data owner are encoded as a set of rules defined in privacy policy files. In essence, the Edge Privacy Manager operates as a privacy proxy between IoT devices and data consumers willing to access their data.
* Video: https://drive.google.com/file/d/1-HPavIH_7CXQluPhBqQGmpldVcI1xrph/view?usp=sharing                                              
* Main publication: R. Rios et al. "Personal IoT Privacy Control at the Edge” IEEE Security and Privacy, vol 20. Issue 1, Jan-Feb 2022. Page(s): 23 - 32. DOI: 10.1109/MSEC.2021.3101865

**Password-less authentication**
* Summary: The password-less authentication asset is based on the FIDO standards8 . It provides a device-centric authentication that implements a) a challenge-response scheme in which the user is authenticated locally (i.e., on the device that it is deployed to access the service) using alternative authentication methods, such as PIN, USB keys, and biometrics and b) public key cryptography to authenticate the device in the service. During the FIDO authentication, when a user (in our case a student) is authenticated in its device (for instance, using a USB key), it unlocks its private key, which subsequently is deployed to sign the challenge and the service deploys the user’s public key, to decode the challenge.
* Video: https://drive.google.com/file/d/1GpjutgdyqpWmXQ_AfIPByX7pOOIiqCC-/view?usp=sharing
* Main publication:

**SS-PP-IdM**
* Summary: SS-PP-IdM uses OLYMPUS virtual identity provider, which is comprised of multiple individual IdPs, to manage user identities and authentication. It relies on distributed p-ABCs to offer privacy- preserving (minimal disclosure and unlinkability) and authentication (presentation of attributes) linked to eIDAS. Moreover, the asset proposes a trust framework based on Blockchain to complement the usage of credentials.
* Video: https://drive.google.com/file/d/1gxqsa_pjZ1bFIbiojzUFOCzrdrzz3pNa/view?usp=sharing
* Main publication:

**pp-FL**
* Summary: Federated Learning (FL) has attracted significant interest given its prominent advantages and applicability in many scenarios. However, it has been demonstrated that sharing updated gradients/weights during the training process can lead to privacy concerns. In the context of the Internet of Things (IoT), this can be exacerbated due to Intrusion Detection Systems (IDS), which are intended to detect security attacks by analyzing the devices’ network traffic. This proposal provides a comprehensive evaluation of Differential Privacy (DP) techniques, which are applied during the training of an FL-enabled IDS for Industrial IoT (IIoT). Unlike previous approaches, we deal with non-iid data over the recent ToN_IoT dataset and compare the accuracy obtained considering different privacy requirements and aggregation functions, namely FedAvg and the recently proposed Fed+. According to our evaluation, the use of Fed+ in our setting provides similar results even when noise is included in the federated training process.
* Video: //TODO: INSERT-LINK//
* Main publication:
# Cybersecurity Research and Areas Priority

--- | Governance and Capacity Building | Trustworthy Ecosystems of Systems | Trust-Building Blocks | Disruptive Emerging Develpment
--- | --- | --- | --- | ---
PTASC | - | :heavy_check_mark: |  - | -
ARGUS | - | - |  :heavy_check_mark: | -
GDPR compliant user experience | - | - |  :heavy_check_mark: | :heavy_check_mark: 
Interoperability and cross-border compliance | :heavy_check_mark: | - |  - | -
Edge Privacy (UMA) |- | :heavy_check_mark:|  - | :heavy_check_mark:
Asset 6 | :heavy_check_mark: | - |  - | :heavy_check_mark:
Password-less AuthN | - | :heavy_check_mark: |  :heavy_check_mark: | -
SS-PP-IdM | - | - |  :heavy_check_mark: | :heavy_check_mark:
CryptoVault | - | - |  :heavy_check_mark: | - 
GENERAL_D | - | :heavy_check_mark: |  :heavy_check_mark: | :heavy_check_mark:
pp-FL | - | - |  :heavy_check_mark: | :heavy_check_mark:
Sharemind | - | - |  :heavy_check_mark: | :heavy_check_mark:
PLEAK DP analysers | - | - |  :heavy_check_mark: | -

<p></p>

--- | Collaborative Networks| Education & Training | Certification | Secure Platforms of Platforms | Infrastructure Protection | Holistic Data Protection | AI-based Security | Systems Security & Security Lifetime Management | Secure Architectures for Next Generation Communication | Secure Quantum Technologies | Secure AI Systems | Personalized Privacy Protection
--- | --- | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
PTASC  | --- | --- | ---  |  :heavy_check_mark: |  :heavy_check_mark: | --- | --- | --- | --- | --- | --- | --- 
ARGUS | --- | --- | ---  | --- | --- |  :heavy_check_mark: | --- |  :heavy_check_mark: | --- | --- | --- | --- 
GDPR compliant user experience  | --- | --- | ---  | --- | --- |  :heavy_check_mark: | --- | --- | --- | --- | --- |  :heavy_check_mark: 
Interoperability and cross-border compliance  |  :heavy_check_mark: | --- | ---  | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Edge Privacy (UMA) | --- | --- | ---  |  :heavy_check_mark: | --- | --- | --- | --- | --- | --- | --- | :heavy_check_mark:
Asset 6  | --- |  :heavy_check_mark: | ---  | --- | --- | --- | --- | --- | --- | --- |  :heavy_check_mark: | --- 
Password-less AuthN  | --- | --- | ---  |  :heavy_check_mark: |  :heavy_check_mark: | --- | --- |  :heavy_check_mark: | --- | --- | --- | --- 
SS-PP-IdM | --- | --- | ---  | --- | --- |  :heavy_check_mark: | --- | --- | --- | --- | --- |  :heavy_check_mark:
CryptoVault  | --- | --- | ---  | --- | --- | --- | --- | --- |  :heavy_check_mark: | --- | --- | --- 
GENERAL_D  | --- | --- | ---  |  :heavy_check_mark: |  :heavy_check_mark: |  :heavy_check_mark: | --- |  :heavy_check_mark: | --- | --- | --- |  :heavy_check_mark: 
pp-FL | --- | --- | ---  | --- | --- |  :heavy_check_mark: |  :heavy_check_mark: | --- | --- | --- |  :heavy_check_mark: | --- 
Sharemind | --- | --- | --- | :heavy_check_mark: | --- | :heavy_check_mark: | --- | --- | --- | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: 
PLEAK DP analysers  | --- | --- | --- | --- | --- | :heavy_check_mark: | --- | --- | :heavy_check_mark: | :heavy_check_mark: | --- | :heavy_check_mark: 

# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1,” CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)

[2 - J. Resende, "D3.13 Updated version of enablers and components"  CyberSec4Europe, 2021.](https://cybersec4europe.eu/wp-content/uploads/2022/02/D3.13-Updated-version-of-enablers-and-components-v3.0-submitted.pdf)

