# Privacy & Redaction Policy
**ETHAN Case Repository**  
**Maintainer:** Diana Gayanovich

---

## Purpose

This document establishes the privacy and redaction standards for all materials published in this repository. The goal is to maximize transparency and public awareness while protecting the privacy rights of minors and non-public individuals.

---

## 1. Guiding Principles

### 1.1 Public Interest vs. Privacy Balance
- **Public interest:** Documenting institutional failures and systemic problems in Belgium's legal system serves a legitimate public interest.
- **Privacy protection:** Minors, private individuals, and non-public officials have privacy rights that must be respected.
- **Proportionality:** Only information necessary to demonstrate the claims should be published.

### 1.2 Transparency and Accountability
- All redactions should be documented with reasoning.
- Redacted versions should maintain evidentiary value while removing identifying information.
- Unredacted originals remain offline in secure storage.

---

## 2. What Must Be Redacted

### 2.1 Minors
- **Full names** of all minors (including Ethan) → use pseudonyms or initials
- **Birth dates** → use age or year only
- **National ID numbers** → fully redact
- **School names** → use only when institutionally necessary (e.g., "Damiaan School" may be used as it's central to the case)
- **Photographs** of minors → never publish without consent

**Exception:** Ethan's first name may be used as it's the case identifier, but last name must be redacted.

### 2.2 Private Individuals
- **Full names** of non-public staff, teachers, social workers → use roles/titles only (e.g., "CLB counselor," "SDJ caseworker")
- **Contact information** (addresses, phone numbers, emails) → fully redact
- **Personal details** irrelevant to the case → redact

**Exception:** Names of public officials acting in their official capacity (judges, prosecutors) may be used if relevant to accountability.

### 2.3 Sensitive Information
- **Medical details** beyond what's necessary to establish harm → redact specifics
- **National ID numbers, social security numbers** → fully redact
- **Financial information** → redact except where relevant to subsidy claims
- **Exact addresses** → use city/region only

---

## 3. What May Be Published

### 3.1 Institutional Information
- **Institution names:** Schools, CLB, courts, SDJ, hospitals (where relevant)
- **Official titles:** Judges, prosecutors, police (without personal names unless public officials)
- **Case numbers:** Where necessary for verification (consider partial redaction)
- **Dates:** Essential for timeline and procedural analysis

### 3.2 Substantive Content
- **Legal arguments** and procedural analysis
- **Timeline of events** with dates
- **Quotes from official documents** (with PII redacted)
- **Findings from expert reports** (with PII redacted)
- **Contradictions between official claims and evidence**

---

## 4. Redaction Methods

### 4.1 Visual Redaction (PDFs/Images)
- Use **permanent black boxes** (not just highlighting)
- Ensure underlying text is removed, not just covered
- Verify redactions cannot be removed or reversed
- Tools: Adobe Acrobat Pro (redaction tool), PDF-XChange Editor, or similar

### 4.2 Text Redaction (Documents/Transcripts)
- Replace names with **[NAME REDACTED]** or **[INITIALS]**
- Replace IDs with **[ID REDACTED]**
- Maintain sentence structure for context
- Use **[...]** for longer redacted passages

### 4.3 Metadata Removal
- Strip all metadata from PDFs and images before publishing
- Remove author, creation date, and editing history
- Tools: ExifTool, PDF metadata strippers

---

## 5. Storage and Handling

### 5.1 Unredacted Originals
- **Never** store unredacted originals in this repository
- Maintain offline storage with encryption
- Keep secure backups in multiple locations
- Document chain of custody

### 5.2 Redacted Versions
- Store in appropriate `/evidence/` subdirectories
- Use clear filename conventions indicating redaction status
- Example: `2021-10-28_incident_report_REDACTED.pdf`

### 5.3 Audit Trail
- Maintain a log of what was redacted and why
- Document redaction decisions in `/evidence/INDEX.md`
- Record who performed redactions and when

---

## 6. Redaction Audit Trail Template

For each redacted document, record:

| Document | Redaction Date | Performed By | Elements Redacted | Reason | Original Location |
|----------|----------------|--------------|-------------------|--------|-------------------|
| 2021-10-28_incident_report.pdf | 2025-12-11 | DG | Minor's full name, teacher names, addresses | Privacy protection per §2.1, §2.2 | Secure offline storage |

---

## 7. Review and Updates

### 7.1 Ongoing Review
- Periodically review published materials for adequacy of redactions
- Update redactions if new privacy concerns identified
- Remove materials if privacy balance shifts unfavorably

### 7.2 Legal Compliance
- Ensure compliance with GDPR (EU General Data Protection Regulation)
- Ensure compliance with Belgian privacy laws
- Consult legal counsel on any uncertain redaction decisions

### 7.3 Feedback Mechanism
- Individuals who identify privacy concerns can contact [maintainer contact]
- Legitimate privacy concerns will be addressed within 7 days
- Document all privacy-related communications

---

## 8. Special Considerations

### 8.1 Public Officials
- Public officials acting in official capacity have reduced privacy expectations
- Names may be used where relevant to accountability
- Personal/private information still protected

### 8.2 Institutional Accountability
- Institution names generally not redacted (schools, agencies, courts)
- Essential for public understanding and accountability
- Individual staff within institutions protected per §2.2

### 8.3 Medical/Psychological Information
- Only publish medical findings necessary to establish harm causation
- Specific diagnoses may be named (e.g., "cPTSD") where relevant
- Detailed symptoms, treatments, and private medical history redacted

---

## 9. Consequences of Privacy Violations

If unredacted or inadequately redacted materials are discovered:
1. **Immediate removal** from public repository
2. **Assessment** of potential harm
3. **Notification** of affected individuals (if appropriate)
4. **Correction** of redaction procedures
5. **Documentation** of incident and remediation

---

## 10. Contact for Privacy Concerns

If you believe materials in this repository violate privacy rights:
- Contact: [maintainer email or contact method]
- Include: specific file, location, nature of concern
- Response time: within 7 days
- Resolution: removal or additional redaction as appropriate

---

## 11. Declaration of Good Faith

This repository is maintained in good faith for the purpose of:
- Documenting institutional failures in the Belgian legal system
- Advocating for systemic reform
- Protecting the rights of children and families
- Promoting transparency and accountability

All privacy measures are undertaken in accordance with Belgian and EU law, and with respect for the dignity and rights of all individuals involved.

---

**Change log**
- v1.0 — Initial privacy policy (2025-12-11).

---

**Acknowledgment:**

I, Diana Gayanovich, as maintainer of this repository, acknowledge my responsibility to uphold these privacy standards and to handle all materials with care and respect for individual privacy rights.

Signed: _______________________________  
Date: _______________________________
