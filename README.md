TaskManagerMA: Malware Analysis & Process Monitoring
Research Internship Project | Indian Institute of Technology (IIT)
📌 Project Overview
This repository contains the research and implementation developed during my Research Internship at IIT. The project, TaskManagerMA, focuses on the intersection of system process management and cybersecurity forensics. The primary goal was to explore how process-level telemetry can be used to detect sophisticated malware behaviors that typically evade standard task managers.

🔬 Research Focus
The project involved analyzing the lifecycle of malicious processes and developing a monitoring framework that captures:

Behavioral Artifacts: Identifying process hollowing, injection, and unusual parent-child relationships.

System Telemetry: Monitoring API calls and registry modifications initiated by suspicious tasks.

Detection Heuristics: Evaluating patterns that differentiate legitimate system utilities from masquerading malware.

📂 Repository Content
/MalwareAnalysis: The core research directory containing scripts for static and dynamic analysis.

ProcessMonitor: (If applicable) Logic for real-time tracking of system tasks.

AnalysisLogs: Sample data and logs generated during the testing of various malware samples in a controlled sandbox.

🛠️ Tools & Technologies Used
Languages: Python / C++ (Adjust based on your actual code)

Analysis Techniques: Static Properties Analysis, Interactive Behavioral Analysis.

Environment: Secure Malware Sandbox (Virtual Machines), Windows API.

Concepts: PE Headers, Entropy Calculation, Persistence Mechanisms, DLL Injection.

🚀 How to Use
Note: This project is intended for research and educational purposes. Always run malware analysis tools in a strictly isolated Virtual Machine.

Clone the Research Repository:

Bash

git clone https://github.com/ashwinrmcf/TaskManagerMA.git
Explore the Analysis Modules: Navigate to the MalwareAnalysis folder to view the research scripts.

Run Sample Analysis:

Bash

python analysis_engine.py --sample <malware_sample_path>
📊 Key Findings
Demonstrated the effectiveness of monitoring specific Windows API sequences to identify ransomware-like behavior.

Developed a lightweight "Task Manager" extension that flags high-entropy processes.

🎓 Internship Acknowledgement
This project was completed as part of a formal research internship at IIT [Insert Campus Name, e.g., Kanpur]. I would like to thank my mentors and the department for their guidance in exploring the complexities of Malware Reverse Engineering and System Security.

👨‍💻 Author
Ashwin Research Intern, IIT GitHub Profile | LinkedIn
