# Power-Logger
Have you ever been involved in a project that required measuring the precise current consumption of a battery or solar-powered prototype? One of the most convenient methods for this is utilizing INA219 or INA3221 modules, both of which are affordable options. However, these modules can sometimes have flaws, necessitating modifications to achieve proper functionality.

As a response to these challenges, I opted to develop my own comprehensive power logger. This DIY solution not only overcomes the limitations of commercial products but also offers a range of enhanced features. Furthermore, the process of creating this power logger proves to be an enjoyable and straightforward endeavor.

## Details
### The hardware boasts several noteworthy features:

- It offers the capability to monitor three channels simultaneously. Notably, one of these channels is equipped with a "USB C to USB A" power monitor, making it suitable for tracking the charging process of USB devices.

- Powered by the ESP32 C3 Mini, the device ensures convenient programming and seamless interfacing.

- For programming and power, a USB C interface is incorporated.

- The inclusion of Micro SD card support facilitates the storage of logging data. This functionality proves particularly beneficial for projects centered around solar power monitoring.

- To accommodate battery-powered scenarios, the device is designed to work harmoniously with a 3.7V battery. This setup includes essential components for safe operation, encompassing features such as overcurrent protection, over/undercharge safeguarding, and a 3.3V low dropout regulator (LDO).

- The device features a TFT display and responsive buttons, forming a programmable interface. This aspect eliminates the necessity for a serial connection to a laptop, enabling standalone usage for value readings.

### In terms of software, the device's potential features include:

- A user-friendly menu system that streamlines tasks like enabling/disabling channels and configuring sampling rates.

- The ability to pair two channels for assessing device efficiency. For instance, evaluating input and output values of a 5V boost converter.

- Accurate recording of date, time, and values onto a microSD card for subsequent review.

- Monitoring of the device's own battery level, accompanied by low-battery alerts, potentially communicated through methods like email or MQTT notifications.

- Real-time tracking of voltage and current across any of the three channels, with the capacity to issue notifications when predefined thresholds are exceeded.

- Displaying historical data in the form of bar graphs, covering time intervals such as the past 1, 5, and 15 minutes.
