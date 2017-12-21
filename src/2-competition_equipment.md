# II. Competition Equipment

## 1. Car Models

### (1) Types of Car Models

The competition allows 4 standard car models to be used in the 6 Racing categories and 2 Creative categories. The 4 car models includes 2 quad-wheel models and 2 duo-wheel vertical models.

| Number | Specifications                  | Categories                               | Supplier        |
| ------ | ------------------------------- | ---------------------------------------- | --------------- |
| B      | Motor: 540 Servo: S-D5          | Quad-Wheel Photoelectric                 | 北京科宇通博科技有限公司    |
| C      | Motor: RN-380 Servo: FUTABA3010 | Duo-Wheel Crossover (only allows C model) | 东莞市博思电子数码科技有限公司 |
| D      | Motor: RS-380                   | Duo-Wheel Vertical                       | 东莞市博思电子数码科技有限公司 |
| E      | Motor: RS-380                   | Duo-Wheel Vertical                       | 北京科宇通博科技有限公司    |
| F      | Motor: RS-380                   | Tri-Wheel Electromagnetic                | 东莞市博思电子数码科技有限公司 |

*Clarification 1:* 东莞市博思公司 has made improvements to the C and D models. The 13th Competition Duo-Wheel Crossover category only allows the use of the new C model. The old C model may only be used in the Power-Saving, Beacon Duel and Creative categories. Whereas both the new and old D models may be used simultaneously.

*Clarification 2:* 北京科宇通博科技有限公司 has made improvements in the B model. The 13th Competition allows the use of both versions.

### (2) Car Model Modification Rules

The 5 different car models provide a unified platform for the competition, and modifying the car models must follow strict rules. Please refer to Appendix 1: Car Model Modification Rules for details.

## 2. Electronic Components

### (1) Microcontrollers

-   You must use a 8-bit, 16-bit or 32-bit series microcontroller produced by NXP as the **only** programmable controlling unit on the car model.
-   Within the Tri-Wheel Electromagnetic, Duo-Wheel Vertical and Wireless Power-Saving categories, you must **only** use the KEA MCU series by NXP, there is otherwise no limitations on MCU for other categories. If a Wireless Power-Saving team is to use a camera sensor for track detection, they may use other MCUs other-than the KEA series by NXP.
-   There is no limitations on the number of microcontroller used.
-   If sensors and other electronic components chosen also include microcontrollers, then there is no limitations on the type or the number used of said microcontrollers, however, they may not participate in the recognition and processing of the information of the track, and they may not participate in the movement decision-making and controlling of the cars.

### (2) Sensors

-   The types of sensors used must follow the regulations of the different competing categories. Please consult "Competition Missions", for details on the allowed types of sensors for different competing categories.
-   There must not be more than 16 sensors. The calculation of the sensors is as follows:
    -   Photoelectric receiver unit counts as 1 sensor. The emitter unit for the receiver is not counted.
    -   CCD sensor counts as 1 sensor.
    -   Magnetic field sensors at the same place for different directions count as 1 sensor. Sensors and coils at different places are counted separately.
    -   Permanent magnetic Reed switches or Hall sensors for the use of detecting the starting line, with no regards on the actual used number, count as 1 sensor in total.
    -   Sensors for detecting the speed and posture of the car are also counted.
-   Limitations on Sensor Models
    -   If you are to use an accelerometer independently, then you must use one produced by NXP.
    -   If you are to use a gyroscope, then there is no limitations on the sensor model.
    -   If you are use use a combined accelerometer and gyroscope sensor, then there is no limitations on the sensor model.

### (3) Servo Motors

-   **Definition:**
    The "servo motors" on the car means motors other than the original motors that drives the wheels. They include: steering motors, stepper motors and other kinds of motors.
-   **Limitations on the Number Used:**
    The number of servo motors must not exceed 3, which includes steering motors. The steering motors must be that provided into original car kit and you must only use 1 of that.
-   **Limitations on Function**
    The servo on the car may only be used to control the position on the sensors on board, or to control the posture of the chassis. It is not permitted to directly or indirectly use the servo to control the turning of the car or the control the speed of the wheels.

## 3. Electronic Board

Besides the minimum system board for the microcontrollers, ICs for accelerometers and gyroscopes, camera and the board within the steering motors, all circuitries are required to be designed in-house, and it is prohibited to purchase functional modules. Purchased minimum system boards must only contain: a microcontroller, clock, and power and microcontroller debugging ports. In-house produced PCB boards includes but not limited to: sensors, signal conditioning circuits, power management circuit, motor drivers, master control circuits, debugging circuits, et cetera. If in-house produced circuitries includes factory processed printed PCB boards, it is a requirement that the copper layer must include the competing team's school name, team name and competing year at a noticeable area. For really small boards, it is allowed to use acronyms of names which has to be easy to spot when examining the car models. (If the circuit board is smaller then 1 cm squared, then the board is not required to carry team information.)

To implement self-aided competition, it may be required that the board should carry a QR code specified when applying for the competition. For this, more details will be released in relevant documentations.