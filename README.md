# Capstone 2026 Template UoA
This document serves as the official framework for the Capstone Project GitHub template repository at the University of Auckland. 

**Kindly replace your project README file with this document.**

This repository is based on an ESP32 C programming project. It is structured according to the following directory organization:

## ADC:
This folder contains the project’s ADC-related source and header files. It includes the necessary .c and .h files required to implement and manage ADC functionality.

## Docs:
All project documentation should be stored in this folder. This includes reports, design documents, references, and any other relevant written materials.

## Server:
In this project, the ESP32 board operates as a client that transmits data to a server. The server-side application responsible for receiving and processing this data is maintained in this folder.

## WiFi:
This folder contains all Wi-Fi–related files, including configuration files, source files, and header files required for network connectivity and communication.

## build:
Following compilation, various generated files—such as compiled objects, downloaded dependencies, required headers, and driver files—are produced. These files should be stored in this folder.

## main:
To maintain a clear and well-organized project structure, this folder contains only two essential files. The first is main.c, which serves as the entry point of the program. The second is CMakeLists.txt, which specifies the main source file and defines the required libraries and build configurations for the project.
