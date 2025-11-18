# arduino-sensor
uses ultrasonic waves to detect if someone has passed

how does it work?
it uses the ultrasonic sensor to detect how long it takes for the wave to return
it then uses the formula (time taken x speed of light) / 2 to get distance
if then checks if the distance decreases (if something is in the way)
if this happens, the LED starts blinking
