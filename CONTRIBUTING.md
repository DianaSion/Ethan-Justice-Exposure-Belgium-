# Contributing to the ETHAN Case Repository

Thank you for your interest in contributing to this repository. This document outlines how you can help document institutional failures in Belgium's legal system while maintaining privacy, accuracy, and legal compliance.

---

## Table of Contents
1. [How You Can Help](#how-you-can-help)
2. [Contribution Guidelines](#contribution-guidelines)
3. [Evidence Submission](#evidence-submission)
4. [Privacy and Redaction](#privacy-and-redaction)
5. [Documentation Standards](#documentation-standards)
6. [Review Process](#review-process)
7. [Code of Conduct](#code-of-conduct)

---

## How You Can Help

### 1. Documentation & Analysis
- Help organize and cross-reference existing documents
- Create visual timelines or flowcharts
- Translate materials (Dutch ↔ English ↔ French)
- Identify legal precedents or similar cases
- Draft summaries or explainers for public understanding

### 2. Legal Research
- Research Belgian juvenile law and procedures
- Identify applicable international human rights standards (ECHR, UNCRC)
- Find similar case law or legal arguments
- Review legal filings for accuracy and completeness

### 3. Technical Support
- Improve repository organization
- Create data visualization tools for timeline/evidence
- Build search or indexing tools
- Enhance privacy/redaction workflows
- Set up automated document processing

### 4. Awareness & Advocacy
- Share the repository with relevant organizations
- Contact media or advocacy groups
- Translate materials for international audiences
- Connect with similar cases or systemic reform efforts

### 5. Expert Review
- Medical/psychological experts: review harm model
- Legal experts: review legal arguments
- Social work experts: assess institutional practices
- Child welfare experts: evaluate procedures

---

## Contribution Guidelines

### General Principles
1. **Accuracy first:** All contributions must be factually accurate and evidence-based.
2. **Privacy respect:** Follow all privacy guidelines in `PRIVACY.md`.
3. **Neutrality:** Present facts objectively; let evidence speak for itself.
4. **Cite sources:** All claims must reference specific exhibits or sources.
5. **Collaboration:** Work constructively with maintainers and other contributors.

### What We Accept
- ✅ Evidence-based documentation
- ✅ Legal research and citations
- ✅ Objective analysis and summaries
- ✅ Translations of existing materials
- ✅ Technical improvements to repository
- ✅ Privacy-compliant redactions

### What We Don't Accept
- ❌ Speculation or unverified claims
- ❌ Personal attacks on individuals
- ❌ Unredacted private information
- ❌ Materials without clear provenance
- ❌ Inflammatory or biased language
- ❌ Copyright-infringing content

---

## Evidence Submission

### Before Submitting Evidence

1. **Verify authenticity:** Ensure the document is genuine and accurately represents what it claims to be.
2. **Check relevance:** Confirm the evidence relates directly to the case claims.
3. **Redact properly:** Follow `PRIVACY.md` guidelines to remove all PII.
4. **Document provenance:** Note the source, date obtained, and chain of custody.

### Submission Process

1. **Contact maintainer first:** Don't submit evidence directly via pull request.
2. **Provide context:**
   - What is the document?
   - When and how was it obtained?
   - What does it prove or disprove?
   - How does it fit into the case timeline?
3. **Wait for review:** Maintainer will assess legal/privacy implications.
4. **Follow instructions:** Maintainer will guide you on proper redaction and formatting.

### Evidence Checklist
- [ ] Document is authentic and verifiable
- [ ] All PII redacted per `PRIVACY.md`
- [ ] Metadata stripped from file
- [ ] Source and date documented
- [ ] Relevance to case claims explained
- [ ] Legal right to publish confirmed

---

## Privacy and Redaction

**Critical:** All contributors must read and follow `PRIVACY.md`.

### Key Privacy Rules
1. **Never publish unredacted documents** containing minors' information.
2. **Redact permanently**, not just with highlights or annotations.
3. **Strip metadata** from all files before submission.
4. **Use pseudonyms** for minors and non-public individuals.
5. **Document redactions** in the audit trail.

### If You Find Privacy Violations
If you discover unredacted PII in the repository:
1. **Immediately notify the maintainer** (do not publicize the violation).
2. **Do not copy or share** the unredacted material.
3. **Allow time** for the maintainer to address the issue.

---

## Documentation Standards

### File Naming Conventions
- **Evidence:** `YYYY-MM-DD_short-description_REDACTED.ext`
- **Analysis:** `descriptive-name.md`
- **Filings:** `document-type_short-description.md`

### Markdown Standards
- Use clear, descriptive headings
- Include a table of contents for long documents
- Cross-reference related files with relative paths
- Use tables for structured data
- Include dates in ISO format (YYYY-MM-DD)

### Citation Standards
- Link to exhibits: `/evidence/01_school/2021-10-28_incident_report.pdf`
- Reference timeline: See `/analysis/timeline.md` entry for 2021-10-28
- Cross-reference contradictions: See `/analysis/contradictions.md` #3
- Use anchor IDs from `anchors.csv` for programmatic references

### Commit Message Standards
- **Format:** `[Type] Short description`
- **Types:** `[DOC]` (documentation), `[EVIDENCE]` (new evidence), `[FIX]` (corrections), `[ANALYSIS]` (analytical updates)
- **Example:** `[DOC] Add timeline entry for 2022-11-11 ER visit`

---

## Review Process

### For Small Contributions (typos, formatting, minor clarifications)
1. Submit a pull request with clear description
2. Maintainer reviews within 7 days
3. If approved, merged; if changes needed, feedback provided

### For Substantial Contributions (new evidence, legal arguments, major analysis)
1. **Discuss first:** Open an issue or contact maintainer before drafting
2. **Draft submission:** Prepare materials per guidelines
3. **Initial review:** Maintainer assesses content, privacy, legal issues
4. **Revisions:** Work with maintainer to address any concerns
5. **Legal review:** If needed, materials may undergo legal review
6. **Final approval:** Maintainer merges or integrates the contribution

### Review Criteria
- **Accuracy:** Is the information factually correct and evidence-based?
- **Privacy:** Are all privacy guidelines followed?
- **Relevance:** Does it advance the case documentation?
- **Quality:** Is it well-written, organized, and clear?
- **Legal compliance:** Does it create any legal risks?

---

## Code of Conduct

### Our Standards

**Positive behaviors:**
- Respectful and professional communication
- Focus on evidence and facts
- Collaborative problem-solving
- Constructive feedback
- Recognition of others' contributions

**Unacceptable behaviors:**
- Personal attacks or harassment
- Doxing or privacy violations
- Spreading misinformation
- Inflammatory or defamatory statements
- Copyright infringement
- Obstruction of the repository's purpose

### Enforcement

1. **First violation:** Warning and request for correction
2. **Second violation:** Temporary suspension of contribution privileges
3. **Serious violations:** Permanent ban and potential legal action (for privacy violations, defamation, etc.)

### Reporting Issues

If you witness or experience unacceptable behavior:
- Contact: [maintainer contact]
- Include: description of incident, participants, date/time
- Response: within 48 hours
- Confidentiality: reports handled privately

---

## Legal Considerations

### Copyright & Licensing

- **Evidence documents:** Typically not copyrighted (public records, legal docs) or used under fair use/public interest exception
- **Your contributions:** By contributing, you agree that your original work (analysis, summaries, etc.) is licensed under [specify license, e.g., CC BY 4.0]
- **Attribution:** All significant contributions will be acknowledged

### Liability

- Contributors are responsible for ensuring their submissions comply with applicable laws
- Maintainer reserves the right to remove any content that poses legal risks
- Seek legal advice if uncertain about any submission

### Disclaimers

This repository is for documentation and public awareness purposes. It does not constitute:
- Legal advice
- An official legal filing (use `/filings/` templates as starting points only)
- A complete record of the case (some materials remain confidential)

---

## Getting Started

### First-Time Contributors

1. **Read these documents:**
   - `README.md` (case overview)
   - `PRIVACY.md` (privacy requirements)
   - This file (`CONTRIBUTING.md`)

2. **Explore the repository:**
   - Review `/evidence/INDEX.md`
   - Read `/analysis/timeline.md`
   - Check `/analysis/contradictions.md`

3. **Identify how you can help:**
   - Look for gaps in documentation
   - Check for "help wanted" issues
   - Propose new contributions via issue or email

4. **Start small:**
   - Fix a typo or formatting issue
   - Add a missing cross-reference
   - Improve a summary or explanation

5. **Build from there:**
   - As you become familiar with the case, take on larger contributions
   - Collaborate with maintainer on complex additions

---

## Contact & Questions

**Maintainer:** Diana Gayanovich  
**Contact:** [email or contact method]  
**Response time:** Within 7 days for most inquiries

**For urgent privacy matters:** Contact immediately with subject line "URGENT: Privacy Issue"

---

## Acknowledgments

We are grateful to all who contribute their time, expertise, and effort to documenting this case and advocating for systemic reform. Your work helps ensure that institutional failures are exposed and that similar cases can be prevented in the future.

Together, we work toward a more just and accountable system.

---

**Thank you for contributing to transparency and justice.**
