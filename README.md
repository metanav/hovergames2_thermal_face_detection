# NXPHoverGames: Face Thermal Measurement

In this project, I built an application which can be used to measure the temperature of a human face from thermal camera readings and can accurately measure person temperature by extrapolating the facial skin temperature. This application has many use-cases for example, it can be used to search and rescue a person in dark or low light condition where generic digital camera may not work. It can be used as a contactless temperature monitoring. This application also serve as a demo for use of Tensorflow Lite on RDDRONE-8MMNavQ "NavQ" Linux companion computer platform based on NXP i.MX 8M Mini SOC.
Please see the complete project story at https://www.hackster.io/naveenbskumar/nxphovergames-face-thermal-measurement-69d0ed

Note: The BlazeFace TensorFlow Lite model used in the application was downloaded from https://github.com/google/mediapipe

## Thermal Camera Setup
The MLX90640 thermal camera is connected to the NavQ using a 9-pin JST-GH cable. 


## Run application
```
git clone https://github.com/metanav/hovergames2_thermal_face_detection.git
cd hovergames2_thermal_face_detection.git
sudo python3 main.py
```

