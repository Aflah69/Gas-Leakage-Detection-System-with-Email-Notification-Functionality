Gas-Leakage-Detection-System-With-Email-Notification-Functionality

Overview:

Combustible gas detection is crucial in various fields to prevent environmental hazards and ensure safety. This project introduces an Internet of Things (IoT) based system designed for the detection and measurement of combustible gases, utilizing the MQ6 gas sensor. The system is engineered to operate effectively in diverse atmospheric conditions, thereby mitigating potential environmental and safety risks associated with gas leakages.


Features:

    MQ6 Gas Sensor: Detects combustible gases in the environment.
    ESP32 Microcontroller: Provides IoT connectivity and data processing capabilities.
    Servo Motor: Regulates gas flow and shuts off regulators upon detection of leaks.
    Buzzer: Raises audible alarms to alert nearby individuals.
    SMTP Integration: Sends email notifications to designated personnel upon gas detection.
    Continuous Monitoring: Facilitates real-time detection and response to gas leakages.
    Enhanced Safety Measures: Prevents accidents and reduces environmental impact by prompt action.


Circuit Components:

![Circuit Diagram](https://github.com/user-attachments/assets/8a76769f-3cf7-46db-a791-e2cb6cb157a5)

Hardware:

    ESP-32 DEV Module - 1
    MQ-6 Gas Sensor - 1
    Buzzer
    DC Servo Motor
    Jumper Wires

Software:

    Arduino IDE
    Outlook

Result Analysis:

![Gas Alert Message Via mail](https://github.com/user-attachments/assets/81416da2-6734-4b9b-917c-15ce897804e9)


The system successfully detects gas leakages and triggers:
    Audible alerts using the buzzer.
    Automatic shutdown of gas regulators via the servo motor.
    Email notifications through SMTP for remote alerting of relevant personnel.

Conclusion

In recent years, there has been a significant transition in households and industries towards using LPG and natural gas, which poses security challenges. This IoT-based gas detection system addresses these challenges by leveraging advanced MQ6 sensor technology integrated with an ESP32 microcontroller. It not only detects gas leaks promptly but also prevents potential accidents, mitigates environmental pollution, and enhances safety measures across various sectors. The incorporation of email alerts and audible alarms ensures timely warnings to nearby individuals, enabling swift response to mitigate risks to human life and property
