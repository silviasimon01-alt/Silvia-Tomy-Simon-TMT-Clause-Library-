# Cybersecurity & Reg-Tech Providers — Clause Compliance Audit Checklist  
*(Cross-Referenced with Cybersecurity-RegTech Linked Clause Library)*  

---

## 1. Definitions & Regulatory Scope  

| Compliance Item | Legal Basis | Audit Checkpoint | Status (✔/✖/N.A.) |
|-----------------|--------------|------------------|-------------------|
| Cybersecurity activities defined (VAPT, SOC, IR) | CERT-In Guidelines 2022 / IT Act §70B | Verify services fall under authorized categories. |   |
| Reg-Tech functions (compliance analytics, regulatory reporting) | DPDP §10; SEBI Circular 2022 | Confirm solution scope aligned to regulated purpose. |   |
| Risk-based security assessment methodology adopted | NIST SP 800-37 / GDPR Art. 32 | Verify existence of risk assessment protocol. |   |

---

## 2. License Grant & SaaS Usage  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| License clearly marked as non-exclusive/non-transferable | Copyright Act §30 / UCC §2-312 | Confirm contract specifies usage scope. |   |
| License limited to internal compliance purposes | DPDP §10(3); GDPR Art. 6(1)(c) | Check that external resale/use is restricted. |   |
| License duration and revocation rights defined | Contract Act §62 | Verify termination and renewal clauses. |   |

---

## 3. Data Protection & Processing  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Data processing purpose and lawful basis specified | DPDP §§7–10 / GDPR Art. 6 | Check existence of DPA (Data Processing Addendum). |   |
| Sectoral compliance identified (RBI/SEBI/IRDAI) | Sectoral IT & Cyber Guidelines | Verify mapping to applicable regulators. |   |
| Data minimization and retention period defined | DPDP §8(6); GDPR Art. 5(1)(e) | Confirm written retention schedule exists. |   |

---

## 4. Security Standards & Controls  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Security controls follow ISO 27001 / NIST 800-171 | FISMA §3554 / CERT-In 2022 | Validate SOC 2 or ISO 27001 certification. |   |
| Vulnerability and patch management implemented | CERT-In 2022 / NIST 800-53 | Review patch logs and CVE remediation cycles. |   |
| Encryption of data at rest and transit ensured | DPDP §8(5); GDPR Art. 32(1) | Verify encryption standards (AES-256, TLS 1.2+). |   |

---

## 5. Incident Notification & Breach Reporting  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Breach reported within 6 hours (India) | CERT-In 2022 | Review incident response SOP and timestamps. |   |
| Notification to data principals/regulators (EU) | GDPR Art. 33 / NIS2 Art. 23 | Confirm reporting workflow and DPO contact defined. |   |
| Post-incident RCA report within 48 hours | CERT-In / DPDP §8(6) | Verify RCA template and corrective action closure. |   |

---

## 6. Client Data Ownership & Return  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Data ownership explicitly vested in client | DPDP §10(3); GDPR Art. 28(3)(g) | Confirm clause grants full ownership rights. |   |
| Secure deletion / return upon termination | NIST SP 800-88 / ISO 27040 | Check data sanitization logs. |   |
| 30-day deletion timeline observed | Contract Act §73 | Verify evidence of timely deletion. |   |

---

## 7. Data Localization (Critical Entities)  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Servers located within India (if critical entity) | IT Act §70; DPDP §16 | Validate hosting certificate / DC location. |   |
| Cross-border transfer approvals documented | GDPR Art. 46; DPDP §16(3) | Check adequacy mechanism or client consent. |   |
| Encryption key control within jurisdiction | CERT-In / NIS2 Directive | Verify key management and storage controls. |   |

---

## 8. Subprocessors & Third-Party Providers  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Client consent for subprocessors obtained | GDPR Art. 28(2); DPDP §10(5) | Check subprocessor register and approvals. |   |
| Flow-down of data obligations included | GDPR Art. 28(4); DPDP §10(5) | Review DPA flow-down template. |   |
| Subprocessor security audits conducted | ISO 27036 / SOC 2 | Verify subcontractor compliance reports. |   |

---

## 9. Confidentiality  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Confidentiality clause includes “strict confidence” | IT Act §72 / Evidence Act §126 | Verify inclusion in main agreement. |   |
| No disclosure without written client consent | GDPR Art. 5(1)(f) | Confirm exceptions are narrowly drafted. |   |
| Confidential data classification applied | ISO 27002 | Check internal data classification matrix. |   |

---

