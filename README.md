### **IAM Implementation and Access Control Project**

**Objective**

The IAM Implementation and Access Control Project aimed to create a secure and scalable identity management system using modern IAM practices. The primary focus was on configuring and managing user identities, enforcing access policies, and integrating Multi-Factor Authentication (MFA) and Single Sign-On (SSO) to enhance security across a cloud-based infrastructure. This project simulated real-world scenarios to better understand how to manage user roles, permissions, and security policies in an enterprise environment.

---

**Skills Learned**

- Comprehensive understanding of IAM principles, including user provisioning, authentication, and authorization.
- Proficiency in implementing and configuring **Single Sign-On (SSO)** and **Multi-Factor Authentication (MFA)**.
- Practical experience with cloud-based IAM solutions like **AWS IAM**, **Azure Active Directory (AD)**, and **Google Identity**.
- Knowledge of role-based access control (RBAC), attribute-based access control (ABAC), and policy enforcement.
- Improved understanding of integrating IAM with cloud services and third-party applications for seamless access management.
- Hands-on experience in auditing and managing access logs to ensure compliance with security standards and regulations.

---

**Tools Used**

- **Cloud IAM Platforms**: AWS IAM, Azure AD, Google Cloud Identity.
- **Authentication Tools**: Okta, Auth0 for integrating SSO and MFA.
- **Monitoring and Logging**: Cloud-native tools like **AWS CloudTrail**, **Azure AD Logs**, or **Google Cloud Audit Logs** for auditing and compliance.
- **Security Tools**: Duo Security (for MFA), Ping Identity (for SSO).

---

**Steps**

- **Step 1**: Set up and configure **AWS IAM** (or any other cloud IAM solution) to manage user access, roles, and permissions.
  
  - Created and managed IAM policies for different roles.
  - Configured permissions for cloud resources (e.g., EC2 instances, S3 buckets) based on user roles.

- **Step 2**: Implemented **Single Sign-On (SSO)** using **Okta** to centralize authentication across multiple applications and services.
  
  - Integrated Okta with cloud and on-premises applications.
  - Configured SSO to allow seamless login for users across different services.

- **Step 3**: Implemented **Multi-Factor Authentication (MFA)** to strengthen access security.
  
  - Configured MFA using tools like **Duo Security** or **Auth0** to require additional authentication steps (e.g., push notifications, SMS, or authenticator apps) during login.

- **Step 4**: Applied **Role-Based Access Control (RBAC)** and **Attribute-Based Access Control (ABAC)** to assign users to appropriate access levels based on roles or attributes.
  
  - Defined custom roles and assigned permissions based on the principle of least privilege.

- **Step 5**: Audited access logs to ensure that all user activity was logged and compliant with security policies and regulations.
  
  - Used tools like **AWS CloudTrail** or **Azure AD Logs** to monitor user access and detect any unauthorized or suspicious behavior.


References

- **Ref 1: IAM Dashboard** – Displays the IAM dashboard with user roles, permissions, and policies configured within AWS IAM or Azure AD.



- **Ref 2: Okta SSO Integration** – A screenshot showing the Okta admin panel, highlighting the integration of various applications with SSO enabled.



- **Ref 3: MFA Configuration** – Shows the MFA configuration page where multiple authentication methods (push notifications, SMS) are enabled for secure login.



- **Ref 4: Access Log Auditing** – A screenshot of the **CloudTrail** or **Azure AD Logs**, demonstrating how access events and user activities are logged for monitoring.


