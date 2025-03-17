# **LastPass Template: AWS IAM SES Keys**

| **Field Name**                  | **Field Type**             | **Purpose** |
|---------------------------------|---------------------------|-------------|
| **Key Name**                    | Text with Copy Button     | Identifies the IAM SES key for easy reference. |
| **Created for Client**          | Text                      | Specifies which client the IAM SES key is assigned to. |
| **Description of Purpose**      | Text                      | Explains the function of the key. |
| **Description of Permissions**  | Notes                     | Documents IAM policy permissions granted by this key. |
| **Created by User**             | Text with Copy Button     | Tracks the LastPass user who generated the key. |
| **Access Key ID**               | Text with Copy Button     | Stores the AWS IAM **Access Key ID** securely. |
| **Secret Access Key**           | Password                  | Securely holds the **IAM Secret Access Key**. |
| **IAM User ARN**                | Text with Copy Button     | Identifies the IAM user associated with the key. |
| **IAM Policy ARN**              | Text with Copy Button     | Stores the AWS policy assigned to this key. |
| **IAM Group Membership(s)**     | Text with Copy Button     | Identifies which IAM group(s) the user belongs to. This determines inherited permissions. |
| **AWS Region**                  | Text with Copy Button     | Specifies the AWS region where SES is configured (e.g., us-east-1). |
| **SMTP Server Address**         | Text with Copy Button     | Stores the SMTP endpoint required for sending email via SES. |
| **SES Sending Limits**          | Notes                     | Captures SES email sending limits and restrictions. |
| **SES Verified Domains**        | Notes                     | Lists SES-verified domains for email sending. |
| **SES Identity Type**           | Text                      | Indicates whether the identity is a domain, email, or IAM user. |
| **Created Date**                | Month/Day/Year Picker     | Logs the creation date for auditing purposes. |
| **Revoked Date**                | Month/Day/Year Picker     | Tracks when the key was revoked. |
| **Revoked by User**             | Text with Copy Button     | Records who revoked the key for accountability. |
| **Revocation Reason**           | Notes                     | Captures the reason the key was revoked. |
| **Creation Ticket Number**      | Text with Copy Button     | Links to the ticket documenting key creation. |
| **Revocation Ticket Number**    | Text with Copy Button     | Links to the ticket documenting key revocation. |

---
