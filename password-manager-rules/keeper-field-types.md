# Keeper Field Type Rules

## Overview

This document outlines the field types supported by Keeper when creating custom templates. Understanding these field types ensures that structured credentials are properly stored and formatted in the Keeper vault.

## Supported Field Types in Keeper

### 1. **Text**

- A free-form text field.
- Used for general descriptions, usernames, or metadata.

### 2. **Secure Note**

- A multi-line encrypted text field.
- Ideal for storing sensitive notes, security policies, or additional context.

### 3. **Password**

- A concealed password field.
- Used for storing login credentials, API tokens, and security keys.

### 4. **File Attachment**

- Allows files to be uploaded within a credential entry.
- Useful for storing security certificates or encrypted key files.

### 5. **Date**

- A structured date field.
- Used for tracking **creation dates, expiration dates, or review timelines**.

## Best Practices for Using Field Types

1. **Use Secure Notes for Sensitive Information** – Store additional sensitive details inside **Secure Note** fields instead of regular text fields.
2. **Leverage Password Fields for Secrets** – Keep passwords and API keys hidden within the **Password** field.
3. **Track Expirations Using Date Fields** – Store renewal, expiration, or review dates in the **Date** field to maintain lifecycle visibility.
4. **Attach Security Files Securely** – Use **File Attachment** fields to store security certificates, encryption keys, or important documents.

## Related Resources

- [Keeper Security Support](https://docs.keeper.io/)
- [How to Use Custom Fields in Keeper](https://docs.keeper.io/user-guides/enterprise-guide/custom-fields)

This document will be updated as Keeper evolves its supported field types and capabilities.
