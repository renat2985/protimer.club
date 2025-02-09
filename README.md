[🇷🇺 Русская версия документации здесь](https://github.com/renat2985/protimer.club/blob/main/README_RU.md)

#  Your Personal Performance Archive!

**ProTimer.club** is a modern solution for athletes, offering precise time measurement, result recording, and analysis to enhance training efficiency. Our devices are suitable for various sports and competitions, providing convenience, accuracy, and cloud integration.

You can log in with a demo profile and explore all the website features right now: [https://protimer.club/login#demo](https://protimer.club/login#demo)

    Email: demo@protimer.club
    Password: demo 

Here’s a link showcasing how you can share your page and display your results to anyone, even those who are not registered on the site: https://protimer.club/share/MzlLRDlaT1hnMTNaeEVZbnFSTTNHUT09

<p align="center">
<a href="https://www.youtube.com/watch?v=7RWEwh4FOdk&list=PL6NJTNxbvy-KKb5Vj-JgzeaAFMx-zqKtX"><img src="https://github.com/renat2985/protimer.club/blob/main/doc/intro.png" height="400px"><img src="https://protimer.club/assets/img/photo/gg-07670-min.png" height="400px"></a>
</p>

## Key Features

  - **Precise time measurement:** Accuracy up to 0.003 seconds.
  - **Ease of use:** Simple system setup accessible to everyone.
  - **Cloud integration:** Export data to ProTimer.club for storing and analyzing training history.
  - **Social network:** Share achievements and follow the progress of your friends.
  - **Versatility:** Support for various modes and features for team and individual training.

_Learn more about the features [here](https://protimer.club/en/doc)._

---

## How It Works

### Master Point — The main module of the system that manages the ProTimer network.

1. **Power On and Connect:**

    - Turn on the Master Point; it will create a Wi-Fi network "ProTimer.club".
    - Connect to this network using your smartphone, tablet, or laptop.

        <img src="https://github.com/renat2985/protimer.club/blob/main/doc/wifi.png" height="300px">

2. **Access the Control Interface:**

    - Open a browser and enter the address `http://192.168.4.1` to access the web interface.
    - Use the interface to configure modes, control the timer, and export data.

        <img src="https://github.com/renat2985/protimer.club/blob/main/doc/AP.png" height="400px"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/AP3.png" height="400px">

3. **Connecting to the Router:**

    - During the first setup, the device will ask for your home Wi-Fi network name and password. This is required for automatic data export to the cloud.
    - Once configured, the device will automatically connect to the specified router every time it is powered on and upload your data to the ProTimer.club cloud.
    - This means that after your training session, you just need to turn on the device for a few seconds — it will connect to Wi-Fi and export all your results automatically. Simple and convenient!

    **Device Display:**

    <img src="https://protimer.club/assets/img/doc14.png" height="100px"> <img src="https://protimer.club/assets/img/doc13.png" height="100px"> <img src="https://protimer.club/assets/img/doc25.png" height="100px"> <img src="https://protimer.club/assets/img/doc15.png" height="100px">

    _Read more details [here](https://protimer.club/en/doc#doc5)._


### Point PRO — An additional module that serves as a start, intermediate, or finish point.

1. **Operating Modes:**

    - **Start:** Starts the timer when the beam between the sensor and the reflector is crossed.
    - **Intermediate:** Captures split times at intermediate points.
    - **Finish:** Stops the timer when the beam is crossed.

2. **Connection to Master Point:**

    - Point PRO automatically synchronizes with Master Point within a range of up to 250 meters.
    - Use the built-in Point PRO display to check the connection and select the operating mode.

3. **Point PRO Features:**

    - Equipped with a display for real-time status updates.
    - Supports multiple channels for simultaneous use of multiple sets on one track.
    - High measurement accuracy of up to 0.003 seconds.

    **Device Display:**

    <img src="https://protimer.club/assets/img/doc23.png" height="100px"> <img src="https://protimer.club/assets/img/doc22.png" height="100px"> <img src="https://protimer.club/assets/img/doc24.png" height="100px">

    _Read more details [here](https://protimer.club/en/doc#doc5)._

#### ⚠️ Point PRO and Master Point work together, giving athletes and coaches full control over training sessions with precise results.

---

## Contact

You can build the device yourself or ask us to do it for you. To order a ready-made device, contact us via [Telegram](https://t.me/ESPiotDevice), [WhatsApp](https://chat.whatsapp.com/H7IpCrilF00H3wGbANnA1i), [Skype](https://skype:renat2985?chat), or [Discord](https://discord.gg/3986vwEdf5).

Ready-made equipment kits with customization options and additional modules are also available on our website.

---

## Connection Diagram

You can build the device using NodeMCU ESP8266 or Wemos ESP8266. This diagram applies to both the Master and Point (PRO) devices. Choose the appropriate software link below for installation.

On the NodeMCU board, the Flash button performs the same functions as the external button connected to D3. If needed, you can use it instead of the external button.

## Pinout Configuration

| **Pin** | **GPIO** | **Function**              |
|---------|----------|---------------------------|
| **D1**  | GPIO5    | SCK (Display)             |
| **D2**  | GPIO4    | SDA (Display)             |
| **RX**  | GPIO3    | IR or LASER Sensor        |
| **D3**  | GPIO0    | Button                    |
| **D7**  | GPIO13   | Active Buzzer (optional)  |
| **D6**  | GPIO12   | Passive Buzzer (optional) |
| **D0**  | GPIO16   | [GATE Relay](https://github.com/renat2985/protimer.club/discussions/6)                 |

### [E3Z-R61](https://www.aliexpress.com/item/1005004123351251.html) (max 2-3m "gates", IR sensor)

<img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic.png" height="200px" alt="Connection Diagram"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic2.png" height="200px" alt="Connection Diagram 2">

### [E3Z-LAS-R8, NPN NO](https://www.aliexpress.com/item/1005005879848648.html) (max 7-8m "gates", Laser sensor) 

<img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic3.png" height="200px" alt="Connection Diagram 3"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic4.png" height="200px" alt="Connection Diagram 4">

## STL (STL Folder)

All these parts can be found and printed from the stl folder.

<img src="https://github.com/renat2985/protimer.club/blob/main/stl/box-big.png" height="200px" alt="Box big"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/box-small.png" height="200px" alt="Box small"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/сover-microUSB.png" height="200px" alt="Cover MicroUSB"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/сover-сable.png" height="200px" alt="Cover cable"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror3.png" height="200px" alt="Reflector Holder 3"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror4.png" height="200px" alt="Reflector Holder 4"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror5.png" height="200px" alt="Reflector Holder 5">


<img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0487.jpg" height="200px" alt="Photo 1">
<img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0488.jpg" height="200px" alt="Photo 2"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0489.jpg" height="200px" alt="Photo 3">

## From AliExpress.com

[E3Z-R61](https://www.aliexpress.com/item/1005004123351251.html) (2-3m, IR sensor) or [E3Z-LAS-R8, NPN NO](https://www.aliexpress.com/item/1005005879848648.html) (7-8m, Laser sensor) 

[Reflector TD-05](https://www.aliexpress.com/item/32990489226.html) (Better) or [Reflector TD-08](https://www.aliexpress.com/item/1005003584568763.html) (Worse)

[I2C SSD1315 128x64](https://www.aliexpress.com/item/1005004118377699.html)

[Wemos MINI ESP07](https://www.aliexpress.com/item/1005007081723288.html) (Suitable for STL case) or [NodeMCU ESP8266](https://www.aliexpress.com/item/1005004893349830.html) 

[Push Button Switch](https://www.aliexpress.com/item/1005004159746274.html)

[Passive Buzzer Shield for WEMOS (D6 gpio)](https://www.aliexpress.com/item/1005007463046770.html) or [Active Buzzer Module for Arduino (D7 gpio)](https://www.aliexpress.com/item/1005005528181661.html)

[Power Bank for 18650 Battery](https://www.aliexpress.com/item/1005002367815544.html)

[Mini Flexible Sponge Octopus Tripod](https://www.aliexpress.com/item/1005004177317958.html)

Other components for E3Z-LAS-R8, NPN NO

[Step-Down Board Mini 360](https://www.aliexpress.com/item/1005005995617482.html)

[Mini DC Boost Converter Board](https://www.aliexpress.com/item/1005007013856492.html)

[1N4728A 3.3V Zener Diode](https://www.aliexpress.com/item/4000297831644.html)

---

### 🚀 **Web Installer (Recommended)**  
Easily set up your device using the web installer. Choose the appropriate version and follow the instructions.

- **[Master Installer](https://renat2985.github.io/protimer.club/):** The main device that records the time.  
- **[Point Installer](https://renat2985.github.io/protimer.club/point.html):** An additional device that marks the finish line, checkpoints, or the start.  

---

## :battery: Donation

If you like this project, you can support us by buying a cup of coffee! ☕  

<img src="https://github.com/renat2985/renat2985/raw/main/donate/donate.png" width="100%" alt="Donate Image">

- **PayPal:** [https://www.paypal.me/RKevrels](https://www.paypal.me/RKevrels/5)