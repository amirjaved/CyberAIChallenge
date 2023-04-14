# CyberAIChallenge
AI and Cybersecurity challenge for Cardiff, Osmania, and Hyderabad university students.

Objectives: The aim of the Cybersecurity and AI challenge is for participants to get a chance to work on different research problems related to cybersecurity and machine learning.
By working on the challenges, participants will get a deeper understanding of cybersecurity best practices and new emerging cybersecurity threats. In addition, they will get hands-on experience with cybersecurity tools and techniques. 

Participants: The challenge is open to all Cardiff, Osmania, and Hyderabad University students.  The students are invited to work on the challenge in teams. 

Duration: The challenge will be open for one month from <insert date>, after which students will be invited to present their work. 

Cybersecurity Theme Challenges: Each participating team could choose from a variety of themed challenges listed below.
1.	Adversarial machine learning and cybersecurity.
2.	Fingerprinting Cybercriminal behaviour using Honeypot.
3.	Online social networks and malware.
4.	Integrating IoT communication with blockchain


Evaluate and Provide Feedback: Each team will be required to present their work in a virtual event, and feedback will be given to each team post the event. 

Prize:  A total of £800 worth of prizes to be won. 

  
 #  Theme 1 Advesarial Machine learning and Cyber security.
 
The cyber threat landscape is evolving every minute, and cybercriminals are finding new innovative techniques to cripple existing malware detection machine learning models. While antivirus and malware classification machine learning models aim to identify malware based on their signature, they do not respond well to adversarial attacks and could lead to misclassification. Thus, each misclassification results in exposing malware to the internal network. Building on this idea, we present our first research based challenge to **develop a proof of concept** of an aadvesarial machine learning model that will either obsfucate malicious traffic as bening and bypass detection or developing techniques to attack the machine learning model to detect ongoing attacks. 
 In order to you do the challenge you have option to pick from one of the dataset listed below
  1. Aposemat IoT-23 dataset https://www.stratosphereips.org/datasets-iot23
  2. BODMAS Malware Dataset https://whyisyoung.github.io/BODMAS/
 
The research challenge should aim to answer below mentioned research questions:
  1. What techniques can a patient adversary use to mistrain or evade a learning system or compromise data privacy?
  2. How might we evaluate the success of adversarial attack?
  3. What are the relevant security criteria necessary to evaluate the security of a malware detection model in a particular adversarial environment?
  
 Resources worth looking 
  
1. https://ieeexplore.ieee.org/abstract/document/9887932 
2. https://arxiv.org/abs/1706.06083
3. https://www.blackhat.com/docs/us-17/thursday/us-17-Anderson-Bot-Vs-Bot-Evading-Machine-Learning-Malware-Detection-wp.pdf

 #  Theme 2 Fingerprinting Cybercriminal behaviour using Honeypots.
  
A honeypot is a decoy system designed to attract and deceive attackers, allowing security experts to study their techniques and behavior. The honeypot does not contain any valuable information, but instead simulates vulnerable systems and services to lure in attackers and gather information about their tactics. In this challenge you will be working from dataset collected from **Net-Centric Computing** research laboratory. Net-Centric Computing is a cutting-edge research laboratory in the Department of Informatics at Institut Teknologi Sepuluh Nopember (ITS), Indonesia, specialising in various fields related to networked computing. The lab's research efforts are centered around the themes of cyber security, data stream engineering, and the Internet of Things (IoT) and smart city technologies. 
The dataset constitues  of six low interaction honeypots: Cowrie, Dionaea, Elasticpot, Gridpot, RDPy, and Honeytrap. Each of these honeypots simulates a different type of system or service, such as a SSH server or a web server, to attract a variety of attackers.

A brief explanations for each of the low interaction honeypots mentioned below:

**Cowrie:** 
This honeypot emulates a SSH server, and records all commands and interactions made by an attacker. It can also capture files downloaded by the attacker and mimic the behavior of a real system, making it difficult for attackers to differentiate between the honeypot and a real system.

**Dionaea:** 
This honeypot emulates a variety of services, including SMB, FTP, and HTTP, and can detect and log different types of attacks, such as SQL injections and malware downloads.

**Elasticpot:** 
This honeypot is designed to emulate web applications and web services, and can simulate vulnerabilities in popular web frameworks such as Ruby on Rails and Wordpress.
  
**Gridpot:** 
This honeypot is focused on industrial control systems (ICS), and can emulate ICS protocols and services such as Modbus and DNP3. It can detect and log attacks targeting ICS systems.

**RDPy:** 
This honeypot emulates a Windows Remote Desktop Protocol (RDP) server, and can capture the actions of attackers who are attempting to gain remote access to a system.

**Honeytrap:** 
This honeypot is a multi-protocol trap that can simulate different services such as SSH, Telnet, and FTP. It can capture data about the behavior of attackers, such as the tools they use and the vulnerabilities they exploit.

By monitoring and analyzing the traffic and activity on these honeypots, security experts can gain valuable insights into the types of attacks that are currently being launched, the methods that attackers are using, and the vulnerabilities that are being targeted. This information can then be used to improve the security posture of the institute's own systems, as well as to inform the development of new security tools and techniques.

**Research challenge:**
You are invited to work in team to use machine learning to fingerprint different cybercriminal behaviour. The research should aim to indetify different/similar techniques used by cybercriminals and in doing so they should present an adapative honeypot, that changes the enviroments based on cybercrimanl behaviour.

**Dataset **
The dataset contains two months of captured attacks to our honeypot from the January to March 2023 and is available in JSON format. The original IP address of our honeypot has been replaced with 1.2.3.4, while other IP addresses of the attackers are inta
  The dataset itself is available at https://itsacid-my.sharepoint.com/:u:/g/personal/baskoro_if_its_ac_id/EWnOot9ohYRHikWZlnqBF4QBvXoukGi3hOOZSZKtiXdliQ?e=tdxGPj. The password to access the file is 'honeypotitscu952$' (without quotes). Feel free to let me know if you have any questions.
