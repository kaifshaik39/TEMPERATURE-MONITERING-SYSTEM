# TEMPERATURE-MONITERING-SYSTEM

TASK 1 (EMBEDDED SYSTEMS INTERNSHIP)

COMPANY: CODTECH IT SOLUTIONS

NAME: SHAIK MOHAMMED KAIF

INTERN ID: CITS0D758

DOMAIN: EMBEDDED SYSTEMS

BATCH DURATION: JUNE 17th,2025 to AUGUST 2ND,2025 (6 Weeks)

MENTOR NAME: Neela Santhosh Kumar

## 📌 Description

The **Temperature Monitoring System** is a beginner-friendly embedded systems project that simulates real-time ambient temperature monitoring using **Arduino** and an **LM35 temperature sensor**. Built and tested in **Tinkercad**, this project demonstrates how to read analog temperature data and display it on a **16x2 I2C LCD**.

This type of system is widely used in **smart homes**, **weather monitoring**, and **industrial automation**, where consistent and accurate temperature tracking is required.

---

## ⚙️ How It Works

- The **LM35 sensor** outputs an analog voltage (10 mV/°C) proportional to the temperature.
- This voltage is read by the Arduino’s analog pin **A0** and converted to temperature using the formula


- The calculated temperature is then displayed on a **16x2 LCD** using an **I2C module**, which connects to Arduino pins **A4 (SDA)** and **A5 (SCL)**.
- In the Tinkercad simulation, the sensor’s analog input was manually varied to test system behavior, since physical temperature changes can't be simulated.

---

## 🧰 Components Used

- Arduino Uno (Simulated)
- LM35 Temperature Sensor
- 16x2 LCD Display with I2C Module
- Jumper Wires & Breadboard (Virtual)
- Tinkercad Circuit Simulator

---

## 🧠 Concepts Demonstrated

- Analog Sensor Interfacing
- Analog-to-Digital Conversion (ADC)
- Real-Time Data Processing
- I2C Communication for Display
- LCD Display Interfacing
- Tinkercad Simulation & Testing

---

## 💡 Future Enhancements

- Add buzzer or fan to trigger above temperature threshold
- Wireless data transmission using ESP32/ESP8266
- Temperature logging to SD card or cloud platform
- Web-based temperature dashboard

---

## Circuit Diagram

<img width="1683" height="648" alt="Circuit diagram of  temp monitering sys" src="https://github.com/user-attachments/assets/f63175b7-3a6f-46a7-b421-23e302425bbd" />

## Output 

<img width="1409" height="789" alt="output of  temp monitering sys" src="https://github.com/user-attachments/assets/1ccd6cd1-09c3-4d01-85de-3917744c378a" />



## ✅ Conclusion

This project effectively demonstrates how to build a basic temperature monitoring system using Arduino and an LM35 sensor. It introduces core concepts such as analog reading, temperature calculation, and display interfacing. Simulating the project in Tinkercad allows for easy experimentation without physical components.

Ideal for students and beginners, the project serves as a foundation for more advanced temperature-based systems used in IoT, automation, and real-time monitoring applications.

---

