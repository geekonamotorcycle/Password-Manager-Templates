# Bitwarden Field Type Rules

## Overview

This document outlines the field types supported by Bitwarden when creating custom templates. Understanding these field types ensures that structured credentials are properly stored and formatted in the Bitwarden vault.

## Supported Field Types in Bitwarden

### 1. **Text**

- A free-form text field.
- Used for storing descriptions, usernames, or additional metadata.

### 2. **Hidden**

- Functions like a standard text field but keeps the value hidden.
- Ideal for **API keys, secret tokens, or private credentials**.

### 3. **Boolean**

- Stores a **true/false** value.
- Used for tracking whether a feature is enabled or disabled.

### 4. **Linked**

- Links the field value to the item's **username or password**.
- Useful for autofill scenarios where standard fields don’t apply.

## Best Practices for Using Field Types

1. **Use Hidden Fields for Sensitive Information** – API keys and security tokens should be stored in **Hidden** fields rather than plain text.
2. **Utilize Boolean Fields for Toggle States** – If storing access status (e.g., enabled/disabled), use **Boolean** fields instead of text.
3. **Leverage Linked Fields for Autofill** – If an application needs an alternate username or password, use **Linked** fields instead of duplicating data.

## Related Resources

- [Bitwarden Custom Fields Documentation](https://bitwarden.com/help/custom-fields/)
- [Bitwarden Support Center](https://bitwarden.com/help/)

This document will be updated as Bitwarden evolves its supported field types and capabilities.