## 10. Audit & Compliance Verification  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Client audit rights defined | DPDP §10(6); GDPR Art. 28(3)(h) | Confirm clause grants inspection access. |   |
| Annual SOC 2 / ISO audits performed | ISO 27001 / SSAE-18 | Review recent audit report. |   |
| CAPA (Corrective Action) process implemented | NIST 800-53 CA-7 | Verify closure rate for audit findings. |   |

---

## 11. Liability Cap & Cyber Risk  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Liability cap ≤ 100% of annual fees | Contract Act §74 | Ensure clause defines limit and exclusions. |   |
| Exclusions for data breach, confidentiality | GDPR Art. 82 / DPDP §33 | Check carve-outs are preserved. |   |
| Cyber insurance coverage maintained | IRDAI Guidelines 2022 | Verify insurance policy and sum assured. |   |

---

## 12. Indemnity (Data Breach / Regulatory Fines)  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Indemnity covers data breach & negligence | DPDP §33 / GDPR Art. 83 | Confirm indemnity language in MSA. |   |
| Includes third-party claims and regulator fines | UCC §2-312(3) | Review indemnity scope and exclusions. |   |
| Caps aligned to liability clause | Contract Act §74 | Check proportionality between indemnity and cap. |   |

---

## 13. Business Continuity & Disaster Recovery  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| BCP/DRP Plan in place and annually tested | ISO 22301 / CERT-In | Verify test results and plan version. |   |
| RTO and RPO defined | NIST 800-34 | Check documented recovery objectives. |   |
| Secondary site geographically separated | ISO 27031 | Validate data center redundancy. |   |

---

## 14. Open-Source & Security Tools  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| OSS usage disclosed and license compliant | GPL v3 / IT Act §43A | Verify OSS inventory. |   |
| Export control compliance (encryption tools) | DGFT ITC(HS) / EAR 772 | Check encryption declarations. |   |
| No copyleft contamination in proprietary modules | GPL v3 Art. 5–6 | Confirm audit via scanning tool (e.g., FOSSA). |   |

---

## 15. Reg-Tech Feed Accuracy  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Sources verified and authentic | RBI / SEBI Circulars | Review update sourcing logs. |   |
| Accuracy and correction protocol established | DPDP §8(5); GDPR Art. 5(1)(d) | Check data quality assurance process. |   |
| Timely updates on regulatory changes | Contract SLA | Validate update frequency (≤24 hours). |   |

---

## 16. Training & Awareness  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Cybersecurity training conducted annually | CERT-In 2022 / NIST 800-50 | Review training records. |   |
| Employees trained on DPDP/GDPR obligations | GDPR Art. 39(1)(b) | Verify training completion rate. |   |
| Record retention of training logs | ISO 27001 Clause 7.2 | Check evidence maintained for audits. |   |

---

## 17. Export Control & Encryption  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| DGFT license obtained for encryption exports | DGFT Notification ITC(HS) | Verify export permissions. |   |
| Compliance with EAR/ITAR (US tech) | EAR 772 / ITAR 121 | Check US-origin software export classification. |   |
| Cross-border encryption transfer approval | DPDP §16 | Confirm regulator or client approval. |   |

---

## 18. Anti-Bribery & Ethics  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Compliance with POCA 1988 | §§7–9 POCA / CVC Manual | Verify declaration form signed. |   |
| FCPA / UK Bribery Act compliance | FCPA 15 USC §§78dd-1; UKBA 2010 | Review anti-corruption policy. |   |
| Whistleblower mechanism in place | ISO 37002 / SEBI LODR | Check hotline / grievance mechanism. |   |

---

## 19. Term & Termination  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Termination for material breach defined | Contract Act §39 | Check definition of “material breach.” |   |
| Regulatory non-compliance triggers termination | DPDP §33 / GDPR Art. 83 | Confirm compliance default provision. |   |
| Post-termination data return/deletion ensured | NIST SP 800-88 | Verify offboarding checklist. |   |

---

## 20. Governing Law & Dispute Resolution  

| Compliance Item | Legal Basis | Audit Checkpoint | Status |
|-----------------|--------------|------------------|--------|
| Governing law clearly stated | §28 Contract Act | Confirm “laws of India” reference. |   |
| Arbitration clause valid under Arbitration Act 1996 | Part I, Arbitration Act | Check seat, procedure, and rules. |   |
| Enforcement under NY Convention if cross-border | NY Convention 1958 | Validate reciprocal territory. |   |

---

## 📘 Optional Annexure Verification  

