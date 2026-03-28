# household-energy-consumption-calculator-in-C-
C++ OOP project for managing households, electrical devices, solar production, and annual energy cost calculation


Overview

This project is an object-oriented C++ application for calculating the annual electricity consumption and power costs of a house with multiple households.

The program allows the user to:

create a house with multiple households
add different types of devices
calculate annual electricity consumption
calculate annual electricity costs
model solar energy production
save and load data from files


Features:

House and household management
Support for multiple device types
Calculation of annual power consumption
Calculation of annual energy costs
File input/output support
Copying devices between households
Reordering devices inside a household
OOP Concepts Used



This project demonstrates several object-oriented programming concepts:

Inheritance
Consumer and Producer inherit from Device
Immobile, Mobile, and Solar extend the class hierarchy further

Polymorphism
Virtual functions such as annual_kWh(), print(), get_a_copy(), and get_string_for_file() are overridden in derived classes

Abstraction
Device acts as an abstract base class with pure virtual methods

Encapsulation
Class attributes are stored privately and accessed through getters/setters

Dynamic Memory Management
Devices and households are created dynamically and deleted in destructors


Class Structure
Device: abstract base class for all devices
Consumer: abstract class for energy-consuming devices
Producer: abstract class for energy-producing devices
Immobile: fixed devices with active and standby consumption
Mobile: movable devices based on distance usage
Solar: solar producer with annual power generation
Household: stores household data and devices
House: manages multiple households
Address: stores address information


Example Functionalities
Add an immobile consumer such as a TV or refrigerator
Add a mobile consumer with km-based consumption
Add a solar producer
Print one household or all households
Save house data to a file
Load house data from a file  


##########################
Possible Improvements
Replace raw pointers with smart pointers
Split the project into multiple header and source files
Improve input validation
Add exception handling
Add unit tests
Improve the file format design
Fix object counter decrement logic in destructors
Author

Abdullah Ismaiel

Notes

This project was developed as a university OOP/C++ project and demonstrates practical use of inheritance, polymorphism, and file handling in C++.
