# Cloudflare DNS API Key Management Template

## Overview

This template is designed for securely managing Cloudflare DNS API tokens within LastPass. It ensures that all relevant metadata is captured to facilitate security, access control, and auditing within IT departments.

## Purpose

The template serves the following key objectives:

- **Security**: Ensures API keys are managed with necessary metadata to prevent unauthorized use.
- **Auditability**: Tracks creation, usage, and revocation of API keys.
- **Operational Efficiency**: Organizes API key storage for easy retrieval and management.

## Fields Included

The following fields are included in this template:

### **Essential Fields**

- **Token Name**: Unique identifier for the API token.
- **CF API Token**: The actual API token for authentication.
- **Key**: Alternative API key if applicable.
- **CF Account ID**: Cloudflare account associated with the API key.
- **CF Zone ID**: Specific Cloudflare DNS zone the key manages.
- **Created Date**: Date the API token was generated.
- **Created by User**: User who generated the API token.
- **Creation Ticket Number**: Internal support ticket number for key creation.

### **Access & Permissions**

- **Permissions Scope**: Defines token permissions (e.g., Read DNS, Edit DNS, Zone Management).
- **Associated Domains**: List of domains the API token has access to.
- **Environment**: Indicates whether token is for Production, Staging, or Development.
- **Usage Notes**: Additional instructions for using the API token.

### **Security & Compliance**

- **Expiration Date**: When the API token is set to expire.
- **Revoked Date**: When the API token was revoked.
- **Revoked by User**: User who revoked the API token.
- **Revocation Reason**: Explanation for why the API token was revoked.
- **Revocation Ticket Number**: Internal support ticket number for key revocation.
- **MFA Requirement**: Whether MFA is required for the associated account.
- **Rotation Schedule**: Defines how often the API token should be rotated.

### **Audit & Monitoring**

- **Audit Log Link**: Link to Cloudflare logs for tracking token activity.
- **Linked Applications**: Services, applications, or scripts using this API token.
- **Backup Contact**: IT contact for assistance with this API token.

### **Additional Considerations (Optional)**

- **Allowed IPs**: IP restrictions for API token usage.
- **Last Used Date**: Helps identify stale or unused API tokens.
- **Token Storage Location**: Where the API token is securely stored (e.g., Vault, HashiCorp Vault).

## How to Use This Template

1. **Download the CSV file**: [Cloudflare DNS API Template CSV](cloudflare_dns_api_template_updated.csv)
2. **Import into LastPass**: Use the CSV import feature in LastPass to create a structured custom item.
3. **Fill out the necessary fields**: Ensure all metadata is documented.
4. **Maintain lifecycle management**: Regularly update token details, expiration dates, and revoke unused tokens.

## Best Practices

- Rotate API tokens periodically based on the **Rotation Schedule**.
- Limit permissions using the **Permissions Scope** field to the least privilege necessary.
- Store the **Audit Log Link** to track all API-related changes.
- Ensure **Allowed IPs** are configured to restrict token use.

## Contribution Guidelines

- If you need to update or add fields, modify both the CSV file and this README.
- Follow the formatting standards for consistency.
- Submit a pull request with a clear description of changes.

## License

This template is part of the LastPass Templates Repository and is open for modification under the MIT License.
