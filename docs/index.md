# ADCS Documentation

The basic goal of any ADCS system is to take in sensor data, do some math on that data to figure out your position, and then use the knowledge of position to control the satellite.
``` mermaid
flowchart TD
    A[Sensors]
    B[Math]
    C[Attitude]
    D[Control]

    A --> B
    B --> C
    C --> D
```
## Software Overview

[Magnetic Field Model](magnetic_field_model.md)

## Hardware Overview
