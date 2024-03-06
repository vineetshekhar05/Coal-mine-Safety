# Autometed Coal mine Saftey monetering and alerting system using IOT

Mine Safety Monitoring and Alerting System is an innovative system designed for mining environments, which uses IoT technology to ensure safety and rapid response to potential threats.
This autonomous device is equipped with sensors and communication modules that continuously monitor crucial parameters like temperature, gas and smoke levels. 
It operates independently, and when finding hazardous conditions sending alerts to the control centers. 
This proactive approach helps in safety of miners in the mining fields with pre-warnings and alert messages to take safety precautions within times.

<p float="left">
  <img src="https://brandslogos.com/wp-content/uploads/images/large/arduino-logo-1.png" width="70" height="70" style="margin-left: 10px;">
</p>

# Overview

IOT Based Coal Mine Safety Monitoring project consists of two hardware modules, one transmitter, and one receiver. The main controller in both modules is an Arduino board.
Transmitter module: It is installed inside the coal mine. The transmitter module contains the smoke sensor, temperature sensor, and methane sensor. The transmitter module also has an LCD. All the sensor data is displayed on the LCD display by Arduino. The RF transmitter present on the transmitter module sends the sensor data to the receiver module.
Receiver module: It has an Arduino controller, LCD display, and an RF receiver. The RF receiver receives the sensor values from the RF transmitter on the transmitter module. The received sensor values are displayed on the LCD screen. The Arduino also sends the sensor data to the remote IOT server using the WiFi module every two minutes. If any of the sensor values exceeds a particular threshold level, the buzzer is turned on to notify the concerned personnel.
The remote server has an IOT platform installed on it which displays the relevant data using the GUI which helps the users in monitoring and system control.

**Technologies, Software, and Main Hardware Components Used**
# Technology used to collect and shows real time data sending by Aurdino - ThingSpeak
**Arduino UNO Microcontroller**

The Arduino UNO R3 microcontroller, equipped with 14 digital pins, PWM outputs, and six analog inputs, serves as the project's control unit. It features a 16 MHz crystal oscillator, USB port, power jack, ICSP header, and a reset button.

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgHCfrINVkq9FHGd516DJyBRB5jPHe_Zf-_kiwrNotW_RBjv-jvSQ_C49Dih98iUtHZDkmwGLxhLbUcMX9mRWcteG2P943QoTO2QhTuQ29zXZyY2zYzjtGNg7uxtlbJnXPToBOWArDhGiVw1IpqGakKiFrK5cqCW7th0pr6x9Fy2tiC_xKHiKeVm-R-J1v3/s1011/Arduino%20uno%20board.png" width="506" height="278">

**MQ135 Air Quality Gas Sensor Module**

The project incorporates the MQ-2 digital sensor to measure air quality in parts per million (PPM). This sensor detects various gases in the atmosphere, signaling when gas levels exceed predefined thresholds.

<img src="https://cdn.shopify.com/s/files/1/0527/2692/3444/files/MQ135_-_Air_Quality_Control_Gas_Sensor_Module.jpg?v=1631792819" width="629" height="287">

**GSM Module**

In coal mining safety, GSM (Global System for Mobile communication) modules are employed as vital communication tools.
These modules enable real-time transmission of safety alerts, data, and status updates from underground mines to surface control centers or control center. 

<img src="https://robosynckits.in/wp-content/uploads/2020/12/8A.jpg" width="440" height="285">

**Temerature Sensor**

The BMP180 high-precision sensor measures barometric pressure digitally, accounting for temperature variations. It is utilized to monitor pressure in underground tunnels.

<img src="https://www.iqsdirectory.com/articles/thermocouple/temperature-sensors/digital-temperature-sensor.jpg" width="566" height="221">

**16x4 LCD Display**

The 16x4 LCD display is employed to showcase outputs from oxygen, carbon dioxide, and temperature sensors. It is chosen for its programmability, ability to display custom characters, and cost-effectiveness.

<img src="https://m.media-amazon.com/images/I/41iRb1AmRsL._AC_UF1000,1000_QL80_.jpg" width="500" height="350">

**Power Source**

To ensure continuous operation underground, rechargeable batteries and power banks with a capacity of 10,000mAh and 5V are used. The system can run for approximately 27 hours, providing an alternative power source in case of a power failure.
