# An Inexpensive 'Homemade' O2/CO2 Regulating Incubator for Mammalian Cell Culture 
> Our incubator is an inexpensive, portable and user friendly device that is capable of regulating O2, CO2 and temperature within physiological ranges. Using an Arduino-based approach to control O2 and CO2 headspace levels via N2 and CO2 gas injection, we were able to convert a temperature-regulating Styrofoam egg incubator into a efficient benchtop cell culture tool comparable to commercial laboratory O2/CO2 incubators. This incubator can be assembled for less than $1000 (CAD), making it highly accessable for biologists seeking to transition towards physiological cell culture practices.

## Table of Contents
* [General Info](#general-information)
* [Project Road Map](#project-road-map)
* [Technologies Used](#technologies-used)
* [Design](#design)
* [Setup](#setup)
* [Usage](#usage)
* [Points to Keep in Mind](#points-to-keep-in-mind)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
- Culturing cells under physiologically-relevant conditions is vital to maintaining cellular phenotypes representative of in vivo biology. While O2 constitutes ~20% of the atmosphere, it's level ranges from 2 to 6% in most mammalian tissues, thus O2/CO2 incubators capable of establishing such conditions are necessary. Unfortuanately, commercial O2/CO2 incubators suitable for mammalian cell culture cost well over CAD $10,000, making them inaccessible to many cell biologists. 
- The "Homemade" O2/CO2 incubator described here works to address this obstacle by providing cell culturists with the means to self assemble an effective O2/CO2 incubator from a standard temperature-regulating Styrofoam egg incubator.  
- The Stuart lab is a large proponent of the importance of physiological conditions in cell culture, thus by making tools to maintain physiological oxygen levels more readily available, we hope to encourage the field to incorporate such practices into standard workflow. 

## Project Road Map 

- :book: [**The Publication**](Coming Soon) - This incubator was published in an international, peer-reviewed, open-access journal called Oxygen. All original designs and assembly details can be found in this manuscript + the supplementary data sections. 
- :computer: [**Arduino Code**](https://github.com/StuartLab/Incubators/blob/main/Arduino%20code) 
- 🛒 [**Materials List**] (Coming Soon)
- ❓ [**Issue Forum**](https://github.com/StuartLab/Incubators/issues) - Submit questions, concerns and assembly requests here!

## Technologies Used
- 


## Design

>Initial Prototype![Picture2](https://user-images.githubusercontent.com/101297687/157755455-99c0945f-f7a3-4207-9f8b-286c8c1c9ab0.png)


>Final Model: gas sensors, arduino controller, soleniod valves and electronics enclosed within a 3D-printed box![Picture3](https://user-images.githubusercontent.com/101297687/157756712-0d27962c-4e54-4745-aece-bd7f54f9b88b.png)

## Setup
-


## Usage
- This benchtop incubator is primarily intended for academic research labs looking to incorporate physioxic cell culture conditions. The interior of the incubator is suitable for both adherent and suspension cell culture, comfortably accomodating at least 25 100mm stacked tissue culture disks and/or flasks. 
- Specific setpoint gas levels (O2 and CO2) can be altered to suit the conditions required by the user. The code is currently set to maintain a physioxic level of 5% O2, and standard 5% CO2. 

## Points to Keep in Mind
- Depending on the application, the Uno and solenoid valves can be powered in one of two ways. For applications where the system is only run for short periods of time, both the Uno and solenoids can be powered with a single 12VDC power supply. However, if the application requires the Uno to be constantly powered, as in the incubator application developed here, the Uno should be powered with a lower voltage (9VDC), while the solenoid valves are powered independently with a 12VDC power supply.
- Heatsinks may be required for various components including the transistors, though we did not find them necessary under our conditions. Monitoring the temperature of electrical components is critical in the early stages of development to determine the need for heatsinks.


## Contact
Created by [@StuartLab](https://github.com/StuartLab) -- Feel free to contact us with questions or concerns about incubator assembly!
