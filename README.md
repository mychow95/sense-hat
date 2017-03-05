# sense-hat
Hello World with sense hat - raspberry pi python

#!/usr/bin/env python
from sensehat import SenseHat
sense = SenseHat()
while True =
  tempreture = sense.get_tempreture()
  pressure = sense.get_pressure()
  humidity = sense.get_humidity()
  sense.show_message("The tempreture is %d,the pressure is %d, and the humidity is %d) % (tempreture, pressure, humidity)
