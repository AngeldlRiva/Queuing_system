# Queuing_system
1.- System_reliability.R

This program simulates the reliability of a two-component system, tracking failures and repairs. Each component has a time-to-failure generated by a Weibull distribution and a repair time generated by a uniform distribution. The simulation runs until a maximum time, updating the system state and accumulating downtime. The output allows for calculating system availability.

2.- Tax_agency.R

This program simulates the spanish tax agency, a two-stage queuing system, modeling customer arrivals, their passage through two sequential service stages, and their exit from the system. It uses random distributions for inter-arrival times and service durations, calculating the accumulated waiting time at each stage. The simulation runs until a defined maximum time, displaying arrival and service completion events.

3.- Airport_simulation.R and montecarlo.R

Airport Simulation Program

This program simulates the operations of an airport, focusing on various service counters such as:

-Check-in

-Passport control

-Security checks

-Boarding

The simulation uses variables to define the number of counters available for each service. The optimal number of counters for each service has been determined using the Monte Carlo method, which is detailed in a separate file included in this repository.

This project can be used to analyze bottlenecks, optimize service capacity, or study passenger behavior under different conditions.

*This project was made alongside threeother students*
