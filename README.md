# Fuzzy Logic Based Traffic Light Management.
## Overview

This Python program is a model of an simplistic attempt to simulate traffic light management system mimicked in four-way intersection that uses fuzzy logic. 
The idea is to calculate the time taken before each conference light depending on vehicles expected at different lanes. Reality is brought by allowing users to issue arrival rates for each intersection.

## Features

**Fuzzy Logic Controller**: The scikit-fuzzy library is used to implement a fuzzy logic controller in which the value of green duration on every traffic light l, N= H(L) is determined by the queue that any driver waiting for at Light.

**User-Defined Arrival Rates**: Users can provide mean arrival rate of cars at any traffic light, which further improves the realism. The program checks the range of inputs as they must lie in requirements.

**Traffic Light Pairs**: A pair system is implemented to simulate the alternative switching characteristic of traffic lights at intersection. The application alternate pairs of red and green lights, enabling one pair to show up in the colorful way while another remains painted.

**Simulation Visualizations**: The program gives visual representations of green light time distributions among multiple simulations using histograms.

## Logic Applied
The simulation follows the logic a pair of two traffic lights can be green at the same tim while the other pair is red, the pairs are based on the mirrored geographical (west-east/north-south) location.

## Usage

Clone the repository.
Make sure to have the necessary libraries installed when using (numpy, scikit-fuzzy and matplotlib).
Run the **traffic_light_simulation.py** script.
Use prompts to supply arrival rates for each traffic light.
Note the simulation outputs particularly green light duration and also, pattern of distribution over several simulations.

## Dependencies

• numpy: For numerical operations.
• scikit-fuzzy: For fuzzy logic operations.
• matplotlib: For data visualization.

### License
This project is free under the [MIT Licence](https://github.com/NikolaosGazis/Fuzzy-Logic-Traffic-Controller/tree/main?tab=MIT-1-ov-file).
