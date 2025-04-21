# 🔋 LiPo Battery Monitor using ESP8266

This is a smart battery percentage and voltage monitor using ESP8266, built for LiPo cells with a charging module and overcharge safety.

It displays:
- Battery Voltage
- Battery Percentage
- Charging Status (optional)
- Data on Arduino IDE serial monitor

## 📸 Demo
[image](![image](https://github.com/user-attachments/assets/573f3db6-b367-4393-87ef-bcdf778d603c)
)


## 🔧 Hardware Used
- ESP8266 (NodeMCU/ESP-12E)
- TP4056 Charging Module (with protection)
- LiPo Battery (3.7V)
- Voltage Divider Circuit
- Optional OLED Display (future update)

## ⚙️ Features
- Overcharge protection
- Safe voltage scaling
- Real-time battery monitoring
- Modular for IoT expansion

## 🛠️ Circuit Diagram
[image](![Screenshot 2025-04-22 005341](https://github.com/user-attachments/assets/7174fcb3-48d1-4c62-9ba3-7d128654bf5d)
)


## 🚀 Getting Started

1. Clone this repo
2. Open `ESP8266_LiPo_Monitor.ino` in Arduino IDE
3. Connect ESP8266, upload code
4. Monitor battery status on Serial Monitor

## 🧠 Future Plans
- Firebase/ThingSpeak sync
- Mobile app dashboard
- Multiple cell monitoring
- Temp monitoring

## 📄 License
MIT – free to use, modify, share
