# Abstract
On this page we describes the demo application that we have set up. The application is meant for gathering and managing information about assets that require cybersecurity and IT security certification. It is possible to define the assets and the different certification needs and events that have been carried out or are  planned in the future. This allows  us  to check the  conformity of assets to certificates  and take  a  step towards continuous certification.
# Overview
# Content

### ARMOUR Methodology
The  ARMOUR  methodology  combines  the  two  perspectives  of  the  ETSI  proposal  and  adds  additional activities inherent to the certification process.It should be pointed out that the ARMOUR methodology adapts the ETSI concepts and processes. In this sense,  the  first  process, establishing  the  context,is  related  with  understanding  the  business,  regulatory environment, and the laws and analysing which security level is required in each of them. <br/>
At the beginning of the security assessment phase, the risk identification activity identifies the potential vulnerabilities  that  can  be  applicable  to  the  scenario  and  context  are  identified. </br>
Test  Design  and  Implementationgenerates  the  test  cases  associated  to  the  vulnerabilities  and  threats considered. In this phase, the tests are also implemented and assembled to test procedures. </br>
Test  Environment  Set  Up  &  Maintenanceinvolves  establishing  and  maintaining  the  environment  in which  tests  are  executed.  The  environment  can  be  local  (e.g.,  a  device)  or  remote  (e.g.,  a  large-scale infrastructure such as FIT IoT Lab), but in any case, typical actions are reserving resources and uploading the code to the devices. </br>
Test Execution, Analysis & Summarydeals with the test execution as well as with the systematic analysis and summary of test results.
</br>
Risk  estimationcalculates  the  risk  level,  understanding  the  origin  of  the  risk  and  its  consequences.
</br>
Risk Evaluationcompares the results of risk estimation with the level of risk analysed at the beginning of the process, at the establishing the context phase
### Demonstrator Goal and Scope
As is the case with most general frameworks, the ARMOUR methodology can be very difficult to get started with, let alone  apply for a person acquainting themselves with it for the first time. Moreover, a complex systematic study can be simplified by technical toolseven for those who are familiar with the methodology.
</br>
We  have  modifiedan  existing  asset  from  CYBER(the  CSA  tool)  to  serve  as  a  prototype  for  this methodology.The CSA tool is originally intended for incident management, but has been altered so that a user  can  enter  and  interlink  information  concerning  a  target  of  evaluation.  At  the  current  stage,  the demonstrator is a prototype of the planned system, and as suchdoes not offer further automation of processes (e.g. risk score estimation, automatic scheduling of tests for recertification). This will be part of our future efforts.
</br>
The demonstrator is divided into three main categories concerning assets, risks and tests.The user can add information about all of these categories and interlink them based on their connections. For an object in any category it is possible to define a level of importance, whichwill help with prioritising. 
# References
[1 - A. Skarmeta, “D3.1 Common Framework Handbook 1,” CyberSec4Europe, 2019.](https://cybersec4europe.eu/wp-content/uploads/2020/06/D3.1-Handbook-v2.0-submitted-1.pdf)
