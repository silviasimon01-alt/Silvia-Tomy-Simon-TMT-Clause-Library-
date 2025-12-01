This repository contains markdown versions and templates derived from the **DPDP Toolkit Compliance PDF** (privacy notices, consent templates, parental consent, withdrawal forms, consent log template, and an implementation checklist).

**Files included**
- `privacy-notice.md`
- `consent-form.md`
- `withdrawal-form.md`
- `parental-consent.md`
- `consent-log.md`
- `implementation-checklist.md`
- `LICENSE`
---

====================================================================
FILE: privacy-notice.md
====================================================================

# Privacy Notice Template (Layered Format)

**Short summary privacy notice**

## WHO WE ARE
**[YOUR COMPANY NAME]** (“we”, “us”, “our”) is committed to protecting your personal data.  
This privacy notice explains how we collect, use, and safeguard your information under India’s **DPDP Act, 2023** and **Rules, 2025**.

### Data Fiduciary Details:
- **Name:** [Your Company Name]  
- **Address:** [Address]  
- **Contact:** [Email]  
- **Data Protection Officer / Contact:** [Name | Email | Phone]

---

## WHAT DATA WE COLLECT

| Data Type | Examples | Source |
|----------|----------|--------|
| Contact Info | Name, email, phone | Registration, app, website |
| Account Info | Username, password | Account creation |
| Transaction Data | Purchases, invoices | Checkout |
| Device Info | IP, browser, OS | Cookies, analytics |
| Communication | Emails, support messages | Support channels |
| Location | GPS, IP-based | App/website |

Add, remove, or refine data types as needed.

---

## WHY WE USE YOUR DATA (PURPOSES)
- Provide service and manage your account  
- Deliver purchases  
- Send updates (only with consent)  
- Fraud prevention  
- Customer support  
- Analytics and service improvement  
- Legal compliance  

---

## HOW LONG WE KEEP YOUR DATA
Example retention schedule (edit as necessary):

| Data Type | Retention |
|-----------|-----------|
| Account Info | Account lifetime + 1 year |
| Transactions | 7 years (legal) |
| Comms | 2 years |
| Cookies | Browser-dependent |

---

## WHO WE SHARE YOUR DATA WITH
- Service providers (payment, hosting, delivery)  
- Legal authorities (only when required)  
- Business partners (if applicable)  
- Internal group companies  

Cross-border transfers must meet DPDP safeguards.

---

## YOUR RIGHTS
You may:
- Access your data  
- Request correction  
- Request deletion  
- Withdraw consent  
- Nominate a representative  

Withdraw consent anytime via email or account settings.

---

## GRIEVANCE REDRESSAL
- **Officer:** [Name]  
- **Email:** [Email]  
- **Phone:** [Phone]  
Response time: **30 days**

---

## CHILDREN’S DATA
Processing requires **verifiable parental consent** for anyone under **18 years**.

---

## UPDATES TO THIS NOTICE  
Last updated: **[Date]**

---

====================================================================
FILE: consent-form.md
====================================================================

# Consent Form Template (Granular Consent Capture)
## DPDP Consent Form — [Your Company Name]

Dear user,  
Below you may provide explicit consent for specific processing purposes. You may select only what you agree to.

---

## 1. SERVICE DELIVERY (Required)
- Purpose: Provide service/product  
- Data: Contact, account, transaction info  
- Retention: Account lifetime + 1 year  
- Choice:  
  - [ ] **I consent**

---

## 2. MARKETING COMMUNICATIONS (Optional)
- Purpose: Promotions, newsletters  
- Data: Email, browsing, purchase pattern  
- Retention: Until withdrawn  
- Choose:  
  - [ ] Email  
  - [ ] SMS / WhatsApp  
  - [ ] Push Notifications  

---

## 3. ANALYTICS (Optional)
- Purpose: Product improvement  
- Data: Device, pages visited, IP (anonymised)
- Retention: Until withdrawn  
- [ ] I give consent

---

## 4. THIRD-PARTY SHARING (Optional)
- Purpose: Sharing **anonymized** insights  
- Data: Aggregated data  
- [ ] I give consent

---

## 5. COOKIES & TRACKING (Optional)
- Purpose: Personalization, ads  
- Data: Cookies, pixels, device IDs  
- [ ] I give consent  

---

## 6. CROSS-BORDER TRANSFER (If applicable)
- Purpose: Cloud hosting, analytics  
- Destinations: [Countries]  
- Safeguards: DPDP-aligned contracts  
- [ ] I give consent  

