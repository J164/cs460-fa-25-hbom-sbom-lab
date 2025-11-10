| Component | Manufacturer | Part Number | Known Risks |
|---|---:|:---:|---|
| Optical Motion Tracking Chip | PixArt Imaging Inc. | PMW3901MB-TXQT | Bright lights or reflections can interfere with the accuracy of the sensor. |
| Barometric Pressure Sensor | BOSCH | BMP280(0x76)@300-1100hPa | Changes in temperature, humidity, and weather can influence the pressure measurements and make altitude measurements inaccurate. |
| Inertial Measurement Unit | BOSCH | BMI270 | POver time, small errors in measurements can compound to a much larger error. |

# Hardware effect on Software Risk

Hardware dependencies increase software supply‑chain risk because compromised components can introduce unexpected behavior that results in software components that interact with them taking unexpected code paths. The creator of a software component may not test the behavior of their software when a hardware device behaves incorrectly and so malicious hardware could exploit undiscovered vulnerability in device software.