#AWS-Cloud Security Project→Configuring and hardening cloud console in AWS Environment

I completed this project showing the design and deployment of a secure cloud infrastructure on Amazon Web Services (AWS).Focusing on Identity and Access Management (IAM), resource tagging and continuous security monitoring.
The environment simulates a realworld enterprise setup with two departments (Deployment and Distribution) each managing its own EC2 instances and governed by IAM policies that enforce the Principle of Least Privilege (PoLP).
Using a combination of custom IAM policies, groups, and tag-based access control (ABAC), this project ensures that only authorized users can perform specific actions on designated cloud resources.Security visibility and compliance are achieved through AWS CloudTrail and AWS Config, which track all API activity and configuration changes across the infrastructure.

Tools & Concepts

Amazon Web Services (AWS) →Cloud platform used for deployment and management.
Amazon EC2 →Virtual servers representing Deployment and Production environments.
AWS Identity and Access Management (IAM)→Core service for user, group, and policy control.
AWS CloudTrail → Logs and monitors API and console activity.
AWS Config→ Tracks configuration changes for compliance and governance.
Amazon S3→Secure storage for audit and configuration logs.
AWS Management Console→Centralized UI for administration and resource control.

Security Concepts

Principle of Least Privilege (PoLP) →Users only have permissions necessary for their role.
Attribute-Based Access Control (ABAC)→Resource access managed through tags like Env=Deployment and Env=Distribution.
Role-Based Access Control (RBAC)→Permissions assigned via IAM groups.
Cloud Governance & Auditing→Continuous monitoring using CloudTrail and AWS Config.
Multi-Factor Authentication (MFA)→Enhanced account protection for IAM users.
