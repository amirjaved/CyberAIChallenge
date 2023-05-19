# CyberAIChallenge
AI and Cybersecurity challenge for Cardiff, Osmania, and Hyderabad university students.

**Objectives:** The aim of the Cybersecurity and AI challenge is for participants to get a chance to work on different research problems related to cybersecurity and machine learning.
By working on the challenges, participants will get a deeper understanding of cybersecurity best practices and new emerging cybersecurity threats. In addition, they will get hands-on experience with cybersecurity tools and techniques. 

**Participants:** The challenge is open to all Cardiff, Osmania, and Hyderabad University students.  The students are invited to work on the challenge in teams. 

**Duration:** The challenge will be open for one month from <insert date>, after which students will be invited to present their work. 

**Cybersecurity Theme Challenges:** Each participating team could choose from a variety of themed challenges listed below.
1.	Adversarial machine learning and cybersecurity.
2.	Fingerprinting Cybercriminal behaviour using Honeypot.
3.	Online social networks and malware.
4.	Integrating IoT communication with blockchain


**Evaluate and Provide Feedback:** Each team will be required to present their work in a virtual event, and feedback will be given to each team post the event. 

**Prize:**  Each winning team from each university will get a prize of £200.

  
 #  Theme 1 Advesarial Machine learning and Cyber security.
 
**Problem statement**
The cyber threat landscape is evolving every minute, and cybercriminals are finding new innovative techniques to cripple existing malware detection machine learning models. While antivirus and malware classification machine learning models aim to identify malware based on their signature, they do not respond well to adversarial attacks and could lead to misclassification. Thus, each misclassification results in exposing malware to the internal network. Building on this idea, we present our first research based challenge to **develop a proof of concept** of an aadvesarial machine learning model that will either obsfucate malicious traffic as bening and bypass detection or developing techniques to attack the machine learning model to detect ongoing attacks. 
 In order to you do the challenge you have option to pick from one of the dataset listed below
  1. Aposemat IoT-23 dataset https://www.stratosphereips.org/datasets-iot23
  2. BODMAS Malware Dataset https://whyisyoung.github.io/BODMAS/
  
**Research challenge:**
The research challenge should aim to answer below mentioned research questions:
  1. What techniques can a patient adversary use to mistrain or evade a learning system or compromise data privacy?
  2. How might we evaluate the success of adversarial attack?
  3. What are the relevant security criteria necessary to evaluate the security of a malware detection model in a particular adversarial environment?
  
** Resources worth looking **
  
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
The research challenge should aim to answer below mentioned research questions:
1. What are the different/similar techniques used by cybercriminals.
2. How should an adapative honeypot that changes the enviroments based on cybercrimanl behaviour look like?

**Dataset **
The dataset contains two months of captured attacks to our honeypot from the January to March 2023 and is available in JSON format. The original IP address of our honeypot has been replaced with 1.2.3.4, while other IP addresses of the attackers are inta
  The dataset itself is available at https://itsacid-my.sharepoint.com/:u:/g/personal/baskoro_if_its_ac_id/EWnOot9ohYRHikWZlnqBF4QBvXoukGi3hOOZSZKtiXdliQ?e=tdxGPj. The password to access the file is 'honeypotitscu952$' (without quotes). Feel free to let me know if you have any questions.

 
# 3 Theme: Adversarial attacks on image classification in self-driving cars

Problem statement: Self-driving cars use image classification models to detect objects on the road and make decisions based on that information. However, these models are vulnerable to adversarial attacks, where attackers can introduce subtle perturbations to the input image to mislead the system into misclassifying objects. This can be a major safety concern, as misclassification can lead to serious accidents.

Background: Self-driving cars rely on a combination of sensors and algorithms to detect and interpret the environment around them. One key component of this system is the image classification model, which uses deep learning algorithms to detect objects such as pedestrians, other vehicles, and traffic signs. However, recent research has shown that these models can be vulnerable to adversarial attacks, where attackers can introduce subtle perturbations to the input image to mislead the system into misclassifying objects.

