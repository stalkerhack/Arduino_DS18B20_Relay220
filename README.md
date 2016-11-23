# Automatic heating system barrier with ds18b20 and arduino


The task was to make the automatic inclusion of the heating system at a certain temperature (-10 degrees Celsius).
I could use the arduino NANO controller, sensor ds18b20 in insulated body and the relay module (220V).
So, i would like to post the code that you can see how can i realised this project.

Components Used:
  -Arduino Nano x1
  -Temperature sensor ds18b20
  -Relay module 220v x1
  -Light-emitting diodes x4:
    1)First green diode indicates that arduino was started.
    2)Second green indicates that module relay workig normally
    3)Third red indicates that power 220v on relay turned on (only if the temperature dropped to -10 degrees Celsius).
    4)Fourth blue diode indicates that the temperature dropped to -10 and that arduino may turn on the relay.
  -Stabilizator L7805CV for power supply arduino and other components (sensor and relay).
  -Resistors:
    1)4.7 kOm x1 (for sensor)
    2)150-250 Om x4 (for light-emitting diodes)
