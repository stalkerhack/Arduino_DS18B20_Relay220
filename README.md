# Automatic heating system barrier with ds18b20 and arduino


The task was to make the automatic inclusion of the heating system at a certain temperature (-10 degrees Celsius).<br>
I could use the arduino NANO controller, sensor ds18b20 in insulated body and the relay module (220V).<br>
So, i would like to post the code that you can see how can i realised this project.<br>
<br>
<br>
Components Used: <br>
  1)Arduino Nano x1<br>
  2)Temperature sensor ds18b20<br>
  3)Relay module 220v x1<br>
  4)Light-emitting diodes x4:<br>
    4.1)First green diode indicates that arduino was started.<br>
    4.2)Second green indicates that module relay workig normally<br>
    4.3)Third red indicates that power 220v on relay turned on (only if the temperature dropped to -10 degrees Celsius).<br>
    4.4)Fourth blue diode indicates that the temperature dropped to -10 and that arduino may turn on the relay.<br>
  5)Stabilizator L7805CV for power supply arduino and other components (sensor and relay).<br>
  6)Resistors:<br>
    6.1)4.7 kOm x1 (for sensor)<br>
    6.2)150-250 Om x4 (for light-emitting diodes)<br>
