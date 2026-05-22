# Incident Response Playbook: Ransomware Response

**Target Framework:** NIST SP 800-61 Rev. 2  
**Owner:** GRC Compliance Team  

---

## 1. Detection & Analysis
* [ ] Identify infected endpoints via EDR (Endpoint Detection and Response) alerts.
* [ ] Analyze log data in the SIEM to locate the initial point of entry (phishing, unpatched VPN, etc.).
* [ ] Document the scope: Determine which servers, cloud buckets, or file shares are encrypted.

## 2. Containment
* [ ] **Network Isolation:** Disconnect infected machines from the local network and corporate Wi-Fi immediately.
* [ ] **Credential Revocation:** Disable compromised user accounts and rotate active enterprise admin passwords.

## 3. Eradication & Recovery
* [ ] Wipe infected systems completely; do not attempt to decrypt files using attacker tools.
* [ ] Restore clean system images from verified, air-gapped backups.
* [ ] Validate that all restored systems are fully patched before reconnecting to the production network.

## 4. Post-Incident Activities (GRC Lead)
* [ ] Conduct a "Lessons Learned" meeting with technical stakeholders within 48 hours.
* [ ] Update the corporate Risk Register to reflect newly discovered vulnerabilities.
* [ ] Submit the formal Incident Report to executive leadership and legal counsel.
  
## 5. Escalation Contacts
* **Primary:** Contact the CISO via corporate Slack channel `#security-alerts`.
* **Secondary:** Call the Infrastructure Team Lead if servers are unresponsive.