Relays:

Electromagnetic switches.
Off -> NC
On -> NO

Poles -> number of circuits controlled by switch
Throw -> number of circuits in ON position

p - pole t -throw s -single d-double

types:
spst dpst spdt dpdt

Zener diode:
like diode but also switch in both biases

Voltage Regulator IC:
7905 IC maintains output at -5V
7805 IC maintians output at 5V

Rectifier:
AC to only positive cycle conversion. Either half or full wave.

Smoothening:
Steady DC from rectified AC using a capacitor(filter).

Filtering:
Specific range of frequencies only are allowed to pass
Bandwidth -> fmax - fmin. Freq above fmax and below fmin are not allowed to pass

Amplitude of signal strength = 20log(Vout/Vin) in terms of dB

Types:

High pass filter:
Voltage taken across resistor
Vout/Vin = wRC/(wRC - j)
Magnitude = (wRC)/(1 + (wRC)^2)^2

So if w -> 0, amplitude -> 0
   if w -> inf, amplitude -> 1

Low pass filter:
Voltage taken across capacitor
Vout/Vin = 1 - (wRC)/(wRC - j)

So if w -> 0, amplitude -> 1
   if w -> inf, amplitude -> 0

Band pass filter:
Sending a high pass filter output to a low pass filter as input to get the final output.

MOSFET:
Metal oxide semiconductor field effect transistors.
Voltage controlled current source.
Can be used as switch or amplifier.

Pull up Resistor:
input pin reads high when button not pressed

Pull down Resistor:
input pin reads low when button not pressed

These resistors stop "floating" signals (neither high nor low)

H-Bridge:
Voltage can be applied in multiple ways across a single load.

Motor Driver IC:
interface between microcontroller and motors.
microcontrollers work in 5V but DC motor takes 9-12V so has to be amplified

L293D Motor Driver:
Vcc1/Power 1 is to power the circuit
Vcc2/Power 2 is to power the motors

Pulse width modulation:
Duty cycle = Ton/(Ton + Toff)
speed is controlled by PWM signal


Motors:-

Brushed DC:
electric brush to provide physics contact to complete the circuit
magnet is stator

Brushless DC:
electronic controlled to change the magnetic field around the shaft at a high frequency
magnet is rotor
