# One_Wire_Interfaces

This repository defines a package gathering software elements allowing to manage the 1-Wire
communication protocol.

The package is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model) and implemented
according to [these C language
patterns](https://github.com/HomeMadeBots/C-language-patterns-for-Embedded-Software-Meta-Model).

## Content

The Physical_Quantities_Interfaces package gathers :
* Data_Types :
  * T_One_Wire_Device_Address
* Interfaces :
  * One_Wire_Protocol
  
## Overview

![Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/One_Wire_Interfaces/master/doc/overview.puml)

## Dependencies

None.

## Use

### With the Arduino IDE

This repository shall be clone within the _libraries_ folder of the _Arduino sketchbook folder_.
