# Abstract
This page describes four IT branches that have seen several interesting developments and applications in the cybersecurity area in the last couple of years: intelligence techniques, mostly based on machine learning models, can be used to handle threats in a timely and privacy-preserving manner with the least amount of human interaction possible; artificial intelligence is frequently used to secure digital assets, but an attacker can also use them for a variety of purposes such as to confuse a machine learning system in order perform the wrong action when an input is received (e.g. misclassify a cyberattack) or help an evildoer to automatically gather information about a victim (i.e. for social engineering purposes); zero-trust security systemscan be used to create a more secure environments and the last few years have seen the developments of new technologies and the discovery of state-of-the-art attacks; 5G,  the  new  wireless  standard,  promises  to  make  the  world  more  connected  than  ever  since  it  is  being adopted in various embedded and Internet-of-Things devices.

# Overview

# Content

## Threat  intelligence  
Threat  intelligence  is a broad field in the heterogeneous realm of cybersecurity where information about attacks  and  attackers  is  gathered  in  a  manual  or  automated  fashion.  The  standard  approach  over  the  last  years  has  been  the  manual  analysis  of  security  related  events.  However,  the  exponential  growth  of  dataproduced  by  organizations  makes  the  adoption  of  artificial  intelligence  and  automatic  techniques  for  cybersecurity purposes a necessity. Machine and deep learning techniques have been recently applied in a plethora of real-life scenarios.
### Web Application FireWalls UseCases
Web Application Firewalls (WAF) are security appliances employed on web servers to monitor the HTTP(HyperText Transfer Protocol) traffic exchanged between the hosted applications and the clients requesting the offered services, in order to detect and consequently block attacks, typically mounted by malicious actors by leveraging vulnerabilities in the code of web applications. WAFs are typically configured manually by network  administrators,  specifying  rules  on  the  payload  of  HTTP  packets  to  identify  specific  attacks.  However,  writing  such  rules  is  typically  cumbersome  and  error  prone.  Thus,  a  lot  of  research  is  being  conducted in using machine learning algorithms to automate this task.
#### Common attacks
* Cross-Site Scripting (XSS) attacks
* SQL injection attacks 
* Cross-Site  Request  Forgery (CSRF) 

### Internet-of-things UseCases
The  introduction  of  the  Internet-Of-Things  (IoT)  paradigm  is  one  of  the  last  big  revolutions  in  the  IT  scenario. The IoT term encompasses the introduction of computational intelligence in objects used in many objects  of  everyday  life,  including,  for  example,  wearable  devices  (e.g.  smartwatches),  automobiles,  domestic and  video  surveillance  appliances.  Typically,  these  objects  do  not  need  a  high  amount  of  computational  power  to  carry  out  their  tasks.  Employing  powerful  hardware  would  lead  therefore  to  unnecessary  costs,  and  in  many  cases  would  be  impossible  (e.g.  battery  capacity  limitations  on  wearable  devices).  However,  from  a  cybersecurity  point  of  view,  this  limitation  renders  the  application  of  typical  security  solutions  (e.g.  antiviruses  and  firewalls)  impossible.  This  in  turn  renders  such  devices  a  perfect  target for attacks by malicious actors. Typically, they try to infect such unprotected devices with some kind of malware, taking control of them in order to create botnets, which are typically used to carry on Distributed Denial-of-Service (DDoS) attacks, unknowingly from the legitimate proprietors of the involved devices. A notable example has been the Mirai malware, which in 2016 has been used to create botnets, which  in  turn  have  been  employed  to  undertake  successful  DDoS  attacks  against  a  wide  range  of  well-known websites and web hosting platforms (including GitHub, Twitter, Reddit and OVH).
### Malware UseCases
Malware (malicious software) is any kind of software designed with the objective of harming the devices on which it is installed (i.e. infectedby it). Indeed, malware applications are one of the most longstanding menaces in the IT scenario. In fact, the first known malware dates to 1988 [Orman 2003]. While in the early days such programs were written mainly for fun or as experiments, nowadays malwares are typically either financially motivated or engineered for political and industrial espionage. The most common typologies of malware are: 
* ransomware  (or  cryptolockers)
* cryptojackers
* trojans

#### Anti-virus Strategies
* signature
* behavioral  analysis

## Machine learning under the restriction of GDPR
While the applications of machine learning seem to be endless, many countries have started to restrict and regulate  the  handling  and  usage  of  data  and  therefore  also  the  field  of  application  by  data  protection  regulations  such  as  the  EU  GDPR  .  Nowadays,  many  companies  still  struggle  with  the  implementation and maintenance of GDPR-conform data handling, not only for cybersecurity related tasks but also for many other purposes. Especially in conservative markets such as for many finance applications, the usage of complex models or even the storage of related data is obviated. To fulfill the requirements of the GDPR on the one hand and to enter new fields of application on the other hand, a variety of new technologies that enable privacy protecting machine learning have emerged during the recent years. Before the potentially game changing technologies are presented, a brief look is taken into the GDPR and four major requirements are elicited:
* explainability
* non-discrimination
* the right to be forgotten
* data  security

