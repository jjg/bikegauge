# bikegauge

An analog/mechanical gauge-based bike computer that is easy to understand and read under any bicycle conditions.

The device consists of circular gauge with a single needle driven by a stepper motor.  The needle can sweep through 360 degrees and indicates against a gauge engraved with a scale of 0-10.

## Mark I Modes

* Speed
* Distance
* Heading
* Nav

### Speed

Speed is displayed as expected by sweeping the needle across the face of the gauge. The device can be configured to indicate MPH or KPH.  If a larger range is required, the firmware can be configured to indicate multiples of the indicated speed.

### Distance

Distance travelled is indicated on the gauge as 0-10 miles/kilometers.  When 10 unites are exceeded, the gauge resets and 


## Mark I Parts List

* [Adafruit Feather M0 Adalogger](https://www.adafruit.com/product/2796)
* [Adafruit Ultimate GPS featherwing](https://learn.adafruit.com/adafruit-ultimate-gps-featherwing/circuitpython-library)
* [Adafruit DC Motor + Stepper Featherwing](https://www.adafruit.com/product/2927)
* [Lithium Ion battery](https://www.adafruit.com/product/1578)
* Stepper motor compatible with stepper motor featherwing
* 3D printed and lasercut custom parts


