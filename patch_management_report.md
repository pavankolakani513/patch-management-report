# Research Report: The Importance of Patch Management

## 1. Introduction
Patch management is the systematic process of identifying, acquiring, testing, deploying, and verifying software and firmware updates across an organization's digital assets. It forms the foundational operational pillar of vulnerability management. In modern distributed IT environments, unpatched systems represent one of the primary attack surfaces exploited by threat actors, as public vulnerability disclosures regularly trigger rapid weaponization by attackers before organizations deploy available vendor fixes.

---

## 2. Why Patches Matter: Vulnerabilities, CVEs, and Exploitation

### The Vulnerability Lifecycle
1. **Discovery & Disclosure:** A security flaw is identified by security researchers, vendors, or threat actors.
2. **Cataloging & Scoring (CVE & CVSS):** The vulnerability is assigned a Common Vulnerabilities and Exposures (CVE) identifier and scored using the Common Vulnerability Scoring System (CVSS) to reflect base severity, attack vector, and impact.
3. **Patch Publication:** The software maintainer issues a patch, configuration guidance, or hotfix.
4. **Adversary Reverse-Engineering:** Threat actors analyze the vendor patch (often within 24–48 hours) to create exploits targeting instances that have not yet updated.

### Real-World Breaches Caused by Unpatched Systems

#### 1. WannaCry Ransomware Outbreak (2017)
- **Vulnerability:** CVE-2017-0144 (exploiting SMBv1, known as EternalBlue).
- **Incident Analysis:** In March 2017, Microsoft published Security Bulletin MS17-010 and released patches for supported Windows versions. Two months later, in May 2017, the WannaCry ransomware worm was launched globally.
- **Impact:** It infected over 200,000 systems across 150 countries within days, severely disrupting global logistics, telecommunications, and healthcare providers (including the UK's National Health Service). The devastation occurred despite a vendor patch being publicly available two months prior.

#### 2. The Equifax Data Breach (2017)
- **Vulnerability:** CVE-2017-5638 (Remote Code Execution in Apache Struts).
- **Incident Analysis:** Apache disclosed the vulnerability and released a patch on March 7, 2017. Equifax's internal security team circulated notice to patch instances within 48 hours, but critical internet-facing web portals remained unpatched due to incomplete asset visibility and tracking breakdowns.
- **Impact:** Attackers gained unauthorized access in May 2017 and maintained persistence for over two months, ultimately exfiltrating sensitive personal and financial data belonging to roughly 147 million consumers, resulting in hundreds of millions of dollars in fines and legal settlements.

---

## 3. Consequences of Inadequate Patch Management
Failing to implement an effective patching program results in significant operational and legal hazards:
- **Data Breaches and Intellectual Property Loss:** Attackers use automated scanners targeting known vulnerabilities to extract proprietary assets and customer records.
- **Ransomware Deployment:** Known CVEs in edge appliances, remote desktop gateways, and operating systems serve as standard initial access vectors for extortion groups.
- **Compliance and Regulatory Penalties:** Frameworks such as PCI-DSS, HIPAA, ISO/IEC 27001, and GDPR mandate timely remediation of critical vulnerabilities. Non-compliance exposes firms to severe fines and audit failures.
- **Financial and Reputational Damage:** Prolonged unplanned downtime, incident response fees, and lost customer trust directly impair business operations.

---

## 4. The Patch Management Lifecycle
