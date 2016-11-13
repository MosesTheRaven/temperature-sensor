# Temperature-sensor
<br>
simple Arduino project using DHT 11 temperature and humidity sensor <br>

<h2>Write mode</h2>
In 1 second intervals the circuit makes a measurment and stores the data in the EEPROM <br>
<h2>Read mode</h2><br>
In 1 second intervals a value at the address in EEPROM is read and printed in Serial Monitor <br>
<h2>Circuit</h2><br>
DHT sensor is connected to pin 8 <br>
pins 0 and 1 MUSTN'T be used while printing in Serial Monitor<br>
