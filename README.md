## **Relay Control with Arduino**

### **Overview**

This project demonstrates how to control a multi-channel relay module using an Arduino. Relays act as electrically operated switches that allow low-voltage digital outputs from the Arduino to control high-voltage devices such as lights, fans, and other appliances safely.

---

### **Features**

* Controls up to **four relays** using digital output pins.
* Each relay can be **activated and deactivated automatically** in a timed sequence.
* Demonstrates basic **digital output control** using Arduino.

---

### **Components Required**

* Arduino board (e.g., **Arduino Uno**)
* **4-channel relay module**
* Jumper wires
* Breadboard (optional, for clean connections)

---

### **Circuit Connections**

| Relay Module Pin | Arduino Pin | Description                       |
| ---------------- | ----------- | --------------------------------- |
| IN1              | 2           | Controls relay 1                  |
| IN2              | 3           | Controls relay 2                  |
| IN3              | 4           | Controls relay 3                  |
| IN4              | 5           | Controls relay 4                  |
| VCC              | 5V          | Power supply for the relay module |
| GND              | GND         | Common ground                     |

---

### **Setup Instructions**

#### **1. Hardware Setup**

* Connect **IN1–IN4** of the relay module to **digital pins 2–5** on the Arduino.
* Connect **VCC** of the relay module to the Arduino’s **5V** pin.
* Connect **GND** of the relay module to the Arduino’s **GND** pin.

#### **2. Software Setup**

1. Open the **Arduino IDE**.
2. Create a new sketch and **paste the provided code**.
3. Connect your Arduino board to your computer via **USB**.
4. Select the correct **board** and **port** in the IDE.
5. Click **Upload** to transfer the sketch to your Arduino.

---

### **Operation**

Once the sketch is uploaded:

* The Arduino will sequentially turn **each relay ON for 1 second**, then **OFF for 1 second**.
* This pattern repeats continuously, demonstrating relay switching behavior.

---

### **Applications**

* Home automation projects
* Device power scheduling
* Industrial control systems
* Load management demonstrations

---

### **Safety Note**

If connecting high-voltage devices:

* **Ensure proper insulation and wiring safety.**
* Always **disconnect power** when modifying the circuit.
* Use relays rated for the voltage and current of your devices.
