# LetsUpgrade-Cyber-Security
Assignment Day 4
Question 1:
Find out the mail servers of the following domain:
Ibm.com
Wipro.com
Ans: 
----> IBM.com ----> Wipro.com mail servers: step 1: open command prompt and type nslookup step 2: set type = mx enter step 3: type IBM.com and Wipro.com 
Result:
set type=mx IBM.com Server: UnKnown Address: 192.168.43.1
Non-authoritative answer: IBM.com MX preference = 5, mail exchanger = mx0b-001b2d01.pphosted.com IBM.com MX preference = 5, mail exchanger = mx0a-001b2d01.pphosted.com.
Wipro.com Server: UnKnown Address: 192.168.43.1
Non-authoritative answer: Wipro.com MX preference = 0, mail exchanger = wipro-com.mail.protection.outlook.com.
Question 2:
 Find the locations, where these email servers are hosted.
Ans. IBM.com -----> USA, Wipro.com ----> India.
Question 3:
Scan and find out port numbers open 203.163.246.23
Ans. All 1000 ports of the above IP are Filtered.
Question 4:
Install nessus in a VM and scan your laptop/desktop for CVE.
Ans. Scanned the laptop and find severity of all applications in my laptop like Critical, high, medium, Info.
