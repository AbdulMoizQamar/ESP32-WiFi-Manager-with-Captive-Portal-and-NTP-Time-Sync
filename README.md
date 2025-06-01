# ESP32-WiFi-Manager-with-Captive-Portal-and-NTP-Time-Sync
This project allows the ESP32 to automatically connect to previously saved WiFi credentials stored in EEPROM. If the connection fails (e.g., network unavailable or credentials changed), the ESP32 sets up a WiFi Access Point (AP) with a captive portal where users can scan available networks and enter new WiFi credentials through a web interface.

📄 Project Description
This project allows the ESP32 to automatically connect to previously saved WiFi credentials stored in EEPROM. If the connection fails (e.g., network unavailable or credentials changed), the ESP32 sets up a WiFi Access Point (AP) with a captive portal where users can scan available networks and enter new WiFi credentials through a web interface.

Key features include:
📶 Auto-connect to saved WiFi credentials
🌐 Fallback to SoftAP mode with a captive portal for new credentials
💾 EEPROM read/write for storing WiFi credentials
🌍 NTP time synchronization (from pool.ntp.org)
🧠 EEPROM-clearing and device auto-restart after new credentials are saved
🔐 Option to secure SoftAP with a password (for enhanced security)
🕒 Real-time clock print from NTP server in 12-hour format

💡 Ideal Use Cases
Headless IoT devices that need WiFi setup without hardcoding SSID/password
Prototypes requiring quick and user-friendly WiFi provisioning
Projects that need accurate local time without an RTC module
