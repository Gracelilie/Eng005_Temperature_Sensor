# ECE Lab #2: Using Temperature Sensors  
**Grace-lilie Acheampong**  
**Fall 2024**

## Project Overview:
This project aims to measure the internal and external temperatures of a microcontroller, both before and after adding a resistor. The experiment focuses on analyzing how electrical parameters (voltage, current, and resistance) influence the temperature measurements and how to use these values for sensor calibration.

### Objectives:
- Measure the internal and external temperatures of the microcontroller.
- Analyze the impact of adding a resistor to the circuit.
- Calculate resistance and use it for temperature sensor calibration.

### Circuit Setup:
- **Power Source:** 3.3V (live wire), GND (neutral wire).
- **Connection to Microcontroller:** P(1.3).
- **Components:** Microcontroller, temperature sensor, resistor, and digital multimeter (DMM).

### Measurement Procedures:
1. **Voltage:**  
   - Measure voltage across the sensor (VT) and the resistor (VR).
   - The sum of these voltages should approach 3.3V.
   - Use a DMM connected in parallel to the outer legs of the transistor in series with the resistor.
   
2. **Current:**  
   - As the circuit is in series, measure the total current (I) by switching the red cable of the DMM to the current port.
   
3. **Resistance:**  
   - Calculate the resistance using Ohm’s Law:  
     \[ R = \frac{V}{I} \]

### Results:
- **Voltage Drop:** 1.311V.
- **Current:** 39.87 µA.
- **Resistance:** 50.088 kΩ.
- **Internal Temperature Sensor Reading:** 27°C.
- **External Temperature Sensor Reading:** 44°C.

### Calibration Formula:
The calibration formula used for temperature correction is:  
\[ T_x = T_2 + \frac{(T_1 - T_2) \cdot (R_x - R_2)}{R_1 - R_2} \]  
Where \( T_x \) is the temperature at a given resistance \( R_x \).

### Safety Rules:
1. Avoid standing on stools, pointing sharp tools, or dropping metal objects onto powered circuits.
2. Ensure stability when testing race cars or similar systems.
3. Wear safety gear (glasses, gloves) when handling high-voltage circuits or soldering.
4. Secure all cables to avoid tripping hazards.
5. Power off circuits before disconnecting components.
6. Ensure correct polarity when connecting power sources: red for positive, black for GND.
