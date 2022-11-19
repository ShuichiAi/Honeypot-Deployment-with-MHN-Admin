# Honeypot Assignment

**Time spent:** 4 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

I used the instructions in the document to create the instance of mhn-admin and then deployed it using GCP.

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

Dionaea is basically a trap that we have set which we later use to track how many different people/bots attack it and get additional data associated with their attack.

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

MHN-Admin uses mySQL as its RDBMS. The information contained in the exported session.json file is the record of all the attacks and the information associated with it like the IP address, ports accessed, protocol used, etc.


