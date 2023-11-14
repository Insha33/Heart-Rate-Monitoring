# Heart-Rate-Monitoring

Aim of this project is to make a wearable device, using Pulse Sensor and Arduino UNO to collect heart rate of the user. The real time data gathered would then be passed through a ML model i.e. Logistic Regression, which will predict whether the patient is in a state of having a stroke or not. The data gathered and the outcome is then encrypted using AES-256 and send via MQTT to the mobile application used by the user and the doctors. The application can be used to analyze the BPM overtime and consult the patient accordingly by the doctor. If the prediction by model suggests that the user will get a heart stroke, the doctor is immediately notified. 
