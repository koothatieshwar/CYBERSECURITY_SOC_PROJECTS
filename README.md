# CYBERSECURITY_SOC_PROJECTS
1. AI Biometric Anti-Spoofing Defender
This tool implements a non-intrusive security layer that verifies user identity based on unique typing rhythms. It moves beyond static passwords by ensuring that the person currently using the device matches the authorized owner's physical behavior.
Core Technology: Unsupervised Anomaly Detection using Isolation Forest.
Key Features:
-Analyzes Dwell Time (duration a key is held) and Flight Time (interval between keys).
-Establishes a behavioral "Digital Fingerprint" unique to the user.
-Triggers real-time alerts if a "Spoofing" or session-hijacking attempt is detected.
Use Case: Preventing unauthorized physical access to critical workstations or "Insider Threats".
2. AI Steganography Auditor
Focusing on the Digital Forensics domain, this tool is designed to audit and detect hidden data within digital media. It addresses the risk of hackers hiding malicious code or stolen information inside harmless-looking image files.
Core Technology: Bit-level Forensic Analysis and Image Security auditing.
Key Features:
-Identifies visual anomalies that indicate hidden data (Steganography).
-Functions as a forensic tool for image integrity verification.
Use Case: Detecting data exfiltration where employees or hackers attempt to smuggle sensitive files through image-based "TV Static" versions or hidden layers.
3. Project SENTINEL: AI-Powered Multi-Vector Threat Correlation
Project SENTINEL is a high-level SIEM/SOAR logic engine that acts as the "Chief Medical Officer" of the security environment. Instead of looking at individual alerts, it correlates multiple "low-level" signals to identify sophisticated, multi-stage attacks.Core Technology: Ensemble Learning using Random Forest Classifiers.The Correlation Logic:It calculates a Total Risk Score ($R$) by fusing data from different security vectors:
<img width="970" height="70" alt="image" src="https://github.com/user-attachments/assets/e3267d23-af55-4dfa-9202-4453eb4f5be6" />
Key Features:
-Connects "Silent" actions—like a late-night login combined with a large data transfer—that single-sensor tools might ignore.
-Provides Context-Aware Security to reduce "Alert Fatigue" for SOC analysts.
-Suggests autonomous response actions, such as isolating endpoints or revoking credentials in real-time.
Use Case: Advanced Threat Hunting in enterprise environments to stop "Zero-Day" or multi-vector breaches.
