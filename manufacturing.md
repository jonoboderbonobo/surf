# Prototyping
## Tiny Tapeout
"Tiny Tapeout is an educational project that aims to make it easier and cheaper than ever to get your digital designs manufactured on a real chip." [[99]](#99) <br>
You can use [Skywater130 PDK](https://skywater-pdk.readthedocs.io/en/main/) and soon [IHPs](https://www.ihp-microelectronics.com/de) SG13G2 derived [BiCMOS 130nm PDK](https://github.com/IHP-GmbH/IHP-Open-PDK-docs). <br>
Usage of those two PDKs is free of charge and required no NDA. Prototyping with Tiny Tapeout can also be significantly cheaper than conventional [Multi Project Wafer (MPW)](https://en.wikipedia.org/wiki/Multi-project_wafer_service) prototyping, depending on your requirements. You can compare [Europractice MPW Pricing](https://europractice-ic.com/schedules-prices-2025/) with [TinyTapeout Pricing](https://app.tinytapeout.com/calculator?tiles=1&pcbs=1).

### Limitations of Tiny Tapeout for Microrobotics
Tiny Tapeout is a "Multi Project Die" (made up name) Fabrication Process rather than a "Multi Project Wafer (MPW)" Fabrication Process.
Therefore its not easy to remove the section of the Die that holds the robot, because the Chip is already Packaged rather then the raw Die (Chip without Package). Additionally there is only ONE Robot on the complete chip, meaning there is no room for failure regarding seperation of the robot from the rest of the Die. That means regarding Microrobotics Tiny Tapeout is mainly recommended for testing circuits rather than testing Displacement, Gait or Swarm Behavior. 
## Multi-Project-Wafer (MPW)

### Manufacturing Prototype - Tiny Tapeout


# References
<a id="99">[99]</a> <br>
https://tinytapeout.com
