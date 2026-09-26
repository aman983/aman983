<img src="Assets/goku_sunset.gif" alt="My Banner" align="right" width="350"/>

### Hi there 👋

I'm Aman, an embedded software engineer focused on building **secure connected devices**.

The systems I work on are small, with limited compute and power. 
</br>More and more of them sit inside everyday products, and many of those products do things people rely on. When they're insecure, an attacker can turn a convenience into a real risk. I want to build devices that hold up against that.

I'm currently doing my **MSc in Embedded Systems at Eindhoven University of Technology (TU/e)**, where I work on both sides of the problem:
- **Breaking things:** attacking low-power wireless networks, such as manipulating IEEE 802.15.4 channel access.
- **Building things:** a secure boot + OTA update chain on the nRF5340, and a low-power BLE/UWB ranging system on Zephyr *(both in progress)*

🎯 **Looking for:** a graduation project (*afstudeeropdracht*) in IoT, embedded security or secure firmware, starting Feb 2027.

📫 **Reach me:** amanshaikhw@gmail.com

### 🧰 Tech Stack
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Zephyr RTOS](https://img.shields.io/badge/Zephyr-RTOS-purple?style=flat&logo=zephyr&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)


### 🚧 Currently Building
- [🔐 Secure Boot + OTA Updates](https://github.com/aman983/Secure-Boot-and-OTA-on-nrf5340) – MCUboot with custom signing keys, rollback protection, and verified firmware updates over Wi-Fi with automatic recovery from failed or interrupted updates. Target: nRF7002 DK.
- [📡 BLE-Triggered UWB Ranging](https://github.com/aman983/UWB-Smart-Audio-Follow) *(in progress)* – Hybrid proximity system on Qorvo DWM3001CDK with Zephyr RTOS. BLE RSSI filtering detects when a tag is nearby, and UWB wakes up only for precise time-of-flight ranging, so the system can trade energy against latency compared with continuous UWB.
  
### 📌 Featured Projects
- [🛡️ MAC-Layer Backoff Manipulation Attack & Defence](https://github.com/aman983/CSMA-Backoff-Manuplation-Attack-) – Selfish-backoff attack on IEEE 802.15.4 CSMA/CA in Contiki-NG. The attack cut a legitimate node's packet delivery ratio from 92% to 46% and raised collisions from 2 to 48 per 100 transmissions. It was paired with an EWMA-based detector that blacklists the attacker.
- [🎯 IMU Gesture Server on ESP8266](https://github.com/aman983/ESP-IMU-Gesture-Server) – FreeRTOS firmware with custom I²C drivers for the MPU-6050 and HMC5883L. A producer/consumer task pipeline runs a complementary filter for pitch and roll, detects tilt, nod, and shake gestures, and serves the result over an HTTP endpoint.
- [🔧 Compact Wireless Relay Module](https://github.com/aman983/ESP-01S_Relay_Module) – Custom PCB for a 2-relay module with Wi-Fi (ESP-01S).

