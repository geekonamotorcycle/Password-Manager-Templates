# OpenAI API Key Management Template

## Overview

This template provides a standardized way to store and document OpenAI API keys in LastPass. It captures all necessary metadata to ensure secure usage, easy rotation, and full auditability.

## Purpose

- **Security**: Keep your keys protected and ensure you know exactly which key is used where.
- **Auditability**: Track who created, used, rotated, or revoked a key, and when.
- **Operational Efficiency**: Quickly locate the right key for the right environment or service.

## Fields Included

### **Essential Fields**

- **Title**  
  Human-readable name (e.g. `openai-prod-chatbot`)
- **URL**  
  API base URL: `https://platform.openai.com/`
- **API Key**  
  The full `sk-…` key (Password field)
- **Key Prefix**  
  First 8–12 characters for quick lookup (Text w/ copy)

### **Environment & Lifecycle**

- **Environment**  
  `development` / `staging` / `production` (Text)
- **Created On**  
  Date generated (Month Day Year)
- **Expires On**  
  Scheduled rotation or expiry (Month Day Year)
- **Next Rotation**  
  High-level reminder (Month Year)

### **Access & Permissions**

- **Scopes & Permissions**  
  Comma-separated list (e.g. `chat:write, files:read`) (Text)
- **Org / Account ID**  
  Your OpenAI Org ID or billing email (Text)

### **Audit & Notes**

- **Notes**  
  (LastPass’s built-in Notes box)
  - Deployment details (CI/CD var names, branch names)
  - “Rotation policy: every 90 days”
  - Who requested the key, ticket numbers, audit links

## Best Practices

- Rotate keys on your scheduled **Expires On** date.
- Grant only the least-privilege scopes needed.
- Keep the **Notes** section up to date with any service or pipeline changes.
- Revoke and document old keys immediately after rotation.

## Contribution Guidelines

1. To add or modify fields, update both this `README.md` and the LastPass template file under `lastpass/`.
2. Follow existing formatting and section order.
3. Submit a pull request with a clear description of your change.

## License

This template is part of the Password-Manager-Templates repo and is available under the MIT License.
