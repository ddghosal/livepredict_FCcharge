
![AWAKE_Logo50](https://github.com/user-attachments/assets/cd483d39-5d4a-498c-abf0-cc4b3e47240f)

# Live-prediction of FC charge

This is an attempted approach to predict charge count in Faraday Cup by extrapolating the data of the BTV (intensity) and scintillator screen (hits).

# Context
A Faraday cup (FC) is a device used to measure the number of charged particles (e.g. ions, electrons etc.) in a beam by collecting them, which creates a current that can be measured to determine the number of particles hitting the cup.

AWAKE (https://home.cern/science/accelerators/awake) is the world’s first proton-driven plasma wakefield acceleration experiment. It is an accelerator R&D project based at CERN, that investigates the use of plasma wakefields driven by a proton bunch to accelerate charged particles.

In run-2b of AWAKE, while the charge count was read at the FC, for certain time window and runs, it was not registered. So, the idea was to get an estimate how the charge would be if it was ON from the data we already had on other devices.
The intnsity profile on the BTV screen and the hits on a Scintillator screen were used to train a basic ML model while the FC was ON; followed by the similar data of the BTV and Scintillator data (when the FC was OFF) was used to predict the charge count on the FC, if the reading was registered from it.

## Built with
![387](https://github.com/user-attachments/assets/b6a93c80-9097-485f-a05b-bf21054ed0a8)

## Prerequisite
It is better if you have access to GPU or a HPC machine, in order to test your prediction.

## Author
Debdeep Ghosal [you can find me here](https://www.linkedin.com/in/debdeep-ghosal-46aa314a/)

