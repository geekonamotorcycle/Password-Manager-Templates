# LastPass Field Type Rules

## Overview

This document outlines the field types supported by LastPass when creating custom templates. Understanding these field types ensures that structured credentials are properly stored and formatted in the LastPass vault.

## Supported Field Types in LastPass

### 1. **Text**

- A free-form text field.
- Used for descriptions, metadata, or general instructional data.

### 2. **Text with Copy Button**

- A free-form text field with a **copy button**.
- Ideal for **API key names, usernames, emails, or frequently copied information**.

### 3. **Month/Day/Year**

- A structured date field formatted as **MM/DD/YYYY**.
- Used for tracking **creation dates, expiration dates, or revocation dates**.

### 4. **Month/Year**

- A structured date field formatted as **MM/YYYY**.
- Used for general tracking of credential validity periods.

### 5. **Password**

- A concealed password field.
- Used for storing **login credentials, API tokens, and secret keys**.
- Copyable but remains hidden unless explicitly revealed.

### 6. **Notes**

- A multi-line text area for additional information.
- Used for **long descriptions, special instructions, or extra context about an item**.

## Best Practices for Using Field Types

1. **Use Password Fields for Sensitive Information** – Always store API keys, passwords, and secret credentials in **Password** fields rather than text fields.

2. **Enable Copy Buttons for Frequently Copied Fields** – Fields like usernames, API key identifiers, and emails should use the **Text with Copy Button** format.

3. **Use Date Fields for Tracking Expirations** – Always set expiration or revocation dates using **Month/Day/Year** or **Month/Year** fields to improve security tracking.

4. **Leverage Notes for Context** – Use the **Notes** field to provide additional details about the credential, such as its intended purpose or security considerations.

## Related Resources

- [LastPass Custom Items Guide](https://support.lastpass.com/s/document-item?_LANG=enus&bundleId=lastpass&language=en_US&topicId=LastPass%2Fcreate_a_custom_note_type.html)
- [LastPass Official Documentation](https://support.lastpass.com/s/)

This document will be updated as LastPass evolves its supported field types and capabilities.
