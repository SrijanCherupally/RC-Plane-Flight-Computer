# RC-Plane-Flight-Computer
I am making an RC Plane, and I want to test the RC Plane for multiple different characteristics, by designing and iterating on new wing designs. For this testing, I want to keep it as numerical and factual as possible, meaning I needed a quanitative way to measure and verify my findings. 
Some of the experiments I will be conducting on my RC Plane are the following: Stall tests (Figuring out how much the Plane can fly vertically up before falling down), STOL Tests (How fast and how short distances the plane needs to take off/land), Flight Endurance tests (Find how long the plane can last until 15% battery), Manueverability tests (Finding out how fast the plane can react to my controls, and how fast it can spin and roll).
In order to gain this data, I will be needing a Flight Computer for my plane, to determine the velocity, acceleration, position, and angle. To determine all of this information, I will need the following capabbilities on the PCB: 1) GPS, 2) IMU, 3) Antenna, 4) MCU. Since GPS and Antenna will be integrated together I will not need to worry about this. 

![image](https://github.com/user-attachments/assets/116bf8ab-4a91-4b29-ba7d-38d6b522504f)

![image](https://github.com/user-attachments/assets/beb2a4b1-f7a2-4149-babd-dfa2cf016b17)

![image](https://github.com/user-attachments/assets/06fc6e53-5af7-4822-bdb8-8c1503d68fe5)

![image](https://github.com/user-attachments/assets/cbea76ec-8aa4-436b-93b6-02a3d2c9394f)

## Bill of Materials

| **Item**                 | **Cost (USD)** | **Description**                                                | **Quantity** | **Link**                                                                                                                                                                                                 |
|--------------------------|----------------|----------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Push Rods                | 10             | For Servo to make the Wing Ailerons move                       | 1            | [Steel Music Wire (4-count)](https://www.amazon.com/dp/B0006O8Q7Y)                                                                                                  |
| CA Glue + Accelerator    | 28             | To glue wing together                                          | 1            | [Magic Chems CA Glue with Activator](https://www.amazon.com/dp/B09V77GH24)                                                                                         |
| 9g Servos                | 15             | To actuate the wing ailerons                                   | 1            | [SG90 Micro Servo 9G Kit - 8 Pcs](https://www.amazon.com/dp/B07R29RRTS)                                                                                            |
| Battery                  | 22             | To power the plane                                             | 1            | [OVONIC 3S 11.1V 1000mAh LiPo Battery](https://www.amazon.com/dp/B08L8QFGDR)                                                                                       |
| Propeller 10x4.7, 8x4    | 30             | To move the plane                                              | 1            | [uxcell RC Propellers CW CCW 8045 8x4.5](https://www.amazon.com/dp/B08XQHYZQK)                                                                                      |
| LW-PLA                   | 50             | To print out the wings                                         | 1            | [LW-PLA Yellow – Lightweight Foaming PLA](https://colorfabb.com/lw-pla-yellow)                                                                                      |
| Soldering Iron           | 33             | To solder the PCB to the GPS Module                            | 1            | [100W Soldering Station Kit](https://www.amazon.com/dp/B08NDQGJMC)                                                                                                  |
| GPS Module               | 11             | To track location and velocity for my experiment               | 1            | [GY-NEO6MV2 GPS Module - 2PCS](https://www.amazon.com/dp/B07GBZ4Q68)                                                                                                |
| PCB                     | 95             | To track location and velocity for my experiment               | 1            | *(Custom, link not provided)*                                                                                                                                       |

**Total Cost:** **$294**