| Annexure | Description | Verified (✔/✖) |
|-----------|--------------|----------------|
| Annexure A | Technical & Security Specifications |   |
| Annexure B | Data Processing Addendum |   |
| Annexure C | Incident Response Plan |   |
| Annexure D | BCP/DRP Evidence & Reports |   |
| Annexure E | Regulatory Feed Validation Log |   |

---
# Cybersecurity & Reg-Tech Providers — Jurisdictional Enforcement Matrix  

**Legend:**  
✅ = Fully Enforceable | ⚠️ = Partially Restricted / Contextual | ❌ = Void / Prohibited  

---

| # | Clause | India | US | EU | Notes & Legal Authority |
|---|---------|--------|----|----|--------------------------|
| **1** | Definitions & Regulatory Scope | ✅ | ✅ | ✅ | All jurisdictions recognize defined service scope; India: IT Act §70B; US: NIST; EU: NIS2 Directive. |
| **2** | License Grant & SaaS Usage | ✅ | ✅ | ✅ | Standard IP license enforceable; Contract Act §30; UCC §2-312; GDPR Art. 6. |
| **3** | Data Protection & Processing | ✅ | ✅ | ✅ | India: DPDP §§7-10; US: State privacy acts (CCPA); EU: GDPR Art. 28. |
| **4** | Security Standards & Controls | ✅ | ✅ | ✅ | CERT-In 2022 / NIST 800-171 / GDPR Art. 32 all mandate baseline security. |
| **5** | Incident Notification & Breach Reporting | ✅ | ✅ | ✅ | India: 6-hour rule (CERT-In); US: FISMA/State; EU: GDPR Art. 33 (72 h). |
| **6** | Client Data Ownership & Return | ✅ | ✅ | ✅ | Recognized globally; DPDP §10(3); GDPR Art. 28(3)(g). |
| **7** | Data Localization (Critical Entities) | ✅ | ⚠️ | ⚠️ | India requires localization for CIIs; US/EU allow transfers with safeguards. |
| **8** | Subprocessors & Third Parties | ✅ | ✅ | ✅ | Requires consent and flow-down; DPDP §10(5); GDPR Art. 28(2). |
| **9** | Confidentiality | ✅ | ✅ | ✅ | IT Act §72; UCC; GDPR Art. 5(1)(f). |
| **10** | Audit & Compliance Verification | ✅ | ✅ | ✅ | DPDP §10(6); FAR 52.215-2; GDPR Art. 28(3)(h). |
| **11** | Liability Cap & Cyber Risk | ✅ | ✅ | ✅ | Contractually valid with data-breach carve-outs; GDPR Art. 82. |
| **12** | Indemnity (Regulatory Fines) | ✅ | ✅ | ✅ | DPDP §33; UCC §2-312(3); GDPR Art. 83. |
| **13** | Business Continuity & DR | ✅ | ✅ | ✅ | CERT-In / ISO 22301 / NIST 800-34 recognized worldwide. |
| **14** | Open-Source & Security Tools | ✅ | ✅ | ✅ | GPL v3 enforceable globally; export controls vary by region. |
| **15** | Reg-Tech Feed Accuracy | ✅ | ✅ | ✅ | DPDP §8(5); GDPR Art. 5(1)(d); regulators expect verified sources. |
| **16** | Training & Awareness | ✅ | ✅ | ✅ | Mandatory in all frameworks (CERT-In / NIST 800-50 / GDPR Art. 39). |
| **17** | Export Control & Encryption | ✅ | ✅ | ⚠️ | India DGFT, US EAR/ITAR enforce; EU Reg 2021/821 allows restricted dual-use. |
| **18** | Anti-Bribery & Ethics | ✅ | ✅ | ✅ | POCA 1988; FCPA; UK Bribery Act; Directive 2014/24 Art. 24. |
| **19** | Term & Termination | ✅ | ✅ | ✅ | Universally enforceable; Contract Act §39; FAR 52.249-2. |
| **20** | Governing Law & Dispute Resolution | ✅ | ✅ | ✅ | Arbitration valid worldwide; NY Convention recognition. |

---

## 🧭 Interpretation Notes  

| Category | India | US | EU |
|-----------|--------|----|----|
| **Data Localization (7)** | Mandatory for CIIs / government clients | Permitted but voluntary; focus on FedRAMP cloud | Conditional transfer with adequacy or SCCs |
| **Incident Reporting (5)** | 6-hour mandatory (CERT-In 2022) | 72 h (federal agencies); state breach laws apply | 72 h to regulator (GDPR Art. 33) |
| **Export Controls (17)** | Encryption export license via DGFT | EAR / ITAR compliance mandatory | Dual-use export under Reg 2021/821 |
| **Indemnity (12)** | Fully enforceable for breach / fines | Common-law recognition | GDPR fine liability limited to responsibility scope |
| **Liability Cap (11)** | Valid if reasonable (§74 Contract Act) | Common-law standard | Must not undermine Art. 82 compensation rights |
| **Audit (10)** | Required for regulated entities | Standard under FAR / SOC2 | Mandatory under GDPR Art. 28(3)(h) |

