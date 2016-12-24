pageTitle: 网络安全 2014
menuTitle: 网络安全 2014 春

## (Mostly) Static Analysis

* (1) Gary Wassermann and Zhendong Su. Sound and Precise Analysis of Web Applications for Injection Vulnerabilities. PLDI 2007
* (2) Zhendong Su and Gary Wassermann. The Essence of Command Injection Attacks in Web Applications . POPL 2006. 韦振峰---3.31
* (3) Nenad Jovanovic, Christopher Kruegel, and Engin Kirda. Pixy: A Static Analysis Tool for Detecting Web Application Vulnerabilities (Short Paper) . 2006 IEEE Symposium on Security and Privacy, Oakland , CA , May 2006. // Tech Report 
* (4) Philipp Vogt, Florian Nentwich, Nenad Jovanovic, Engin Kirda, Christopher Kruegel, Giovanni Vigna. Cross Site Scripting Prevention with Dynamic Data Tainting and Static Analysis . NDSS 2007. 姚姝娜---4.14
* (5) Nenad Jovanovic, Christopher Kruegel, and Engin Kirda. Precise Alias Analysis for Static Detection of Web Application Vulnerabilities . ACM SIGPLAN Workshop on Programming Languages and Analysis for Security, Ottawa , Canada , June 2006. 李绍滔---4.14
* (6) Yichen Xie and Alex Aiken. Static Detection of Security Vulnerabilities in Scripting Languages . USENIX Security 2006. 龙帅---5.19
(7) Stefan Kals, Engin Kirda, Christopher Kruegel, Nenad Jovanovic. SecuBat: A Web Vulnerability Scanner . WWW 2006. 刘聪---4.21
* (8) Michael Martin, Benjamin Livshits, and Monica S. Lam. Finding Application Errors and Security Flaws Using PQL: a Program Query Language . Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA), October 2005.
* (9) Benjamin Livshits and Monica S. Lam. Finding Security Vulnerabilities in Java Applications with Static Analysis . USENIX Security 2005. 程竹青---4.21
* (10) William G.J. Halfond and Jeremy Viegas and Alessandro Orso. A Classification of SQL-Injection Attacks and Countermeasures . International Symposium on Secure Software Engineering 2006. 陈政宇---3.31
* (11) Yao-Wen Huang, Fang Yu, Christian Hang, Chung-Hung Tsai, Der-Tsai Lee, Sy-Yen Kuo. Securing Web Application Code by Static Analysis and Runtime Protection . 13th International World Wide Web Conference (WWW2004). 朱银---4.28

## Dynamic Defenses

* (12) Emre Kiciman and Helen J. Wang. Live Monitoring: Using Adaptive Instrumentation and Analysis to Debug and Maintain Web Applications . Hot Topics in Operating Systems, 2007.
* (13) Wei Xu, Sandeep Bhatkar, and R. Sekar. Taint-Enhanced Policy Enforcement: A Practical Approach to Defeat a Wide Range of Attacks . USENIX Security 2006 王苏苏---4.28
* (14) W. Halfond and A. Orso and P. Manolios. Using Positive Tainting and Syntax-Aware Evaluation to Counter SQL Injection Attacks . ACM SIGSOFT Symposium on the Foundations of Software Engineering (FSE) 2006.

## Dynamic Defenses

* (15) Shuo Chen, David Ross, and Yi-Min Wang. An Analysis of Browser Domain-Isolation Bugs and A Light-Weight Transparent Defense Mechanism . ACM CCS 2007. 刘婷---5.5
* (16) Emre Kiciman and Benjamin Livshits. AjaxScope: A Platform for Remotely Monitoring the Client-Side Behavior of Web 2.0 Applications . SOSP 2007.
* (17) Trevor Jim, Nikhil Swamy, Michael Hicks. Defeating Script Injection Attacks with Browser-Enforced Embedded Policies . WWW 2007. 罗文---4.21
* (18) Ulfar Erlingsson, Benjamin Livshits, Yinglian Xie. End-to-end Web Application Security . Hot Topics in Operating Systems, 2007. 肖振德---5.12
* (19) Chris Karlof, Umesh Shankar, J. D. Tygar, David Wagner. Dynamic Pharming Attacks and the Locked Same-Origin Policies for Web Browsers . ACM CCS 2007. 吴斌---5.12

## Malicious Content Detection

* (20) Alexander Moshchuk, Tanya Bragin, Damien Deville, Steven D. Gribble, and Henry M. Levy. SpyProxy: Execution-based Detection of Malicious Web Content . USENIX Security 2007. 熊洁---5.19
* (21) Charles Reis, John Dunagan, Helen J. Wang, Opher Dubrovsky, Saher Esmeir. BrowserShield: Vulnerability-Driven Filtering of Dynamic HTML . OSDI 2006. 刘渊---5.19

## Malicious Code Defense

### - Exploit and Worm Defense (I)

* (22) Towards Automatic Generation of Vulnerability Signatures 孙慧---5.26
Optional reading: The Spread of the Witty Worm | Automated Worm Fingerprinting

### - Exploit and Worm Defense (II)

* (23) Bouncer: Securing Software by Blocking Bad Input 郑锦涛---5.26
* (24) ShieldGen: Automatic Data Patch Generation for Unknown Vulnerabilities with Informed Probing

### - Botnets Analysis and Defense (I)

* (25) BotHunter: Detecting Malware Infection Through IDS-Driven Dialog Correlation 赵凯 ---6.9
* (26) Wide Scale Botnet Detection and Characterization
Optional reading: A Multifaceted Approach to Understanding the Botnet Phenomenon

### - Malware analysis and defense (I): Privacy-breach Malware

* (27) Behavior -based Spyware Detection 孔攀---5.26
* (28)TightLip: Keeping Applications from Spilling the Beans 刘鹏---5.5
  * Optional reading: Panaroma: Capturing System-wide Information Flow for Malware Detection and Analysis

### - Malware analysis and defense (II): Rootkits and Stealth Malware

* (29) SubVirt: Implementing Malware with Virtual Machines
* (30) Detecting stealth software with Strider GhostBuster
  * Optional reading: Shadow Walker : Raising The Bar For Windows Rootkit Detection | Compatibility is Not Transparency: VMM Detection Myths and Realities

### - Malware analysis and defense (III): In-depth Analysis

* (31) Exploring Multiple Execution Paths for Malware Analysis
Optional reading: BitScope: Automatically Dissecting Malicious Binaries