---

## CONSENT SUMMARY TABLE

| Purpose | Consent |
|--------|---------|
| Service Delivery | Yes |
| Marketing | Yes / No |
| Analytics | Yes / No |
| Sharing | Yes / No |
| Cookies | Yes / No |
| Cross-Border | Yes / No |

---

## WITHDRAWAL OF CONSENT
Email: **[Email]**  
Or use your account settings.

---

## SIGNATURE
I freely give my consent for the selected purposes.

Name: __________  
Email: __________  
Date: __________  
Signature: __________  

---

====================================================================
FILE: withdrawal-form.md
====================================================================

# Consent Withdrawal Form

## USER DETAILS
- Name: __________________  
- Email: __________________  
- Account ID: ______________  
- Phone: __________________  

---

## CONSENTS TO WITHDRAW
Select all that apply:

- [ ] Marketing communication  
- [ ] Analytics  
- [ ] Third-party sharing  
- [ ] Personalized ads  
- [ ] Cross-border transfers  
- [ ] **All consents** (except service-essential processing)

---

## OPTIONAL DETAILS
Reason for withdrawal: ____________________

---

## WHAT HAPPENS NEXT
- Processing for the withdrawn purpose stops **immediately**  
- Data is deleted within **30 days** unless legally required  
- Confirmation email sent to user  

---

## CONFIRMATION
- [ ] CONFIRM withdrawal  
- [ ] CANCEL  

---

====================================================================
FILE: parental-consent.md
====================================================================

# Parental Consent Verification Form

## CHILD DETAILS
- Name: __________________  
- Date of Birth: _________  
- Account/Email: __________  

---

## PARENT/GUARDIAN DETAILS
- Name: __________________  
- Email: __________________  
- Phone: __________________  
- Relationship: Parent / Legal Guardian  

---

## ID VERIFICATION (Select one)
- [ ] DigiLocker verification  
- [ ] Aadhaar-linked verification system  
- [ ] Government ID (upload)  
- [ ] Email OTP verification  

---

## DATA PROCESSING DETAILS
**Data:** Name, email, age, usage  
**Purpose:** Service delivery, communication, analytics  
**Retention:** Until account deletion or required by law  

---

## DECLARATION
I confirm I am the parent/guardian and provide consent.

Name: __________________  
Signature: _____________  
Date: __________________  

---

## WITHDRAWAL INSTRUCTIONS
Email **[Email]** with subject:  
**“Withdraw Parental Consent – [Child Name]”**

Data deleted within **30 days** (unless legal retention applies).

---

====================================================================
FILE: consent-log.md
====================================================================

# Consent Log Template (DPDP-Compliant)

Suggested columns:

| Field | Description |
|-------|-------------|
| Consent ID | Unique identifier |
| Date | Timestamp (IST) |
| User ID | Email / internal ID |
| Purpose | Marketing, analytics, etc. |
| Consent Type | Given / Withdrawn |
| Legal Basis | Consent / Contract |
| IP Address | For audit proof |
| Device | Browser / OS |
| Withdrawal Date | If applicable |
| Status | Active / Withdrawn |
| Notes | Additional audit detail |

Retention should match legal/audit requirements (e.g., **7 years**).

---

====================================================================
FILE: implementation-checklist.md
====================================================================

# DPDP Implementation Checklist

## PHASE 1 — PREPARATION
- Map all data flows  
- Identify collection points  
- Assign DPO / privacy owner  
- Vendor list & risk classification  
- Audit current compliance  

---

## PHASE 2 — DOCUMENTATION
- Short privacy notice  
- Full privacy policy  
- Consent forms  
- Withdrawal forms  
- Parental consent  
- Record of Processing Activities  
- Data retention schedule  

---

## PHASE 3 — LEGAL REVIEW
- Ensure DPDP compliance  
- Validate cross-border transfer safeguards  
- Revise vendor contracts  

---

## PHASE 4 — TECH IMPLEMENTATION
- Update website/app banners  
- Implement consent management  
- Store consent logs  
- Create user-access/ deletion workflows  

---

## PHASE 5 — TESTING
- Test forms, cookies, withdrawal flow  
- Verify no pre-ticked boxes  
- Validate retention & deletion logic  

---

## PHASE 6 — TRAINING & GO-LIVE
- Train internal staff  
- Publish updated privacy pages  
- Start quarterly compliance checks  

---

====================================================================
FILE: LICENSE
====================================================================

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software...

(You may replace with your preferred license.)

====================================================================

