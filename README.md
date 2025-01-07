# SOC Analyst Challenge: Building a Security Monitoring System

## Objective
To develop hands-on skills and knowledge necessary for a SOC analyst role by designing and implementing a security monitoring system focused on threat detection and incident response. This project demonstrates expertise in setting up tools, analyzing security incidents, and managing a simulated environment.

---

## Skills Acquired

- **Elasticsearch & Kibana Management**  
  - Deployed and managed Elasticsearch and Kibana for ingesting and visualizing security logs.  
  - Configured real-time dashboards to monitor security incidents effectively.  

- **Log Ingestion**  
  - Gained proficiency in collecting and ingesting logs from diverse systems, including Windows and Linux servers.  

- **Alerting & Visualization**  
  - Created custom alerts to detect anomalies and generated dashboards for insightful visualization of security events.  

- **Incident Handling**  
  - Investigated and responded to incidents like SSH brute force attacks and Command & Control (C2) techniques.  

- **Command & Control Understanding**  
  - Set up a C2 server to simulate advanced attack methodologies, improving comprehension of attacker tactics.  

- **Ticketing System Integration**  
  - Configured and integrated a ticketing system to streamline incident management and improve response workflows.  

---

## Tools & Technologies Used

- **Elasticsearch & Kibana**: For log storage, analysis, and visualization of security data.  
- **Windows & Linux Servers**: Used for testing and simulating real-world attack scenarios.  
- **Command & Control Server**: Deployed to learn advanced attacker techniques and their implications.  
- **Ticketing System**: Implemented to track incidents and improve response efficiency.  

---

## Methodology

1. **Infrastructure Setup**  
   - Spun up Elasticsearch and Kibana instances to establish the foundation for security monitoring.  
   - Deployed Windows and Linux servers for simulating target environments.  

2. **Log Management & Analysis**  
   - Ingested system and application logs into Elasticsearch for centralized analysis.  
   - Configured alerts to detect brute force attempts and other suspicious activities.  

3. **Threat Simulation**  
   - Set up a Command & Control server to replicate real-world attack vectors.  
   - Simulated SSH and RDP brute force attacks to observe system behavior and test detection mechanisms.  

4. **Incident Response Workflow**  
   - Integrated a ticketing system to document and manage security incidents.  
   - Responded to simulated attacks by analyzing logs, generating alerts, and closing tickets efficiently.  

5. **Visualization**  
   - Built dashboards to visualize attack trends and system activity, enabling real-time monitoring and actionable insights.  

---

## Architecture Overview

### 1. Security Monitoring System
- Centralized log collection and analysis using Elasticsearch & Kibana.  
- Windows and Linux servers serve as the testbed for detecting incidents.  

### 2. Incident Management Workflow
- Alerts from Kibana feed into a ticketing system for streamlined resolution.  

### 3. C2 Server Integration
- Hosted a command & control server to simulate and understand advanced threats.  

*(Include an architecture diagram here for added impact.)*

---

## Results & Insights

- **Improved Threat Detection**  
  - Successfully detected and investigated SSH brute force and C2 activities.  
  - Visualized system anomalies in real-time, enabling faster responses.  

- **Streamlined Incident Response**  
  - Integrated a ticketing system to ensure a structured approach to incident handling.  
  - Reduced response time for resolving security incidents by leveraging automation.  

- **Enhanced Understanding of Threats**  
  - Developed a deeper understanding of attacker techniques, including C2 mechanisms.  

---

## Before & After Scenarios

### Initial State:
- Ingested raw logs and observed incidents manually.  
- Limited visibility into attack patterns and system performance.  

### Final State:
- Automated alerting and incident tracking through Kibana and a ticketing system.  
- Real-time monitoring with custom dashboards displaying key metrics and trends.  

---

## Key Artifacts

*Ref 1: Architecture Diagram*

![Architecture Diagram](https://github.com/user-attachments/assets/38a33ebf-066b-477a-aa2c-92868ef5e086)

*Ref 2: Elastic Dashboard Displaying Alerts*

![Elastic Dashboard Displaying Alerts](https://github.com/user-attachments/assets/b55ae1fa-f586-4f7d-9855-ebfd8383c52b)

*Ref 3: Creating Dashboard*

![Creating Dashboard](https://github.com/user-attachments/assets/0c5cd83f-2167-42eb-ab3d-e0107a072576)

*Ref 4: Set up your own command & control server*

![Set up your own command & control server](https://github.com/user-attachments/assets/fdf1cc41-e1fb-48d0-a28e-21e40db3a1e0)

*Ref 5: Configure and integrate your own ticketing system*

![Configure and integrate your own ticketing system](https://github.com/user-attachments/assets/3377f4e5-b0e6-4fe1-a376-3ec24f9b1201) 

---

## Conclusion
This project exemplifies a comprehensive approach to setting up and managing a security monitoring system. From threat simulation to incident response, every aspect was designed to emulate real-world SOC operations. The integration of diverse tools and techniques highlights both technical proficiency and a practical understanding of cybersecurity principles.  


---

I have written a detailed blog post about my journey building a security monitoring system. You can read it [here](https://medium.com/@ac243501/30-day-journey-building-a-security-monitoring-system-with-elasticsearch-kibana-05849f59ee2d).


