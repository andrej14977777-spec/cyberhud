Privacy Policy for CyberHUD
Effective Date: February 2026
1. Introduction
CyberHUD ("we", "our", or "the App") is developed by Zhivoglas ("Developer"). This Privacy Policy explains how information is processed when using the App.
By installing or using CyberHUD, you acknowledge and agree to the practices described in this Policy.
2. Nature of the Application
CyberHUD is a locally operating diagnostic utility, network firewall, and remote management tool.
The App:
Operates Offline-First: Does not collect data to developer-controlled servers or cloud platforms.
No Centralized Accounts: Does not maintain user accounts.
User Controlled: All connections (PC control, blocking apps) are initiated and managed by the user.
Transparent: Does not operate in "stealth" mode; active services are visible via notifications.
3. Legal Basis for Processing
Data processing is based on:
User Consent: Explicitly granted permissions (e.g., VPN usage, file access).
Legitimate Interest: Providing the diagnostic and firewall functionality requested by the user.
4. Categories of Data Processed
All data is processed locally on the user’s device.
4.1 System & Device Information
The App collects the following data strictly for local diagnostic display:
Hardware specifications (CPU, GPU, RAM, Motherboard).
Operating System version and API level.
Device Identifiers (used locally to distinguish devices).
Purpose: To display system health and performance statistics to the user.
4.2 Installed Applications (Package Visibility)
The App requests permission to access the list of installed applications (QUERY_ALL_PACKAGES).
Purpose: To allow the user to select specific applications for internet blocking (Firewall) and to view process statistics.
Storage: The list of apps is processed in volatile memory and is never transmitted to the Developer.
4.3 Use of VpnService (Firewall Functionality)
To strictly block internet access for applications selected by the user, CyberHUD utilizes the Android VpnService API.
Local Routing: The VpnService creates a local loopback interface.
No Remote Server: User traffic is NOT routed to any remote VPN server, proxy, or third-party collector. Traffic meant for blocked apps is dropped locally on the device.
No Data Logging: The App does not inspect, log, or save the content of your network traffic (packet data).
Purpose: Exclusively to enforce the user's firewall rules.
4.4 Local Network & PC Control
The App may connect to a PC application (CyberHUD Desktop) over the local network (Wi-Fi/LAN).
Protocols: The App uses secure local protocols (based on SSH/Netty libraries) to establish a direct connection.
Data: Local IP addresses and device names are used to pair devices.
Authorization: Connections require user authentication (e.g., pairing via local network). No data is sent to external clouds.
4.5 Screen Capture & Media Control
The App may use OS capabilities to capture screen content or control media only when initiated by the user for remote management.
Visibility: A persistent notification is displayed when these features are active.
No Cloud Storage: Streams are transmitted directly to the paired local device and are not saved on Developer servers.
5. Data Storage & Retention
No Cloud Storage: The Developer does not store user data.
Temporary Files: Diagnostic logs or temporary files are stored locally and deleted upon session termination or at the user's discretion.
6. No Sale or Sharing of Data
The Developer does not:
Sell, share, or monetize personal data.
Integrate third-party advertising networks.
Use third-party tracking SDKs (e.g., Google Analytics, Facebook Pixel).
Collect browsing history via the Firewall feature.
7. Security
CyberHUD operates within the user’s local environment.
Encryption: Local communication between the App and the PC uses industry-standard encryption (SSH/TLS) provided by the underlying libraries.
User Responsibility: Security depends on the user's local network configuration (Wi-Fi password, firewall) and device integrity.
8. Children’s Privacy
The App is not directed to individuals under the age of 13. We do not knowingly collect data from minors.
9. Changes to This Policy
The Developer reserves the right to update this Policy. Updates will be distributed through the App’s update mechanism on the app store. Continued use implies acceptance.
10. Contact Information
For privacy-related inquiries or to report issues, please contact the Developer:
Email: andrej14977777@gmail.com
Developer: Zhivoglas
