# Simple-Refrigerator-Door-Open-Alarm-Circuit
Simple Refrigerator Door Open Alarm Circuit
This presented refrigerator door open alarm circuit which alerts you after a period of time whenever your refrigerator door is left open.

This circuit becomes very handy, because in case the door is left due to carelessness may cause significant increase in the consumption and affect the life of the fridge.
<img width="1090" height="701" alt="image" src="https://github.com/user-attachments/assets/ff21d9c0-b200-41d1-aa9d-4ec44c0e7223" />
<img width="699" height="524" alt="image" src="https://github.com/user-attachments/assets/db172fee-3503-42bc-9c05-a65e746e710b" />
This circuit uses a photosensor LDR for detecting whether the door is open, or not. Whenever the sensor is illuminated by the light coming out from inside of the refrigerator, the circuit begins emitting an intermittent sound to alert you and bring the situation to your attention.

And as soon as the door is closed, and the fridge light goes off, the circuit and the alarm shuts off and stops emitting the sound.

When the LDR is not introduced to light the voltage on pin 2 (trigger) of the first IC 555 stays higher and its output (pin 3) is rendered low. Due to this the second IC 555 is rendered inhibited (low voltage level on pin 4) and the alarm is not allowed to activate.

When the LDR experiences an illumination (door is opened), the voltage level on pin 2 of the first 555 gets low causing the output (pin 3) to oscillate (square wave).

During the oscillation when output of the first 555 is at high level enables the second 555 to get triggered which also begins oscillating in tune with the first but at a much higher frequency.

A buzzer which may be seen connected with the output of IC2 now begins buzzing and alarming.

The circuit makes use of a PP3 9 volt battery, and should be placed as close as possible to the inner light of the refrigerator.