---

## ✅ Quick Compliance Color Key  

| Symbol | Meaning |
|---------|----------|
| ✅ | Fully enforceable and standard drafting acceptable |
| ⚠️ | Enforceable only if narrowly tailored or justified |
| ❌ | Prohibited / non-enforceable provision |

---

# Cybersecurity & Reg-Tech Providers — Redline Risk Heatmap  

| Clause | Risk Level | Key Sensitivities | Drafting Guidance |
|---------|-------------|------------------|-------------------|
| **1. Definitions & Scope** | 🟢 Low | Broadly accepted | Ensure clear definition of “Cybersecurity” to include legal authorization for testing. |
| **2. License Grant** | 🟢 Low | IP scope clarity | Avoid ambiguity around resale / analytics rights. |
| **3. Data Protection** | 🟢 Low | Cross-jurisdictional harmonization | Align with GDPR + DPDP terms; include DPA. |
| **4. Security Standards** | 🟢 Low | Technical benchmarks | Reference ISO 27001 + NIST; update yearly. |
| **5. Incident Reporting** | 🟢 Low | Timeframes vary | Include dual window: 6 h (IN) / 72 h (EU). |
| **6. Data Ownership** | 🟢 Low | Fully enforceable | Specify secure deletion and proof of purge. |
| **7. Data Localization** | 🟠 Medium | Jurisdictional divergence | Add waiver if hosted on global cloud. |
| **8. Subprocessors** | 🟢 Low | Client consent | Maintain subprocessor register. |
| **9. Confidentiality** | 🟢 Low | Universal duty | Cross-reference NDA. |
| **10. Audit Rights** | 🟢 Low | Compliance proof | Define notice period; restrict frequency. |
| **11. Liability Cap** | 🟠 Medium | Cap reasonableness | Exclude data breaches from cap. |
| **12. Indemnity** | 🟢 Low | Regulator fines | Align with DPDP §33 / GDPR Art. 83. |
| **13. BCP/DRP** | 🟢 Low | Procedural | Attach test evidence annually. |
| **14. Open-Source** | 🟠 Medium | GPL contagion risk | Keep OSS separate; disclose fully. |
| **15. Feed Accuracy** | 🟢 Low | Content authenticity | Document source logs. |
| **16. Training** | 🟢 Low | Personnel compliance | Annual refresh mandatory. |
| **17. Export Control** | 🟠 Medium | Encryption restrictions | Obtain DGFT / EAR license. |
| **18. Anti-Bribery** | 🟢 Low | Statutory compliance | Annual certification. |
| **19. Termination** | 🟢 Low | Standard | Include cure period. |
| **20. Dispute Resolution** | 🟢 Low | Arbitration enforceable | Seat aligned with governing law. |

---

## 🔍 Regional Risk Summary  

| Region | 🔴 High | 🟠 Medium | 🟢 Low |
|--------|----------|-----------|--------|
| **India** | 0 | 4 (Localization, Liability, OSS, Export) | 16 |
| **US** | 0 | 3 (Export, Liability, OSS) | 17 |
| **EU** | 0 | 4 (Localization, Export, OSS, Liability) | 16 |

---

## ⚖️ Drafting Recommendations  

**🔴 High Risk — none identified.**  
**🟠 Medium Risk — Qualify / Condition:**  
- Add explicit *client consent* for cross-border transfers (DPDP §16).  
- Clarify *GPL disclosure & segregation* of open-source components.  
- Include *data breach carve-out* from liability cap.  
- Verify *encryption export license* per DGFT/EAR.  

**🟢 Low Risk — Standard Boilerplate:**  
- Maintain SLA alignment with ISO/NIST norms.  
- Include standard audit, indemnity, and arbitration clauses.  

---

## 📊 Visual Key for Partner Decks  

| Color | Meaning | Action |
|--------|----------|--------|
| 🔴 | High validity or enforcement risk | Redraft / seek counsel review |
| 🟠 | Medium / context-dependent | Add qualifiers or jurisdictional notes |
| 🟢 | Low risk | Acceptable for standard deployment |

---
