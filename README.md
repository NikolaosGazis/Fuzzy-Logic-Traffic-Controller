# Fuzzy logic based traffic light management.
## Overview

This Python is a model of an ideal traffic light management system mimicked in four-way intersection that uses fuzzy logic. The idea is to calculate the time taken before each conference light depending on vehicles expected at different lanes. Reality is brought by allowing users to issue arrival rates for each intersection.
Features

Fuzzy Logic Controller: The scikit-fuzzy library is used to implement a fuzzy logic controller in which the value of green duration on every traffic light l, N= H(L) is determined by the queue that any driver waiting for at L.

User-Defined Arrival Rates: Users can provide mean arrival rate of cars at any traffic light, which further improves the realism. The program checks the range of inputs as they must lie in requirements.

Traffic Light Pairs: A pair system is implemented to simulate the alternative switching characteristic of traffic lights at intersection. The application alternate pairs of red and green lights, enabling one pair to show up in the colorful way while another remains painted.

Simulation Visualizations: The program gives visual representations of green light time distributions among multiple simulations using histograms.

## Usage

Checkout the repository to your local machine.
Make sure to have the necessary libraries installed when using (numpy, scikit-fuzzy and matplotlib).
Run the traffic_light_simulation.py script.
Use prompts to supply arrival rates for each traffic light.
Note the simulation outputs particularly green light duration and also, pattern of distribution over several simulations.

## Dependencies

numpy: For numerical operations.

matplotlib: For data visualization.

### License

The MIT License applies to this project.
