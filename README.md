# Freezing-of-esp32-at-powerup

When powering up the esp32 or esp8266 sometimes it does not start and is frozen. <br />

At first i was puzzled. resetting  via the rest button and  it was back ok. I digged somewhat deeper  because i noticed it was recurring many times and each time at powerup .<br />

It appears and proven by the great youtuber andreas spiess, when power is supplied and it is somewhat slow the esp starts with unsufficient power and freezes.<br />
Using a kda75330  (3.3v voltage level guard)connected to enable esp32 prevents the freezing, and hardware wise resets it for you.<br />

Links:<br />

#315 How to use Voltage Supervisors to protect ESP32, Raspberry Pi, and Batteries<br />

https://www.youtube.com/watch?v=cKDv0aN67BY<br />



or #436 How to use Voltage Supervisors to protect ESP32, Raspberry Pi, and Batteries" (or the earlier version, "#315").<br />



I hope this info helps for the many esp32 fans. :) <br />
