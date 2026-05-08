# Cybersecurity-Risk-Quantification-Lab
A data-driven cybersecurity risk assessment for SecureBank, quantifying technical vulnerabilities into financial impact and demonstrating a 77% reduction in risk exposure through targeted security controls.
# Overview
This project involved a comprehensive security assessment of the SecureMobile platform for SecureBank. The analysis focuses on quantifying technical vulnerabilities into financial risk exposure to drive data-driven executive decision-making.

**Phase 1:** Risk Exposure CalculationUsing standardized risk quantification formulas, I calculated the financial impact for key vulnerabilities:  SLE (Single Loss Expectancy): Impact per incident.  ARO (Annual Rate of Occurrence): Probability of occurrence.  ALE (Annualized Loss Expectancy): $SLE \times ARO.

Vulnerability Breakdown
| Vulnerability | SLE ($) | ARO (%) | ALE ($) | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **Database Injection** | 125,000,000 | 25% | **31,250,000** |Critical
| **Session Hijacking** | 7,500,000 | 40% | **3,000,000** |High
| **API Auth Bypass** | 5,000,000 | 15% | **750,000** |Medium
Key Insight: Database Injection is the dominant risk, accounting for over 89% of the total risk distribution.

**Phase 2:** Control Evaluation & Cost-Benefit Analysis
I conducted a financial evaluation of proposed security controls to determine their effectiveness and Return on Investment (ROI).
| Control | Initial Cost ($) | Risk Reduction ($) | ROI (%) | Payback Period |
| :--- | :--- | :--- | :--- | :--- |
| **WAF** | 150,000 | 23,437,500 | **15,608%** | [cite_start]**2 Days** [cite: 60] |
| **MFA** | 200,000 | 2,850,000 | **1,410%** | [cite_start]**25 Days** [cite: 60] |
| **API Gateway** | 350,000 | 675,000 | **178.6%** | [cite_start]**7 Months** [cite: 60] |

**Primary Recommendation:** The Web Application Firewall (WAF) delivers the highest ROI and is the top priority for immediate risk reduction.

### Strategic Implementation Roadmap
The implementation is divided into three phases to ensure immediate protection and long-term resilience.  
**Immediate (0-30 Days):** Deploy Web Application Firewall (WAF) to eliminate the highest financial risk quickly.  
**Short-Term (30-90 Days):** Implement Multi-Factor Authentication (MFA) to prevent account takeover and fraud.  
**Long-Term (3-12 Months):** Deploy API Security Gateway to strengthen API-level security.  

### Business Value & Conclusion
Implementing these controls will:
Reduce total financial exposure by 77% (from $35M to $8M).  
Improve the organization’s regulatory compliance posture. 
Strengthen customer trust and brand reputation.  

### Documentation
[Download Full Lab Report (DOCX)](./docs/Advanced_Cybersecurity_Risk_Quantification_Ebere_Emilia_Ikechukwu.docx)
