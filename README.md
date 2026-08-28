# Hospital Inventory System Simulation

A discrete-event simulation project developed as part of the Systems Modeling and Simulation course at the Faculty of Computers and Artificial Intelligence, Cairo University.

## Course Information

- **University:** Cairo University
- **Faculty:** Faculty of Computers and Artificial Intelligence
- **Department:** Operations Research and Decision Support
- **Course:** Systems Modeling and Simulation
- **Course Code:** DS331 / DS241
- **Instructor:** Assoc. Prof. Ayman Ghoneim
- **Academic Year:** 2024

## Project Overview

This project simulates a two-level hospital inventory system consisting of:

- First-floor inventory
- Basement inventory
- Patient rooms
- Daily medical supply demand
- Inventory replenishment
- Random lead times

The simulation uses the **Discrete Event Simulation** approach to analyze inventory performance and investigate the effect of different inventory policies on stock levels and shortages.

## Problem Objectives

The simulation aims to:

1. Calculate the average ending inventory for the first-floor and basement inventories.
2. Determine the number of days in which shortages occur.
3. Compare theoretical and experimental average demand.
4. Compare theoretical and experimental average lead time.
5. Investigate the effect of changing the review period `N`.
6. Investigate the effect of changing the maximum basement capacity `M`.

## Methodology

The model uses probability distributions to generate:

- Daily demand based on the number of occupied patient rooms.
- Random lead times for basement replenishment.

The simulation tracks inventory levels, demand, replenishment orders, lead times, and shortage occurrences over multiple days.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Discrete Event Simulation
- Statistical Analysis
- Data Visualization

## Results

The simulation was evaluated using different simulation durations and multiple runs to compare theoretical distributions with experimental results and analyze inventory performance.

Key performance measures include:

- Average ending first-floor inventory
- Average ending basement inventory
- Number of shortage days
- Experimental average demand
- Experimental average lead time
- Inventory behavior under different values of `N` and `M`

## My Contribution

Implemented **Problem II – Hospital Inventory System** in Python, including the simulation model, inventory and replenishment logic, statistical analysis, and data visualization.

## Project Files

- `Hospital_Inventory_Simulation.ipynb` — Python simulation notebook.
- `report/Problem_II_Hospital_Inventory_Report.pdf` — Project report and analysis.

## Academic Context

This project was completed as part of the **Systems Modeling and Simulation (DS331/DS241)** course at Cairo University.
