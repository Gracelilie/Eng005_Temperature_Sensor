# ECE Lab #2: Using Temperature Sensors  
**Grace-lilie Acheampong**  
**Fall 2024**
**Date Written:** 9/23/2024  
**Date Updated:** 9/25/2024

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
   - As the circuit is in series, measure the total current (I) by connecting both the red and black wires in series.
   - Also, the red cable of the DMM is moved to the current port.
   
3. **Resistance:**  
   - Calculate the resistance using Ohm’s Law:  
     R= V/I

### Results:
- **Voltage Drop:** 1.311V.
- **Current:** 39.87 µA.
- **Resistance:** 50.088 kΩ.
- **Internal Temperature Sensor Reading:** 27°C.
- **External Temperature Sensor Reading:** 44°C.

