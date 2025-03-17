# AWS IAM SES Keys - LastPass Template

## Overview

This document provides a **LastPass-specific template** for securely storing AWS IAM SES keys.  
It follows **LastPass field type rules** and **security best practices** to ensure compliance with industry standards for **privileged access management**.

## Purpose

AWS IAM SES keys are used to **authenticate and authorize email-sending services** via AWS Simple Email Service (SES).  
This template helps **track, secure, and audit IAM SES keys** in a structured format.

## Field Types Used

This template is designed with **LastPass-supported field types** to ensure structured, secure, and user-friendly storage:

- **Text with Copy Button** → Used for frequently referenced fields (e.g., Key Name, Access Key ID, IAM Group Memberships).  
- **Text** → Stores descriptive metadata (e.g., Purpose, Client, SES Identity Type).  
- **Password** → Used for **AWS IAM Secret Access Key** to keep it protected.  
- **Notes** → Captures additional details such as IAM permissions, SES limits, and revocation reasons.  
- **Month/Day/Year Picker** → Tracks key creation and revocation dates for compliance.  

## Usage Guidelines

1. **Store AWS IAM SES keys only in LastPass** – Do not store them in plaintext, emails, or internal documentation.  
2. **Enable Multi-Factor Authentication (MFA) for IAM users** – Ensure MFA is required for users managing SES keys.  
3. **Restrict IAM permissions using groups** – Assign permissions through **IAM Groups** rather than direct user policies.  
4. **Enforce least privilege access** – SES API keys should have only the necessary permissions for their intended function.  
5. **Regularly rotate IAM SES keys** – Expired or compromised keys must be **revoked and regenerated**.  
6. **Log all key activities in a ticketing system** – Document **creation and revocation ticket numbers** for auditing.  

## Template File

The full template is available in [`aws-iam-ses-keys-template-lastpass.md`](./aws-iam-ses-keys-template.md).

---

## Security & Compliance Considerations

- **Regulatory Compliance**:  
  - This template aligns with **ISO 27001, SOC 2, NIST SP 800-63B, CISA, and CIS Controls** security best practices.  
  - **IAM Secret Access Key is always stored in a Password field** to prevent unauthorized access.  
- **IAM Role-Based Access Control (RBAC)**:  
  - **IAM Group Membership tracking ensures that permissions are not assigned directly to users.**  
  - **IAM policies should be strictly enforced at the group level** rather than using inline policies.  
- **Least Privilege & Security Audits**:  
  - IAM SES keys should be **restricted to the minimal permissions required for email-sending tasks**.  
  - **Audits must be performed regularly** to ensure **no excessive permissions** are granted to IAM users.  
- **Revocation & Rotation**:  
  - **IAM SES keys must be rotated periodically** to mitigate security risks.  
  - **All revocations should be logged in LastPass** with a **corresponding ticket number** for compliance tracking.  

---

## Contributing

If you have suggestions for improving this template, follow these steps:

1. Fork the repository and create a new branch.
2. Update `aws-iam-ses-keys-template-lastpass.md` with necessary changes.
3. Submit a pull request with a description of the changes.

---

## Related Documentation

- [AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)  
- [AWS SES Developer Guide](https://docs.aws.amazon.com/ses/latest/dg/Welcome.html)  
- [LastPass Field Type Reference](https://support.lastpass.com/s/document-item?language=en_US&bundleId=lastpass&topicId=LastPass/t_lp_edit_or_delete_an_item.html)  
- [Secure Password Management Best Practices](../best-practices-for-password-management.md)  

---
