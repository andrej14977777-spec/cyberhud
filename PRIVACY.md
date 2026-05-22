Privacy Policy for CyberHUD
Effective Date: February 2026
Package Name: com.zhivoglas.cyberhud

1. Introduction
CyberHUD ("we", "our", or "the App") is developed by Zhivoglas ("Developer"). This Privacy Policy explains how information is processed when using the App. By installing or using CyberHUD, you acknowledge and agree to the practices described in this Policy.

2. Nature of the Application
CyberHUD is a locally operating diagnostic utility, network firewall, and remote management tool. 
- Operates Offline-First: Does not collect data to developer-controlled servers or cloud platforms.
- No Centralized Accounts: Does not maintain user accounts.
- User Controlled: All connections (PC control, blocking apps) are initiated and managed by the user.
- Transparent: Does not operate in "stealth" mode; active services are visible via persistent notifications.

3. Legal Basis for Processing
Data processing is based on User Consent (explicitly granted permissions like VPN and Package Visibility) and Legitimate Interest (providing diagnostic and firewall functionality).

4. Categories of Data Processed (Local Only)
4.1 System & Device Information
The App displays hardware specifications (CPU, GPU, RAM) and OS version. This data is used strictly for local diagnostic display and is never transmitted externally.

4.2 Installed Applications (Package Visibility)
The App requests the QUERY_ALL_PACKAGES permission to allow users to select specific applications for internet blocking (Firewall) and to view per-app process statistics. This list is processed locally in volatile memory.

4.3 VpnService & Firewall Functionality
To enforce user-defined internet blocking rules, CyberHUD utilizes the Android VpnService API.
- Local Routing: It creates a local loopback interface. No traffic is routed to remote VPN servers.
- No Data Logging: The App does not inspect, log, or collect the content of network traffic.
- Purpose: Exclusively for the local firewall/SOCKS5 server functionality.

4.4 Local Network & Wi-Fi Connectivity
The App connects to the CyberHUD Desktop client via the local Wi-Fi/LAN network.
- Peer-to-Peer: Data is transmitted directly between the Android device and the PC using secure protocols (SSH/TLS).
- No Cloud Intermediaries: No data is sent to external clouds or third-party servers.

4.5 Screen Capture & Media Control
Initiated only by the user for remote management. A persistent notification is displayed when active. Streams are strictly local.

5. Data Storage & Retention
No Cloud Storage: The Developer does not store user data. 
Temporary Files: Local diagnostic logs are deleted upon session termination.

6. No Sale or Sharing of Data
We do not sell, share, or monetize any data. We do not use third-party ads or tracking SDKs (no Google Analytics, no Firebase Analytics).

7. Security
All local Wi-Fi communication uses industry-standard encryption. Security depends on the user's local network configuration.

8. Contact Information
Developer: Zhivoglas
Email: andrej14977777@gmail.com
