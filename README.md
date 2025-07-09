# RC-Plane-Flight-Computer
I am making an RC Plane, and I want to test the RC Plane for multiple different characteristics, by designing and iterating on new wing designs. For this testing, I want to keep it as numerical and factual as possible, meaning I needed a quanitative way to measure and verify my findings. 
Some of the experiments I will be conducting on my RC Plane are the following: Stall tests (Figuring out how much the Plane can fly vertically up before falling down), STOL Tests (How fast and how short distances the plane needs to take off/land), Flight Endurance tests (Find how long the plane can last until 15% battery), Manueverability tests (Finding out how fast the plane can react to my controls, and how fast it can spin and roll).
In order to gain this data, I will be needing a Flight Computer for my plane, to determine the velocity, acceleration, position, and angle. To determine all of this information, I will need the following capabbilities on the PCB: 1) GPS, 2) IMU, 3) Antenna, 4) MCU. Since GPS and Antenna will be integrated together I will not need to worry about this. 

![image](https://github.com/user-attachments/assets/116bf8ab-4a91-4b29-ba7d-38d6b522504f)

![image](https://github.com/user-attachments/assets/beb2a4b1-f7a2-4149-babd-dfa2cf016b17)

![image](https://github.com/user-attachments/assets/06fc6e53-5af7-4822-bdb8-8c1503d68fe5)

![image](https://github.com/user-attachments/assets/cbea76ec-8aa4-436b-93b6-02a3d2c9394f)

## Bill of Materials

| **Item**         | **Cost (USD)** | **Description**                                      | **Quantity** | **Link** |
|------------------|----------------|------------------------------------------------------|--------------|---------|
| Push Rods        | 10             | For servo to move the wing ailerons                 | 1            | [Steel Music Wire (4-count)](https://www.familyhardware.com/product/k-s-032-in-x-36-in-steel-music-wire-4-count-/277975) |
| 9g Servos        | 15             | To actuate the wing ailerons                        | 1            | [SG90 Micro Servo 9G Kit - 8 Pcs](https://www.amazon.com/AYWHP-Helicopter-Drones-Robotics-Control/dp/B0DRHXGY4X) |
| Battery          | 22             | To power the plane                                  | 1            | [OVONIC 3S 11.1V 1000mAh LiPo Battery](https://www.amazon.com/1000mAh-Airplane-Quadcopter-Helicopter-Multi-Motor/dp/B07TJW4SY9) |
| Soldering Iron   | 33             | To solder the PCB to the GPS module                 | 1            | [100W Soldering Station Kit](https://www.amazon.com/Soldering-Station-Digital-Display-Helping/dp/B0DJR79P3J) |
| GPS Module       | 11             | To track location and velocity for my experiment    | 1            | [GY-NEO6MV2 GPS Module - 2PCS](https://www.amazon.com/AITRIP-GY-NEO6MV2-Controller-Ceramic-Antenna/dp/B0CWL774NR) |
| PCB              | 95             | Custom flight computer PCB                          | 1            | *(Custom Part)* |

**Total Cost:** **$186**
