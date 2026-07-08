# Splunk-Detection-Lab

A hands-on detection engineering lab focused on identifying critical data sources, ingesting logs into a SIEM, generating attack telemetry, and analyzing events to understand attacker behavior and defensive detection strategies.

This lab simulates real-world attack scenarios using controlled telemetry generation tools and offensive security utilities. The goal is to strengthen practical SIEM skills, improve log analysis proficiency, and deepen understanding of network security fundamentals.

---

##  Objective

Identify critical data sources on the target host such as:

- Windows Event Logs  
- Linux syslog  
- Process information  
- Network telemetry  

The primary focus was to ingest and analyze logs within a **Security Information and Event Management (SIEM)** system, generating test telemetry to mimic real-world attack scenarios.

This hands-on experience was designed to deepen understanding of:

- network security  
- attack patterns  
- defensive strategies  
- detection engineering workflows  

---

##  Skills Learned

- Advanced understanding of SIEM concepts and practical application  
- Proficiency in analyzing and interpreting network logs  
- Ability to generate and recognize attack signatures and patterns  
- Enhanced knowledge of network protocols and security vulnerabilities  
- Development of critical thinking and problem‑solving skills in cybersecurity  

---

##  Tools Used

- **SIEM Platform** — log ingestion, parsing, correlation, and analysis  
- **Network Analysis Tools** (e.g., Wireshark) — capture and examine network traffic  
- **Telemetry Generation Tools** — create realistic network traffic and attack scenarios  
- **Offensive Security Tools** — used to simulate attacker behavior and generate detection signals  

---

##  Steps

Below is an example workflow demonstrating how telemetry was generated using offensive tools to simulate realistic attack behavior.

### **Ref 1–28: Tools to create realistic malware and attack scenarios**

These represent sequential steps taken on a Kali Linux host to generate telemetry:

![kali1](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/5beb67d5-88a8-4e8f-8a78-baede3231d94)



![kaliifconfig2](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/af1d04aa-157d-4566-9a57-b8373545a873)



![kali3nmap-h](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/451f7ea4-9caf-408f-ac34-b3e8c5ca08c4)



![kali4nmaptargetmachine](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/6a93c519-b2f0-416a-89fd-1504ca90f4ec)




![kali5nmaptargetmachine](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/d7d7803a-0e07-4ce5-b116-50c726b1d03c)




![kali6exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/8840b563-d3ae-4873-b0d5-faef85064bc2)





![kali7exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/06a0a673-b65a-413b-9001-5c2f1fe2c53d)


![kali8exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/66f5b90e-1f9d-4735-973d-8619e76d3b15)



![kali9exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/51cc147d-6858-4997-ab22-78f3c067924d)



![kali10exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/c722efe5-d9bc-4fe0-ad3c-67c634c411c0)




![kali11exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/1e7b3360-08bc-410c-a9f2-3054edb2e8b9)



![kali12exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/39bca2f2-fd69-4b37-b7fa-69493b31b704)





![kali13exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/59bc400f-53a8-4c44-8b29-2c328c816b73)




![kali14exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/7b9b674a-0361-4269-adb2-007b0a9fa204)





![kali15exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/6d3a74fa-beea-4d0d-8a5f-5844e6e3e751)





![kali16exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/8d9ed07b-39ed-4e82-b9eb-a07c1af4ab84)



![kali17exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/143b7586-eb94-4a16-98bf-471401f91ee1)


![kali18exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/ce011c96-85b8-4b94-aceb-b2cf7d6de09d)



![kali19exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/7243a35b-6206-4c7b-ac06-183831508973)


![kali20exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/3eb2d212-e31a-413b-b745-c253a5baa270)



![kali21exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/59f70c85-5a8c-4c0e-b497-930faab7a266)



![kali22exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/8f224beb-142c-4d9b-a79a-5dd2a2a53dee)



![kali23exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/a9be9e07-02e3-4f78-b436-0806dc2d491f)



![kali24exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/7035b902-0d56-44b7-acf4-c54b6b52c5db)




![kali25exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/2ad3a531-4047-4a29-8dfc-5d57cbc130ed)



![kali26exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/da16232e-4928-4f15-bbe2-b673c4b968ee)





![kali27exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/8e5fe1db-a944-4292-8b9b-9b92964dd42b)








![kali28exploit](https://github.com/outlaw777/Splunk-Detection-Lab/assets/156555250/48f503b9-52c5-4944-a27d-6940685a5aa1)


These steps simulate reconnaissance, enumeration, exploitation attempts, and post‑exploitation activity — all of which generate logs that can be ingested into Splunk for detection analysis.

---

##  Summary

This lab provides a structured environment for:

- practicing SIEM log ingestion  
- analyzing attacker telemetry  
- building detection logic  
- understanding how offensive actions appear in logs  
- improving defensive response strategies  

It serves as a foundational exercise for anyone pursuing detection engineering, SOC analysis, or cybersecurity operations.

---

##  Contributing

Contributions, enhancements, and additional attack scenarios are welcome.  
Please open an issue or submit a pull request.

---

##  License

This project is licensed under the MIT License.


































