# IoT-based-WaterFlowRate-measurement-using-Arduino

![circuit diagram](https://user-images.githubusercontent.com/84971685/235324429-601cfb88-b5f1-4773-843e-cff1bbd16cc6.png)

The water flow rate and volume using an Arduino and a Flow Sensor. In this circuit, the water flow sensor is linked to an Arduino and an LCD, which is programmed to display the volume of water that has passed through the valve. The water flow sensor used in this circuit is an S201, which uses a hall effect to sense the flow rate of the liquid.
The working of the YFS201 water flow sensor is simple to understand. The water flow sensor works on the principle of hall effect. Hall effect is the production of the potential difference across an electric conductor when a magnetic field is applied in the direction perpendicular to that of the flow of current. The water flow sensor is integrated with a magnetic hall effect sensor, which generates an electric pulse with every revolution. Its design is in such a way that the hall effect sensor is sealed off from the water, and allows the sensor to stay safe and dry. 


In this circuit, the water flow sensor is connected to a pipe; if the pipe’s output valve is closed, no water is sensed by the flow sensor, and thus no pulses are generated. There will be no interrupt signal on Arduino pin 2 and the flow frequency count will be zero. When the pipe’s output valve is opened, water flows through the sensor, rotating the wheel inside the sensor. There will now be pulses, and the Arduino will send an interrupt signal, and the count of the flow frequency will be increased by one for each interrupt signal. In this way we can measure the water flow rate and volume using an Arduino.

Uses and Application:
Automatic water dispensers,
Soft drink industries,
Chemical industries,
Smart irrigation systems.
