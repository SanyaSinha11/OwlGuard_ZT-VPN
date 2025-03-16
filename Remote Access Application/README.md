OwlGuard - Secure Remote Access Application

Overview

OwlGuard is an application designed to provide secure remote access to enterprise resources. It ensures strong authentication, device posture validation, and policy-based access control to mitigate security risks.

Features

User Authentication – Secure login via a PyQt desktop application.

Device Compliance Check – Assesses system security before granting access.

Automated VPN Setup – Fetches user-specific configurations and connects via OpenVPN.

Centralized Management – Allows administrators to monitor users and manage access.

Certificate-Based Security – Uses EasyRSA for strong encryption and authentication.

Workflow

User Login – The user provides credentials via the OwlGuard application.

Device Posture Evaluation – The application checks compliance (e.g., OS updates, antivirus status, security policies).

Access Decision – If the device meets security standards, the VPN configuration is retrieved.

Secure VPN Connection – OpenVPN Connect is launched for establishing a secure tunnel.

Access Monitoring – Administrators can oversee active connections and revoke access if necessary.

Installation & Usage

Download and install the OwlGuard desktop application.

Open the application and log in using your credentials.

Allow the application to conduct a security compliance check.

If approved, connect securely via OpenVPN.

Maintain compliance to ensure uninterrupted access.

Security Measures

Implements Zero Trust principles to prevent unauthorized access.

Uses EasyRSA for certificate-based authentication and encryption.

Requires device compliance before establishing a connection.

Enables real-time session monitoring and access revocation.

License

OwlGuard is developed by UPES as part of a secure remote access project. The application is subject to specific licensing terms and restrictions

<img src="https://raw.githubusercontent.com/gr3edydevel0per/ZTNA/refs/heads/main/Remote%20Access%20Application/Assets/images/login.png">


<img src="https://raw.githubusercontent.com/gr3edydevel0per/ZTNA/refs/heads/main/Remote%20Access%20Application/Assets/images/landing.jpg">

<img src="https://raw.githubusercontent.com/gr3edydevel0per/ZTNA/refs/heads/main/Remote%20Access%20Application/Assets/images/con.png">
