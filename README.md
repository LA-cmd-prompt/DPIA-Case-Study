# DPIA-Case-Study
DPIA template + completed example
# Data Protection Impact Assessment (DPIA) – SmartCity Surveillance

## 1. Project Overview
**Project:** SmartCity Surveillance Initiative  
**Owner:** City of [Fictional Canadian Municipality]  
**Prepared by:** LA-cmd-prompt (Privacy Compliance Professional)  
**Date:** March 2025  

**Objective:**  
Deploy AI-enabled CCTV systems in public spaces to enhance safety, monitor traffic, and support law enforcement.

---

## 2. Description of Processing
- **Data Collected:**  
  - Video footage (24/7 recording).  
  - Biometric data (facial recognition templates).  
  - License plate numbers.  
  - Metadata (time, location, movement).  

- **Scale:**  
  - 500 cameras across city core.  
  - Expected to process millions of individuals’ data annually.  

- **Storage & Retention:**  
  - Data stored in cloud (AWS Canada).  
  - Facial recognition matches retained for 30 days.  
  - Video footage retained for 90 days unless flagged.  

---

## 3. Legal & Regulatory Basis
- **Canada:** PIPEDA (private vendor data processing) + Charter rights (privacy in public spaces).  
- **EU Model Reference:** GDPR Art. 35 (DPIA required for systematic monitoring, large-scale biometric processing).  

---

## 4. Assessment of Necessity & Proportionality
- **Necessity:** Supports crime prevention, traffic monitoring.  
- **Proportionality:** Concerns raised: surveillance scope vs. individual privacy.  
- **Alternatives Considered:** Motion sensors, anonymized traffic analytics (lower risk).  

---

## 5. Risk Assessment

| Risk Category         | Description | Likelihood | Impact | Mitigation |
|-----------------------|-------------|------------|--------|------------|
| Mass Surveillance     | Individuals constantly monitored in public spaces | High | High | Limit scope to high-crime areas; disable constant tracking |
| Misidentification     | Facial recognition false positives | Medium | High | Accuracy testing, human review required before enforcement |
| Unauthorized Access   | Hackers stealing video/biometric data | Medium | High | AES-256 encryption, role-based access, logging |
| Function Creep        | Data used for purposes beyond original (e.g., marketing) | Medium | High | Purpose limitation contracts; strong governance |
| Public Trust Erosion  | Citizens feel unsafe or discriminated against | High | High | Transparency campaigns, public consultations, opt-outs |

---

## 6. Mitigation Strategies
- **Technical:** Strong encryption, access controls, anonymization of non-relevant footage.  
- **Organizational:** Clear governance, privacy training for staff, DPIA reviews every 12 months.  
- **Transparency:** Publish data usage policies, hold public information sessions.  
- **Human Oversight:** Facial recognition matches require human officer review before action.  

---

## 7. Residual Risks
- Inherent tension between public safety and civil liberties.  
- Public perception risks may remain even with safeguards.  

---

## 8. Conclusion
While the SmartCity Surveillance project offers safety benefits, **residual high risks remain** for rights and freedoms.  
Recommendation: proceed only if mitigations (strong governance, human oversight, strict purpose limitation) are fully implemented.  

**Signed Off By:**  
- Privacy Officer – City of [Fictional Municipality]  
- LA-cmd-prompt (Privacy Compliance Professional)  
