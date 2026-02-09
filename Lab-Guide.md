 🛡️ Full Linux SOC Monitoring Lab Guide
Ubuntu SOC Server Investigating RHEL Victim 

---

### Screenshot 1: Network Configuration


![SOC VM](images/1.png) 
![Log VM](images/2.png) 


**What is shown:**  

Established SOC server and monitored endpoint on same network.


---

### Screenshot 2: Prepare RHEL Victim

![OS Verification](images/3.png)

**What is shown:**  

SSH running on victim & Enabled remote access service to simulate attack surface.

---

### Screenshot 3: Create Target User

![SSH Access](images/4.png)

**What is shown:**  

Created standard user to simulate credential targeting.

---

### Screenshot 4: SOC Server Setup (Ubuntu)

![Logging Services](images/5.png)

**What is shown:** 

Installed monitoring tools & Configured SOC server with network and log analysis utilities.

---

### Screenshot 5: ATTACK SIMULATION

![Failed Logins](images/6.png)

**What is shown:**  

Simulated external reconnaissance identifying exposed services.

---

### Screenshot 6: SOC Investigation

![Log Forwarding](images/7.png)

**What is shown:**  

Connection attempts in logs. Detected reconnaissance activity through abnormal connection logs.

---

### Screenshot 7: Attack 2 — SSH Brute Force

![Log Ingestion](images/8.png)

**What is shown:**  

Failed login attempts. Identified brute-force activity through repeated authentication failures.

---

### Screenshot 8: Successful Compromise

![Log Analysis](images/9.png)

**What is shown:**  

Successful login event, Confirmed unauthorized access to user account.


### Screenshot 9: Persistence Creation

![Log Analysis](images/10.png)

**What is shown:**  

New unauthorized account, Detected attacker persistence through unauthorized account creation


### Screenshot 10: Backdoor Listener

![Log Analysis](images/11.png)

**What is shown:**  

Suspicious port listener, Identified unauthorized network service indicating possible backdoor.


### Screenshot 11: SOC INCIDENT RESPONSE

![Log Analysis](images/12.png)

**What is shown:**  

Containment actions applied, Performed containment and eradication procedures


#
