![Project Screenshot](Roofclosingckt.jpeg)

Introduction:
The Automatic Roof Closing System utilizes a Light Dependent Resistor (LDR) to detect changes in light intensity. When the LDR senses a significant decrease in light intensity, indicating the presence of rain or excessive sunlight, it triggers the system to close the roof automatically.

Components required:
LDR
Diode IN4007
Opamp LM741
Resistor
Motor 
Relay 6V
Transistor

Circuit Analysis:
• LDR Resistance at normal room light = 9.5kΩ 
• LDR Resistance at full dark = 19.5kΩ 
• LDR Resistance at smart phone flash light = 0.3kΩ ( Distance between the Light sensor and flash light is in between 1cm-3cm ) 
• Op amp output in smart phone flash light = 0.09v 
• Op amp output in dark = 0.78v 
• Op-amp and transistor output in smart phone flash light = 0v 
• Op-amp and transistor output in dark = 4.07v 
• NOT Gate and transistor output in smart phone flash light = 3.98v 
• NOT Gate and transistor output in dark = 0v



