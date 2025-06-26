
# **Penetration Testing on Network Ports for Vulnerability Assessment**

### **Project Overview:**

This project focuses on identifying and assessing potential security vulnerabilities in open network ports using penetration testing methodologies. The goal is to simulate real-world attack scenarios to help organizations or educational environments understand how unprotected or misconfigured network ports can serve as entry points for cyber threats.

### **Objective:**

- To analyze open ports and associated services on a target network.
- To identify vulnerabilities that may be exploited through these ports.
- To perform ethical penetration testing using widely recognized tools.
- To document findings and recommend mitigation strategies.

### **Scope:**

- Perform reconnaissance and port scanning on a controlled or test network.
- Focus on common ports such as **FTP (21), SSH (22), Telnet (23), HTTP (80), HTTPS (443), SMB (445)** and others.
- Use open-source tools to test for vulnerabilities such as weak configurations, outdated services, and unpatched software.

### **Tools & Technologies:**

- **Nmap** – for network discovery and port scanning.
- **Netcat** – for testing connectivity and banner grabbing.
- **Metasploit Framework** – for simulating exploits.
- **Wireshark** – for traffic analysis.
- **Nikto** – for scanning web server vulnerabilities.
- **Hydra** – for brute-force attacks on login services.

### **Methodology:**

1. **Information Gathering:**
    
    Identify active hosts and open ports using Nmap and OS fingerprinting.
    
2. **Service Enumeration:**
    
    Determine the services running on each open port and gather detailed information (version numbers, service banners).
    
3. **Vulnerability Analysis:**
    
    Cross-reference identified services with known CVEs and vulnerabilities using online databases or tools like **Vulners** or **SearchSploit**.
    
4. **Exploitation (Ethical):**
    
    Use Metasploit or manual scripts to test selected vulnerabilities on the test network only.
    
5. **Reporting & Recommendations:**
    
    Compile a technical report that includes:
    
    - Summary of findings
    - Screenshots and logs
    - Risk ratings (e.g., CVSS)
    - Remediation suggestions

### **Expected Outcome:**

- Understand the importance of securing network ports.
- Develop skills in network scanning, vulnerability assessment, and ethical hacking.
- Create a detailed penetration testing report to simulate real-world security audit practices.

### **Educational Value:**

This project helps bridge the gap between theoretical knowledge and real-world cybersecurity practices. It prepares students for professional roles in **network security**, **penetration testing**, and **cyber defense** by providing hands-on experience with common industry tools and techniques.

#Methodology
1. Information Gathering
2. Scanning and Enumeration
3. Vulnerability Analysis 
4. Exploitation
5. Post-Exploitation
6. Reporting


