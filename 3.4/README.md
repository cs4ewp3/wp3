# Abstract
This page describes the demonstrator that we have set up for CS4E-WP3-T4. The demonstrator is based on a conceptual platform, meant for gathering and managing threat information from different data sources. Basically, the demonstrator has the twofold objective of (i) improving the accuracy of Threat Intelligence Services (such as, e.g., TDSs) in detecting and characterizing incoming attacks, and (ii) enabling the sharing of trusted, reliable and relevant threat information (e.g., discovered by TDSs or gathered by means of honeypots) among organizations and threat detection algorithms.

# Overview
We propose a general framework of interaction and cooperation with threat intelligence services and provided three specific use cases where these services can cooperate. The partners contributed by creating tangible software assets, by integrating them into joint proof-of-concepts, and illustrating the practical feasibility of a modular cybersecurity platform able to provide key information about the status of a system to monitor. This deliverable documented 3 possible integration scenarios, culminating in a variety of videos, online demonstrators and scientific publications. Within these scenarios, we illustrate how such cooperation can (i) improve the performances of the threat prevention and detection systems and minimize the attack surface by strengthening the robustness of machine learning and deep learning models, making them more robust to new threats, false positives and lowering the time to threat detection; and (ii) enable more robust threat intelligence by allowing to better contextualize threat data and devise flexible strategies, methodologies and data formats for collaborative threat intelligence. 


## Content

### Scenario 1: Sharing cyberthreat intelligence in a confidential and privacy-preserving manner

#### Summary

The focus of the first scenario is on the sharing of cyber threat intelligence (CTI) within and across communities, as this is a key enabler for cooperation between threat intelligence services and to trigger the deployment of adaptive honeypots. By sharing cyber threat information, other stakeholders or systems can leverage the shared information and collaborate to further analyse the data, increase the confidence in the shared intelligence, or to augment it with additional information such as the reputation and trustworthiness of the reporting entities. Additionally, the information can be leveraged in an adaptive honeypot that aims to deploy software vulnerable against reported threats as a way to lure adversaries and gather more intelligence while they attack the reported vulnerabilities. The sharing capability within and across communities is already present within state-of-practice cyber threat intelligence platforms, though due to the sensitive nature targets of cyberthreats are not always willing to share this information unless they are obliged to be compliant with mandatory incident reporting regulations.  

This scenario demonstrates how we address this concern. As we are dealing with sensitive information about threat targets and detailed information about vulnerabilities, the information should never end up in the wrong hands, e.g., malicious adversaries that aim to exploit the intelligence. This scenario builds upon state-of-practice and open-source threat intelligence tools for storing and sharing information to further strengthen the security and privacy posture of intelligence sharing. The main objectives of this scenario are to mitigate privacy concerns by (1) pre-processing threat intelligence with well-known privacy enhancing technologies and data anonymization techniques before the intelligence is shared, and (2) cryptographically protecting the shared threat intelligence in a fine-grained manner so that only authorized entities can decrypt and act upon it.  

The following scenarios about enriching CTI and adaptive honeypots can leverage the capabilities offered by this scenario to request access to privatized and protected information, or to protect their own information before sharing within and across the community. 

#### Resources

*	Online proof-of-concept demonstrators and repositories:
     * https://nuage.cs.kuleuven.be/	[KUL's MISP instance]
     * https://nuage.cs.kuleuven.be/tatis/	[integration with KUL's MISP instance]
     * https://ciel.cs.kuleuven.be/tatis/ 	[integration with CNR's MISP instance]
     * http://155.54.95.184:8082/anonymizer/AnonymizerAPI.html [PP-CTI anonymizer service, integrated with TATIS]
* Videos:
     * https://people.cs.kuleuven.be/~davy.preuveneers/tatis.mp4
* Scientific dissemination: 
     * Preuveneers, D., et al. &quot;TATIS: trustworthy APIs for threat intelligence sharing with UMA and CP-ABE.&quot; Foundations and Practice of Security. 12th International Symposium, FPS 2019, Toulouse, France, November 5–7, 2019, Revised Selected Papers. Vol. 12056. Springer International Publishing; Switzerland, 2020.
     * Preuveneers, D., et al. &quot;Distributed Security Framework for Reliable Threat Intelligence Sharing.&quot; Security and Communication Networks 2020 (2020).
     * Preuveneers, D., and Wouter J. &quot;Sharing Machine Learning Models as Indicators of Compromise for Cyber Threat Intelligence.&quot; Journal of Cybersecurity and Privacy 1.1 (2021): 140-163.

