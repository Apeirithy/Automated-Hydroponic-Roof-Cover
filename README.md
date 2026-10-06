# Automated Hydroponic Roof Cover (Rain Protection System)
An automated hardware system designed to shield hydroponic plants from rain, preventing nutrient leaching and overwatering. This project is a purely hardware-driven embedded system (no microcontrollers) that relies on analog circuit logic, sensors, and custom mechanical design.

## Project Demonstration
* **Live Demo Video:** https://youtu.be/wRM6VF9FyS4
* **Documentation & Building Process:** https://youtu.be/xM9J6tyTu58

## Hardware & Circuit Logic
The system's automation is driven entirely by analog components:
* **Rain Sensor & Op-Amp Comparator:** Detects rainwater and uses an Operational Amplifier as a comparator to output a high/low signal based on the sensor's moisture level.
* **DPDT Relay:** Reverses the polarity of the DC Gearbox Motors to roll the tarp open or closed depending on the weather conditions.
* **Limit Switches:** Acts as an endpoint detection mechanism to automatically cut off the motor current when the roof is fully opened or fully closed, preventing mechanical overextension.

## Mechanical Design & 3D Printing
The physical structure was custom-designed to integrate seamlessly with the electrical components:
* **Belt and Pulley System:** Translates the motor's rotational motion into linear motion to pull the sliding bar and unroll the tarp.
* **Rapid Prototyping:** Key mechanical components and mountings were 3D modeled and 3D printed for precise dimensional accuracy.
* **Custom Guide Pipe:** Designed and implemented a guide pipe above the roller to solve real-world mechanical misalignment issues, ensuring the tarp unrolls perfectly without folding backward.

## Project Documents
All comprehensive academic reports, including problem identification, progress reports, and final evaluations, can be found in the [Reports folder](./Reports).
