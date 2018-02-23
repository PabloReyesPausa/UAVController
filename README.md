# UAVController
Android application for drone control based on the MAVLINK protocol via Raspberry Pi





The upper section contains the following buttons:
  1. RTL button, responsible for sending the flight order Return To Home.
  2. LOITER button, responsible for establishing the flight mode in Loiter.
  3. STABILIZE button, responsible for establishing the flight mode in Stabilize.
  4. DISARM button, this is responsible for deactivating the motors.
  
Also included in the central part are two TextView that are responsible for displaying the SSID of the
WiFi connected and the signal quality of this.
The lower section contains the main controls; it's a button called Arm Motors and
two joystick. The button is responsible for turning on the motors, so, if you do not press this
button the aircraft does not respond to any order. The joysticks are responsible for directing
aircraft.