### Scenario 2: Enriching the information on detected threats via TDS cooperation and gathered by means of honeypot instances:

#### Summary 

The main idea consists in enriching the information on detected threats with further details provided by different TDSs. Moreover, the honeynet allows for gathering further attack instances which will be used in the learning phase of the ML-Based TDSs to improve their effectiveness. 

A typical flow within the proposed scenario includes the following steps: (1) An IDS documents an attack and updates its corresponding MISP with threat intelligence (events and attributes) describing the attack. (2) The information concerning the attack is shared between entities, possibly after enhancing its confidentiality and privacy, and an operator, using TIP information, deploys a honeypot configured to enrich information concerning the new attack. (3) further information concerning the uploaded events or external events potentially relevant for the monitored network infrastructure can be collected by exploiting the data enrichment platforms. In addition, when the information on a new intrusion is gathered by the honeynet, once again these data are shared with the MISP via a custom MISP object. 

#### Resources

* Online proof-of-concept demonstrators and repositories
     * https://misp1.icar.cnr.it/		[CNR MISP instance] 
* Videos:
     * https://github.com/massimo-guarascio/cs4e_ebids_asset 
     * https://tinyurl.com/tie-atos	
* Scientific dissemination: 
     * Folino, F., G. Folino, M. Guarascio, F.S. Pisani, and L. Pontieri. 2021. "On learning effective ensembles of deep neural networks for intrusion detection." Information Fusion 48-69. 
     * Guarascio, M., N. Cassavia, F.S. Pisani, and G. Manco. 2021. "Boosting Cyber Threat Intelligence via Collaborative Intrusion Detection." Under Review.  

### Scenario 3: Adaptive deployment

#### Summary

Gathering relevant information on attack strategies and sharing precious IoCs to improve the security degree of the entities belonging to the MISP network is the main objective of this use case. In more details, this scenario aims at demonstrating how internal information gathered by means of a pool of honeypots can be used in the context of the security of an infrastructure.  

Two assets collaborate to achieve this aim: (i) Briareos, a HIDS capable of launch Honeypots in any linux system and (ii) Roce, a system devoted to evaluating the fundamental problems of the software contained in a device. The information extracted by Briareos and data from a public APT database are combined by Roce and exploited to yield the probability of compromise of the monitored systems. 

#### Resources 

* Online proof-of-concept demonstrators and repositories:
     * [INSERT LINK]
* Videos:
     * https://www.dcc.fc.up.pt/~jresende/videos/briareos.mp4
* Scientific dissemination: 
     * Pinto Bastos Martins, Maria Inês. 2020. Anomaly Detection in Cybersecurity. Mater Thesis, https://sigarra.up.pt/fcup/pt/pub_geral.show_file?pi_doc_id=275358. 
     * Dinis da Silva e Barbosa, Mário. 2020. JBriareos: A Secure and Scalable Distributed Intrusion Detection System. Master Thesis, https://sigarra.up.pt/fcup/pt/pub_geral.show_file?pi_doc_id=274710. 


# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1”, CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)

[2 - D. Preuveneers et al., “D3.3: Research Challenges and Requirements to Manage Digital Evidence”, CyberSec4Europe, 2020.](https://cybersec4europe.eu/wp-content/uploads/2020/02/D3.3-Research-challenges-and-requirements-to-manage-digital-evidence-Submitted.pdf)

[3 - M. Guarascio et al., “Deliverable D3.14: Cooperation With Threat Intelligence Services For Deploying Adaptive Honeypots”, CyberSec4Europe, 2021.](https://cybersec4europe.eu/wp-content/uploads/2021/10/D3.14-Cooperation-with-Threat-Intelligence-Services-for-deploying-adaptive-honeypots_2.05_submitted.pdf)

[4 - Original repository](https://github.com/cs4ewp3t4/cs4ewp3t4)
</br>
