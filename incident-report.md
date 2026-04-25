# 📄 Security Analysis Report

## 🧾 Incident Summary
Suspicious network activity was observed during traffic analysis using Wireshark.

## ⏱️ Timeline
- 10:00 – DNS queries detected
- 10:02 – LDAP traffic observed
- 10:05 – TCP communication established

## 🔍 Analysis
Captured packets showed:
- Repeated DNS queries to external domains
- LDAP requests indicating directory access
- TCP handshake activity (SYN, ACK)

## 🚨 Findings
- Possible abnormal network communication
- Potential exposure of directory services
- Unusual traffic patterns

## 🛠️ Recommendations
- Monitor DNS traffic for anomalies
- Secure LDAP services
- Implement network intrusion detection systems

## 📌 Conclusion
The analysis highlights potential security risks in network communication that require monitoring and mitigation.
