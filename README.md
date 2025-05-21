Smart Curtain System - Procedure
 1. Introduction:
 The Smart Curtain System is an automated curtain control system that opens and closes curtains
 based on various inputs such as sunlight, temperature, time of day, or manual override using a
 mobile app or voice assistant.
 2. Components Required:- Microcontroller (e.g., Arduino or ESP32)- Light sensor (LDR)- Temperature sensor (optional)- Motor (servo or stepper motor)- Motor driver module- Wi-Fi module (if not inbuilt)- Power supply- Mobile App or Voice Assistant integration
 3. Circuit Setup:- Connect LDR to analog pin to detect light intensity.- Connect the motor to the motor driver and then to the microcontroller.- Connect temperature sensor to a suitable pin (if used).- Establish Wi-Fi connection for remote control.
 4. Programming the Microcontroller:- Write code to read sensor values.- Implement logic to open/close curtains based on thresholds.
- Include manual override options through app or voice assistant.- Upload code to microcontroller.
 5. Mobile App Integration:- Use platforms like Blynk or custom app for control.- Link app buttons to microcontroller via Wi-Fi.
 6. Voice Control (Optional):- Integrate with Google Assistant or Alexa using IFTTT and webhooks.
 7. Testing:- Test curtain operation in various light and temperature conditions.- Ensure motor moves curtains smoothly without obstruction.
 8. Final Setup:- Mount the system on the curtain rod.- Ensure proper alignment of the motor and curtain mechanism.- Secure all components and hide wiring for a neat look.
 9. Maintenance:- Periodically check sensor accuracy.- Lubricate moving parts if needed.- Ensure Wi-Fi connection is stable for remote operation
