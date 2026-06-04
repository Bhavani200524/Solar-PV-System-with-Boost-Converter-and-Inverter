# Solar-PV-System-with-Boost-Converter-and-Inverter
This project presents the design and simulation of a Solar Photovoltaic (PV) Power Generation System using MATLAB Simulink. The system consists of a PV array, DC-DC Boost Converter, PWM-controlled Inverter, LC Filter, and RLC Load. The generated DC power from the solar panel is boosted and converted into AC power suitable for electrical loads.

# Features:
Solar PV Array Modeling
DC-DC Boost Converter
PWM-Based IGBT Switching
DC Link Capacitor
Universal Bridge Inverter
LC Output Filter
Voltage Measurement and Monitoring
MATLAB Simulink Implementation

# System Architecture: 
Solar Irradiance & Temperature
            │
            ▼
        PV Array
            │
            ▼
    DC-DC Boost Converter
            │
            ▼
      DC Link Capacitor
            │
            ▼
     PWM Inverter
            │
            ▼
        LC Filter
            │
            ▼
        AC Load
        
# Components Used:

Component	Function
PV Array	Generates DC power from solar energy
Boost Converter	Increases DC voltage
IGBT Switch	Controls converter operation
Diode	Allows one-way current flow
DC Capacitor	Reduces voltage ripple
PWM Generator	Generates switching signals
Universal Bridge	Converts DC to AC
LC Filter	Removes harmonics
RLC Load	Consumes output power
Powergui	Simulink power electronics support
Simulation Parameters
Parameter	Value
Irradiance	1500 W/m²
Temperature	25°C
Converter Type	Boost Converter
Inverter Type	PWM-Based Universal Bridge

# Results:

Successful DC power generation from PV Array.
Voltage boosting using DC-DC converter.
Conversion of DC voltage into AC voltage.
Harmonic reduction through LC filter.
Stable AC output supplied to the load.

# Applications:
Solar Home Systems
Renewable Energy Systems
Microgrid Applications
Solar Power Research
Smart Grid Technologies

# Software Used:
MATLAB
Simulink
Simscape Electrical
