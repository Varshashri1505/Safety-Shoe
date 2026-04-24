# Safety-Shoe
Hybrid Piezoelectric and solar Powered AI-Enabled Smart Safety Shoe for Accident Detection and Emergency SOS

👟 Smart Safety Shoe with Energy Harvesting

📌 Overview
The Smart Safety Shoe is an innovative wearable system designed to enhance personal safety by integrating fall detection, real-time location tracking, emergency alert mechanisms, and energy harvesting technologies. This project combines embedded systems with communication modules to provide a reliable and efficient safety solution.

🎯 Objectives

To detect falls automatically using motion sensors

To send emergency alerts with real-time location

To provide manual SOS functionality

To generate energy using piezoelectric sensors and solar panel

To develop a compact and wearable safety device

⚙️ Components Used

ESP32 Microcontroller

MPU6050 (Accelerometer + Gyroscope)

GPS Module (NEO-6M)

GSM Module (SIM800L)

Piezoelectric Sensor

Solar Panel

Li-ion Battery

Push Button (SOS)

🔄 Working Principle

The MPU6050 sensor continuously monitors user movement

If a fall is detected:

ESP32 processes the data

GPS module retrieves location

GSM module sends SMS alert with location

User can manually trigger SOS using a button

Piezoelectric sensor generates energy from walking

Solar panel provides additional charging support

💡 Features

Automatic fall detection

Manual SOS alert system

Real-time GPS tracking

GSM-based SMS communication

Hybrid energy system (Piezo + Solar)

Compact wearable design

🚧 Limitations

Low energy output from piezoelectric sensor

Dependence on GSM network availability

GPS accuracy may reduce indoors

Threshold-based detection (no AI yet)

🔮 Future Enhancements

Integration of AI/ML for accurate fall detection

Mobile application for real-time monitoring

IoT-based cloud connectivity

Improved battery and energy efficiency

Health monitoring features (heart rate, steps)

💰 Estimated Budget

Approximate total cost: ₹2000 – ₹2500

🧠 Technologies Used

Embedded Systems

Arduino IDE (C/C++)

Sensor Integration

Wireless Communication (GSM, GPS)

Energy Harvesting

📂 Project Structure

/code        → Arduino code (ESP32)
/docs        → Project documentation
/images      → Diagrams & prototype images

🚀 How to Run

Upload the code to ESP32 using Arduino IDE

Connect all hardware components properly

Insert SIM card into GSM module

Power the system

Monitor output via Serial Monitor

👩‍💻 Author

Varshashri Nagapuri

📜 License

This project is for academic purposes. Do not reuse without permission.