### Privacy preserving machine learning
To protect ML models from a variety of attacks that try to reveal the data, training features or the algorithm itself, a variety of countermeasures have evolved during the recent years. These techniques in general, can be summarized under the term of Privacy Preserving Machine Learning (PPML). While most techniques, were not invented in the recent years, their application to the field of machine learning is new and most of them are not well established or applied. Examples for this are cryptographic protocols to encrypt data that is submitted from multiple parties to one single database, or homomorphic encryption that enables simple computation tasks with encrypted data. 
### Explainable machine learning
When designing a machine learning model, good scores in an evaluation metric are not enough to evaluate the performance of an algorithm. With the data protection regulations, algorithms have also to be designed in a way that they are explainable and non-discriminatory. Therefore, methods  for  explainable  machine  learning  will  be  important  in  the  near  and  long  future.  Model  specific  methods give insights in how a specific model makes decisions and often try to explain the black-box.  These methods can often not be compared over different models. In the opposite to this, model agnostic methods give insights into a model without understanding how the model works. The model is treated as a black  -box and  the  relation  between  input  and  output  is  analyzed.  One  of  the  most  common  methods  are  Local Interpretable Model-agnostic Explanations (LIME)  and is constantly improved, e.g. by Visany et al.  who aim to increase the stability to make the explanations more reliable. 
## AI for adversarial purposes
### Adversarial AI
AI-driven technologies have become an indispensable part of our lives. Thanks to the ever-evolving nature of machine learning techniques, they are now increasingly applied in various applications. However, serious concerns have been raised about the security and reliability issues of machine learning models. As discussed throughout this report, a great number of advanced machine learning models are vulnerable to adversarial attacks.  Previous  studies  have  shown  that  such  attacks  can  be  efficiently  applied  to  many  application  domains ranging from computer vision to natural language processing. As such, it is of importance to initiate calls for action considering the evolving nature, likelihood, criticality, and impact of such attacks through providing a comprehensive roadmap considering the future challenges associated with adversarial artificial intelligence.   </br>
There  exist  multiple  challenges  associated  with  the  future  trend  of  adversarial  AI.  To  avoid  or  at  least  minimize the negative effect of adversarial attacks on available AI-driven technologies, it is highly crucial to provide a holistic roadmap that will tackle the following challenges.

## Social engineering attacks
While  AI  and  ML  are  usually  seen,  at  least  from  the  researchers  point-of-view, as powerful tools for the defenders, they can also simplify the attacker’s life.
</br>
In the future, we can expect more automated phishing and in general social engineering calls, because the described machine learning and AI capabilities not only lead to an increased quality of the attacks, are harder to  spot  by  countermeasures  and  for  the  humans,  but  also  reduce  the  effort  for  the  attacker.  AI  trained  to  gather  some  information  instead  of  assisting  humans  in  making  appointments  for  the  hairdresser  or  restaurants might also be a severe threat in the future.

## Zero-trust security systems
In order to make simpler and even wider the adoption of TPM as a solution to enhance security of the IaaS infrastructure, more flexible solutions must be adopted. For instance, a middleware capable of interacting
with both hypervisors and VMs and creating a software layer that allows a simpler integration of the TPM in  a  cloud  environment  is  required.  Remote  attestation  of  virtual  machines  is  still  not  fully  supported.  Different mechanisms exist, such as the vTPM , but they still lack a proper method to bind the vTPMs to the physical TPM. </br>
Furthermore, the use of this technology has a heavy toll on the performance of a machine. The RA operations are particularly expensive in terms of execution time. This situation is exacerbated when dozens of VMs are deployed  on  a  single  node  and  all  of  them  may  require  the  use  of  these  operations  periodically.  This  challenge still has no real solution and needs to be addressed in order to deploy the TPM technology at full scale.
</br>
In addition, due some new side-channel attacks, issues in the validation and certification process of devices and the advent of quantum technologies, the security of the current TPM-enabled devices is at risk. 
</br>
The  TPM  is  a  promising  technology,  but,  as  we  discussed,  it  has  several  limitations  and  drawback.  It  is  foreseeable that soon we will see a new version of this flexible chip that will increase even more its adoption, especially in cloud environments.

## 5G applications
5G is the new promised land where every device is connected. The adoption of this family of technologies, however, will also bring new problems. An attack on a 5G-enabled appliance may have severe repercussions on its connected devices, thus exacerbating  the attack's effects. The wide use of both hardware and software protections will most likely be a decisive factor to make 5G networks more secure, especially with the growth of the SDN paradigm. Furthermore, user authentication will play a pivotal role. Different stakeholders and the vast heterogeneity of devices supporting 5G will be a challenge in the near future.
# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1,” CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)
