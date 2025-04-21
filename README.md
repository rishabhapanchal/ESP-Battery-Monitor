# 🔋 LiPo Battery Monitor using ESP8266

This is a smart battery percentage and voltage monitor using ESP8266, built for LiPo cells with a charging module and overcharge safety.

It displays:
- Battery Voltage
- Battery Percentage
- Charging Status (optional)
- Data on Arduino IDE serial monitor

## 📸 Demo
![Setup]![image](![Screenshot 2025-04-22 005341](https://github.com/user-attachments/assets/543a5777-33f7-4486-aaf6-e0eabead9374)
)
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
![Circuit]![image](https://github.com/user-attachments/assets/00d4263f-a43c-4f18-8867-8d10b67f0760)


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
