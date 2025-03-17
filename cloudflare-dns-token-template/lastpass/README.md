# Cloudflare DNS API Token - LastPass Template

## Overview

This document provides a **LastPass-specific template** for storing Cloudflare DNS API tokens securely.  
It follows **LastPass field type rules** to ensure compliance with security best practices, password management standards, and auditing requirements.

## Purpose

Cloudflare API tokens allow automation and API-based control over **DNS records, firewall rules, caching, and other Cloudflare services**.  
This template ensures that **API keys are properly stored, tracked, and managed** in accordance with **security best practices**.

## Field Types Used

This template uses **LastPass-supported field types** to maintain structured and secure storage:

- **Text with Copy Button** → Used for reference fields that need quick access (e.g., token names, zone/account IDs).  
- **Text** → Stores descriptive information (e.g., purpose of the token, client it was created for).  
- **Password** → Used for API keys and sensitive credentials.  
- **Notes** → Used for additional information, such as permission details and revocation reasons.  
- **Month/Day/Year Picker** → Used for tracking creation and revocation dates.  

## Usage Guidelines

1. **Store all API tokens in LastPass** – Never store them in plaintext, emails, or documentation files.  
2. **Enable Multi-Factor Authentication (MFA)** for all Cloudflare accounts with API token access.  
3. **Use separate API tokens for different functions** (e.g., DNS updates vs. firewall rule changes).  
4. **Ensure API tokens have the least privilege required** for the intended operation.  
5. **Revoke and regenerate API tokens regularly**, especially if a token is no longer needed or suspected to be compromised.  
6. **Always log the creation and revocation of API tokens** using a ticketing system and store the ticket numbers in LastPass.

## Template File

The template is available in the [`cloudflare-dns-token-lastpass.md`](./cloudflare-dns-token-lastpass.md) file.

---

## Security & Compliance Considerations

- **Regulatory Compliance**:  
  - This template aligns with **NIST SP 800-63B**, **ISO 27001**, **SOC 2**, and **CISA best practices** for secure password and credential storage.  
  - All **sensitive fields use the Password type** to prevent accidental exposure.  
- **Auditing & Traceability**:  
  - Creation and revocation ticket numbers are included for **audit trails and compliance tracking**.  
- **Least Privilege**:  
  - API tokens should always be assigned **only the minimum required permissions** to perform their function.  
- **Revocation & Rotation**:  
  - Tokens should be **periodically rotated and immediately revoked** if compromised.

---

## Contributing

If you have suggestions for improving this template, follow these steps:

1. Fork the repository and create a new branch.
2. Update `cloudflare-dns-token-lastpass.md` with necessary changes.
3. Submit a pull request with a description of the changes.

---

## Related Documentation

- [Cloudflare API Token Documentation](https://developers.cloudflare.com/api/tokens/)
- [LastPass Field Type Reference](https://support.lastpass.com/s/document-item?language=en_US&bundleId=lastpass&topicId=LastPass/t_lp_edit_or_delete_an_item.html)
- [Secure Password Management Best Practices](../best-practices-for-password-management.md)

---
