# Repository Security Configuration Guide

**Maintainer:** Diana Gayanovich  
**Purpose:** Securing this sensitive legal documentation repository  
**Date:** February 2026

---

## Why Security Matters for This Repository

This repository contains sensitive legal documentation related to institutional failures in Belgium's juvenile justice system. Proper security protections ensure:

- Evidence integrity and authenticity
- Protection against unauthorized modifications
- Prevention of evidence tampering claims
- Maintaining chain of custody for legal materials
- Safeguarding privacy-sensitive redacted documents

---

## GitHub Account Protection Setup

### Enabling Two-Factor Authentication (2FA)

GitHub 2FA adds an extra security layer requiring both your password and a second verification method.

#### Step-by-Step Setup Instructions

**1. Access Security Settings**
   - Navigate to: github.com (logged in)
   - Click your profile photo (top right corner)
   - Select: "Settings"
   - Left sidebar: click "Password and authentication"

**2. Initiate 2FA Configuration**
   - Locate section: "Two-factor authentication"
   - Click green button: "Enable two-factor authentication"

**3. Choose Your Authentication Method**

   **Option A: Mobile Authenticator App (Recommended)**
   - Download an authenticator app on your phone:
     * Authy (recommended - works across devices)
     * Microsoft Authenticator
     * Google Authenticator
   - Scan the QR code shown on GitHub with your authenticator app
   - Enter the 6-digit verification code from your app
   
   **Option B: SMS Text Messages**
   - Select "Set up using SMS"
   - Enter your mobile phone number
   - Receive and enter verification code via text message
   - Note: SMS is less secure than authenticator apps but easier to use

**4. Save Recovery Codes (CRITICAL)**
   - GitHub will display recovery codes
   - **Download these codes immediately**
   - Store them securely offline (printed paper in safe location)
   - These codes are your backup access if you lose your phone
   - Without these codes, you may lose repository access permanently

**5. Verify Configuration**
   - Log out of GitHub
   - Log back in to test 2FA is working
   - You should be prompted for your second factor

---

## Troubleshooting Common 2FA Issues

### "I don't see the 2FA option"

**Possible causes:**
- Your account may already have 2FA enabled
  * Check: Settings → Password and authentication → Look for "Two-factor methods"
- You may be using a managed organization account
  * Contact your organization administrator

**Solution:** 
- Verify current 2FA status by checking for existing authentication methods
- Look for "Configured" status under two-factor authentication section

### "My authenticator app isn't working"

**Time synchronization issues:**
- Authenticator apps require accurate device time
- Fix: Go to phone settings → Date & Time → Enable "Automatic date & time"

**Wrong app configuration:**
- Ensure you're looking at the correct account entry in your authenticator app
- Each GitHub account needs its own entry

### "I lost my phone and recovery codes"

**If you're currently logged in:**
1. Immediately go to Settings → Password and authentication
2. Generate new recovery codes
3. Consider adding a backup authentication method

**If you're locked out:**
- Contact GitHub Support with account verification details
- Recovery may require identity verification
- This process can take several days

### "SMS codes aren't arriving"

**Check these factors:**
- Phone number entered correctly (include country code)
- Phone has cellular service
- Messages aren't blocked by spam filter
- Try "Resend code" option

**Alternative:** Switch to authenticator app method instead

---

## Additional Repository Security Measures

### 1. Enable Branch Protection

For this evidence repository, protect your main documentation:

**Settings → Branches → Add rule:**
- Branch name pattern: `main`
- Enable: "Require a pull request before merging"
- Enable: "Require status checks to pass before merging"
- Enable: "Do not allow bypassing the above settings"

This prevents accidental deletion or modification of evidence files.

### 2. Enable Signed Commits

Cryptographically sign your commits to prove authenticity:

```bash
# Configure GPG signing
git config --global commit.gpgsign true
git config --global user.signingkey YOUR_GPG_KEY_ID
```

Signed commits add legal weight by proving document provenance.

### 3. Repository Access Review

Regularly audit who has access:
- Settings → Collaborators and teams
- Remove any accounts that no longer require access
- Use principle of least privilege

### 4. Enable Security Alerts

Stay informed about vulnerabilities:
- Settings → Security & analysis
- Enable "Dependency alerts" (if applicable)
- Enable "Secret scanning alerts"

---

## Security Checklist for Legal Documentation Repositories

- [ ] Two-factor authentication enabled on account
- [ ] Recovery codes saved in secure offline location
- [ ] Branch protection enabled on main branch
- [ ] Regular backups of repository maintained offline
- [ ] Access list reviewed monthly
- [ ] Commit signing configured (optional but recommended)
- [ ] Repository visibility set appropriately (public vs private)
- [ ] Sensitive data properly redacted before commits
- [ ] Audit trail maintained for all evidence additions

---

## Emergency Access Recovery Plan

**If you lose access to your GitHub account:**

1. **Immediate Actions:**
   - Attempt recovery using saved recovery codes
   - Contact GitHub Support: support.github.com

2. **Evidence Protection:**
   - Maintain offline backup of all evidence files
   - Keep copies on encrypted external drive
   - Document all repository contents in separate log

3. **Continuity Measures:**
   - Consider adding a trusted backup maintainer with repository access
   - Maintain documented evidence chain of custody separately
   - Keep paper trail of all repository updates

---

## Questions or Issues?

**2FA specifically not working?**
- GitHub Support: https://support.github.com/
- GitHub Community Forum: https://github.community/

**Repository security questions?**
- Review this document
- Check GitHub's security best practices documentation
- Consider consulting with IT security professional for sensitive repositories

---

## Document Version

Version: 1.0  
Last Updated: 2026-02-06  
Maintainer: Diana Gayanovich
