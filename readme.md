**Weatherstation basic**
simple weatherstation using:
1. arduino
2. DS3231 (rtc - clock)
3. DTH11  (weather sensor)

this project reads time & weather and then prints it on the serial monitor

**connections:**
(*listed for aduino pro micro*)
|DS3231|arduino|
|--|--|
|vcc|vcc|
|gnd|gnd|
|sda|2|
|scl|3|

|dth11|arduino|
|--|--|
|vcc|vcc|
|data|9|
|-|-|
|gnd|gnd|

**Picture of output:**

![picture](/pic.png)