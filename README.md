# Mobile sensors based platform for COVID-19 contact tracing leveraging artificial intelligence

[Research paper published with this repository is available online](https://link.springer.com/article/10.1007/s12652-023-04713-7)


# Machine learning-based (LSTM) approach for virus/disease spread control using mobile sensor data

This is the approach for COVID-19 spread control but can be used for any virus or disease that spreads from person to person.
The COVID-19 pandemic is an active epidemic disease and is evolving into various variants of SAR-COV-2. The most critical point for COVID-19 is to break the transmission chain by early detection and isolation. It necessitates monitoring human interactions using remote technologies as a proactive strategy to minimize the spread. This paper presents a framework for user behavior recognition and localization in a heterogeneous environment leveraging artificial intelligence for COVID-19 contact tracing. This approach designed and developed a mobile application to acquire the mobile sensors (received signal strength indicator (RSSI), accelerometer, gyroscope, and speed), sensors response, and machine learning-based user behavior classification to assess the spread of COVID-19 with better proximity detection. This paper presents a machine learning-based free-space path loss (FSPL) model to estimate the distance between users holding mobile devices. The framework considers comprehensive user interaction scenarios depending upon multiple parameters, including the randomness of a user's interaction (device-device communication), device position, environmental obstacles, and device type. This platform classifies user behavior on a train, bus, walking, and sitting at one, two, and three-meter from the suspected patient. The proposed system outperforms existing models, estimates the distance up to three meters, and accurately classifies each user's behavior. This system can send alert notifications to all users within three meters of a person whose COVID-19 test is positive. This approach uses machine learning models and finds that the random forest classifier shows a higher accuracy of 97.95% for user behavior classification and uses the LSTM model for distance estimation from one to three meters between users with the highest accuracy of 98.07%.


# Architecture Diagram

<img src="https://github.com/user-attachments/assets/1afcc426-ddef-4d6e-8faf-7dff235b7f7c" alt="MobileSensorPlatform" style="width: 650px;"/>



# RSSI Distribution for 1, 2, and 3 Indoor sitting

<img src="https://github.com/user-attachments/assets/286dae62-3e6f-443b-8c8c-4efad12d40a1" alt="RSSIDistribution" style="width: 650px;"/>

We have done different experiments and can be found all of them in the research paper.

# Confusion Matrix (Decision Tree Regression)

<img src="https://github.com/user-attachments/assets/99b6b380-6148-47bc-96a4-bf1eaadc0258" alt="Results" style="width: 650px;"/>


The results for all the user distance classifications for other models can be found in the research paper

&#8594;   https://link.springer.com/article/10.1007/s12652-023-04713-7

# Mobile App in Flutter
The mobile app with complete code for this research study can be found here

&#8594;   https://github.com/jamshid-bacha/Social-BLE-Distancing-App-English-Korean-Version.git




