# ORP Model

## Project Overview
This project focuses on model a critical output control variable of a process: the oxidation-reduction potential (ORP) of the conversion reaction from iodate to iodine. Currently, an ORP sensor is in place; however, this measurement is taken at the end of the conversion process, with a residence time of approximately 15 minutes from the addition of the other process reagents. For this reason, the ORP will be modeled to predict its behavior at the same timestamp as the upstream variables. This will serve as an indicator to anticipate potential deviations


## Objectives
- Develop a Predictive Model for ORP: Create a regression model capable of predicting the oxidation-reduction potential (ORP) at the same timestamp as the upstream variables, enabling 
  real-time insights..
- Integrate the Model into the Control System: Ensure the trained model can be seamlessly incorporated into the plant's control system as a reference for operational adjustments.

## Tools and Technologies
- **Programming Language**: Python
- **Library**: pandas, missingno, numpy, scipy, pycaret, matplotlib, pickle and warnings
- **Data Sources**: Data from the control system (plc)

## Repository Structure
- `data/`: Contains raw data.
- `notebooks/`: Includes the Jupyter notebook with the main analysis.
- `README.md`: This file, describing the project.
