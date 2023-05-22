# Real time digital modelling using robotic glove
The model on-screen can be manipulated using the robotic glove. The digital hand mimics the movement of the robotic glove. Speed of movement and angle of rotation of the digital hand is controlled using accelorometer and gyroscope values respectively. To reduce noise and to filter out good values for movement of the digital hand, a complementary filter is used.

- **Formula used by the complementary filter:**\
$angle = (1 - α) * (angle + gyroscope * dt) + α * accelerometer$

- **Microcontroller used:** Arduino Uno

- **Communication protocol:** Wired or HC-05 Bluetooth serial module

- **3D Modelling software:** Blender

- **Sensors on the robotic glove:**
  * MPU6050 (consists of accelerometer and gyroscope)
  * Flex sensors (variable resistors that change resistance based on the bend of the sensor)

## Result:

<img src="https://github.com/Ank-G/Real-time-digital-modelling-using-robotic-glove/blob/main/Result.gif" width=40% height=20%>
