# PLC Code Description

Our PLC program continuously monitors inputs from the **IFM J2100 Inclination Sensor** and **IFM TA2115 Temperature Sensor** to ensure warehouse safety and environmental control.

## Key Functions

- **Real-time Tilt Monitoring:**  
  Reads the forklift or structure’s tilt angle. If the tilt exceeds safe limits, it immediately triggers an alert (e.g., buzzer or indicator) to prevent tipping accidents.

- **Temperature Control:**  
  Continuously measures ambient temperature. When temperature crosses predefined thresholds, the PLC activates the cooling system to maintain optimal storage conditions.

- **Safety Alerts:**  
  Alerts remain active until sensor values return to safe ranges, ensuring continuous protection.

## Outcome

This PLC logic enables real-time, automated safety management, reducing risks of equipment accidents and protecting stored goods through environmental control.

