# Honeypot-Assignment
Assignment for codepath regarding the Honeypot
**5 Hours** **X** spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:**
I utilized Google Cloud in order to setup the MHN-Admin deployment, with the free credits I was able to setup an Admin machine to monitor the status of the Honeypot machine that will be collecting traffic from attacks that it's exposed to. 

<img src="mhnadmin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:**
Dionaea is a type of honeypot which can capture attack payloads and malware once it's properly setup. I was able to log dozens of attacks coming from all over the world along with the attack I tried with my own Kali Linux machine.

<img src="honeypot1.gif">

### Database Backup (Required) 

**Summary:** 
The RDBMS that MHN-Admin uses would be Cloud SQL, and the information in the JSON file that has been recorded would be the source IP addresses of the attackers along with the source ports, destination ports, and other identiifers as they connected and attacked the honeypot.
