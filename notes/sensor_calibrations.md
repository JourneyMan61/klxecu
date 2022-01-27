# Sensor Calibrations


### Throttle Position Sensor
- Input voltage spec: 5V
- Output at closed throttle: 0.58-0.62 V
- Output at WOT: 3.7-3.9V

### Crankshaft Position Sensor
- Type: Variable Reluctance
- Trigger pattern: 18-1*
- Trigger angle: ?
- Voltage peak: 3.2V

### MAP Sensor
- Pressure at 0V: ?
- Pressure at 5V: ?
- Sensor spec is 2.87-2.93V at 101.35 kPa, will need to calibrate

### O2 Sensor
- Type: Narrowband
- Rich: 0.8V and up
- Lean: 0.24V and below

### Coolant Temperature Sensor
- -20c: 18.80k +/- 2.37k
- 0c: 6.544k
- 40c: 1.136k +/- 0.095k
- 100c: 0.1553k +/- 0.0070k
- Bias resistor: TBD
- Spec voltage: 2.8-2.97V at 20c (probably won't apply for us because the bias reistor is different)

### Intake air temperature sensor
- 0c: 6k +/- 0.6k
- 80c: 0.34k +/- 0.05k
- Spec voltage at 20c is 2.375 +/- 0.125V, which works out to a theoretical resistance of 2.5k. Will need to experimentally test though.

### Subthrottle Position sensor
- Input voltage spec: 5V
- Output at closed throttle: 0.48-0.52V
- Output at WOT: 3.60-3.80V

### Speed Sensor
- Type: Hall effect
- Spec: 0-5v output
- 8 pulses per rotation

### Kickstand
- Up: Logic low (ground)
- Down: Logic high (pullup to 5V?)**

### Neutral switch
- Neutral: low
- In gear: hign (pullup to 5V?)**

### Clutch Switch
- Pulled in: low
- let out: high (pulled up? who knows. let's see)