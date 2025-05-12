# Power Electronics Project

## Author
Phạm Lê Ngọc Sơn

## Project Overview
This project focuses on power electronics simulation using MATLAB/Simulink. It includes models for:
- Three-phase PWM inverter systems
- Phase-Locked Loop (PLL) implementation

## Project Structure
- `Inverter_Trifase_PWM.slx`: Main three-phase PWM inverter Simulink model
- `Inverter_Trifase_PWM_23.slx`: Alternative version of the three-phase PWM inverter model
- `pll.slx`: Phase-Locked Loop implementation model
- `data.m`: Parameter initialization script containing system configuration values
- `data.asv`: Autosave file for the parameter script
- `slprj/`: Folder containing Simulink cache files

## Parameter Configuration
The `data.m` file contains essential parameters for the simulation:
- Input voltage (Vd)
- Load resistance (Rc)
- Load inductance (Lc)
- Cycle time (Tc)
- Time constant (tau)

## How to Use
1. Open MATLAB and navigate to the project directory
2. Run the `data.m` file to initialize simulation parameters
3. Open the desired Simulink model (`.slx` file)
4. Run the simulation using Simulink controls
5. Analyze the results through Simulink scopes and displays

## Requirements
- MATLAB R2020a or later
- Simulink
- Power Electronics Toolbox
- Control System Toolbox

## Notes
The project includes multiple models for three-phase PWM inverters with different implementations and configurations. The PLL model demonstrates techniques for grid synchronization in power electronic systems.