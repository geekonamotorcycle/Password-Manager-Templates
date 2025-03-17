# 1Password Field Type Rules

## Overview

This document outlines the field types supported by 1Password when creating custom templates. Understanding these field types ensures that structured credentials are properly stored and formatted in the 1Password vault.

## Supported Field Types in 1Password

### 1. **Password (CONCEALED)**

- A concealed field for storing passwords and secret keys.
- Remains hidden unless explicitly revealed.
- Ideal for API keys, login credentials, and security tokens.

### 2. **Text (STRING)**

- A standard text string field.
- Used for descriptions, usernames, or additional metadata.

### 3. **Email (EMAIL)**

- A dedicated field for storing email addresses.
- Helps with autofill and categorization.

### 4. **URL (URL)**

- A web address field.
- Used for linking login credentials to websites.

### 5. **Date (DATE)**

- A structured date field formatted as **YYYY-MM-DD**.
- Used for tracking creation dates, expiration dates, or access review timelines.

### 6. **Month/Year (MONTH_YEAR)**

- A date field formatted as **YYYYMM** or **YYYY/MM**.
- Ideal for tracking validity periods without specific days.

### 7. **Phone (PHONE)**

- Stores phone numbers in a structured format.
- Useful for storing contact information related to credentials.

### 8. **One-Time Password (OTP)**

- A field specifically for storing **one-time passwords**.
- Supports **otpauth:// URI** values for authentication apps.

### 9. **File Attachment (FILE)**

- Allows file uploads within a credential entry.
- Useful for storing security certificates or encrypted keys.

## Best Practices for Using Field Types

1. **Use Concealed Fields for Sensitive Information** – Passwords, API keys, and security tokens should always be stored in the **Password (CONCEALED)** field.
2. **Leverage OTP for Secure Authentication** – If storing 2FA secrets, use the **OTP** field rather than a plain text field.
3. **Track Expirations Using Date Fields** – Use **DATE** or **MONTH_YEAR** fields to track credential lifecycles.
4. **Use File Attachments for Certificates** – If storing SSL certificates or encrypted documents, upload them as **FILE ATTACHMENT**.

## Related Resources

- [1Password Developer Documentation](https://developer.1password.com/docs/cli/item-fields/)
- [1Password Help Center](https://support.1password.com/)

This document will be updated as 1Password evolves its supported field types and capabilities.
