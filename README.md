# Vehicle-to-Vehicle (V2V) Energy Transfer

## Project Overview

This project presents a MATLAB/Simulink-based Vehicle-to-Vehicle (V2V) energy transfer system for electric vehicles.

The system enables energy to be transferred from one electric vehicle to another through a controlled bidirectional power transfer system. This concept can help balance energy between EVs when one vehicle has a higher state of charge (SOC) and another vehicle requires additional energy.

## Objectives

- Develop a V2V energy transfer model using MATLAB/Simulink.
- Study bidirectional power flow between two electric vehicles.
- Transfer energy from a source EV to a receiving EV.
- Analyze battery State of Charge (SOC) during energy transfer.
- Study the power and voltage characteristics of the system.
- Demonstrate the potential of EVs as distributed energy resources.

## V2V Energy Transfer Concept

The system consists of two electric vehicles:

- **EV1:** Source vehicle that supplies electrical energy.
- **EV2:** Receiving vehicle that receives electrical energy.

When EV1 has sufficient battery SOC and EV2 requires additional energy, power can be transferred from EV1 to EV2 through the power conversion system.

### Basic Power Flow

EV1 Battery
↓
Bidirectional Power Converter
↓
EV2 Battery

The direction of power flow can be controlled according to the charging and discharging requirements of the vehicles.

## Battery System

Each electric vehicle is represented by a battery system with parameters such as:

- Battery voltage
- Battery capacity
- State of Charge (SOC)
- Charging/discharging power

The battery SOC is monitored to evaluate the performance of the V2V energy transfer process.

## Bidirectional Power Flow

A bidirectional power conversion system is used to control the transfer of energy between the two EV batteries.

During energy transfer:

**EV1 → EV2**

EV1 operates as the source vehicle while EV2 operates as the receiving vehicle.

The power flow and battery conditions can be monitored throughout the simulation.

## Software Used

- MATLAB
- Simulink
- Simscape Electrical

## How to Run

1. Install MATLAB with the required Simulink/Simscape Electrical components.
2. Download or clone this repository.
3. Open MATLAB.
4. Set the project folder as the MATLAB current folder.
5. Open `V2V_Model.slx`.
6. Run the Simulink simulation.
7. Observe battery voltage, power flow and SOC results.

## Simulation Results

The simulation results can be used to analyze:

- EV1 battery SOC
- EV2 battery SOC
- Battery voltage
- Charging/discharging power
- Direction of power flow
- Energy transferred between the vehicles

Simulation screenshots and results are provided in the `Results` folder.

## Applications

V2V energy transfer can have potential applications in:

- Emergency EV charging
- EV energy sharing
- Fleet energy management
- Distributed energy systems
- Smart transportation systems
- Renewable-energy-integrated EV systems

## Future Improvements

- Develop an intelligent energy management system.
- Implement SOC-based automatic power transfer.
- Add renewable energy sources.
- Implement Vehicle-to-Grid (V2G) operation.
- Add multiple-EV energy sharing.
- Optimize power transfer efficiency.
- Implement real-time hardware control.
