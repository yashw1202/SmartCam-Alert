# Smart Cam Alert

**Smart Cam Alert** is an intelligent motion detection system built using the **ESP32-CAM module** and an **IR sensor**. The system detects motion via the IR sensor and sends an alert to a Telegram bot with an ip address link to video stream from the ESP32-CAM. The system is designed for efficient home surveillance and monitoring, with real-time alerts and easy access to live video footage.

## Features

- **Motion Detection:** Detects motion using an IR sensor.
- **Telegram Alerts:** Sends a Telegram message with a link to the live stream when motion is detected.
- **Live Video Streaming:** Streams video from the ESP32-CAM when motion is detected.
- **Low Power Consumption:** Efficient design using the ESP32-CAM for energy savings.
- **Wireless Operation:** Connects to Wi-Fi for seamless monitoring and notifications.

## Components Used

- **ESP32-CAM Module**
- **IR Sensor (PIR or similar)**
- **Wi-Fi Network** for remote access and notifications
- **Telegram Bot API** for sending alerts
- **Power Supply** (5V for ESP32-CAM)

## How It Works

1. **Motion Detection:** The system continuously monitors the area through the IR sensor for any motion.
2. **Image Capture or Video Streaming:** Upon detecting motion, the ESP32-CAM either captures an image or starts streaming video, depending on the configuration.
3. **Telegram Alerts:** The system sends a message to a configured Telegram chat with a link to the live stream or captured image.
4. **Real-Time Monitoring:** The user can click the link in the Telegram message to stream live video from the ESP32-CAM.

## Key Features

- **Real-Time Notifications:** As soon as motion is detected, the system sends an instant notification to the configured Telegram bot.
- **Instant Access to Footage:** The Telegram message includes a direct link to view the video stream from the camera.
- **Customizable Settings:** Adjust detection thresholds, camera resolution, and other parameters as needed for your specific use case.

## Usage

Once set up, the system will automatically:

- Monitor for motion in the designated area using the IR sensor.
- Trigger an alert when motion is detected, sending a message to the Telegram bot with a stream link or an image.
- Provide live video streaming accessible through the provided Telegram link.

## Contributing Members
 **Yash Wathrey**
 **Aman Kushwaha, Amit Kanojia , Anuj Sahu**
- Feel free to fork the repository, submit issues, or open pull requests. Contributions are always welcome to improve the project.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

 