Impact: Adversarial attacks on image classification in self-driving cars can have serious consequences, including accidents and loss of life. For example, an attacker could introduce subtle perturbations to a stop sign that would cause the self-driving car to misclassify it as a yield sign, potentially leading to a collision. As self-driving cars become more common, it is important to develop defenses against such attacks to ensure their safety on the road.

Tasks : Researchers have proposed several solutions to defend against adversarial attacks on image classification models. One approach is to use adversarial training, where the model is trained on both clean and adversarial examples to make it more robust against attacks. Another approach is to use defensive distillation, where the model is trained to output probabilities instead of hard labels, making it more difficult for attackers to manipulate the output. You are tasked to propose a potential viable solution to the above problem statement using the below mentioned dataset.

References:
1.	Deng, Y., Zhang, T., Lou, G., Zheng, X., Jin, J., & Han, Q. L. (2021). Deep learning-based autonomous driving systems: A survey of attacks and defenses. IEEE Transactions on Industrial Informatics, 17(12), 7897-7912.      Link: Click Here
2.	Mahima, K. T. Y., Ayoob, Mohamed and Poravi, Guhanathan. "Adversarial Attacks and Defense Technologies on Autonomous Vehicles: A Review" Applied Computer Systems, vol.26, no.2, 2021, pp.96-106. https://doi.org/10.2478/acss-2021-0012
3.	Cao, Y., Xiao, C., Cyr, B., Zhou, Y., Park, W., Rampazzi, S., ... & Mao, Z. M. (2019, November). Adversarial sensor attack on lidar-based perception in autonomous driving. In Proceedings of the 2019 ACM SIGSAC conference on computer and communications security (pp. 2267-2281).
Link: https://dl.acm.org/doi/pdf/10.1145/3319535.3339815

Datasets:
1.	The Udacity Self-Driving Car Dataset: https://github.com/udacity/self-driving-car/tree/master/datasets



# Theme 4: Privacy concerns in machine learning models trained on medical data

Problem statement: Machine learning models trained on medical data can reveal sensitive information about individuals, which can be exploited by attackers. Ensuring the privacy of such data is a major concern in machine learning applications.

Background: Machine learning models trained on medical data have the potential to revolutionize healthcare by providing personalized diagnoses and treatments. However, these models can also reveal sensitive information about individuals, such as their medical history or genetic information. This information can be exploited by attackers, who can use it for identity theft or other malicious purposes. As a result, ensuring the privacy of medical data is a major concern in machine learning applications.

Impact: Privacy breaches in machine learning models trained on medical data can have serious consequences for individuals, including identity theft and discrimination. For example, an attacker could use a machine learning model trained on medical data to identify individuals with certain medical conditions, and then use that information to discriminate against them in employment or insurance.

Task: Researchers have proposed several solutions to address privacy concerns in machine learning models trained on medical data. One approach is to use differential privacy, which adds noise to the data to prevent attackers from identifying specific individuals. Another approach is to use federated learning, where the model is trained on data from multiple sources without ever sharing the raw data itself. You are tasked to propose a potential viable solution to the above problem statement using the below mentioned dataset.

References:
1.	Beaulieu-Jones, B. K., Wu, Z. S., Williams, C., Lee, R., Bhavnani, S. P., Byrd, J. B., & Greene, C. S. (2019). Privacy-preserving generative deep neural networks support clinical data sharing. Circulation: Cardiovascular Quality and Outcomes, 12(7), e005122. Link: Click Here
2.	Yang, Q., Liu, Y., Chen, T., & Tong, Y. (2019). Federated machine learning: Concept and applications. ACM Transactions on Intelligent Systems and Technology (TIST), 10(2), 1-19. Link: Click Here
3.	Wei, K., Li, J., Ding, M., Ma, C., Yang, H. H., Farokhi, F., ... & Poor, H. V. (2020). Federated learning with differential privacy: Algorithms and performance analysis. IEEE Transactions on Information Forensics and Security, 15, 3454-3469.  Link: Click Here
Datasets:
1.	MIMIC-III: https://mimic.physionet.org/
2.	UK Biobank: https://www.ukbiobank.ac.uk/
3.	TCGA: https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga

   #  Theme 4 <>
   #  Theme 5 <>
   #  Theme 6 <>
